---
title: Class Jpeg2000Options
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.ImageOptions.Jpeg2000Options klass. Filformatsalternativen Jpeg2000.
type: docs
weight: 4830
url: /sv/net/aspose.psd.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

Filformatsalternativen Jpeg2000.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Jpeg2000Options](jpeg2000options/#constructor)() | Initierar en ny instans av`Jpeg2000Options` class. |
| [Jpeg2000Options](jpeg2000options/#constructor_1)(Jpeg2000Options) | Initierar en ny instans av`Jpeg2000Options` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [Codec](../../aspose.psd.imageoptions/jpeg2000options/codec/) { get; set; } | Hämtar eller ställer in JPEG2000 codec |
| [Comments](../../aspose.psd.imageoptions/jpeg2000options/comments/) { get; set; } | Hämtar eller ställer in Jpeg-kommentarmarkörerna. |
| [CompressionRatios](../../aspose.psd.imageoptions/jpeg2000options/compressionratios/) { get; set; } | Hämtar eller ställer in matrisen av kompressionsförhållande. Olika kompressionsförhållanden för på varandra följande lager. Hastigheten som anges för varje kvalitetsnivå är den önskade kompressionsfaktorn. Minskande förhållanden krävs. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Hämtar eller ställer in standardersättningsteckensnittet (teckensnitt som kommer att användas för att rita text vid export till raster, om befintligt lagerteckensnitt i PSD-filen inte presenteras i systemet). För att ta korrekt namn på standardteckensnitt kan nästa kodavsnitt användas : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familjer = col.Families; sträng defaultFontName = familjer[0]. PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Hämtar eller ställer in ett värde som anger om [helbild]. |
| [Irreversible](../../aspose.psd.imageoptions/jpeg2000options/irreversible/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om du använder den irreversibla DWT 9-7 (true) eller om du använder förlustfri DWT 5-3-komprimering (standard). |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Alternativen för flera sidor |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Hämtar eller ställer in färgpaletten. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Hämtar eller ställer in förloppshändelsehanteraren. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Hämtar eller ställer in upplösningsinställningarna. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Hämtar eller ställer in källan för att skapa bild i. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Hämtar eller ställer in vektorrasteriseringsalternativen. |
| override [XmpData](../../aspose.psd.imageoptions/jpeg2000options/xmpdata/) { get; set; } | Hämtar eller ställer in XMP-metadatabehållaren. |

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


