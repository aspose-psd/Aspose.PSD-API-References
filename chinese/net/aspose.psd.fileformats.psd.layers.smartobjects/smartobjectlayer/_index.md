---
title: "类 SmartObjectLayer"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartObjects.SmartObjectLayer 类。定义了 SmartObjectLayer 类，该类包含嵌入在 PSD 文件中的或外部文件中链接的智能对象。使用智能对象，您可以执行非破坏性变换。您可以缩放、旋转、倾斜、扭曲、透视变换或扭曲图层，而不会丢失原始图像数据或质量，因为这些变换不会影响原始数据。可以处理矢量数据，例如来自 Illustrator 的矢量艺术作品，否则会被光栅化。执行非破坏性过滤。您可以随时编辑应用于智能对象的滤镜。编辑一个智能对象即可自动更新所有链接的实例。对智能对象图层应用链接或未链接的图层蒙版。使用低分辨率占位图像尝试各种设计，随后再替换为最终版本。在 Adobe Photoshop 中，您可以将图像内容嵌入到 PSD 文档中。更多信息请访问 https//helpx.adobe.com/photoshop/using/createsmartobjects.html。一个包含嵌入智能对象的图层包含放置的 PlLd 和 SoLd 资源以及智能对象属性。对于 PSD 10 之前的版本，PlLd 资源可以单独存在。这些资源在全局 Lnk2Resource 中包含 LiFdDataSource 的 UniqueId、嵌入的文件名以及其他参数，包括以字节数组形式的原始格式嵌入文件内容。"
type: docs
weight: 3910
url: /zh/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---
{{< psd/tize >}}
## SmartObjectLayer class

