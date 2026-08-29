---
title: "PixelDataFormat"
second_title: "Java için Aspose.PSD API Referansı"
description: "Piksel veri biçimi."
type: docs
weight: 80
url: /tr/java/com.aspose.psd/pixeldataformat/
---

**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

Piksel veri formatı. Bu değiştirilemez bir nesnedir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen  System.Object  bu örnek ile eşit olup olmadığını belirler. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Örnek başına belirtilen bit sayısı ile BGR rengini alır. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Örnek başına belirtilen bit sayısı ile BGRA rengini alır. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Piksel başına bit sayısını alır. |
| [getCaption()](#getCaption--) | Piksel veri formatı başlığını alır. |
| [getChannelBits()](#getChannelBits--) | Her kanal için bit sayısını alır. |
| [getChannelsCount()](#getChannelsCount--) | Kanal sayısını alır. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Belirtilen örnek başına bit sayısıyla CIE Lab rengini alır. |
| [getClass()](#getClass--) |  |
| [getCmyk()](#getCmyk--) | 32 bit piksel başına, her bir camgöbeği, macenta, sarı ve siyah için 8 bit tanımlı  PixelDataFormat  alır. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Belirtilen örnek başına bit sayısıyla CMYK rengini alır. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Belirtilen örnek başına bit sayısıyla CMYK rengini alır. |
| [getCmyk16()](#getCmyk16--) | 64 bit piksel başına, her bir camgöbeği, macenta, sarı ve siyah için 16 bit tanımlı [PixelDataFormat](../../com.aspose.psd/pixeldataformat) alır. |
| [getCmyka()](#getCmyka--) | acmyk'yi alır. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Belirtilen örnek başına bit sayısıyla CMYKA rengini alır. |
| [getCmyka16()](#getCmyka16--) | acmyk'yi alır. |
| [getGrayscale()](#getGrayscale--) | 0-255 aralığında gri ton yoğunluğunu temsil eden 8 bit ile 8 bit piksel başına tanımlı  PixelDataFormat  alır. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Belirtilen örnek başına bit sayısıyla Gri ton rengini alır. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | 0-255 aralığında gri ton yoğunluğunu temsil eden 8 bit ve ek 8 bit alfa bileşeni ile 16 bit piksel başına tanımlı  PixelDataFormat  alır. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Belirtilen örnek başına bit sayısıyla GriTonAlfa rengini alır. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Belirtilen örnek başına bit sayısıyla GriTonAlfa rengini alır. |
| [getGrayscaleFloat32_internalized()](#getGrayscaleFloat32-internalized--) | 32 bit piksel başına, gri ton yoğunluğunu kayan nokta biçiminde temsil eden [PixelDataFormat](../../com.aspose.psd/pixeldataformat) alır. |
| [getPixelFormat()](#getPixelFormat--) | Piksel biçimini alır. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Belirtilen örnek başına bit sayısıyla RGB rengini alır. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Belirtilen örnek başına bit sayısıyla RGB rengini alır. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | 16 bit piksel başına, kırmızı, yeşil ve mavi için her biri 5 bit tanımlı, alfa tanımlı olmayan  PixelDataFormat  alır. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | 16 bit piksel başına, kırmızı için 5 bit, yeşil için 6 bit ve mavi için 5 bit tanımlı, alfa tanımlı olmayan  PixelDataFormat  alır. |
| [getRgb24Bpp()](#getRgb24Bpp--) | 24 bit piksel başına, alfa, kırmızı, yeşil ve mavi için her biri 8 bit tanımlı, alfa tanımlı olmayan  PixelDataFormat  alır. |
| [getRgb24BppPng()](#getRgb24BppPng--) | 24 bit piksel başına, alfa, kırmızı, yeşil ve mavi için her biri 8 bit tanımlı, alfa tanımlı olmayan  PixelDataFormat  alır. |
| [getRgb32Bpp()](#getRgb32Bpp--) | 32 bit piksel başına, alfa, kırmızı, yeşil ve mavi için her biri 8 bit tanımlı  PixelDataFormat  alır. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Belirtilen örnek başına bit sayısıyla BGRA indeksli rengini alır. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Renk başına indeksli 1 bit tanımlı  PixelDataFormat  alır. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Renk başına indeksli 2 bit tanımlı  PixelDataFormat  alır. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Renk başına indeksli 4 bit tanımlı  PixelDataFormat  alır. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Renk başına indeksli 8 bit tanımlı  PixelDataFormat  alır. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Belirtilen örnek başına bit sayısıyla RGBA rengini alır. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Belirtilen örnek başına bit sayısıyla RGBA rengini alır. |
| [getRgba32Bpp()](#getRgba32Bpp--) | 32 bit piksel başına, alfa, kırmızı, yeşil ve mavi için her biri 8 bit tanımlı  PixelDataFormat  alır. |
| [getRgba64Bpp()](#getRgba64Bpp--) | 64 bit piksel başına alfa, kırmızı, yeşil ve mavi için 16 bit tanımlı [PixelDataFormat](../../com.aspose.psd/pixeldataformat) alır. |
| [getYCbCr()](#getYCbCr--) | 24 bit piksel başına luma, mavi-fark ve kırmızı-fark renk doygunluğu bileşenleri için 8 bit tanımlı  PixelDataFormat  alır. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Belirtilen örnek başına bit sayısı ile YCbCr rengini alır. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Belirtilen örnek başına bit sayısı ile YCbCr rengini alır. |
| [getYcck()](#getYcck--) | 32 bit piksel başına luma, mavi-fark, kırmızı-fark ve siyah renk doygunluğu bileşenleri için 8 bit tanımlı  PixelDataFormat  alır. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Belirtilen örnek başına bit sayısı ile YCCK rengini alır. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
| [isIndexed_internalized()](#isIndexed-internalized--) | Bu örneğin indeksli olup olmadığını gösteren bir değeri alır. |
| [newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)](#newPixelDataFormat-internalized-int---int-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | İki  PixelDataFormat  sınıfı için eşitlik sonucunu döndürür. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | İki  PixelDataFormat  sınıfı için eşitsizlik sonucunu döndürür. |
| [toString()](#toString--) | Bu örneği temsil eden bir  System.String  döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen  System.Object  bu örnek ile eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnek ile karşılaştırılacak System.Object. |

**Returns:**
boolean - belirtilen System.Object bu örnek ile eşitse true; aksi takdirde false.
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Örnek başına belirtilen bit sayısı ile BGR rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGR color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Örnek başına belirtilen bit sayısı ile BGRA rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Piksel başına bit sayısını alır.

**Returns:**
int - Piksel başına bitler.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Piksel veri formatı başlığını alır.

**Returns:**
java.lang.String
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Her kanal için bit sayısını alır.

**Returns:**
int[] - Kanal bitleri.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Kanal sayısını alır.

**Returns:**
int - Kanal sayısı.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Belirtilen örnek başına bit sayısıyla CIE Lab rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerL | int | L kanalı başına bit sayısı. |
| bitsPerA | int | A kanalı başına bit sayısı. |
| bitsPerB | int | B kanalı başına bit sayısı. |

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


32 bit piksel başına, her bir camgöbeği, macenta, sarı ve siyah için 8 bit tanımlı  PixelDataFormat  alır.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Belirtilen örnek başına bit sayısıyla CMYK rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Belirtilen örnek başına bit sayısıyla CMYK rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerCyanChannel | int | Cyan kanalı başına bit sayısı. |
| bitsPerMagentaChannel | int | Magenta kanalı başına bit sayısı. |
| bitsPerYellowChannel | int | Yellow kanalı başına bit sayısı. |
| bitsPerKeyChannel | int | Key kanalındaki bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk16() {#getCmyk16--}
```
public static PixelDataFormat getCmyk16()
```


64 bit piksel başına, her bir camgöbeği, macenta, sarı ve siyah için 16 bit tanımlı [PixelDataFormat](../../com.aspose.psd/pixeldataformat) alır.

Değer: 64 bit/piksel için tanımlanan [PixelDataFormat](../../com.aspose.psd/pixeldataformat), camgöbeği, macenta, sarı ve siyah için her biri 16 bit olmak üzere.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


acmyk'yi alır.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Belirtilen örnek başına bit sayısıyla CMYKA rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerCyanChannel | int | Cyan kanalı başına bit sayısı. |
| bitsPerMagentaChannel | int | Magenta kanalı başına bit sayısı. |
| bitsPerYellowChannel | int | Yellow kanalı başına bit sayısı. |
| bitsPerKeyChannel | int | Key kanalındaki bit sayısı. |
| bitsPerAlphaChannel | int | Alfa kanalındaki bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyka16() {#getCmyka16--}
```
public static PixelDataFormat getCmyka16()
```


acmyk'yi alır.

Değer: 80 bit/piksel için tanımlanan [PixelDataFormat](../../com.aspose.psd/pixeldataformat), alfa, camgöbeği, macenta, sarı ve siyah için her biri 16 bit olmak üzere.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getGrayscale() {#getGrayscale--}
```
public static PixelDataFormat getGrayscale()
```


0-255 aralığında gri ton yoğunluğunu temsil eden 8 bit ile 8 bit piksel başına tanımlı  PixelDataFormat  alır.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Belirtilen örnek başına bit sayısıyla Gri ton rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


0-255 aralığında gri ton yoğunluğunu temsil eden 8 bit ve ek 8 bit alfa bileşeni ile 16 bit piksel başına tanımlı  PixelDataFormat  alır.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Belirtilen örnek başına bit sayısıyla GriTonAlfa rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Belirtilen örnek başına bit sayısıyla GriTonAlfa rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |
| alphaChannelBits | int | Alfa kanalındaki örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleFloat32_internalized() {#getGrayscaleFloat32-internalized--}
```
public static PixelDataFormat getGrayscaleFloat32_internalized()
```


32 bit piksel başına, gri ton yoğunluğunu kayan nokta biçiminde temsil eden [PixelDataFormat](../../com.aspose.psd/pixeldataformat) alır.

Değer: 32 bit/piksel için tanımlanan [PixelDataFormat](../../com.aspose.psd/pixeldataformat), kayan nokta formatında gri ton yoğunluğunu temsil eder.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Piksel biçimini alır.

**Returns:**
int - Piksel formatı.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Belirtilen örnek başına bit sayısıyla RGB rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Belirtilen örnek başına bit sayısıyla RGB rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerRedChannel | int | Kırmızı kanalındaki bit sayısı. |
| bitsPerGreenChannel | int | Yeşil kanalındaki bit sayısı. |
| bitsPerBlueChannel | int | Mavi kanalındaki bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


16 bit piksel başına, kırmızı, yeşil ve mavi için her biri 5 bit tanımlı, alfa tanımlı olmayan  PixelDataFormat  alır.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


16 bit piksel başına, kırmızı için 5 bit, yeşil için 6 bit ve mavi için 5 bit tanımlı, alfa tanımlı olmayan  PixelDataFormat  alır.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


24 bit piksel başına, alfa, kırmızı, yeşil ve mavi için her biri 8 bit tanımlı, alfa tanımlı olmayan  PixelDataFormat  alır.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


24 bit piksel başına, alfa, kırmızı, yeşil ve mavi için her biri 8 bit tanımlı, alfa tanımlı olmayan  PixelDataFormat  alır.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


32 bit piksel başına, alfa, kırmızı, yeşil ve mavi için her biri 8 bit tanımlı  PixelDataFormat  alır.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Belirtilen örnek başına bit sayısıyla BGRA indeksli rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


1 bit renk başına indeksli olarak tanımlanan PixelDataFormat'ı alır. İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolama ve geri almayı sağlamak için tasarlanmıştır. Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerekebilir.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 1 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


2 bit renk başına indeksli olarak tanımlanan PixelDataFormat'ı alır. İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolama ve geri almayı sağlamak için tasarlanmıştır. Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerekebilir.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 2 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


4 bit renk başına indeksli olarak tanımlanan PixelDataFormat'ı alır. İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolama ve geri almayı sağlamak için tasarlanmıştır. Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerekebilir.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 4 bit per color.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


8 bit renk başına indeksli olarak tanımlanan PixelDataFormat'ı alır. İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolama ve geri almayı sağlamak için tasarlanmıştır. Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerekebilir.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 8 bit per color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Belirtilen örnek başına bit sayısıyla RGBA rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Belirtilen örnek başına bit sayısıyla RGBA rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerRedChannel | int | Kırmızı kanalındaki bit sayısı. |
| bitsPerGreenChannel | int | Yeşil kanalındaki bit sayısı. |
| bitsPerBlueChannel | int | Mavi kanalındaki bit sayısı. |
| bitsPerAlphaChannel | int | Alfa kanalındaki bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


32 bit piksel başına, alfa, kırmızı, yeşil ve mavi için her biri 8 bit tanımlı  PixelDataFormat  alır.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgba64Bpp() {#getRgba64Bpp--}
```
public static PixelDataFormat getRgba64Bpp()
```


64 bit piksel başına alfa, kırmızı, yeşil ve mavi için 16 bit tanımlı [PixelDataFormat](../../com.aspose.psd/pixeldataformat) alır.

Değer: 64 bit/piksel için tanımlanan [PixelDataFormat](../../com.aspose.psd/pixeldataformat), alfa, kırmızı, yeşil ve mavi için her biri 16 bit olmak üzere.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


24 bit piksel başına luma, mavi-fark ve kırmızı-fark renk doygunluğu bileşenleri için 8 bit tanımlı  PixelDataFormat  alır.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Belirtilen örnek başına bit sayısı ile YCbCr rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Belirtilen örnek başına bit sayısı ile YCbCr rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerY | int | Y kanalındaki bit sayısı. |
| bitsPerCb | int | Cb kanalındaki bit sayısı. |
| bitsPerCr | int | Cr kanalındaki bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


32 bit piksel başına luma, mavi-fark, kırmızı-fark ve siyah renk doygunluğu bileşenleri için 8 bit tanımlı  PixelDataFormat  alır.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Belirtilen örnek başına bit sayısı ile YCCK rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCCK color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir karma kodu döndürür.

**Returns:**
int - Bu örnek için bir karma kodu, hash algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygun.
### isIndexed_internalized() {#isIndexed-internalized--}
```
public final boolean isIndexed_internalized()
```


Bu örneğin indeksli olup olmadığını gösteren bir değeri alır.

Değer:  true  bu örnek indekslenmişse; aksi takdirde,  false .

**Returns:**
boolean - bu örneğin indekslenip indekslenmediğini gösteren bir değer.
### newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption) {#newPixelDataFormat-internalized-int---int-java.lang.String-}
```
public static PixelDataFormat newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


İki  PixelDataFormat  sınıfı için eşitlik sonucunu döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | İlk  PixelDataFormat  karşılaştırılacak. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | İkinci  PixelDataFormat  karşılaştırılacak. |

**Returns:**
boolean - True eğer hem  pixelFormat1  hem de  pixelFormat2  eşit veri içeriyorsa veya her iki parametre de null ise.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


İki  PixelDataFormat  sınıfı için eşitsizlik sonucunu döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | İlk  PixelDataFormat  karşılaştırılacak. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | İkinci  PixelDataFormat  karşılaştırılacak. |

**Returns:**
boolean - True eğer hem  pixelFormat1  hem de  pixelFormat2  eşit olmayan veri içeriyorsa veya parametrelerden biri null ise.
### toString() {#toString--}
```
public String toString()
```


Bu örneği temsil eden bir  System.String  döndürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir System.String.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

