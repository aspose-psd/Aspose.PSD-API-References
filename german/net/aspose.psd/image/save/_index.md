---
title: Image.Save
second_title: Aspose.PSD für .NET-API-Referenz
description: Image methode. Speichert die Bilddaten im zugrunde liegenden Stream.
type: docs
weight: 230
url: /de/net/aspose.psd/image/save/
---
## Save() {#save}

Speichert die Bilddaten im zugrunde liegenden Stream.

```csharp
public void Save()
```

### Siehe auch

* class [Image](../)
* namensraum [Aspose.PSD](../../image/)
* Montage [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad. |
| options | ImageOptionsBase | Die Optionen. |

### Beispiele

Das folgende Beispiel zeigt, wie Sie Adobe Illustrator-Dateien in das PDF-Format in Aspose.PSD exportieren können

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

Das folgende Beispiel zeigt, dass AsposePSD den Export von PSB-Dateien in ein PSD-Format unterstützt.

```csharp
[C#]

// Unterstützt das Speichern von PSB als PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Der folgende Code speichert PsdImage als PDF-Dokument mit auswählbarem Text.

```csharp
[C#]

// Beim Speichern von PSD in PDF wird kein auswählbarer Text bereitgestellt
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Das folgende Beispiel zeigt, wie Sie AI-Dateien in das PSD- und PNG-Format in Aspose.PSD exportieren können

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

Das folgende Beispiel zeigt, dass die Textausrichtung durch ITextPortion für rechts-nach-links-Sprachen ordnungsgemäß funktioniert.

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

Dieses Beispiel zeigt die einfachen Schritte zum Speichern eines Bildes. Um diesen Vorgang zu demonstrieren, laden wir eine vorhandene Datei von einem Speicherort auf der Festplatte, führen einen Drehvorgang für das Bild aus und speichern das Bild im Jpeg-Dateiformat unter Verwendung des Dateipfads

```csharp
[C#]

//Erstellen Sie eine Instanz der Bildklasse und initialisieren Sie sie mit einer vorhandenen Datei über den Dateipfad
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // Drehen Sie das Bild um 180 Grad um die X-Achse
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    //Speichern Sie das Bild als JPEG im Dateipfad mit den Standardeinstellungen von JpegOptions
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

Das folgende Beispiel zeigt, wie Sie die LayerGroup-Sichtbarkeit in Aspose.PSD ändern können

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// Änderungen an den Ebenennamen vornehmen und speichern
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Alles innerhalb einer Gruppe ausschalten
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

Das folgende Beispiel zeigt, wie Sie auf einer neu erstellten Ebene zeichnen können, wenn die einfache Konstruktorversion in Aspose.PSD verwendet wird

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

    // Zeichnen Sie ein Rechteck mit dem Stiftwerkzeug
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // zeichne ein weiteres Rechteck mit Solid Brush in blauer Farbe
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

Das folgende Beispiel zeigt, dass das Lesen und Speichern der Graustufen-16-Bit-PSD-Dateien in 16-Bit-RGB pro Kanal korrekt und ohne Ausnahme funktioniert.

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
    // Hier sollte keine Ausnahme sein.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Das folgende Beispiel zeigt, dass das Lesen und Speichern der Graustufen-16-Bit-PSD-Dateien in 8-Bit-Graustufen pro Kanal korrekt und ohne Ausnahme funktioniert.

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
    // Hier sollte keine Ausnahme sein.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Das folgende Beispiel zeigt, wie Sie den PassThrough-Ebenenmischmodus in Aspose.PSD verwenden können

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

Das folgende Beispiel zeigt, dass der Dokumentkonvertierungsfortschritt korrekt und ohne Ausnahme funktioniert.

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

Das folgende Beispiel zeigt, dass das Lesen und Speichern der Graustufen-16-Bit-PSD-Dateien korrekt und ohne Ausnahme funktioniert.

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
        // Hier sollte keine Ausnahme sein.
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

### Siehe auch

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namensraum [Aspose.PSD](../../image/)
* Montage [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad. |
| options | ImageOptionsBase | Die Optionen. |
| boundsRectangle | Rectangle | Das Zielbild umgrenzt ein Rechteck. Legen Sie das leere Rechteck für die Verwendung von Quellgrenzen fest. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Optionen |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Bildspeicherung fehlgeschlagen. |

### Siehe auch

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namensraum [Aspose.PSD](../../image/)
* Montage [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, in dem die Bilddaten gespeichert werden sollen. |
| optionsBase | ImageOptionsBase | Die Speicheroptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | OptionenBasis |
| ArgumentException | Speichern im angegebenen Format nicht möglich, da es derzeit nicht unterstützt wird.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Bildexport fehlgeschlagen. |

### Beispiele

Dieses Beispiel zeigt den Vorgang zum Speichern eines Bildes in MemoryStream. Um diesen Vorgang zu demonstrieren, lädt das Beispiel eine vorhandene Datei von einem Speicherort auf der Festplatte, führt einen Drehvorgang für das Bild aus und speichert das Bild im GIF-Format

```csharp
[C#]

//Eine Instanz von MemoryStream erstellen
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Erstellen Sie eine Instanz der Bildklasse und initialisieren Sie sie mit einer vorhandenen Datei über den Dateipfad
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        // Drehen Sie das Bild um 180 Grad um die X-Achse
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        //Speichern Sie das Bild als PSD in MemoryStream mit den standardmäßigen GifOptions-Einstellungen
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### Siehe auch

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namensraum [Aspose.PSD](../../image/)
* Montage [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, in dem die Bilddaten gespeichert werden sollen. |
| optionsBase | ImageOptionsBase | Die Speicheroptionen. |
| boundsRectangle | Rectangle | Das Zielbild umgrenzt ein Rechteck. Legen Sie das leere Rechteck für die Verwendung von Quellgrenzen fest. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | OptionenBasis |
| ArgumentException | Speichern im angegebenen Format nicht möglich, da es derzeit nicht unterstützt wird.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Bildexport fehlgeschlagen. |

### Siehe auch

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namensraum [Aspose.PSD](../../image/)
* Montage [Aspose.PSD](../../../)


