---
title: Image.Save
second_title: Aspose.PSD voor .NET API-referentie
description: Image methode. Slaat de afbeeldingsgegevens op in de onderliggende stream.
type: docs
weight: 230
url: /nl/net/aspose.psd/image/save/
---
## Save() {#save}

Slaat de afbeeldingsgegevens op in de onderliggende stream.

```csharp
public void Save()
```

### Zie ook

* class [Image](../)
* naamruimte [Aspose.PSD](../../image/)
* montage [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Slaat de objectgegevens op naar de opgegeven bestandslocatie in de opgegeven bestandsindeling volgens de opslagopties.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad. |
| options | ImageOptionsBase | De opties. |

### Voorbeelden

Het volgende voorbeeld laat zien hoe u Adobe Illustrator-bestanden kunt exporteren naar PDF-indeling in Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

Het volgende voorbeeld laat zien dat AsposePSD ondersteuning biedt voor het exporteren van PSB-bestanden naar een PSD-indeling.

```csharp
[C#]

// Ondersteuning voor het opslaan van PSB als PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

De volgende code slaat PsdImage op als PDF-document met selecteerbare tekst.

```csharp
[C#]

// PSD opslaan in PDF biedt geen selecteerbare tekst
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Het volgende voorbeeld laat zien hoe u een AI-bestand kunt exporteren naar PSD- en PNG-indeling in Aspose.PSD

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

Het volgende voorbeeld laat zien dat de tekstuitlijning via ITextPortion voor rechts-naar-links-talen correct werkt.

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

Dit voorbeeld toont de eenvoudige stappen om een afbeelding op te slaan. Om deze bewerking te demonstreren, laden we een bestaand bestand vanaf een bepaalde schijflocatie, voeren we de rotatiebewerking uit op de afbeelding en slaan we de afbeelding op in Jpeg-bestandsindeling met behulp van Bestandspad

```csharp
[C#]

// Maak een instantie van de afbeeldingsklasse en initialiseer deze met een bestaand bestand via Bestandspad
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // Draai de afbeelding 180 graden rond de X-as
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // Sla de afbeelding op als Jpeg naar bestandspad met standaard JpegOptions-instellingen
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

Het volgende voorbeeld laat zien hoe u de zichtbaarheid van LayerGroup in Aspose.PSD kunt wijzigen

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// breng wijzigingen aan in de laagnamen en sla deze op
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Schakel alles binnen een groep uit
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

Het volgende voorbeeld laat zien hoe u kunt tekenen op een nieuw gemaakte laag als de eenvoudige constructorversie wordt gebruikt in Aspose.PSD

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

    // teken een rechthoek met het gereedschap Pen
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // teken nog een rechthoek met Solid Brush in blauwe kleur
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

Het volgende voorbeeld laat zien dat het lezen en opslaan van de Grayscale 16 bit PSD-bestanden naar 16 bit per kanaal RGB correct en zonder uitzondering werkt.

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
    // Hier zou geen uitzondering moeten zijn.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Het volgende voorbeeld laat zien dat het lezen en opslaan van de Grayscale 16 bit PSD-bestanden naar 8 bit per kanaal Grayscale correct en zonder uitzondering werkt.

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
    // Hier zou geen uitzondering moeten zijn.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Het volgende voorbeeld laat zien hoe u de PassThrough-laagovervloeimodus in Aspose.PSD kunt gebruiken

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

Het volgende voorbeeld laat zien dat de voortgang van de documentconversie correct en zonder uitzondering werkt.

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

Het volgende voorbeeld laat zien dat het lezen en opslaan van de Grayscale 16 bit PSD-bestanden correct en zonder uitzondering werkt.

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
        // Hier zou geen uitzondering moeten zijn.
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

### Zie ook

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* naamruimte [Aspose.PSD](../../image/)
* montage [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Slaat de objectgegevens op naar de opgegeven bestandslocatie in de opgegeven bestandsindeling volgens de opslagopties.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad. |
| options | ImageOptionsBase | De opties. |
| boundsRectangle | Rectangle | De bestemmingsafbeelding begrenst de rechthoek. Stel de lege rechthoek in om zure grenzen te gebruiken. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | opties |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Het opslaan van afbeeldingen is mislukt. |

### Zie ook

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* naamruimte [Aspose.PSD](../../image/)
* montage [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Slaat de afbeeldingsgegevens op in de opgegeven stream in de opgegeven bestandsindeling volgens de opslagopties.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De stream waarin de gegevens van de afbeelding moeten worden opgeslagen. |
| optionsBase | ImageOptionsBase | De bewaaropties. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | optiesBase |
| ArgumentException | Kan niet opslaan in het opgegeven formaat omdat het momenteel niet wordt ondersteund.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Het exporteren van afbeeldingen is mislukt. |

### Voorbeelden

Dit voorbeeld toont het proces van het opslaan van een afbeelding in MemoryStream. Om deze bewerking te demonstreren, laadt u bijvoorbeeld een bestaand bestand vanaf een bepaalde schijflocatie, voert u de rotatiebewerking uit op de afbeelding en slaat u de afbeelding op in Gif-indeling

```csharp
[C#]

//Maak een exemplaar van MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    // Maak een instantie van de afbeeldingsklasse en initialiseer deze met een bestaand bestand via Bestandspad
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        // Draai de afbeelding 180 graden rond de X-as
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        // Sla de afbeelding op als PSD in MemoryStream met standaard GifOptions-instellingen
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### Zie ook

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* naamruimte [Aspose.PSD](../../image/)
* montage [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Slaat de afbeeldingsgegevens op in de opgegeven stream in de opgegeven bestandsindeling volgens de opslagopties.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De stream waarin de gegevens van de afbeelding moeten worden opgeslagen. |
| optionsBase | ImageOptionsBase | De bewaaropties. |
| boundsRectangle | Rectangle | De bestemmingsafbeelding begrenst de rechthoek. Stel de lege rechthoek in voor gebruiksbrongrenzen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | optiesBase |
| ArgumentException | Kan niet opslaan in het opgegeven formaat omdat het momenteel niet wordt ondersteund.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Het exporteren van afbeeldingen is mislukt. |

### Zie ook

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* naamruimte [Aspose.PSD](../../image/)
* montage [Aspose.PSD](../../../)


