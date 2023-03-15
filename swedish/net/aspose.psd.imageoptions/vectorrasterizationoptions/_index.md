---
title: Class VectorRasterizationOptions
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.ImageOptions.VectorRasterizationOptions klass. Vektorrastreringsalternativen.
type: docs
weight: 4980
url: /sv/net/aspose.psd.imageoptions/vectorrasterizationoptions/
---
## VectorRasterizationOptions class

Vektorrastreringsalternativen.

```csharp
public abstract class VectorRasterizationOptions : ImageOptionsBase
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BackgroundColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/backgroundcolor/) { get; set; } | Hämtar eller ställer in en bakgrundsfärg. |
| [BorderX](../../aspose.psd.imageoptions/vectorrasterizationoptions/borderx/) { get; set; } | Hämtar eller ställer in gränsen X. |
| [BorderY](../../aspose.psd.imageoptions/vectorrasterizationoptions/bordery/) { get; set; } | Hämtar eller ställer in gränsen Y. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [CenterDrawing](../../aspose.psd.imageoptions/vectorrasterizationoptions/centerdrawing/) { get; set; } | Hämtar eller ställer in ett värde som anger om mittritning. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Hämtar eller ställer in standardersättningsteckensnittet (teckensnitt som kommer att användas för att rita text vid export till raster, om befintligt lagerteckensnitt i PSD-filen inte presenteras i systemet). För att ta korrekt namn på standardteckensnitt kan nästa kodavsnitt användas : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familjer = col.Families; sträng defaultFontName = familjer[0]. PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [DrawColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/drawcolor/) { get; set; } | Får eller ställer in en förgrundsfärg. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Hämtar eller ställer in ett värde som anger om [helbild]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Alternativen för flera sidor |
| [PageHeight](../../aspose.psd.imageoptions/vectorrasterizationoptions/pageheight/) { get; set; } | Hämtar eller ställer in sidhöjden. |
| [PageSize](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagesize/) { get; set; } | Hämtar eller ställer in sidstorleken. |
| [PageWidth](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagewidth/) { get; set; } | Hämtar eller ställer in sidbredden. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Hämtar eller ställer in färgpaletten. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Hämtar eller ställer in förloppshändelsehanteraren. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Hämtar eller ställer in upplösningsinställningarna. |
| [SmoothingMode](../../aspose.psd.imageoptions/vectorrasterizationoptions/smoothingmode/) { get; set; } | Hämtar eller ställer in utjämningsläget. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Hämtar eller ställer in källan för att skapa bild i. |
| [TextRenderingHint](../../aspose.psd.imageoptions/vectorrasterizationoptions/textrenderinghint/) { get; set; } | Hämtar eller ställer in textåtergivningstipset. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Hämtar eller ställer in vektorrasteriseringsalternativen. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Hämtar eller ställer in XMP-metadatabehållaren. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klonar den här instansen. |
| [CopyTo](../../aspose.psd.imageoptions/vectorrasterizationoptions/copyto/)(VectorRasterizationOptions) | Kopierar till. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |

### Se även

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namnutrymme [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* hopsättning [Aspose.PSD](../../)


