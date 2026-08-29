---
title: "Klass TiffOptions"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.ImageOptions.TiffOptions klass. Tiff‑filformatets alternativ. Observera att bredd‑ och höjdtaggar kommer att skrivas över vid bildskapande av bredd‑ och höjdpå parametrar, så det behövs inte att ange dem direkt. Observera att många alternativ returnerar ett standardvärde men det betyder inte att detta alternativ är satt explicit som ett taggvärde. För att verifiera att taggen finns, använd egenskapen Tags eller motsvarande metod IsTagPresent"
type: docs
weight: 5430
url: /sv/net/aspose.psd.imageoptions/tiffoptions/
---
{{< psd/tize >}}
## TiffOptions class

tiff-filformatalternativen. Observera att bredd- och höjdmärken kommer att skrivas över vid bildskapande av bredd- och höjdpARAMetrar så det inte behövs att ange dem direkt. Observera att många alternativ returnerar ett standardvärde men det betyder inte att detta alternativ är satt explicit som ett märkesvärde. För att verifiera att märket finns, använd Tags property eller motsvarande IsTagPresent method.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | Initierar en ny instans av klassen `TiffOptions`. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | Initierar en ny instans av klassen `TiffOptions`. Som standard används little‑endian‑konventionen. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | Initierar en ny instans av klassen `TiffOptions`. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Initierar en ny instans av klassen `TiffOptions`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | Hämtar eller anger alfa‑lagringsalternativet. Alternativ annat än Unspecified används när det finns mer än 3 [`SamplesPerPixel`](./samplesperpixel/) definierade. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | Hämtar eller anger konstnären. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | Hämtar bitarna per pixel. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | Hämtar eller anger bitar per sample. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Hämtar eller anger en hint för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | Hämtar eller anger ett värde som indikerar tiff‑byteordning. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | Hämtar eller anger färgkartan. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | Hämtar eller anger komprimerad bildkvalitet. Används med Jpeg-komprimering. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | Hämtar eller anger komprimeringen. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | Hämtar eller anger upphovsrätt. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | Hämtar eller anger datum och tid. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/tiffoptions/defaultmemoryallocationlimit/) { get; set; } | Hämtar eller anger standardgränsen för minnesallokering. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Hämtar eller anger standardersättningsfonten (font som kommer att användas för att rita text vid export till raster, om befintlig lagerfont i PSD‑filen inte finns i systemet). För att få rätt namn på standardfonten kan följande kodsnutt användas: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | Hämtar eller anger dokumentets namn. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | Hämtar eller anger pekaren till EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | Hämtar eller anger fax t4-alternativ. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | Hämtar eller anger TIFF-filstandard. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | Hämtar eller anger bytebits fyllningsordning. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Hämtar eller anger ett värde som indikerar om [full frame]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | Hämtar eller anger halvtontips. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Hämtar eller anger Icc-profilsström. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | Hämtar eller anger bildbeskrivning. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | Hämtar eller anger bildlängd. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | Hämtar eller anger bildbredd. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | Hämtar eller anger bläcknamn. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Hämtar ett värde som indikerar om extra prover finns. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | Hämtar ett värde som indikerar om bilden är kaklad. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | Hämtar ett värde som indikerar om `TiffOptions` har konfigurerats korrekt. Använd Validate‑metoden för att hitta felorsaken. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Hämtar eller anger maximalt provvärde. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Hämtar eller anger minimalt provvärde. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Alternativen för flersidiga |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | Hämtar eller anger orientering. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | Hämtar eller anger sidnamn. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | Hämtar eller anger sidnummer‑tagg. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | Hämtar eller anger färgpaletten. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | Hämtar eller anger photometric. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Hämtar eller anger planar konfiguration. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | Hämtar eller anger förutsägaren för LZW-komprimering. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Hämtar eller anger ett värde som indikerar om komponenter måste förmultipliceras. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Hämtar eller anger händelsehanteraren för framsteg. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Hämtar eller anger upplösningsinställningarna. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Hämtar eller anger upplösningsenheten. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Hämtar eller anger rader per remsa. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | Hämtar eller anger provformatet. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | Hämtar prover per bildpunkt. För att ändra detta egenskapsvärde, använd egenskaps‑settern för [`BitsPerSample`](./bitspersample/). |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Hämtar eller anger skannertillverkaren. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | Hämtar eller anger skannermodellen. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Hämtar eller anger det maximala provvärdet. Värdet har en fälttyp som bäst matchar provdata (Byte-, Short- eller Long-typ). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Hämtar eller anger det minsta provvärdet. Värdet har en fälttyp som bäst matchar provdata (Byte-, Short- eller Long-typ). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | Hämtar eller anger programvarutypen. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Hämtar eller anger källan för att skapa bilden i. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Hämtar eller anger antalet byte per remsa. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Hämtar eller anger remsaförskjutningarna. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | Hämtar eller anger en allmän indikation på vilken typ av data som finns i denna underfil. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | Hämtar eller anger taggarna. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | Hämtar eller anger målskrivaren. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | Hämtar eller anger tröskelvärdet. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Hämtar eller anger antalet byte per ruta. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | Hämtar ot anger rutlängden. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Hämtar eller anger rutförskjutningarna. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | Hämtar ot anger rutbredden. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | Hämtar det totala antalet sidor. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | Hämtar det giltiga antalet taggar. Detta är inte det totala antalet taggar utan antalet taggar som kan bevaras. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Hämtar eller anger vektor‑rasteriseringsalternativen. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | Hämtar eller anger XMP-metadatabehållaren. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Hämtar eller anger bildens författare, som används av Windows Explorer. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Hämtar eller anger kommentar på bilden, som används av Windows Explorer. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Hämtar eller anger bildens ämne, som används av Windows Explorer. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | Hämtar eller anger x‑positionen. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Hämtar eller anger information om bilden som används av Windows Explorer. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Hämtar eller anger information om bilden som används av Windows Explorer. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | Hämtar eller anger x-upplösningen. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | Hämtar eller anger YCbCr-koefficienterna. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | Hämtar eller anger subsamplingsfaktorerna för YCbCr-fotometrisk. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | Hämtar eller anger y-positionen. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | Hämtar eller anger y-upplösningen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | Lägger till en ny tagg. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Lägger till taggarna. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klonar detta objekt. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Hämtar instansen av taggen efter typ. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Bestämmer om taggen finns i alternativen eller inte. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | Tar bort taggen. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | Validerar om alternativen har en giltig kombination av taggar |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Hämtar antalet giltiga taggar. |

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

Detta exempel använder GraphicsPath- och Graphics-klassen för att skapa och manipulera figurer på en bildyta. Exemplet skapar en ny bild och ritar banor med hjälp av GraphicsPath-klassen. I slutet anropas DrawPath‑metoden som exponeras av Graphics-klassen för att rendera banorna på ytan. Slutligen exporteras bilden till Tiff‑filformat.

```csharp
[C#]

//Skapa en instans av Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapa och initiera en instans av Graphics-klassen
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensa Graphics-ytan
    graphics.Clear(Color.Wheat);

    //Skapa en instans av GraphicsPath-klassen
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Skapa en instans av Figure-klassen
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Lägg till former till Figure-objektet
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Lägg till Figure-objektet till GraphicsPath
    graphicspath.AddFigure(figure);

    //Rita bana med Pen-objektet i färgen svart
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Skapa en instans av TiffOptions och ange dess olika egenskaper
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // spara alla ändringar.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Se även

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


