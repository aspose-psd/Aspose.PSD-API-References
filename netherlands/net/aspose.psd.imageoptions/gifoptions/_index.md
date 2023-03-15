---
title: Class GifOptions
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.ImageOptions.GifOptions klas. De opties voor het maken van gifbestandsindelingen.
type: docs
weight: 4810
url: /nl/net/aspose.psd.imageoptions/gifoptions/
---
## GifOptions class

De opties voor het maken van gif-bestandsindelingen.

```csharp
public class GifOptions : ImageOptionsBase
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | Initialiseert een nieuw exemplaar van het`GifOptions` klasse. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | Initialiseert een nieuw exemplaar van het`GifOptions` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | Haalt de GIF-achtergrondkleurindex op of stelt deze in. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Haalt de hint voor de buffergrootte op of stelt deze in, de maximale toegestane grootte voor alle interne buffers. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution/) { get; set; } | Krijgt of stelt de GIF-kleurresolutie in. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Haalt het standaardvervangende lettertype op of stelt het in (lettertype dat zal worden gebruikt om tekst te tekenen bij het exporteren naar raster, als het bestaande laaglettertype in het PSD-bestand niet in het systeem wordt gepresenteerd). Om de juiste naam van het standaardlettertype te gebruiken, kan het volgende codefragment worden gebruikt : System.Drawing.Text.InstalledFontCollection col = nieuw System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = nieuwe PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | Haalt of stelt een waarde in die aangeeft of paletcorrectie wordt toegepast. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Haalt of stelt een waarde in die aangeeft of [full frame]. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer/) { get; set; } | Krijgt of stelt een waarde in die aangeeft of GIF een trailer heeft. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced/) { get; set; } | Waar als het beeld moet worden geïnterlinieerd. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of paletitems zijn gesorteerd. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff/) { get; set; } | Haalt of stelt het maximaal toegestane pixelverschil in. Indien groter dan nul, wordt compressie met verlies gebruikt. De aanbevolen waarde voor optimale compressie met verlies is 80. 30 is zeer lichte compressie, 200 is zware. Het werkt het beste wanneer er slechts weinig verlies wordt geïntroduceerd en vanwege de beperking van het compressie-algoritme zeer hoge verliesniveaus geven niet zoveel winst. Het bereik van toegestane waarden is [0, 1000]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | De opties voor meerdere pagina's |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Haalt of stelt het kleurenpalet in. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | Haalt de beeldverhouding van de GIF-pixel op of stelt deze in. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Haalt de voortgangsgebeurtenishandler op of stelt deze in. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Haalt of stelt de resolutie-instellingen in. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Haalt of stelt de bron in om een afbeelding in te maken. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Haalt of stelt de vectorrasteropties in. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata/) { get; set; } | Haalt de XMP-metagegevenscontainer op of stelt deze in. |

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


