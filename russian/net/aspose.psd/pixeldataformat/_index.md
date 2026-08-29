---
title: "Класс PixelDataFormat"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.PixelDataFormat. Формат данных пикселя. Это неизменяемый объект."
type: docs
weight: 5720
url: /ru/net/aspose.psd/pixeldataformat/
---
{{< psd/tize >}}
## PixelDataFormat class

Формат данных пикселей. Это неизменяемый объект.

```csharp
public class PixelDataFormat
```

## Свойства

| Имя | Описание |
| --- | --- |
| static [Cmyk](../../aspose.psd/pixeldataformat/cmyk/) { get; } | Возвращает `PixelDataFormat`, определённый для 32 бит на пиксель с 8 битами для каждого из цветов циан, маджента, жёлтого и чёрного. |
| static [Cmyka](../../aspose.psd/pixeldataformat/cmyka/) { get; } | Возвращает acmyk. |
| static [Grayscale](../../aspose.psd/pixeldataformat/grayscale/) { get; } | Возвращает `PixelDataFormat`, определённый для 8 бит на пиксель, где 8 бит представляют интенсивность в градациях серого в диапазоне 0‑255. |
| static [GrayscaleAlpha](../../aspose.psd/pixeldataformat/grayscalealpha/) { get; } | Возвращает `PixelDataFormat`, определённый для 16 бит на пиксель, где 8 бит представляют интенсивность в градациях серого в диапазоне 0‑255 и добавлен 8‑битный альфа‑компонент. |
| static [Rgb16Bpp555](../../aspose.psd/pixeldataformat/rgb16bpp555/) { get; } | Возвращает `PixelDataFormat`, определённый для 16 бит на пиксель с 5 битами для каждого из цветов красного, зелёного и синего, альфа‑компонент не определён. |
| static [Rgb16Bpp565](../../aspose.psd/pixeldataformat/rgb16bpp565/) { get; } | Возвращает `PixelDataFormat`, определённый для 16 бит на пиксель с 5 битами для красного, 6 битами для зелёного и 5 битами для синего, альфа‑компонент не определён. |
| static [Rgb24Bpp](../../aspose.psd/pixeldataformat/rgb24bpp/) { get; } | Возвращает `PixelDataFormat`, определённый для 24 бит на пиксель с 8 битами для каждого из альфа, красного, зелёного и синего, альфа‑компонент не определён. |
| static [Rgb24BppPng](../../aspose.psd/pixeldataformat/rgb24bpppng/) { get; } | Возвращает `PixelDataFormat`, определённый для 24 бит на пиксель с 8 битами для каждого из альфа, красного, зелёного и синего, альфа‑компонент не определён. |
| static [Rgb32Bpp](../../aspose.psd/pixeldataformat/rgb32bpp/) { get; } | Возвращает `PixelDataFormat`, определенный для 32 бит на пиксель с 8 битами для каждого из альфа, красного, зеленого и синего. |
| static [Rgba32Bpp](../../aspose.psd/pixeldataformat/rgba32bpp/) { get; } | Возвращает `PixelDataFormat`, определенный для 32 бит на пиксель с 8 битами для каждого из альфа, красного, зеленого и синего. |
| static [Rgba64Bpp](../../aspose.psd/pixeldataformat/rgba64bpp/) { get; } | Возвращает `PixelDataFormat`, определенный для 64 бит на пиксель с 16 битами для каждого из альфа, красного, зеленого и синего. |
| static [RgbIndexed1Bpp](../../aspose.psd/pixeldataformat/rgbindexed1bpp/) { get; } | Возвращает `PixelDataFormat`, определенный для индексированного 1 бита на цвет. Индексированное хранение пиксельных данных предназначено для обеспечения хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, так как может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель. |
| static [RgbIndexed2Bpp](../../aspose.psd/pixeldataformat/rgbindexed2bpp/) { get; } | Возвращает `PixelDataFormat`, определенный для индексированного 2 бита на цвет. Индексированное хранение пиксельных данных предназначено для обеспечения хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, так как может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель. |
| static [RgbIndexed4Bpp](../../aspose.psd/pixeldataformat/rgbindexed4bpp/) { get; } | Возвращает `PixelDataFormat`, определенный для индексированного 4 бита на цвет. Индексированное хранение пиксельных данных предназначено для обеспечения хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, так как может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель. |
| static [RgbIndexed8Bpp](../../aspose.psd/pixeldataformat/rgbindexed8bpp/) { get; } | Возвращает `PixelDataFormat`, определенный для индексированного 8 бита на цвет. Индексированное хранение пиксельных данных предназначено для обеспечения хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, так как может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель. |
| static [YCbCr](../../aspose.psd/pixeldataformat/ycbcr/) { get; } | Возвращает `PixelDataFormat`, определенный для 24 бит на пиксель с 8 битами для каждого из компонентов яркости, разницы синего и разницы красного хромы. |
| static [Ycck](../../aspose.psd/pixeldataformat/ycck/) { get; } | Возвращает `PixelDataFormat`, определенный для 32 бит на пиксель с 8 битами для каждого из компонентов яркости, разницы синего, разницы красного и черной хромы. |
| [BitsPerPixel](../../aspose.psd/pixeldataformat/bitsperpixel/) { get; } | Возвращает количество бит на пиксель. |
| [Caption](../../aspose.psd/pixeldataformat/caption/) { get; } | Возвращает подпись формата пиксельных данных. |
| [ChannelBits](../../aspose.psd/pixeldataformat/channelbits/) { get; } | Возвращает количество бит для каждого канала. |
| [ChannelsCount](../../aspose.psd/pixeldataformat/channelscount/) { get; } | Возвращает количество каналов. |
| [PixelFormat](../../aspose.psd/pixeldataformat/pixelformat/) { get; } | Возвращает формат пикселя. |

