---
title: Class RasterCachedImage
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.RasterCachedImage 班级. 表示支持光栅图形操作的光栅图像此图像在需要时缓存像素数据
type: docs
weight: 5310
url: /zh/net/aspose.psd/rastercachedimage/
---
## RasterCachedImage class

表示支持光栅图形操作的光栅图像。此图像在需要时缓存像素数据。

```csharp
public abstract class RasterCachedImage : RasterImage
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 获取或设置一个值，指示是否自动调整调色板。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | 获取每像素计数的图像位数。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，它是为所有内部缓冲区定义的最大允许大小。 |
| [Container](../../aspose.psd/image/container/) { get; } | 获取[`Image`](../image/)容器. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | 获取文件格式 的值 |
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | 获取一个值，指示此实例是否具有 alpha. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 获取或设置图像是否有背景色的值。 |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | 获取图像是否有透明色的值。 |
| abstract [Height](../../aspose.psd/image/height/) { get; } | 获取图像高度。 |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | 获取或设置水平分辨率，以每英寸像素为单位，[`RasterImage`](../rasterimage/) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | 获取此图像的不透明度。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | 获取当前是否缓存图像数据的值。 |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | 获取原始数据加载是否可用的值。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | 获取或设置调色板。直接表示像素时不使用调色板。 |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | 获取或设置一个值，指示图像分量是否必须预乘。 |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | 获取或设置自定义颜色转换器 |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | 获取原始数据格式。 |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | 获取当前原始数据设置。请注意，使用这些设置时，数据加载时无需转换。 |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | 获取或设置调色板索引超出范围时使用的回退索引 |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | 获取或设置索引颜色转换器 |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | 获取以字节为单位的原始行大小。 |
| [Size](../../aspose.psd/image/size/) { get; } | 获取图像大小。 |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | 获取图像透明色。 |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | 获取或设置当原始数据加载可用时是否使用原始数据加载的值。 |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | 获取或设置垂直分辨率，以每英寸像素为单位，[`RasterImage`](../rasterimage/) . |
| abstract [Width](../../aspose.psd/image/width/) { get; } | 获取图像宽度。 |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | 获取或设置 XMP 元数据。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | 调整图像的亮度。 |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | 图像对比 |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/#adjustgamma)(float) | 图像的伽马校正。 |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/#adjustgamma_1)(float, float, float) | 图像的伽马校正。 |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/#binarizebradley)(double) | 使用 Bradley 自适应阈值算法对图像进行二值化，使用积分图像阈值 |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/#binarizebradley_1)(double, int) | 使用 Bradley 自适应阈值算法对图像进行二值化，使用积分图像阈值 |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | 具有预定义阈值的图像二值化 |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | 使用 Otsu 阈值对图像进行二值化 |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | 缓存数据并确保不会从底层执行额外的数据加载[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传递的保存选项所代表的指定文件格式。 |
| override [Crop](../../aspose.psd/rastercachedimage/crop/#crop)(Rectangle) | 裁剪图像。 |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | 带位移的裁剪图像。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 处理当前实例。 |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | 对当前图像执行抖动。 |
| override [Dither](../../aspose.psd/rastercachedimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | 对当前图像执行抖动。 |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | 过滤指定矩形。 |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | 获取图像 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | 获取默认选项。 |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | 获取默认原始数据数组。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认原始数据数组。 |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | 获取上次修改资源图像的日期和时间。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 获取基于原始文件设置的选项。 这有助于保持原始图像的位深度和其他参数不变。 例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 the 保存[`Save`](../datastreamsupporter/save/)方法，将生成每像素 8 位的输出 PNG 图像。 要避免它并保存每像素 1 位的 PNG 图像，请使用此方法获取相应的保存选项并将它们 传递给[`Save`](../image/save/)方法作为第二个参数. |
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
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | 归一化角度。 此方法适用于扫描的文本文档，以消除倾斜扫描。 此方法使用[`GetSkewAngle`](../rasterimage/getskewangle/)和[`Rotate`](../rasterimage/rotate/)方法. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | 归一化角度。 此方法适用于扫描的文本文档，以消除倾斜扫描。 此方法使用[`GetSkewAngle`](../rasterimage/getskewangle/)和[`Rotate`](../rasterimage/rotate/)方法. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | 按指定扫描线索引读取整条扫描线。 |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | 按指定扫描线索引读取整条扫描线。 |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | 将一种颜色替换为具有允许差异的另一种颜色并保留原始 alpha 值以保存平滑的边缘。 |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | 将一种颜色替换为具有允许差异的另一种颜色并保留原始 alpha 值以保存平滑的边缘。 |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | 用新颜色替换所有非透明颜色并保留原始 alpha 值以保存平滑边缘。 注意：如果您在没有透明度的图像上使用它，所有颜色将被替换为一个颜色。 |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | 用新颜色替换所有非透明颜色并保留原始 alpha 值以保存平滑边缘。 注意：如果您在没有透明度的图像上使用它，所有颜色将被替换为一个颜色。 |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 调整图像大小。默认值LeftTopToLeftTop使用. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/#resize_1)(int, int, ImageResizeSettings) | 调整图像大小。 |
| override [Resize](../../aspose.psd/rastercachedimage/resize/#resize_2)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | 按比例调整宽度。 |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | 围绕中心旋转图像。 |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/#rotate_1)(float, bool, Color) | 围绕中心旋转图像。 |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | 旋转、翻转或旋转并翻转图像。 |
| [Save](../../aspose.psd/image/save/)() | 将图像数据保存到底层流中。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流中。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 根据保存选项以指定文件格式将图像数据保存到指定流。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | 根据保存选项以指定的文件格式将对象的数据保存到指定的文件位置。 |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项以指定文件格式将图像数据保存到指定流。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | 根据保存选项以指定的文件格式将对象的数据保存到指定的文件位置。 |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 保存 32 位 ARGB 像素。 |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | 保存像素。 |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | 保存像素。 |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | 保存原始数据。 |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | 为指定位置设置图像 32 位 ARGB 像素。 |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | 为指定位置设置图像像素。 |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | 为此设置分辨率[`RasterImage`](../rasterimage/) . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | 将光栅图像转换为位图。 |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | 将整个扫描线写入指定的扫描线索引。 |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | 将整个扫描线写入指定的扫描线索引。 |

### 例子

以下代码演示了按特定矩形裁剪图像的能力。

```csharp
[C#]

string sourceFileName = "SourceFile.psd";
string exportPath = "SourceFileEdited.psd";
string exportPathPng = "SourceFileEdited.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    var oldLayer = image.Layers[0];
    var oldBounds = oldLayer.Bounds;

    var oldLayerData = image.Layers[0].LoadArgb32Pixels(oldBounds);

    var layers = new Layer[4];
    for (int i = 0; i < 4; i++)
    {
        layers[i] = new Layer(
            oldBounds,
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            "Layer " + i.ToString());
        layers[i].SaveArgb32Pixels(oldBounds, oldLayerData);
    }

    image.Resize(186, 602);

    layers[0].Crop(new Rectangle(0, 0, 186, 159));
    layers[1].Crop(new Rectangle(186, 0, 186, 159));
    layers[2].Crop(new Rectangle(0, 159, 186, 142));
    layers[3].Crop(new Rectangle(186, 159, 186, 142));

    oldLayer.Dispose();
    image.Layers = layers;

    var top = 0;
    for (int i = 0; i < 4; i++)
    {
        var width = layers[i].Width;
        var height = layers[i].Height;
        layers[i].Left = 0;
        layers[i].Top = top;
        layers[i].Right = width;
        layers[i].Bottom = height + layers[i].Top;
        top += layers[i].Height;
    }

    // 保存psd
    image.Save(exportPath, new PsdOptions());

    // 保存png
    image.Save(exportPathPng, new PngOptions());
}
```

### 也可以看看

* class [RasterImage](../rasterimage/)
* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


