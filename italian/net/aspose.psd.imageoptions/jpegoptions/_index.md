---
title: Class JpegOptions
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.ImageOptions.JpegOptions classe. Il formato file jpeg crea opzioni.
type: docs
weight: 4840
url: /it/net/aspose.psd.imageoptions/jpegoptions/
---
## JpegOptions class

Il formato file jpeg crea opzioni.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | Inizializza una nuova istanza di`JpegOptions` classe. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | Inizializza una nuova istanza di`JpegOptions` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | Ottiene o imposta i bit per canale per l'immagine jpeg senza perdita di dati. Ora supportiamo da 2 a 8 bit per canale. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Ottiene o imposta l'hint della dimensione del buffer che è definita dimensione massima consentita per tutti i buffer interni. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | Il profilo colore CMYK di destinazione per le immagini jpeg CMYK. Utilizzare per salvare le immagini. Deve essere abbinato a RGBColorProfile per una corretta conversione del colore. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | Ottiene o imposta il tipo di colore per l'immagine jpeg. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | Ottiene o imposta il commento del file jpeg. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | Ottiene o imposta il tipo di compressione. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Ottiene o imposta il carattere sostitutivo predefinito (carattere che verrà utilizzato per disegnare il testo durante l'esportazione in raster, se il carattere del livello esistente nel file PSD non è presentato nel sistema). Per prendere il nome corretto del carattere predefinito può essere utilizzato il prossimo frammento di codice : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] famiglie = col.Families; string defaultFontName = famiglie[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | Ottieni o imposta il contenitore di dati exif |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Ottiene o imposta un valore che indica se [full frame]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | Ottiene o imposta i sottocampionamenti orizzontali per ciascun componente. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | Ottiene o imposta jfif. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | Ottiene o imposta la differenza JPEG-LS legata alla codifica quasi senza perdita (parametro NEAR dalla specifica JPEG-LS). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | Ottiene o imposta la modalità di interleave JPEG-LS. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | Ottiene o imposta i parametri predefiniti JPEG-LS. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Le opzioni multipagina |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Ottiene o imposta la tavolozza dei colori. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | Ottiene o imposta un valore che indica se i componenti rosso, verde e blu devono essere miscelati con un colore di sfondo, se è presente il canale alfa. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Ottiene o imposta il gestore dell'evento progress. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | Ottiene o imposta la qualità dell'immagine. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | Ottiene o imposta le impostazioni dell'ottimizzatore RD. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Ottiene o imposta le impostazioni di risoluzione. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | Ottiene o imposta l'unità di risoluzione. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | Il profilo colore RGB di destinazione per le immagini jpeg CMYK. Utilizzare per salvare le immagini. Deve essere abbinato a CMYKColorProfile per una corretta conversione del colore. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | Ottiene o imposta la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit.BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | La qualità ridimensionata. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Ottiene o imposta l'origine in cui creare l'immagine. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | Ottiene o imposta i sottocampionamenti verticali per ciascun componente. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | Ottiene o imposta il contenitore dei metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clona questa istanza. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina l'istanza corrente. |

### Esempi

Questo esempio dimostra l'uso di Aspose.PSD per l'API .Net per convertire le immagini in formato Jpeg. Per raggiungere questo obiettivo, questo esempio carica un'immagine esistente e quindi la converte in formato file Jpeg.

```csharp
[C#]

//Crea un'istanza della classe immagine e la inizializza con un file esistente tramite Percorso file
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

Questo esempio dimostra l'uso di System.IO.Stream per creare un nuovo file di immagine

```csharp
[C#]

//Crea un'istanza di PsdOptions e ne imposta le varie proprietà
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Crea un'istanza di System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Definire la proprietà di origine per l'istanza di PsdOptions
//Il secondo parametro booleano determina se lo Stream viene eliminato una volta uscito dall'ambito
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Crea un'istanza di Image e chiama il metodo Create con PsdOptions come parametro per inizializzare l'oggetto Image   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //fai un po' di elaborazione delle immagini
}
```

Questo esempio dimostra l'uso di classi diverse da SaveOptions Namespace per scopi di esportazione. Un'immagine di tipo Psd viene caricata in un'istanza di Image e quindi esportata in diversi formati.

```csharp
[C#]

//Carica un'immagine esistente in un'istanza della classe Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Esporta in formato file BMP utilizzando le opzioni predefinite
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Esporta in formato file JPEG utilizzando le opzioni predefinite
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Esporta nel formato di file JPEG 2000 utilizzando le opzioni predefinite
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Esporta in formato file PNG utilizzando le opzioni predefinite
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Esporta in formato file TIFF utilizzando le opzioni predefinite
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### Guarda anche

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* spazio dei nomi [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assemblea [Aspose.PSD](../../)


