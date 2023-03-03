---
title: Image.Load
second_title: Aspose.PSD für .NET-API-Referenz
description: Image methode. Lädt ein neues Bild aus der angegebenen Datei.
type: docs
weight: 20
url: /de/net/aspose.psd/image/load/
---
## Load(string, LoadOptions) {#load_3}

Lädt ein neues Bild aus der angegebenen Datei.

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad, aus dem das Bild geladen werden soll. |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Rückgabewert

Das geladene Bild.

### Siehe auch

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namensraum [Aspose.PSD](../../image/)
* Montage [Aspose.PSD](../../../)

---

## Load(string) {#load_2}

Lädt ein neues Bild aus der angegebenen Datei.

```csharp
public static Image Load(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad, aus dem das Bild geladen werden soll. |

### Rückgabewert

Das geladene Bild.

### Beispiele

Dieses Beispiel zeigt das Laden einer vorhandenen Bilddatei in eine Instanz von Aspose.PSD.Image unter Verwendung des angegebenen Dateipfads

```csharp
[C#]

//Bildinstanz erstellen und mit einer vorhandenen Bilddatei vom Speicherort initialisieren
string path = "C:\\temp\\image.psd";
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(path))
{
    // Bildverarbeitung durchführen
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

* class [Image](../)
* namensraum [Aspose.PSD](../../image/)
* Montage [Aspose.PSD](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

Lädt ein neues Bild aus dem angegebenen Stream.

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, aus dem das Bild geladen werden soll. |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Rückgabewert

Das geladene Bild.

### Siehe auch

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namensraum [Aspose.PSD](../../image/)
* Montage [Aspose.PSD](../../../)

---

## Load(Stream) {#load}

Lädt ein neues Bild aus dem angegebenen Stream.

```csharp
public static Image Load(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, aus dem das Bild geladen werden soll. |

### Rückgabewert

Das geladene Bild.

### Beispiele

Dieses Beispiel demonstriert die Verwendung von System.IO.Stream-Objekten zum Laden einer vorhandenen Bilddatei

```csharp
[C#]

//Eine Instanz von FileStream erstellen
using(System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\sample.psd",System.IO.FileMode.Open))
{
    //Eine Instanz der Image-Klasse erstellen und eine vorhandene Datei durch das FileStream-Objekt laden, indem die Load-Methode aufgerufen wird
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(stream))
    {
        // Bildverarbeitung durchführen.
    }
}
```

### Siehe auch

* class [Image](../)
* namensraum [Aspose.PSD](../../image/)
* Montage [Aspose.PSD](../../../)


