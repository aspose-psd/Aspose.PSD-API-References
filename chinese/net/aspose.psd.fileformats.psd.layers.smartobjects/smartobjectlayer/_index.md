---
title: SmartObjectLayer
second_title: Aspose.PSD for .NET API 参考
description: 定义包含嵌入 PSD 文件或外部文件中链接的智能对象的 SmartObjectLayer 类 使用智能对象您可以 执行无损转换您可以缩放旋转倾斜扭曲透视变换或扭曲图层 而不会丢失原始图像数据或质量因为这些变换不会影响原始数据 使用矢量数据例如来自 Illustrator 的矢量图否则会被光栅化 执行无损过滤您可以随时编辑应用于智能对象的过滤器 编辑一个智能对象并自动更新其所有链接实例 应用链接或未链接到智能对象图层的图层蒙版 尝试使用低分辨率占位符图像的各种设计然后用最终版本替换它们 在 Adobe Photoshop 中您可以将图像的内容嵌入到 PSD 文档中 更多信息在这里ltsee hrefhttps//helpx.adobe.com/photoshop/using/create-smart-objects.html /gt 具有嵌入式智能的层对象包含具有智能对象属性的已放置 PlLd 和 SoLd 资源 PlLd 资源对于早于 10 的 PSD 版本可以单独使用 这些资源包含全局 Lnk2Resource 中 LiFdDataSource 的 UniqueId具有嵌入的文件名 和其他参数包括嵌入的原始格式的文件内容作为字节数组
type: docs
weight: 3380
url: /zh/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---
## SmartObjectLayer class

定义包含嵌入 PSD 文件或外部文件中链接的智能对象的 SmartObjectLayer 类。 使用智能对象，您可以： 执行无损转换。您可以缩放、旋转、倾斜、扭曲、透视变换或扭曲图层 ，而不会丢失原始图像数据或质量，因为这些变换不会影响原始数据。 使用矢量数据，例如来自 Illustrator 的矢量图，否则会被光栅化。 执行无损过滤。您可以随时编辑应用于智能对象的过滤器。 编辑一个智能对象并自动更新其所有链接实例。 应用链接或未链接到智能对象图层的图层蒙版。 尝试使用低分辨率占位符图像的各种设计，然后用最终版本替换它们。 在 Adobe® Photoshop® 中，您可以将图像的内容嵌入到 PSD 文档中。 更多信息在这里：&lt;see href="https://helpx.adobe.com/photoshop/using/create-smart-objects.html" /&gt; 具有嵌入式智能的层对象包含具有智能对象属性的已放置 (PlLd) 和 SoLd 资源。 PlLd 资源对于早于 10 的 PSD 版本可以单独使用。 这些资源包含全局 Lnk2Resource 中 LiFdDataSource 的 UniqueId，具有嵌入的文件名 和其他参数，包括嵌入的原始格式的文件内容作为字节数组。

