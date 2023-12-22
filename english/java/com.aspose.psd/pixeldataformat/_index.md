---
title: PixelDataFormat
second_title: Aspose.PSD for Java API Reference
description: The pixel data format.
type: docs
weight: 80
url: /java/com.aspose.psd/pixeldataformat/
---

**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

The pixel data format. This is an immutable object.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified  System.Object  is equal to this instance. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Gets BGR color with a specified number of bits per sample. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Gets BGRA color with a specified number of bits per sample. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the bits per pixel. |
| [getCaption()](#getCaption--) | Gets the pixel data format caption. |
| [getChannelBits()](#getChannelBits--) | Gets the bits count for each channel. |
| [getChannelsCount()](#getChannelsCount--) | Gets the channels count. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Gets CIE Lab color with a specified number of bits per sample. |
| [getClass()](#getClass--) |  |
| [getCmyk()](#getCmyk--) | Gets the  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Gets CMYK color with a specified number of bits per sample. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Gets CMYK color with a specified number of bits per sample. |
| [getCmyk16()](#getCmyk16--) | Gets the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 64 bits per pixel with 16 bits for each of the cyan, magenta, yellow and black. |
| [getCmyka()](#getCmyka--) | Gets the acmyk. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Gets CMYKA color with a specified number of bits per sample. |
| [getCmyka16()](#getCmyka16--) | Gets the acmyk. |
| [getGrayscale()](#getGrayscale--) | Gets the  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Gets Grayscale color with a specified number of bits per sample. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Gets the  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Gets GrayscaleAlpha color with a specified number of bits per sample. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Gets GrayscaleAlpha color with a specified number of bits per sample. |
| [getGrayscaleFloat32_internalized()](#getGrayscaleFloat32-internalized--) | Gets the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format. |
| [getPixelFormat()](#getPixelFormat--) | Gets the pixel format. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Gets RGB color with a specified number of bits per sample. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Gets RGB color with a specified number of bits per sample. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Gets the  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Gets the  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Gets the  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Gets the  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined. |
| [getRgb32Bpp()](#getRgb32Bpp--) | Gets the  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Gets BGRA indexed color with a specified number of bits per sample. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Gets the  PixelDataFormat  defined for indexed 1 bit per color. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Gets the  PixelDataFormat  defined for indexed 2 bit per color. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Gets the  PixelDataFormat  defined for indexed 4 bit per color. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Gets the  PixelDataFormat  defined for indexed 8 bit per color. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Gets RGBA color with a specified number of bits per sample. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Gets RGBA color with a specified number of bits per sample. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Gets the  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue. |
| [getRgba64Bpp()](#getRgba64Bpp--) | Gets the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 64 bits per pixel with 16 bits for each of the alpha, red, green and blue. |
| [getYCbCr()](#getYCbCr--) | Gets the  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Gets YCbCr color with a specified number of bits per sample. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Gets YCbCr color with a specified number of bits per sample. |
| [getYcck()](#getYcck--) | Gets the  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Gets YCCK color with a specified number of bits per sample. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [isIndexed_internalized()](#isIndexed-internalized--) | Gets a value indicating whether this instance is indexed. |
| [newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)](#newPixelDataFormat-internalized-int---int-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Returns result of equality for two  PixelDataFormat  classes. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Returns result of non-equality for two  PixelDataFormat  classes. |
| [toString()](#toString--) | Returns a  System.String  that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified  System.Object  is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The  System.Object  to compare with this instance. |

**Returns:**
boolean -  true  if the specified  System.Object  is equal to this instance; otherwise,  false .
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Gets BGR color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGR color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Gets BGRA color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the bits per pixel.

**Returns:**
int - The bits per pixel.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Gets the pixel data format caption.

**Returns:**
java.lang.String
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Gets the bits count for each channel.

**Returns:**
int[] - The channel bits.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Gets the channels count.

**Returns:**
int - The channels count.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Gets CIE Lab color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerL | int | The number of bits per L channel. |
| bitsPerA | int | The number of bits per A channel. |
| bitsPerB | int | The number of bits per B channel. |

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


Gets the  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Gets CMYK color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Gets CMYK color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerCyanChannel | int | The number of bits per Cyan channel. |
| bitsPerMagentaChannel | int | The number of bits per Magenta channel. |
| bitsPerYellowChannel | int | The number of bits per Yellow channel. |
| bitsPerKeyChannel | int | The number of bits per Key channel. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk16() {#getCmyk16--}
```
public static PixelDataFormat getCmyk16()
```


Gets the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 64 bits per pixel with 16 bits for each of the cyan, magenta, yellow and black.

Value: The [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 64 bits per pixel with 16 bits for each of the cyan, magenta, yellow and black.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Gets the acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Gets CMYKA color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerCyanChannel | int | The number of bits per Cyan channel. |
| bitsPerMagentaChannel | int | The number of bits per Magenta channel. |
| bitsPerYellowChannel | int | The number of bits per Yellow channel. |
| bitsPerKeyChannel | int | The number of bits per Key channel. |
| bitsPerAlphaChannel | int | The number of bits per Alpha channel. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyka16() {#getCmyka16--}
```
public static PixelDataFormat getCmyka16()
```


Gets the acmyk.

Value: The [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 80 bits per pixel with 16 bits for each of the alpha, cyan, magenta, yellow and black.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getGrayscale() {#getGrayscale--}
```
public static PixelDataFormat getGrayscale()
```


Gets the  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Gets Grayscale color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Gets the  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Gets GrayscaleAlpha color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Gets GrayscaleAlpha color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |
| alphaChannelBits | int | The number of bits per sample in the alpha channel. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleFloat32_internalized() {#getGrayscaleFloat32-internalized--}
```
public static PixelDataFormat getGrayscaleFloat32_internalized()
```


Gets the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.

Value: The [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Gets the pixel format.

**Returns:**
int - The pixel format.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Gets RGB color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Gets RGB color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerRedChannel | int | The number of bits per Red channel. |
| bitsPerGreenChannel | int | The number of bits per Green channel. |
| bitsPerBlueChannel | int | The number of bits per Blue channel. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Gets the  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Gets the  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Gets the  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Gets the  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Gets the  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Gets BGRA indexed color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Gets the  PixelDataFormat  defined for indexed 1 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 1 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Gets the  PixelDataFormat  defined for indexed 2 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 2 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Gets the  PixelDataFormat  defined for indexed 4 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 4 bit per color.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Gets the  PixelDataFormat  defined for indexed 8 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 8 bit per color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Gets RGBA color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Gets RGBA color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerRedChannel | int | The number of bits per Red channel. |
| bitsPerGreenChannel | int | The number of bits per Green channel. |
| bitsPerBlueChannel | int | The number of bits per Blue channel. |
| bitsPerAlphaChannel | int | The number of bits per Alpha channel. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Gets the  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgba64Bpp() {#getRgba64Bpp--}
```
public static PixelDataFormat getRgba64Bpp()
```


Gets the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 64 bits per pixel with 16 bits for each of the alpha, red, green and blue.

Value: The [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 64 bits per pixel with 16 bits for each of the alpha, red, green and blue.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Gets the  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Gets YCbCr color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Gets YCbCr color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerY | int | The number of bits per Y channel. |
| bitsPerCb | int | The number of bits per Cb channel. |
| bitsPerCr | int | The number of bits per Cr channel. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Gets the  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Gets YCCK color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCCK color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
### isIndexed_internalized() {#isIndexed-internalized--}
```
public final boolean isIndexed_internalized()
```


Gets a value indicating whether this instance is indexed.

Value:  true  if this instance is indexed; otherwise,  false .

**Returns:**
boolean - a value indicating whether this instance is indexed.
### newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption) {#newPixelDataFormat-internalized-int---int-java.lang.String-}
```
public static PixelDataFormat newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)
```




**Parameters:**
| Parameter | Type | Description |
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


Returns result of equality for two  PixelDataFormat  classes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | The first  PixelDataFormat  to compare. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | The second  PixelDataFormat  to compare. |

**Returns:**
boolean - True if both  pixelFormat1  and  pixelFormat2  contain equal data or both parameters are null.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Returns result of non-equality for two  PixelDataFormat  classes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | The first  PixelDataFormat  to compare. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | The second  PixelDataFormat  to compare. |

**Returns:**
boolean - True if both  pixelFormat1  and  pixelFormat2  contain non-equal data or one of the parameters is null.
### toString() {#toString--}
```
public String toString()
```


Returns a  System.String  that represents this instance.

**Returns:**
java.lang.String - A  System.String  that represents this instance.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

