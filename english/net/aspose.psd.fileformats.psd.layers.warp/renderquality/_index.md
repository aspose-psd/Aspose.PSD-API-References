---
title: Enum RenderQuality
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.Warp.RenderQuality enum. It describes the rendering quality of Warp
type: docs
weight: 3950
url: /net/aspose.psd.fileformats.psd.layers.warp/renderquality/
---
{{< psd/tize >}}
## RenderQuality enumeration

It describes the rendering quality of Warp.

```csharp
public enum RenderQuality
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Turbo | `4` | The fastest option, but the quality suffers. |
| VeryFast | `18` | If you need it fast, it may be suitable for small curvatures. |
| Fast | `35` | Allows you to make rendering faster with a small drop in quality. |
| Normal | `60` | Recommended value for most curvatures |
| Good | `130` | Higher than standard quality, slower speed. Recommended for strong distortions. |
| Excellent | `260` | The slowest option. Recommended for strong distortions and high resolutions. |

## Examples

The following code demonstrates WarpSettings.RenderQuality property to configure warp deformation.

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
        // It gets WarpSettings from Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // It sets size of warp processing area
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // There should no error here
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### See Also

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


