---
title: Class PsdOptions
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.ImageOptions.PsdOptions classe. Il formato di file psd crea opzioni.
type: docs
weight: 4900
url: /it/net/aspose.psd.imageoptions/psdoptions/
---
## PsdOptions class

Il formato di file psd crea opzioni.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PsdOptions](psdoptions/#constructor)() | Inizializza una nuova istanza di`PsdOptions` classe. |
| [PsdOptions](psdoptions/#constructor_1)(PsdImage) | Inizializza una nuova istanza di`PsdOptions` classe. |
| [PsdOptions](psdoptions/#constructor_2)(PsdOptions) | Inizializza una nuova istanza di`PsdOptions` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Ottiene o imposta l'hint della dimensione del buffer che è definita dimensione massima consentita per tutti i buffer interni. |
| [ChannelBitsCount](../../aspose.psd.imageoptions/psdoptions/channelbitscount/) { get; set; } | Ottiene o imposta il numero di bit per canale di colore. |
| [ChannelsCount](../../aspose.psd.imageoptions/psdoptions/channelscount/) { get; set; } | Ottiene o imposta il conteggio dei canali colore. |
| [ColorMode](../../aspose.psd.imageoptions/psdoptions/colormode/) { get; set; } | Ottiene o imposta la modalità colore psd. |
| [CompressionMethod](../../aspose.psd.imageoptions/psdoptions/compressionmethod/) { get; set; } | Ottiene o imposta il metodo di compressione psd. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Ottiene o imposta il carattere sostitutivo predefinito (carattere che verrà utilizzato per disegnare il testo durante l'esportazione in raster, se il carattere del livello esistente nel file PSD non è presentato nel sistema). Per prendere il nome corretto del carattere predefinito può essere utilizzato il prossimo frammento di codice : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] famiglie = col.Families; string defaultFontName = famiglie[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Ottiene o imposta un valore che indica se [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Le opzioni multipagina |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Ottiene o imposta la tavolozza dei colori. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Ottiene o imposta il gestore dell'evento progress. |
| [PsdVersion](../../aspose.psd.imageoptions/psdoptions/psdversion/) { get; set; } | Ottiene o imposta la versione del formato del file. Può essere PSD o PSB. |
| [RefreshImagePreviewData](../../aspose.psd.imageoptions/psdoptions/refreshimagepreviewdata/) { get; set; } | Ottiene o imposta un valore che indica se [aggiorna i dati di anteprima dell'immagine] - opzione utilizzata per massimizzare la compatibilità con altri visualizzatori di immagini PSD. Si prega di notare che i livelli di testo che disegnano il layout finale non sono supportati per la piattaforma Compact Framework |
| [RemoveGlobalTextEngineResource](../../aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource/) { get; set; } | Ottiene o imposta un valore che indica se - Rimuovi la risorsa del motore di testo globale - Utilizzato per alcuni file psd con livelli di testo, nel solo caso in cui non possono essere aperti in Adobe Photoshop dopo l'elaborazione (principalmente per font assenti correlati ai livelli di testo). Dopo aver utilizzato questa opzione, l'utente deve aprire il file Photoshop successivo: Menu "Testo" -&gt; "Elaborazione caratteri assenti". Dopo tale operazione, tutto il testo riapparirà. Si prega di notare che questa operazione potrebbe causare alcune modifiche finali al layout. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Ottiene o imposta le impostazioni di risoluzione. |
| [Resources](../../aspose.psd.imageoptions/psdoptions/resources/) { get; set; } | Ottiene o imposta le risorse psd. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Ottiene o imposta l'origine in cui creare l'immagine. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| [Version](../../aspose.psd.imageoptions/psdoptions/version/) { get; set; } | Ottiene o imposta la versione del file psd. |
| override [XmpData](../../aspose.psd.imageoptions/psdoptions/xmpdata/) { get; set; } | Ottieni o imposta il contenitore di dati XMP |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clona questa istanza. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina l'istanza corrente. |

### Esempi

L'esempio seguente mostra come esportare file AI in formato PSD e PNG in Aspose.PSD

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Questo esempio crea un nuovo file immagine in una posizione del disco come specificato dalla proprietà Source dell'istanza PsdOptions. Diverse proprietà per l'istanza PsdOptions vengono impostate prima di creare l'immagine effettiva. Soprattutto la proprietà Source, che in questo caso fa riferimento alla posizione effettiva del disco.

```csharp
[C#]

//Crea un'istanza di PsdOptions e imposta le sue varie proprietà
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Crea un'istanza di FileCreateSource e assegnala come origine per l'istanza di PsdOptions
//Il secondo parametro booleano determina se il file da creare è IsTemporal o meno
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Crea un'istanza di Image e inizializzala con un'istanza di PsdOptions chiamando il metodo Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //fai un po' di elaborazione delle immagini

    // salva tutte le modifiche
    image.Save();
}
```

L'esempio seguente dimostra che la lettura e il salvataggio dei file PSD a 16 bit in scala di grigi in RGB a 16 bit per canale funziona correttamente e senza eccezioni.

```csharp
[C#]

string sourceFilePath = "grayscale5x5.psd";
string exportFilePath = "rgb16bit5x5.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Rgb,
    ChannelBitsCount = 16,
    ChannelsCount = 4
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // Qui non dovrebbero esserci eccezioni.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

L'esempio seguente dimostra che la lettura e il salvataggio dei file PSD a 16 bit della scala di grigi nella scala di grigi a 8 bit per canale funziona correttamente e senza eccezioni.

```csharp
[C#]

string sourceFilePath = "grayscale16bit.psd";
string exportFilePath = "grayscale16bit_Grayscale8_2_RLE.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Grayscale,
    ChannelBitsCount = 8,
    ChannelsCount = 2
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // Qui non dovrebbero esserci eccezioni.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

L'esempio seguente mostra come utilizzare la modalità di fusione del livello PassThrough in Aspose.PSD

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

L'esempio seguente dimostra che l'avanzamento della conversione del documento funziona correttamente e senza eccezioni.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

Questo esempio mostra come caricare le informazioni sui pixel in un array di tipo colore, manipolare l'array e reimpostarlo sull'immagine. Per eseguire queste operazioni, questo esempio crea un nuovo file immagine (in formato PSD) utilizzando l'oggetto MemoryStream.

```csharp
[C#]

//Crea un'istanza di MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Crea un'istanza di PsdOptions e imposta le sue varie proprietà, inclusa la proprietà Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Crea un'istanza di Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Ottiene i pixel dell'immagine specificando l'area come confine dell'immagine
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Esegui il loop sull'array e imposta il colore del pixel indicizzato alternativo
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Imposta il colore del pixel indicizzato su giallo
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Imposta il colore del pixel indicizzato su blu
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Applica le modifiche dei pixel all'immagine
        image.SavePixels(image.Bounds, pixels);

        // salva tutte le modifiche.
        image.Save();
    }

    //Scrivi MemoryStream su file
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

L'esempio seguente dimostra che la lettura e il salvataggio dei file PSD a 16 bit in scala di grigi funziona correttamente e senza eccezioni.

```csharp
[C#]

Stack<string> outputFilePathStack = new Stack<string>();

void SaveToPsdThenLoadAndSaveToPng(
    string file,
    ColorModes colorMode,
    short channelBitsCount,
    short channelsCount,
    CompressionMethod compression,
    int layerNumber)
{
    string filePath = file + ".psd";
    string postfix = colorMode.ToString() + channelBitsCount + "_" + channelsCount + "_" + compression;
    string exportPath = file + postfix + ".psd";
    PsdOptions psdOptions = new PsdOptions()
    {
        ColorMode = colorMode,
        ChannelBitsCount = channelBitsCount,
        ChannelsCount = channelsCount,
        CompressionMethod = compression
    };

    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        RasterCachedImage raster = layerNumber >= 0 ? (RasterCachedImage)image.Layers[layerNumber] : image;

        Aspose.PSD.Graphics graphics = new Graphics(raster);
        int width = raster.Width;
        int height = raster.Height;
        Rectangle rect = new Rectangle(
            width / 3,
            height / 3,
            width - (2 * (width / 3)) - 1,
            height - (2 * (height / 3)) - 1);
        graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);

        image.Save(exportPath, psdOptions);
    }

    string pngExportPath = Path.ChangeExtension(exportPath, "png");
    using (PsdImage image = (PsdImage)Image.Load(exportPath))
    {
        // Qui non dovrebbero esserci eccezioni.
        image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
    }

    outputFilePathStack.Push(exportPath);
}

SaveToPsdThenLoadAndSaveToPng("grayscale5x5", ColorModes.Cmyk, 16, 5, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("cmyk16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("index8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
```

### Guarda anche

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* spazio dei nomi [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assemblea [Aspose.PSD](../../)


