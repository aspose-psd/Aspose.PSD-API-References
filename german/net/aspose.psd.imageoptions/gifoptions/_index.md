---
title: GifOptions
second_title: Aspose.PSD für .NET-API-Referenz
description: Die Optionen zum Erstellen des GIFDateiformats.
type: docs
weight: 4740
url: /de/net/aspose.psd.imageoptions/gifoptions/
---
## GifOptions class

Die Optionen zum Erstellen des GIF-Dateiformats.

```csharp
public class GifOptions : ImageOptionsBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [GifOptions](gifoptions#constructor)() | Initialisiert eine neue Instanz von[`GifOptions`](../gifoptions) Klasse. |
| [GifOptions](gifoptions#constructor_1)(GifOptions) | Initialisiert eine neue Instanz von[`GifOptions`](../gifoptions) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex) { get; set; } | Ruft den GIF-Hintergrundfarbindex ab oder legt ihn fest. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution) { get; set; } | Ruft die GIF-Farbauflösung ab oder legt sie fest. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Ruft die Standard-Ersatzschriftart ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Exportieren in Raster verwendet wird, wenn die vorhandene Layer-Schriftart in der PSD-Datei nicht im System angezeigt wird). Um den richtigen Namen der Standardschriftart zu übernehmen, kann das nächste Code-Snippet verwendet werden : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] Familie = col.Families; string defaultFontName = Familie[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Palettenkorrektur angewendet wird. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Vollbild]. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob GIF einen Trailer hat. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced) { get; set; } | Wahr, wenn das Bild interlaced sein soll. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob Paletteneinträge sortiert sind. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff) { get; set; } | Holt oder setzt den maximal erlaubten Pixelunterschied. Wenn größer als Null, wird verlustbehaftete Komprimierung verwendet. Der empfohlene Wert für eine optimale verlustbehaftete Komprimierung ist 80. 30 ist eine sehr leichte Komprimierung, 200 ist stark. Es funktioniert am besten, wenn nur wenig Verlust eingeführt wird, und aufgrund der Beschränkung des Komprimierungsalgorithmus sehr hohe Verlustniveaus ergeben nicht so viel Gewinn. Der zulässige Wertebereich ist [0, 1000]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Die mehrseitigen Optionen |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio) { get; set; } | Ruft das GIF-Pixel-Seitenverhältnis ab oder legt es fest. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Ruft den Fortschrittsereignishandler ab oder legt ihn fest. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings) { get; set; } | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Ruft die Quelle zum Erstellen des Bildes ab oder legt sie fest. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ruft die Optionen für die Vektorrasterung ab oder legt sie fest. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata) { get; set; } | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | Klont diese Instanz. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |

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

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase)
* namensraum [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
