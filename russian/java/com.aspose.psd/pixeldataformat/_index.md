---
title: "PixelDataFormat"
second_title: "Aspose.PSD for Java API Справочник"
description: "Формат данных пикселей."
type: docs
weight: 80
url: /ru/java/com.aspose.psd/pixeldataformat/
---

**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

Формат пиксельных данных. Это неизменяемый объект.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный  System.Object  этому экземпляру. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Получает цвет BGR с указанным количеством битов на образец. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Получает цвет BGRA с указанным количеством битов на образец. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество битов на пиксель. |
| [getCaption()](#getCaption--) | Получает подпись формата данных пикселя. |
| [getChannelBits()](#getChannelBits--) | Получает количество битов для каждого канала. |
| [getChannelsCount()](#getChannelsCount--) | Получает количество каналов. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Получает цвет CIE Lab с указанным количеством битов на образец. |
| [getClass()](#getClass--) |  |
| [getCmyk()](#getCmyk--) | Получает  PixelDataFormat  определённый для 32 бит на пиксель с 8 битами для каждого из циана, мадженты, желтого и черного. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Получает цвет CMYK с указанным количеством битов на образец. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Получает цвет CMYK с указанным количеством битов на образец. |
| [getCmyk16()](#getCmyk16--) | Получает [PixelDataFormat](../../com.aspose.psd/pixeldataformat), определённый для 64 бит на пиксель с 16 битами для каждого из циана, мадженты, желтого и черного. |
| [getCmyka()](#getCmyka--) | Получает acmyk. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Получает цвет CMYKA с указанным количеством битов на образец. |
| [getCmyka16()](#getCmyka16--) | Получает acmyk. |
| [getGrayscale()](#getGrayscale--) | Получает  PixelDataFormat , определённый для 8 бит на пиксель с 8 битами, представляющими интенсивность оттенков серого в диапазоне 0‑255. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Получает цвет Grayscale с указанным количеством битов на образец. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Получает  PixelDataFormat , определённый для 16 бит на пиксель с 8 битами, представляющими интенсивность оттенков серого в диапазоне 0‑255, и дополнительным 8‑битным альфа‑компонентом. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Получает цвет GrayscaleAlpha с указанным количеством битов на образец. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Получает цвет GrayscaleAlpha с указанным количеством битов на образец. |
| [getGrayscaleFloat32_internalized()](#getGrayscaleFloat32-internalized--) | Получает [PixelDataFormat](../../com.aspose.psd/pixeldataformat), определённый для 32 бит на пиксель, представляющий интенсивность оттенков серого в формате с плавающей точкой. |
| [getPixelFormat()](#getPixelFormat--) | Получает формат пикселя. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Получает цвет RGB с указанным количеством битов на образец. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Получает цвет RGB с указанным количеством битов на образец. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Получает  PixelDataFormat , определённый для 16 бит на пиксель с 5 битами для каждого из красного, зелёного и синего, альфа не определена. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Получает  PixelDataFormat , определённый для 16 бит на пиксель с 5 битами для красного, 6 битами для зелёного и 5 битами для синего, альфа не определена. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Получает  PixelDataFormat , определённый для 24 бит на пиксель с 8 битами для каждого из альфа, красного, зелёного и синего, альфа не определена. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Получает  PixelDataFormat , определённый для 24 бит на пиксель с 8 битами для каждого из альфа, красного, зелёного и синего, альфа не определена. |
| [getRgb32Bpp()](#getRgb32Bpp--) | Получает  PixelDataFormat , определённый для 32 бит на пиксель с 8 битами для каждого из альфа, красного, зелёного и синего. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Получает индексированный цвет BGRA с указанным количеством битов на образец. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Получает  PixelDataFormat  , определенный для индексированного 1 бита на цвет. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Получает  PixelDataFormat  , определенный для индексированного 2 бита на цвет. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Получает  PixelDataFormat  , определенный для индексированного 4 бита на цвет. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Получает  PixelDataFormat  , определенный для индексированного 8 бит на цвет. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Получает цвет RGBA с указанным количеством бит на образец. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Получает цвет RGBA с указанным количеством бит на образец. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Получает  PixelDataFormat , определённый для 32 бит на пиксель с 8 битами для каждого из альфа, красного, зелёного и синего. |
| [getRgba64Bpp()](#getRgba64Bpp--) | Получает [PixelDataFormat](../../com.aspose.psd/pixeldataformat), определенный для 64 бит на пиксель с 16 битами для каждого из альфа, красного, зеленого и синего. |
| [getYCbCr()](#getYCbCr--) | Получает  PixelDataFormat  , определенный для 24 бит на пиксель с 8 битами для каждого из компонентов яркости, разницы синего и разницы красного хрома. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Получает цвет YCbCr с указанным количеством бит на образец. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Получает цвет YCbCr с указанным количеством бит на образец. |
| [getYcck()](#getYcck--) | Получает  PixelDataFormat  , определенный для 32 бит на пиксель с 8 битами для каждого из компонентов яркости, разницы синего, разницы красного и черного хрома. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Получает цвет YCCK с указанным количеством бит на образец. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [isIndexed_internalized()](#isIndexed-internalized--) | Получает значение, указывающее, является ли этот экземпляр индексированным. |
| [newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)](#newPixelDataFormat-internalized-int---int-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Возвращает результат сравнения на равенство для двух  PixelDataFormat  классов. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Возвращает результат сравнения на неравенство для двух  PixelDataFormat  классов. |
| [toString()](#toString--) | Возвращает  System.String  который представляет этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный  System.Object  этому экземпляру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект  System.Object  для сравнения с этим экземпляром. |

**Returns:**
boolean -  true  если указанный  System.Object  равен этому экземпляру; иначе,  false .
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Получает цвет BGR с указанным количеством битов на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGR color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Получает цвет BGRA с указанным количеством битов на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает количество битов на пиксель.

**Returns:**
int - количество бит на пиксель.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Получает подпись формата данных пикселя.

**Returns:**
java.lang.String
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Получает количество битов для каждого канала.

**Returns:**
int[] - биты каналов.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Получает количество каналов.

**Returns:**
int - количество каналов.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Получает цвет CIE Lab с указанным количеством битов на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerL | int | Количество бит на канал L. |
| bitsPerA | int | Количество бит на канал A. |
| bitsPerB | int | Количество бит на канал B. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CIE Lab color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


Получает  PixelDataFormat  определённый для 32 бит на пиксель с 8 битами для каждого из циана, мадженты, желтого и черного.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Получает цвет CMYK с указанным количеством битов на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Получает цвет CMYK с указанным количеством битов на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerCyanChannel | int | Количество битов на канал Cyan. |
| bitsPerMagentaChannel | int | Количество битов на канал Magenta. |
| bitsPerYellowChannel | int | Количество битов на канал Yellow. |
| bitsPerKeyChannel | int | Количество битов на канал Key. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk16() {#getCmyk16--}
```
public static PixelDataFormat getCmyk16()
```


Получает [PixelDataFormat](../../com.aspose.psd/pixeldataformat), определённый для 64 бит на пиксель с 16 битами для каждого из циана, мадженты, желтого и черного.

Значение: [PixelDataFormat](../../com.aspose.psd/pixeldataformat) определённый для 64 бит на пиксель с 16 битами для каждого из cyan, magenta, yellow и black.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Получает acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Получает цвет CMYKA с указанным количеством битов на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerCyanChannel | int | Количество битов на канал Cyan. |
| bitsPerMagentaChannel | int | Количество битов на канал Magenta. |
| bitsPerYellowChannel | int | Количество битов на канал Yellow. |
| bitsPerKeyChannel | int | Количество битов на канал Key. |
| bitsPerAlphaChannel | int | Количество битов на канал Alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyka16() {#getCmyka16--}
```
public static PixelDataFormat getCmyka16()
```


Получает acmyk.

Значение: [PixelDataFormat](../../com.aspose.psd/pixeldataformat) определённый для 80 бит на пиксель с 16 битами для каждого из alpha, cyan, magenta, yellow и black.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getGrayscale() {#getGrayscale--}
```
public static PixelDataFormat getGrayscale()
```


Получает  PixelDataFormat , определённый для 8 бит на пиксель с 8 битами, представляющими интенсивность оттенков серого в диапазоне 0‑255.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Получает цвет Grayscale с указанным количеством битов на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Получает  PixelDataFormat , определённый для 16 бит на пиксель с 8 битами, представляющими интенсивность оттенков серого в диапазоне 0‑255, и дополнительным 8‑битным альфа‑компонентом.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Получает цвет GrayscaleAlpha с указанным количеством битов на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Получает цвет GrayscaleAlpha с указанным количеством битов на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |
| alphaChannelBits | int | Количество битов на образец в канале alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleFloat32_internalized() {#getGrayscaleFloat32-internalized--}
```
public static PixelDataFormat getGrayscaleFloat32_internalized()
```


Получает [PixelDataFormat](../../com.aspose.psd/pixeldataformat), определённый для 32 бит на пиксель, представляющий интенсивность оттенков серого в формате с плавающей точкой.

Значение: [PixelDataFormat](../../com.aspose.psd/pixeldataformat) определённый для 32 бит на пиксель, представляющий интенсивность в градациях серого в формате с плавающей точкой

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Получает формат пикселя.

**Returns:**
int - Формат пикселя.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Получает цвет RGB с указанным количеством битов на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Получает цвет RGB с указанным количеством битов на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerRedChannel | int | Количество битов на канал Red. |
| bitsPerGreenChannel | int | Количество битов на канал Green. |
| bitsPerBlueChannel | int | Количество битов на канал Blue. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Получает  PixelDataFormat , определённый для 16 бит на пиксель с 5 битами для каждого из красного, зелёного и синего, альфа не определена.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Получает  PixelDataFormat , определённый для 16 бит на пиксель с 5 битами для красного, 6 битами для зелёного и 5 битами для синего, альфа не определена.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Получает  PixelDataFormat , определённый для 24 бит на пиксель с 8 битами для каждого из альфа, красного, зелёного и синего, альфа не определена.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Получает  PixelDataFormat , определённый для 24 бит на пиксель с 8 битами для каждого из альфа, красного, зелёного и синего, альфа не определена.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Получает  PixelDataFormat , определённый для 32 бит на пиксель с 8 битами для каждого из альфа, красного, зелёного и синего.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Получает индексированный цвет BGRA с указанным количеством битов на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Получает PixelDataFormat, определённый для индексированных 1 бита на цвет. Индексированное хранение пиксельных данных предназначено для обеспечения хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, так как может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 1 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Получает PixelDataFormat, определённый для индексированных 2 бит на цвет. Индексированное хранение пиксельных данных предназначено для обеспечения хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, так как может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 2 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Получает PixelDataFormat, определённый для индексированных 4 бит на цвет. Индексированное хранение пиксельных данных предназначено для обеспечения хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, так как может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 4 bit per color.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Получает PixelDataFormat, определённый для индексированных 8 бит на цвет. Индексированное хранение пиксельных данных предназначено для обеспечения хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, так как может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 8 bit per color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Получает цвет RGBA с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Получает цвет RGBA с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerRedChannel | int | Количество битов на канал Red. |
| bitsPerGreenChannel | int | Количество битов на канал Green. |
| bitsPerBlueChannel | int | Количество битов на канал Blue. |
| bitsPerAlphaChannel | int | Количество битов на канал Alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Получает  PixelDataFormat , определённый для 32 бит на пиксель с 8 битами для каждого из альфа, красного, зелёного и синего.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgba64Bpp() {#getRgba64Bpp--}
```
public static PixelDataFormat getRgba64Bpp()
```


Получает [PixelDataFormat](../../com.aspose.psd/pixeldataformat), определенный для 64 бит на пиксель с 16 битами для каждого из альфа, красного, зеленого и синего.

Значение: [PixelDataFormat](../../com.aspose.psd/pixeldataformat) определён для 64 бит на пиксель с 16 битами для каждого из альфа, красного, зелёного и синего.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Получает  PixelDataFormat  , определенный для 24 бит на пиксель с 8 битами для каждого из компонентов яркости, разницы синего и разницы красного хрома.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Получает цвет YCbCr с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Получает цвет YCbCr с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerY | int | Количество бит на канал Y. |
| bitsPerCb | int | Количество бит на канал Cb. |
| bitsPerCr | int | Количество бит на канал Cr. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Получает  PixelDataFormat  , определенный для 32 бит на пиксель с 8 битами для каждого из компонентов яркости, разницы синего, разницы красного и черного хрома.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Получает цвет YCCK с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCCK color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int - Хеш-код для этого экземпляра, подходящий для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
### isIndexed_internalized() {#isIndexed-internalized--}
```
public final boolean isIndexed_internalized()
```


Получает значение, указывающее, является ли этот экземпляр индексированным.

Значение:  true  если этот экземпляр индексирован; иначе,  false .

**Returns:**
boolean - значение, указывающее, индексирован ли этот экземпляр.
### newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption) {#newPixelDataFormat-internalized-int---int-java.lang.String-}
```
public static PixelDataFormat newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| channelBits | int[] |  |
| pixelFormat | int |  |
| caption | java.lang.String |  |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Возвращает результат сравнения на равенство для двух  PixelDataFormat  классов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Первый PixelDataFormat для сравнения. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Второй PixelDataFormat для сравнения. |

**Returns:**
boolean - True, если оба pixelFormat1 и pixelFormat2 содержат одинаковые данные или оба параметра равны null.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Возвращает результат сравнения на неравенство для двух  PixelDataFormat  классов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Первый PixelDataFormat для сравнения. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Второй PixelDataFormat для сравнения. |

**Returns:**
boolean - True, если оба pixelFormat1 и pixelFormat2 содержат различающиеся данные или один из параметров равен null.
### toString() {#toString--}
```
public String toString()
```


Возвращает  System.String  который представляет этот экземпляр.

**Returns:**
java.lang.String -  System.String  представляющий этот экземпляр.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

