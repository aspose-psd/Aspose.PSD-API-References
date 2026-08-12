---
title: "WarpSettings.RenderQuality"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad WarpSettings. Obtiene o establece el valor de la calidad de renderizado del warp entre velocidad y calidad"
type: docs
weight: 50
url: /es/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/
---
{{< psd/tize >}}
## WarpSettings.RenderQuality property

Obtiene o establece el valor de la calidad de renderizado warp - entre velocidad y calidad

```csharp
public RenderQuality RenderQuality { get; set; }
```

## Ejemplos

El siguiente código muestra la propiedad WarpSettings.RenderQuality para configurar la deformación del warp.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

RenderQuality[] qualityValues = { RenderQuality.Turbo, RenderQuality.Fast, RenderQuality.Normal, RenderQuality.Excellent };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Obtiene WarpSettings de Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Establece el tamaño del área de procesamiento del warp
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // No debería haber error aquí
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Ver también

* enum [RenderQuality](../../renderquality/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