## Методы

| Имя | Описание |
| --- | --- |
| static [GetBgr](../../aspose.psd/pixeldataformat/getbgr/)(int) | Возвращает цвет BGR с указанным количеством бит на образец. |
| static [GetBgra](../../aspose.psd/pixeldataformat/getbgra/)(int) | Возвращает цвет BGRA с указанным количеством бит на образец. |
| static [GetCieLab](../../aspose.psd/pixeldataformat/getcielab/)(int, int, int) | Возвращает цвет CIE Lab с указанным количеством бит на образец. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk)(int) | Возвращает цвет CMYK с указанным количеством бит на образец. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk_1)(int, int, int, int) | Возвращает цвет CMYK с указанным количеством бит на образец. |
| static [GetCmyka](../../aspose.psd/pixeldataformat/getcmyka/)(int, int, int, int, int) | Возвращает цвет CMYKA с указанным количеством бит на образец. |
| static [GetGrayscale](../../aspose.psd/pixeldataformat/getgrayscale/)(int) | Возвращает цвет Grayscale с указанным количеством бит на образец. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha)(int) | Возвращает цвет GrayscaleAlpha с указанным количеством бит на образец. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha_1)(int, int) | Возвращает цвет GrayscaleAlpha с указанным количеством бит на образец. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb)(int) | Возвращает цвет RGB с указанным количеством бит на образец. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb_1)(int, int, int) | Возвращает цвет RGB с указанным количеством бит на образец. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba)(int) | Возвращает цвет RGBA с указанным количеством бит на образец. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba_1)(int, int, int, int) | Возвращает цвет RGBA с указанным количеством бит на образец. |
| static [GetRgbIndexed](../../aspose.psd/pixeldataformat/getrgbindexed/)(int) | Возвращает индексированный цвет BGRA с указанным количеством бит на образец. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr)(int) | Возвращает цвет YCbCr с указанным количеством бит на образец. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr_1)(int, int, int) | Возвращает цвет YCbCr с указанным количеством бит на образец. |
| static [GetYcck](../../aspose.psd/pixeldataformat/getycck/)(int) | Возвращает цвет YCCK с указанным количеством бит на образец. |
| override [Equals](../../aspose.psd/pixeldataformat/equals/)(object) | Определяет, равен ли указанный объект этому экземпляру. |
| override [GetHashCode](../../aspose.psd/pixeldataformat/gethashcode/)() | Возвращает хеш‑код для этого экземпляра. |
| override [ToString](../../aspose.psd/pixeldataformat/tostring/)() | Возвращает строку, представляющую этот экземпляр. |
| [operator ==](../../aspose.psd/pixeldataformat/op_equality/) | Возвращает результат сравнения на равенство для двух классов `PixelDataFormat`. |
| [operator !=](../../aspose.psd/pixeldataformat/op_inequality/) | Возвращает результат неравенства для двух классов `PixelDataFormat`. |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


