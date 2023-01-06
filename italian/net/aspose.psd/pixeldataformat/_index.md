---
title: PixelDataFormat
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Il formato dei dati dei pixel. Questo è un oggetto immutabile.
type: docs
weight: 5160
url: /it/net/aspose.psd/pixeldataformat/
---
## PixelDataFormat class

Il formato dei dati dei pixel. Questo è un oggetto immutabile.

```csharp
public class PixelDataFormat
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [Cmyk](../../aspose.psd/pixeldataformat/cmyk) { get; } | Ottiene il[`PixelDataFormat`](../pixeldataformat) definito per 32 bit per pixel con 8 bit per ciascuno dei colori ciano, magenta, giallo e nero. |
| static [Cmyka](../../aspose.psd/pixeldataformat/cmyka) { get; } | Ottiene acmyk. |
| static [Grayscale](../../aspose.psd/pixeldataformat/grayscale) { get; } | Ottiene il[`PixelDataFormat`](../pixeldataformat)definito per 8 bit per pixel con 8 bit che rappresentano l'intensità della scala di grigi nell'intervallo 0-255. |
| static [GrayscaleAlpha](../../aspose.psd/pixeldataformat/grayscalealpha) { get; } | Ottiene il[`PixelDataFormat`](../pixeldataformat) definito per 16 bit per pixel con 8 bit che rappresentano l'intensità della scala di grigi nell'intervallo 0-255 e componente alfa a 8 bit aggiuntivo. |
| static [Rgb16Bpp555](../../aspose.psd/pixeldataformat/rgb16bpp555) { get; } | Ottiene il[`PixelDataFormat`](../pixeldataformat) definito per 16 bit per pixel con 5 bit per ciascuno dei rosso, verde e blu, alfa non è definito. |
| static [Rgb16Bpp565](../../aspose.psd/pixeldataformat/rgb16bpp565) { get; } | Ottiene il[`PixelDataFormat`](../pixeldataformat)definito per 16 bit per pixel con 5 bit per il rosso, 6 bit per il verde e 5 bit per il blu, l'alfa non è definito. |
| static [Rgb24Bpp](../../aspose.psd/pixeldataformat/rgb24bpp) { get; } | Ottiene il[`PixelDataFormat`](../pixeldataformat) definito per 24 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu, alfa non è definito. |
| static [Rgb24BppPng](../../aspose.psd/pixeldataformat/rgb24bpppng) { get; } | Ottiene il[`PixelDataFormat`](../pixeldataformat) definito per 24 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu, alfa non è definito. |
| static [Rgb32Bpp](../../aspose.psd/pixeldataformat/rgb32bpp) { get; } | Ottiene il[`PixelDataFormat`](../pixeldataformat) definito per 32 bit per pixel con 8 bit per ciascuno dei caratteri alfa, rosso, verde e blu. |
| static [Rgba32Bpp](../../aspose.psd/pixeldataformat/rgba32bpp) { get; } | Ottiene il[`PixelDataFormat`](../pixeldataformat) definito per 32 bit per pixel con 8 bit per ciascuno dei caratteri alfa, rosso, verde e blu. |
| static [RgbIndexed1Bpp](../../aspose.psd/pixeldataformat/rgbindexed1bpp) { get; } | Ottiene il[`PixelDataFormat`](../pixeldataformat) definito per 1 bit indicizzato per colore. L'archiviazione dei dati dei pixel indicizzati ha lo scopo di consentire l'archiviazione e il recupero dei dati ovunque venga utilizzata la tavolozza dei colori. Utilizzare con cautela, poiché potrebbe richiedere la conversione da una tavolozza all'altra o da RGBA al modello di colore indicizzato . |
| static [RgbIndexed2Bpp](../../aspose.psd/pixeldataformat/rgbindexed2bpp) { get; } | Ottiene il[`PixelDataFormat`](../pixeldataformat)definito per 2 bit indicizzati per colore. L'archiviazione dei dati dei pixel indicizzati ha lo scopo di consentire l'archiviazione e il recupero dei dati ovunque venga utilizzata la tavolozza dei colori. Utilizzare con cautela, poiché potrebbe richiedere la conversione da una tavolozza all'altra o da RGBA al modello di colore indicizzato . |
| static [RgbIndexed4Bpp](../../aspose.psd/pixeldataformat/rgbindexed4bpp) { get; } | Ottiene il[`PixelDataFormat`](../pixeldataformat) definito per 4 bit indicizzati per colore. L'archiviazione dei dati dei pixel indicizzati ha lo scopo di consentire l'archiviazione e il recupero dei dati ovunque venga utilizzata la tavolozza dei colori. Utilizzare con cautela, poiché potrebbe richiedere la conversione da una tavolozza all'altra o da RGBA al modello di colore indicizzato . |
| static [RgbIndexed8Bpp](../../aspose.psd/pixeldataformat/rgbindexed8bpp) { get; } | Ottiene il[`PixelDataFormat`](../pixeldataformat) definito per 8 bit indicizzati per colore. L'archiviazione dei dati dei pixel indicizzati ha lo scopo di consentire l'archiviazione e il recupero dei dati ovunque venga utilizzata la tavolozza dei colori. Utilizzare con cautela, poiché potrebbe richiedere la conversione da una tavolozza all'altra o da RGBA al modello di colore indicizzato . |
| static [YCbCr](../../aspose.psd/pixeldataformat/ycbcr) { get; } | Ottiene il[`PixelDataFormat`](../pixeldataformat) definito per 24 bit per pixel con 8 bit per ciascuna delle componenti di crominanza luminanza, differenza blu e differenza rossa. |
| static [Ycck](../../aspose.psd/pixeldataformat/ycck) { get; } | Ottiene il[`PixelDataFormat`](../pixeldataformat) definito per 32 bit per pixel con 8 bit per ciascuna delle componenti luma, differenza blu, differenza rossa e crominanza nera. |
| [BitsPerPixel](../../aspose.psd/pixeldataformat/bitsperpixel) { get; } | Ottiene i bit per pixel. |
| [Caption](../../aspose.psd/pixeldataformat/caption) { get; } | Ottiene la didascalia del formato dati pixel. |
| [ChannelBits](../../aspose.psd/pixeldataformat/channelbits) { get; } | Ottiene il conteggio dei bit per ciascun canale. |
| [ChannelsCount](../../aspose.psd/pixeldataformat/channelscount) { get; } | Ottiene il conteggio dei canali. |
| [PixelFormat](../../aspose.psd/pixeldataformat/pixelformat) { get; } | Ottiene il formato pixel. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [GetBgr](../../aspose.psd/pixeldataformat/getbgr)(int) | Ottiene il colore BGR con un numero specificato di bit per campione. |
| static [GetBgra](../../aspose.psd/pixeldataformat/getbgra)(int) | Ottiene il colore BGRA con un numero specificato di bit per campione. |
| static [GetCieLab](../../aspose.psd/pixeldataformat/getcielab)(int, int, int) | Ottiene il colore CIE Lab con un numero specificato di bit per campione. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk#getcmyk)(int) | Ottiene il colore CMYK con un numero specificato di bit per campione. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk#getcmyk_1)(int, int, int, int) | Ottiene il colore CMYK con un numero specificato di bit per campione. |
| static [GetCmyka](../../aspose.psd/pixeldataformat/getcmyka)(int, int, int, int, int) | Ottiene il colore CMYKA con un numero specificato di bit per campione. |
| static [GetGrayscale](../../aspose.psd/pixeldataformat/getgrayscale)(int) | Ottiene il colore in scala di grigi con un numero specificato di bit per campione. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha#getgrayscalealpha)(int) | Ottiene il colore GrayscaleAlpha con un numero specificato di bit per campione. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha#getgrayscalealpha_1)(int, int) | Ottiene il colore GrayscaleAlpha con un numero specificato di bit per campione. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb#getrgb)(int) | Ottiene il colore RGB con un numero specificato di bit per campione. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb#getrgb_1)(int, int, int) | Ottiene il colore RGB con un numero specificato di bit per campione. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba#getrgba)(int) | Ottiene il colore RGBA con un numero specificato di bit per campione. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba#getrgba_1)(int, int, int, int) | Ottiene il colore RGBA con un numero specificato di bit per campione. |
| static [GetRgbIndexed](../../aspose.psd/pixeldataformat/getrgbindexed)(int) | Ottiene il colore indicizzato BGRA con un numero specificato di bit per campione. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr#getycbcr)(int) | Ottiene il colore YCbCr con un numero specificato di bit per campione. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr#getycbcr_1)(int, int, int) | Ottiene il colore YCbCr con un numero specificato di bit per campione. |
| static [GetYcck](../../aspose.psd/pixeldataformat/getycck)(int) | Ottiene il colore YCCK con un numero specificato di bit per campione. |
| override [Equals](../../aspose.psd/pixeldataformat/equals)(object) | Determina se è specificatoObject è uguale a questa istanza. |
| override [GetHashCode](../../aspose.psd/pixeldataformat/gethashcode)() | Restituisce un codice hash per questa istanza. |
| override [ToString](../../aspose.psd/pixeldataformat/tostring)() | Restituisce aString che rappresenta questa istanza. |
| [operator ==](../../aspose.psd/pixeldataformat/op_equality) | Restituisce il risultato dell'uguaglianza per due[`PixelDataFormat`](../pixeldataformat) classi. |
| [operator !=](../../aspose.psd/pixeldataformat/op_inequality) | Restituisce il risultato della non uguaglianza per due[`PixelDataFormat`](../pixeldataformat) classi. |

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
