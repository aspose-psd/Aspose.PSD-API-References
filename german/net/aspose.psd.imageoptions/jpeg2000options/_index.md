---
title: Class Jpeg2000Options
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.ImageOptions.Jpeg2000Options klas. Die Jpeg2000Dateiformatoptionen.
type: docs
weight: 4830
url: /de/net/aspose.psd.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

Die Jpeg2000-Dateiformatoptionen.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Jpeg2000Options](jpeg2000options/#constructor)() | Initialisiert eine neue Instanz von`Jpeg2000Options` Klasse. |
| [Jpeg2000Options](jpeg2000options/#constructor_1)(Jpeg2000Options) | Initialisiert eine neue Instanz von`Jpeg2000Options` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [Codec](../../aspose.psd.imageoptions/jpeg2000options/codec/) { get; set; } | Holt oder setzt den JPEG2000-Codec |
| [Comments](../../aspose.psd.imageoptions/jpeg2000options/comments/) { get; set; } | Ruft die Jpeg-Kommentarmarkierungen ab oder setzt sie. |
| [CompressionRatios](../../aspose.psd.imageoptions/jpeg2000options/compressionratios/) { get; set; } | Ruft das Komprimierungsverhältnis des Arrays ab oder legt es fest. Unterschiedliche Komprimierungsverhältnisse für aufeinanderfolgende Schichten. Die für jede Qualitätsstufe angegebene Rate ist der gewünschte Komprimierungsfaktor. Verringern der Verhältnisse erforderlich. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Ruft die Standard-Ersatzschriftart ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Exportieren in Raster verwendet wird, wenn die vorhandene Layer-Schriftart in der PSD-Datei nicht im System angezeigt wird). Um den richtigen Namen der Standardschriftart zu übernehmen, kann das nächste Code-Snippet verwendet werden : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] Familie = col.Families; string defaultFontName = Familie[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Vollbild]. |
| [Irreversible](../../aspose.psd.imageoptions/jpeg2000options/irreversible/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die irreversible DWT 9-7-Komprimierung (true) oder die verlustfreie DWT 5-3-Komprimierung (Standard) verwendet wird. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Die mehrseitigen Optionen |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Ruft den Fortschrittsereignishandler ab oder legt ihn fest. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Ruft die Quelle zum Erstellen des Bildes ab oder legt sie fest. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Ruft die Optionen für die Vektorrasterung ab oder legt sie fest. |
| override [XmpData](../../aspose.psd.imageoptions/jpeg2000options/xmpdata/) { get; set; } | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klont diese Instanz. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwirft die aktuelle Instanz. |

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

### Siehe auch

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namensraum [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* Montage [Aspose.PSD](../../)


