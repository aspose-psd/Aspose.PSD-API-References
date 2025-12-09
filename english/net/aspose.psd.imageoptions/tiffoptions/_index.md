---
title: Class TiffOptions
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.ImageOptions.TiffOptions class. The tiff file format options. Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly. Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method
type: docs
weight: 5390
url: /net/aspose.psd.imageoptions/tiffoptions/
---
{{< psd/tize >}}
## TiffOptions class

The tiff file format options. Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly. Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | Initializes a new instance of the `TiffOptions` class. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | Initializes a new instance of the `TiffOptions` class. By default little endian convention is used. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | Initializes a new instance of the `TiffOptions` class. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Initializes a new instance of the `TiffOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | Gets or sets the alpha storage option. Options other than Unspecified are used when there are more than 3 [`SamplesPerPixel`](./samplesperpixel/) defined. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | Gets or sets the artist. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | Gets the bits per pixel. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | Gets or sets the bits per sample. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | Gets or sets a value indicating the tiff byte order. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | Gets or sets the color map. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | Gets or sets compressed image quality. Used with the Jpeg compression. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | Gets or sets the compression. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | Gets or sets the copyright. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | Gets or sets the date and time. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/tiffoptions/defaultmemoryallocationlimit/) { get; set; } | Gets or sets the default memory allocation limit. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system). To take proper name of default font can be used next code snippet: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | Gets or sets the name of the document. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | Gets or sets the pointer to EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | Gets or sets the fax t4 options. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | Gets or sets the TIFF file standard. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | Gets or sets the byte bits fill order. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Gets or sets a value indicating whether [full frame]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | Gets or sets the halftone hints. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Gets or sets the Icc profile stream. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | Gets or sets the image description. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | Gets or sets the image length. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | Gets or sets the image width. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | Gets or sets the ink names. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Gets a value indicating whether the extra samples is present. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | Gets a value indicating whether image is tiled. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | Gets a value indicating whether the `TiffOptions` have been properly configured. Use Validate method as to find the failure reason. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Gets or sets the max sample value. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Gets or sets the min sample value. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | The multipage options |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | Gets or sets the orientation. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | Gets or sets the page name. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | Gets or sets the page number tag. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | Gets or sets the color palette. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | Gets or sets the photometric. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Gets or sets the planar configuration. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | Gets or sets the predictor for LZW compression. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Gets or sets a value indicating whether components must be premultiplied. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Gets or sets the progress event handler. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Gets or sets the resolution settings. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Gets or sets the resolution unit. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Gets or sets the rows per strip. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | Gets or sets the sample format. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | Gets the samples per pixel. To change this property value use the [`BitsPerSample`](./bitspersample/) property setter. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Gets or sets the scanner manufacturer. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | Gets or sets the scanner model. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Gets or sets the max sample value. The value has a field type which best matches the sample data (Byte, Short or Long type). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Gets or sets the min sample value. The value has a field type which best matches the sample data (Byte, Short or Long type). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | Gets or sets the software type. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Gets or sets the source to create image in. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Gets or sets the strip byte counts. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Gets or sets the strip offsets. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | Gets or sets a general indication of the kind of data contained in this subfile. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | Gets or sets the tags. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | Gets or sets the target printer. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | Gets or sets the threshholding. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Gets or sets the tile byte counts. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | Gets ot sets tile length. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Gets or sets the tile offsets. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | Gets ot sets tile width. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | Gets the total pages. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | Gets the valid tag count. This is not the total tags count but the number of tags which may be preserved. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Gets or sets the vector rasterization options. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | Gets or sets the XMP metadata container. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Gets or sets image author, which used by Windows Explorer. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Gets or sets comment on image, which used by Windows Explorer. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Gets or sets subject image, which used by Windows Explorer. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | Gets or sets the x position. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Gets or sets information about image, which used by Windows Explorer. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Gets or sets information about image, which used by Windows Explorer. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | Gets or sets the x resolution. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | Gets or sets the YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | Gets or sets the subsampling factors for YCbCr photometric. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | Gets or sets the y position. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | Gets or sets the y resolution. |

## Methods

| Name | Description |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | Adds a new tag. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Adds the tags. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clones this instance. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Disposes the current instance. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Gets the instance of the tag by type. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Determines whether tag is present in the options or not. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | Removes the tag. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | Validates if options have valid combination of tags |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Gets the valid tags count. |

## Examples

This example demonstrates the use of different classes from SaveOptions Namespace for export purposes. An image of type Psd is loaded into an instance of Image and then exported out to several formats.

```csharp
[C#]

//Load an existing image in an instance of Image class
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Export to BMP file format using the default options
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Export to JPEG file format using the default options
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Export to JPEG 2000 file format using the default options
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Export to PNG file format using the default options
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Export to TIFF file format using the default options
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface. Example creates a new Image and draws paths with the help of GraphicsPath class. At the end DrawPath method exposed by Graphics class is called to render the paths on surface. Finally image is exported to Tiff file format.

```csharp
[C#]

//Create an instance of Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Create and initialize an instance of Graphics class
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Clear Graphics surface
    graphics.Clear(Color.Wheat);

    //Create an instance of GraphicsPath class
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Create an instance of Figure class
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Add Shapes to Figure object
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Add Figure object to GraphicsPath
    graphicspath.AddFigure(figure);

    //Draw path with Pen object of color Black
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Create an instance of TiffOptions and set its various properties
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // save all changes.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### See Also

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


