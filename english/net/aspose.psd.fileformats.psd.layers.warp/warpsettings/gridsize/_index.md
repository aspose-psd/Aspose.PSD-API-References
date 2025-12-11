---
title: WarpSettings.GridSize
second_title: Aspose.PSD for .NET API Reference
description: WarpSettings property. Gets or sets the size of the warp grid. Default is 1
type: docs
weight: 30
url: /net/aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/
---
{{< psd/tize >}}
## WarpSettings.GridSize property

Gets or sets the size of the warp grid. Default is 1.

```csharp
public Size GridSize { get; set; }
```

## Examples

The following code demonstrates support of WarpSettings.GridSize property.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Get warp settings
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Set new size
    // For the Photoshop value can be between 1 and 50 and you can not save PSD file correctly.
    warpSettings.GridSize = new Size(100, 100);

    // Set valid value
    warpSettings.GridSize = new Size(3, 3);

    // Render example file with x3 grid
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### See Also

* struct [Size](../../../aspose.psd/size/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


