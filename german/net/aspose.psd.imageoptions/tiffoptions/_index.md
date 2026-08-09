---
title: "Klasse TiffOptions"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.ImageOptions.TiffOptions Klasse. Die TIFF-Dateiformatoptionen. Hinweis: Breiten- und Höhen-Tags werden bei der Bildgenerierung durch die Breiten- und Höhen‑Parameter überschrieben, sodass sie nicht direkt angegeben werden müssen. Hinweis: Viele Optionen geben einen Standardwert zurück, das bedeutet jedoch nicht, dass diese Option explizit als Tag‑Wert gesetzt ist. Um zu prüfen, ob das Tag vorhanden ist, verwenden Sie die Tags‑Eigenschaft oder die entsprechende IsTagPresent‑Methode."
type: docs
weight: 5430
url: /de/net/aspose.psd.imageoptions/tiffoptions/
---
{{< psd/tize >}}
## TiffOptions class

Die TIFF-Datei-Formatoptionen. Hinweis: Die Breiten- und Höhen-Tags werden bei der Bildgenerierung durch die Breiten- und Höhen-Parameter überschrieben, sodass sie nicht direkt angegeben werden müssen. Hinweis: Viele Optionen geben einen Standardwert zurück, was nicht bedeutet, dass diese Option explizit als Tag-Wert gesetzt ist. Um zu überprüfen, ob das Tag vorhanden ist, verwenden Sie die Tags‑Eigenschaft oder die entsprechende IsTagPresent‑Methode.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | Initialisiert eine neue Instanz der `TiffOptions` Klasse. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | Initialisiert eine neue Instanz der `TiffOptions` Klasse. Standardmäßig wird die Little‑Endian‑Konvention verwendet. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | Initialisiert eine neue Instanz der `TiffOptions` Klasse. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Initialisiert eine neue Instanz der `TiffOptions` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | Liest oder setzt die Alpha‑Speicheroption. Optionen außer Unspecified werden verwendet, wenn mehr als 3 [`SamplesPerPixel`](./samplesperpixel/) definiert sind. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | Liest oder setzt den Künstler. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | Liest die Bits pro Pixel. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | Liest oder setzt die Bits pro Sample. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | Liest oder setzt einen Wert, der die TIFF-Byte-Reihenfolge angibt. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | Liest oder setzt die Farbkarte. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | Liest oder setzt die komprimierte Bildqualität. Wird mit der JPEG-Kompression verwendet. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | Liest oder setzt die Kompression. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | Liest oder setzt das Urheberrecht. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | Liest oder setzt Datum und Uhrzeit. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/tiffoptions/defaultmemoryallocationlimit/) { get; set; } | Liest oder setzt das Standard‑Limit für Speicherzuweisungen. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Liest oder setzt die standardmäßige Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen-Schriftart in der PSD-Datei im System nicht vorhanden ist). Um den korrekten Namen der Standardschriftart zu erhalten, kann das folgende Code‑Snippet verwendet werden: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | Liest oder setzt den Namen des Dokuments. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | Liest oder setzt den Zeiger auf EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | Liest oder setzt die Fax‑T4‑Optionen. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | Liest oder setzt den TIFF-Dateistandard. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | Liest oder setzt die Füllreihenfolge der Byte‑Bits. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [full frame]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | Liest oder setzt die Halbton‑Hinweise. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Liest oder setzt den ICC‑Profil‑Stream. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | Liest oder setzt die Bildbeschreibung. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | Liest oder setzt die Bildlänge. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | Liest oder setzt die Bildbreite. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | Liest oder setzt die Tinten­namen. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Liest einen Wert, der angibt, ob zusätzliche Proben vorhanden sind. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | Liest einen Wert, der angibt, ob das Bild gekachelt ist. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | Liest einen Wert, der angibt, ob die `TiffOptions` korrekt konfiguriert wurden. Verwenden Sie die Validate‑Methode, um den Fehlgrund zu finden. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Liest oder setzt den maximalen Sample‑Wert. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Liest oder setzt den minimalen Sample‑Wert. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Die Mehrseitenoptionen |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | Liest oder setzt die Orientierung. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | Liest oder setzt den Seitennamen. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | Liest oder setzt das Seitenzahl-Tag. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | Liest oder setzt die Farbpalette. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | Liest oder setzt die Photometrie. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Liest oder setzt die planare Konfiguration. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | Liest oder setzt den Prädiktor für LZW-Kompression. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob Komponenten vormultipliziert werden müssen. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Liest oder setzt den Fortschritts-Event-Handler. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Liest oder setzt die Auflösungseinstellungen. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Liest oder setzt die Auflösungseinheit. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Liest oder setzt die Zeilen pro Streifen. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | Liest oder setzt das Sample-Format. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | Liest die Samples pro Pixel. Um diesen Eigenschaftswert zu ändern, verwenden Sie den Setter der [`BitsPerSample`](./bitspersample/) Eigenschaft. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Liest oder setzt den Scanner-Hersteller. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | Liest oder setzt das Scanner-Modell. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Liest oder setzt den maximalen Sample-Wert. Der Wert hat einen Feldtyp, der am besten zu den Sample-Daten passt (Byte-, Short- oder Long-Typ). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Liest oder setzt den minimalen Sample-Wert. Der Wert hat einen Feldtyp, der am besten zu den Sample-Daten passt (Byte-, Short- oder Long-Typ). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | Liest oder setzt den Softwaretyp. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Liest oder setzt die Byte-Anzahl der Streifen. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Liest oder setzt die Streifen-Offsets. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | Liest oder setzt eine allgemeine Angabe zur Art der in dieser Unterdatei enthaltenen Daten. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | Liest oder setzt die Tags. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | Liest oder setzt den Ziel-Drucker. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | Liest oder setzt die Schwellenwertbestimmung. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Liest oder setzt die Byte-Anzahl der Kacheln. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | Liest ot setzt die Kachel-Länge. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Liest oder setzt die Kachel-Offsets. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | Liest ot setzt die Kachel-Breite. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | Liest die Gesamtseiten. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | Liest die gültige Tag-Anzahl. Dies ist nicht die Gesamtzahl der Tags, sondern die Anzahl der Tags, die erhalten bleiben können. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | Liest oder setzt den XMP‑Metadaten‑Container. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Liest oder setzt den Bildautor, der von Windows Explorer verwendet wird. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Liest oder setzt den Kommentar zum Bild, der von Windows Explorer verwendet wird. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Liest oder setzt das Bildthema, das von Windows Explorer verwendet wird. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | Liest oder setzt die x-Position. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Liest oder setzt Informationen über das Bild, die von Windows Explorer verwendet werden. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Liest oder setzt Informationen über das Bild, die von Windows Explorer verwendet werden. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | Liest oder setzt die x-Auflösung. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | Liest oder setzt die YCbCr-Koeffizienten. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | Liest oder setzt die Subsampling-Faktoren für die YCbCr-Photometrie. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | Liest oder setzt die y-Position. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | Liest oder setzt die y-Auflösung. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | Fügt ein neues Tag hinzu. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Fügt die Tags hinzu. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klonen Sie diese Instanz. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Liest die Instanz des Tags nach Typ. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Bestimmt, ob das Tag in den Optionen vorhanden ist oder nicht. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | Entfernt das Tag. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | Validiert, ob die Optionen eine gültige Kombination von Tags haben |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Ermittelt die gültige Anzahl von Tags. |

## Beispiele

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

Dieses Beispiel verwendet die Klassen GraphicsPath und Graphics, um Figuren auf einer Bildoberfläche zu erstellen und zu manipulieren. Das Beispiel erstellt ein neues Bild und zeichnet Pfade mit Hilfe der Klasse GraphicsPath. Am Ende wird die von der Klasse Graphics bereitgestellte Methode DrawPath aufgerufen, um die Pfade auf der Oberfläche zu rendern. Schließlich wird das Bild in das Tiff-Dateiformat exportiert.

```csharp
[C#]

//Erstelle eine Instanz von Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Erstelle und initialisiere eine Instanz der Klasse Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Leere die Graphics-Oberfläche
    graphics.Clear(Color.Wheat);

    //Erstelle eine Instanz der Klasse GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Erstelle eine Instanz der Klasse Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Füge Formen zum Figure-Objekt hinzu
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Füge das Figure-Objekt zu GraphicsPath hinzu
    graphicspath.AddFigure(figure);

    //Zeichne Pfad mit Pen-Objekt in der Farbe Schwarz
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Erstellen Sie eine Instanz von TiffOptions und setzen Sie deren verschiedene Eigenschaften
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // Speichere alle Änderungen.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Siehe auch

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


