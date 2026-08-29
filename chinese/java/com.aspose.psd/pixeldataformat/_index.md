---
title: "PixelDataFormat"
second_title: "Aspose.PSD 的 Java API 参考"
description: "像素数据格式。"
type: docs
weight: 80
url: /zh/java/com.aspose.psd/pixeldataformat/
---

**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

像素数据格式。这是一个不可变对象。
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的  System.Object  是否等于此实例。 |
| [getBgr(int bitsPerSample)](#getBgr-int-) | 获取具有指定每样本位数的 BGR 颜色。 |
| [getBgra(int bitsPerSample)](#getBgra-int-) | 获取具有指定每样本位数的 BGRA 颜色。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取每像素位数。 |
| [getCaption()](#getCaption--) | 获取像素数据格式的标题。 |
| [getChannelBits()](#getChannelBits--) | 获取每个通道的位计数。 |
| [getChannelsCount()](#getChannelsCount--) | 获取通道数。 |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | 获取具有指定每样本位数的 CIE Lab 颜色。 |
| [getClass()](#getClass--) |  |
| [getCmyk()](#getCmyk--) | 获取为每像素 32 位且每种青色、品红、黄色和黑色各 8 位定义的 PixelDataFormat。 |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | 获取具有指定每样本位数的 CMYK 颜色。 |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | 获取具有指定每样本位数的 CMYK 颜色。 |
| [getCmyk16()](#getCmyk16--) | 获取为每像素 64 位且每种青色、品红、黄色和黑色各 16 位定义的 [PixelDataFormat](../../com.aspose.psd/pixeldataformat)。 |
| [getCmyka()](#getCmyka--) | 获取 acmyk。 |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | 获取具有指定每样本位数的 CMYKA 颜色。 |
| [getCmyka16()](#getCmyka16--) | 获取 acmyk。 |
| [getGrayscale()](#getGrayscale--) | 获取为每像素 8 位且 8 位表示 0-255 区间内灰度强度定义的 PixelDataFormat。 |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | 获取具有指定每样本位数的灰度颜色。 |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | 获取为每像素 16 位且 8 位表示 0-255 区间内灰度强度并附加 8 位 alpha 分量定义的 PixelDataFormat。 |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | 获取具有指定每样本位数的灰度 Alpha 颜色。 |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | 获取具有指定每样本位数的灰度 Alpha 颜色。 |
| [getGrayscaleFloat32_internalized()](#getGrayscaleFloat32-internalized--) | 获取为每像素 32 位且以浮点格式表示灰度强度定义的 [PixelDataFormat](../../com.aspose.psd/pixeldataformat)。 |
| [getPixelFormat()](#getPixelFormat--) | 获取像素格式。 |
| [getRgb(int bitsPerSample)](#getRgb-int-) | 获取具有指定每样本位数的 RGB 颜色。 |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | 获取具有指定每样本位数的 RGB 颜色。 |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | 获取为每像素 16 位且红、绿、蓝各 5 位、未定义 alpha 的 PixelDataFormat。 |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | 获取为每像素 16 位且红 5 位、绿 6 位、蓝 5 位、未定义 alpha 的 PixelDataFormat。 |
| [getRgb24Bpp()](#getRgb24Bpp--) | 获取为每像素 24 位且 alpha、红、绿、蓝各 8 位、未定义 alpha 的 PixelDataFormat。 |
| [getRgb24BppPng()](#getRgb24BppPng--) | 获取为每像素 24 位且 alpha、红、绿、蓝各 8 位、未定义 alpha 的 PixelDataFormat。 |
| [getRgb32Bpp()](#getRgb32Bpp--) | 获取为每像素 32 位且 alpha、红、绿、蓝各 8 位定义的 PixelDataFormat。 |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | 获取具有指定每样本位数的 BGRA 索引颜色。 |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | 获取为每种颜色 1 位索引定义的 PixelDataFormat。 |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | 获取为每种颜色 2 位索引定义的 PixelDataFormat。 |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | 获取为每种颜色 4 位索引定义的 PixelDataFormat。 |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | 获取为每种颜色 8 位索引定义的 PixelDataFormat。 |
| [getRgba(int bitsPerSample)](#getRgba-int-) | 获取具有指定每样本位数的 RGBA 颜色。 |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | 获取具有指定每样本位数的 RGBA 颜色。 |
| [getRgba32Bpp()](#getRgba32Bpp--) | 获取为每像素 32 位且 alpha、红、绿、蓝各 8 位定义的 PixelDataFormat。 |
| [getRgba64Bpp()](#getRgba64Bpp--) | 获取为每像素 64 位且 alpha、红、绿、蓝各 16 位定义的 [PixelDataFormat](../../com.aspose.psd/pixeldataformat)。 |
| [getYCbCr()](#getYCbCr--) | 获取为每像素 24 位且亮度、蓝差、红差各 8 位色度分量定义的 PixelDataFormat。 |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | 获取具有指定每样本位数的 YCbCr 颜色。 |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | 获取具有指定每样本位数的 YCbCr 颜色。 |
| [getYcck()](#getYcck--) | 获取为每像素 32 位且每个亮度、蓝差、红差和黑色色度分量各为 8 位的 PixelDataFormat。 |
| [getYcck(int bitsPerSample)](#getYcck-int-) | 获取具有指定每样本位数的 YCCK 颜色。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isIndexed_internalized()](#isIndexed-internalized--) | 获取指示此实例是否为索引的值。 |
| [newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)](#newPixelDataFormat-internalized-int---int-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | 返回两个 PixelDataFormat 类相等的结果。 |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | 返回两个 PixelDataFormat 类不相等的结果。 |
| [toString()](#toString--) | 返回 一个  System.String  表示此实例。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的  System.Object  是否等于此实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 System.Object。 |

**Returns:**
布尔 - 如果指定的 System.Object 等于此实例，则为 true；否则为 false。
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


获取具有指定每样本位数的 BGR 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGR color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


获取具有指定每样本位数的 BGRA 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取每像素位数。

**Returns:**
int - 每像素的位数。
### getCaption() {#getCaption--}
```
public String getCaption()
```


获取像素数据格式的标题。

**Returns:**
java.lang.String
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


获取每个通道的位计数。

**Returns:**
int[] - 通道位数。
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


获取通道数。

**Returns:**
int - 通道数量。
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


获取具有指定每样本位数的 CIE Lab 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerL | int | L 通道的位数。 |
| bitsPerA | int | A 通道的位数。 |
| bitsPerB | int | B 通道的位数。 |

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


获取为每像素 32 位且每种青色、品红、黄色和黑色各 8 位定义的 PixelDataFormat。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


获取具有指定每样本位数的 CMYK 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


获取具有指定每样本位数的 CMYK 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerCyanChannel | int | 青色通道的位数。 |
| bitsPerMagentaChannel | int | 品红通道的位数。 |
| bitsPerYellowChannel | int | 黄色通道的位数。 |
| bitsPerKeyChannel | int | 关键通道的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk16() {#getCmyk16--}
```
public static PixelDataFormat getCmyk16()
```


获取为每像素 64 位且每种青色、品红、黄色和黑色各 16 位定义的 [PixelDataFormat](../../com.aspose.psd/pixeldataformat)。

值：该 [PixelDataFormat](../../com.aspose.psd/pixeldataformat) 定义为每像素 64 位，每种青色、品红、黄色和黑色各 16 位。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


获取 acmyk。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


获取具有指定每样本位数的 CMYKA 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerCyanChannel | int | 青色通道的位数。 |
| bitsPerMagentaChannel | int | 品红通道的位数。 |
| bitsPerYellowChannel | int | 黄色通道的位数。 |
| bitsPerKeyChannel | int | 关键通道的位数。 |
| bitsPerAlphaChannel | int | Alpha 通道的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyka16() {#getCmyka16--}
```
public static PixelDataFormat getCmyka16()
```


获取 acmyk。

值：该 [PixelDataFormat](../../com.aspose.psd/pixeldataformat) 定义为每像素 80 位，每种 alpha、青色、品红、黄色和黑色各 16 位。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getGrayscale() {#getGrayscale--}
```
public static PixelDataFormat getGrayscale()
```


获取为每像素 8 位且 8 位表示 0-255 区间内灰度强度定义的 PixelDataFormat。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


获取具有指定每样本位数的灰度颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


获取为每像素 16 位且 8 位表示 0-255 区间内灰度强度并附加 8 位 alpha 分量定义的 PixelDataFormat。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


获取具有指定每样本位数的灰度 Alpha 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


获取具有指定每样本位数的灰度 Alpha 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |
| alphaChannelBits | int | alpha 通道中每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleFloat32_internalized() {#getGrayscaleFloat32-internalized--}
```
public static PixelDataFormat getGrayscaleFloat32_internalized()
```


获取为每像素 32 位且以浮点格式表示灰度强度定义的 [PixelDataFormat](../../com.aspose.psd/pixeldataformat)。

值：该 [PixelDataFormat](../../com.aspose.psd/pixeldataformat) 定义为每像素 32 位，表示以浮点格式的灰度强度。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


获取像素格式。

**Returns:**
int - 像素格式。
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


获取具有指定每样本位数的 RGB 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


获取具有指定每样本位数的 RGB 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerRedChannel | int | Red 通道的位数。 |
| bitsPerGreenChannel | int | Green 通道的位数。 |
| bitsPerBlueChannel | int | Blue 通道的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


获取为每像素 16 位且红、绿、蓝各 5 位、未定义 alpha 的 PixelDataFormat。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


获取为每像素 16 位且红 5 位、绿 6 位、蓝 5 位、未定义 alpha 的 PixelDataFormat。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


获取为每像素 24 位且 alpha、红、绿、蓝各 8 位、未定义 alpha 的 PixelDataFormat。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


获取为每像素 24 位且 alpha、红、绿、蓝各 8 位、未定义 alpha 的 PixelDataFormat。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


获取为每像素 32 位且 alpha、红、绿、蓝各 8 位定义的 PixelDataFormat。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


获取具有指定每样本位数的 BGRA 索引颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


获取定义为每种颜色 1 位索引的  PixelDataFormat。索引像素数据存储旨在在使用调色板的所有地方允许数据的存储和检索。使用时需谨慎，因为可能需要将调色板从一种转换为另一种，或将 RGBA 转换为索引颜色模型。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 1 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


获取定义为每种颜色 2 位索引的  PixelDataFormat。索引像素数据存储旨在在使用调色板的所有地方允许数据的存储和检索。使用时需谨慎，因为可能需要将调色板从一种转换为另一种，或将 RGBA 转换为索引颜色模型。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 2 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


获取定义为每种颜色 4 位索引的  PixelDataFormat。索引像素数据存储旨在在使用调色板的所有地方允许数据的存储和检索。使用时需谨慎，因为可能需要将调色板从一种转换为另一种，或将 RGBA 转换为索引颜色模型。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 4 bit per color.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


获取定义为每种颜色 8 位索引的  PixelDataFormat。索引像素数据存储旨在在使用调色板的所有地方允许数据的存储和检索。使用时需谨慎，因为可能需要将调色板从一种转换为另一种，或将 RGBA 转换为索引颜色模型。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 8 bit per color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


获取具有指定每样本位数的 RGBA 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


获取具有指定每样本位数的 RGBA 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerRedChannel | int | Red 通道的位数。 |
| bitsPerGreenChannel | int | Green 通道的位数。 |
| bitsPerBlueChannel | int | Blue 通道的位数。 |
| bitsPerAlphaChannel | int | Alpha 通道的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


获取为每像素 32 位且 alpha、红、绿、蓝各 8 位定义的 PixelDataFormat。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgba64Bpp() {#getRgba64Bpp--}
```
public static PixelDataFormat getRgba64Bpp()
```


获取为每像素 64 位且 alpha、红、绿、蓝各 16 位定义的 [PixelDataFormat](../../com.aspose.psd/pixeldataformat)。

值：该 [PixelDataFormat](../../com.aspose.psd/pixeldataformat) 定义为每像素 64 位，每种 alpha、红色、绿色和蓝色各 16 位。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


获取为每像素 24 位且亮度、蓝差、红差各 8 位色度分量定义的 PixelDataFormat。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


获取具有指定每样本位数的 YCbCr 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


获取具有指定每样本位数的 YCbCr 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerY | int | Y 通道的位数。 |
| bitsPerCb | int | Cb 通道的位数。 |
| bitsPerCr | int | Cr 通道的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


获取为每像素 32 位且每个亮度、蓝差、红差和黑色色度分量各为 8 位的 PixelDataFormat。

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


获取具有指定每样本位数的 YCCK 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCCK color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和诸如哈希表之类的数据结构。
### isIndexed_internalized() {#isIndexed-internalized--}
```
public final boolean isIndexed_internalized()
```


获取指示此实例是否为索引的值。

值：  true  如果此实例已索引；否则，  false 。

**Returns:**
boolean - 指示此实例是否已索引的值。
### newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption) {#newPixelDataFormat-internalized-int---int-java.lang.String-}
```
public static PixelDataFormat newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| channelBits | int[] |  |
| pixelFormat | int |  |
| 标题 | java.lang.String |  |

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


返回两个 PixelDataFormat 类相等的结果。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 第一个要比较的  PixelDataFormat  。 |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 第二个要比较的  PixelDataFormat  。 |

**Returns:**
boolean - 如果  pixelFormat1  和  pixelFormat2  都包含相等的数据，或两个参数均为 null，则为 True。
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


返回两个 PixelDataFormat 类不相等的结果。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 第一个要比较的  PixelDataFormat  。 |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 第二个要比较的  PixelDataFormat  。 |

**Returns:**
boolean - 如果  pixelFormat1  和  pixelFormat2  包含不相等的数据，或其中一个参数为 null，则为 True。
### toString() {#toString--}
```
public String toString()
```


返回 一个  System.String  表示此实例。

**Returns:**
java.lang.String - 一个  System.String  表示此实例。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

