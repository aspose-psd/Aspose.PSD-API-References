---
title: "Klasse JpegOptions"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.ImageOptions.JpegOptions Klasse. Die Erstellungsoptionen für das JPEG-Dateiformat"
type: docs
weight: 5330
url: /de/net/aspose.psd.imageoptions/jpegoptions/
---
{{< psd/tize >}}
## JpegOptions class

Die JPEG-Datei-Format-Erstellungsoptionen.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | Initialisiert eine neue Instanz der `JpegOptions`-Klasse. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | Initialisiert eine neue Instanz der `JpegOptions`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | Liest oder setzt Bits pro Kanal für verlustfreie JPEG-Bilder. Jetzt unterstützen wir 2 bis 8 Bits pro Kanal. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | Das Ziel‑CMYK‑Farbprofil für CMYK-JPEG-Bilder. Verwenden zum Speichern von Bildern. Muss zusammen mit RGBColorProfile für eine korrekte Farbumwandlung verwendet werden. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | Liest oder setzt den Farbtyp für JPEG-Bilder. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | Liest oder setzt den JPEG-Dateikommentar. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | Liest oder setzt den Kompressionstyp. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/jpegoptions/defaultmemoryallocationlimit/) { get; set; } | Liest oder setzt das Standard‑Limit für Speicherzuweisungen. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Liest oder setzt die standardmäßige Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen-Schriftart in der PSD-Datei im System nicht vorhanden ist). Um den korrekten Namen der Standardschriftart zu erhalten, kann das folgende Code‑Snippet verwendet werden: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | Lese oder setze den EXIF-Datencontainer |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [full frame]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | Liest oder setzt die horizontalen Subsamplings für jede Komponente. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | Liest oder setzt das jfif. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | Liest oder setzt die JPEG-LS-Differenzgrenze für nahezu verlustlose Kodierung (NEAR-Parameter aus der JPEG-LS-Spezifikation). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | Liest oder setzt den JPEG-LS-Interleave-Modus. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | Liest oder setzt die JPEG-LS-Voreinstellungsparameter. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Die Mehrseitenoptionen |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Liest oder setzt die Farbpalette. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob Rot-, Grün- und Blau-Komponenten mit einer Hintergrundfarbe gemischt werden sollen, wenn ein Alpha-Kanal vorhanden ist. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Liest oder setzt den Fortschritts-Event-Handler. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | Liest oder setzt die Bildqualität. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | Liest oder setzt die RD-Optimizer-Einstellungen. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Liest oder setzt die Auflösungseinstellungen. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | Liest oder setzt die Auflösungseinheit. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | Das Ziel-RGB-Farbprofil für CMYK-JPEG-Bilder. Wird zum Speichern von Bildern verwendet. Muss zusammen mit CMYKColorProfile für eine korrekte Farbumwandlung verwendet werden. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | Liest oder setzt den Sample-Rundungsmodus, um einen 8‑Bit‑Wert an einen n‑Bit‑Wert anzupassen. BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | Die skalierte Qualität. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | Liest oder setzt die vertikalen Subsamplings für jede Komponente. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | Liest oder setzt den XMP‑Metadaten‑Container. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klonen Sie diese Instanz. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |

## Beispiele

Dieses Beispiel demonstriert die Verwendung der Aspose.PSD für .Net API, um Bilder in das Jpeg-Format zu konvertieren. Um dieses Ziel zu erreichen, lädt dieses Beispiel ein vorhandenes Bild und konvertiert es anschließend in das Jpeg-Dateiformat.

```csharp
[C#]

//Erstellt eine Instanz der Image-Klasse und initialisiert sie mit einer vorhandenen Datei über den Dateipfad.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Erstelle eine Instanz der PsdOptions-Klasse.
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //Setze die Qualität auf 50 %, um die Größe des Ausgabebildes zu verringern.
    jpegOptions.Quality = 50;

    //Setze die EXIF-Kommentare.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //Speichere das Bild am Speicherort mit den bereitgestellten JpegOptions-Einstellungen.
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

Dieses Beispiel demonstriert die Verwendung von System.IO.Stream, um eine neue Bilddatei zu erstellen.

```csharp
[C#]

//Erstellt eine Instanz von PsdOptions und setzt deren verschiedene Eigenschaften.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Erstelle eine Instanz von System.IO.Stream.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Definiere die Quell‑Eigenschaft für die Instanz von PsdOptions.
//Der zweite boolesche Parameter bestimmt, ob der Stream freigegeben wird, sobald er den Gültigkeitsbereich verlässt.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Erstellt eine Instanz von Image und ruft die Create‑Methode mit PsdOptions als Parameter auf, um das Image‑Objekt zu initialisieren.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Führe einige Bildverarbeitungen durch
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

### Siehe auch

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


