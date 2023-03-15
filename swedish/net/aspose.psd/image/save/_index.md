---
title: Image.Save
second_title: Aspose.PSD för .NET API-referens
description: Image metod. Sparar bilddata till den underliggande strömmen.
type: docs
weight: 230
url: /sv/net/aspose.psd/image/save/
---
## Save() {#save}

Sparar bilddata till den underliggande strömmen.

```csharp
public void Save()
```

### Se även

* class [Image](../)
* namnutrymme [Aspose.PSD](../../image/)
* hopsättning [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen. |
| options | ImageOptionsBase | Alternativen. |

### Exempel

Följande exempel visar hur du kan exportera Adobe Illustrator-filer till PDF-format i Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

Följande exempel visar att AsposePSD stöder PSB-filer som exporteras till ett PSD-format.

```csharp
[C#]

// Stöd för att spara PSB som PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Följande kod sparar PsdImage som PDF-dokument med valbar text.

```csharp
[C#]

// Att spara PSD i PDF ger inte valbar text
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Följande exempel visar hur du kan exportera AI-fil till PSD- och PNG-format i Aspose.PSD

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

Följande exempel visar att textjustering genom ITextPortion för höger-till-vänster-språk fungerar korrekt.

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

Det här exemplet visar de enkla stegen för att spara en bild. För att demonstrera denna operation, laddar vi en befintlig fil från någon diskplats, utför rotera operationen på bilden och sparar bilden i Jpeg-filformat med hjälp av filsökväg

```csharp
[C#]

//Skapa en instans av bildklass och initiera den med en befintlig fil via filsökväg
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Rotera bilden 180 grader runt X-axeln
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    //Spara bilden som Jpeg till filsökväg med standardinställningar för JpegOptions
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

Följande exempel visar hur du kan ändra LayerGroup-synlighet i Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// gör ändringar i lagernamn och spara det
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Stäng av allt i en grupp
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

Följande exempel visar hur du kan rita på ett nyskapat lager om den enkla konstruktorversionen används i Aspose.PSD

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

    // rita en rektangel med pennverktyget
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // rita ytterligare en rektangel med Solid Brush i blå färg
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

Följande exempel visar att läsning och lagring av Gråskala 16-bitars PSD-filer till 16bit per kanal RGB fungerar korrekt och utan undantag.

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
    // Här bör inget undantag vara.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Följande exempel visar att läsning och lagring av Gråskala 16 bitars PSD-filer till 8 bitar per kanal Gråskala fungerar korrekt och utan undantag.

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
    // Här bör inget undantag vara.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Följande exempel visar hur du kan använda blandningsläget PassThrough-lager i Aspose.PSD

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

Följande exempel visar att dokumentkonverteringen fungerar korrekt och utan undantag.

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

Följande exempel visar att läsning och lagring av Gråskala 16 bitars PSD-filer fungerar korrekt och utan undantag.

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
        // Här bör inget undantag vara.
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

### Se även

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namnutrymme [Aspose.PSD](../../image/)
* hopsättning [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen. |
| options | ImageOptionsBase | Alternativen. |
| boundsRectangle | Rectangle | Målbilden avgränsar rektangeln. Ställ in den tomma rektangeln för att använda sura gränser. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | alternativ |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Det gick inte att spara bild. |

### Se även

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namnutrymme [Aspose.PSD](../../image/)
* hopsättning [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Streamen att spara bildens data till. |
| optionsBase | ImageOptionsBase | Spara alternativen. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | alternativBas |
| ArgumentException | Det går inte att spara i det angivna formatet eftersom det inte stöds för tillfället.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Bildexport misslyckades. |

### Exempel

Det här exemplet visar processen att spara en bild i MemoryStream. För att demonstrera den här åtgärden, laddar exemplet en befintlig fil från någon diskplats, utför rotationsoperationen på bilden och sparar bilden i Gif-format

```csharp
[C#]

//Skapa en instans av MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Skapa en instans av bildklass och initiera den med en befintlig fil via filsökväg
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        //Rotera bilden 180 grader runt X-axeln
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        //Spara bilden som PSD till MemoryStream med standardinställningar för GifOptions
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### Se även

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namnutrymme [Aspose.PSD](../../image/)
* hopsättning [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Streamen att spara bildens data till. |
| optionsBase | ImageOptionsBase | Spara alternativen. |
| boundsRectangle | Rectangle | Målbilden avgränsar rektangeln. Ställ in den tomma rektangeln för användningskällans gränser. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | alternativBas |
| ArgumentException | Det går inte att spara i det angivna formatet eftersom det inte stöds för tillfället.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Bildexport misslyckades. |

### Se även

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namnutrymme [Aspose.PSD](../../image/)
* hopsättning [Aspose.PSD](../../../)


