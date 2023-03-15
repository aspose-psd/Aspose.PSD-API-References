---
title: Class TiffOptions
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.ImageOptions.TiffOptions classe. Le opzioni del formato del file tiff. Nota che i tag di larghezza e altezza verranno sovrascritti durante la creazione dellimmagine dai parametri di larghezza e altezza quindi non è necessario specificarli direttamente. Nota che molte opzioni restituiscono un valore predefinito ma ciò non significa che questa opzione è impostata esplicitamente come valore di tag. Per verificare la presenza del tag utilizzare la proprietà Tags o il metodo IsTagPresent corrispondente.
type: docs
weight: 4940
url: /it/net/aspose.psd.imageoptions/tiffoptions/
---
## TiffOptions class

Le opzioni del formato del file tiff. Nota che i tag di larghezza e altezza verranno sovrascritti durante la creazione dell'immagine dai parametri di larghezza e altezza, quindi non è necessario specificarli direttamente. Nota che molte opzioni restituiscono un valore predefinito ma ciò non significa che questa opzione è impostata esplicitamente come valore di tag. Per verificare la presenza del tag utilizzare la proprietà Tags o il metodo IsTagPresent corrispondente.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | Inizializza una nuova istanza di`TiffOptions` classe. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | Inizializza una nuova istanza di`TiffOptions` classe. Per impostazione predefinita viene utilizzata la convenzione little endian. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | Inizializza una nuova istanza di`TiffOptions` classe. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Inizializza una nuova istanza di`TiffOptions` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | Ottiene o imposta l'opzione di archiviazione alfa. Opzioni diverse daUnspecified sono usati quando ce ne sono più di 3[`SamplesPerPixel`](./samplesperpixel/) definito. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | Ottiene o imposta l'artista. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | Ottiene i bit per pixel. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | Ottiene o imposta i bit per campione. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Ottiene o imposta l'hint della dimensione del buffer che è definita dimensione massima consentita per tutti i buffer interni. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | Ottiene o imposta un valore che indica l'ordine dei byte tiff. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | Ottiene o imposta la mappa dei colori. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | Ottiene o imposta la qualità dell'immagine compressa. Utilizzato con la compressione Jpeg. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | Ottiene o imposta la compressione. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | Ottiene o imposta il copyright. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | Ottiene o imposta la data e l'ora. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Ottiene o imposta il carattere sostitutivo predefinito (carattere che verrà utilizzato per disegnare il testo durante l'esportazione in raster, se il carattere del livello esistente nel file PSD non è presentato nel sistema). Per prendere il nome corretto del carattere predefinito può essere utilizzato il prossimo frammento di codice : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] famiglie = col.Families; string defaultFontName = famiglie[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | Ottiene o imposta il nome del documento. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | Ottiene o imposta il puntatore a EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | Ottiene o imposta le opzioni fax t4. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | Ottiene o imposta lo standard del file TIFF. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | Ottiene o imposta l'ordine di riempimento dei bit di byte. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Ottiene o imposta un valore che indica se [full frame]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | Ottiene o imposta i suggerimenti sui mezzitoni. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Ottiene o imposta il flusso del profilo Icc. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | Ottiene o imposta la descrizione dell'immagine. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | Ottiene o imposta la lunghezza dell'immagine. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | Ottiene o imposta la larghezza dell'immagine. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | Ottiene o imposta i nomi degli inchiostri. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Ottiene un valore che indica se sono presenti campioni extra. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | Ottiene un valore che indica se l'immagine è affiancata. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | Ottiene un valore che indica se il`TiffOptions` sono stati correttamente configurati. Utilizzare il metodo Validate per trovare il motivo dell'errore. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Ottiene o imposta il valore massimo del campione. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Ottiene o imposta il valore minimo del campione. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Le opzioni multipagina |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | Ottiene o imposta l'orientamento. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | Ottiene o imposta il nome della pagina. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | Ottiene o imposta il tag del numero di pagina. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | Ottiene o imposta la tavolozza dei colori. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | Ottiene o imposta la fotometrica. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Ottiene o imposta la configurazione planare. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | Ottiene o imposta il predittore per la compressione LZW. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Ottiene o imposta un valore che indica se i componenti devono essere premoltiplicati. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Ottiene o imposta il gestore dell'evento progress. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Ottiene o imposta le impostazioni di risoluzione. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Ottiene o imposta l'unità di risoluzione. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Ottiene o imposta le righe per striscia. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | Ottiene o imposta il formato di esempio. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | Ottiene i campioni per pixel. Per modificare questo valore di proprietà utilizzare il[`BitsPerSample`](./bitspersample/) impostatore di proprietà. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Ottiene o imposta il produttore dello scanner. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | Ottiene o imposta il modello dello scanner. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Ottiene o imposta il valore massimo del campione. Il valore ha un tipo di campo che meglio corrisponde ai dati di esempio (tipo Byte, Short o Long). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Ottiene o imposta il valore minimo del campione. Il valore ha un tipo di campo che meglio corrisponde ai dati di esempio (tipo Byte, Short o Long). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | Ottiene o imposta il tipo di software. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Ottiene o imposta l'origine in cui creare l'immagine. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Ottiene o imposta il conteggio dei byte delle strisce. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Ottiene o imposta gli offset della striscia. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | Ottiene o imposta un'indicazione generale del tipo di dati contenuti in questo sottofile. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | Ottiene o imposta i tag. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | Ottiene o imposta la stampante di destinazione. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | Ottiene o imposta la soglia. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Ottiene o imposta il numero di byte del riquadro. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | Ottiene o imposta la lunghezza del riquadro. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Ottiene o imposta gli offset delle tessere. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | Ottiene o imposta la larghezza del riquadro. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | Ottiene le pagine totali. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | Ottiene il conteggio dei tag validi. Questo non è il conteggio totale dei tag, ma il numero di tag che possono essere conservati. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | Ottiene o imposta il contenitore dei metadati XMP. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Ottiene o imposta l'autore dell'immagine, utilizzato da Esplora risorse. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Ottiene o imposta il commento sull'immagine, utilizzato da Windows Explorer. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Ottiene o imposta l'immagine del soggetto, utilizzata da Esplora risorse. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | Ottiene o imposta la posizione x. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Ottiene o imposta informazioni sull'immagine, utilizzate da Windows Explorer. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Ottiene o imposta informazioni sull'immagine, utilizzate da Windows Explorer. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | Ottiene o imposta la risoluzione x. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | Ottiene o imposta YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | Ottiene o imposta i fattori di sottocampionamento per YCbCr fotometrico. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | Ottiene o imposta la posizione y. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | Ottiene o imposta la risoluzione y. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | Aggiunge un nuovo tag. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Aggiunge i tag. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clona questa istanza. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina l'istanza corrente. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Ottiene l'istanza del tag per tipo. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Determina se il tag è presente o meno nelle opzioni. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | Rimuove il tag. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | Convalida se le opzioni hanno una combinazione valida di tag |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Ottiene il conteggio dei tag validi. |

### Esempi

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

Questi esempi utilizzano la classe GraphicsPath e Graphics per creare e manipolare figure su una superficie immagine. L'esempio crea una nuova immagine e disegna percorsi con l'aiuto della classe GraphicsPath. Alla fine viene chiamato il metodo DrawPath esposto dalla classe Graphics per rendere i percorsi sulla superficie. Infine l'immagine viene esportata nel formato di file Tiff.

```csharp
[C#]

//Crea un'istanza di Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea e inizializza un'istanza della classe Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Superficie grafica chiara
    graphics.Clear(Color.Wheat);

    //Crea un'istanza della classe GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Crea un'istanza della classe Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Aggiungi forme all'oggetto Figura
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Aggiungi l'oggetto Figura a GraphicsPath
    graphicspath.AddFigure(figure);

    //Disegna il percorso con l'oggetto Penna di colore Nero
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Crea un'istanza di TiffOptions e imposta le sue varie proprietà
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // salva tutte le modifiche.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Guarda anche

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* spazio dei nomi [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assemblea [Aspose.PSD](../../)