定义了 SmartObjectLayer 类，该类包含嵌入在 PSD 文件中的或外部文件中链接的智能对象。使用智能对象，您可以：执行非破坏性变换。您可以缩放、旋转、倾斜、扭曲、透视变换或扭曲图层，而不会丢失原始图像数据或质量，因为这些变换不会影响原始数据。处理向量数据，例如来自 Illustrator 的向量艺术作品，否则会被光栅化。执行非破坏性过滤。您可以随时编辑应用于智能对象的滤镜。编辑一个智能对象并自动更新其所有链接实例。应用与智能对象图层链接或未链接的图层蒙版。使用低分辨率占位图尝试各种设计，随后再替换为最终版本。在 Adobe Photoshop 中，您可以将图像内容嵌入到 PSD 文档中。更多信息请参阅此处：[https://helpx.adobe.com/photoshop/using/create-smart-objects.html](https://helpx.adobe.com/photoshop/using/create-smart-objects.html) 包含嵌入智能对象的图层包含 placed (PlLd) 和 SoLd 资源以及智能对象属性。对于 PSD 版本早于 10 的情况，PlLd 资源可以单独存在。这些资源在全局 Lnk2Resource 中包含 LiFdDataSource 的 UniqueId、嵌入的文件名以及其他参数，包括以字节数组形式的原始格式嵌入文件内容。

```csharp
public class SmartObjectLayer : Layer
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SmartObjectLayer](smartobjectlayer/)(Stream) | 初始化 `SmartObjectLayer` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 获取或设置一个值，指示是否自动调整调色板。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | 获取图像每像素位数的计数。 |
| [BlendClippedElements](../../aspose.psd.fileformats.psd.layers/layer/blendclippedelements/) { get; set; } | 获取或设置裁剪元素的混合方式。 |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | 获取混合选项。 |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | 获取或设置混合模式键。 |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | 获取混合模式签名。 |
| virtual [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | 获取或设置底层位置。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | 获取或设置信道信息。 |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | 获取图层的通道计数。 |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | 获取或设置图层裁剪。0 = 基础，1 = 非基础。 |
| [Container](../../aspose.psd/image/container/) { get; } | 获取 [`Image`](../../aspose.psd/image/) 容器。 |
| [Contents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/) { get; set; } | 获取或设置智能对象图层内容。嵌入的智能对象内容是嵌入的原始图像文件：[`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) 及其属性。链接的智能对象内容是已可用的链接图像文件的原始内容及其属性：[`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/)。当 [`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) 为 true 时，我们不支持从 Adobe® Photoshop®™ 图形库加载。对于常规链接文件，首先我们使用 [`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) 相对于源图像路径 SourceImagePath 查找文件，如果不可用则查看 [`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/)，如果仍未找到，则在我们的图像所在的同一目录（SourceImagePath）中查找链接文件。 |
| [ContentsBounds](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentsbounds/) { get; set; } | 获取或设置智能对象内容的边界。 |
| [ContentsSource](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentssource/) { get; set; } | 获取或设置智能对象内容的来源。 |
| [ContentType](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contenttype/) { get; } | 获取智能对象图层内容的类型。嵌入的智能对象内容是嵌入的原始图像文件：[`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/)。链接的智能对象内容是已可用的链接图像文件的原始内容：[`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/)。当 [`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) 为 true 时，我们不支持从 Adobe® Photoshop®™ 图形库加载。对于常规链接文件，首先我们使用 [`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) 相对于源图像路径 SourceImagePath 查找文件，如果不可用则查看 [`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/)，如果仍未找到，则在我们的图像所在的同一目录（SourceImagePath）中查找链接文件。 |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | 获取或设置图层的显示名称。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | 获取图层额外信息的字节长度。 |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | 获取文件格式的值 |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | 获取或设置图层填充器。 |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | 获取或设置填充不透明度。 |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | 获取或设置图层标志。位 0 = 透明受保护；位 1 = 可见；位 2 = 已废弃；位 3 = 对 Photoshop 5.0 及更高版本为 1，指示位 4 是否包含有用信息；位 4 = 像素数据与文档外观无关。 |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | 获取一个值，指示此实例是否具有 alpha 通道。 |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 获取或设置一个值，指示图像是否具有背景颜色。 |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | 获取一个值，指示图像是否具有透明颜色。 |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | 获取图像高度。 |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | 获取或设置此 [`RasterImage`](../../aspose.psd/rasterimage/) 的水平分辨率，单位为每英寸像素数。 |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | 获取此图像的不透明度。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | 获取一个值，指示图像数据当前是否已缓存。 |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | 获取一个值，指示是否可以加载原始数据。 |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | 获取或设置一个值，指示图层是否可见 |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | 获取一个值，指示此实例在组中是否可见（如果图层不在组中，则表示根组）。 |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | 获取或设置图层混合范围数据。 |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | 获取或设置图层创建日期时间。 |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | 获取或设置图层锁定。注意，如果设置了标志 LayerFlags.TransparencyProtected，它将被图层锁定标志覆盖。要返回 LayerFlags.TransparencyProtected 标志，需要对图层选项使用 layer.Flags &#x7C;= LayerFlags.TransparencyProtected |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | 获取或设置图层蒙版数据。 |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | 获取图层选项。 |
| virtual [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | 获取或设置左侧图层位置。 |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | 获取图层的整体长度（字节）。 |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | 获取或设置图层名称。 |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | 获取或设置图层不透明度。0 = 透明，255 = 不透明。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，不使用颜色调色板。 |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | 获取或设置一个值，指示图像组件是否必须预乘。 |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | 获取或设置自定义颜色转换器 |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | 获取原始数据格式。 |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | 获取当前原始数据设置。注意，在使用这些设置时，数据会在不进行转换的情况下加载。 |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | 获取或设置当调色板索引超出范围时使用的回退索引 |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | 获取或设置索引颜色转换器 |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | 获取原始行大小（字节）。 |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | 获取或设置图层资源。 |
| virtual [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | 获取或设置右侧图层位置。 |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | 获取或设置图层列表中装饰纸张颜色高亮 |
| [Size](../../aspose.psd/image/size/) { get; } | 获取图像尺寸。 |
| [SmartFilters](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartfilters/) { get; } | 获取智能过滤器。 |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartobjectprovider/) { get; } | 获取智能对象提供程序。 |
| virtual [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | 获取或设置顶部图层位置。 |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | 获取图像透明颜色。 |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | 获取或设置指示是否更新 XMP 元数据的值。 |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | 获取指示是否使用图像调色板的值。 |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | 获取或设置指示在可用原始数据加载时是否使用原始数据加载的值。 |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | 获取或设置此 [`RasterImage`](../../aspose.psd/rasterimage/) 的垂直分辨率（每英寸像素数）。 |
| [WarpSettings](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/warpsettings/) { get; set; } | 获取或设置从资源中设置或获取的 Warp 参数（默认） |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | 获取图像宽度。 |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | 获取或设置 XMP 元数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | 将遮罩添加到当前图层。 |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | 调整图像的亮度。 |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | 图像对比度 |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | 图像的伽马校正。 |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | 图像的伽马校正。 |
| [ApplyLayerMask](../../aspose.psd.fileformats.psd.layers/layer/applylayermask/)() | 将图层遮罩应用到图层，然后删除遮罩。 |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | 使用 Bradley 的自适应阈值算法和积分图阈值对图像进行二值化 |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | 使用 Bradley 的自适应阈值算法和积分图阈值对图像进行二值化 |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | 使用预定义阈值对图像进行二值化 |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | 使用 Otsu 阈值法对图像进行二值化 |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | 缓存数据并确保不会从底层 [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) 再次加载额外数据。 |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 确定图像是否可以使用传入的保存选项保存为指定的文件格式。 |
| [ConvertToLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/converttolinked/)(string) | 将此嵌入的智能对象转换为链接的智能对象。 |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | 裁剪图像。 |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | 带位移裁剪图像。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 释放当前实例。 |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | 对当前图像执行抖动处理。 |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | 对当前图像执行抖动处理。 |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | 在图层上绘制图像。 |
| [DuplicateLayer](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/)() | 通过复制此对象创建一个新的智能对象图层。请注意，对于嵌入的智能对象，嵌入的图像是共享的。如果想复制嵌入的图像，请使用 [`NewSmartObjectViaCopy`](./newsmartobjectviacopy/) 方法。 |
| [EmbedLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/embedlinked/)() | 在此图层中嵌入链接的智能对象。 |
| [ExportContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/exportcontents/)(string) | 将嵌入的或链接的内容导出到文件。 |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | 过滤指定的矩形区域。 |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | 获取图像的 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | 获取默认选项。 |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 获取默认原始数据数组。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认原始数据数组。 |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | 返回此实例的哈希码。 |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | 获取资源图像的最后修改日期和时间。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 根据原始文件设置获取选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们以每像素 1 位加载黑白 PNG 图像，然后使用 [`Save`](../../aspose.psd/datastreamsupporter/save/) 方法保存，输出的 PNG 图像将是每像素 8 位。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](../../aspose.psd/image/save/) 方法。 |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | 获取图像像素。性能警告：避免使用此方法遍历所有图像像素，因为这可能导致显著的性能问题。为了更高效的像素操作，请使用 `LoadArgb32Pixels` 方法一次性检索整个像素数组。 |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | 获取倾斜角度。此方法适用于扫描的文本文档，用于确定扫描时的倾斜角度。 |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | 将图像转换为灰度表示 |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 加载 32 位 ARGB 像素。 |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 加载 64 位 ARGB 像素。 |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | 加载 CMYK 格式的像素。 |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | 加载 CMYK 格式的像素。此方法已弃用。请使用更高效的 [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/) 方法。 |
| [LoadContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/loadcontents/)(LoadOptions) | 获取智能对象图层的嵌入或链接图像内容。 |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 按包部分加载 32 位 ARGB 像素。 |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | 按包部分加载像素。 |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | 加载像素。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto/)(Layer) | 将图层合并到指定图层 |
| [NewSmartObjectViaCopy](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/)() | 通过复制此图层创建一个新的智能对象图层。重现 Adobe� Photoshop� 中 `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` 功能。请注意，仅对嵌入的智能对象启用此功能，因为嵌入的图像也会被复制。如果想共享嵌入的图像，请使用 [`DuplicateLayer`](./duplicatelayer/) 方法。 |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | 标准化角度。此方法适用于扫描的文本文档，以消除倾斜扫描。此方法使用 [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) 和 [`Rotate`](../../aspose.psd/rasterimage/rotate/) 方法。 |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | 标准化角度。此方法适用于扫描的文本文档，以消除倾斜扫描。此方法使用 [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) 和 [`Rotate`](../../aspose.psd/rasterimage/rotate/) 方法。 |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | 按指定的扫描线索引读取整条扫描线。 |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | 按指定的扫描线索引读取整条扫描线。 |
| [RelinkToFile](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/relinktofile/)(string) | 将已链接的智能对象重新链接到新文件。之后无需调用 UpdateModifiedContent 方法。 |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents)(Image) | 替换嵌入在智能对象图层中的智能对象内容。 |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_2)(string) | 使用文件替换内容。之后无需调用 UpdateModifiedContent 方法。 |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_1)(Image, ResolutionSetting) | 替换嵌入在智能对象图层中的智能对象内容。 |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_5)(string, bool) | 使用文件替换内容。之后无需调用 UpdateModifiedContent 方法。 |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_3)(string, ResolutionSetting) | 使用文件替换内容。之后无需调用 UpdateModifiedContent 方法。 |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_4)(string, ResolutionSetting, bool) | 使用文件替换内容。之后无需调用 UpdateModifiedContent 方法。 |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它会将所有颜色替换为单一颜色。 |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它会将所有颜色替换为单一颜色。 |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 调整图像大小。使用默认的 NearestNeighbourResample。 |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | 调整图像大小。 |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | 按比例调整宽度。 |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | 围绕中心旋转图像。 |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | 围绕中心旋转图像。 |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | 旋转、翻转或旋转并翻转图像。 |
| [Save](../../aspose.psd/image/save/)() | 将图像数据保存到底层流。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | 将对象的数据保存到指定的流。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 保存 32 位 ARGB 像素。 |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | 保存像素。 |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | 保存像素。此方法已弃用。请使用更有效的 [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/) 方法。 |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | 保存像素。 |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | 保存原始数据。 |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | 为指定位置设置图像的 32 位 ARGB 像素。 |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | 为指定位置设置图像像素。 |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | 为此 [`RasterImage`](../../aspose.psd/rasterimage/) 设置分辨率。 |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | 创建当前图层的浅拷贝。请参阅 [https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) 了解说明。 |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | 将光栅图像转换为位图。 |
| [UpdateModifiedContent](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/updatemodifiedcontent/)() | 使用修改后的内容更新智能对象图层的图像缓存。 |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | 将整条扫描线写入指定的扫描线索引。 |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | 将整条扫描线写入指定的扫描线索引。 |

## 示例

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

// 此示例演示了如何更改 PSD 文件中的智能对象图层并导出/更新智能对象的原始嵌入内容。
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

        // 让我们从 PSD 智能对象图层导出嵌入的智能对象图像
        smartObjectLayer.ExportContents(exportPath);

        // 让我们检查原始图像是否已正确保存
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

            // 让我们替换 PSD 图层中的嵌入智能对象图像
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // 让我们检查更新后的图像是否已正确保存
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 另请参阅

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* class [SmartObjectProvider](../../aspose.psd.fileformats.psd/smartobjectprovider/)
* class [LinkDataSource](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../)


