---
title: Save
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Salva i dati dellimmagine nel flusso sottostante.
type: docs
weight: 230
url: /it/net/aspose.psd/image/save/
---
## Save() {#save}

Salva i dati dell'immagine nel flusso sottostante.

```csharp
public void Save()
```

### Guarda anche

* class [Image](../../image)
* spazio dei nomi [Aspose.PSD](../../image)
* assemblea [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file. |
| options | ImageOptionsBase | Le opzioni. |

### Esempi

L'esempio seguente mostra come esportare file Adobe Illustrator in formato PDF in Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

L'esempio seguente dimostra che AsposePSD supporta l'esportazione di file PSB in un formato PSD.

```csharp
[C#]

// Supporta il salvataggio di PSB come PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Il codice seguente salva PsdImage come documento PDF con testo selezionabile.

```csharp
[C#]

// Il salvataggio di PSD in PDF non fornisce testo selezionabile
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

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

Nell'esempio seguente viene illustrato che l'allineamento del testo tramite ITextPortion per le lingue da destra a sinistra funziona correttamente.

```csharp
[C#]

string sourceFilePath = "bidi.psd";
string exportFilePath = "bidiOutput.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    TextLayer layer = (TextLayer)image.Layers[2];
    ITextPortion[] portions = layer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Center;
    layer.TextData.UpdateLayerData();

    image.Save(exportFilePath);
}
```

Questo esempio mostra i semplici passaggi per salvare un'immagine. Per dimostrare questa operazione, carichiamo un file esistente da una posizione su disco, eseguiamo l'operazione Ruota sull'immagine e salviamo l'immagine in formato file Jpeg usando File Path

```csharp
[C#]

//Crea un'istanza della classe image e inizializzala con un file esistente tramite il percorso del file
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Ruota l'immagine di 180 gradi sull'asse X
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    //Salva l'immagine come Jpeg nel percorso del file con le impostazioni JpegOptions predefinite
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

L'esempio seguente mostra come modificare la visibilità LayerGroup in Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// apportare modifiche ai nomi dei livelli e salvarlo
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Disattiva tutto all'interno di un gruppo
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

L'esempio seguente mostra come disegnare su un livello appena creato se in Aspose.PSD viene utilizzata la versione del costruttore semplice

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // disegna un rettangolo con lo strumento Penna
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // disegna un altro rettangolo con Pennello solido in colore blu
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

L'esempio seguente dimostra che la lettura e il salvataggio dei file PSD in scala di grigi a 16 bit a 16 bit per canale RGB funzionano correttamente e senza eccezioni.

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

L'esempio seguente dimostra che la lettura e il salvataggio dei file PSD in scala di grigi a 16 bit su scala di grigi a 8 bit per canale funzionano correttamente e senza eccezioni.

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

L'esempio seguente mostra come utilizzare la modalità di fusione dei livelli PassThrough in Aspose.PSD

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

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* spazio dei nomi [Aspose.PSD](../../image)
* assemblea [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file. |
| options | ImageOptionsBase | Le opzioni. |
| boundsRectangle | Rectangle | L'immagine di destinazione delimita il rettangolo. Imposta il rettangolo vuoto per utilizzare i limiti sorgente. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | opzioni |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception) | Salvataggio dell'immagine non riuscito. |

### Guarda anche

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* spazio dei nomi [Aspose.PSD](../../image)
* assemblea [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso in cui salvare i dati dell'immagine. |
| optionsBase | ImageOptionsBase | Le opzioni di salvataggio. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | opzioniBase |
| ArgumentException | Impossibile salvare nel formato specificato poiché al momento non è supportato.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception) | Esportazione dell'immagine non riuscita. |

### Esempi

Questo esempio mostra il processo di salvataggio di un'immagine in MemoryStream. Per dimostrare questa operazione, l'esempio carica un file esistente da una posizione del disco, esegue l'operazione Ruota sull'immagine e Salva l'immagine in formato Gif

```csharp
[C#]

//Crea un'istanza di MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Crea un'istanza della classe image e inizializzala con un file esistente tramite il percorso del file
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        //Ruota l'immagine di 180 gradi sull'asse X
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        //Salva l'immagine come PSD su MemoryStream con le impostazioni GifOptions predefinite
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### Guarda anche

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* spazio dei nomi [Aspose.PSD](../../image)
* assemblea [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso in cui salvare i dati dell'immagine. |
| optionsBase | ImageOptionsBase | Le opzioni di salvataggio. |
| boundsRectangle | Rectangle | L'immagine di destinazione delimita il rettangolo. Imposta il rettangolo vuoto per utilizzare i limiti di origine. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | opzioniBase |
| ArgumentException | Impossibile salvare nel formato specificato poiché al momento non è supportato.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception) | Esportazione dell'immagine non riuscita. |

### Guarda anche

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* spazio dei nomi [Aspose.PSD](../../image)
* assemblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
