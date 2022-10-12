---
title: GifOptions
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Opzioni di creazione del formato file gif.
type: docs
weight: 4740
url: /it/net/aspose.psd.imageoptions/gifoptions/
---
## GifOptions class

Opzioni di creazione del formato file gif.

```csharp
public class GifOptions : ImageOptionsBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GifOptions](gifoptions#constructor)() | Inizializza una nuova istanza di[`GifOptions`](../gifoptions) classe. |
| [GifOptions](gifoptions#constructor_1)(GifOptions) | Inizializza una nuova istanza di[`GifOptions`](../gifoptions) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex) { get; set; } | Ottiene o imposta l'indice del colore di sfondo GIF. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution) { get; set; } | Ottiene o imposta la risoluzione del colore GIF. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Ottiene o imposta il carattere sostitutivo predefinito (carattere che verrà utilizzato per disegnare il testo durante l'esportazione in formato raster, se il carattere del livello esistente nel file PSD non è presente nel sistema). Per prendere il nome corretto del carattere predefinito può essere utilizzato il frammento di codice successivo : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] famiglie = col.Families; string defaultFontName = famiglie[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection) { get; set; } | Ottiene o imposta un valore che indica se è stata applicata la correzione della tavolozza. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Ottiene o imposta un valore che indica se [fotogramma intero]. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer) { get; set; } | Ottiene o imposta un valore che indica se GIF ha trailer. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced) { get; set; } | Vero se l'immagine deve essere interlacciata. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted) { get; set; } | Ottiene o imposta un valore che indica se le voci della tavolozza sono ordinate. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff) { get; set; } | Ottiene o imposta la differenza di pixel massima consentita. Se maggiore di zero, verrà utilizzata la compressione con perdita. Il valore consigliato per una compressione con perdita ottimale è 80. 30 è una compressione molto leggera, 200 è pesante. Funziona meglio quando viene introdotta solo una piccola perdita ea causa della limitazione dell'algoritmo di compressione livelli di perdita molto elevati non daranno molto guadagno. L'intervallo di valori consentiti è [0, 1000]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Le opzioni multipagina |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio) { get; set; } | Ottiene o imposta le proporzioni dei pixel GIF. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Ottiene o imposta il gestore dell'evento di avanzamento. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings) { get; set; } | Ottiene o imposta le impostazioni di risoluzione. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Ottiene o imposta l'origine in cui creare l'immagine. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ottiene o imposta le opzioni di rasterizzazione del vettore. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata) { get; set; } | Ottiene o imposta il contenitore di metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | Clona questa istanza. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Elimina l'istanza corrente. |

### Esempi

Questo esempio mostra l'uso di classi diverse da SaveOptions Namespace per scopi di esportazione. Un'immagine di tipo Psd viene caricata in un'istanza di Image e quindi esportata in diversi formati.

```csharp
[C#]

//Carica un'immagine esistente in un'istanza della classe Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Esporta in formato file BMP utilizzando le opzioni predefinite
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Esporta in formato file JPEG utilizzando le opzioni predefinite
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Esporta in formato file JPEG 2000 utilizzando le opzioni predefinite
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Esporta in formato file PNG utilizzando le opzioni predefinite
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Esporta in formato file TIFF utilizzando le opzioni predefinite
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### Guarda anche

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase)
* spazio dei nomi [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
