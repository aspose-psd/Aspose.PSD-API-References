---
title: Class TiffOptions
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.ImageOptions.TiffOptions klas. De opties voor het TIFFbestandsformaat. Houd er rekening mee dat breedte en hoogtetags bij het maken van afbeeldingen worden overschreven door breedte en hoogteparameters dus het is niet nodig om ze rechtstreeks op te geven. Merk op dat veel opties een standaardwaarde retourneren maar dat betekent niet dat deze optie is expliciet ingesteld als tagwaarde. Om te controleren of de tag aanwezig is gebruikt u de eigenschap Tags of de overeenkomstige IsTagPresentmethode.
type: docs
weight: 4940
url: /nl/net/aspose.psd.imageoptions/tiffoptions/
---
## TiffOptions class

De opties voor het TIFF-bestandsformaat. Houd er rekening mee dat breedte- en hoogtetags bij het maken van afbeeldingen worden overschreven door breedte- en hoogteparameters, dus het is niet nodig om ze rechtstreeks op te geven. Merk op dat veel opties een standaardwaarde retourneren, maar dat betekent niet dat deze optie is expliciet ingesteld als tagwaarde. Om te controleren of de tag aanwezig is, gebruikt u de eigenschap Tags of de overeenkomstige IsTagPresent-methode.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | Initialiseert een nieuw exemplaar van het`TiffOptions` klasse. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | Initialiseert een nieuw exemplaar van het`TiffOptions` klas. Standaard wordt weinig endian-conventie gebruikt. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | Initialiseert een nieuw exemplaar van het`TiffOptions` klasse. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Initialiseert een nieuw exemplaar van het`TiffOptions` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | Haalt of stelt de alfa-opslagoptie in. Opties anders danUnspecified worden gebruikt als er meer dan 3 zijn[`SamplesPerPixel`](./samplesperpixel/) gedefinieerd. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | Haalt of stelt de artiest in. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | Haalt de bits per pixel op. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | Haalt of stelt de bits per sample in. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Haalt de hint voor de buffergrootte op of stelt deze in, de maximale toegestane grootte voor alle interne buffers. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | Haalt of stelt een waarde in die de tiff-bytevolgorde aangeeft. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | Haalt of stelt de kleurenkaart in. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | Hiermee krijgt of stelt u de gecomprimeerde beeldkwaliteit in. Gebruikt met de Jpeg-compressie. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | Haalt of stelt de compressie in. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | Verkrijgt of stelt het copyright in. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | Ontvangt of stelt de datum en tijd in. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Haalt het standaardvervangende lettertype op of stelt het in (lettertype dat zal worden gebruikt om tekst te tekenen bij het exporteren naar raster, als het bestaande laaglettertype in het PSD-bestand niet in het systeem wordt gepresenteerd). Om de juiste naam van het standaardlettertype te gebruiken, kan het volgende codefragment worden gebruikt : System.Drawing.Text.InstalledFontCollection col = nieuw System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = nieuwe PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | Haalt de naam van het document op of stelt deze in. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | Haalt de aanwijzer op of stelt deze in op EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | Haalt of stelt de fax t4-opties in. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | Haalt of stelt de TIFF-bestandsstandaard in. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | Haalt of stelt de vulvolgorde van bytebits in. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Haalt of stelt een waarde in die aangeeft of [full frame]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | Haalt de halftoonhints op of stelt deze in. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Haalt de Icc-profielstream op of stelt deze in. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | Haalt de afbeeldingsbeschrijving op of stelt deze in. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | Haalt of stelt de afbeeldingslengte in. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | Haalt of stelt de beeldbreedte in. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | Haalt of stelt de inktnamen in. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Krijgt een waarde die aangeeft of de extra samples aanwezig zijn. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | Krijgt een waarde die aangeeft of de afbeelding betegeld is. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | Krijgt een waarde die aangeeft of de`TiffOptions` correct zijn geconfigureerd. Gebruik de methode Valideren om de reden van de fout te vinden. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Haalt de maximale samplewaarde op of stelt deze in. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Haalt de minimale samplewaarde op of stelt deze in. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | De opties voor meerdere pagina's |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | Haalt of stelt de oriëntatie in. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | Haalt de paginanaam op of stelt deze in. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | Haalt of stelt de tag voor het paginanummer in. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | Haalt of stelt het kleurenpalet in. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | Haalt of stelt de fotometrie in. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Haalt of stelt de vlakke configuratie in. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | Haalt de voorspelling voor LZW-compressie op of stelt deze in. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Haalt of stelt een waarde in die aangeeft of componenten vooraf moeten worden vermenigvuldigd. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Haalt de voortgangsgebeurtenishandler op of stelt deze in. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Haalt of stelt de resolutie-instellingen in. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Haalt of stelt de resolutie-eenheid in. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Haalt of stelt de rijen per strip in. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | Haalt of stelt het voorbeeldformaat in. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | Haalt de monsters per pixel op. Gebruik de om deze eigenschapswaarde te wijzigen[`BitsPerSample`](./bitspersample/) eigenschappensetter. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Haalt of stelt de fabrikant van de scanner in. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | Haalt of stelt het scannermodel in. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Haalt of stelt de maximale samplewaarde in. De waarde heeft een veldtype dat het beste overeenkomt met de voorbeeldgegevens (byte, kort of lang type). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Haalt of stelt de minimale steekproefwaarde in. De waarde heeft een veldtype dat het beste overeenkomt met de voorbeeldgegevens (byte, kort of lang type). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | Haalt het softwaretype op of stelt het in. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Haalt of stelt de bron in om een afbeelding in te maken. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Haalt of stelt het aantal stripbytes in. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Haalt de stripoffsets op of stelt deze in. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | Krijgt of stelt een algemene indicatie in van het soort gegevens in dit subbestand. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | Haalt of stelt de tags in. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | Haalt of stelt de doelprinter in. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | Haalt of stelt de drempelwaarde in. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Haalt of stelt het aantal tegelbytes in. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | Haalt of stelt tegellengte in. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Haalt of stelt de tegeloffsets in. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | Haalt iet sets tegelbreedte op. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | Haalt het totale aantal pagina's op. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | Haalt het geldige aantal tags op. Dit is niet het totale aantal tags, maar het aantal tags dat behouden kan blijven. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Haalt of stelt de vectorrasteropties in. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | Haalt de XMP-metagegevenscontainer op of stelt deze in. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Haalt of stelt de auteur van de afbeelding in, die wordt gebruikt door Windows Verkenner. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Krijgt of plaatst commentaar op de afbeelding, die wordt gebruikt door Windows Verkenner. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Krijgt of stelt onderwerpafbeelding in, die wordt gebruikt door Windows Verkenner. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | Haalt of stelt de x-positie in. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Krijgt of stelt informatie in over de afbeelding, die wordt gebruikt door Windows Verkenner. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Krijgt of stelt informatie in over de afbeelding, die wordt gebruikt door Windows Verkenner. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | Haalt of stelt de x-resolutie in. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | Haalt de YCbCrCoëfficiënten op of stelt deze in. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | Hiermee worden de subsamplingfactoren voor YCbCr fotometrisch opgehaald of ingesteld. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | Haalt of stelt de y-positie in. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | Haalt of stelt de y-resolutie in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | Voegt een nieuwe tag toe. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Voegt de tags toe. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Kloont deze instantie. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwijdert de huidige instantie. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Haalt de instantie van de tag op type op. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Bepaalt of tag aanwezig is in de opties of niet. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | Verwijdert de tag. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | Valideert of opties een geldige combinatie van tags hebben |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Haalt het aantal geldige tags op. |

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

Deze voorbeelden maken gebruik van de klasse GraphicsPath en Graphics om figuren op een afbeeldingsoppervlak te maken en te manipuleren. Voorbeeld maakt een nieuwe afbeelding en tekent paden met behulp van de klasse GraphicsPath. Aan het einde wordt de DrawPath-methode die wordt weergegeven door de klasse Graphics aangeroepen om de paden op het oppervlak weer te geven. Ten slotte wordt de afbeelding geëxporteerd naar het Tiff-bestandsformaat.

```csharp
[C#]

//Maak een exemplaar van Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Maak en initialiseer een instantie van de klasse Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Grafisch oppervlak wissen
    graphics.Clear(Color.Wheat);

    //Maak een instantie van de klasse GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Maak een instantie van de klasse Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    // Vormen toevoegen aan figuurobject
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Voeg figuurobject toe aan GraphicsPath
    graphicspath.AddFigure(figure);

    // Teken een pad met een Pen-object in de kleur Zwart
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Maak een exemplaar van TiffOptions en stel de verschillende eigenschappen in
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // sla alle veranderingen op.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Zie ook

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* naamruimte [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* montage [Aspose.PSD](../../)


