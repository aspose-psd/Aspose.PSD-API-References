---
title: Class JpegOptions
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.ImageOptions.JpegOptions klas. Optionen zum Erstellen des JPEGDateiformats.
type: docs
weight: 4840
url: /de/net/aspose.psd.imageoptions/jpegoptions/
---
## JpegOptions class

Optionen zum Erstellen des JPEG-Dateiformats.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | Initialisiert eine neue Instanz von`JpegOptions` Klasse. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | Initialisiert eine neue Instanz von`JpegOptions` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | Holt oder setzt Bits pro Kanal für ein verlustfreies JPEG-Bild. Jetzt unterstützen wir 2 bis 8 Bit pro Kanal. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | Das Ziel-CMYK-Farbprofil für CMYK-JPEG-Bilder. Zum Speichern von Bildern verwenden. Muss für eine korrekte Farbkonvertierung mit RGBColorProfile gekoppelt sein. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | Ruft den Farbtyp für das JPEG-Bild ab oder legt ihn fest. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | Ruft den JPEG-Dateikommentar ab oder legt ihn fest. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | Ruft den Komprimierungstyp ab oder legt ihn fest. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Ruft die Standard-Ersatzschriftart ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Exportieren in Raster verwendet wird, wenn die vorhandene Layer-Schriftart in der PSD-Datei nicht im System angezeigt wird). Um den richtigen Namen der Standardschriftart zu übernehmen, kann das nächste Code-Snippet verwendet werden : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] Familie = col.Families; string defaultFontName = Familie[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | Exif-Datencontainer abrufen oder setzen |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Vollbild]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | Ruft die horizontalen Unterabtastungen für jede Komponente ab oder legt sie fest. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | Holt oder setzt jfif. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | Ruft die JPEG-LS-Differenzgrenze für nahezu verlustfreie Codierung ab oder legt sie fest (NEAR-Parameter aus der JPEG-LS-Spezifikation). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | Ruft den JPEG-LS-Interleave-Modus ab oder legt ihn fest. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | Ruft die voreingestellten JPEG-LS-Parameter ab oder legt sie fest. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Die mehrseitigen Optionen |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob rote, grüne und blaue Komponenten mit einer Hintergrundfarbe gemischt werden sollen, wenn ein Alphakanal vorhanden ist. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Ruft den Fortschrittsereignishandler ab oder legt ihn fest. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | Ruft die Bildqualität ab oder legt sie fest. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | Ruft die RD-Optimierereinstellungen ab oder legt sie fest. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | Ruft die Auflösungseinheit ab oder legt sie fest. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | Das Ziel-RGB-Farbprofil für CMYK-JPEG-Bilder. Zum Speichern von Bildern verwenden. Muss für eine korrekte Farbkonvertierung mit CMYKColorProfile gepaart sein. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | Ruft den Abtastrundungsmodus ab oder legt ihn fest, um einen 8-Bit-Wert an einen n-Bit-Wert anzupassen.BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | Die skalierte Qualität. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Ruft die Quelle zum Erstellen des Bildes ab oder legt sie fest. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Ruft die Optionen für die Vektorrasterung ab oder legt sie fest. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | Ruft die vertikalen Unterabtastungen für jede Komponente ab oder legt sie fest. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klont diese Instanz. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwirft die aktuelle Instanz. |

### Beispiele

Dieses Beispiel zeigt die Verwendung von Aspose.PSD für die .Net-API zum Konvertieren von Bildern in das JPEG-Format. Um dieses Ziel zu erreichen, lädt dieses Beispiel ein vorhandenes Bild und konvertiert es dann in das JPEG-Dateiformat.

```csharp
[C#]

//Erzeugt eine Instanz der Bildklasse und initialisiert sie mit einer vorhandenen Datei über den Dateipfad
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Eine Instanz der PsdOptions-Klasse erstellen
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    // Stellen Sie die Qualität auf 50 % ein, um die Größe des Ausgabebilds zu verringern.
    jpegOptions.Quality = 50;

    // Setze die Exif-Kommentare.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //Speichern Sie das Bild mit den angegebenen JpegOptions-Einstellungen am Speicherort der Festplatte
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

Dieses Beispiel zeigt die Verwendung von System.IO.Stream zum Erstellen einer neuen Image-Datei

```csharp
[C#]

//Erzeugt eine Instanz von PsdOptions und legt ihre verschiedenen Eigenschaften fest
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Eine Instanz von System.IO.Stream erstellen
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Definieren Sie die Quelleigenschaft für die Instanz von PsdOptions
//Der zweite boolesche Parameter bestimmt, ob der Stream verworfen wird, sobald er den Gültigkeitsbereich verlässt
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Erzeugt eine Instanz von Image und ruft die Create-Methode mit PsdOptions als Parameter auf, um das Image-Objekt zu initialisieren   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // Bildverarbeitung durchführen
}
```

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


