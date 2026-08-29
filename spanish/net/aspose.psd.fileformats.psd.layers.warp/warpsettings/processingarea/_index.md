---
title: "WarpSettings.ProcessingArea"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad WarpSettings. Obtiene o establece el valor del tamaño del área de procesamiento. El valor predeterminado es 10. El rango es 240."
type: docs
weight: 40
url: /es/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/processingarea/
---
{{< psd/tize >}}
## WarpSettings.ProcessingArea property

Obtiene o establece el valor del tamaño del área de procesamiento. El valor predeterminado es 10. El rango es [2;40]

```csharp
public int ProcessingArea { get; set; }
```

## Ejemplos

El siguiente código demuestra la propiedad WarpSettings.ProcessingArea para configurar la deformación de la distorsión.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

int[] areaValues = { 5, 10, 25, 40 };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Obtiene WarpSettings de Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Establece el tamaño del área de procesamiento del warp
        warpSettings.ProcessingArea = areaValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + areaValues[i] + ".png";
        outputFiles.Add(outputFile);

        // No debería haber error aquí
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Ver también

* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


