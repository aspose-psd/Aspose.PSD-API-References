---
title: "Klasse PngOptions"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.ImageOptions.PngOptions Klasse. Die Erstellungsoptionen für das PNG-Dateiformat"
type: docs
weight: 5370
url: /de/net/aspose.psd.imageoptions/pngoptions/
---
{{< psd/tize >}}
## PngOptions class

Die PNG-Datei-Format-Erstellungsoptionen.

```csharp
public class PngOptions : ImageOptionsBase
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PngOptions](pngoptions/#constructor)() | Initialisiert eine neue Instanz der `PngOptions`-Klasse. |
| [PngOptions](pngoptions/#constructor_1)(PngOptions) | Initialisiert eine neue Instanz der `PngOptions`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BitDepth](../../aspose.psd.imageoptions/pngoptions/bitdepth/) { get; set; } | Die Bit-Tiefe. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [ColorType](../../aspose.psd.imageoptions/pngoptions/colortype/) { get; set; } | Liest oder legt den Typ der Farbe fest. |
| [CompressionLevel](../../aspose.psd.imageoptions/pngoptions/compressionlevel/) { get; set; } | Der PNG-Bildkomprimierungsgrad im Bereich 0‑9, wobei 9 maximale Kompression und 0 der Speicher‑Modus ist. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Liest oder setzt die standardmäßige Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen-Schriftart in der PSD-Datei im System nicht vorhanden ist). Um den korrekten Namen der Standardschriftart zu erhalten, kann das folgende Code‑Snippet verwendet werden: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| [FilterType](../../aspose.psd.imageoptions/pngoptions/filtertype/) { get; set; } | Liest oder setzt den Filtertyp, der beim Speichern von PNG-Dateien verwendet wird. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Die Mehrseitenoptionen |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Liest oder setzt die Farbpalette. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Liest oder setzt den Fortschritts-Event-Handler. |
| [Progressive](../../aspose.psd.imageoptions/pngoptions/progressive/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob dieses `PngOptions` progressiv ist. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Liest oder setzt die Auflösungseinstellungen. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| override [XmpData](../../aspose.psd.imageoptions/pngoptions/xmpdata/) { get; set; } | Liest oder setzt den XMP‑Metadaten‑Container. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klonen Sie diese Instanz. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DefaultCompressionLevel](../../aspose.psd.imageoptions/pngoptions/defaultcompressionlevel/) | Der Standardkomprimierungsgrad. |

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

Dieses Beispiel demonstriert die Verwendung verschiedener Klassen aus dem SaveOptions‑Namespace für Exportzwecke. Ein Bild vom Typ Psd wird in eine Instanz von Image geladen und anschließend in mehrere Formate exportiert.

```csharp
[C#]

//Laden Sie ein vorhandenes Bild in eine Instanz der Image‑Klasse.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Exportieren Sie in das BMP‑Dateiformat mit den Standardoptionen.
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Exportieren in das JPEG-Dateiformat mit den Standardeinstellungen
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Exportieren in das JPEG 2000-Dateiformat mit den Standardeinstellungen
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Exportieren in das PNG-Dateiformat mit den Standardeinstellungen
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Exportieren in das TIFF-Dateiformat mit den Standardeinstellungen
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
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

Dieses Beispiel verwendet die Graphics class, um primitive Formen auf der Image Oberfläche zu erstellen. Um den Vorgang zu demonstrieren, erstellt das Beispiel ein neues Image im PSD‑Format und zeichnet primitive Formen auf der Image Oberfläche mithilfe der von der Graphics class bereitgestellten Draw‑Methoden, um es anschließend in das PSD‑Dateiformat zu exportieren.

```csharp
[C#]

//Erstelle eine Instanz von Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Erstelle und initialisiere eine Instanz der Klasse Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Leere die Graphics-Oberfläche
    graphics.Clear(Color.Wheat);

    //Zeichnen Sie einen Bogen, indem Sie das Pen‑Objekt mit schwarzer Farbe angeben, 
    //ein Rechteck, das den Bogen umgibt, Startwinkel und Sweep‑Winkel
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Zeichnen Sie eine Bézier-Kurve, indem Sie das Pen‑Objekt mit blauer Farbe und Koordinatenpunkten angeben.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Zeichnen Sie eine Kurve, indem Sie das Pen‑Objekt mit grüner Farbe und einem Array von Punkten angeben
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Zeichnen Sie eine Ellipse mit dem Pen‑Objekt und einem umgebenden Rechteck
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Zeichnen Sie eine Linie 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Zeichnen Sie ein Kuchen‑Segment
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Zeichnen Sie ein Polygon, indem Sie das Pen‑Objekt mit roter Farbe und einem Array von Punkten angeben
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Zeichnen Sie ein Rechteck
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Erstellen Sie ein SolidBrush‑Objekt und setzen Sie dessen verschiedene Eigenschaften
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Zeichnen Sie einen String mit dem SolidBrush-Objekt und Font an einem bestimmten Punkt
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Erstellen Sie eine Instanz von PngOptions und setzen Sie deren verschiedene Eigenschaften
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // Speichere alle Änderungen.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Siehe auch

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


