---
title: PsdOptions.BackgroundContents
second_title: Aspose.PSD for .NET API Reference
description: PsdOptions property. Gets or sets the color of background. It can be seen under transparent objects
type: docs
weight: 20
url: /net/aspose.psd.imageoptions/psdoptions/backgroundcontents/
---
{{< psd/tize >}}
## PsdOptions.BackgroundContents property

Gets or sets the color of background. It can be seen under transparent objects.

```csharp
public RawColor BackgroundContents { get; set; }
```

## Examples

The following code demonstrates support of BackgroundContents property in PsdOptions.

```csharp
[C#]

// Semi transparency is processed wrong on the psd file preview.
// BackgroundContents assigned to White. Transparent areas should have white color.

string sourceFile = "frog_nosymb.psd";
string outputFile = "frog_nosymb_backgroundcontents_output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    RawColor backgroundColor = new RawColor(PixelDataFormat.Rgb32Bpp);
    int argbValue = 255 << 24 | 255 << 16 | 255 << 8 | 255;
    backgroundColor.SetAsInt(argbValue); // White

    PsdOptions psdOptions = new PsdOptions(psdImage)
    {
        ColorMode = ColorModes.Rgb,
        CompressionMethod = CompressionMethod.RLE,
        ChannelsCount = 4,
        BackgroundContents = backgroundColor,
    };

    psdImage.Save(outputFile, psdOptions);
}
```

### See Also

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


