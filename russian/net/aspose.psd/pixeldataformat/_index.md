---
title: Class PixelDataFormat
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.PixelDataFormat сорт. Формат данных пикселей. Это неизменяемый объект.
type: docs
weight: 5230
url: /ru/net/aspose.psd/pixeldataformat/
---
## PixelDataFormat class

Формат данных пикселей. Это неизменяемый объект.

```csharp
public class PixelDataFormat
```

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Cmyk](../../aspose.psd/pixeldataformat/cmyk/) { get; } | Получает`PixelDataFormat` определяется для 32 бит на пиксель с 8 битами для каждого из голубого, пурпурного, желтого и черного. |
| static [Cmyka](../../aspose.psd/pixeldataformat/cmyka/) { get; } | Получает акмык. |
| static [Grayscale](../../aspose.psd/pixeldataformat/grayscale/) { get; } | Получает`PixelDataFormat`определяется для 8 бит на пиксель, где 8 бит представляют интенсивность оттенков серого в интервале 0–255. |
| static [GrayscaleAlpha](../../aspose.psd/pixeldataformat/grayscalealpha/) { get; } | Получает`PixelDataFormat` определено для 16 бит на пиксель с 8 битами, представляющими интенсивность оттенков серого в интервале 0–255, и дополнительным 8-битным альфа-компонентом. |
| static [Rgb16Bpp555](../../aspose.psd/pixeldataformat/rgb16bpp555/) { get; } | Получает`PixelDataFormat` определено для 16 бит на пиксель с 5 битами для каждого из красного, зеленого и синего, альфа не определена. |
| static [Rgb16Bpp565](../../aspose.psd/pixeldataformat/rgb16bpp565/) { get; } | Получает`PixelDataFormat`определяется для 16 бит на пиксель с 5 битами для красного, 6 битами для зеленого и 5 битами для синего, альфа не определена. |
| static [Rgb24Bpp](../../aspose.psd/pixeldataformat/rgb24bpp/) { get; } | Получает`PixelDataFormat` определяется для 24 бит на пиксель с 8 битами для каждого из альфа, красного, зеленого и синего, альфа не определен. |
| static [Rgb24BppPng](../../aspose.psd/pixeldataformat/rgb24bpppng/) { get; } | Получает`PixelDataFormat` определяется для 24 бит на пиксель с 8 битами для каждого из альфа, красного, зеленого и синего, альфа не определен. |
| static [Rgb32Bpp](../../aspose.psd/pixeldataformat/rgb32bpp/) { get; } | Получает`PixelDataFormat` определяется для 32 бит на пиксель с 8 битами для каждого из альфа, красного, зеленого и синего. |
| static [Rgba32Bpp](../../aspose.psd/pixeldataformat/rgba32bpp/) { get; } | Получает`PixelDataFormat` определяется для 32 бит на пиксель с 8 битами для каждого из альфа, красного, зеленого и синего. |
| static [Rgba64Bpp](../../aspose.psd/pixeldataformat/rgba64bpp/) { get; } | Получает`PixelDataFormat` определяется для 64 бит на пиксель с 16 битами для каждого из альфа, красного, зеленого и синего. |
| static [RgbIndexed1Bpp](../../aspose.psd/pixeldataformat/rgbindexed1bpp/) { get; } | Получает`PixelDataFormat` определено для индексированного 1 бита на цвет. Хранилище данных индексированного пикселя предназначено для хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, поскольку может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель . |
| static [RgbIndexed2Bpp](../../aspose.psd/pixeldataformat/rgbindexed2bpp/) { get; } | Получает`PixelDataFormat`определено для индексированного 2 бита на цвет. Хранилище данных индексированного пикселя предназначено для хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, поскольку может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель . |
| static [RgbIndexed4Bpp](../../aspose.psd/pixeldataformat/rgbindexed4bpp/) { get; } | Получает`PixelDataFormat` определено для индексированных 4 бит на цвет. Хранилище данных индексированных пикселей предназначено для хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, поскольку может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель . |
| static [RgbIndexed8Bpp](../../aspose.psd/pixeldataformat/rgbindexed8bpp/) { get; } | Получает`PixelDataFormat` определено для индексированных 8 бит на цвет. Хранилище данных индексированных пикселей предназначено для хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, поскольку может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель . |
| static [YCbCr](../../aspose.psd/pixeldataformat/ycbcr/) { get; } | Получает`PixelDataFormat` определяется для 24 бит на пиксель с 8 битами для каждого из компонентов яркости, синего и красного контраста цветности. |
| static [Ycck](../../aspose.psd/pixeldataformat/ycck/) { get; } | Получает`PixelDataFormat` определяется для 32 бит на пиксель с 8 битами для каждого компонента яркости, синего, красного и черного цветных компонентов. |
| [BitsPerPixel](../../aspose.psd/pixeldataformat/bitsperpixel/) { get; } | Получает количество бит на пиксель. |
| [Caption](../../aspose.psd/pixeldataformat/caption/) { get; } | Получает заголовок формата пиксельных данных. |
| [ChannelBits](../../aspose.psd/pixeldataformat/channelbits/) { get; } | Получает количество битов для каждого канала. |
| [ChannelsCount](../../aspose.psd/pixeldataformat/channelscount/) { get; } | Получает количество каналов. |
| [PixelFormat](../../aspose.psd/pixeldataformat/pixelformat/) { get; } | Получает формат пикселей. |

