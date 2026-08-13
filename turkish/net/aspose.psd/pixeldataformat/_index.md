---
title: "Sınıf PixelDataFormat"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.PixelDataFormat sınıfı. Piksel veri formatı. Bu değiştirilemez bir nesnedir."
type: docs
weight: 5750
url: /tr/net/aspose.psd/pixeldataformat/
---
{{< psd/tize >}}
## PixelDataFormat class

Piksel veri biçimi. Bu, değiştirilemez bir nesnedir.

```csharp
public class PixelDataFormat
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [Cmyk](../../aspose.psd/pixeldataformat/cmyk/) { get; } | `PixelDataFormat`'i, her bir camgöbeği, macenta, sarı ve siyah için 8 bit olmak üzere piksel başına 32 bit olarak tanımlı olanı alır. |
| static [Cmyka](../../aspose.psd/pixeldataformat/cmyka/) { get; } | acmyk'yi alır. |
| static [Grayscale](../../aspose.psd/pixeldataformat/grayscale/) { get; } | `PixelDataFormat`'i, 0-255 aralığında gri ton yoğunluğunu temsil eden 8 bit ile piksel başına 8 bit olarak tanımlı olanı alır. |
| static [GrayscaleAlpha](../../aspose.psd/pixeldataformat/grayscalealpha/) { get; } | `PixelDataFormat`'i, 0-255 aralığında gri ton yoğunluğunu temsil eden 8 bit ve ek 8 bit alfa bileşeni ile piksel başına 16 bit olarak tanımlı olanı alır. |
| static [Rgb16Bpp555](../../aspose.psd/pixeldataformat/rgb16bpp555/) { get; } | `PixelDataFormat`'i, kırmızı, yeşil ve mavi için her biri 5 bit olmak üzere piksel başına 16 bit olarak tanımlı olanı alır, alfa tanımlı değildir. |
| static [Rgb16Bpp565](../../aspose.psd/pixeldataformat/rgb16bpp565/) { get; } | `PixelDataFormat`'i, kırmızı için 5 bit, yeşil için 6 bit ve mavi için 5 bit olmak üzere piksel başına 16 bit olarak tanımlı olanı alır, alfa tanımlı değildir. |
| static [Rgb24Bpp](../../aspose.psd/pixeldataformat/rgb24bpp/) { get; } | `PixelDataFormat`'i, alfa, kırmızı, yeşil ve mavi için her biri 8 bit olmak üzere piksel başına 24 bit olarak tanımlı olanı alır, alfa tanımlı değildir. |
| static [Rgb24BppPng](../../aspose.psd/pixeldataformat/rgb24bpppng/) { get; } | `PixelDataFormat`'i, alfa, kırmızı, yeşil ve mavi için her biri 8 bit olmak üzere piksel başına 24 bit olarak tanımlı olanı alır, alfa tanımlı değildir. |
| static [Rgb32Bpp](../../aspose.psd/pixeldataformat/rgb32bpp/) { get; } | 32 bit piksel başına, alfa, kırmızı, yeşil ve mavi için her biri 8 bit tanımlanan `PixelDataFormat`'ı alır. |
| static [Rgba32Bpp](../../aspose.psd/pixeldataformat/rgba32bpp/) { get; } | 32 bit piksel başına, alfa, kırmızı, yeşil ve mavi için her biri 8 bit tanımlanan `PixelDataFormat`'ı alır. |
| static [Rgba64Bpp](../../aspose.psd/pixeldataformat/rgba64bpp/) { get; } | 64 bit piksel başına, alfa, kırmızı, yeşil ve mavi için her biri 16 bit tanımlanan `PixelDataFormat`'ı alır. |
| static [RgbIndexed1Bpp](../../aspose.psd/pixeldataformat/rgbindexed1bpp/) { get; } | Renk başına indeksli 1 bit tanımlanan `PixelDataFormat`'ı alır. İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolama ve geri almayı sağlamak için tasarlanmıştır. Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerektirebilir. |
| static [RgbIndexed2Bpp](../../aspose.psd/pixeldataformat/rgbindexed2bpp/) { get; } | Renk başına indeksli 2 bit tanımlanan `PixelDataFormat`'ı alır. İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolama ve geri almayı sağlamak için tasarlanmıştır. Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerektirebilir. |
| static [RgbIndexed4Bpp](../../aspose.psd/pixeldataformat/rgbindexed4bpp/) { get; } | Renk başına indeksli 4 bit tanımlanan `PixelDataFormat`'ı alır. İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolama ve geri almayı sağlamak için tasarlanmıştır. Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerektirebilir. |
| static [RgbIndexed8Bpp](../../aspose.psd/pixeldataformat/rgbindexed8bpp/) { get; } | Renk başına indeksli 8 bit tanımlanan `PixelDataFormat`'ı alır. İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolama ve geri almayı sağlamak için tasarlanmıştır. Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerektirebilir. |
| static [YCbCr](../../aspose.psd/pixeldataformat/ycbcr/) { get; } | Piksel başına 24 bit, luma, mavi-fark ve kırmızı-fark kromatik bileşenlerinin her biri 8 bit tanımlanan `PixelDataFormat`'ı alır. |
| static [Ycck](../../aspose.psd/pixeldataformat/ycck/) { get; } | Piksel başına 32 bit, luma, mavi-fark, kırmızı-fark ve siyah kromatik bileşenlerinin her biri 8 bit tanımlanan `PixelDataFormat`'ı alır. |
| [BitsPerPixel](../../aspose.psd/pixeldataformat/bitsperpixel/) { get; } | Piksel başına bit sayısını alır. |
| [Caption](../../aspose.psd/pixeldataformat/caption/) { get; } | Piksel veri formatı başlığını alır. |
| [ChannelBits](../../aspose.psd/pixeldataformat/channelbits/) { get; } | Her kanal için bit sayısını alır. |
| [ChannelsCount](../../aspose.psd/pixeldataformat/channelscount/) { get; } | Kanal sayısını alır. |
| [PixelFormat](../../aspose.psd/pixeldataformat/pixelformat/) { get; } | Piksel formatını alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [GetBgr](../../aspose.psd/pixeldataformat/getbgr/)(int) | Örnek başına belirtilen bit sayısıyla BGR rengini alır. |
| static [GetBgra](../../aspose.psd/pixeldataformat/getbgra/)(int) | Örnek başına belirtilen bit sayısıyla BGRA rengini alır. |
| static [GetCieLab](../../aspose.psd/pixeldataformat/getcielab/)(int, int, int) | Örnek başına belirtilen bit sayısıyla CIE Lab rengini alır. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk)(int) | Örnek başına belirtilen bit sayısıyla CMYK rengini alır. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk_1)(int, int, int, int) | Örnek başına belirtilen bit sayısıyla CMYK rengini alır. |
| static [GetCmyka](../../aspose.psd/pixeldataformat/getcmyka/)(int, int, int, int, int) | Örnek başına belirtilen bit sayısıyla CMYKA rengini alır. |
| static [GetGrayscale](../../aspose.psd/pixeldataformat/getgrayscale/)(int) | Örnek başına belirtilen bit sayısıyla Gri tonlamalı rengi alır. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha)(int) | Örnek başına belirtilen bit sayısıyla Gri tonlamalı Alfa rengini alır. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha_1)(int, int) | Örnek başına belirtilen bit sayısıyla Gri tonlamalı Alfa rengini alır. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb)(int) | Örnek başına belirtilen bit sayısıyla RGB rengini alır. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb_1)(int, int, int) | Örnek başına belirtilen bit sayısıyla RGB rengini alır. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba)(int) | Örnek başına belirtilen bit sayısıyla RGBA rengini alır. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba_1)(int, int, int, int) | Örnek başına belirtilen bit sayısıyla RGBA rengini alır. |
| static [GetRgbIndexed](../../aspose.psd/pixeldataformat/getrgbindexed/)(int) | Örnek başına belirtilen bit sayısıyla BGRA indeksli rengi alır. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr)(int) | Örnek başına belirtilen bit sayısıyla YCbCr rengini alır. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr_1)(int, int, int) | Örnek başına belirtilen bit sayısıyla YCbCr rengini alır. |
| static [GetYcck](../../aspose.psd/pixeldataformat/getycck/)(int) | Örnek başına belirtilen bit sayısıyla YCCK rengini alır. |
| override [Equals](../../aspose.psd/pixeldataformat/equals/)(object) | Belirtilen Nesnenin bu örnek ile eşit olup olmadığını belirler. |
| override [GetHashCode](../../aspose.psd/pixeldataformat/gethashcode/)() | Bu örnek için bir hash kodu döndürür. |
| override [ToString](../../aspose.psd/pixeldataformat/tostring/)() | Bu örneği temsil eden bir String döndürür. |
| [operator ==](../../aspose.psd/pixeldataformat/op_equality/) | `PixelDataFormat` sınıflarının eşitlik sonucunu döndürür. |
| [operator !=](../../aspose.psd/pixeldataformat/op_inequality/) | İki `PixelDataFormat` sınıfı için eşitsizlik sonucunu döndürür. |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


