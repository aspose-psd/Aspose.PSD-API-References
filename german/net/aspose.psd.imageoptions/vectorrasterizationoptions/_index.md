---
title: Class VectorRasterizationOptions
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.ImageOptions.VectorRasterizationOptions klas. Die Vektorrasteroptionen.
type: docs
weight: 4980
url: /de/net/aspose.psd.imageoptions/vectorrasterizationoptions/
---
## VectorRasterizationOptions class

Die Vektorrasteroptionen.

```csharp
public abstract class VectorRasterizationOptions : ImageOptionsBase
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/backgroundcolor/) { get; set; } | Ruft eine Hintergrundfarbe ab oder legt sie fest. |
| [BorderX](../../aspose.psd.imageoptions/vectorrasterizationoptions/borderx/) { get; set; } | Holt oder setzt den Rand X. |
| [BorderY](../../aspose.psd.imageoptions/vectorrasterizationoptions/bordery/) { get; set; } | Holt oder setzt den Rand Y. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [CenterDrawing](../../aspose.psd.imageoptions/vectorrasterizationoptions/centerdrawing/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Zeichnen zentriert ist. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Ruft die Standard-Ersatzschriftart ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Exportieren in Raster verwendet wird, wenn die vorhandene Layer-Schriftart in der PSD-Datei nicht im System angezeigt wird). Um den richtigen Namen der Standardschriftart zu übernehmen, kann das nächste Code-Snippet verwendet werden : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] Familie = col.Families; string defaultFontName = Familie[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [DrawColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/drawcolor/) { get; set; } | Ruft eine Vordergrundfarbe ab oder legt sie fest. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Vollbild]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Die mehrseitigen Optionen |
| [PageHeight](../../aspose.psd.imageoptions/vectorrasterizationoptions/pageheight/) { get; set; } | Ruft die Seitenhöhe ab oder legt sie fest. |
| [PageSize](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagesize/) { get; set; } | Ruft die Seitengröße ab oder legt sie fest. |
| [PageWidth](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagewidth/) { get; set; } | Ruft die Seitenbreite ab oder legt sie fest. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Ruft den Fortschrittsereignishandler ab oder legt ihn fest. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [SmoothingMode](../../aspose.psd.imageoptions/vectorrasterizationoptions/smoothingmode/) { get; set; } | Ruft den Glättungsmodus ab oder legt ihn fest. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Ruft die Quelle zum Erstellen des Bildes ab oder legt sie fest. |
| [TextRenderingHint](../../aspose.psd.imageoptions/vectorrasterizationoptions/textrenderinghint/) { get; set; } | Ruft den Textwiedergabehinweis ab oder legt ihn fest. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Ruft die Optionen für die Vektorrasterung ab oder legt sie fest. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klont diese Instanz. |
| [CopyTo](../../aspose.psd.imageoptions/vectorrasterizationoptions/copyto/)(VectorRasterizationOptions) | Kopien nach. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwirft die aktuelle Instanz. |

### Siehe auch

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namensraum [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* Montage [Aspose.PSD](../../)


