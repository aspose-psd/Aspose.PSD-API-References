---
title: "Class Jpeg2000Options"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.ImageOptions.Jpeg2000Options class. Alternativen för Jpeg2000‑filformatet"
type: docs
weight: 5320
url: /sv/net/aspose.psd.imageoptions/jpeg2000options/
---
{{< psd/tize >}}
## Jpeg2000Options class

Jpeg2000-filformatalternativen.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Jpeg2000Options](jpeg2000options/#constructor)() | Initierar en ny instans av klassen `Jpeg2000Options`. |
| [Jpeg2000Options](jpeg2000options/#constructor_1)(Jpeg2000Options) | Initierar en ny instans av klassen `Jpeg2000Options`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Hämtar eller anger en hint för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar. |
| [Codec](../../aspose.psd.imageoptions/jpeg2000options/codec/) { get; set; } | Hämtar eller anger JPEG2000‑codec |
| [Comments](../../aspose.psd.imageoptions/jpeg2000options/comments/) { get; set; } | Hämtar eller anger Jpeg‑kommentarmarkörer. |
| [CompressionRatios](../../aspose.psd.imageoptions/jpeg2000options/compressionratios/) { get; set; } | Hämtar eller anger Array av komprimeringsförhållanden. Olika komprimeringsförhållanden för på varandra följande lager. Den hastighet som anges för varje kvalitetsnivå är den önskade komprimeringsfaktorn. Minskande förhållanden krävs. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Hämtar eller anger standardersättningsfonten (font som kommer att användas för att rita text vid export till raster, om befintlig lagerfont i PSD‑filen inte finns i systemet). För att få rätt namn på standardfonten kan följande kodsnutt användas: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Hämtar eller anger ett värde som indikerar om [full frame]. |
| [Irreversible](../../aspose.psd.imageoptions/jpeg2000options/irreversible/) { get; set; } | Hämtar eller anger ett värde som indikerar om den irreversibla DWT 9‑7 (true) ska användas eller om förlustfri DWT 5‑3‑kompression (standard) ska användas. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Alternativen för flersidiga |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Hämtar eller anger färgpaletten. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Hämtar eller anger händelsehanteraren för framsteg. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Hämtar eller anger upplösningsinställningarna. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Hämtar eller anger källan för att skapa bilden i. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Hämtar eller anger vektor‑rasteriseringsalternativen. |
| override [XmpData](../../aspose.psd.imageoptions/jpeg2000options/xmpdata/) { get; set; } | Hämtar eller anger XMP-metadatabehållaren. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klonar detta objekt. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |

## Exempel

Detta exempel visar användningen av olika klasser från SaveOptions-namnområdet för exportändamål. En bild av typen Psd laddas in i en instans av Image och exporteras sedan till flera format.

```csharp
[C#]

//Läs in en befintlig bild i en instans av Image-klassen
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
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


