---
title: PsdImage
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 3410
url: /net/aspose.psd.fileformats.psd/psdimage/
---
## PsdImage class

Defines the PsdImage class that provides the ability to load, edit, save PSD files as well as update properties, add watermarks, perform graphics operations or convert one file format to another. Aspose.PSD supports import as a layer and export to the following formats: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb along with export to Pdf with selectable text

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Constructors

| Name | Description |
| --- | --- |
| [PsdImage](psdimage)(RasterImage) | Initializes a new instance of the [`PsdImage`](../psdimage) class from existing raster image (not psd image) with RGB color mode with 4 channels 8 bit/channel and no compression. |
| [PsdImage](psdimage)(Stream) | Initializes a new instance of the [`PsdImage`](../psdimage) class from specified path from raster image (not psd image in stream). Used to initialize psd image with default parameters - Color mode - rgb, 4 channels, 8 bit per channel, Compression - Raw. |
| [PsdImage](psdimage)(string) | Initializes a new instance of the [`PsdImage`](../psdimage) class from specified path from raster image (not psd image in path). Used to initialize psd image with default parameters - Color mode - rgb, 4 channels, 8 bit per channel, Compression - Raw. |
| [PsdImage](psdimage)(int, int) | Initializes a new instance of the [`PsdImage`](../psdimage) class with specified width and height. Used to initialize empty psd image. |
| [PsdImage](psdimage)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Initializes a new instance of the [`PsdImage`](../psdimage) class from existing raster image (not psd image) with constructor parameters. |
| [PsdImage](psdimage)(Stream, ColorModes, short, short, int, CompressionMethod) | Initializes a new instance of the [`PsdImage`](../psdimage) class from specified path from raster image (not psd image in stream) with constructor parameters. |
| [PsdImage](psdimage)(string, ColorModes, short, short, int, CompressionMethod) | Initializes a new instance of the [`PsdImage`](../psdimage) class from specified path from raster image (not psd image in path) with constructor parameters. |
| [PsdImage](psdimage)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Initializes a new instance of the [`PsdImage`](../psdimage) class with specified width,height, paletter, color mode, channels count and channels bit-length and specified compression mode parameters. Used to initialize empty psd image. |

## Properties

| Name | Description |
| --- | --- |
| [ActiveLayer](activelayer) { get; set; } | Gets or sets the active layer. |
| [BitsPerChannel](bitsperchannel) { get; } | Gets the bits per channel. |
| override [BitsPerPixel](bitsperpixel) { get; } | Gets the image bits per pixel count. |
| [ChannelsCount](channelscount) { get; } | Gets the PSD channels count. |
| [CmykColorProfile](cmykcolorprofile) { get; set; } | Gets or sets the CMYK color profile for CMYK PSD images. Must be in pair with RgbColorProfile for correct color conversion. |
| [ColorMode](colormode) { get; set; } | Gets or sets the color mode. |
| [Compression](compression) { get; } | Gets the compression method. |
| override [FileFormat](fileformat) { get; } | Gets a value of file format |
| [GlobalAngle](globalangle) { get; set; } | Gets or sets the global angle. |
| [GlobalLayerMaskInfo](globallayermaskinfo) { get; } | Gets the global layer mask info. |
| [GlobalLayerResources](globallayerresources) { get; set; } | Gets or sets the global layer resources. |
| [GrayColorProfile](graycolorprofile) { get; set; } | Gets or sets the GRAY (monochrome) color profile for Grayscale PSD images. |
| override [HasAlpha](hasalpha) { get; } | Gets or sets the vertical resolution, in pixels per inch, of this [`RasterImage`](../../aspose.psd/rasterimage). |
| [HasTransparencyData](hastransparencydata) { get; set; } | Gets or sets a value indicating whether first alpha channel contains the transparency data for the merged result when specifying layers data. |
| override [Height](height) { get; } | Gets the image height. |
| override [HorizontalResolution](horizontalresolution) { get; set; } | Gets or sets the horizontal resolution, in pixels per inch, of this [`PsdImage`](../psdimage). |
| [ImageResources](imageresources) { get; set; } | Gets or sets the PSD image resources. |
| [IsFlatten](isflatten) { get; } | Gets a value indicating whether psd image is flattened. |
| [Layers](layers) { get; set; } | Gets or sets the PSD layers. |
| [LinkedLayersManager](linkedlayersmanager) { get; } | Gets the linked layers manager. |
| override [RawDataFormat](rawdataformat) { get; } | Gets the raw data format. |
| [RgbColorProfile](rgbcolorprofile) { get; set; } | Gets or sets the RGB color profile for CMYK PSD images. Must be in pair with CmykColorProfile for correct color conversion. |
| [SmartObjectProvider](smartobjectprovider) { get; } | Gets the smart object provider. |
| [Version](version) { get; set; } | Gets or sets the version. |
| override [VerticalResolution](verticalresolution) { get; set; } | Gets or sets the vertical resolution, in pixels per inch, of this [`PsdImage`](../psdimage). |
| override [Width](width) { get; } | Gets the image width. |
| override [XmpData](xmpdata) { get; set; } | Gets or sets the XMP metadata. |

