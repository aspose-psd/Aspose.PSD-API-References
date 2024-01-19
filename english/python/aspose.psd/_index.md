---
title: aspose.psd
type: docs
weight: 10
url: /python-net/aspose.psd/
---


The module is the core for nested modules and the most basic objects used for Aspose.PSD processing.

## **Classes**
| **Class** | **Description** |
| :- | :- |
| [Blend](/psd/python-net/aspose.psd/blend/) | Defines a blend pattern. This class cannot be inherited. |
| [Brush](/psd/python-net/aspose.psd/brush/) | The base brush class. |
| [BuildVersionInfo](/psd/python-net/aspose.psd/buildversioninfo/) | Contains the current build version information. |
| [Cache](/psd/python-net/aspose.psd/cache/) | Contains cache settings. |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) | The CMYK color of pixel. |
| [CmykColorHelper](/psd/python-net/aspose.psd/cmykcolorhelper/) | Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct. |
| [Color](/psd/python-net/aspose.psd/color/) | The color of the pixel. |
| [ColorBlend](/psd/python-net/aspose.psd/colorblend/) | Defines arrays of colors and positions used for interpolating color blending in a multicolor gradient. This class cannot be inherited. |
| [ColorMap](/psd/python-net/aspose.psd/colormap/) | Defines a map for converting colors. Several methods of the [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) class adjust image colors by using a color-remap table, which is an array of [ColorMap](/psd/python-net/aspose.psd/colormap/) structures. Not inheritable. |
| [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) | Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited. |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) | Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable. |
| [ColorPaletteHelper](/psd/python-net/aspose.psd/colorpalettehelper/) | Helper class for color palettes manipulation. |
| [ColorTranslator](/psd/python-net/aspose.psd/colortranslator/) | Translates colors to and from GDI+ Color structures. This class cannot be inherited. |
| [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) | Encapsulates a custom user-defined line cap. |
| [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/) | The data stream container. |
| [DisposableObject](/psd/python-net/aspose.psd/disposableobject/) | Represents disposable object. |
| [Figure](/psd/python-net/aspose.psd/figure/) | The figure. A container for shapes. |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer/) | Helper for file stream processing. |
| [Font](/psd/python-net/aspose.psd/font/) | Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited. |
| [FontSettings](/psd/python-net/aspose.psd/fontsettings/) | General PSD vector formats renderer font settings. |
| [Graphics](/psd/python-net/aspose.psd/graphics/) | Represents the graphics according to the graphics engine used in the current assembly. |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) | Represents a series of connected lines and curves. This class cannot be inherited. |
| [IAdvancedBufferProcessor](/psd/python-net/aspose.psd/iadvancedbufferprocessor/) | The advanced buffer processor. |
| [IBufferProcessor](/psd/python-net/aspose.psd/ibufferprocessor/) | The buffer processor. |
| [IColorConverter](/psd/python-net/aspose.psd/icolorconverter/) | The color converter. |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette/) | The color palette interface. |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator/) | The image creator. |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor/) | The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues. |
| [IImageDescriptor](/psd/python-net/aspose.psd/iimagedescriptor/) | The image descriptor. Contains base properties and methods for all other image descriptor types. |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter/) | The image exporter. Can export data from internal Aspose.PSD format to a specified data format. |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor/) | Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues. |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader/) | The image loader. |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor/) | The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues. |
| [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter/) | The color converter for indexed image formats. |
| [IKeyedObject](/psd/python-net/aspose.psd/ikeyedobject/) | Represents interface for objects with keys. |
| [IObjectWithBounds](/psd/python-net/aspose.psd/iobjectwithbounds/) | Represents an object with bounds. |
| [IOrderedShape](/psd/python-net/aspose.psd/iorderedshape/) | Represents an ordered shape. An ordered shape is a continuous set of points having a start point and end point.<br/>            The continuous set of points connected using a specific rule. |
| [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader/) | Conforms to the 32-bit ARGB pixels loaded partially. |
| [IPartialArgb64PixelLoader](/psd/python-net/aspose.psd/ipartialargb64pixelloader/) | The 64-bit ARGB pixels loader. |
| [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader/) | Conforms to the pixels loaded partially. |
| [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader/) | The partial data loader. |
| [IPsdColorPalette](/psd/python-net/aspose.psd/ipsdcolorpalette/) | The pasd color palette |
| [IRasterImageArgb32PixelLoader](/psd/python-net/aspose.psd/irasterimageargb32pixelloader/) | The raster image 32-bit ARGB pixel loader. |
| [IRasterImagePixelLoader](/psd/python-net/aspose.psd/irasterimagepixelloader/) | The raster image pixel loader. |
| [IRasterImageRawDataLoader](/psd/python-net/aspose.psd/irasterimagerawdataloader/) | The raster image raw data loader. |
| [Image](/psd/python-net/aspose.psd/image/) | The image is the base class for all type of images. |
| [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) | An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object and pass the path of that [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object (along with the path of an [Image](/psd/python-net/aspose.psd/image/)) to the DrawImage method. |
| [ImageCreatorsRegistry](/psd/python-net/aspose.psd/imagecreatorsregistry/) | Represents the image creators registry. |
| [ImageExportersRegistry](/psd/python-net/aspose.psd/imageexportersregistry/) | Represents the image exporters registry. |
| [ImageLoadersRegistry](/psd/python-net/aspose.psd/imageloadersregistry/) | Represents the image loaders registry. |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase/) | The image base options. |
| [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings/) | Image resize settings class |
| [IntRange](/psd/python-net/aspose.psd/intrange/) | Class for representing sequence of elements |
| [License](/psd/python-net/aspose.psd/license/) | Provides methods to license the component. |
| [LoadOptions](/psd/python-net/aspose.psd/loadoptions/) | Represents the loading options. |
| [Matrix](/psd/python-net/aspose.psd/matrix/) | Replaces the GDI+ Matrix. |
| [Metered](/psd/python-net/aspose.psd/metered/) | Provides methods to set metered key. |
| [NonGenericDictionary](/psd/python-net/aspose.psd/nongenericdictionary/) | Represents a non generic dictionary. |
| [NonGenericList](/psd/python-net/aspose.psd/nongenericlist/) | Non generic list of objects |
| [ObjectWithBounds](/psd/python-net/aspose.psd/objectwithbounds/) | The object having bounds. |
| [OpenTypeFontsCache](/psd/python-net/aspose.psd/opentypefontscache/) | Cache for OpenType fonts that are installed in the system. |
| [Pen](/psd/python-net/aspose.psd/pen/) | Defines an object used to draw lines, curves and figures. |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) | The pixel data format. This is an immutable object. |
| [PixelsData](/psd/python-net/aspose.psd/pixelsdata/) | The class to store image pixels data and its bounds. |
| [PluginLicenseException](/psd/python-net/aspose.psd/pluginlicenseexception/) | Exception for Plugin License |
| [Point](/psd/python-net/aspose.psd/point/) | Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane. |
| [PointF](/psd/python-net/aspose.psd/pointf/) | Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane. |
| [RasterCachedImage](/psd/python-net/aspose.psd/rastercachedimage/) | Represents a raster image supporting raster graphics operations. This image caches pixel data when required. |
| [RasterImage](/psd/python-net/aspose.psd/rasterimage/) | Represents a raster image supporting raster graphics operations. |
| [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings/) | The raw data settings |
| [Rectangle](/psd/python-net/aspose.psd/rectangle/) | Stores a set of four integers that represent the location and size of a rectangle. |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef/) | Stores a set of four floating-point numbers that represent the location and size of a rectangle. |
| [Region](/psd/python-net/aspose.psd/region/) | Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited. |
| [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting/) | The resolution setting for image save options. |
| [Shape](/psd/python-net/aspose.psd/shape/) | The shape. A continuous set of points connected using a specific rule. |
| [ShapeSegment](/psd/python-net/aspose.psd/shapesegment/) | Represents a shape segment. A segment is a line or curve connecting two points. |
| [Size](/psd/python-net/aspose.psd/size/) | Represents size. |
| [SizeF](/psd/python-net/aspose.psd/sizef/) | Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle. |
| [Source](/psd/python-net/aspose.psd/source/) | The source is used to contain all relevant information for an object pipe. |
| [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) | Represents split stream container which contains the stream and provides stream processing routines. |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) | Represents stream container which contains the stream and provides stream processing routines. |
| [StringFormat](/psd/python-net/aspose.psd/stringformat/) | Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited. |
| [TransparencySupporter](/psd/python-net/aspose.psd/transparencysupporter/) | The object supporting transparency. |
| [VectorImage](/psd/python-net/aspose.psd/vectorimage/) | The vector image is the base class for all type of vector images. |
## **Enumerations**
| **Enumeration** | **Description** |
| :- | :- |
| [CacheType](/psd/python-net/aspose.psd/cachetype/) | Specifies the cache type to use. |
| [CharacterSet](/psd/python-net/aspose.psd/characterset/) | Represents the character set used. |
| [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) | Specifies which objects use color adjustment information. |
| [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) | Specifies individual channels in the CMYK (cyan, magenta, yellow, black) color space. This enumeration is used by the SetOutputChannel methods. |
| [ColorCompareMethod](/psd/python-net/aspose.psd/colorcomparemethod/) | Color comparison method to adjust to nearest neighbor |
| [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) | Specifies the types of images and colors that will be affected by the color and grayscale adjustment settings of an [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/). |
| [ColorQuantizationMethod](/psd/python-net/aspose.psd/colorquantizationmethod/) | Colors quantization  methods |
| [CompositingQuality](/psd/python-net/aspose.psd/compositingquality/) | Specifies the quality level to use during compositing. |
| [DashCap](/psd/python-net/aspose.psd/dashcap/) | Specifies the type of graphic shape to use on both ends of each dash in a dashed line. |
| [DashStyle](/psd/python-net/aspose.psd/dashstyle/) | Specifies the style of dashed lines drawn with a [Pen](/psd/python-net/aspose.psd/pen/) object. |
| [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode/) | The data recovery mode. |
| [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod/) | Dithering method. |
| [DitheringMethods](/psd/python-net/aspose.psd/ditheringmethods/) | The dithering methods used to control color conversion. |
| [FileFormat](/psd/python-net/aspose.psd/fileformat/) | One of supported PSD file formats. |
| [FillMode](/psd/python-net/aspose.psd/fillmode/) | Specifies how the interior of a closed path is filled. |
| [FontStyle](/psd/python-net/aspose.psd/fontstyle/) | Specifies style information applied to text. |
| [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) | Specifies the unit of measure for the given data. |
| [HatchStyle](/psd/python-net/aspose.psd/hatchstyle/) | Specifies the different patterns available for [HatchBrush](/psd/python-net/aspose.psd.brushes/hatchbrush/) objects. |
| [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) | Specifies the type of display for hot-key prefixes that relate to text. |
| [ImageFilterType](/psd/python-net/aspose.psd/imagefiltertype/) | Image filters to use |
| [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) | The [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) enumeration specifies the algorithm that is used when images are scaled or rotated. |
| [KnownColor](/psd/python-net/aspose.psd/knowncolor/) | Specifies the known system colors. |
| [LineCap](/psd/python-net/aspose.psd/linecap/) | Specifies the available cap styles with which a [Pen](/psd/python-net/aspose.psd/pen/) object can end a line. |
| [LineJoin](/psd/python-net/aspose.psd/linejoin/) | Specifies how to join consecutive line or curve segments in a figure (subpath) contained in a [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) object. |
| [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) | Specifies the order for matrix transform operations. |
| [PdfComplianceVersion](/psd/python-net/aspose.psd/pdfcomplianceversion/) | Specifies the PDF compliance level to output file. |
| [PenAlignment](/psd/python-net/aspose.psd/penalignment/) | Specifies the alignment of a [Pen](/psd/python-net/aspose.psd/pen/) object in relation to the theoretical, zero-width line. |
| [PenType](/psd/python-net/aspose.psd/pentype/) | Specifies the type of fill a [Pen](/psd/python-net/aspose.psd/pen/) object uses to fill lines. |
| [PixelFormat](/psd/python-net/aspose.psd/pixelformat/) | The pixel data format actual meaning. |
| [ResizeType](/psd/python-net/aspose.psd/resizetype/) | Specifies the resize type. |
| [ResolutionUnit](/psd/python-net/aspose.psd/resolutionunit/) | Resolution unit enum. |
| [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype/) | Specifies how much an image is rotated and the axis used to flip the image. |
| [SeekOrigin](/psd/python-net/aspose.psd/seekorigin/) | Provides the fields that represent reference points in [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) for seeking. |
| [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode/) | Specifies whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas. |
| [StringAlignment](/psd/python-net/aspose.psd/stringalignment/) | Specifies the alignment of a text string relative to its layout rectangle. |
| [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute/) | The enumeration specifies how to substitute digits in a string according to a user's locale or language. |
| [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) | Specifies the display and layout information for text strings. |
| [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) | Specifies how to trim characters from a string that does not completely fit into a layout shape. |
| [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint/) | Specifies the quality of text rendering. |
| [WarpMode](/psd/python-net/aspose.psd/warpmode/) | Specifies the type of warp transformation applied. |
| [WrapMode](/psd/python-net/aspose.psd/wrapmode/) | Specifies how a texture or gradient is tiled when it is smaller than the area being filled. |
