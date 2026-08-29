---
title: "PixelDataFormat"
second_title: "Aspose.PSD för Java API-referens"
description: "Pixeldataformatet."
type: docs
weight: 80
url: /sv/java/com.aspose.psd/pixeldataformat/
---

**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

Pixeldataformatet. Detta är ett oföränderligt objekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det angivna  System.Object  är lika med denna instans. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Hämtar BGR-färg med ett specificerat antal bitar per prov. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Hämtar BGRA-färg med ett specificerat antal bitar per prov. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar bitarna per pixel. |
| [getCaption()](#getCaption--) | Hämtar rubriken för pixeldataformatet. |
| [getChannelBits()](#getChannelBits--) | Hämtar bitantalet för varje kanal. |
| [getChannelsCount()](#getChannelsCount--) | Hämtar antalet kanaler. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Hämtar CIE Lab-färg med ett specificerat antal bitar per prov. |
| [getClass()](#getClass--) |  |
| [getCmyk()](#getCmyk--) | Hämtar  PixelDataFormat  definierad för 32 bitar per pixel med 8 bitar för varje cyan, magenta, gul och svart. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Hämtar CMYK-färg med ett specificerat antal bitar per prov. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Hämtar CMYK-färg med ett specificerat antal bitar per prov. |
| [getCmyk16()](#getCmyk16--) | Hämtar [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definierad för 64 bitar per pixel med 16 bitar för varje cyan, magenta, gul och svart. |
| [getCmyka()](#getCmyka--) | Hämtar acmyk. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Hämtar CMYKA-färg med ett specificerat antal bitar per prov. |
| [getCmyka16()](#getCmyka16--) | Hämtar acmyk. |
| [getGrayscale()](#getGrayscale--) | Hämtar  PixelDataFormat  definierad för 8 bitar per pixel med 8 bitar som representerar gråskaleintensitet i intervallet 0-255. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Hämtar gråskala-färg med ett specificerat antal bitar per prov. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Hämtar  PixelDataFormat  definierad för 16 bitar per pixel med 8 bitar som representerar gråskaleintensitet i intervallet 0-255 och en extra 8-bitars alfakomponent. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Hämtar GrayscaleAlpha-färg med ett specificerat antal bitar per prov. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Hämtar GrayscaleAlpha-färg med ett specificerat antal bitar per prov. |
| [getGrayscaleFloat32_internalized()](#getGrayscaleFloat32-internalized--) | Hämtar [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definierad för 32 bitar per pixel som representerar gråskaleintensitet i flyttalsformat. |
| [getPixelFormat()](#getPixelFormat--) | Hämtar pixelformatet. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Hämtar RGB-färg med ett specificerat antal bitar per prov. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Hämtar RGB-färg med ett specificerat antal bitar per prov. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Hämtar  PixelDataFormat  definierad för 16 bitar per pixel med 5 bitar för varje röd, grön och blå, alfa är inte definierad. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Hämtar  PixelDataFormat  definierad för 16 bitar per pixel med 5 bitar för röd, 6 bitar för grön och 5 bitar för blå, alfa är inte definierad. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Hämtar  PixelDataFormat  definierad för 24 bitar per pixel med 8 bitar för varje alfa, röd, grön och blå, alfa är inte definierad. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Hämtar  PixelDataFormat  definierad för 24 bitar per pixel med 8 bitar för varje alfa, röd, grön och blå, alfa är inte definierad. |
| [getRgb32Bpp()](#getRgb32Bpp--) | Hämtar  PixelDataFormat  som är definierad för 32 bitar per pixel med 8 bitar för varje av alfa, röd, grön och blå. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Hämtar BGRA-indexerad färg med ett specificerat antal bitar per sample. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Hämtar  PixelDataFormat  som är definierad för indexerad 1 bit per färg. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Hämtar  PixelDataFormat  som är definierad för indexerad 2 bitar per färg. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Hämtar  PixelDataFormat  som är definierad för indexerad 4 bitar per färg. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Hämtar  PixelDataFormat  som är definierad för indexerad 8 bitar per färg. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Hämtar RGBA-färg med ett specificerat antal bitar per sample. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Hämtar RGBA-färg med ett specificerat antal bitar per sample. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Hämtar  PixelDataFormat  som är definierad för 32 bitar per pixel med 8 bitar för varje av alfa, röd, grön och blå. |
| [getRgba64Bpp()](#getRgba64Bpp--) | Hämtar [PixelDataFormat](../../com.aspose.psd/pixeldataformat) som är definierad för 64 bitar per pixel med 16 bitar för varje av alfa, röd, grön och blå. |
| [getYCbCr()](#getYCbCr--) | Hämtar  PixelDataFormat  som är definierad för 24 bitar per pixel med 8 bitar för varje av luma, blå-differens och röd-differens kromakomponenter. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Hämtar YCbCr-färg med ett specificerat antal bitar per sample. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Hämtar YCbCr-färg med ett specificerat antal bitar per sample. |
| [getYcck()](#getYcck--) | Hämtar  PixelDataFormat  som är definierad för 32 bitar per pixel med 8 bitar för varje av luma, blå-differens, röd-differens och svart kromakomponenter. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Hämtar YCCK-färg med ett specificerat antal bitar per sample. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för den här instansen. |
| [isIndexed_internalized()](#isIndexed-internalized--) | Hämtar ett värde som indikerar om detta objekt är indexerat. |
| [newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)](#newPixelDataFormat-internalized-int---int-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Returnerar resultatet av likhet för två  PixelDataFormat  klasser. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Returnerar resultatet av ojämlikhet för två  PixelDataFormat  klasser. |
| [toString()](#toString--) | Returnerar en  System.String  som representerar detta objekt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det angivna  System.Object  är lika med denna instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det  System.Object  att jämföra med den här instansen. |

**Returns:**
boolean -  true  om det angivna  System.Object  är lika med den här instansen; annars  false .
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Hämtar BGR-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGR color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Hämtar BGRA-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar bitarna per pixel.

**Returns:**
int - Bitarna per pixel.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Hämtar rubriken för pixeldataformatet.

**Returns:**
java.lang.String
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Hämtar bitantalet för varje kanal.

**Returns:**
int[] - Kanalbitarna.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Hämtar antalet kanaler.

**Returns:**
int - Antalet kanaler.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Hämtar CIE Lab-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerL | int | Antalet bitar per L-kanal. |
| bitsPerA | int | Antalet bitar per A-kanal. |
| bitsPerB | int | Antalet bitar per B-kanal. |

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


Hämtar  PixelDataFormat  definierad för 32 bitar per pixel med 8 bitar för varje cyan, magenta, gul och svart.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Hämtar CMYK-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Hämtar CMYK-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerCyanChannel | int | Antalet bitar per Cyan-kanal. |
| bitsPerMagentaChannel | int | Antalet bitar per Magenta-kanal. |
| bitsPerYellowChannel | int | Antalet bitar per Yellow-kanal. |
| bitsPerKeyChannel | int | Antalet bitar per Key-kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk16() {#getCmyk16--}
```
public static PixelDataFormat getCmyk16()
```


Hämtar [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definierad för 64 bitar per pixel med 16 bitar för varje cyan, magenta, gul och svart.

Värde: Den [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definierad för 64 bitar per pixel med 16 bitar för varje av cyan, magenta, yellow och svart.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Hämtar acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Hämtar CMYKA-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerCyanChannel | int | Antalet bitar per Cyan-kanal. |
| bitsPerMagentaChannel | int | Antalet bitar per Magenta-kanal. |
| bitsPerYellowChannel | int | Antalet bitar per Yellow-kanal. |
| bitsPerKeyChannel | int | Antalet bitar per Key-kanal. |
| bitsPerAlphaChannel | int | Antalet bitar per Alpha-kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyka16() {#getCmyka16--}
```
public static PixelDataFormat getCmyka16()
```


Hämtar acmyk.

Värde: Den [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definierad för 80 bitar per pixel med 16 bitar för varje av alpha, cyan, magenta, yellow och svart.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getGrayscale() {#getGrayscale--}
```
public static PixelDataFormat getGrayscale()
```


Hämtar  PixelDataFormat  definierad för 8 bitar per pixel med 8 bitar som representerar gråskaleintensitet i intervallet 0-255.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Hämtar gråskala-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Hämtar  PixelDataFormat  definierad för 16 bitar per pixel med 8 bitar som representerar gråskaleintensitet i intervallet 0-255 och en extra 8-bitars alfakomponent.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Hämtar GrayscaleAlpha-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Hämtar GrayscaleAlpha-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |
| alphaChannelBits | int | Antalet bitar per prov i alpha-kanalen. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleFloat32_internalized() {#getGrayscaleFloat32-internalized--}
```
public static PixelDataFormat getGrayscaleFloat32_internalized()
```


Hämtar [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definierad för 32 bitar per pixel som representerar gråskaleintensitet i flyttalsformat.

Värde: Den [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definierad för 32 bitar per pixel som representerar gråskaleintensitet i flyttalsformat.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Hämtar pixelformatet.

**Returns:**
int - Pixelformatet.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Hämtar RGB-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Hämtar RGB-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerRedChannel | int | Antalet bitar per Red-kanal. |
| bitsPerGreenChannel | int | Antalet bitar per Green-kanal. |
| bitsPerBlueChannel | int | Antalet bitar per Blue-kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Hämtar  PixelDataFormat  definierad för 16 bitar per pixel med 5 bitar för varje röd, grön och blå, alfa är inte definierad.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Hämtar  PixelDataFormat  definierad för 16 bitar per pixel med 5 bitar för röd, 6 bitar för grön och 5 bitar för blå, alfa är inte definierad.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Hämtar  PixelDataFormat  definierad för 24 bitar per pixel med 8 bitar för varje alfa, röd, grön och blå, alfa är inte definierad.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Hämtar  PixelDataFormat  definierad för 24 bitar per pixel med 8 bitar för varje alfa, röd, grön och blå, alfa är inte definierad.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Hämtar  PixelDataFormat  som är definierad för 32 bitar per pixel med 8 bitar för varje av alfa, röd, grön och blå.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Hämtar BGRA-indexerad färg med ett specificerat antal bitar per sample.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Hämtar  PixelDataFormat  definierad för indexerad 1 bit per färg. Den indexerade pixeldatalagringen är avsedd att möjliggöra datalagring och hämtning överallt där färgpaletten används. Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till en indexerad färgmodell.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 1 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Hämtar  PixelDataFormat  definierad för indexerad 2 bit per färg. Den indexerade pixeldatalagringen är avsedd att möjliggöra datalagring och hämtning överallt där färgpaletten används. Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till en indexerad färgmodell.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 2 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Hämtar den  PixelDataFormat  som är definierad för indexerad 4 bit per färg. Den indexerade pixeldata lagringen är avsedd att möjliggöra datalagring och hämtning överallt där färgpaletten används. Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till en indexerad färgmodell.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 4 bit per color.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Hämtar den  PixelDataFormat  som är definierad för indexerad 8 bit per färg. Den indexerade pixeldata lagringen är avsedd att möjliggöra datalagring och hämtning överallt där färgpaletten används. Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till en indexerad färgmodell.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 8 bit per color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Hämtar RGBA-färg med ett specificerat antal bitar per sample.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Hämtar RGBA-färg med ett specificerat antal bitar per sample.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerRedChannel | int | Antalet bitar per Red-kanal. |
| bitsPerGreenChannel | int | Antalet bitar per Green-kanal. |
| bitsPerBlueChannel | int | Antalet bitar per Blue-kanal. |
| bitsPerAlphaChannel | int | Antalet bitar per Alpha-kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Hämtar  PixelDataFormat  som är definierad för 32 bitar per pixel med 8 bitar för varje av alfa, röd, grön och blå.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgba64Bpp() {#getRgba64Bpp--}
```
public static PixelDataFormat getRgba64Bpp()
```


Hämtar [PixelDataFormat](../../com.aspose.psd/pixeldataformat) som är definierad för 64 bitar per pixel med 16 bitar för varje av alfa, röd, grön och blå.

Värde: Den [PixelDataFormat](../../com.aspose.psd/pixeldataformat) som är definierad för 64 bitar per pixel med 16 bitar för varje av alfa, röd, grön och blå.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Hämtar  PixelDataFormat  som är definierad för 24 bitar per pixel med 8 bitar för varje av luma, blå-differens och röd-differens kromakomponenter.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Hämtar YCbCr-färg med ett specificerat antal bitar per sample.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Hämtar YCbCr-färg med ett specificerat antal bitar per sample.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerY | int | Antalet bitar per Y-kanal. |
| bitsPerCb | int | Antalet bitar per Cb-kanal. |
| bitsPerCr | int | Antalet bitar per Cr-kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Hämtar  PixelDataFormat  som är definierad för 32 bitar per pixel med 8 bitar för varje av luma, blå-differens, röd-differens och svart kromakomponenter.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Hämtar YCCK-färg med ett specificerat antal bitar per sample.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCCK color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för den här instansen.

**Returns:**
int - En hashkod för den här instansen, lämplig för användning i hash‑algoritmer och datastrukturer som en hashtabell.
### isIndexed_internalized() {#isIndexed-internalized--}
```
public final boolean isIndexed_internalized()
```


Hämtar ett värde som indikerar om detta objekt är indexerat.

Värde:  true  om detta objekt är indexerat; annars,  false .

**Returns:**
boolean - ett värde som indikerar om detta objekt är indexerat.
### newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption) {#newPixelDataFormat-internalized-int---int-java.lang.String-}
```
public static PixelDataFormat newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Returnerar resultatet av likhet för två  PixelDataFormat  klasser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Den första  PixelDataFormat  att jämföra. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Den andra  PixelDataFormat  att jämföra. |

**Returns:**
boolean - True om både  pixelFormat1  och  pixelFormat2  innehåller lika data eller båda parametrarna är null.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Returnerar resultatet av ojämlikhet för två  PixelDataFormat  klasser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Den första  PixelDataFormat  att jämföra. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Den andra  PixelDataFormat  att jämföra. |

**Returns:**
boolean - True om både  pixelFormat1  och  pixelFormat2  innehåller olika data eller en av parametrarna är null.
### toString() {#toString--}
```
public String toString()
```


Returnerar en  System.String  som representerar detta objekt.

**Returns:**
java.lang.String - En  System.String  som representerar detta objekt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

