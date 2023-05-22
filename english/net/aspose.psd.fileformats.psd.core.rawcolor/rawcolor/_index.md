---
title: Class RawColor
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Core.RawColor.RawColor class. Raw Color Class helps to store colors with any channels count any color mode and any bit depth Please note some internal classes can have issues with converting RawColor to its native format so if API provides for you CMYK color its more reliable to use the provided format. Also there are can be some cases when Raw Color can be converted
type: docs
weight: 1640
url: /net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor class

Raw Color Class helps to store colors with any channels count, any color mode and any bit depth Please note, some internal classes can have issues with converting RawColor to its' native format, so if API provides for you CMYK color, it's more reliable to use the provided format. Also, there are can be some cases when Raw Color can be converted

```csharp
public sealed class RawColor
```

## Constructors

| Name | Description |
| --- | --- |
| [RawColor](rawcolor/#constructor)(ColorComponent[]) | Initializes a new instance of the `RawColor` class. |
| [RawColor](rawcolor/#constructor_1)(PixelDataFormat, short) | Initializes a new instance of the `RawColor` class from pixel data format using predefined color modes |

## Properties

| Name | Description |
| --- | --- |
| [ColorMode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/colormode/) { get; set; } | Mode for the color to follow. |
| [Components](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/components/) { get; } | Gets the components of color. Each component is separate channel, and if you use not popular color scheme, it's better to work with each channel separately. |

## Methods

| Name | Description |
| --- | --- |
| [GetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getasint/)() | Gets the color as int in case it's possible to get it. |
| [GetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getaslong/)() | Gets the color as long in case it's possible to get it. |
| [GetBitDepth](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getbitdepth/)() | Gets the bit depth of Raw Color. For example for ARGB color with 8 bits per channel/component is 32 Bit Depth of full ARGB color with 16 bits per channel/component is 64. Bit depth is accumulated from the sum of channels' bit depths. It's possible if different channels will have different bit depths. |
| [GetColorModeName](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getcolormodename/)() | Gets the name of the color mode. Color mode name accumulated from channels/components names |
| [SetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setasint/)(int) | Sets data to all channels from int argument if it's possible |
| [SetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setaslong/)(long) | Sets data to all channels from int argument if it's possible |

## Examples

The following code demonstrates the support of RawColor class instead of obsolete Color struct.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### See Also

* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../)


