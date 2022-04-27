---
title: RasterImage
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 5120
url: /net/aspose.psd/rasterimage/
---
## RasterImage class

Represents a raster image supporting raster graphics operations.

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
```

## Properties

| Name | Description |
| --- | --- |
| virtual [HasAlpha](hasalpha) { get; } | Gets a value indicating whether this instance has alpha. |
| virtual [HasTransparentColor](hastransparentcolor) { get; set; } | Gets a value indicating whether image has transparent color. |
| virtual [HorizontalResolution](horizontalresolution) { get; set; } | Gets or sets the horizontal resolution, in pixels per inch, of this [`RasterImage`](../rasterimage). |
| virtual [ImageOpacity](imageopacity) { get; } | Gets opacity of this image. |
| [IsRawDataAvailable](israwdataavailable) { get; } | Gets a value indicating whether raw data loading is available. |
| virtual [PremultiplyComponents](premultiplycomponents) { get; set; } | Gets or sets a value indicating whether the image components must be premultiplied. |
| [RawCustomColorConverter](rawcustomcolorconverter) { get; set; } | Gets or sets the custom color converter |
| virtual [RawDataFormat](rawdataformat) { get; } | Gets the raw data format. |
| [RawDataSettings](rawdatasettings) { get; } | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| [RawFallbackIndex](rawfallbackindex) { get; set; } | Gets or sets the fallback index to use when palette index is out of bounds |
| [RawIndexedColorConverter](rawindexedcolorconverter) { get; set; } | Gets or sets the indexed color converter |
| virtual [RawLineSize](rawlinesize) { get; } | Gets the raw line size in bytes. |
| virtual [TransparentColor](transparentcolor) { get; set; } | Gets the image transparent color. |
| virtual [UpdateXmpData](updatexmpdata) { get; set; } | Gets or sets a value indicating whether to update the XMP metadata. |
| virtual [UseRawData](userawdata) { get; set; } | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| virtual [VerticalResolution](verticalresolution) { get; set; } | Gets or sets the vertical resolution, in pixels per inch, of this [`RasterImage`](../rasterimage). |
| virtual [XmpData](xmpdata) { get; set; } | Gets or sets the XMP metadata. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AdjustBrightness](adjustbrightness)(int) |  |
| virtual [AdjustContrast](adjustcontrast)(float) |  |
| virtual [AdjustGamma](adjustgamma)(float) |  |
| virtual [AdjustGamma](adjustgamma)(float, float, float) |  |
| virtual [BinarizeBradley](binarizebradley)(double) |  |
| virtual [BinarizeBradley](binarizebradley)(double, int) |  |
| virtual [BinarizeFixed](binarizefixed)(byte) |  |
| virtual [BinarizeOtsu](binarizeotsu)() |  |
| virtual [Crop](crop)(Rectangle) |  |
| virtual [Crop](crop)(int, int, int, int) |  |
| [Dither](dither)(DitheringMethod, int) | Performs dithering on the current image. |
| abstract [Dither](dither)(DitheringMethod, int, IColorPalette) | Performs dithering on the current image. |
| virtual [Filter](filter)(Rectangle, FilterOptionsBase) |  |
| [GetArgb32Pixel](getargb32pixel)(int, int) | Gets an image 32-bit ARGB pixel. |
| [GetDefaultArgb32Pixels](getdefaultargb32pixels)(Rectangle) | Gets the default 32-bit ARGB pixels array. |
| [GetDefaultPixels](getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Gets the default pixels array using partial pixel loader. |
| [GetDefaultRawData](getdefaultrawdata)(Rectangle, RawDataSettings) | Gets the default raw data array. |
| [GetDefaultRawData](getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Gets the default raw data array using partial pixel loader. |
| virtual [GetModifyDate](getmodifydate)(bool) | Gets the date and time the resource image was last modified. |
| [GetPixel](getpixel)(int, int) | Gets an image pixel. |
| [GetSkewAngle](getskewangle)() |  |
| virtual [Grayscale](grayscale)() |  |
| [LoadArgb32Pixels](loadargb32pixels)(Rectangle) | Loads 32-bit ARGB pixels. |
| [LoadArgb64Pixels](loadargb64pixels)(Rectangle) | Loads 64-bit ARGB pixels. |
| [LoadCmyk32Pixels](loadcmyk32pixels)(Rectangle) | Loads pixels in CMYK format. |
| [LoadPartialArgb32Pixels](loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Loads 32-bit ARGB pixels partially by packs. |
| [LoadPartialPixels](loadpartialpixels)(Rectangle, IPartialPixelLoader) | Loads pixels partially by packs. |
| [LoadPixels](loadpixels)(Rectangle) | Loads pixels. |
| [LoadRawData](loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Loads raw data. |
| [LoadRawData](loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Loads raw data. |
| [NormalizeAngle](normalizeangle)() |  |
| virtual [NormalizeAngle](normalizeangle)(bool, Color) |  |
| [ReadArgb32ScanLine](readargb32scanline)(int) | Reads the whole scan line by the specified scan line index. |
| [ReadScanLine](readscanline)(int) | Reads the whole scan line by the specified scan line index. |
| [ReplaceColor](replacecolor)(Color, byte, Color) |  |
| virtual [ReplaceColor](replacecolor)(int, byte, int) |  |
| [ReplaceNonTransparentColors](replacenontransparentcolors)(Color) |  |
| virtual [ReplaceNonTransparentColors](replacenontransparentcolors)(int) |  |
| override [Resize](resize)(int, int, ImageResizeSettings) |  |
| override [Resize](resize)(int, int, ResizeType) |  |
| virtual [Rotate](rotate)(float) |  |
| virtual [Rotate](rotate)(float, bool, Color) |  |
| override [Save](save)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [SaveArgb32Pixels](saveargb32pixels)(Rectangle, int[]) | Saves the 32-bit ARGB pixels. |
| [SaveCmyk32Pixels](savecmyk32pixels)(Rectangle, int[]) |  |
| [SavePixels](savepixels)(Rectangle, Color[]) | Saves the pixels. |
| [SaveRawData](saverawdata)(byte[], int, Rectangle, RawDataSettings) | Saves the raw data. |
| [SetArgb32Pixel](setargb32pixel)(int, int, int) | Sets an image 32-bit ARGB pixel for the specified position. |
| override [SetPalette](setpalette)(IColorPalette, bool) |  |
| [SetPixel](setpixel)(int, int, Color) | Sets an image pixel for the specified position. |
| virtual [SetResolution](setresolution)(double, double) |  |
| virtual [ToBitmap](tobitmap)() |  |
| [WriteArgb32ScanLine](writeargb32scanline)(int, int[]) | Writes the whole scan line to the specified scan line index. |
| [WriteScanLine](writescanline)(int, Color[]) | Writes the whole scan line to the specified scan line index. |

### See Also

* class [Image](../image)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader)
* namespace [Aspose.PSD](../../aspose.psd)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
