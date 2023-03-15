---
title: Class LayerGroup
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerGroup 班级. 组图层类
type: docs
weight: 2220
url: /zh/net/aspose.psd.fileformats.psd.layers/layergroup/
---
## LayerGroup class

组图层类

```csharp
public class LayerGroup : Layer
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 获取或设置一个值，指示是否自动调整调色板。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | 获取每像素计数的图像位数。 |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | 获取混合选项。 |
| override [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layergroup/blendmodekey/) { get; set; } | 获取或设置混合模式键。 |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | 获取混合模式签名。 |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | 获取或设置底层位置。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，它是为所有内部缓冲区定义的最大允许大小。 |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | 获取或设置频道信息。 |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | 获取层的通道数。 |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | 获取或设置图层裁剪。 0 = 基础，1 = 非基础. |
| [Container](../../aspose.psd/image/container/) { get; } | 获取[`Image`](../../aspose.psd/image/)容器. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | 获取或设置图层的显示名称。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | 获取以字节为单位的层额外信息长度。 |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | 获取文件格式 的值 |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | 获取或设置图层填充。 |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | 获取或设置填充不透明度。 |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | 获取或设置图层标志。 位 0 = 透明保护； 位 1 = 可见； 位 2 = 过时； 位 3 = 1 对于 Photoshop 5.0 及更高版本，指示位 4 是否有有用的信息； 位 4 =与文档外观无关的像素数据. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | 获取一个值，指示此实例是否具有 alpha. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 获取或设置图像是否有背景色的值。 |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | 获取图像是否有透明色的值。 |
| override [Height](../../aspose.psd.fileformats.psd.layers/layergroup/height/) { get; } | 获取图层组的高度。 |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | 获取或设置水平分辨率，以每英寸像素为单位，[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | 获取此图像的不透明度。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | 获取当前是否缓存图像数据的值。 |
| [IsOpen](../../aspose.psd.fileformats.psd.layers/layergroup/isopen/) { get; set; } | 获取或设置文件夹是否打开 如果设置为`真的`组在启动时将处于打开状态，否则处于最小化状态。 |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | 获取原始数据加载是否可用的值。 |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | 获取或设置图层是否可见的值 |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | 获取一个值，指示此实例是否在组中可见（如果图层不在组中，则表示根组）。 |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | 获取或设置图层混合范围数据。 |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | 获取或设置图层创建日期时间。 |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | 获取或设置layer lock. 注意如果设置了flag LayerFlags.TransparencyProtected 将被layer lock flag覆盖。 返回LayerFlags.TransparencyProtected flag需要申请layer option layer.Flags &#x7C;= LayerFlags.TransparencyProtected |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | 获取或设置图层蒙版数据。 |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | 获取图层选项。 |
| [Layers](../../aspose.psd.fileformats.psd.layers/layergroup/layers/) { get; } | 获取图层组 中的图层 |
| [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | 获取或设置左图层位置。 |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | 获取以字节为单位的总层长度。 |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | 获取或设置图层名称。 |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | 获取或设置图层不透明度。 0 = 透明，255 = 不透明。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | 获取或设置调色板。直接表示像素时不使用调色板。 |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | 获取或设置一个值，指示图像分量是否必须预乘。 |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | 获取或设置自定义颜色转换器 |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | 获取原始数据格式。 |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | 获取当前原始数据设置。请注意，使用这些设置时，数据加载时无需转换。 |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | 获取或设置调色板索引超出范围时使用的回退索引 |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | 获取或设置索引颜色转换器 |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | 获取以字节为单位的原始行大小。 |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | 获取或设置图层资源。 |
| [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | 获取或设置正确的图层位置。 |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | 获取或设置图层列表中的装饰板颜色高亮 |
| [Size](../../aspose.psd/image/size/) { get; } | 获取图像大小。 |
| [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | 获取或设置顶层位置。 |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | 获取图像透明色。 |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | 获取或设置当原始数据加载可用时是否使用原始数据加载的值。 |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | 获取或设置垂直分辨率，以每英寸像素为单位，[`RasterImage`](../../aspose.psd/rasterimage/) . |
| override [Width](../../aspose.psd.fileformats.psd.layers/layergroup/width/) { get; } | 获取图层组的宽度。 |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | 获取或设置 XMP 元数据。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.psd.layers/layergroup/addlayer/)(Layer) | 将图层添加到图层组。 |
| [AddLayerGroup](../../aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/)(string, int) | 添加层组。 |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | 将蒙版添加到当前层。 |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | 调整图像的亮度。 |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | 图像对比 |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | 图像的伽马校正。 |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | 图像的伽马校正。 |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | 使用 Bradley 自适应阈值算法对图像进行二值化，使用积分图像阈值 |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | 使用 Bradley 自适应阈值算法对图像进行二值化，使用积分图像阈值 |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | 具有预定义阈值的图像二值化 |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | 使用 Otsu 阈值对图像进行二值化 |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | 缓存数据并确保不会从底层执行额外的数据加载[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传递的保存选项所代表的指定文件格式。 |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | 裁剪图像。 |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | 带位移的裁剪图像。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 处理当前实例。 |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | 对当前图像执行抖动。 |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | 对当前图像执行抖动。 |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | 在图层上绘制图像。 |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | 过滤指定矩形。 |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | 获取图像 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | 获取默认选项。 |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 获取默认原始数据数组。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认原始数据数组。 |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | 返回此实例的哈希码。 |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | 获取上次修改资源图像的日期和时间。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 获取基于原始文件设置的选项。 这有助于保持原始图像的位深度和其他参数不变。 例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 the 保存[`Save`](../../aspose.psd/datastreamsupporter/save/)方法，将生成每像素 8 位的输出 PNG 图像。 要避免它并保存每像素 1 位的 PNG 图像，请使用此方法获取相应的保存选项并将它们 传递给[`Save`](../../aspose.psd/image/save/)方法作为第二个参数. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | 获取图像像素。 |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | 获取倾斜角度。 该方法适用于扫描的文本文档，用于确定扫描时的倾斜角度。 |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | 将图像转换为灰度表示 |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 加载 32 位 ARGB 像素。 |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 加载 64 位 ARGB 像素。 |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | 以 CMYK 格式加载像素。 |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 按包加载部分 32 位 ARGB 像素。 |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | 按包加载部分像素。 |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | 加载像素。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto/)(Layer) | 将图层合并到指定的图层 |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | 归一化角度。 此方法适用于扫描的文本文档，以消除倾斜扫描。 此方法使用[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/)和[`Rotate`](../../aspose.psd/rasterimage/rotate/)方法. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | 归一化角度。 此方法适用于扫描的文本文档，以消除倾斜扫描。 此方法使用[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/)和[`Rotate`](../../aspose.psd/rasterimage/rotate/)方法. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | 按指定扫描线索引读取整条扫描线。 |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | 按指定扫描线索引读取整条扫描线。 |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | 将一种颜色替换为具有允许差异的另一种颜色并保留原始 alpha 值以保存平滑的边缘。 |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | 将一种颜色替换为具有允许差异的另一种颜色并保留原始 alpha 值以保存平滑的边缘。 |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | 用新颜色替换所有非透明颜色并保留原始 alpha 值以保存平滑边缘。 注意：如果您在没有透明度的图像上使用它，所有颜色将被替换为一个颜色。 |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | 用新颜色替换所有非透明颜色并保留原始 alpha 值以保存平滑边缘。 注意：如果您在没有透明度的图像上使用它，所有颜色将被替换为一个颜色。 |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 调整图像大小。默认值LeftTopToLeftTop使用. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | 调整图像大小。 |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | 按比例调整宽度。 |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | 围绕中心旋转图像。 |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | 围绕中心旋转图像。 |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | 旋转、翻转或旋转并翻转图像。 |
| [Save](../../aspose.psd/image/save/)() | 将图像数据保存到底层流中。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | 将对象的数据保存到指定的流中。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 根据保存选项以指定文件格式将图像数据保存到指定流。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | 根据保存选项以指定的文件格式将对象的数据保存到指定的文件位置。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项以指定文件格式将图像数据保存到指定流。 |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | 根据保存选项以指定的文件格式将对象的数据保存到指定的文件位置。 |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 保存 32 位 ARGB 像素。 |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | 保存像素。 |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | 保存像素。 |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | 保存原始数据。 |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | 为指定位置设置图像 32 位 ARGB 像素。 |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | 为指定位置设置图像像素。 |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | 为此设置分辨率[`RasterImage`](../../aspose.psd/rasterimage/) . |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | 创建当前层的浅表副本。 请[https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx)解释. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | 将光栅图像转换为位图。 |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | 将整个扫描线写入指定的扫描线索引。 |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | 将整个扫描线写入指定的扫描线索引。 |

### 例子

以下示例演示了如何更改 Aspose.PSD 中的 LayerGroup 可见性

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// 更改图层名称并保存
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // 关闭组内的所有内容
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### 也可以看看

* class [Layer](../layer/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* 部件 [Aspose.PSD](../../)