## Методы

| Имя | Описание |
| --- | --- |
| static [GetBgr](../../aspose.psd/pixeldataformat/getbgr/)(int) | Получает цвет BGR с указанным количеством битов на выборку. |
| static [GetBgra](../../aspose.psd/pixeldataformat/getbgra/)(int) | Получает цвет BGRA с указанным количеством битов на выборку. |
| static [GetCieLab](../../aspose.psd/pixeldataformat/getcielab/)(int, int, int) | Получает цвет CIE Lab с указанным количеством битов на выборку. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk)(int) | Получает цвет CMYK с указанным количеством битов на образец. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk_1)(int, int, int, int) | Получает цвет CMYK с указанным количеством битов на образец. |
| static [GetCmyka](../../aspose.psd/pixeldataformat/getcmyka/)(int, int, int, int, int) | Получает цвет CMYKA с указанным количеством битов на образец. |
| static [GetGrayscale](../../aspose.psd/pixeldataformat/getgrayscale/)(int) | Получает цвет в градациях серого с указанным количеством битов на выборку. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha)(int) | Получает цвет GrayscaleAlpha с указанным количеством битов на выборку. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha_1)(int, int) | Получает цвет GrayscaleAlpha с указанным количеством битов на выборку. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb)(int) | Получает цвет RGB с указанным количеством битов на выборку. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb_1)(int, int, int) | Получает цвет RGB с указанным количеством битов на выборку. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba)(int) | Получает цвет RGBA с указанным количеством битов на выборку. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba_1)(int, int, int, int) | Получает цвет RGBA с указанным количеством битов на выборку. |
| static [GetRgbIndexed](../../aspose.psd/pixeldataformat/getrgbindexed/)(int) | Получает индексированный BGRA цвет с указанным количеством битов на выборку. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr)(int) | Получает цвет YCbCr с указанным количеством битов на выборку. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr_1)(int, int, int) | Получает цвет YCbCr с указанным количеством битов на выборку. |
| static [GetYcck](../../aspose.psd/pixeldataformat/getycck/)(int) | Получает цвет YCCK с указанным количеством битов на выборку. |
| override [Equals](../../aspose.psd/pixeldataformat/equals/)(object) | Определяет, является ли указанныйObject равен этому экземпляру. |
| override [GetHashCode](../../aspose.psd/pixeldataformat/gethashcode/)() | Возвращает хэш-код для этого экземпляра. |
| override [ToString](../../aspose.psd/pixeldataformat/tostring/)() | ВозвращаетString который представляет этот экземпляр. |
| [operator ==](../../aspose.psd/pixeldataformat/op_equality/) | Возвращает результат равенства для двух`PixelDataFormat` классы. |
| [operator !=](../../aspose.psd/pixeldataformat/op_inequality/) | Возвращает результат неравноправия для двух`PixelDataFormat` классы. |

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd/)
* сборка [Aspose.PSD](../../)


