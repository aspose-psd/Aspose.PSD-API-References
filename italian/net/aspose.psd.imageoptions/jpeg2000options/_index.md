---
title: Jpeg2000Options
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Le opzioni del formato del file JPEG2000.
type: docs
weight: 4760
url: /it/net/aspose.psd.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

Le opzioni del formato del file JPEG2000.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Jpeg2000Options](jpeg2000options#constructor)() | Inizializza una nuova istanza di[`Jpeg2000Options`](../jpeg2000options) classe. |
| [Jpeg2000Options](jpeg2000options#constructor_1)(Jpeg2000Options) | Inizializza una nuova istanza di[`Jpeg2000Options`](../jpeg2000options) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [Codec](../../aspose.psd.imageoptions/jpeg2000options/codec) { get; set; } | Ottiene o imposta il codec JPEG2000 |
| [Comments](../../aspose.psd.imageoptions/jpeg2000options/comments) { get; set; } | Ottiene o imposta i marcatori di commento JPEG. |
| [CompressionRatios](../../aspose.psd.imageoptions/jpeg2000options/compressionratios) { get; set; } | Ottiene o imposta il rapporto di compressione dell'array. Rapporti di compressione diversi per livelli successivi. Il tasso specificato per ciascun livello di qualità è il fattore di compressione desiderato . Rapporti decrescenti richiesti. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Ottiene o imposta il carattere sostitutivo predefinito (carattere che verrà utilizzato per disegnare il testo durante l'esportazione in formato raster, se il carattere del livello esistente nel file PSD non è presente nel sistema). Per prendere il nome corretto del carattere predefinito può essere utilizzato il frammento di codice successivo : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] famiglie = col.Families; string defaultFontName = famiglie[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Ottiene o imposta un valore che indica se [fotogramma intero]. |
| [Irreversible](../../aspose.psd.imageoptions/jpeg2000options/irreversible) { get; set; } | Ottiene o imposta un valore che indica se utilizzare la compressione DWT 9-7 irreversibile (true) o utilizzare la compressione DWT 5-3 senza perdita di dati (predefinita). |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Le opzioni multipagina |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Ottiene o imposta il gestore dell'evento di avanzamento. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings) { get; set; } | Ottiene o imposta le impostazioni di risoluzione. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Ottiene o imposta l'origine in cui creare l'immagine. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ottiene o imposta le opzioni di rasterizzazione del vettore. |
| override [XmpData](../../aspose.psd.imageoptions/jpeg2000options/xmpdata) { get; set; } | Ottiene o imposta il contenitore di metadati XMP. |

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
