---
title: PsdOptions
second_title: Aspose.PSD für .NET-API-Referenz
description: Optionen zum Erstellen des PSDDateiformats.
type: docs
weight: 4830
url: /de/net/aspose.psd.imageoptions/psdoptions/
---
## PsdOptions class

Optionen zum Erstellen des PSD-Dateiformats.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PsdOptions](psdoptions#constructor)() | Initialisiert eine neue Instanz von[`PsdOptions`](../psdoptions) Klasse. |
| [PsdOptions](psdoptions#constructor_1)(PsdImage) | Initialisiert eine neue Instanz von[`PsdOptions`](../psdoptions) Klasse. |
| [PsdOptions](psdoptions#constructor_2)(PsdOptions) | Initialisiert eine neue Instanz von[`PsdOptions`](../psdoptions) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [ChannelBitsCount](../../aspose.psd.imageoptions/psdoptions/channelbitscount) { get; set; } | Ruft die Anzahl der Bits pro Farbkanal ab oder setzt sie. |
| [ChannelsCount](../../aspose.psd.imageoptions/psdoptions/channelscount) { get; set; } | Ruft die Anzahl der Farbkanäle ab oder legt sie fest. |
| [ColorMode](../../aspose.psd.imageoptions/psdoptions/colormode) { get; set; } | Ruft den PSD-Farbmodus ab oder legt ihn fest. |
| [CompressionMethod](../../aspose.psd.imageoptions/psdoptions/compressionmethod) { get; set; } | Ruft die psd-Komprimierungsmethode ab oder legt sie fest. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Ruft die Standard-Ersatzschriftart ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Exportieren in Raster verwendet wird, wenn die vorhandene Layer-Schriftart in der PSD-Datei nicht im System angezeigt wird). Um den richtigen Namen der Standardschriftart zu übernehmen, kann das nächste Code-Snippet verwendet werden : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] Familie = col.Families; string defaultFontName = Familie[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Vollbild]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Die mehrseitigen Optionen |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Ruft den Fortschrittsereignishandler ab oder legt ihn fest. |
| [PsdVersion](../../aspose.psd.imageoptions/psdoptions/psdversion) { get; set; } | Ruft die Version des Dateiformats ab oder legt sie fest. Es kann PSD oder PSB sein. |
| [RefreshImagePreviewData](../../aspose.psd.imageoptions/psdoptions/refreshimagepreviewdata) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Bildvorschaudaten aktualisieren] - Option, die verwendet wird, um die Kompatibilität mit anderen PSD-Bildbetrachtern zu maximieren. Bitte beachten Sie, dass das Zeichnen von Textebenen im endgültigen Layout für die Compact Framework-Plattform nicht unterstützt wird |
| [RemoveGlobalTextEngineResource](../../aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource) { get; set; } | Erhält oder setzt einen Wert, der angibt, ob - die globale Text-Engine-Ressource entfernt wird - nur für einige PSD-Dateien mit Textebenen verwendet wird, wenn sie nach der Verarbeitung nicht in Adobe Photoshop geöffnet werden können (hauptsächlich für Textebenen mit fehlenden Schriftarten). Nachdem Sie diese Option verwendet haben, müssen Sie als Nächstes die in Photoshop geöffnete Datei erstellen: Menü „Text“ -&gt; „Fehlende Schriftarten verarbeiten“. Nach diesem Vorgang wird der gesamte Text wieder angezeigt. Bitte beachten Sie, dass dieser Vorgang einige endgültige Layoutänderungen verursachen kann. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings) { get; set; } | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [Resources](../../aspose.psd.imageoptions/psdoptions/resources) { get; set; } | Ruft die PSD-Ressourcen ab oder legt sie fest. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Ruft die Quelle zum Erstellen des Bildes ab oder legt sie fest. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ruft die Optionen für die Vektorrasterung ab oder legt sie fest. |
| [Version](../../aspose.psd.imageoptions/psdoptions/version) { get; set; } | Ruft die PSD-Dateiversion ab oder legt sie fest. |
| override [XmpData](../../aspose.psd.imageoptions/psdoptions/xmpdata) { get; set; } | XMP-Datencontainer abrufen oder festlegen |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | Klont diese Instanz. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |

### Beispiele

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

In diesem Beispiel wird eine neue Bilddatei an einem Speicherort auf dem Datenträger erstellt, wie durch die Source-Eigenschaft der PsdOptions-Instanz angegeben. Mehrere Eigenschaften für die PsdOptions-Instanz werden festgelegt, bevor das eigentliche Bild erstellt wird. Insbesondere die Source-Eigenschaft, die sich in diesem Fall auf den tatsächlichen Speicherort der Festplatte bezieht.

```csharp
[C#]

//Eine Instanz von PsdOptions erstellen und ihre verschiedenen Eigenschaften festlegen
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Eine Instanz von FileCreateSource erstellen und als Quelle für die Instanz von PsdOptions zuweisen
//Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei Temporär ist oder nicht
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

// Erstellen Sie eine Instanz von Image und initialisieren Sie sie mit einer Instanz von PsdOptions, indem Sie die Create-Methode aufrufen
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // Bildverarbeitung durchführen

    // Alle Änderungen speichern
    image.Save();
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

Dieses Beispiel zeigt, wie Pixelinformationen in ein Array vom Typ Color geladen, das Array manipuliert und wieder auf das Bild gesetzt wird. Um diese Vorgänge auszuführen, erstellt dieses Beispiel eine neue Bilddatei (im PSD-Format) mit dem MemoryStream-Objekt.

```csharp
[C#]

//Eine Instanz von MemoryStream erstellen
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Erstellen Sie eine Instanz von PsdOptions und legen Sie die verschiedenen Eigenschaften einschließlich der Source-Eigenschaft fest
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Eine Instanz von Image erstellen
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Die Pixel des Bildes abrufen, indem der Bereich als Bildgrenze angegeben wird
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        // Schleife über das Array und setzt die Farbe des alternativen indizierten Pixels
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Indizierte Pixelfarbe auf gelb setzen
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Indizierte Pixelfarbe auf Blau setzen
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        // Pixeländerungen auf das Bild anwenden
        image.SavePixels(image.Bounds, pixels);

        // Alle Änderungen speichern.
        image.Save();
    }

    //MemoryStream in Datei schreiben
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
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

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase)
* namensraum [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
