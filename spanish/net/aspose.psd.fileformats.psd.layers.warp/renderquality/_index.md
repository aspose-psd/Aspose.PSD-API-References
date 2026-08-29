---
title: "Enumeración RenderQuality"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.RenderQuality enum. Describe la calidad de renderizado del Warp"
type: docs
weight: 3990
url: /es/net/aspose.psd.fileformats.psd.layers.warp/renderquality/
---
{{< psd/tize >}}
## RenderQuality enumeration

Describe la calidad de renderizado de Warp.

```csharp
public enum RenderQuality
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Turbo | `4` | La opción más rápida, pero la calidad sufre. |
| VeryFast | `18` | Si lo necesitas rápido, puede ser adecuado para curvaturas pequeñas. |
| Fast | `35` | Permite que el renderizado sea más rápido con una pequeña pérdida de calidad. |
| Normal | `60` | Valor recomendado para la mayoría de las curvaturas |
| Good | `130` | Mayor que la calidad estándar, velocidad más lenta. Recomendado para distorsiones fuertes. |
| Excellent | `260` | La opción más lenta. Recomendado para distorsiones fuertes y altas resoluciones. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