```csharp
public class SmartObjectLayer : Layer
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette) { get; set; } | 获取或设置是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel) { get; } | 获取每像素的图像位数。 |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions) { get; } | 获取混合选项。 |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey) { get; set; } | 获取或设置混合模式键。 |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature) { get; } | 获取混合模式签名。 |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom) { get; set; } | 获取或设置底层位置。 |
| [Bounds](../../aspose.psd/image/bounds) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation) { get; set; } | 获取或设置频道信息。 |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount) { get; } | 获取层的通道数。 |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping) { get; set; } | 获取或设置图层剪辑。 0 = 基础，1 = 非基础。 |
| [Container](../../aspose.psd/image/container) { get; } | 获取[`Image`](../../aspose.psd/image)容器。 |
| [Contents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents) { get; set; } | 获取或设置智能对象层内容。 嵌入的智能对象内容是嵌入的原始图像文件：[`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data)及其属性。 链接的智能对象内容是链接图像文件的原始内容（如果可用）及其属性：[`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource)。 当[`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink)为真时，我们不支持从 Adobe�Photoshop���图形库加载。 对于常规的链接文件，我们首先使用[`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath)来查找相对于 的文件源图像路径SourceImagePath, 如果它不可用，我们查看[`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath), 如果没有，那么我们在图像所在的同一目录中查找链接文件：SourceImagePath。 |
| [ContentsBounds](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentsbounds) { get; set; } | 获取或设置智能对象内容的边界。 |
| [ContentsSource](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentssource) { get; set; } | 获取或设置智能对象内容的来源。 |
| [ContentType](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contenttype) { get; } | 获取智能对象图层内容的类型。 嵌入的智能对象内容是嵌入的原始图像文件：[`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data)。 链接的智能对象内容是链接图像文件的原始内容（如果可用）：[`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource)。 当[`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink)为真时，我们不支持从 Adobe�Photoshop���图形库加载。 对于常规的链接文件，我们首先使用[`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath)来查找相对于 的文件源图像路径SourceImagePath, 如果它不可用，我们查看[`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath), 如果没有，那么我们在图像所在的同一目录中查找链接文件：SourceImagePath。 |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer) { get; } | 获取对象的数据流。 |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname) { get; set; } | 获取或设置图层的显示名称。 |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | 获取一个值，该值指示该实例是否被释放。 |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength) { get; } | 获取层额外信息长度（以字节为单位）。 |
| virtual [FileFormat](../../aspose.psd/image/fileformat) { get; } | 获取文件格式的值 |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler) { get; set; } | 获取或设置图层填充。 |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity) { get; set; } | 获取或设置填充不透明度。 |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags) { get; set; } | 获取或设置图层标志。 位 0 = 透明保护； 位 1 = 可见； 位 2 = 已过时； 位 3 = 1 对于 Photoshop 5.0 及更高版本，表示位 4 是否有有用信息； 位 4 = 与文档外观无关的像素数据。 |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha) { get; } | 获取一个值，该值指示此实例是否具有 alpha。 |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor) { get; set; } | 获取或设置一个值，该值指示图像是否具有背景色。 |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor) { get; set; } | 获取图像是否具有透明色的值。 |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height) { get; } | 获取图像高度。 |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution) { get; set; } | 获取或设置此[`RasterImage`](../../aspose.psd/rasterimage)的水平分辨率，以每英寸像素为单位。 |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity) { get; } | 获取此图像的不透明度。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached) { get; } | 获取当前是否缓存图像数据的值。 |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable) { get; } | 获取一个值，该值指示是否可以加载原始数据。 |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible) { get; set; } | 获取或设置图层是否可见的值 |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup) { get; } | 获取一个值，指示此实例在组中是否可见（如果图层不在组中，则表示根组）。 |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata) { get; set; } | 获取或设置图层混合范围数据。 |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime) { get; set; } | 获取或设置图层创建日期时间。 |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock) { get; set; } | 获取或设置图层锁定。 请注意，如果设置了标志 LayerFlags.TransparencyProtected，它将被层锁定标志覆盖。 要返回LayerFlags.TransparencyProtected标志需要申请层选项layer.Flags &#x7C;= LayerFlags.TransparencyProtected |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata) { get; set; } | 获取或设置图层蒙版数据。 |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions) { get; } | 获取图层选项。 |
| [Left](../../aspose.psd.fileformats.psd.layers/layer/left) { get; set; } | 获取或设置左侧图层位置。 |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length) { get; } | 获取总层长度（以字节为单位）。 |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name) { get; set; } | 获取或设置图层名称。 |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity) { get; set; } | 获取或设置图层不透明度。 0 = 透明，255 = 不透明。 |
| [Palette](../../aspose.psd/image/palette) { get; set; } | 获取或设置调色板。直接表示像素时不使用调色板。 |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents) { get; set; } | 获取或设置一个值，该值指示是否必须对图像分量进行预乘。 |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter) { get; set; } | 获取或设置自定义颜色转换器 |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat) { get; } | 获取原始数据格式。 |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings) { get; } | 获取当前的原始数据设置。请注意，使用这些设置时，数据加载时无需转换。 |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex) { get; set; } | 获取或设置调色板索引超出范围时使用的后备索引 |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter) { get; set; } | 获取或设置索引颜色转换器 |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize) { get; } | 获取原始行大小（以字节为单位）。 |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources) { get; set; } | 获取或设置图层资源。 |
| [Right](../../aspose.psd.fileformats.psd.layers/layer/right) { get; set; } | 获取或设置正确的图层位置。 |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight) { get; set; } | 获取或设置图层列表中的装饰板颜色高亮 |
| [Size](../../aspose.psd/image/size) { get; } | 获取图像大小。 |
| [SmartFilters](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartfilters) { get; } | 获取智能过滤器。 |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartobjectprovider) { get; } | 获取智能对象提供者。 |
| [Top](../../aspose.psd.fileformats.psd.layers/layer/top) { get; set; } | 获取或设置顶层位置。 |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor) { get; set; } | 获取图像透明色。 |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata) { get; set; } | 获取或设置是否更新 XMP 元数据的值。 |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata) { get; set; } | 获取或设置一个值，该值指示当原始数据加载可用时是否使用原始数据加载。 |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution) { get; set; } | 获取或设置此[`RasterImage`](../../aspose.psd/rasterimage)的垂直分辨率，以每英寸像素为单位。 |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width) { get; } | 获取图像宽度。 |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata) { get; set; } | 获取或设置 XMP 元数据。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask)(LayerMaskData) | 将蒙版添加到当前图层。 |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness)(int) | 调整图像的亮度。 |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast)(float) | 图像对比度 |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma)(float) | 图像的伽玛校正。 |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma)(float, float, float) | 图像的伽玛校正。 |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley)(double) | 使用 Bradley 自适应阈值算法对图像进行二值化，使用积分图像阈值 |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley)(double, int) | 使用 Bradley 自适应阈值算法对图像进行二值化，使用积分图像阈值 |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed)(byte) | 具有预定义阈值的图像的二值化 |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu)() | 使用 Otsu 阈值对图像进行二值化 |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata)() | 缓存数据并确保不会从底层[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer)执行额外的数据加载。 |
| [CanSave](../../aspose.psd/image/cansave)(ImageOptionsBase) | 确定图像是否可以保存为传递的保存选项表示的指定文件格式。 |
| [ConvertToLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/converttolinked)(string) | 将此嵌入的智能对象转换为链接的智能对象。 |
| override [Crop](../../aspose.psd/rastercachedimage/crop)(Rectangle) | 裁剪图像。 |
| virtual [Crop](../../aspose.psd/rasterimage/crop)(int, int, int, int) | 带班次裁剪图像。 |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | 释放当前实例。 |
| [Dither](../../aspose.psd/rasterimage/dither)(DitheringMethod, int) | 对当前图像执行抖动。 |
| override [Dither](../../aspose.psd/rastercachedimage/dither)(DitheringMethod, int, IColorPalette) | 对当前图像执行抖动。 |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage)(Point, RasterImage) | 在图层上绘制图像。 |
| [DuplicateLayer](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer)() | 通过应对这一层来创建一个新的智能对象层。 请注意，对于嵌入的智能对象，嵌入的图像是共享的。 如果要复制嵌入的图像，请使用[`NewSmartObjectViaCopy`](./newsmartobjectviacopy)方法。 |
| [EmbedLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/embedlinked)() | 在此层中嵌入链接的智能对象。 |
| [ExportContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/exportcontents)(string) | 将嵌入或链接的内容导出到文件。 |
| virtual [Filter](../../aspose.psd/rasterimage/filter)(Rectangle, FilterOptionsBase) | 过滤指定的矩形。 |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel)(int, int) | 获取图像 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions)(object[]) | 获取默认选项。 |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | 获取默认的原始数据数组。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认的原始数据数组。 |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode)() | 返回此实例的哈希码。 |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate)(bool) | 获取上次修改资源图像的日期和时间。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions)() | 获取基于原始文件设置的选项。 这有助于保持原始图像的位深度和其他参数不变。 例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../../aspose.psd/datastreamsupporter/save)方法，将生成每像素 8 位的输出 PNG 图像。 为了避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项并将它们 传递给[`Save`](../../aspose.psd/image/save)方法作为第二个参数。 |
| [GetPixel](../../aspose.psd/rasterimage/getpixel)(int, int) | 获取图像像素。 |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle)() | 获取倾斜角度。 此方法适用于扫描的文本文档，用于确定扫描时的倾斜角度。 |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale)() | 将图像转换为其灰度表示 |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels)(Rectangle) | 加载 32 位 ARGB 像素。 |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels)(Rectangle) | 加载 64 位 ARGB 像素。 |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels)(Rectangle) | 以 CMYK 格式加载像素。 |
| [LoadContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/loadcontents)(LoadOptions) | 获取智能对象图层的嵌入或链接图像内容。 |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | 部分按包加载 32 位 ARGB 像素。 |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | 部分按包加载像素。 |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels)(Rectangle) | 加载像素。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto)(Layer) | 将图层合并到指定图层 |
| [NewSmartObjectViaCopy](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy)() | 通过应对这一层来创建一个新的智能对象层。 再现`图层-&gt;智能对象 -&gt;通过 Adobe® Photoshop® 的复制功能创建新的智能对象。 请注意，它仅对嵌入的智能对象启用，因为嵌入的图像也会被复制。 如果要共享嵌入的图像，请使用[`DuplicateLayer`](./duplicatelayer)方法。 |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle)() | 标准化角度。 此方法适用于扫描的文本文档，以消除倾斜扫描。 此方法使用[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle)和[`Rotate`](../../aspose.psd/rasterimage/rotate)方法。 |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle)(bool, Color) | 标准化角度。 此方法适用于扫描的文本文档，以消除倾斜扫描。 此方法使用[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle)和PSD。颜色）方法。 |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline)(int) | 按指定的扫描线索引读取整个扫描线。 |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline)(int) | 按指定的扫描线索引读取整个扫描线。 |
| [RelinkToFile](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/relinktofile)(string) | 将链接的智能对象重新链接到新文件。 之后不需要调用UpdateModifiedContent 方法。 |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor)(Color, byte, Color) | 用允许的差异将一种颜色替换为另一种颜色，并保留原始 Alpha 值以保存平滑边缘。 |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor)(int, byte, int) | 用允许的差异将一种颜色替换为另一种颜色，并保留原始 Alpha 值以保存平滑边缘。 |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents#replacecontents)(Image) | 替换嵌入在智能对象层中的智能对象内容。 |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents#replacecontents_2)(string) | 将内容替换为文件。 之后不需要调用UpdateModifiedContent 方法。 |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents#replacecontents_1)(Image, ResolutionSetting) | 替换嵌入在智能对象层中的智能对象内容。 |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents#replacecontents_3)(string, ResolutionSetting) | 将内容替换为文件。 之后不需要调用UpdateModifiedContent 方法。 |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors)(Color) | 用新颜色替换所有非透明颜色并保留原始 alpha 值以保存平滑边缘。 注意：如果您在没有透明度的图像上使用它，所有颜色都将替换为一种颜色。 |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors)(int) | 用新颜色替换所有非透明颜色并保留原始 alpha 值以保存平滑边缘。 注意：如果您在没有透明度的图像上使用它，所有颜色都将替换为一种颜色。 |
| [Resize](../../aspose.psd/image/resize)(int, int) | 调整图像大小。使用默认的LeftTopToLeftTop。 |
| override [Resize](../../aspose.psd/rastercachedimage/resize)(int, int, ImageResizeSettings) | 调整图像大小。 |
| override [Resize](../../aspose.psd/rastercachedimage/resize)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int, ResizeType) | 按比例调整宽度。 |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate)(float) | 围绕中心旋转图像。 |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate)(float, bool, Color) | 围绕中心旋转图像。 |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip)(RotateFlipType) | 旋转、翻转或旋转和翻转图像。 |
| [Save](../../aspose.psd/image/save)() | 将图像数据保存到底层流。 |
| [Save](../../aspose.psd/datastreamsupporter/save)(Stream) | 将对象的数据保存到指定的流中。 |
| [Save](../../aspose.psd/datastreamsupporter/save)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.psd/image/save)(Stream, ImageOptionsBase) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save)(string, ImageOptionsBase) | 根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save)(string, ImageOptionsBase, Rectangle) | 根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。 |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels)(Rectangle, int[]) | 保存 32 位 ARGB 像素。 |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels)(Rectangle, int[]) | 保存像素。 |
| [SavePixels](../../aspose.psd/rasterimage/savepixels)(Rectangle, Color[]) | 保存像素。 |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | 保存原始数据。 |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel)(int, int, int) | 为指定位置设置图像 32 位 ARGB 像素。 |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette)(IColorPalette, bool) | 设置图像调色板。 |
| [SetPixel](../../aspose.psd/rasterimage/setpixel)(int, int, Color) | 为指定位置设置图像像素。 |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution)(double, double) | 设置此[`RasterImage`](../../aspose.psd/rasterimage)的分辨率。 |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy)() | 创建当前层的浅表副本。 请&lt;see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /&gt; 解释。 |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap)() | 将光栅图像转换为位图。 |
| [UpdateModifiedContent](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/updatemodifiedcontent)() | 使用修改后的内容更新智能对象层图像缓存。 |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline)(int, int[]) | 将整个扫描线写入指定的扫描线索引。 |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline)(int, Color[]) | 将整个扫描线写入指定的扫描线索引。 |

### 例子

以下代码演示了对嵌入式智能对象的支持。

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// 此示例演示如何更改 PSD 文件中的智能对象图层并导出/更新智能对象原始嵌入内容。
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // 让我们从 PSD 智能对象层导出嵌入的智能对象图像
        smartObjectLayer.ExportContents(exportPath);

        // 让我们检查原始图像是否正确保存
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // 让我们反转原始智能对象图像
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // 让我们替换 PSD 层中嵌入的智能对象图像
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // 让我们检查更新的图像是否正确保存
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 也可以看看

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer)
* class [SmartObjectProvider](../../aspose.psd.fileformats.psd/smartobjectprovider)
* class [LinkDataSource](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../aspose.psd.fileformats.psd.layers.smartobjects)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
