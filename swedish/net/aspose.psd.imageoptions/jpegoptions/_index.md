---
title: "Klass JpegOptions."
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.ImageOptions.JpegOptions klass. Alternativ för skapande av jpeg-filformatet."
type: docs
weight: 5330
url: /sv/net/aspose.psd.imageoptions/jpegoptions/
---
{{< psd/tize >}}
## JpegOptions class

jpeg-filformatets skapandealternativ.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | Initierar en ny instans av klassen `JpegOptions`. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | Initierar en ny instans av klassen `JpegOptions`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | Hämtar eller anger bitar per kanal för förlustfri jpeg-bild. Nu stödjer vi 2 till 8 bitar per kanal. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Hämtar eller anger en hint för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | Destinations-CMYK-färgprofilen för CMYK jpeg-bilder. Använd för att spara bilder. Måste vara i par med RGBColorProfile för korrekt färgkonvertering. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | Hämtar eller anger färgtypen för jpeg-bild. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | Hämtar eller anger jpeg-filens kommentar. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | Hämtar eller anger komprimeringstypen. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/jpegoptions/defaultmemoryallocationlimit/) { get; set; } | Hämtar eller anger standardgränsen för minnesallokering. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Hämtar eller anger standardersättningsfonten (font som kommer att användas för att rita text vid export till raster, om befintlig lagerfont i PSD‑filen inte finns i systemet). För att få rätt namn på standardfonten kan följande kodsnutt användas: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | Hämta eller ange exif-datakontainer. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Hämtar eller anger ett värde som indikerar om [full frame]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | Hämtar eller anger de horisontella subsamplingarna för varje komponent. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | Hämtar eller anger jfif. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | Hämtar eller anger JPEG-LS-differensgränsen för nästan förlustfri kodning (NEAR-parameter från JPEG-LS-specifikationen). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | Hämtar eller anger JPEG-LS-interleavläge. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | Hämtar eller anger JPEG-LS-förinställda parametrar. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Alternativen för flersidiga |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Hämtar eller anger färgpaletten. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | Hämtar eller anger ett värde som indikerar om röd, grön och blå komponenter ska blandas med en bakgrundsfärg, om alfakanal finns. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Hämtar eller anger händelsehanteraren för framsteg. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | Hämtar eller anger bildkvalitet. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | Hämtar eller anger RD-optimeringsinställningarna. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Hämtar eller anger upplösningsinställningarna. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | Hämtar eller anger upplösningsenheten. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | Destinations‑RGB‑färgprofilen för CMYK‑jpeg‑bilder. Använd för att spara bilder. Måste vara i par med CMYKColorProfile för korrekt färgkonvertering. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | Hämtar eller anger provavrundningsläget för att anpassa ett 8‑bitars värde till ett n‑bitars värde. BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | Den skalade kvaliteten. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Hämtar eller anger källan för att skapa bilden i. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Hämtar eller anger vektor‑rasteriseringsalternativen. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | Hämtar eller anger de vertikala delprovningarna för varje komponent. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | Hämtar eller anger XMP-metadatabehållaren. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klonar detta objekt. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |

## Exempel

Detta exempel visar hur man använder Aspose.PSD för .Net API för att konvertera bilder till Jpeg‑format. För att uppnå detta mål laddar exemplet en befintlig bild och konverterar den sedan till Jpeg‑filformat.

```csharp
[C#]

//Skapar en instans av bildklassen och initierar den med en befintlig fil via filsökväg.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Skapa en instans av klassen PsdOptions.
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //Ställ in kvaliteten till 50 % för att minska storleken på den resulterande bilden.
    jpegOptions.Quality = 50;

    //Ange exif‑kommentarerna.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //Spara bilden till en diskplats med de medföljande JpegOptions‑inställningarna.
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

Detta exempel visar hur man använder System.IO.Stream för att skapa en ny bildfil.

```csharp
[C#]

//Skapar en instans av PsdOptions och anger dess olika egenskaper.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Skapa en instans av System.IO.Stream.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Definiera käll‑egenskapen för instansen av PsdOptions.
//Andra boolska parametern bestämmer om Streamen avyttras när den lämnar scopet.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Skapar en instans av Image och anropar Create‑metoden med PsdOptions som parameter för att initiera Image‑objektet.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //utför någon bildbehandling
}
```

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


