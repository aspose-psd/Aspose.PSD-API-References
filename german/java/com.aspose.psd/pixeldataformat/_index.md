---
title: "PixelDataFormat"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Das Pixel‑Datenformat."
type: docs
weight: 80
url: /de/java/com.aspose.psd/pixeldataformat/
---

**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

Das Pixel-Datenformat. Dies ist ein unveränderliches Objekt.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene  System.Object  gleich dieser Instanz ist. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Gibt BGR-Farbe mit einer angegebenen Bitanzahl pro Sample zurück. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Gibt BGRA-Farbe mit einer angegebenen Bitanzahl pro Sample zurück. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gibt die Bits pro Pixel zurück. |
| [getCaption()](#getCaption--) | Gibt die Beschriftung des Pixel-Datenformats zurück. |
| [getChannelBits()](#getChannelBits--) | Gibt die Bitanzahl für jeden Kanal zurück. |
| [getChannelsCount()](#getChannelsCount--) | Gibt die Kanalanzahl zurück. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Gibt CIE Lab-Farbe mit einer angegebenen Bitanzahl pro Sample zurück. |
| [getClass()](#getClass--) |  |
| [getCmyk()](#getCmyk--) | Gibt das  PixelDataFormat  zurück, das für 32 Bit pro Pixel definiert ist, mit 8 Bit für jedes der Cyan, Magenta, Gelb und Schwarz. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Gibt CMYK-Farbe mit einer angegebenen Bitanzahl pro Sample zurück. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Gibt CMYK-Farbe mit einer angegebenen Bitanzahl pro Sample zurück. |
| [getCmyk16()](#getCmyk16--) | Gibt das [PixelDataFormat](../../com.aspose.psd/pixeldataformat) zurück, das für 64 Bit pro Pixel definiert ist, mit 16 Bit für jedes der Cyan, Magenta, Gelb und Schwarz. |
| [getCmyka()](#getCmyka--) | Gibt das acmyk zurück. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Gibt CMYKA-Farbe mit einer angegebenen Bitanzahl pro Sample zurück. |
| [getCmyka16()](#getCmyka16--) | Gibt das acmyk zurück. |
| [getGrayscale()](#getGrayscale--) | Gibt das  PixelDataFormat  zurück, das für 8 Bit pro Pixel definiert ist, mit 8 Bit, die die Graustufenintensität im Intervall 0‑255 darstellen. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Gibt Graustufenfarbe mit einer angegebenen Bitanzahl pro Sample zurück. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Gibt das  PixelDataFormat  zurück, das für 16 Bit pro Pixel definiert ist, mit 8 Bit, die die Graustufenintensität im Intervall 0‑255 darstellen, und einem zusätzlichen 8‑Bit‑Alpha‑Komponente. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Gibt GraustufenAlpha-Farbe mit einer angegebenen Bitanzahl pro Sample zurück. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Gibt GraustufenAlpha-Farbe mit einer angegebenen Bitanzahl pro Sample zurück. |
| [getGrayscaleFloat32_internalized()](#getGrayscaleFloat32-internalized--) | Gibt das [PixelDataFormat](../../com.aspose.psd/pixeldataformat) zurück, das für 32 Bit pro Pixel definiert ist und die Graustufenintensität im Gleitkommaformat darstellt. |
| [getPixelFormat()](#getPixelFormat--) | Gibt das Pixel-Format zurück. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Gibt RGB-Farbe mit einer angegebenen Bitanzahl pro Sample zurück. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Gibt RGB-Farbe mit einer angegebenen Bitanzahl pro Sample zurück. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Gibt das  PixelDataFormat  zurück, das für 16 Bit pro Pixel definiert ist, mit 5 Bit für jedes der Rot, Grün und Blau, Alpha ist nicht definiert. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Gibt das  PixelDataFormat  zurück, das für 16 Bit pro Pixel definiert ist, mit 5 Bit für Rot, 6 Bit für Grün und 5 Bit für Blau, Alpha ist nicht definiert. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Gibt das  PixelDataFormat  zurück, das für 24 Bit pro Pixel definiert ist, mit 8 Bit für jedes der Alpha, Rot, Grün und Blau, Alpha ist nicht definiert. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Gibt das  PixelDataFormat  zurück, das für 24 Bit pro Pixel definiert ist, mit 8 Bit für jedes der Alpha, Rot, Grün und Blau, Alpha ist nicht definiert. |
| [getRgb32Bpp()](#getRgb32Bpp--) | Gibt das  PixelDataFormat  zurück, das für 32 Bit pro Pixel definiert ist, mit 8 Bit für jeweils Alpha, Rot, Grün und Blau. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Gibt BGRA‑indizierte Farbe mit einer angegebenen Anzahl von Bits pro Sample zurück. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Gibt das  PixelDataFormat  zurück, das für indizierte 1‑Bit‑Farben definiert ist. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Gibt das  PixelDataFormat  zurück, das für indizierte 2‑Bit‑Farben definiert ist. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Gibt das  PixelDataFormat  zurück, das für indizierte 4‑Bit‑Farben definiert ist. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Gibt das  PixelDataFormat  zurück, das für indizierte 8‑Bit‑Farben definiert ist. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Gibt RGBA‑Farbe mit einer angegebenen Anzahl von Bits pro Sample zurück. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Gibt RGBA‑Farbe mit einer angegebenen Anzahl von Bits pro Sample zurück. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Gibt das  PixelDataFormat  zurück, das für 32 Bit pro Pixel definiert ist, mit 8 Bit für jeweils Alpha, Rot, Grün und Blau. |
| [getRgba64Bpp()](#getRgba64Bpp--) | Gibt das [PixelDataFormat](../../com.aspose.psd/pixeldataformat) zurück, das für 64 Bit pro Pixel definiert ist, mit 16 Bit für jeweils Alpha, Rot, Grün und Blau. |
| [getYCbCr()](#getYCbCr--) | Gibt das  PixelDataFormat  zurück, das für 24 Bit pro Pixel definiert ist, mit 8 Bit für jeweils die Luma-, Blau‑Differenz‑ und Rot‑Differenz‑Chroma‑Komponenten. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Gibt YCbCr‑Farbe mit einer angegebenen Anzahl von Bits pro Sample zurück. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Gibt YCbCr‑Farbe mit einer angegebenen Anzahl von Bits pro Sample zurück. |
| [getYcck()](#getYcck--) | Gibt das  PixelDataFormat  zurück, das für 32 Bit pro Pixel definiert ist, mit 8 Bit für jeweils Luma-, Blau‑Differenz‑, Rot‑Differenz‑ und Schwarz‑Chroma‑Komponenten. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Gibt YCCK‑Farbe mit einer angegebenen Anzahl von Bits pro Sample zurück. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
| [isIndexed_internalized()](#isIndexed-internalized--) | Gibt einen Wert zurück, der angibt, ob diese Instanz indiziert ist. |
| [newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)](#newPixelDataFormat-internalized-int---int-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Gibt das Ergebnis der Gleichheit für zwei  PixelDataFormat  Klassen zurück. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Gibt das Ergebnis der Ungleichheit für zwei  PixelDataFormat  Klassen zurück. |
| [toString()](#toString--) | Gibt einen  System.String  zurück, der diese Instanz darstellt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene  System.Object  gleich dieser Instanz ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das  System.Object  zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  true  wenn das angegebene  System.Object  dieser Instanz gleich ist; andernfalls  false .
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Gibt BGR-Farbe mit einer angegebenen Bitanzahl pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGR color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Gibt BGRA-Farbe mit einer angegebenen Bitanzahl pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gibt die Bits pro Pixel zurück.

**Returns:**
int – Die Bits pro Pixel.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Gibt die Beschriftung des Pixel-Datenformats zurück.

**Returns:**
java.lang.String
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Gibt die Bitanzahl für jeden Kanal zurück.

**Returns:**
int[] – Die Kanalbits.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Gibt die Kanalanzahl zurück.

**Returns:**
int – Die Kanalanzahl.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Gibt CIE Lab-Farbe mit einer angegebenen Bitanzahl pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerL | int | Die Anzahl der Bits pro L‑Kanal. |
| bitsPerA | int | Die Anzahl der Bits pro A‑Kanal. |
| bitsPerB | int | Die Anzahl der Bits pro B-Kanal. |

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


Gibt das  PixelDataFormat  zurück, das für 32 Bit pro Pixel definiert ist, mit 8 Bit für jedes der Cyan, Magenta, Gelb und Schwarz.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Gibt CMYK-Farbe mit einer angegebenen Bitanzahl pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Gibt CMYK-Farbe mit einer angegebenen Bitanzahl pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerCyanChannel | int | Die Anzahl der Bits pro Cyan-Kanal. |
| bitsPerMagentaChannel | int | Die Anzahl der Bits pro Magenta-Kanal. |
| bitsPerYellowChannel | int | Die Anzahl der Bits pro Gelb-Kanal. |
| bitsPerKeyChannel | int | Die Anzahl der Bits pro Key-Kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk16() {#getCmyk16--}
```
public static PixelDataFormat getCmyk16()
```


Gibt das [PixelDataFormat](../../com.aspose.psd/pixeldataformat) zurück, das für 64 Bit pro Pixel definiert ist, mit 16 Bit für jedes der Cyan, Magenta, Gelb und Schwarz.

Wert: Das [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definiert für 64 Bit pro Pixel mit 16 Bit für jedes der Cyan, Magenta, Gelb und Schwarz.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Gibt das acmyk zurück.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Gibt CMYKA-Farbe mit einer angegebenen Bitanzahl pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerCyanChannel | int | Die Anzahl der Bits pro Cyan-Kanal. |
| bitsPerMagentaChannel | int | Die Anzahl der Bits pro Magenta-Kanal. |
| bitsPerYellowChannel | int | Die Anzahl der Bits pro Gelb-Kanal. |
| bitsPerKeyChannel | int | Die Anzahl der Bits pro Key-Kanal. |
| bitsPerAlphaChannel | int | Die Anzahl der Bits pro Alpha-Kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyka16() {#getCmyka16--}
```
public static PixelDataFormat getCmyka16()
```


Gibt das acmyk zurück.

Wert: Das [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definiert für 80 Bit pro Pixel mit 16 Bit für jedes der Alpha, Cyan, Magenta, Gelb und Schwarz.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getGrayscale() {#getGrayscale--}
```
public static PixelDataFormat getGrayscale()
```


Gibt das  PixelDataFormat  zurück, das für 8 Bit pro Pixel definiert ist, mit 8 Bit, die die Graustufenintensität im Intervall 0‑255 darstellen.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Gibt Graustufenfarbe mit einer angegebenen Bitanzahl pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Gibt das  PixelDataFormat  zurück, das für 16 Bit pro Pixel definiert ist, mit 8 Bit, die die Graustufenintensität im Intervall 0‑255 darstellen, und einem zusätzlichen 8‑Bit‑Alpha‑Komponente.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Gibt GraustufenAlpha-Farbe mit einer angegebenen Bitanzahl pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Gibt GraustufenAlpha-Farbe mit einer angegebenen Bitanzahl pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |
| alphaChannelBits | int | Die Anzahl der Bits pro Sample im Alpha-Kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleFloat32_internalized() {#getGrayscaleFloat32-internalized--}
```
public static PixelDataFormat getGrayscaleFloat32_internalized()
```


Gibt das [PixelDataFormat](../../com.aspose.psd/pixeldataformat) zurück, das für 32 Bit pro Pixel definiert ist und die Graustufenintensität im Gleitkommaformat darstellt.

Wert: Das [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definiert für 32 Bit pro Pixel, die Graustufenintensität im Gleitkommaformat darstellen

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Gibt das Pixel-Format zurück.

**Returns:**
int - Das Pixel-Format.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Gibt RGB-Farbe mit einer angegebenen Bitanzahl pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Gibt RGB-Farbe mit einer angegebenen Bitanzahl pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerRedChannel | int | Die Anzahl der Bits pro Rot-Kanal. |
| bitsPerGreenChannel | int | Die Anzahl der Bits pro Grün-Kanal. |
| bitsPerBlueChannel | int | Die Anzahl der Bits pro Blau-Kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Gibt das  PixelDataFormat  zurück, das für 16 Bit pro Pixel definiert ist, mit 5 Bit für jedes der Rot, Grün und Blau, Alpha ist nicht definiert.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Gibt das  PixelDataFormat  zurück, das für 16 Bit pro Pixel definiert ist, mit 5 Bit für Rot, 6 Bit für Grün und 5 Bit für Blau, Alpha ist nicht definiert.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Gibt das  PixelDataFormat  zurück, das für 24 Bit pro Pixel definiert ist, mit 8 Bit für jedes der Alpha, Rot, Grün und Blau, Alpha ist nicht definiert.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Gibt das  PixelDataFormat  zurück, das für 24 Bit pro Pixel definiert ist, mit 8 Bit für jedes der Alpha, Rot, Grün und Blau, Alpha ist nicht definiert.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Gibt das  PixelDataFormat  zurück, das für 32 Bit pro Pixel definiert ist, mit 8 Bit für jeweils Alpha, Rot, Grün und Blau.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Gibt BGRA‑indizierte Farbe mit einer angegebenen Anzahl von Bits pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Liefert das  PixelDataFormat  definiert für indiziertes 1 Bit pro Farbe. Der indizierte Pixeldatenspeicher ist dafür vorgesehen, Datenspeicherung und -abruf überall dort zu ermöglichen, wo die Farbpalette verwendet wird. Mit Vorsicht verwenden, da eine Konvertierung von einer Palette zur anderen oder von RGBA zum indizierten Farbmodell erforderlich sein kann.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 1 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Liefert das  PixelDataFormat  definiert für indiziertes 2 Bit pro Farbe. Der indizierte Pixeldatenspeicher ist dafür vorgesehen, Datenspeicherung und -abruf überall dort zu ermöglichen, wo die Farbpalette verwendet wird. Mit Vorsicht verwenden, da eine Konvertierung von einer Palette zur anderen oder von RGBA zum indizierten Farbmodell erforderlich sein kann.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 2 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Ruft das  PixelDataFormat  ab, das für indizierte 4‑Bit‑Farben definiert ist. Der indizierte Pixeldatenspeicher soll die Datenspeicherung und -abfrage überall dort ermöglichen, wo die Farbpalette verwendet wird. Mit Vorsicht verwenden, da möglicherweise eine Konvertierung von einer Palette zur anderen oder von RGBA zum indizierten Farbmodell erforderlich ist.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 4 bit per color.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Ruft das  PixelDataFormat  ab, das für indizierte 8‑Bit‑Farben definiert ist. Der indizierte Pixeldatenspeicher soll die Datenspeicherung und -abfrage überall dort ermöglichen, wo die Farbpalette verwendet wird. Mit Vorsicht verwenden, da möglicherweise eine Konvertierung von einer Palette zur anderen oder von RGBA zum indizierten Farbmodell erforderlich ist.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 8 bit per color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Gibt RGBA‑Farbe mit einer angegebenen Anzahl von Bits pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Gibt RGBA‑Farbe mit einer angegebenen Anzahl von Bits pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerRedChannel | int | Die Anzahl der Bits pro Rot-Kanal. |
| bitsPerGreenChannel | int | Die Anzahl der Bits pro Grün-Kanal. |
| bitsPerBlueChannel | int | Die Anzahl der Bits pro Blau-Kanal. |
| bitsPerAlphaChannel | int | Die Anzahl der Bits pro Alpha-Kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Gibt das  PixelDataFormat  zurück, das für 32 Bit pro Pixel definiert ist, mit 8 Bit für jeweils Alpha, Rot, Grün und Blau.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgba64Bpp() {#getRgba64Bpp--}
```
public static PixelDataFormat getRgba64Bpp()
```


Gibt das [PixelDataFormat](../../com.aspose.psd/pixeldataformat) zurück, das für 64 Bit pro Pixel definiert ist, mit 16 Bit für jeweils Alpha, Rot, Grün und Blau.

Wert: Das [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definiert für 64 Bit pro Pixel mit jeweils 16 Bit für Alpha, Rot, Grün und Blau.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Gibt das  PixelDataFormat  zurück, das für 24 Bit pro Pixel definiert ist, mit 8 Bit für jeweils die Luma-, Blau‑Differenz‑ und Rot‑Differenz‑Chroma‑Komponenten.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Gibt YCbCr‑Farbe mit einer angegebenen Anzahl von Bits pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Gibt YCbCr‑Farbe mit einer angegebenen Anzahl von Bits pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerY | int | Die Anzahl der Bits pro Y‑Kanal. |
| bitsPerCb | int | Die Anzahl der Bits pro Cb‑Kanal. |
| bitsPerCr | int | Die Anzahl der Bits pro Cr‑Kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Gibt das  PixelDataFormat  zurück, das für 32 Bit pro Pixel definiert ist, mit 8 Bit für jeweils Luma-, Blau‑Differenz‑, Rot‑Differenz‑ und Schwarz‑Chroma‑Komponenten.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Gibt YCCK‑Farbe mit einer angegebenen Anzahl von Bits pro Sample zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCCK color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int - Ein Hashcode für diese Instanz, geeignet für die Verwendung in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
### isIndexed_internalized() {#isIndexed-internalized--}
```
public final boolean isIndexed_internalized()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz indiziert ist.

Wert:  true  wenn diese Instanz indiziert ist; andernfalls  false .

**Returns:**
boolean – ein Wert, der angibt, ob diese Instanz indiziert ist.
### newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption) {#newPixelDataFormat-internalized-int---int-java.lang.String-}
```
public static PixelDataFormat newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Gibt das Ergebnis der Gleichheit für zwei  PixelDataFormat  Klassen zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Das erste  PixelDataFormat  zum Vergleichen. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Das zweite  PixelDataFormat  zum Vergleichen. |

**Returns:**
boolean – True, wenn sowohl  pixelFormat1  als auch  pixelFormat2  gleiche Daten enthalten oder beide Parameter null sind.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Gibt das Ergebnis der Ungleichheit für zwei  PixelDataFormat  Klassen zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Das erste  PixelDataFormat  zum Vergleichen. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Das zweite  PixelDataFormat  zum Vergleichen. |

**Returns:**
boolean – True, wenn sowohl  pixelFormat1  als auch  pixelFormat2  unterschiedliche Daten enthalten oder einer der Parameter null ist.
### toString() {#toString--}
```
public String toString()
```


Gibt einen  System.String  zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein  System.String  der diese Instanz darstellt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

