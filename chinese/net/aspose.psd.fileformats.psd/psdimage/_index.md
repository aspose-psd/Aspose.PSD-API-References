---
title: "类 PsdImage"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.PsdImage 类。定义了 PsdImage 类，提供加载、编辑、保存 PSD 文件的能力，并可更新属性、添加水印、执行图形操作或将一种文件格式转换为另一种。Aspose.PSD 支持将图层导入以及导出为以下格式：Png、Jpeg、Jpeg2000、Gif、Bmp、Tiff、Psd、Psb，并可导出为可选择文本的 Pdf。"
type: docs
weight: 4050
url: /zh/net/aspose.psd.fileformats.psd/psdimage/
---
{{< psd/tize >}}
## PsdImage class

定义了 PsdImage 类，提供加载、编辑、保存 PSD 文件以及更新属性、添加水印、执行图形操作或将一种文件格式转换为另一种文件格式的能力。Aspose.PSD 支持将导入作为图层，并导出为以下格式：Png、Jpeg、Jpeg2000、Gif、Bmp、Tiff、Psd、Psb，以及导出为可选择文本的 Pdf。

```csharp
public sealed class PsdImage : RasterCachedImage
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | 使用现有光栅图像（非 PSD 图像）在 RGB 颜色模式、4 通道、8 位/通道且无压缩的情况下初始化 `PsdImage` 类的新实例。 |
| [PsdImage](psdimage/#constructor_4)(Stream) | 从指定路径的光栅图像（流中的非 PSD 图像）初始化 `PsdImage` 类的新实例。用于使用默认参数初始化 PSD 图像——颜色模式：rgb，4 通道，8 位/通道，压缩方式：Raw。 |
| [PsdImage](psdimage/#constructor_6)(string) | 从指定路径的光栅图像（路径中的非 PSD 图像）初始化 `PsdImage` 类的新实例。用于使用默认参数初始化 PSD 图像——颜色模式：rgb，4 通道，8 位/通道，压缩方式：Raw。 |
| [PsdImage](psdimage/#constructor_2)(int, int) | 使用指定的宽度和高度初始化 `PsdImage` 类的新实例。用于初始化空的 PSD 图像。 |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | 使用构造函数参数，从现有光栅图像（非 PSD 图像）初始化 `PsdImage` 类的新实例。 |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | 使用构造函数参数，从指定路径的光栅图像（流中的非 PSD 图像）初始化 `PsdImage` 类的新实例。 |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | 使用构造函数参数，从指定路径的光栅图像（路径中不是 psd 图像）初始化 `PsdImage` 类的新实例。 |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | 使用指定的宽度、长度、调色板、颜色模式、通道数、通道位深以及指定的压缩模式参数，初始化 `PsdImage` 类的新实例。用于初始化空的 psd 图像。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | 获取或设置活动图层。 |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 获取或设置一个值，指示是否自动调整调色板。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | 获取每个通道的位数。 |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | 获取图像每像素位数的计数。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | 获取 PSD 通道数量。 |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | 获取或设置 CMYK PSD 图像的 CMYK 颜色配置文件。必须与 RgbColorProfile 配对以实现正确的颜色转换。 |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | 获取或设置颜色模式。 |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | 获取压缩方式。 |
| [Container](../../aspose.psd/image/container/) { get; } | 获取 [`Image`](../../aspose.psd/image/) 容器。 |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | 获取文件格式的值 |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | 获取或设置全局角度。 |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | 获取全局图层蒙版信息。 |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | 获取或设置全局图层资源。 |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | 获取或设置灰度（单色）PSD 图像的 GRAY 颜色配置文件。 |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | 获取或设置此 [`RasterImage`](../../aspose.psd/rasterimage/) 的垂直分辨率（每英寸像素数）。 |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 获取或设置一个值，指示图像是否具有背景颜色。 |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | 获取或设置一个值，指示在指定图层数据时，第一个 alpha 通道是否包含合并结果的透明度数据。 |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | 获取一个值，指示图像是否具有透明颜色。 |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | 获取图像高度。 |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | 获取或设置此 `PsdImage` 的水平分辨率（每英寸像素数）。 |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | 获取此图像的不透明度。 |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | 获取或设置 PSD 图像资源。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | 获取一个值，指示图像数据当前是否已缓存。 |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | 获取一个值，指示 psd 图像是否已展平。 |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | 获取一个值，指示是否可以加载原始数据。 |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | 获取或设置 PSD 图层。 |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | 获取链接图层管理器。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，不使用颜色调色板。 |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | 获取或设置一个值，指示图像组件是否必须预乘。 |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | 获取或设置自定义颜色转换器 |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | 获取原始数据格式。 |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | 获取当前原始数据设置。注意，在使用这些设置时，数据会在不进行转换的情况下加载。 |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | 获取或设置当调色板索引超出范围时使用的回退索引 |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | 获取或设置索引颜色转换器 |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | 获取原始行大小（字节）。 |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | 获取或设置 CMYK PSD 图像的 RGB 颜色配置文件。必须与 CmykColorProfile 配对以实现正确的颜色转换。 |
| [Size](../../aspose.psd/image/size/) { get; } | 获取图像尺寸。 |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | 获取智能对象提供程序。 |
| [Timeline](../../aspose.psd.fileformats.psd/psdimage/timeline/) { get; } | 获取此 `PsdImage` 的 [`Timeline`](./timeline/)。 |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | 获取图像透明颜色。 |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | 获取或设置指示是否更新 XMP 元数据的值。 |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | 获取指示是否使用图像调色板的值。 |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | 获取或设置指示在可用原始数据加载时是否使用原始数据加载的值。 |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | 获取或设置版本。 |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | 获取或设置此 `PsdImage` 的垂直分辨率（每英寸像素数）。 |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | 获取图像宽度。 |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | 获取或设置 XMP 元数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | 添加黑白调整图层。 |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | 添加亮度/对比度调整图层。 |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | 添加带默认参数的通道混合器调整图层 |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | 添加颜色平衡调整图层。 |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | 添加曲线调整图层。 |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | 添加曝光调整图层。 |
| [AddGradientMapAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/)() | 添加渐变映射调整图层。 |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | 添加色相/饱和度调整图层。 |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | 添加反相调整图层。 |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | 添加图层。 |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | 添加图层组。 |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | 添加色阶调整图层。 |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | 添加照片滤镜图层。 |
| [AddPosterizeAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/)() | 添加色调分离调整图层。 |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | 添加一个新的普通图层。 |
| [AddSelectiveColorAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addselectivecoloradjustmentlayer/)() | 添加选择性颜色调整图层。 |
| [AddShapeLayer](../../aspose.psd.fileformats.psd/psdimage/addshapelayer/)() | 添加空的形状图层。没有路径。它们应在保存前添加到形状图层。 |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | 添加一个新的文本图层。 |
| [AddThresholdAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/)() | 添加阈值调整图层。 |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | 添加活力调整图层。 |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | 调整图像的亮度。 |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | 图像对比度 |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | 图像的伽马校正。 |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | 图像的伽马校正。 |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | 使用 Bradley 的自适应阈值算法和积分图阈值对图像进行二值化 |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | 使用 Bradley 的自适应阈值算法和积分图阈值对图像进行二值化 |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | 使用预定义阈值对图像进行二值化 |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | 使用 Otsu 阈值法对图像进行二值化 |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | 缓存数据并确保不会从底层 [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) 再次加载额外数据。 |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 确定图像是否可以使用传入的保存选项保存为指定的文件格式。 |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | 将此图像格式转换为选项中指定的格式。 |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | 裁剪图像。 |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | 带位移裁剪图像。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 释放当前实例。 |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | 对当前图像执行抖动处理。 |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | 对当前图像执行抖动处理。 |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | 过滤指定的矩形区域。 |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | 合并所有图层。 |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | 获取图像的 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | 获取默认选项。 |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 获取默认原始数据数组。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认原始数据数组。 |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | 获取资源图像的最后修改日期和时间。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 根据原始文件设置获取选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们以每像素 1 位加载黑白 PNG 图像，然后使用 [`Save`](../../aspose.psd/datastreamsupporter/save/) 方法保存，输出的 PNG 图像将是每像素 8 位。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](../../aspose.psd/image/save/) 方法。 |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | 获取图像像素。性能警告：避免使用此方法遍历所有图像像素，因为这可能导致显著的性能问题。为了更高效的像素操作，请使用 `LoadArgb32Pixels` 方法一次性检索整个像素数组。 |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | 获取倾斜角度。此方法适用于扫描的文本文档，用于确定扫描时的倾斜角度。 |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | 将图像转换为灰度表示 |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 加载 32 位 ARGB 像素。 |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 加载 64 位 ARGB 像素。 |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | 加载 CMYK 格式的像素。 |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | 加载 CMYK 格式的像素。此方法已弃用。请使用更高效的 [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/) 方法。 |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 按包部分加载 32 位 ARGB 像素。 |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | 按包部分加载像素。 |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | 加载像素。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | 合并图层。 |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | 标准化角度。此方法适用于扫描的文本文档，以消除倾斜扫描。此方法使用 [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) 和 [`Rotate`](../../aspose.psd/rasterimage/rotate/) 方法。 |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | 标准化角度。此方法适用于扫描的文本文档，以消除倾斜扫描。此方法使用 [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) 和 [`Rotate`](../../aspose.psd/rasterimage/rotate/) 方法。 |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | 按指定的扫描线索引读取整条扫描线。 |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | 按指定的扫描线索引读取整条扫描线。 |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它会将所有颜色替换为单一颜色。 |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它会将所有颜色替换为单一颜色。 |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 调整图像大小。使用默认的 NearestNeighbourResample。 |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | 调整图像大小。 |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 按比例调整高度。 |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | 按比例调整高度。 |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | 按比例调整宽度。 |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | 按比例调整宽度。 |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | 围绕中心旋转图像。 |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | 围绕中心旋转图像。 |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | 旋转、翻转或旋转并翻转图像。 |
| [Save](../../aspose.psd/image/save/)() | 将图像数据保存到底层流。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 保存 32 位 ARGB 像素。 |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | 保存像素。 |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | 保存像素。此方法已弃用。请使用更有效的 [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/) 方法。 |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | 保存像素。 |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | 保存原始数据。 |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | 为指定位置设置图像的 32 位 ARGB 像素。 |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | 为指定位置设置图像像素。 |
| override [SetResolution](../../aspose.psd.fileformats.psd/psdimage/setresolution/)(double, double) | 设置此 `PsdImage` 的分辨率。 |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | 将光栅图像转换为位图。 |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | 将整条扫描线写入指定的扫描线索引。 |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | 将整条扫描线写入指定的扫描线索引。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | 默认的 PSD 版本。 |

## 示例

以下代码演示了按特定角度值旋转图像的功能。

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// 整个图像旋转
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

### 另请参阅

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


