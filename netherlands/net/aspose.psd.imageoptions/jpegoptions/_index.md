---
title: Class JpegOptions
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.ImageOptions.JpegOptions klas. Het jpegbestandsformaat creëert opties.
type: docs
weight: 4840
url: /nl/net/aspose.psd.imageoptions/jpegoptions/
---
## JpegOptions class

Het jpeg-bestandsformaat creëert opties.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | Initialiseert een nieuw exemplaar van het`JpegOptions` klasse. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | Initialiseert een nieuw exemplaar van het`JpegOptions` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | Haalt of stelt bits per kanaal in voor lossless jpeg-afbeeldingen. Nu ondersteunen we 2 tot 8 bits per kanaal. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Haalt de hint voor de buffergrootte op of stelt deze in, de maximale toegestane grootte voor alle interne buffers. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | Het bestemmings-CMYK-kleurprofiel voor CMYK jpeg-afbeeldingen. Gebruik voor het opslaan van afbeeldingen. Moet gekoppeld zijn aan RGBColorProfile voor correcte kleurconversie. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | Hiermee wordt het kleurtype voor jpeg-afbeelding opgehaald of ingesteld. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | Krijgt of stelt het jpeg-bestandcommentaar in. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | Haalt het compressietype op of stelt het in. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Haalt het standaardvervangende lettertype op of stelt het in (lettertype dat zal worden gebruikt om tekst te tekenen bij het exporteren naar raster, als het bestaande laaglettertype in het PSD-bestand niet in het systeem wordt gepresenteerd). Om de juiste naam van het standaardlettertype te gebruiken, kan het volgende codefragment worden gebruikt : System.Drawing.Text.InstalledFontCollection col = nieuw System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = nieuwe PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | Exif-gegevenscontainer ophalen of instellen |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Haalt of stelt een waarde in die aangeeft of [full frame]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | Haalt of stelt de horizontale subsamplings voor elke component in. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | Haalt of stelt de jfif. in |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | Haalt of stelt de JPEG-LS-verschilgrens in voor vrijwel verliesvrije codering (NEAR-parameter van de JPEG-LS-specificatie). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | Haalt de JPEG-LS interleave-modus op of stelt deze in. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | Haalt de vooraf ingestelde JPEG-LS-parameters op of stelt deze in. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | De opties voor meerdere pagina's |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Haalt of stelt het kleurenpalet in. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | Haalt of stelt een waarde in die aangeeft of rode, groene en blauwe componenten moeten worden gemengd met een achtergrondkleur, als alfakanaal aanwezig is. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Haalt de voortgangsgebeurtenishandler op of stelt deze in. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | Beeldkwaliteit ophalen of instellen. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | Haalt of stelt de RD-optimalisatie-instellingen in. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Haalt of stelt de resolutie-instellingen in. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | Haalt of stelt de resolutie-eenheid in. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | Het doel-RGB-kleurprofiel voor CMYK jpeg-afbeeldingen. Gebruik voor het opslaan van afbeeldingen. Moet gekoppeld zijn aan CMYKColorProfile voor correcte kleurconversie. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | Haalt de afrondingsmodus voor monsters op of stelt deze zo in dat een 8-bits waarde past bij een n-bits waarde.BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | De geschaalde kwaliteit. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Haalt of stelt de bron in om een afbeelding in te maken. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Haalt of stelt de vectorrasteropties in. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | Haalt of stelt de verticale subsamplings voor elke component in. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | Haalt de XMP-metagegevenscontainer op of stelt deze in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Kloont deze instantie. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwijdert de huidige instantie. |

### Voorbeelden

Dit voorbeeld demonstreert het gebruik van Aspose.PSD voor .Net API om afbeeldingen naar JPEG-indeling te converteren. Om dit doel te bereiken, laadt dit voorbeeld een bestaande afbeelding en converteert deze vervolgens naar het JPEG-bestandsformaat.

```csharp
[C#]

//Maakt een instantie van de afbeeldingsklasse en initialiseert deze met een bestaand bestand via Bestandspad
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // Maak een instantie van de klasse PsdOptions
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    // Stel de kwaliteit in op 50% om de uitvoerafbeelding kleiner te maken.
    jpegOptions.Quality = 50;

    // Stel de exif-opmerkingen in.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //Sla de afbeelding op schijflocatie op met de meegeleverde JpegOptions-instellingen
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

Dit voorbeeld demonstreert het gebruik van System.IO.Stream om een nieuw afbeeldingsbestand te maken

```csharp
[C#]

//Maakt een instantie van PsdOptions en stelt de verschillende eigenschappen ervan in
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Maak een exemplaar van System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Definieer de broneigenschap voor de instantie van PsdOptions
// Tweede booleaanse parameter bepaalt of de stream wordt verwijderd zodra deze buiten bereik is
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Maakt een instantie van Image en roept de Create-methode aan met PsdOptions als parameter om het Image-object te initialiseren   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // doe wat beeldverwerking
}
```

Dit voorbeeld demonstreert het gebruik van verschillende klassen uit SaveOptions Namespace voor exportdoeleinden. Een afbeelding van het type Psd wordt geladen in een exemplaar van Afbeelding en vervolgens geëxporteerd naar verschillende indelingen.

```csharp
[C#]

// Laad een bestaande afbeelding in een instantie van de klasse Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Exporteren naar BMP-bestandsindeling met de standaardopties
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Exporteren naar JPEG-bestandsindeling met de standaardopties
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Exporteren naar JPEG 2000-bestandsindeling met de standaardopties
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Exporteren naar PNG-bestandsindeling met de standaardopties
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Exporteren naar TIFF-bestandsindeling met de standaardopties
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### Zie ook

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* naamruimte [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* montage [Aspose.PSD](../../)


