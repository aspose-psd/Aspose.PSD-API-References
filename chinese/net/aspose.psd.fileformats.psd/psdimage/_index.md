---
title: PsdImage
second_title: Aspose.PSD for .NET API 参考
description: 定义 PsdImage 类该类提供加载编辑保存 PSD 文件以及 更新属性添加水印执行图形操作或将一种文件格式转换为其他 Aspose.PSD 支持作为图层导入并导出为以下格式 PngJpegJpeg2000GifBmpTiffPsdPsb 以及导出为带有可选文本的 Pdf
type: docs
weight: 3480
url: /zh/net/aspose.psd.fileformats.psd/psdimage/
---
## PsdImage class

定义 PsdImage 类，该类提供加载、编辑、保存 PSD 文件以及 更新属性、添加水印、执行图形操作或将一种文件格式转换为其他。 Aspose.PSD 支持作为图层导入并导出为以下格式： Png、Jpeg、Jpeg2000、Gif、Bmp、Tiff、Psd、Psb 以及导出为带有可选文本的 Pdf

```csharp
public sealed class PsdImage : RasterCachedImage
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PsdImage](psdimage#constructor)(RasterImage) | 从现有的光栅图像（不是 psd 图像）初始化[`PsdImage`](../psdimage)类的新实例，RGB 颜色模式为 4通道 8 位/通道，无压缩。 |
| [PsdImage](psdimage#constructor_4)(Stream) | 从光栅图像（不是流中的 psd 图像）的指定路径初始化[`PsdImage`](../psdimage)类的新实例。用于使用默认参数初始化 psd 图像 - 颜色模式 - rgb，4 通道，每通道 8 位，压缩 - 原始。 |
| [PsdImage](psdimage#constructor_6)(string) | 从光栅图像的指定路径（不是路径中的 psd 图像）初始化[`PsdImage`](../psdimage)类的新实例。用于使用默认参数初始化 psd 图像 - 颜色模式 - rgb，4 通道，每通道 8 位，压缩 - 原始。 |
| [PsdImage](psdimage#constructor_2)(int, int) | 初始化具有指定宽度和高度的[`PsdImage`](../psdimage)类的新实例。用于初始化空的 psd 图像。 |
| [PsdImage](psdimage#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | 使用构造函数参数从现有光栅图像（不是 psd 图像）初始化[`PsdImage`](../psdimage)类的新实例。 |
| [PsdImage](psdimage#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | 使用构造函数从光栅图像（不是流中的 psd 图像）的指定路径初始化[`PsdImage`](../psdimage)类的新实例参数。 |
| [PsdImage](psdimage#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | 使用构造函数从光栅图像（不是路径中的 psd 图像）的指定路径初始化[`PsdImage`](../psdimage)类的新实例参数。 |
| [PsdImage](psdimage#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | 初始化[`PsdImage`](../psdimage)类的新实例，具有指定的宽度、高度、调色板、颜色模式、通道数和通道位长和指定的压缩模式参数。用于初始化空的 psd 图像。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer) { get; set; } | 获取或设置活动层。 |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette) { get; set; } | 获取或设置是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor) { get; set; } | 获取或设置背景颜色的值。 |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel) { get; } | 获取每个通道的位。 |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel) { get; } | 获取每像素的图像位数。 |
| [Bounds](../../aspose.psd/image/bounds) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount) { get; } | 获取 PSD 通道数。 |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile) { get; set; } | 获取或设置 CMYK PSD 图像的 CMYK 颜色配置文件。必须与 RgbColorProfile 配对以进行正确的颜色转换。 |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode) { get; set; } | 获取或设置颜色模式。 |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression) { get; } | 获取压缩方法。 |
| [Container](../../aspose.psd/image/container) { get; } | 获取[`Image`](../../aspose.psd/image)容器。 |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | 获取一个值，该值指示该实例是否被释放。 |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat) { get; } | 获取文件格式的值 |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle) { get; set; } | 获取或设置全局角度。 |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo) { get; } | 获取全局图层蒙版信息。 |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources) { get; set; } | 获取或设置全局图层资源。 |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile) { get; set; } | 获取或设置灰度 PSD 图像的 GRAY（单色）颜色配置文件。 |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha) { get; } | 获取或设置此[`RasterImage`](../../aspose.psd/rasterimage)的垂直分辨率，以每英寸像素为单位。 |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor) { get; set; } | 获取或设置一个值，该值指示图像是否具有背景色。 |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata) { get; set; } | 获取或设置一个值，该值指示在指定图层数据时第一个 Alpha 通道是否包含合并结果的透明度数据。 |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor) { get; set; } | 获取图像是否具有透明色的值。 |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height) { get; } | 获取图像高度。 |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution) { get; set; } | 获取或设置此[`PsdImage`](../psdimage)的水平分辨率，以每英寸像素为单位。 |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity) { get; } | 获取此图像的不透明度。 |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources) { get; set; } | 获取或设置 PSD 图片资源。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached) { get; } | 获取当前是否缓存图像数据的值。 |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten) { get; } | 获取一个表示psd图像是否被展平的值。 |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable) { get; } | 获取一个值，该值指示是否可以加载原始数据。 |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers) { get; set; } | 获取或设置 PSD 层。 |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager) { get; } | 获取链接层管理器。 |
| [Palette](../../aspose.psd/image/palette) { get; set; } | 获取或设置调色板。直接表示像素时不使用调色板。 |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents) { get; set; } | 获取或设置一个值，该值指示是否必须对图像分量进行预乘。 |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter) { get; set; } | 获取或设置自定义颜色转换器 |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat) { get; } | 获取原始数据格式。 |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings) { get; } | 获取当前的原始数据设置。请注意，使用这些设置时，数据加载时无需转换。 |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex) { get; set; } | 获取或设置调色板索引超出范围时使用的后备索引 |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter) { get; set; } | 获取或设置索引颜色转换器 |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize) { get; } | 获取原始行大小（以字节为单位）。 |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile) { get; set; } | 获取或设置 CMYK PSD 图像的 RGB 颜色配置文件。必须与 CmykColorProfile 配对以进行正确的颜色转换。 |
| [Size](../../aspose.psd/image/size) { get; } | 获取图像大小。 |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider) { get; } | 获取智能对象提供者。 |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor) { get; set; } | 获取图像透明色。 |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata) { get; set; } | 获取或设置是否更新 XMP 元数据的值。 |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata) { get; set; } | 获取或设置一个值，该值指示当原始数据加载可用时是否使用原始数据加载。 |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version) { get; set; } | 获取或设置版本。 |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution) { get; set; } | 获取或设置此[`PsdImage`](../psdimage)的垂直分辨率，以每英寸像素为单位。 |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width) { get; } | 获取图像宽度。 |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata) { get; set; } | 获取或设置 XMP 元数据。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer)() | 添加黑白调整图层。 |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer)(int, int) | 添加亮度/对比度调整层。 |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer)() | 使用默认参数添加通道混合器调整层 |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer)() | 添加色彩平衡调整图层。 |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer)() | 添加曲线调整图层。 |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer)(float, float, float) | 添加曝光调整图层。 |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer)() | 添加色相/饱和度调整图层。 |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer)() | 添加反转调整图层。 |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer)(Layer) | 添加图层。 |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup)(string, int, bool) | 添加图层组。 |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer)() | 添加色阶调整图层。 |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer)(Color) | 添加照片滤镜层。 |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer)() | 添加一个新的常规层。 |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer)(string, Rectangle) | 添加一个新的文本层。 |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer)() | 添加自然饱和度调整图层。 |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness)(int) | 调整图像的亮度。 |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast)(float) | 图像对比度 |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma#adjustgamma)(float) | 图像的伽玛校正。 |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma#adjustgamma_1)(float, float, float) | 图像的伽玛校正。 |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley#binarizebradley)(double) | 使用 Bradley 自适应阈值算法对图像进行二值化，使用积分图像阈值 |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley#binarizebradley_1)(double, int) | 使用 Bradley 自适应阈值算法对图像进行二值化，使用积分图像阈值 |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed)(byte) | 具有预定义阈值的图像的二值化 |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu)() | 使用 Otsu 阈值对图像进行二值化 |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata)() | 缓存数据并确保不会从底层[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer)执行额外的数据加载。 |
| [CanSave](../../aspose.psd/image/cansave)(ImageOptionsBase) | 确定图像是否可以保存为传递的保存选项表示的指定文件格式。 |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert)(PsdOptions) | 将此图像格式转换为选项中指定的格式。 |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop#crop)(Rectangle) | 裁剪图像。 |
| virtual [Crop](../../aspose.psd/rasterimage/crop)(int, int, int, int) | 带班次裁剪图像。 |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | 释放当前实例。 |
| [Dither](../../aspose.psd/rasterimage/dither)(DitheringMethod, int) | 对当前图像执行抖动。 |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | 对当前图像执行抖动。 |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter)(Rectangle, FilterOptionsBase) | 过滤指定的矩形。 |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage)() | 展平所有层。 |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel)(int, int) | 获取图像 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions)(object[]) | 获取默认选项。 |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | 获取默认的原始数据数组。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认的原始数据数组。 |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate)(bool) | 获取上次修改资源图像的日期和时间。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions)() | 获取基于原始文件设置的选项。 这有助于保持原始图像的位深度和其他参数不变。 例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../../aspose.psd/datastreamsupporter/save)方法，将生成每像素 8 位的输出 PNG 图像。 为了避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项并将它们 传递给[`Save`](../../aspose.psd/image/save)方法作为第二个参数。 |
| [GetPixel](../../aspose.psd/rasterimage/getpixel)(int, int) | 获取图像像素。 |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle)() | 获取倾斜角度。 此方法适用于扫描的文本文档，用于确定扫描时的倾斜角度。 |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale)() | 将图像转换为其灰度表示 |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels)(Rectangle) | 加载 32 位 ARGB 像素。 |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels)(Rectangle) | 加载 64 位 ARGB 像素。 |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels)(Rectangle) | 以 CMYK 格式加载像素。 |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | 部分按包加载 32 位 ARGB 像素。 |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | 部分按包加载像素。 |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels)(Rectangle) | 加载像素。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers)(Layer, Layer) | 合并图层。 |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle)() | 标准化角度。 此方法适用于扫描的文本文档，以消除倾斜扫描。 此方法使用[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle)和[`Rotate`](../../aspose.psd/rasterimage/rotate)方法。 |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle)(bool, Color) | 标准化角度。 此方法适用于扫描的文本文档，以消除倾斜扫描。 此方法使用[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle)和PSD。颜色）方法。 |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline)(int) | 按指定的扫描线索引读取整个扫描线。 |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline)(int) | 按指定的扫描线索引读取整个扫描线。 |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor)(Color, byte, Color) | 用允许的差异将一种颜色替换为另一种颜色，并保留原始 Alpha 值以保存平滑边缘。 |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor#replacecolor_1)(int, byte, int) | 用允许的差异将一种颜色替换为另一种颜色，并保留原始 Alpha 值以保存平滑边缘。 |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors)(Color) | 用新颜色替换所有非透明颜色并保留原始 alpha 值以保存平滑边缘。 注意：如果您在没有透明度的图像上使用它，所有颜色都将替换为一种颜色。 |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors#replacenontransparentcolors_1)(int) | 用新颜色替换所有非透明颜色并保留原始 alpha 值以保存平滑边缘。 注意：如果您在没有透明度的图像上使用它，所有颜色都将替换为一种颜色。 |
| [Resize](../../aspose.psd/image/resize)(int, int) | 调整图像大小。使用默认的LeftTopToLeftTop。 |
| override [Resize](../../aspose.psd/rastercachedimage/resize)(int, int, ImageResizeSettings) | 调整图像大小。 |
| override [Resize](../../aspose.psd/rastercachedimage/resize)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int) | 按比例调整高度。 |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | 按比例调整高度。 |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int) | 按比例调整宽度。 |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | 按比例调整宽度。 |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | 按比例调整宽度。 |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate#rotate)(float) | 围绕中心旋转图像。 |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate#rotate_1)(float, bool, Color) | 围绕中心旋转图像。 |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip)(RotateFlipType) | 旋转、翻转或旋转和翻转图像。 |
| [Save](../../aspose.psd/image/save)() | 将图像数据保存到底层流。 |
| [Save](../../aspose.psd/datastreamsupporter/save)(Stream) | 将对象的数据保存到指定的流中。 |
| [Save](../../aspose.psd/datastreamsupporter/save)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.psd/image/save)(Stream, ImageOptionsBase) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.psd/image/save)(string, ImageOptionsBase) | 根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。 |
| override [Save](../../aspose.psd/rasterimage/save)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.psd/image/save)(string, ImageOptionsBase, Rectangle) | 根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。 |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels)(Rectangle, int[]) | 保存 32 位 ARGB 像素。 |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels)(Rectangle, int[]) | 保存像素。 |
| [SavePixels](../../aspose.psd/rasterimage/savepixels)(Rectangle, Color[]) | 保存像素。 |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | 保存原始数据。 |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel)(int, int, int) | 为指定位置设置图像 32 位 ARGB 像素。 |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette)(IColorPalette, bool) | 设置图像调色板。 |
| [SetPixel](../../aspose.psd/rasterimage/setpixel)(int, int, Color) | 为指定位置设置图像像素。 |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution)(double, double) | 设置此[`RasterImage`](../../aspose.psd/rasterimage)的分辨率。 |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap)() | 将光栅图像转换为位图。 |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline)(int, int[]) | 将整个扫描线写入指定的扫描线索引。 |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline)(int, Color[]) | 将整个扫描线写入指定的扫描线索引。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion) | 默认的 PSD 版本。 |

### 例子

以下代码演示了将图像旋转特定角度值的能力。

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// 整张图片旋转
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// 图层旋转
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### 也可以看看

* class [RasterCachedImage](../../aspose.psd/rastercachedimage)
* 命名空间 [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
