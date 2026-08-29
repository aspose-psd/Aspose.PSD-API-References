---
title: "PixelDataFormat"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Het pixelgegevensformaat."
type: docs
weight: 80
url: /nl/java/com.aspose.psd/pixeldataformat/
---

**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

Het pixelgegevensformaat. Dit is een onveranderlijk object.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of het opgegeven  System.Object  gelijk is aan deze instantie. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Haalt BGR-kleur op met een gespecificeerd aantal bits per monster. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Haalt BGRA-kleur op met een gespecificeerd aantal bits per monster. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Haalt het aantal bits per pixel op. |
| [getCaption()](#getCaption--) | Haalt de bijschrift van het pixelgegevensformaat op. |
| [getChannelBits()](#getChannelBits--) | Haalt het aantal bits per kanaal op. |
| [getChannelsCount()](#getChannelsCount--) | Haalt het aantal kanalen op. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Haalt CIE Lab-kleur op met een gespecificeerd aantal bits per monster. |
| [getClass()](#getClass--) |  |
| [getCmyk()](#getCmyk--) | Haalt de  PixelDataFormat  op die is gedefinieerd voor 32 bits per pixel met 8 bits voor elk van cyaan, magenta, geel en zwart. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Haalt CMYK-kleur op met een gespecificeerd aantal bits per monster. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Haalt CMYK-kleur op met een gespecificeerd aantal bits per monster. |
| [getCmyk16()](#getCmyk16--) | Haalt de [PixelDataFormat](../../com.aspose.psd/pixeldataformat) op die is gedefinieerd voor 64 bits per pixel met 16 bits voor elk van cyaan, magenta, geel en zwart. |
| [getCmyka()](#getCmyka--) | Haalt de acmyk op. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Haalt CMYKA-kleur op met een gespecificeerd aantal bits per monster. |
| [getCmyka16()](#getCmyka16--) | Haalt de acmyk op. |
| [getGrayscale()](#getGrayscale--) | Haalt de  PixelDataFormat  op die is gedefinieerd voor 8 bits per pixel met 8 bits die de grijswaardenintensiteit weergeven in het interval 0-255. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Haalt Grayscale-kleur op met een gespecificeerd aantal bits per monster. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Haalt de  PixelDataFormat  op die is gedefinieerd voor 16 bits per pixel met 8 bits die de grijswaardenintensiteit weergeven in het interval 0-255 en een extra 8‑bit alpha component. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Haalt GrayscaleAlpha-kleur op met een gespecificeerd aantal bits per monster. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Haalt GrayscaleAlpha-kleur op met een gespecificeerd aantal bits per monster. |
| [getGrayscaleFloat32_internalized()](#getGrayscaleFloat32-internalized--) | Haalt de [PixelDataFormat](../../com.aspose.psd/pixeldataformat) op die is gedefinieerd voor 32 bits per pixel die de grijswaardenintensiteit weergeven in zwevendekommagetalformaat. |
| [getPixelFormat()](#getPixelFormat--) | Haalt het pixelformaat op. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Haalt RGB-kleur op met een gespecificeerd aantal bits per monster. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Haalt RGB-kleur op met een gespecificeerd aantal bits per monster. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Haalt de  PixelDataFormat  op die is gedefinieerd voor 16 bits per pixel met 5 bits voor elk van rood, groen en blauw, alpha is niet gedefinieerd. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Haalt de  PixelDataFormat  op die is gedefinieerd voor 16 bits per pixel met 5 bits voor rood, 6 bits voor groen en 5 bits voor blauw, alpha is niet gedefinieerd. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Haalt de  PixelDataFormat  op die is gedefinieerd voor 24 bits per pixel met 8 bits voor elk van alpha, rood, groen en blauw, alpha is niet gedefinieerd. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Haalt de  PixelDataFormat  op die is gedefinieerd voor 24 bits per pixel met 8 bits voor elk van alpha, rood, groen en blauw, alpha is niet gedefinieerd. |
| [getRgb32Bpp()](#getRgb32Bpp--) | Haalt de  PixelDataFormat  op die is gedefinieerd voor 32 bits per pixel met 8 bits voor elk van alpha, rood, groen en blauw. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Haalt BGRA geïndexeerde kleur op met een opgegeven aantal bits per sample. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Haalt de  PixelDataFormat  op die is gedefinieerd voor geïndexeerde 1 bit per kleur. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Haalt de  PixelDataFormat  op die is gedefinieerd voor geïndexeerde 2 bit per kleur. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Haalt de  PixelDataFormat  op die is gedefinieerd voor geïndexeerde 4 bit per kleur. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Haalt de  PixelDataFormat  op die is gedefinieerd voor geïndexeerde 8 bit per kleur. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Haalt RGBA-kleur op met een opgegeven aantal bits per sample. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Haalt RGBA-kleur op met een opgegeven aantal bits per sample. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Haalt de  PixelDataFormat  op die is gedefinieerd voor 32 bits per pixel met 8 bits voor elk van alpha, rood, groen en blauw. |
| [getRgba64Bpp()](#getRgba64Bpp--) | Haalt de [PixelDataFormat](../../com.aspose.psd/pixeldataformat) op die is gedefinieerd voor 64 bits per pixel met 16 bits voor elk van de alfa, rood, groen en blauw. |
| [getYCbCr()](#getYCbCr--) | Haalt de  PixelDataFormat  op die is gedefinieerd voor 24 bits per pixel met 8 bits voor elk van de luma-, blauwverschil- en roodverschil chroma‑componenten. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Haalt YCbCr-kleur op met een opgegeven aantal bits per sample. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Haalt YCbCr-kleur op met een opgegeven aantal bits per sample. |
| [getYcck()](#getYcck--) | Haalt de  PixelDataFormat  op die is gedefinieerd voor 32 bits per pixel met 8 bits voor elk van de luma-, blauwverschil-, roodverschil- en zwart chroma‑componenten. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Haalt YCCK-kleur op met een opgegeven aantal bits per sample. |
| [hashCode()](#hashCode--) | Retourneert een hashcode voor dit exemplaar. |
| [isIndexed_internalized()](#isIndexed-internalized--) | Haalt een waarde op die aangeeft of deze instantie geïndexeerd is. |
| [newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)](#newPixelDataFormat-internalized-int---int-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Retourneert het resultaat van gelijkheid voor twee  PixelDataFormat  klassen. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Retourneert het resultaat van ongelijkheid voor twee  PixelDataFormat  klassen. |
| [toString()](#toString--) | Retourneert een  System.String  die deze instantie vertegenwoordigt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of het opgegeven  System.Object  gelijk is aan deze instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het  System.Object  om te vergelijken met dit exemplaar. |

**Returns:**
boolean -  true  als het opgegeven  System.Object  gelijk is aan deze instantie; anders,  false .
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Haalt BGR-kleur op met een gespecificeerd aantal bits per monster.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerSample | int | Het aantal bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGR color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Haalt BGRA-kleur op met een gespecificeerd aantal bits per monster.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerSample | int | Het aantal bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Haalt het aantal bits per pixel op.

**Returns:**
int - Het aantal bits per pixel.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Haalt de bijschrift van het pixelgegevensformaat op.

**Returns:**
java.lang.String
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Haalt het aantal bits per kanaal op.

**Returns:**
int[] - De kanaalbits.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Haalt het aantal kanalen op.

**Returns:**
int - Het aantal kanalen.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Haalt CIE Lab-kleur op met een gespecificeerd aantal bits per monster.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerL | int | Het aantal bits per L-kanaal. |
| bitsPerA | int | Het aantal bits per A-kanaal. |
| bitsPerB | int | Het aantal bits per B-kanaal. |

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


Haalt de  PixelDataFormat  op die is gedefinieerd voor 32 bits per pixel met 8 bits voor elk van cyaan, magenta, geel en zwart.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Haalt CMYK-kleur op met een gespecificeerd aantal bits per monster.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerSample | int | Het aantal bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Haalt CMYK-kleur op met een gespecificeerd aantal bits per monster.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerCyanChannel | int | Het aantal bits per cyaankanaal. |
| bitsPerMagentaChannel | int | Het aantal bits per magentakanaal. |
| bitsPerYellowChannel | int | Het aantal bits per geelkanaal. |
| bitsPerKeyChannel | int | Het aantal bits per keykanaal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk16() {#getCmyk16--}
```
public static PixelDataFormat getCmyk16()
```


Haalt de [PixelDataFormat](../../com.aspose.psd/pixeldataformat) op die is gedefinieerd voor 64 bits per pixel met 16 bits voor elk van cyaan, magenta, geel en zwart.

Waarde: De [PixelDataFormat](../../com.aspose.psd/pixeldataformat) gedefinieerd voor 64 bits per pixel met 16 bits voor elk van de cyaan, magenta, geel en zwart.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Haalt de acmyk op.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Haalt CMYKA-kleur op met een gespecificeerd aantal bits per monster.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerCyanChannel | int | Het aantal bits per cyaankanaal. |
| bitsPerMagentaChannel | int | Het aantal bits per magentakanaal. |
| bitsPerYellowChannel | int | Het aantal bits per geelkanaal. |
| bitsPerKeyChannel | int | Het aantal bits per keykanaal. |
| bitsPerAlphaChannel | int | Het aantal bits per alfacanaal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyka16() {#getCmyka16--}
```
public static PixelDataFormat getCmyka16()
```


Haalt de acmyk op.

Waarde: De [PixelDataFormat](../../com.aspose.psd/pixeldataformat) gedefinieerd voor 80 bits per pixel met 16 bits voor elk van de alfa, cyaan, magenta, geel en zwart.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getGrayscale() {#getGrayscale--}
```
public static PixelDataFormat getGrayscale()
```


Haalt de  PixelDataFormat  op die is gedefinieerd voor 8 bits per pixel met 8 bits die de grijswaardenintensiteit weergeven in het interval 0-255.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Haalt Grayscale-kleur op met een gespecificeerd aantal bits per monster.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerSample | int | Het aantal bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Haalt de  PixelDataFormat  op die is gedefinieerd voor 16 bits per pixel met 8 bits die de grijswaardenintensiteit weergeven in het interval 0-255 en een extra 8‑bit alpha component.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Haalt GrayscaleAlpha-kleur op met een gespecificeerd aantal bits per monster.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerSample | int | Het aantal bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Haalt GrayscaleAlpha-kleur op met een gespecificeerd aantal bits per monster.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerSample | int | Het aantal bits per sample. |
| alphaChannelBits | int | Het aantal bits per monster in het alfacanaal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleFloat32_internalized() {#getGrayscaleFloat32-internalized--}
```
public static PixelDataFormat getGrayscaleFloat32_internalized()
```


Haalt de [PixelDataFormat](../../com.aspose.psd/pixeldataformat) op die is gedefinieerd voor 32 bits per pixel die de grijswaardenintensiteit weergeven in zwevendekommagetalformaat.

Waarde: De [PixelDataFormat](../../com.aspose.psd/pixeldataformat) gedefinieerd voor 32 bits per pixel die de grijswaardenintensiteit weergeeft in zwevendekommagetalformaat

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Haalt het pixelformaat op.

**Returns:**
int - Het pixelformaat.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Haalt RGB-kleur op met een gespecificeerd aantal bits per monster.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerSample | int | Het aantal bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Haalt RGB-kleur op met een gespecificeerd aantal bits per monster.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerRedChannel | int | Het aantal bits per roodkanaal. |
| bitsPerGreenChannel | int | Het aantal bits per groenkanaal. |
| bitsPerBlueChannel | int | Het aantal bits per blauwkanaal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Haalt de  PixelDataFormat  op die is gedefinieerd voor 16 bits per pixel met 5 bits voor elk van rood, groen en blauw, alpha is niet gedefinieerd.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Haalt de  PixelDataFormat  op die is gedefinieerd voor 16 bits per pixel met 5 bits voor rood, 6 bits voor groen en 5 bits voor blauw, alpha is niet gedefinieerd.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Haalt de  PixelDataFormat  op die is gedefinieerd voor 24 bits per pixel met 8 bits voor elk van alpha, rood, groen en blauw, alpha is niet gedefinieerd.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Haalt de  PixelDataFormat  op die is gedefinieerd voor 24 bits per pixel met 8 bits voor elk van alpha, rood, groen en blauw, alpha is niet gedefinieerd.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Haalt de  PixelDataFormat  op die is gedefinieerd voor 32 bits per pixel met 8 bits voor elk van alpha, rood, groen en blauw.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Haalt BGRA geïndexeerde kleur op met een opgegeven aantal bits per sample.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerSample | int | Het aantal bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Haalt het  PixelDataFormat  op dat is gedefinieerd voor geïndexeerde 1 bit per kleur. De geïndexeerde pixelgegevensopslag is bedoeld om gegevensopslag en -ophaling overal waar het kleurenpalet wordt gebruikt mogelijk te maken. Gebruik met voorzichtigheid, omdat conversie van het ene palet naar het andere of van RGBA naar een geïndexeerd kleurenmodel vereist kan zijn.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 1 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Haalt het  PixelDataFormat  op dat is gedefinieerd voor geïndexeerde 2 bit per kleur. De geïndexeerde pixelgegevensopslag is bedoeld om gegevensopslag en -ophaling overal waar het kleurenpalet wordt gebruikt mogelijk te maken. Gebruik met voorzichtigheid, omdat conversie van het ene palet naar het andere of van RGBA naar een geïndexeerd kleurenmodel vereist kan zijn.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 2 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Haalt het  PixelDataFormat  op dat is gedefinieerd voor geïndexeerde 4 bit per kleur. De geïndexeerde pixelgegevensopslag is bedoeld om gegevensopslag en -ophaling overal waar het kleurenpalet wordt gebruikt mogelijk te maken. Gebruik met voorzichtigheid, omdat conversie van het ene palet naar het andere of van RGBA naar een geïndexeerd kleurenmodel vereist kan zijn.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 4 bit per color.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Haalt de  PixelDataFormat  op die is gedefinieerd voor geïndexeerde 8 bits per kleur. De geïndexeerde pixelgegevensopslag is bedoeld om gegevensopslag en -ophaling overal waar het kleurenpalet wordt gebruikt mogelijk te maken. Gebruik met voorzichtigheid, omdat conversie van het ene palet naar het andere of van RGBA naar een geïndexeerd kleurmodel vereist kan zijn.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 8 bit per color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Haalt RGBA-kleur op met een opgegeven aantal bits per sample.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerSample | int | Het aantal bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Haalt RGBA-kleur op met een opgegeven aantal bits per sample.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerRedChannel | int | Het aantal bits per roodkanaal. |
| bitsPerGreenChannel | int | Het aantal bits per groenkanaal. |
| bitsPerBlueChannel | int | Het aantal bits per blauwkanaal. |
| bitsPerAlphaChannel | int | Het aantal bits per alfacanaal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Haalt de  PixelDataFormat  op die is gedefinieerd voor 32 bits per pixel met 8 bits voor elk van alpha, rood, groen en blauw.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgba64Bpp() {#getRgba64Bpp--}
```
public static PixelDataFormat getRgba64Bpp()
```


Haalt de [PixelDataFormat](../../com.aspose.psd/pixeldataformat) op die is gedefinieerd voor 64 bits per pixel met 16 bits voor elk van de alfa, rood, groen en blauw.

Waarde: De [PixelDataFormat](../../com.aspose.psd/pixeldataformat) gedefinieerd voor 64 bits per pixel met 16 bits voor elk van de alfa, rood, groen en blauw.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Haalt de  PixelDataFormat  op die is gedefinieerd voor 24 bits per pixel met 8 bits voor elk van de luma-, blauwverschil- en roodverschil chroma‑componenten.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Haalt YCbCr-kleur op met een opgegeven aantal bits per sample.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerSample | int | Het aantal bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Haalt YCbCr-kleur op met een opgegeven aantal bits per sample.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerY | int | Het aantal bits per Y-kanaal. |
| bitsPerCb | int | Het aantal bits per Cb-kanaal. |
| bitsPerCr | int | Het aantal bits per Cr-kanaal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Haalt de  PixelDataFormat  op die is gedefinieerd voor 32 bits per pixel met 8 bits voor elk van de luma-, blauwverschil-, roodverschil- en zwart chroma‑componenten.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Haalt YCCK-kleur op met een opgegeven aantal bits per sample.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitsPerSample | int | Het aantal bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCCK color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor dit exemplaar.

**Returns:**
int - Een hashcode voor deze instantie, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hashtabel.
### isIndexed_internalized() {#isIndexed-internalized--}
```
public final boolean isIndexed_internalized()
```


Haalt een waarde op die aangeeft of deze instantie geïndexeerd is.

Waarde:  true  als deze instantie geïndexeerd is; anders,  false .

**Returns:**
boolean - een waarde die aangeeft of deze instantie geïndexeerd is.
### newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption) {#newPixelDataFormat-internalized-int---int-java.lang.String-}
```
public static PixelDataFormat newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Retourneert het resultaat van gelijkheid voor twee  PixelDataFormat  klassen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | De eerste  PixelDataFormat  om te vergelijken. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | De tweede  PixelDataFormat  om te vergelijken. |

**Returns:**
boolean - True als zowel  pixelFormat1  als  pixelFormat2  gelijke gegevens bevatten of beide parameters null zijn.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Retourneert het resultaat van ongelijkheid voor twee  PixelDataFormat  klassen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | De eerste  PixelDataFormat  om te vergelijken. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | De tweede  PixelDataFormat  om te vergelijken. |

**Returns:**
boolean - True als zowel  pixelFormat1  als  pixelFormat2  ongelijke gegevens bevatten of een van de parameters null is.
### toString() {#toString--}
```
public String toString()
```


Retourneert een  System.String  die deze instantie vertegenwoordigt.

**Returns:**
java.lang.String - Een  System.String  die deze instantie vertegenwoordigt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

