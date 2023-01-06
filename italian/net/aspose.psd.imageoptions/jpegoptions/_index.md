---
title: JpegOptions
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Il formato del file jpeg crea opzioni.
type: docs
weight: 4770
url: /it/net/aspose.psd.imageoptions/jpegoptions/
---
## JpegOptions class

Il formato del file jpeg crea opzioni.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [JpegOptions](jpegoptions#constructor)() | Inizializza una nuova istanza di[`JpegOptions`](../jpegoptions) classe. |
| [JpegOptions](jpegoptions#constructor_1)(JpegOptions) | Inizializza una nuova istanza di[`JpegOptions`](../jpegoptions) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel) { get; set; } | Ottiene o imposta i bit per canale per l'immagine JPEG senza perdita di dati. Ora supportiamo da 2 a 8 bit per canale. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile) { get; set; } | Il profilo colore CMYK di destinazione per le immagini jpeg CMYK. Utilizzare per salvare le immagini. Deve essere abbinato a RGBColorProfile per una corretta conversione del colore. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype) { get; set; } | Ottiene o imposta il tipo di colore per l'immagine jpeg. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment) { get; set; } | Ottiene o imposta il commento del file jpeg. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype) { get; set; } | Ottiene o imposta il tipo di compressione. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Ottiene o imposta il carattere sostitutivo predefinito (carattere che verrà utilizzato per disegnare il testo durante l'esportazione in formato raster, se il carattere del livello esistente nel file PSD non è presente nel sistema). Per prendere il nome corretto del carattere predefinito può essere utilizzato il frammento di codice successivo : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] famiglie = col.Families; string defaultFontName = famiglie[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata) { get; set; } | Ottieni o imposta il contenitore dati exif |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Ottiene o imposta un valore che indica se [fotogramma intero]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling) { get; set; } | Ottiene o imposta i sottocampionamenti orizzontali per ogni componente. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif) { get; set; } | Ottiene o imposta jfif. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror) { get; set; } | Ottiene o imposta la differenza JPEG-LS associata alla codifica quasi senza perdita di dati (parametro NEAR dalla specifica JPEG-LS). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode) { get; set; } | Ottiene o imposta la modalità interleave JPEG-LS. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset) { get; set; } | Ottiene o imposta i parametri predefiniti JPEG-LS. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Le opzioni multipagina |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent) { get; set; } | Ottiene o imposta un valore che indica se i componenti rosso, verde e blu devono essere mischiati con un colore di sfondo, se è presente il canale alfa. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality) { get; set; } | Ottiene o imposta la qualità dell'immagine. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings) { get; set; } | Ottiene o imposta le impostazioni dell'ottimizzatore RD. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings) { get; set; } | Ottiene o imposta le impostazioni di risoluzione. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit) { get; set; } | Ottiene o imposta l'unità di risoluzione. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile) { get; set; } | Il profilo colore RGB di destinazione per le immagini jpeg CMYK. Utilizzare per salvare le immagini. Deve essere abbinato a CMYKColorProfile per una corretta conversione del colore. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode) { get; set; } | Ottiene o imposta la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit.BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality) { get; } | La qualità in scala. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Ottiene o imposta l'origine in cui creare l'immagine. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ottiene o imposta le opzioni di rasterizzazione del vettore. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling) { get; set; } | Ottiene o imposta i sottocampionamenti verticali per ogni componente. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata) { get; set; } | Ottiene o imposta il contenitore di metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | Clona questa istanza. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Elimina l'istanza corrente. |

### Esempi

Questo esempio illustra l'uso di Aspose.PSD per l'API .Net per convertire le immagini in formato Jpeg. Per raggiungere questo obiettivo, questo esempio carica un'immagine esistente e quindi la converte in formato file Jpeg.

```csharp
[C#]

//Crea un'istanza della classe image e la inizializza con un file esistente tramite il percorso del file
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Crea un'istanza della classe PsdOptions
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //Imposta la qualità al 50% per ridurre le dimensioni dell'immagine di output.
    jpegOptions.Quality = 50;

    //Imposta i commenti exif.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //Salva l'immagine nella posizione del disco con le impostazioni JpegOptions fornite
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

Questo esempio illustra l'uso di System.IO.Stream per creare un nuovo file immagine

```csharp
[C#]

//Crea un'istanza di PsdOptions e ne imposta le varie proprietà
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Crea un'istanza di System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Definisci la proprietà di origine per l'istanza di PsdOptions
//Il secondo parametro booleano determina se lo Stream viene eliminato una volta uscito dall'ambito
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Crea un'istanza di Image e chiama il metodo Create con PsdOptions come parametro per inizializzare l'oggetto Image   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //eseguo un po' di elaborazione delle immagini
}
```

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
