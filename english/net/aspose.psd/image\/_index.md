---
title: Class Image
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Image class. 
type: docs
weight: 4710
url: /net/aspose.psd/image/
---
{{< psd/tize >}}
## Image class

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
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
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } |  |
| abstract [Height](../../aspose.psd/image/height/) { get; } |  |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } |  |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } |  |
| [Palette](../../aspose.psd/image/palette/) { get; set; } |  |
| [Size](../../aspose.psd/image/size/) { get; } |  |
| abstract [Width](../../aspose.psd/image/width/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) |  |
| static [Load](../../aspose.psd/image/load/#load)(Stream) |  |
| static [Load](../../aspose.psd/image/load/#load_2)(string) |  |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) |  |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) |  |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() |  |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) |  |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() |  |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) |  |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() |  |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) |  |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) |  |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) |  |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) |  |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) |  |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) |  |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) |  |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) |  |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) |  |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) |  |
| [Save](../../aspose.psd/image/save/#save)() |  |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) |  |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) |  |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) |  |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) |  |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) |  |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) |  |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) |  |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) |  |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) |  |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) |  |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) |  |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) |  |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) |  |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) |  |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) |  |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) |  |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) |  |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) |  |

### See Also

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


