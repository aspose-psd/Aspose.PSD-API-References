---
title: Image
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 4390
url: /net/aspose.psd/image/
---
## Image class

The image is the base class for all type of images.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](autoadjustpalette) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| virtual [BackgroundColor](backgroundcolor) { get; set; } | Gets or sets a value for the background color. |
| abstract [BitsPerPixel](bitsperpixel) { get; } | Gets the image bits per pixel count. |
| [Bounds](bounds) { get; } | Gets the image bounds. |
| [BufferSizeHint](buffersizehint) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](container) { get; } | Gets the [`Image`](../image) container. |
| virtual [FileFormat](fileformat) { get; } | Gets a value of file format |
| virtual [HasBackgroundColor](hasbackgroundcolor) { get; set; } | Gets or sets a value indicating whether image has background color. |
| abstract [Height](height) { get; } | Gets the image height. |
| [InterruptMonitor](interruptmonitor) { get; set; } | Gets or sets the interrupt monitor. |
| [Palette](palette) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| [Size](size) { get; } | Gets the image size. |
| abstract [Width](width) { get; } | Gets the image width. |

## Methods

| Name | Description |
| --- | --- |
| static [Create](create)(ImageOptionsBase, int, int) | Creates a new image using the specified create options. |
| static [Load](load)(Stream) | Loads a new image from the specified stream. |
| static [Load](load)(string) | Loads a new image from the specified file. |
| static [Load](load)(Stream, LoadOptions) | Loads a new image from the specified stream. |
| static [Load](load)(string, LoadOptions) | Loads a new image from the specified file. |
| [CanSave](cansave)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| virtual [GetDefaultOptions](getdefaultoptions)(object[]) | Gets the default options. |
| virtual [GetOriginalOptions](getoriginaloptions)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../datastreamsupporter/save) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](./save) method as the second parameter. |
| [Resize](resize)(int, int) | Resizes the image. The default LeftTopToLeftTop is used. |
| abstract [Resize](resize)(int, int, ImageResizeSettings) | Resizes the image. |
| abstract [Resize](resize)(int, int, ResizeType) | Resizes the image. |
| [ResizeHeightProportionally](resizeheightproportionally)(int) | Resizes the height proportionally. |
| virtual [ResizeHeightProportionally](resizeheightproportionally)(int, ImageResizeSettings) | Resizes the height proportionally. |
| virtual [ResizeHeightProportionally](resizeheightproportionally)(int, ResizeType) | Resizes the height proportionally. |
| [ResizeWidthProportionally](resizewidthproportionally)(int) | Resizes the width proportionally. |
| virtual [ResizeWidthProportionally](resizewidthproportionally)(int, ImageResizeSettings) | Resizes the width proportionally. |
| virtual [ResizeWidthProportionally](resizewidthproportionally)(int, ResizeType) | Resizes the width proportionally. |
| abstract [RotateFlip](rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the image. |
| [Save](save)() | Saves the image data to the underlying stream. |
| [Save](save)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](save)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| virtual [Save](save)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](save)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| abstract [SetPalette](setpalette)(IColorPalette, bool) | Sets the image palette. |
| static [CanLoad](canload)(Stream) | Determines whether image can be loaded from the specified stream. |
| static [CanLoad](canload)(string) | Determines whether image can be loaded from the specified file path. |
| static [CanLoad](canload)(Stream, LoadOptions) | Determines whether image can be loaded from the specified stream and optionally using the specified *loadOptions*. |
| static [CanLoad](canload)(string, LoadOptions) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| static [GetFileFormat](getfileformat)(Stream) | Gets the file format. |
| static [GetFileFormat](getfileformat)(string) | Gets the file format. |
| static [GetFittingRectangle](getfittingrectangle)(Rectangle, int, int) | Gets rectangle which fits the current image. |
| static [GetFittingRectangle](getfittingrectangle)(Rectangle, int[], int, int) | Gets rectangle which fits the current image. |
| static [GetProportionalHeight](getproportionalheight)(int, int, int) | Gets a proportional height. |
| static [GetProportionalWidth](getproportionalwidth)(int, int, int) | Gets a proportional width. |

### See Also

* class [DataStreamSupporter](../datastreamsupporter)
* interface [IObjectWithBounds](../iobjectwithbounds)
* namespace [Aspose.PSD](../../aspose.psd)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
