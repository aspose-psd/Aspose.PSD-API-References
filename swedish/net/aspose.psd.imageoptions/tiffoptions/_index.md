---
title: Class TiffOptions
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.ImageOptions.TiffOptions klass. Alternativen för tifffilformat. Observera att bredd och höjdtaggar kommer att skrivas över vid bildskapande av parametrar för bredd och höjd så det finns ingen anledning att ange dem direkt. Observera att många alternativ returnerar ett standardvärde men det betyder inte att det här alternativet är uttryckligen inställt som ett taggvärde. För att verifiera att taggen finns använd Tagsegenskapen eller motsvarande IsTagPresentmetod.
type: docs
weight: 4940
url: /sv/net/aspose.psd.imageoptions/tiffoptions/
---
## TiffOptions class

Alternativen för tiff-filformat. Observera att bredd- och höjdtaggar kommer att skrivas över vid bildskapande av parametrar för bredd och höjd, så det finns ingen anledning att ange dem direkt. Observera att många alternativ returnerar ett standardvärde men det betyder inte att det här alternativet är uttryckligen inställt som ett taggvärde. För att verifiera att taggen finns, använd Tags-egenskapen eller motsvarande IsTagPresent-metod.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | Initierar en ny instans av`TiffOptions` class. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | Initierar en ny instans av`TiffOptions` klass. Som standard används little endian-konventionen. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | Initierar en ny instans av`TiffOptions` class. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Initierar en ny instans av`TiffOptions` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | Hämtar eller ställer in alfalagringsalternativet. Andra alternativ änUnspecified används när det finns fler än 3[`SamplesPerPixel`](./samplesperpixel/) definierad. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | Hämtar eller ställer in artisten. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | Hämtar bitarna per pixel. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | Hämtar eller ställer in bitarna per sampel. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | Hämtar eller ställer in ett värde som anger tiff-byteordningen. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | Hämtar eller ställer in färgkartan. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | Hämtar eller ställer in komprimerad bildkvalitet. Används med Jpeg-komprimeringen. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | Hämtar eller ställer in komprimeringen. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | Får eller anger upphovsrätten. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | Hämtar eller ställer in datum och tid. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Hämtar eller ställer in standardersättningsteckensnittet (teckensnitt som kommer att användas för att rita text vid export till raster, om befintligt lagerteckensnitt i PSD-filen inte presenteras i systemet). För att ta korrekt namn på standardteckensnitt kan nästa kodavsnitt användas : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familjer = col.Families; sträng defaultFontName = familjer[0]. PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | Hämtar eller ställer in namnet på dokumentet. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | Hämtar eller ställer in pekaren till EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | Hämtar eller ställer in fax t4-alternativen. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | Hämtar eller ställer in TIFF-filstandarden. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | Hämtar eller ställer in bytebitarnas fyllningsordning. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Hämtar eller ställer in ett värde som anger om [helbild]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | Hämtar eller ställer in halvtonstipsen. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Hämtar eller ställer in Icc-profilströmmen. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | Hämtar eller ställer in bildbeskrivningen. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | Hämtar eller ställer in bildlängden. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | Hämtar eller ställer in bildbredden. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | Hämtar eller ställer in bläcknamnen. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Får ett värde som indikerar om de extra samplen finns. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | Får ett värde som indikerar om bilden är sida vid sida. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | Får ett värde som indikerar om`TiffOptions` har konfigurerats korrekt. Använd metoden Validera för att hitta orsaken till felet. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Hämtar eller ställer in det maximala sampelvärdet. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Hämtar eller ställer in det minsta sampelvärdet. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Alternativen för flera sidor |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | Hämtar eller ställer in orienteringen. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | Hämtar eller ställer in sidnamnet. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | Hämtar eller ställer in sidnummertaggen. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | Hämtar eller ställer in färgpaletten. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | Hämtar eller ställer in fotometrisk. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Hämtar eller ställer in den plana konfigurationen. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | Hämtar eller ställer in prediktorn för LZW-komprimering. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Hämtar eller ställer in ett värde som anger om komponenter måste förmultipliceras. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Hämtar eller ställer in förloppshändelsehanteraren. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Hämtar eller ställer in upplösningsinställningarna. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Hämtar eller ställer in upplösningsenheten. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Hämtar eller ställer in raderna per remsa. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | Hämtar eller ställer in exempelformatet. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | Hämtar samplen per pixel. För att ändra detta egenskapsvärde använd[`BitsPerSample`](./bitspersample/) egenskapsinställare. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Hämtar eller ställer in skannertillverkaren. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | Hämtar eller ställer in skannermodellen. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Hämtar eller ställer in det maximala sampelvärdet. Värdet har en fälttyp som bäst matchar exempeldata (Byte, Short eller Long type). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Hämtar eller ställer in det minsta sampelvärdet. Värdet har en fälttyp som bäst matchar exempeldata (Byte, Short eller Long type). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | Hämtar eller ställer in mjukvarutypen. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Hämtar eller ställer in källan för att skapa bild i. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Hämtar eller ställer in remsantalet byte. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Får eller ställer in remsoffset. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | Hämtar eller ställer in en allmän indikation på vilken typ av data som finns i denna underfil. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | Hämtar eller ställer in taggarna. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | Hämtar eller ställer in målskrivaren. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | Hämtar eller ställer in tröskelvärdet. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Hämtar eller ställer in antalet brickbyte. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | Får ot sets kakellängd. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Hämtar eller ställer in brickförskjutningarna. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | Får ot set kakelbredd. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | Får det totala antalet sidor. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | Får det giltiga taggantalet. Detta är inte det totala antalet taggar utan antalet taggar som kan bevaras. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Hämtar eller ställer in vektorrasteriseringsalternativen. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | Hämtar eller ställer in XMP-metadatabehållaren. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Hämtar eller ställer in bildförfattare, som används av Utforskaren i Windows. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Hämtar eller ställer in en kommentar till bilden, som används av Windows Explorer. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Hämtar eller ställer in ämnesbild, som används av Utforskaren i Windows. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | Hämtar eller ställer in x-positionen. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Hämtar eller ställer in information om bild, som används av Windows Explorer. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Hämtar eller ställer in information om bild, som används av Windows Explorer. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | Hämtar eller ställer in x-upplösningen. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | Hämtar eller ställer in YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | Hämtar eller ställer in delsamplingsfaktorerna för YCbCr fotometrisk. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | Hämtar eller ställer in y-positionen. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | Hämtar eller ställer in y-upplösningen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | Lägger till en ny tagg. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Lägger till taggarna. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klonar den här instansen. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Hämtar instansen av taggen efter typ. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Avgör om tagg finns i alternativen eller inte. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | Tar bort taggen. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | Validerar om alternativen har en giltig kombination av taggar |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Får antalet giltiga taggar. |

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

det här exemplet används GraphicsPath och Graphics-klassen för att skapa och manipulera figurer på en bildyta. Exempel skapar en ny bild och ritar banor med hjälp av klassen GraphicsPath. I slutet anropas DrawPath-metoden som exponeras av Graphics-klassen för att rendera banorna på ytan. Slutligen exporteras bilden till Tiff-filformat.

```csharp
[C#]

//Skapa en instans av bild 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapa och initiera en instans av klassen Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensa grafikytan
    graphics.Clear(Color.Wheat);

    //Skapa en instans av klassen GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Skapa en instans av figurklassen
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Lägg till former till figurobjekt
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Lägg till figurobjekt till GraphicsPath
    graphicspath.AddFigure(figure);

    //Rita bana med pennobjekt av färg svart
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Skapa en instans av TiffOptions och ställ in dess olika egenskaper
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // spara alla ändringar.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Se även

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namnutrymme [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* hopsättning [Aspose.PSD](../../)


