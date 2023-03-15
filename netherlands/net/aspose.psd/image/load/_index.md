---
title: Image.Load
second_title: Aspose.PSD voor .NET API-referentie
description: Image methode. Laadt een nieuwe afbeelding uit het opgegeven bestand.
type: docs
weight: 20
url: /nl/net/aspose.psd/image/load/
---
## Load(string, LoadOptions) {#load_3}

Laadt een nieuwe afbeelding uit het opgegeven bestand.

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad waaruit de afbeelding moet worden geladen. |
| loadOptions | LoadOptions | De laadopties. |

### Winstwaarde

De geladen afbeelding.

### Zie ook

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* naamruimte [Aspose.PSD](../../image/)
* montage [Aspose.PSD](../../../)

---

## Load(string) {#load_2}

Laadt een nieuwe afbeelding uit het opgegeven bestand.

```csharp
public static Image Load(string filePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad waaruit de afbeelding moet worden geladen. |

### Winstwaarde

De geladen afbeelding.

### Voorbeelden

Dit voorbeeld demonstreert het laden van een bestaand afbeeldingsbestand in een exemplaar van Aspose.PSD.Image met behulp van het opgegeven bestandspad

```csharp
[C#]

//Maak een afbeeldingsinstantie en initialiseer deze met een bestaand afbeeldingsbestand vanaf de schijflocatie
string path = "C:\\temp\\image.psd";
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(path))
{
    // doe wat beeldverwerking
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

* class [Image](../)
* naamruimte [Aspose.PSD](../../image/)
* montage [Aspose.PSD](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

Laadt een nieuwe afbeelding van de opgegeven stream.

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De stream waaruit de afbeelding moet worden geladen. |
| loadOptions | LoadOptions | De laadopties. |

### Winstwaarde

De geladen afbeelding.

### Zie ook

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* naamruimte [Aspose.PSD](../../image/)
* montage [Aspose.PSD](../../../)

---

## Load(Stream) {#load}

Laadt een nieuwe afbeelding van de opgegeven stream.

```csharp
public static Image Load(Stream stream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De stream waaruit de afbeelding moet worden geladen. |

### Winstwaarde

De geladen afbeelding.

### Voorbeelden

Dit voorbeeld demonstreert het gebruik van System.IO.Stream-objecten om een bestaand afbeeldingsbestand te laden

```csharp
[C#]

//Maak een instantie van FileStream
using(System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\sample.psd",System.IO.FileMode.Open))
{
    //Maak een instantie van de klasse Image en laad een bestaand bestand via het FileStream-object door de methode Load aan te roepen
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(stream))
    {
        // doe wat beeldverwerking.
    }
}
```

### Zie ook

* class [Image](../)
* naamruimte [Aspose.PSD](../../image/)
* montage [Aspose.PSD](../../../)


