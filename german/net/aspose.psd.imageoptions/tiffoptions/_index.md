---
title: TiffOptions
second_title: Aspose.PSD für .NET-API-Referenz
description: Die TIFFDateiformatoptionen. Beachten Sie dass Breiten und HöhenTags bei der Bilderzeugung durch Breiten und Höhenparameter überschrieben werden sodass sie nicht direkt angegeben werden müssen. Beachten Sie dass viele Optionen einen Standardwert zurückgeben aber das bedeutet nicht diese Option wird explizit als TagWert festgelegt. Um zu überprüfen ob das Tag vorhanden ist verwenden Sie die TagsEigenschaft oder die entsprechende IsTagPresentMethode.
type: docs
weight: 4870
url: /de/net/aspose.psd.imageoptions/tiffoptions/
---
## TiffOptions class

Die TIFF-Dateiformatoptionen. Beachten Sie, dass Breiten- und Höhen-Tags bei der Bilderzeugung durch Breiten- und Höhenparameter überschrieben werden, sodass sie nicht direkt angegeben werden müssen. Beachten Sie, dass viele Optionen einen Standardwert zurückgeben, aber das bedeutet nicht diese Option wird explizit als Tag-Wert festgelegt. Um zu überprüfen, ob das Tag vorhanden ist, verwenden Sie die Tags-Eigenschaft oder die entsprechende IsTagPresent-Methode.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TiffOptions](tiffoptions#constructor_2)(TiffDataType[]) | Initialisiert eine neue Instanz von[`TiffOptions`](../tiffoptions) Klasse. |
| [TiffOptions](tiffoptions#constructor)(TiffExpectedFormat) | Initialisiert eine neue Instanz von[`TiffOptions`](../tiffoptions) Klasse. Standardmäßig wird die Little-Endian-Konvention verwendet. |
| [TiffOptions](tiffoptions#constructor_3)(TiffOptions) | Initialisiert eine neue Instanz von[`TiffOptions`](../tiffoptions) Klasse. |
| [TiffOptions](tiffoptions#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Initialisiert eine neue Instanz von[`TiffOptions`](../tiffoptions) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage) { get; set; } | Ruft die Alpha-Speicheroption ab oder legt sie fest. Andere Optionen alsUnspecified werden verwendet, wenn es mehr als 3 gibt[`SamplesPerPixel`](./samplesperpixel) definiert. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist) { get; set; } | Ruft den Künstler ab oder legt ihn fest. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel) { get; } | Ruft die Bits pro Pixel ab. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample) { get; set; } | Holt oder setzt die Bits pro Sample. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der die TIFF-Byte-Reihenfolge angibt. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap) { get; set; } | Ruft die Farbkarte ab oder legt sie fest. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality) { get; set; } | Ruft die komprimierte Bildqualität ab oder legt sie fest. Wird mit der JPEG-Komprimierung verwendet. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression) { get; set; } | Ruft die Komprimierung ab oder legt sie fest. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright) { get; set; } | Ruft das Urheberrecht ab oder legt es fest. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime) { get; set; } | Ruft Datum und Uhrzeit ab oder legt sie fest. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Ruft die Standard-Ersatzschriftart ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Exportieren in Raster verwendet wird, wenn die vorhandene Layer-Schriftart in der PSD-Datei nicht im System angezeigt wird). Um den richtigen Namen der Standardschriftart zu übernehmen, kann das nächste Code-Snippet verwendet werden : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] Familie = col.Families; string defaultFontName = Familie[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname) { get; set; } | Ruft den Namen des Dokuments ab oder legt ihn fest. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd) { get; } | Holt oder setzt den Zeiger auf EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options) { get; set; } | Ruft die Fax-t4-Optionen ab oder legt sie fest. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard) { get; set; } | Ruft den TIFF-Dateistandard ab oder legt ihn fest. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder) { get; set; } | Ruft die Füllreihenfolge der Byte-Bits ab oder legt sie fest. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Vollbild]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints) { get; set; } | Ruft die Halbtonhinweise ab oder legt sie fest. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile) { get; set; } | Ruft den Icc-Profilstream ab oder legt ihn fest. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription) { get; set; } | Ruft die Bildbeschreibung ab oder legt sie fest. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength) { get; set; } | Ruft die Bildlänge ab oder legt sie fest. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth) { get; set; } | Ruft die Bildbreite ab oder legt sie fest. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames) { get; set; } | Ruft die Tintennamen ab oder legt sie fest. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent) { get; } | Ruft einen Wert ab, der angibt, ob die zusätzlichen Proben vorhanden sind. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled) { get; } | Ruft einen Wert ab, der angibt, ob das Bild gekachelt ist. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid) { get; } | Ruft einen Wert ab, der angibt, ob die[`TiffOptions`](../tiffoptions) richtig konfiguriert wurden. Verwenden Sie die Validate-Methode, um die Fehlerursache zu finden. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue) { get; set; } | Ruft den maximalen Abtastwert ab oder legt ihn fest. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue) { get; set; } | Ruft den minimalen Abtastwert ab oder legt ihn fest. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Die mehrseitigen Optionen |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation) { get; set; } | Ruft die Ausrichtung ab oder legt sie fest. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename) { get; set; } | Ruft den Seitennamen ab oder legt ihn fest. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber) { get; set; } | Ruft das Seitenzahl-Tag ab oder legt es fest. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric) { get; set; } | Ruft die photometrischen Daten ab oder legt sie fest. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration) { get; set; } | Ruft die planare Konfiguration ab oder legt sie fest. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor) { get; set; } | Ruft den Prädiktor für die LZW-Komprimierung ab oder legt ihn fest. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob Komponenten vormultipliziert werden müssen. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Ruft den Fortschrittsereignishandler ab oder legt ihn fest. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings) { get; set; } | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit) { get; set; } | Ruft die Auflösungseinheit ab oder legt sie fest. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip) { get; set; } | Ruft die Zeilen pro Streifen ab oder legt sie fest. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat) { get; set; } | Ruft das Beispielformat ab oder legt es fest. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel) { get; } | Ruft die Samples pro Pixel ab. Um diesen Eigenschaftswert zu ändern, verwenden Sie die[`BitsPerSample`](./bitspersample) Property-Setter. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer) { get; set; } | Ruft den Scannerhersteller ab oder legt ihn fest. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel) { get; set; } | Ruft das Scannermodell ab oder legt es fest. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue) { get; set; } | Ruft den maximalen Abtastwert ab oder setzt ihn. Der Wert hat einen Feldtyp, der am besten zu den Beispieldaten passt (Typ Byte, Short oder Long). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue) { get; set; } | Ruft den minimalen Abtastwert ab oder setzt ihn. Der Wert hat einen Feldtyp, der am besten zu den Beispieldaten passt (Typ Byte, Short oder Long). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype) { get; set; } | Ruft den Softwaretyp ab oder legt ihn fest. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Ruft die Quelle zum Erstellen des Bildes ab oder legt sie fest. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts) { get; set; } | Ruft die Anzahl der Strip-Bytes ab oder legt sie fest. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets) { get; set; } | Holt oder setzt die Streifen-Offsets. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype) { get; set; } | Holt oder setzt einen allgemeinen Hinweis auf die Art der Daten, die in dieser Unterdatei enthalten sind. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags) { get; set; } | Ruft die Tags ab oder legt sie fest. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter) { get; set; } | Ruft den Zieldrucker ab oder setzt ihn. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding) { get; set; } | Ruft den Schwellenwert ab oder legt ihn fest. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts) { get; set; } | Ruft die Tile-Byte-Anzahl ab oder legt sie fest. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength) { get; set; } | Ruft ot-Sets-Kachellänge ab. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets) { get; set; } | Ruft die Kachel-Offsets ab oder legt sie fest. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth) { get; set; } | Ruft die Kachelbreite ab. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages) { get; } | Ruft die Gesamtzahl der Seiten ab. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount) { get; } | Ruft die gültige Tag-Anzahl ab. Dies ist nicht die Gesamtzahl der Tags, sondern die Anzahl der Tags, die beibehalten werden können. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ruft die Optionen für die Vektorrasterung ab oder legt sie fest. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata) { get; set; } | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor) { get; set; } | Ruft den Bildautor ab oder legt ihn fest, der von Windows Explorer verwendet wird. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment) { get; set; } | Holt oder setzt Kommentar zum Bild, das von Windows Explorer verwendet wird. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords) { get; set; } | Ruft das Motivbild ab oder legt es fest, das von Windows Explorer verwendet wird. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition) { get; set; } | Ruft die x-Position ab oder legt sie fest. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject) { get; set; } | Ruft Informationen über Bilder ab oder legt sie fest, die von Windows Explorer verwendet werden. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle) { get; set; } | Ruft Informationen über Bilder ab oder legt sie fest, die von Windows Explorer verwendet werden. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution) { get; set; } | Ruft die x-Auflösung ab oder legt sie fest. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients) { get; set; } | Ruft die YCbCrCoefficients ab oder setzt sie. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling) { get; set; } | Liest oder setzt die Subsampling-Faktoren für YCbCr photometric. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition) { get; set; } | Ruft die y-Position ab oder legt sie fest. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution) { get; set; } | Ruft die y-Auflösung ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag)(TiffDataType) | Fügt ein neues Tag hinzu. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags)(TiffDataType[]) | Fügt die Tags hinzu. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | Klont diese Instanz. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype)(TiffTags) | Ruft die Instanz des Tags nach Typ ab. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent)(TiffTags) | Legt fest, ob Tag in den Optionen vorhanden ist oder nicht. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag)(TiffTags) | Entfernt das Tag. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate)() | Prüft, ob Optionen eine gültige Kombination von Tags haben |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount)(TiffDataType[]) | Ruft die Anzahl gültiger Tags ab. |

### Beispiele

Dieses Beispiel demonstriert die Verwendung verschiedener Klassen aus dem SaveOptions-Namespace für Exportzwecke. Ein Bild vom Typ Psd wird in eine Instanz von Image geladen und dann in mehrere Formate exportiert.

```csharp
[C#]

//Ein vorhandenes Bild in eine Instanz der Image-Klasse laden
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Export in das BMP-Dateiformat unter Verwendung der Standardoptionen
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    // Mit den Standardoptionen in das JPEG-Dateiformat exportieren
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    // Mit den Standardoptionen in das Dateiformat JPEG 2000 exportieren
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    // Mit den Standardoptionen in das PNG-Dateiformat exportieren
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    // Mit den Standardoptionen in das TIFF-Dateiformat exportieren
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

Dieses Beispiel verwendet GraphicsPath und die Graphics-Klasse, um Figuren auf einer Bildoberfläche zu erstellen und zu manipulieren. Beispiel erstellt ein neues Bild und zeichnet Pfade mit Hilfe der GraphicsPath-Klasse. Am Ende wird die DrawPath-Methode aufgerufen, die von der Graphics-Klasse bereitgestellt wird, um die Pfade auf der Oberfläche zu rendern. Schließlich wird das Bild in das Tiff-Dateiformat exportiert.

```csharp
[C#]

//Eine Instanz von Image erstellen 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Eine Instanz der Graphics-Klasse erstellen und initialisieren
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Grafikoberfläche löschen
    graphics.Clear(Color.Wheat);

    //Eine Instanz der GraphicsPath-Klasse erstellen
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Eine Instanz der Figure-Klasse erstellen
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Formen zum Figurobjekt hinzufügen
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Figure-Objekt zu GraphicsPath hinzufügen
    graphicspath.AddFigure(figure);

    // Pfad mit Stiftobjekt der Farbe Schwarz zeichnen
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Eine Instanz von TiffOptions erstellen und ihre verschiedenen Eigenschaften festlegen
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // Alle Änderungen speichern.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Siehe auch

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase)
* namensraum [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
