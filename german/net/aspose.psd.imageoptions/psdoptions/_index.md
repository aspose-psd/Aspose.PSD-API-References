---
title: "Klasse PsdOptions"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.ImageOptions.PsdOptions Klasse. Die Erstellungsoptionen für das PSD-Dateiformat"
type: docs
weight: 5390
url: /de/net/aspose.psd.imageoptions/psdoptions/
---
{{< psd/tize >}}
## PsdOptions class

Die PSD-Datei-Format-Erstellungsoptionen.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PsdOptions](psdoptions/#constructor)() | Initialisiert eine neue Instanz der `PsdOptions`-Klasse. |
| [PsdOptions](psdoptions/#constructor_1)(PsdImage) | Initialisiert eine neue Instanz der `PsdOptions`-Klasse. |
| [PsdOptions](psdoptions/#constructor_2)(PsdOptions) | Initialisiert eine neue Instanz der `PsdOptions`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundContents](../../aspose.psd.imageoptions/psdoptions/backgroundcontents/) { get; set; } | Liest oder setzt die Hintergrundfarbe. Sie kann bei transparenten Objekten gesehen werden. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [ChannelBitsCount](../../aspose.psd.imageoptions/psdoptions/channelbitscount/) { get; set; } | Liest oder setzt die Bitanzahl pro Farbkanal. |
| [ChannelsCount](../../aspose.psd.imageoptions/psdoptions/channelscount/) { get; set; } | Liest oder setzt die Anzahl der Farbkanäle. |
| [ColorMode](../../aspose.psd.imageoptions/psdoptions/colormode/) { get; set; } | Liest oder setzt den PSD-Farbmodus. |
| [CompressionMethod](../../aspose.psd.imageoptions/psdoptions/compressionmethod/) { get; set; } | Liest oder setzt die PSD-Komprimierungsmethode. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Liest oder setzt die standardmäßige Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen-Schriftart in der PSD-Datei im System nicht vorhanden ist). Um den korrekten Namen der Standardschriftart zu erhalten, kann das folgende Code‑Snippet verwendet werden: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Die Mehrseitenoptionen |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Liest oder setzt die Farbpalette. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Liest oder setzt den Fortschritts-Event-Handler. |
| [PsdVersion](../../aspose.psd.imageoptions/psdoptions/psdversion/) { get; set; } | Liest oder setzt die Dateiformatversion. Sie kann PSD oder PSB sein. |
| [RefreshImagePreviewData](../../aspose.psd.imageoptions/psdoptions/refreshimagepreviewdata/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [refresh image preview data] - Option zur Maximierung der Kompatibilität mit anderen PSD-Bildbetrachtern verwendet wird. Bitte beachten Sie, dass das Zeichnen von Textebenen in das endgültige Layout für die Compact Framework-Plattform nicht unterstützt wird. |
| [RemoveGlobalTextEngineResource](../../aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob - Die globale Text-Engine-Ressource entfernt wird - Wird für einige textschichtige PSD-Dateien verwendet, ausschließlich in dem Fall, dass sie nach der Verarbeitung nicht in Adobe Photoshop geöffnet werden können (hauptsächlich bei fehlenden Schriftarten in Textebenen). Nach der Verwendung dieser Option muss der Benutzer im geöffneten Photoshop-Dokument Folgendes ausführen: Menü "Text" -> "Process absent fonts". Nach diesem Vorgang werden alle Texte wieder angezeigt. Bitte beachten Sie, dass dieser Vorgang einige Änderungen im endgültigen Layout verursachen kann. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Liest oder setzt die Auflösungseinstellungen. |
| [Resources](../../aspose.psd.imageoptions/psdoptions/resources/) { get; set; } | Liest oder setzt die PSD-Ressourcen. Wenn Wert: NULL - dann die ursprünglichen ImageResources speichern (Standardverhalten) Nicht leer - dann die in diese Eigenschaft übergebenen Ressourcen + [required resources] speichern. Leer - dann nur [required resources] gespeichert werden. Erforderliche Ressourcen: ResolutionInfoResource, XmpResource |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| [UpdateMetadata](../../aspose.psd.imageoptions/psdoptions/updatemetadata/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [update metadata]. Ist der Wert true, werden die Metadaten beim Speichern eines Bildes aktualisiert. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| [Version](../../aspose.psd.imageoptions/psdoptions/version/) { get; set; } | Liest oder setzt die PSD-Dateiversion. |
| override [XmpData](../../aspose.psd.imageoptions/psdoptions/xmpdata/) { get; set; } | Lese oder setze den XMP-Datencontainer |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klonen Sie diese Instanz. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |

## Beispiele

Das folgende Beispiel zeigt, wie Sie eine AI-Datei in das PSD- und PNG-Format in Aspose.PSD exportieren können.

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

Dieses Beispiel erstellt eine neue Bilddatei an einem Speicherort, der durch die Source‑Eigenschaft der PsdOptions‑Instanz angegeben ist. Mehrere Eigenschaften der PsdOptions‑Instanz werden gesetzt, bevor das eigentliche Bild erstellt wird. Insbesondere die Source‑Eigenschaft, die in diesem Fall auf den tatsächlichen Speicherort verweist.

```csharp
[C#]

//Erstellen Sie eine Instanz von PsdOptions und setzen Sie deren verschiedene Eigenschaften.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Source für die Instanz von PsdOptions zu.
//Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei temporär ist oder nicht.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Erstellen Sie eine Instanz von Image und initialisieren Sie sie mit einer Instanz von PsdOptions, indem Sie die Create‑Methode aufrufen.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Führe einige Bildverarbeitungen durch

    // Alle Änderungen speichern
    image.Save();
}
```

Das folgende Beispiel zeigt, dass das Lesen und Speichern von 16‑Bit‑Graustufen‑PSD‑Dateien in 16‑Bit‑pro‑Kanal‑RGB korrekt funktioniert und ohne Ausnahme.

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
    // Hier sollte keine Ausnahme auftreten.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Das folgende Beispiel zeigt, dass das Lesen und Speichern von 16‑Bit‑Graustufen‑PSD‑Dateien in 8‑Bit‑pro‑Kanal‑Graustufen korrekt funktioniert und ohne Ausnahme.

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
    // Hier sollte keine Ausnahme auftreten.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Das folgende Beispiel zeigt, wie Sie den PassThrough‑Ebenen‑Blendmodus in Aspose.PSD verwenden können.

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

Das folgende Beispiel demonstriert, dass der Dokumentkonvertierungsfortschritt korrekt funktioniert und ohne Ausnahme.

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

Dieses Beispiel zeigt, wie Pixelinformationen in einem Array vom Typ Color geladen, das Array manipuliert und zurück zum Bild gesetzt werden. Um diese Vorgänge auszuführen, erstellt dieses Beispiel eine neue Bilddatei (im PSD-Format) mithilfe eines MemoryStream-Objekts.

```csharp
[C#]

//Erstelle eine Instanz von MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Erstelle eine Instanz von PsdOptions und setze deren verschiedene Eigenschaften, einschließlich der Source-Eigenschaft
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Erstelle eine Instanz von Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Hole die Pixel des Bildes, indem du den Bereich als Bildgrenze angibst
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Durchlaufe das Array und setze die Farbe des alternativen indizierten Pixels
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Setze die Farbe des indizierten Pixels auf Gelb
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Setze die Farbe des indizierten Pixels auf Blau
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Wende die Pixeländerungen auf das Bild an
        image.SavePixels(image.Bounds, pixels);

        // Speichere alle Änderungen.
        image.Save();
    }

    //Schreibe MemoryStream in eine Datei
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

Das folgende Beispiel demonstriert, dass das Lesen und Speichern von 16‑Bit Graustufen‑PSD‑Dateien korrekt und ohne Ausnahme funktioniert.

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
        // Hier sollte keine Ausnahme auftreten.
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

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


