---
title: Class JpegOptions
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.ImageOptions.JpegOptions klass. Skapa alternativ för jpegfilformat.
type: docs
weight: 4840
url: /sv/net/aspose.psd.imageoptions/jpegoptions/
---
## JpegOptions class

Skapa alternativ för jpeg-filformat.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | Initierar en ny instans av`JpegOptions` class. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | Initierar en ny instans av`JpegOptions` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | Hämtar eller ställer in bitar per kanal för förlustfri jpeg-bild. Nu stöder vi från 2 till 8 bitar per kanal. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | Mål-CMYK-färgprofilen för CMYK-jpeg-bilder. Använd för att spara bilder. Måste vara i par med RGBColorProfile för korrekt färgkonvertering. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | Hämtar eller ställer in färgtypen för jpeg-bild. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | Hämtar eller ställer in jpeg-filkommentaren. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | Hämtar eller ställer in komprimeringstypen. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Hämtar eller ställer in standardersättningsteckensnittet (teckensnitt som kommer att användas för att rita text vid export till raster, om befintligt lagerteckensnitt i PSD-filen inte presenteras i systemet). För att ta korrekt namn på standardteckensnitt kan nästa kodavsnitt användas : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familjer = col.Families; sträng defaultFontName = familjer[0]. PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | Hämta eller ställ in exif data container |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Hämtar eller ställer in ett värde som anger om [helbild]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | Hämtar eller ställer in de horisontella delsamplingarna för varje komponent. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | Hämtar eller ställer in jfif. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | Hämtar eller ställer in JPEG-LS-skillnaden för nästan förlustfri kodning (NEAR-parameter från JPEG-LS-specifikationen). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | Hämtar eller ställer in JPEG-LS-interfolieringsläget. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | Hämtar eller ställer in JPEG-LS förinställda parametrar. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Alternativen för flera sidor |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Hämtar eller ställer in färgpaletten. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | Hämtar eller ställer in ett värde som anger om röda, gröna och blå komponenter ska blandas med en bakgrundsfärg, om alfakanal finns. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Hämtar eller ställer in förloppshändelsehanteraren. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | Hämtar eller ställer in bildkvalitet. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | Hämtar eller ställer in RD-optimeringsinställningarna. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Hämtar eller ställer in upplösningsinställningarna. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | Hämtar eller ställer in upplösningsenheten. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | Mål RGB-färgprofilen för CMYK jpeg-bilder. Använd för att spara bilder. Måste vara i par med CMYKColorProfile för korrekt färgkonvertering. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | Hämtar eller ställer in sampelavrundningsläget så att det passar ett 8-bitars värde till ett n-bitars värde.BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | Den skalade kvaliteten. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Hämtar eller ställer in källan för att skapa bild i. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Hämtar eller ställer in vektorrasteriseringsalternativen. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | Hämtar eller ställer in de vertikala delsamplingarna för varje komponent. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | Hämtar eller ställer in XMP-metadatabehållaren. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klonar den här instansen. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |

### Exempel

Det här exemplet visar användningen av Aspose.PSD för .Net API för att konvertera bilder till Jpeg-format. För att uppnå detta mål laddar detta exempel en befintlig bild och konverterar den sedan till Jpeg-filformat.

```csharp
[C#]

//Skapar en instans av bildklass och initierar den med en befintlig fil via filsökväg
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Skapa en instans av klassen PsdOptions
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //Ställ in kvaliteten på 50 % för att minska storleken på utdatabilden.
    jpegOptions.Quality = 50;

    //Ställ in exif-kommentarerna.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //Spara bilden på diskplats med medföljande JpegOptions-inställningar
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

Det här exemplet visar användningen av System.IO.Stream för att skapa en ny bildfil

```csharp
[C#]

//Skapar en instans av PsdOptions och ställer in dess olika egenskaper
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Skapa en instans av System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Definiera källegenskapen för instansen av PsdOptions
//Den andra booleska parametern bestämmer om strömmen kasseras när den kommit utanför räckvidden
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Skapar en instans av Image and call Create-metoden med PsdOptions som parameter för att initiera Image-objektet   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //gör lite bildbehandling
}
```

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


