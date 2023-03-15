---
title: Class Jpeg2000Options
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.ImageOptions.Jpeg2000Options klas. De Jpeg2000bestandsindelingsopties.
type: docs
weight: 4830
url: /nl/net/aspose.psd.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

De Jpeg2000-bestandsindelingsopties.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Jpeg2000Options](jpeg2000options/#constructor)() | Initialiseert een nieuw exemplaar van het`Jpeg2000Options` klasse. |
| [Jpeg2000Options](jpeg2000options/#constructor_1)(Jpeg2000Options) | Initialiseert een nieuw exemplaar van het`Jpeg2000Options` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Haalt de hint voor de buffergrootte op of stelt deze in, de maximale toegestane grootte voor alle interne buffers. |
| [Codec](../../aspose.psd.imageoptions/jpeg2000options/codec/) { get; set; } | Haalt de JPEG2000-codec op of stelt deze in |
| [Comments](../../aspose.psd.imageoptions/jpeg2000options/comments/) { get; set; } | Haalt of stelt de Jpeg-commentaarmarkeringen in. |
| [CompressionRatios](../../aspose.psd.imageoptions/jpeg2000options/compressionratios/) { get; set; } | Haalt of stelt de reeks compressieverhoudingen in. Verschillende compressieverhoudingen voor opeenvolgende lagen. De opgegeven snelheid voor elk kwaliteitsniveau is de gewenste compressiefactor. Dalende verhoudingen vereist. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Haalt het standaardvervangende lettertype op of stelt het in (lettertype dat zal worden gebruikt om tekst te tekenen bij het exporteren naar raster, als het bestaande laaglettertype in het PSD-bestand niet in het systeem wordt gepresenteerd). Om de juiste naam van het standaardlettertype te gebruiken, kan het volgende codefragment worden gebruikt : System.Drawing.Text.InstalledFontCollection col = nieuw System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = nieuwe PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Haalt of stelt een waarde in die aangeeft of [full frame]. |
| [Irreversible](../../aspose.psd.imageoptions/jpeg2000options/irreversible/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of de onomkeerbare DWT 9-7 (true) of lossless DWT 5-3-compressie (standaard) wordt gebruikt. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | De opties voor meerdere pagina's |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Haalt of stelt het kleurenpalet in. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Haalt de voortgangsgebeurtenishandler op of stelt deze in. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Haalt of stelt de resolutie-instellingen in. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Haalt of stelt de bron in om een afbeelding in te maken. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Haalt of stelt de vectorrasteropties in. |
| override [XmpData](../../aspose.psd.imageoptions/jpeg2000options/xmpdata/) { get; set; } | Haalt de XMP-metagegevenscontainer op of stelt deze in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Kloont deze instantie. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwijdert de huidige instantie. |

### Voorbeelden

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


