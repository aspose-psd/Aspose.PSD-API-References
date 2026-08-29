---
title: "类 PixelDataFormat"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.PixelDataFormat 类。像素数据格式。这是一个不可变对象。"
type: docs
weight: 5720
url: /zh/net/aspose.psd/pixeldataformat/
---
{{< psd/tize >}}
## PixelDataFormat class

像素数据格式。这是一个不可变对象。

```csharp
public class PixelDataFormat
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Cmyk](../../aspose.psd/pixeldataformat/cmyk/) { get; } | 获取为每像素 32 位定义的 `PixelDataFormat`，其中青、品红、黄和黑各占 8 位。 |
| static [Cmyka](../../aspose.psd/pixeldataformat/cmyka/) { get; } | 获取 acmyk。 |
| static [Grayscale](../../aspose.psd/pixeldataformat/grayscale/) { get; } | 获取为每像素 8 位定义的 `PixelDataFormat`，其中 8 位表示 0-255 区间的灰度强度。 |
| static [GrayscaleAlpha](../../aspose.psd/pixeldataformat/grayscalealpha/) { get; } | 获取为每像素 16 位定义的 `PixelDataFormat`，其中 8 位表示 0-255 区间的灰度强度，另有 8 位的 alpha 分量。 |
| static [Rgb16Bpp555](../../aspose.psd/pixeldataformat/rgb16bpp555/) { get; } | 获取为每像素 16 位定义的 `PixelDataFormat`，其中红、绿、蓝各占 5 位，未定义 alpha。 |
| static [Rgb16Bpp565](../../aspose.psd/pixeldataformat/rgb16bpp565/) { get; } | 获取为每像素 16 位定义的 `PixelDataFormat`，其中红占 5 位，绿占 6 位，蓝占 5 位，未定义 alpha。 |
| static [Rgb24Bpp](../../aspose.psd/pixeldataformat/rgb24bpp/) { get; } | 获取为每像素 24 位定义的 `PixelDataFormat`，其中 alpha、红、绿、蓝各占 8 位，但未定义 alpha。 |
| static [Rgb24BppPng](../../aspose.psd/pixeldataformat/rgb24bpppng/) { get; } | 获取为每像素 24 位定义的 `PixelDataFormat`，其中 alpha、红、绿、蓝各占 8 位，但未定义 alpha。 |
| static [Rgb32Bpp](../../aspose.psd/pixeldataformat/rgb32bpp/) { get; } | 获取为每像素 32 位定义的 `PixelDataFormat`，其中 alpha、红、绿、蓝各占 8 位。 |
| static [Rgba32Bpp](../../aspose.psd/pixeldataformat/rgba32bpp/) { get; } | 获取为每像素 32 位定义的 `PixelDataFormat`，其中 alpha、红、绿、蓝各占 8 位。 |
| static [Rgba64Bpp](../../aspose.psd/pixeldataformat/rgba64bpp/) { get; } | 获取为每像素 64 位定义的 `PixelDataFormat`，其中 alpha、红、绿、蓝各占 16 位。 |
| static [RgbIndexed1Bpp](../../aspose.psd/pixeldataformat/rgbindexed1bpp/) { get; } | 获取为每种颜色 1 位索引定义的 `PixelDataFormat`。索引像素数据存储旨在在使用调色板的所有地方实现数据的存储和检索。请谨慎使用，因为可能需要将调色板从一种转换为另一种，或将 RGBA 转换为索引颜色模型。 |
| static [RgbIndexed2Bpp](../../aspose.psd/pixeldataformat/rgbindexed2bpp/) { get; } | 获取为每种颜色索引的 2 位定义的 `PixelDataFormat`。索引像素数据存储旨在在使用调色板的所有地方允许数据的存储和检索。使用时请谨慎，因为可能需要将一个调色板转换为另一个调色板，或将 RGBA 转换为索引颜色模型。 |
| static [RgbIndexed4Bpp](../../aspose.psd/pixeldataformat/rgbindexed4bpp/) { get; } | 获取为每种颜色索引的 4 位定义的 `PixelDataFormat`。索引像素数据存储旨在在使用调色板的所有地方允许数据的存储和检索。使用时请谨慎，因为可能需要将一个调色板转换为另一个调色板，或将 RGBA 转换为索引颜色模型。 |
| static [RgbIndexed8Bpp](../../aspose.psd/pixeldataformat/rgbindexed8bpp/) { get; } | 获取为每种颜色索引的 8 位定义的 `PixelDataFormat`。索引像素数据存储旨在在使用调色板的所有地方允许数据的存储和检索。使用时请谨慎，因为可能需要将一个调色板转换为另一个调色板，或将 RGBA 转换为索引颜色模型。 |
| static [YCbCr](../../aspose.psd/pixeldataformat/ycbcr/) { get; } | 获取为每像素 24 位、每个亮度、蓝差和红差色度分量各 8 位定义的 `PixelDataFormat`。 |
| static [Ycck](../../aspose.psd/pixeldataformat/ycck/) { get; } | 获取为每像素 32 位、每个亮度、蓝差、红差和黑色色度分量各 8 位定义的 `PixelDataFormat`。 |
| [BitsPerPixel](../../aspose.psd/pixeldataformat/bitsperpixel/) { get; } | 获取每像素位数。 |
| [Caption](../../aspose.psd/pixeldataformat/caption/) { get; } | 获取像素数据格式的标题。 |
| [ChannelBits](../../aspose.psd/pixeldataformat/channelbits/) { get; } | 获取每个通道的位数。 |
| [ChannelsCount](../../aspose.psd/pixeldataformat/channelscount/) { get; } | 获取通道数量。 |
| [PixelFormat](../../aspose.psd/pixeldataformat/pixelformat/) { get; } | 获取像素格式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [GetBgr](../../aspose.psd/pixeldataformat/getbgr/)(int) | 获取具有指定每样本位数的 BGR 颜色。 |
| static [GetBgra](../../aspose.psd/pixeldataformat/getbgra/)(int) | 获取具有指定每样本位数的 BGRA 颜色。 |
| static [GetCieLab](../../aspose.psd/pixeldataformat/getcielab/)(int, int, int) | 获取具有指定每样本位数的 CIE Lab 颜色。 |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk)(int) | 获取具有指定每样本位数的 CMYK 颜色。 |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk_1)(int, int, int, int) | 获取具有指定每样本位数的 CMYK 颜色。 |
| static [GetCmyka](../../aspose.psd/pixeldataformat/getcmyka/)(int, int, int, int, int) | 获取具有指定每样本位数的 CMYKA 颜色。 |
| static [GetGrayscale](../../aspose.psd/pixeldataformat/getgrayscale/)(int) | 获取具有指定每样本位数的灰度颜色。 |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha)(int) | 获取具有指定每样本位数的灰度 Alpha 颜色。 |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha_1)(int, int) | 获取具有指定每样本位数的灰度 Alpha 颜色。 |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb)(int) | 获取具有指定每样本位数的 RGB 颜色。 |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb_1)(int, int, int) | 获取具有指定每样本位数的 RGB 颜色。 |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba)(int) | 获取具有指定每样本位数的 RGBA 颜色。 |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba_1)(int, int, int, int) | 获取具有指定每样本位数的 RGBA 颜色。 |
| static [GetRgbIndexed](../../aspose.psd/pixeldataformat/getrgbindexed/)(int) | 获取具有指定每样本位数的 BGRA 索引颜色。 |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr)(int) | 获取具有指定每样本位数的 YCbCr 颜色。 |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr_1)(int, int, int) | 获取具有指定每样本位数的 YCbCr 颜色。 |
| static [GetYcck](../../aspose.psd/pixeldataformat/getycck/)(int) | 获取具有指定每样本位数的 YCCK 颜色。 |
| override [Equals](../../aspose.psd/pixeldataformat/equals/)(object) | 确定指定的对象是否等于此实例。 |
| override [GetHashCode](../../aspose.psd/pixeldataformat/gethashcode/)() | 返回此实例的哈希码。 |
| override [ToString](../../aspose.psd/pixeldataformat/tostring/)() | 返回一个表示此实例的字符串。 |
| [operator ==](../../aspose.psd/pixeldataformat/op_equality/) | 返回两个 `PixelDataFormat` 类相等性的结果。 |
| [operator !=](../../aspose.psd/pixeldataformat/op_inequality/) | 返回两个 `PixelDataFormat` 类不相等性的结果。 |

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


