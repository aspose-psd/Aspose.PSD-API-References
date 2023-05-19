---
title: Class RasterImage
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.RasterImage class. 
type: docs
weight: 5450
url: /net/aspose.psd/rasterimage/
---
{{< psd/tize >}}
## RasterImage class

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
```

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } |  |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } |  |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } |  |
| [Bounds](../../aspose.psd/image/bounds/) { get; } |  |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } |  |
| [Container](../../aspose.psd/image/container/) { get; } |  |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } |  |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } |  |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } |  |
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } |  |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } |  |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } |  |
| abstract [Height](../../aspose.psd/image/height/) { get; } |  |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } |  |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } |  |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } |  |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } |  |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } |  |
| [Palette](../../aspose.psd/image/palette/) { get; set; } |  |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } |  |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } |  |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } |  |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } |  |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } |  |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } |  |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } |  |
| [Size](../../aspose.psd/image/size/) { get; } |  |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } |  |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } |  |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } |  |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } |  |
| abstract [Width](../../aspose.psd/image/width/) { get; } |  |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } |  |

## Methods

| Name | Description |
| --- | --- |
| virtual [AdjustBrightness](../../aspose.psd/rasterimage/adjustbrightness/)(int) |  |
| virtual [AdjustContrast](../../aspose.psd/rasterimage/adjustcontrast/)(float) |  |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma)(float) |  |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma_1)(float, float, float) |  |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley)(double) |  |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley_1)(double, int) |  |
| virtual [BinarizeFixed](../../aspose.psd/rasterimage/binarizefixed/)(byte) |  |
| virtual [BinarizeOtsu](../../aspose.psd/rasterimage/binarizeotsu/)() |  |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() |  |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) |  |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop)(Rectangle) |  |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop_1)(int, int, int, int) |  |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() |  |
| [Dither](../../aspose.psd/rasterimage/dither/#dither)(DitheringMethod, int) |  |
| abstract [Dither](../../aspose.psd/rasterimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) |  |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) |  |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) |  |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) |  |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) |  |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) |  |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata)(Rectangle, RawDataSettings) |  |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata_1)(Rectangle, IPartialRawDataLoader, RawDataSettings) |  |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) |  |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() |  |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) |  |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() |  |
| virtual [Grayscale](../../aspose.psd/rasterimage/grayscale/)() |  |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) |  |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) |  |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) |  |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) |  |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) |  |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) |  |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) |  |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) |  |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata_1)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) |  |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle)() |  |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle_1)(bool, Color) |  |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) |  |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) |  |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor)(Color, byte, Color) |  |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor_1)(int, byte, int) |  |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors)(Color) |  |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) |  |
| [Resize](../../aspose.psd/image/resize/)(int, int) |  |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_1)(int, int, ImageResizeSettings) |  |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_2)(int, int, ResizeType) |  |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) |  |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) |  |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) |  |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) |  |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) |  |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) |  |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate)(float) |  |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate_1)(float, bool, Color) |  |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) |  |
| [Save](../../aspose.psd/image/save/)() |  |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) |  |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) |  |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) |  |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) |  |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) |  |
| override [Save](../../aspose.psd/rasterimage/save/#save_3)(Stream, ImageOptionsBase, Rectangle) |  |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) |  |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) |  |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) |  |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) |  |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) |  |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) |  |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) |  |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) |  |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) |  |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) |  |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() |  |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) |  |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) |  |

### See Also

* class [Image](../image/)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


