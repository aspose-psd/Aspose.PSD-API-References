---
title: Class WarpSettings
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpSettings class. Parameters of layer with warp
type: docs
weight: 3920
url: /net/aspose.psd.fileformats.psd.layers.warp/warpsettings/
---
{{< psd/tize >}}
## WarpSettings class

Parameters of layer with warp

```csharp
public class WarpSettings
```

## Constructors

| Name | Description |
| --- | --- |
| [WarpSettings](warpsettings/#constructor_1)(PlacedResource) | Initializes a new instance of the `WarpSettings` class. |
| [WarpSettings](warpsettings/#constructor)(OSTypeStructure[], Rectangle) | Initializes a new instance of the `WarpSettings` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/bounds/) { get; } | Gets or sets bounds of warp image |
| [MeshPoints](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/meshpoints/) { get; set; } | Photoshop mesh points |
| [ProcessingArea](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/processingarea/) { get; set; } | Gets or sets value of processing area size. Default value is 10. Range is [2;40] |
| [Rotate](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/rotate/) { get; set; } | Gets or sets rotate value |
| [Style](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/style/) { get; set; } | Gets or sets style of warp |
| [Value](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/value/) { get; set; } | Gets or sets value of warp |

## Examples

The following code demonstrates how to manipulate WarpSettings to do warp transformation on SmartObjectLayer and TexLayer.

```csharp
[C#]

string sourceFile = "smart_without_warp.psd";

var opt = new PsdLoadOptions()
{
    LoadEffectsResource = true,
    AllowWarpRepaint = true
};

string[] outputImageFile = new string[4];
string[] outputPsdFile = new string[4];

for (int caseIndex = 0; caseIndex < outputImageFile.Length; caseIndex++)
{
    outputImageFile[caseIndex] = "export_" + caseIndex + ".png";
    outputPsdFile[caseIndex] = "export_" + caseIndex + ".psd";

    using (PsdImage img = (PsdImage)Image.Load(sourceFile, opt))
    {
        foreach (Layer layer in img.Layers)
        {
            if (layer is SmartObjectLayer)
            {
                var smartLayer = (SmartObjectLayer)layer;
                smartLayer.WarpSettings = GetWarpSettingsByIndex(smartLayer.WarpSettings, caseIndex);
            }

            if (layer is TextLayer)
            {
                var textLayer = (TextLayer)layer;

                if (caseIndex != 3)
                {
                    textLayer.WarpSettings = GetWarpSettingsByIndex(textLayer.WarpSettings, caseIndex);
                }
            }
        }

        img.Save(outputPsdFile[caseIndex], new PsdOptions());
    }

    using (PsdImage img = (PsdImage)Image.Load(outputPsdFile[caseIndex], opt))
    {
        img.Save(outputImageFile[caseIndex],
            new PngOptions() { CompressionLevel = 9, ColorType = PngColorType.TruecolorWithAlpha });
    }
}

WarpSettings GetWarpSettingsByIndex(WarpSettings warpParams, int caseIndex)
{
    switch (caseIndex)
    {
        case 0:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 20;
            break;
        case 1:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Vertical;
            warpParams.Value = 10;
            break;
        case 2:
            warpParams.Style = WarpStyles.Flag;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 30;
            break;
        case 3:
            warpParams.Style = WarpStyles.Custom;
            warpParams.MeshPoints[2].Y += 70;
            break;
    }

    return warpParams;
}
```

### See Also

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


