---
title: "PixelDataFormat"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il formato dei dati pixel."
type: docs
weight: 80
url: /it/java/com.aspose.psd/pixeldataformat/
---

**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

Il formato dei dati pixel. Questo è un oggetto immutabile.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'oggetto  System.Object  specificato è uguale a questa istanza. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Restituisce il colore BGR con un numero specificato di bit per campione. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Restituisce il colore BGRA con un numero specificato di bit per campione. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Restituisce i bit per pixel. |
| [getCaption()](#getCaption--) | Restituisce la didascalia del formato dei dati pixel. |
| [getChannelBits()](#getChannelBits--) | Restituisce il conteggio dei bit per ciascun canale. |
| [getChannelsCount()](#getChannelsCount--) | Restituisce il conteggio dei canali. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Restituisce il colore CIE Lab con un numero specificato di bit per campione. |
| [getClass()](#getClass--) |  |
| [getCmyk()](#getCmyk--) | Restituisce il  PixelDataFormat  definito per 32 bit per pixel con 8 bit per ciascuno dei colori ciano, magenta, giallo e nero. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Restituisce il colore CMYK con un numero specificato di bit per campione. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Restituisce il colore CMYK con un numero specificato di bit per campione. |
| [getCmyk16()](#getCmyk16--) | Restituisce il [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definito per 64 bit per pixel con 16 bit per ciascuno dei colori ciano, magenta, giallo e nero. |
| [getCmyka()](#getCmyka--) | Restituisce l'acmyk. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Restituisce il colore CMYKA con un numero specificato di bit per campione. |
| [getCmyka16()](#getCmyka16--) | Restituisce l'acmyk. |
| [getGrayscale()](#getGrayscale--) | Restituisce il  PixelDataFormat  definito per 8 bit per pixel con 8 bit che rappresentano l'intensità in scala di grigi nell'intervallo 0-255. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Restituisce il colore in scala di grigi con un numero specificato di bit per campione. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Restituisce il  PixelDataFormat  definito per 16 bit per pixel con 8 bit che rappresentano l'intensità in scala di grigi nell'intervallo 0-255 e un componente alfa aggiuntivo di 8 bit. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Restituisce il colore GrayscaleAlpha con un numero specificato di bit per campione. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Restituisce il colore GrayscaleAlpha con un numero specificato di bit per campione. |
| [getGrayscaleFloat32_internalized()](#getGrayscaleFloat32-internalized--) | Restituisce il [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definito per 32 bit per pixel che rappresenta l'intensità in scala di grigi in formato a virgola mobile. |
| [getPixelFormat()](#getPixelFormat--) | Restituisce il formato pixel. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Restituisce il colore RGB con un numero specificato di bit per campione. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Restituisce il colore RGB con un numero specificato di bit per campione. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Restituisce il  PixelDataFormat  definito per 16 bit per pixel con 5 bit per ciascuno di rosso, verde e blu, l'alfa non è definito. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Restituisce il  PixelDataFormat  definito per 16 bit per pixel con 5 bit per rosso, 6 bit per verde e 5 bit per blu, l'alfa non è definito. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Restituisce il  PixelDataFormat  definito per 24 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu, l'alfa non è definito. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Restituisce il  PixelDataFormat  definito per 24 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu, l'alfa non è definito. |
| [getRgb32Bpp()](#getRgb32Bpp--) | Restituisce il  PixelDataFormat  definito per 32 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Ottiene il colore indicizzato BGRA con un numero specificato di bit per campione. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Ottiene il  PixelDataFormat  definito per 1 bit indicizzato per colore. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Ottiene il  PixelDataFormat  definito per 2 bit indicizzato per colore. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Ottiene il  PixelDataFormat  definito per 4 bit indicizzato per colore. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Ottiene il  PixelDataFormat  definito per 8 bit indicizzato per colore. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Ottiene il colore RGBA con un numero specificato di bit per campione. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Ottiene il colore RGBA con un numero specificato di bit per campione. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Restituisce il  PixelDataFormat  definito per 32 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu. |
| [getRgba64Bpp()](#getRgba64Bpp--) | Ottiene il [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definito per 64 bit per pixel con 16 bit per ciascuno di alfa, rosso, verde e blu. |
| [getYCbCr()](#getYCbCr--) | Ottiene il  PixelDataFormat  definito per 24 bit per pixel con 8 bit per ciascuno dei componenti cromatici luma, differenza blu e differenza rossa. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Ottiene il colore YCbCr con un numero specificato di bit per campione. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Ottiene il colore YCbCr con un numero specificato di bit per campione. |
| [getYcck()](#getYcck--) | Ottiene il  PixelDataFormat  definito per 32 bit per pixel con 8 bit per ciascuno dei componenti cromatici luma, differenza blu, differenza rossa e nero. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Ottiene il colore YCCK con un numero specificato di bit per campione. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
| [isIndexed_internalized()](#isIndexed-internalized--) | Ottiene un valore che indica se questa istanza è indicizzata. |
| [newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)](#newPixelDataFormat-internalized-int---int-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Restituisce il risultato dell'uguaglianza per due classi  PixelDataFormat . |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Restituisce il risultato della non uguaglianza per due classi  PixelDataFormat . |
| [toString()](#toString--) | Restituisce un  System.String  che rappresenta questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'oggetto  System.Object  specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'  System.Object  da confrontare con questa istanza. |

**Returns:**
boolean - true se l'oggetto System.Object specificato è uguale a questa istanza; altrimenti, false.
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Restituisce il colore BGR con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGR color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Restituisce il colore BGRA con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Restituisce i bit per pixel.

**Returns:**
int - I bit per pixel.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Restituisce la didascalia del formato dei dati pixel.

**Returns:**
java.lang.String
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Restituisce il conteggio dei bit per ciascun canale.

**Returns:**
int[] - I bit del canale.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Restituisce il conteggio dei canali.

**Returns:**
int - Il conteggio dei canali.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Restituisce il colore CIE Lab con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerL | int | Il numero di bit per il canale L. |
| bitsPerA | int | Il numero di bit per il canale A. |
| bitsPerB | int | Il numero di bit per il canale B. |

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


Restituisce il  PixelDataFormat  definito per 32 bit per pixel con 8 bit per ciascuno dei colori ciano, magenta, giallo e nero.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Restituisce il colore CMYK con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Restituisce il colore CMYK con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerCyanChannel | int | Il numero di bit per il canale Ciano. |
| bitsPerMagentaChannel | int | Il numero di bit per il canale Magenta. |
| bitsPerYellowChannel | int | Il numero di bit per il canale Giallo. |
| bitsPerKeyChannel | int | Il numero di bit per il canale Key. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk16() {#getCmyk16--}
```
public static PixelDataFormat getCmyk16()
```


Restituisce il [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definito per 64 bit per pixel con 16 bit per ciascuno dei colori ciano, magenta, giallo e nero.

Valore: Il [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definito per 64 bit per pixel con 16 bit per ciascuno dei ciano, magenta, giallo e nero.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Restituisce l'acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Restituisce il colore CMYKA con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerCyanChannel | int | Il numero di bit per il canale Ciano. |
| bitsPerMagentaChannel | int | Il numero di bit per il canale Magenta. |
| bitsPerYellowChannel | int | Il numero di bit per il canale Giallo. |
| bitsPerKeyChannel | int | Il numero di bit per il canale Key. |
| bitsPerAlphaChannel | int | Il numero di bit per il canale Alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyka16() {#getCmyka16--}
```
public static PixelDataFormat getCmyka16()
```


Restituisce l'acmyk.

Valore: Il [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definito per 80 bit per pixel con 16 bit per ciascuno dei alfa, ciano, magenta, giallo e nero.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getGrayscale() {#getGrayscale--}
```
public static PixelDataFormat getGrayscale()
```


Restituisce il  PixelDataFormat  definito per 8 bit per pixel con 8 bit che rappresentano l'intensità in scala di grigi nell'intervallo 0-255.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Restituisce il colore in scala di grigi con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Restituisce il  PixelDataFormat  definito per 16 bit per pixel con 8 bit che rappresentano l'intensità in scala di grigi nell'intervallo 0-255 e un componente alfa aggiuntivo di 8 bit.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Restituisce il colore GrayscaleAlpha con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Restituisce il colore GrayscaleAlpha con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |
| alphaChannelBits | int | Il numero di bit per campione nel canale alfa. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleFloat32_internalized() {#getGrayscaleFloat32-internalized--}
```
public static PixelDataFormat getGrayscaleFloat32_internalized()
```


Restituisce il [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definito per 32 bit per pixel che rappresenta l'intensità in scala di grigi in formato a virgola mobile.

Valore: Il [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definito per 32 bit per pixel che rappresenta l'intensità in scala di grigi in formato a virgola mobile

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Restituisce il formato pixel.

**Returns:**
int - Il formato pixel.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Restituisce il colore RGB con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Restituisce il colore RGB con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerRedChannel | int | Il numero di bit per il canale Rosso. |
| bitsPerGreenChannel | int | Il numero di bit per il canale Verde. |
| bitsPerBlueChannel | int | Il numero di bit per il canale Blu. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Restituisce il  PixelDataFormat  definito per 16 bit per pixel con 5 bit per ciascuno di rosso, verde e blu, l'alfa non è definito.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Restituisce il  PixelDataFormat  definito per 16 bit per pixel con 5 bit per rosso, 6 bit per verde e 5 bit per blu, l'alfa non è definito.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Restituisce il  PixelDataFormat  definito per 24 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu, l'alfa non è definito.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Restituisce il  PixelDataFormat  definito per 24 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu, l'alfa non è definito.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Restituisce il  PixelDataFormat  definito per 32 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Ottiene il colore indicizzato BGRA con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Restituisce il  PixelDataFormat  definito per 1 bit per colore indicizzato. L'archiviazione dei dati pixel indicizzati è destinata a consentire l'archiviazione e il recupero dei dati ovunque venga utilizzata la tavolozza dei colori. Usare con cautela, poiché potrebbe richiedere la conversione da una tavolozza all'altra o da RGBA a modello di colore indicizzato.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 1 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Restituisce il  PixelDataFormat  definito per 2 bit per colore indicizzato. L'archiviazione dei dati pixel indicizzati è destinata a consentire l'archiviazione e il recupero dei dati ovunque venga utilizzata la tavolozza dei colori. Usare con cautela, poiché potrebbe richiedere la conversione da una tavolozza all'altra o da RGBA a modello di colore indicizzato.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 2 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Restituisce il  PixelDataFormat  definito per 4 bit per colore indicizzato. L'archiviazione dei dati pixel indicizzati è destinata a consentire l'archiviazione e il recupero dei dati ovunque venga utilizzata la tavolozza dei colori. Usare con cautela, poiché potrebbe richiedere la conversione da una tavolozza all'altra o da RGBA a modello di colore indicizzato.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 4 bit per color.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Ottiene il  PixelDataFormat  definito per 8 bit indicizzati per colore. L'archiviazione dei dati pixel indicizzati è destinata a consentire l'archiviazione e il recupero dei dati ovunque venga utilizzata la tavolozza dei colori. Usare con cautela, poiché potrebbe richiedere la conversione da una tavolozza all'altra o da RGBA a modello di colore indicizzato.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 8 bit per color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Ottiene il colore RGBA con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Ottiene il colore RGBA con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerRedChannel | int | Il numero di bit per il canale Rosso. |
| bitsPerGreenChannel | int | Il numero di bit per il canale Verde. |
| bitsPerBlueChannel | int | Il numero di bit per il canale Blu. |
| bitsPerAlphaChannel | int | Il numero di bit per il canale Alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Restituisce il  PixelDataFormat  definito per 32 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgba64Bpp() {#getRgba64Bpp--}
```
public static PixelDataFormat getRgba64Bpp()
```


Ottiene il [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definito per 64 bit per pixel con 16 bit per ciascuno di alfa, rosso, verde e blu.

Valore: Il [PixelDataFormat](../../com.aspose.psd/pixeldataformat) definito per 64 bit per pixel con 16 bit per ciascuno di alfa, rosso, verde e blu.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Ottiene il  PixelDataFormat  definito per 24 bit per pixel con 8 bit per ciascuno dei componenti cromatici luma, differenza blu e differenza rossa.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Ottiene il colore YCbCr con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Ottiene il colore YCbCr con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerY | int | Il numero di bit per il canale Y. |
| bitsPerCb | int | Il numero di bit per il canale Cb. |
| bitsPerCr | int | Il numero di bit per il canale Cr. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Ottiene il  PixelDataFormat  definito per 32 bit per pixel con 8 bit per ciascuno dei componenti cromatici luma, differenza blu, differenza rossa e nero.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Ottiene il colore YCCK con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCCK color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
### isIndexed_internalized() {#isIndexed-internalized--}
```
public final boolean isIndexed_internalized()
```


Ottiene un valore che indica se questa istanza è indicizzata.

Valore:  true  se questa istanza è indicizzata; altrimenti,  false .

**Returns:**
boolean - un valore che indica se questa istanza è indicizzata.
### newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption) {#newPixelDataFormat-internalized-int---int-java.lang.String-}
```
public static PixelDataFormat newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Restituisce il risultato dell'uguaglianza per due classi  PixelDataFormat .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Il primo  PixelDataFormat  da confrontare. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Il secondo  PixelDataFormat  da confrontare. |

**Returns:**
boolean - True se sia  pixelFormat1  che  pixelFormat2  contengono dati uguali o entrambi i parametri sono null.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Restituisce il risultato della non uguaglianza per due classi  PixelDataFormat .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Il primo  PixelDataFormat  da confrontare. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Il secondo  PixelDataFormat  da confrontare. |

**Returns:**
boolean - True se sia  pixelFormat1  che  pixelFormat2  contengono dati non uguali o uno dei parametri è null.
### toString() {#toString--}
```
public String toString()
```


Restituisce un  System.String  che rappresenta questa istanza.

**Returns:**
java.lang.String - Un  System.String  che rappresenta questa istanza.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