## Methods

| Name | Description |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](addblackwhiteadjustmentlayer)() | Adds the black white adjustment layer. |
| [AddBrightnessContrastAdjustmentLayer](addbrightnesscontrastadjustmentlayer)(int, int) | Adds the brightness/contrast adjustment layer. |
| [AddChannelMixerAdjustmentLayer](addchannelmixeradjustmentlayer)() | Adds the channel mixer adjustment layer with default parameters |
| [AddColorBalanceAdjustmentLayer](addcolorbalanceadjustmentlayer)() | Adds the color balance adjustment layer. |
| [AddCurvesAdjustmentLayer](addcurvesadjustmentlayer)() | Adds the Curves Adjustment layer. |
| [AddExposureAdjustmentLayer](addexposureadjustmentlayer)(float, float, float) | Adds the exposure adjustment layer. |
| [AddHueSaturationAdjustmentLayer](addhuesaturationadjustmentlayer)() | Adds the hue/saturation adjustment layer. |
| [AddInvertAdjustmentLayer](addinvertadjustmentlayer)() | Adds an invert adjustment layer. |
| [AddLayer](addlayer)(Layer) | Adds the layer. |
| [AddLayerGroup](addlayergroup)(string, int, bool) | Adds the layer group. |
| [AddLevelsAdjustmentLayer](addlevelsadjustmentlayer)() | Adds the Levels adjustment layer. |
| [AddPhotoFilterLayer](addphotofilterlayer)(Color) | Adds the PhotoFilter layer. |
| [AddRegularLayer](addregularlayer)() | Adds a new regular layer. |
| [AddTextLayer](addtextlayer)(string, Rectangle) | Adds a new Text layer. |
| [AddVibranceAdjustmentLayer](addvibranceadjustmentlayer)() | Adds the Vibrance adjustment layer. |
| override [AdjustBrightness](adjustbrightness)(int) | Adjust of a brightness for image. |
| override [AdjustContrast](adjustcontrast)(float) | Image contrasting |
| override [AdjustGamma](adjustgamma)(float) | Gamma-correction of an image. |
| override [AdjustGamma](adjustgamma)(float, float, float) | Gamma-correction of an image. |
| override [BinarizeBradley](binarizebradley)(double) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeBradley](binarizebradley)(double, int) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeFixed](binarizefixed)(byte) | Binarization of an image with predefined threshold |
| override [BinarizeOtsu](binarizeotsu)() | Binarization of an image with Otsu thresholding |
| [Convert](convert)(PsdOptions) | Converts this image format to the one specified in options. |
| override [Crop](crop)(Rectangle) | Cropping the image. |
| override [Dither](dither)(DitheringMethod, int, IColorPalette) | Performs dithering on the current image. |
| override [Filter](filter)(Rectangle, FilterOptionsBase) | Filters the specified rectangle. |
| [FlattenImage](flattenimage)() | Flattens all layers. |
| override [Grayscale](grayscale)() | Transformation of an image to its grayscale representation |
| [MergeLayers](mergelayers)(Layer, Layer) | Merges the layers. |
| override [ReplaceColor](replacecolor)(int, byte, int) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| override [ReplaceNonTransparentColors](replacenontransparentcolors)(int) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| override [ResizeHeightProportionally](resizeheightproportionally)(int, ImageResizeSettings) | Resizes the height proportionally. |
| override [ResizeHeightProportionally](resizeheightproportionally)(int, ResizeType) | Resizes the height proportionally. |
| override [ResizeWidthProportionally](resizewidthproportionally)(int, ImageResizeSettings) | Resizes the width proportionally. |
| override [ResizeWidthProportionally](resizewidthproportionally)(int, ResizeType) | Resizes the width proportionally. |
| override [Rotate](rotate)(float) | Rotate image around the center. |
| override [Rotate](rotate)(float, bool, Color) | Rotate image around the center. |

## Other Members

| Name | Description |
| --- | --- |
| const [DefaultVersion](defaultversion) | The default PSD version. |

### See Also

* class [RasterCachedImage](../../aspose.psd/rastercachedimage)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
