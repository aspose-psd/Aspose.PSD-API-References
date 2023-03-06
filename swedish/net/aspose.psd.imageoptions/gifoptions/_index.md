---
title: Class GifOptions
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.ImageOptions.GifOptions klass. Alternativen för att skapa giffilformat.
type: docs
weight: 4810
url: /sv/net/aspose.psd.imageoptions/gifoptions/
---
## GifOptions class

Alternativen för att skapa gif-filformat.

```csharp
public class GifOptions : ImageOptionsBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | Initierar en ny instans av`GifOptions` class. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | Initierar en ny instans av`GifOptions` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | Hämtar eller ställer in GIF-bakgrundsfärgindex. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution/) { get; set; } | Hämtar eller ställer in GIF-färgupplösningen. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Hämtar eller ställer in standardersättningsteckensnittet (teckensnitt som kommer att användas för att rita text vid export till raster, om befintligt lagerteckensnitt i PSD-filen inte presenteras i systemet). För att ta korrekt namn på standardteckensnitt kan nästa kodavsnitt användas : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familjer = col.Families; sträng defaultFontName = familjer[0]. PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | Hämtar eller ställer in ett värde som anger om palettkorrigering tillämpas. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Hämtar eller ställer in ett värde som anger om [helbild]. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer/) { get; set; } | Hämtar eller ställer in ett värde som anger om GIF har trailer. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced/) { get; set; } | Sant om bilden ska vara sammanflätad. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted/) { get; set; } | Hämtar eller ställer in ett värde som anger om palettposter är sorterade. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff/) { get; set; } | Hämtar eller ställer in den maximala tillåtna pixelskillnaden. Om den är större än noll kommer komprimering med förlust att användas. Rekommenderat värde för optimal komprimering med förlust är 80. 30 är mycket lätt komprimering, 200 är tung. Det fungerar bäst när endast liten förlust introduceras, och på grund av begränsning av komprimeringsalgoritmen mycket höga förlustnivåer ger inte lika mycket förstärkning. Intervallet för tillåtna värden är [0, 1000]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Alternativen för flera sidor |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Hämtar eller ställer in färgpaletten. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | Hämtar eller ställer in GIF-pixelns bildförhållande. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Hämtar eller ställer in förloppshändelsehanteraren. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Hämtar eller ställer in upplösningsinställningarna. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Hämtar eller ställer in källan för att skapa bild i. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Hämtar eller ställer in vektorrasteriseringsalternativen. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata/) { get; set; } | Hämtar eller ställer in XMP-metadatabehållaren. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klonar den här instansen. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |

### Exempel

Det här exemplet visar användningen av olika klasser från SaveOptions Namespace för exportändamål. En bild av typen Psd laddas in i en instans av Image och exporteras sedan ut till flera format.

```csharp
[C#]

//Ladda in en befintlig bild i en instans av klassen Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Exportera till BMP-filformat med standardalternativen
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Exportera till JPEG-filformat med standardalternativen
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Exportera till JPEG 2000-filformat med standardalternativen
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Exportera till PNG-filformat med standardalternativen
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Exportera till TIFF-filformat med standardalternativen
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### Se även

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namnutrymme [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* hopsättning [Aspose.PSD](../../)


