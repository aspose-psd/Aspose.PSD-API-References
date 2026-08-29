---
title: "Klasse BmpOptions"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.ImageOptions.BmpOptions Klasse. Die Erstellungsoptionen für das BMP‑Dateiformat."
type: docs
weight: 5280
url: /de/net/aspose.psd.imageoptions/bmpoptions/
---
{{< psd/tize >}}
## BmpOptions class

Die BMP-Dateiformat-Erstellungsoptionen.

```csharp
public class BmpOptions : ImageOptionsBase
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [BmpOptions](bmpoptions/#constructor)() | Initialisiert eine neue Instanz der `BmpOptions` Klasse. |
| [BmpOptions](bmpoptions/#constructor_1)(BmpOptions) | Initialisiert eine neue Instanz der `BmpOptions` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BitsPerPixel](../../aspose.psd.imageoptions/bmpoptions/bitsperpixel/) { get; set; } | Liest oder setzt die Bild‑Bits‑pro‑Pixel‑Anzahl. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [Compression](../../aspose.psd.imageoptions/bmpoptions/compression/) { get; set; } | Liest oder setzt die Kompression. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Liest oder setzt die standardmäßige Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen-Schriftart in der PSD-Datei im System nicht vorhanden ist). Um den korrekten Namen der Standardschriftart zu erhalten, kann das folgende Code‑Snippet verwendet werden: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Die Mehrseitenoptionen |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Liest oder setzt die Farbpalette. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Liest oder setzt den Fortschritts-Event-Handler. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Liest oder setzt die Auflösungseinstellungen. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Liest oder setzt den XMP‑Metadaten‑Container. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klonen Sie diese Instanz. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |

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

### Siehe auch

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


