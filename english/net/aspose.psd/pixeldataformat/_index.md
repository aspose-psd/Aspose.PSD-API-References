---
title: Class PixelDataFormat
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.PixelDataFormat class. The pixel data format. This is an immutable object
type: docs
weight: 5510
url: /net/aspose.psd/pixeldataformat/
---
{{< psd/tize >}}
## PixelDataFormat class

The pixel data format. This is an immutable object.

```csharp
public class PixelDataFormat
```

## Properties

| Name | Description |
| --- | --- |
| static [Cmyk](../../aspose.psd/pixeldataformat/cmyk/) { get; } | Gets the `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black. |
| static [Cmyka](../../aspose.psd/pixeldataformat/cmyka/) { get; } | Gets the acmyk. |
| static [Grayscale](../../aspose.psd/pixeldataformat/grayscale/) { get; } | Gets the `PixelDataFormat` defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval. |
| static [GrayscaleAlpha](../../aspose.psd/pixeldataformat/grayscalealpha/) { get; } | Gets the `PixelDataFormat` defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component. |
| static [Rgb16Bpp555](../../aspose.psd/pixeldataformat/rgb16bpp555/) { get; } | Gets the `PixelDataFormat` defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined. |
| static [Rgb16Bpp565](../../aspose.psd/pixeldataformat/rgb16bpp565/) { get; } | Gets the `PixelDataFormat` defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined. |
| static [Rgb24Bpp](../../aspose.psd/pixeldataformat/rgb24bpp/) { get; } | Gets the `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined. |
| static [Rgb24BppPng](../../aspose.psd/pixeldataformat/rgb24bpppng/) { get; } | Gets the `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined. |
| static [Rgb32Bpp](../../aspose.psd/pixeldataformat/rgb32bpp/) { get; } | Gets the `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue. |
| static [Rgba32Bpp](../../aspose.psd/pixeldataformat/rgba32bpp/) { get; } | Gets the `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue. |
| static [Rgba64Bpp](../../aspose.psd/pixeldataformat/rgba64bpp/) { get; } | Gets the `PixelDataFormat` defined for 64 bits per pixel with 16 bits for each of the alpha, red, green and blue. |
| static [RgbIndexed1Bpp](../../aspose.psd/pixeldataformat/rgbindexed1bpp/) { get; } | Gets the `PixelDataFormat` defined for indexed 1 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model. |
| static [RgbIndexed2Bpp](../../aspose.psd/pixeldataformat/rgbindexed2bpp/) { get; } | Gets the `PixelDataFormat` defined for indexed 2 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model. |
| static [RgbIndexed4Bpp](../../aspose.psd/pixeldataformat/rgbindexed4bpp/) { get; } | Gets the `PixelDataFormat` defined for indexed 4 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model. |
| static [RgbIndexed8Bpp](../../aspose.psd/pixeldataformat/rgbindexed8bpp/) { get; } | Gets the `PixelDataFormat` defined for indexed 8 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model. |
| static [YCbCr](../../aspose.psd/pixeldataformat/ycbcr/) { get; } | Gets the `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components. |
| static [Ycck](../../aspose.psd/pixeldataformat/ycck/) { get; } | Gets the `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components. |
| [BitsPerPixel](../../aspose.psd/pixeldataformat/bitsperpixel/) { get; } | Gets the bits per pixel. |
| [Caption](../../aspose.psd/pixeldataformat/caption/) { get; } | Gets the pixel data format caption. |
| [ChannelBits](../../aspose.psd/pixeldataformat/channelbits/) { get; } | Gets the bits count for each channel. |
| [ChannelsCount](../../aspose.psd/pixeldataformat/channelscount/) { get; } | Gets the channels count. |
| [PixelFormat](../../aspose.psd/pixeldataformat/pixelformat/) { get; } | Gets the pixel format. |

## Methods

| Name | Description |
| --- | --- |
| static [GetBgr](../../aspose.psd/pixeldataformat/getbgr/)(int) | Gets BGR color with a specified number of bits per sample. |
| static [GetBgra](../../aspose.psd/pixeldataformat/getbgra/)(int) | Gets BGRA color with a specified number of bits per sample. |
| static [GetCieLab](../../aspose.psd/pixeldataformat/getcielab/)(int, int, int) | Gets CIE Lab color with a specified number of bits per sample. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk)(int) | Gets CMYK color with a specified number of bits per sample. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk_1)(int, int, int, int) | Gets CMYK color with a specified number of bits per sample. |
| static [GetCmyka](../../aspose.psd/pixeldataformat/getcmyka/)(int, int, int, int, int) | Gets CMYKA color with a specified number of bits per sample. |
| static [GetGrayscale](../../aspose.psd/pixeldataformat/getgrayscale/)(int) | Gets Grayscale color with a specified number of bits per sample. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha)(int) | Gets GrayscaleAlpha color with a specified number of bits per sample. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha_1)(int, int) | Gets GrayscaleAlpha color with a specified number of bits per sample. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb)(int) | Gets RGB color with a specified number of bits per sample. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb_1)(int, int, int) | Gets RGB color with a specified number of bits per sample. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba)(int) | Gets RGBA color with a specified number of bits per sample. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba_1)(int, int, int, int) | Gets RGBA color with a specified number of bits per sample. |
| static [GetRgbIndexed](../../aspose.psd/pixeldataformat/getrgbindexed/)(int) | Gets BGRA indexed color with a specified number of bits per sample. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr)(int) | Gets YCbCr color with a specified number of bits per sample. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr_1)(int, int, int) | Gets YCbCr color with a specified number of bits per sample. |
| static [GetYcck](../../aspose.psd/pixeldataformat/getycck/)(int) | Gets YCCK color with a specified number of bits per sample. |
| override [Equals](../../aspose.psd/pixeldataformat/equals/)(object) | Determines whether the specified Object is equal to this instance. |
| override [GetHashCode](../../aspose.psd/pixeldataformat/gethashcode/)() | Returns a hash code for this instance. |
| override [ToString](../../aspose.psd/pixeldataformat/tostring/)() | Returns a String that represents this instance. |
| [operator ==](../../aspose.psd/pixeldataformat/op_equality/) | Returns result of equality for two `PixelDataFormat` classes. |
| [operator !=](../../aspose.psd/pixeldataformat/op_inequality/) | Returns result of non-equality for two `PixelDataFormat` classes. |

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


