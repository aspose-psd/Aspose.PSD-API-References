---
title: AiImage
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Limmagine di Adobe Illustrator AI
type: docs
weight: 1260
url: /it/net/aspose.psd.fileformats.ai/aiimage/
---
## AiImage class

L'immagine di Adobe Illustrator (AI)

```csharp
public sealed class AiImage : Image
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [AiImage](aiimage)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette) { get; set; } | Ottiene o imposta un valore che indica se regolare automaticamente la tavolozza. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor) { get; set; } | Ottiene o imposta un valore per il colore di sfondo. |
| override [BitsPerPixel](../../aspose.psd.fileformats.ai/aiimage/bitsperpixel) { get; } | Ottiene il numero di bit dell'immagine per pixel. |
| [Bounds](../../aspose.psd/image/bounds) { get; } | Ottiene i limiti dell'immagine. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [Container](../../aspose.psd/image/container) { get; } | Ottiene il[`Image`](../../aspose.psd/image) contenitore. |
| [DataSection](../../aspose.psd.fileformats.ai/aiimage/datasection) { get; } | Ottiene la sezione dati. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| override [FileFormat](../../aspose.psd.fileformats.ai/aiimage/fileformat) { get; } | Ottiene un valore di formato file |
| [FinalizeSection](../../aspose.psd.fileformats.ai/aiimage/finalizesection) { get; } | Ottiene la sezione di finalizzazione. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor) { get; set; } | Ottiene o imposta un valore che indica se l'immagine ha il colore di sfondo. |
| [Header](../../aspose.psd.fileformats.ai/aiimage/header) { get; } | Ottiene l'intestazione. |
| override [Height](../../aspose.psd.fileformats.ai/aiimage/height) { get; } | Ottiene l'altezza dell'immagine. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor) { get; set; } | Ottiene o imposta il monitor di interruzione. |
| override [IsCached](../../aspose.psd.fileformats.ai/aiimage/iscached) { get; } | Ottiene un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è richiesta la lettura dei dati. |
| [Layers](../../aspose.psd.fileformats.ai/aiimage/layers) { get; } | Ottiene le sezioni del livello. |
| [Palette](../../aspose.psd/image/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| [SetupSection](../../aspose.psd.fileformats.ai/aiimage/setupsection) { get; } | Ottiene la sezione di configurazione. |
| [Size](../../aspose.psd/image/size) { get; } | Ottiene la dimensione dell'immagine. |
| [Version](../../aspose.psd.fileformats.ai/aiimage/version) { get; } | Ottiene la versione del formato Adobe Illustrator |
| override [Width](../../aspose.psd.fileformats.ai/aiimage/width) { get; } | Ottiene la larghezza dell'immagine. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.ai/aiimage/addlayer)(AiLayerSection) | Aggiunge la sezione del livello AI. |
| override [CacheData](../../aspose.psd.fileformats.ai/aiimage/cachedata)() | Memorizza i dati nella cache e garantisce che nessun ulteriore caricamento dei dati venga eseguito dal sottostante[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.psd/image/cansave)(ImageOptionsBase) | Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio passate. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Elimina l'istanza corrente. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions)(object[]) | Ottiene le opzioni predefinite. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions)() | Ottiene le opzioni in base alle impostazioni del file originale. Questo può essere utile per mantenere invariati la profondità di bit e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e quindi salvalo usando il [`Save`](../../aspose.psd/datastreamsupporter/save) metodo, verrà prodotta l'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, utilizzare questo metodo per ottenere le opzioni di salvataggio corrispondenti e passarle al[`Save`](../../aspose.psd/image/save)metodo come secondo parametro. |
| [Resize](../../aspose.psd/image/resize)(int, int) | Ridimensiona l'immagine. Il predefinitoLeftTopToLeftTopviene utilizzato. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize#resize_1)(int, int, ImageResizeSettings) | Ridimensiona l'immagine. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize#resize_2)(int, int, ResizeType) | Ridimensiona l'immagine. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int) | Ridimensiona proporzionalmente l'altezza. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int, ImageResizeSettings) | Ridimensiona proporzionalmente l'altezza. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int, ResizeType) | Ridimensiona proporzionalmente l'altezza. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int) | Ridimensiona proporzionalmente la larghezza. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int, ImageResizeSettings) | Ridimensiona proporzionalmente la larghezza. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| override [RotateFlip](../../aspose.psd.fileformats.ai/aiimage/rotateflip)(RotateFlipType) | Ruota, capovolge o ruota e capovolge l'immagine. |
| [Save](../../aspose.psd/image/save)() | Salva i dati dell'immagine nel flusso sottostante. |
| [Save](../../aspose.psd/datastreamsupporter/save)(Stream) | Salva i dati dell'oggetto nel flusso specificato. |
| [Save](../../aspose.psd/datastreamsupporter/save)(string) | Salva i dati dell'oggetto nella posizione del file specificata. |
| [Save](../../aspose.psd/image/save)(Stream, ImageOptionsBase) | Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save)(string, bool) | Salva i dati dell'oggetto nella posizione del file specificata. |
| virtual [Save](../../aspose.psd/image/save)(string, ImageOptionsBase) | Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.psd/image/save)(Stream, ImageOptionsBase, Rectangle) | Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.psd/image/save)(string, ImageOptionsBase, Rectangle) | Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio. |
| override [SetPalette](../../aspose.psd.fileformats.ai/aiimage/setpalette)(IColorPalette, bool) | Imposta la tavolozza dell'immagine. |

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

L'esempio seguente mostra il supporto dell'esportazione del formato Ai nei formati PSD, PNG, JPG, GIF e TIF.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"34992OStroke",
    @"rect2_color",
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string name = sourcesFiles[i];
    string sourceFileName = name + ".ai";

    using (AiImage image = (AiImage)Image.Load(sourceFileName))
    {
        string outFileName = name + ".psd";
        ImageOptionsBase options = new PsdOptions();
        image.Save(outFileName, options);

        outFileName = name + ".png";
        options = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
        image.Save(outFileName, options);

        outFileName = name + ".jpg";
        options = new JpegOptions() { Quality = 85 };
        image.Save(outFileName, options);

        outFileName = name + ".gif";
        options = new GifOptions() { DoPaletteCorrection = false };
        image.Save(outFileName, options);

        outFileName = name + ".tif";
        options = new TiffOptions(TiffExpectedFormat.TiffDeflateRgba);
        image.Save(outFileName, options);
    }
}
```

### Guarda anche

* class [Image](../../aspose.psd/image)
* spazio dei nomi [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
