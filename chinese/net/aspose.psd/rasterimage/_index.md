---
title: RasterImage
second_title: Aspose.PSD for .NET API 参考
description: 表示支持光栅图形操作的光栅图像
type: docs
weight: 5200
url: /zh/net/aspose.psd/rasterimage/
---
## RasterImage class

表示支持光栅图形操作的光栅图像。

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette) { get; set; } | 获取或设置是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor) { get; set; } | 获取或设置背景颜色的值。 |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel) { get; } | 获取每像素的图像位数。 |
| [Bounds](../../aspose.psd/image/bounds) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.psd/image/container) { get; } | 获取[`Image`](../image)容器。 |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | 获取一个值，该值指示该实例是否被释放。 |
| virtual [FileFormat](../../aspose.psd/image/fileformat) { get; } | 获取文件格式的值 |
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha) { get; } | 获取一个值，该值指示此实例是否具有 alpha。 |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor) { get; set; } | 获取或设置一个值，该值指示图像是否具有背景色。 |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor) { get; set; } | 获取图像是否具有透明色的值。 |
| abstract [Height](../../aspose.psd/image/height) { get; } | 获取图像高度。 |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution) { get; set; } | 获取或设置此[`RasterImage`](../rasterimage)的水平分辨率，以每英寸像素为单位。 |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity) { get; } | 获取此图像的不透明度。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor) { get; set; } | 获取或设置中断监视器。 |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached) { get; } | 获取一个值，表示当前是否缓存了对象的数据，不需要读取数据。 |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable) { get; } | 获取一个值，该值指示是否可以加载原始数据。 |
| [Palette](../../aspose.psd/image/palette) { get; set; } | 获取或设置调色板。直接表示像素时不使用调色板。 |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents) { get; set; } | 获取或设置一个值，该值指示是否必须对图像分量进行预乘。 |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter) { get; set; } | 获取或设置自定义颜色转换器 |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat) { get; } | 获取原始数据格式。 |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings) { get; } | 获取当前的原始数据设置。请注意，使用这些设置时，数据加载时无需转换。 |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex) { get; set; } | 获取或设置调色板索引超出范围时使用的后备索引 |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter) { get; set; } | 获取或设置索引颜色转换器 |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize) { get; } | 获取原始行大小（以字节为单位）。 |
| [Size](../../aspose.psd/image/size) { get; } | 获取图像大小。 |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor) { get; set; } | 获取图像透明色。 |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata) { get; set; } | 获取或设置是否更新 XMP 元数据的值。 |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata) { get; set; } | 获取或设置一个值，该值指示当原始数据加载可用时是否使用原始数据加载。 |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution) { get; set; } | 获取或设置此[`RasterImage`](../rasterimage)的垂直分辨率，以每英寸像素为单位。 |
| abstract [Width](../../aspose.psd/image/width) { get; } | 获取图像宽度。 |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata) { get; set; } | 获取或设置 XMP 元数据。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [AdjustBrightness](../../aspose.psd/rasterimage/adjustbrightness)(int) | 调整图像的亮度。 |
| virtual [AdjustContrast](../../aspose.psd/rasterimage/adjustcontrast)(float) | 图像对比度 |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma#adjustgamma)(float) | 图像的伽玛校正。 |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma#adjustgamma_1)(float, float, float) | 图像的伽玛校正。 |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley#binarizebradley)(double) | 使用 Bradley 自适应阈值算法对图像进行二值化，使用积分图像阈值 |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley#binarizebradley_1)(double, int) | 使用 Bradley 自适应阈值算法对图像进行二值化，使用积分图像阈值 |
| virtual [BinarizeFixed](../../aspose.psd/rasterimage/binarizefixed)(byte) | 具有预定义阈值的图像的二值化 |
| virtual [BinarizeOtsu](../../aspose.psd/rasterimage/binarizeotsu)() | 使用 Otsu 阈值对图像进行二值化 |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata)() | 缓存数据并确保不会从底层[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer)执行额外的数据加载。 |
| [CanSave](../../aspose.psd/image/cansave)(ImageOptionsBase) | 确定图像是否可以保存为传递的保存选项表示的指定文件格式。 |
| virtual [Crop](../../aspose.psd/rasterimage/crop#crop)(Rectangle) | 裁剪指定的矩形。 |
| virtual [Crop](../../aspose.psd/rasterimage/crop#crop_1)(int, int, int, int) | 带班次裁剪图像。 |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | 释放当前实例。 |
| [Dither](../../aspose.psd/rasterimage/dither#dither)(DitheringMethod, int) | 对当前图像执行抖动。 |
| abstract [Dither](../../aspose.psd/rasterimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | 对当前图像执行抖动。 |
| virtual [Filter](../../aspose.psd/rasterimage/filter)(Rectangle, FilterOptionsBase) | 过滤指定的矩形。 |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel)(int, int) | 获取图像 32 位 ARGB 像素。 |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels)(Rectangle) | 获取默认的 32 位 ARGB 像素数组。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions)(object[]) | 获取默认选项。 |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | 使用部分像素加载器获取默认像素数组。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata#getdefaultrawdata)(Rectangle, RawDataSettings) | 获取默认的原始数据数组。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata#getdefaultrawdata_1)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 使用部分像素加载器获取默认的原始数据数组。 |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate)(bool) | 获取上次修改资源图像的日期和时间。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions)() | 获取基于原始文件设置的选项。 这有助于保持原始图像的位深度和其他参数不变。 例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../datastreamsupporter/save)方法，将生成每像素 8 位的输出 PNG 图像。 为了避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项并将它们 传递给[`Save`](../image/save)方法作为第二个参数。 |
| [GetPixel](../../aspose.psd/rasterimage/getpixel)(int, int) | 获取图像像素。 |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle)() | 获取倾斜角度。 此方法适用于扫描的文本文档，用于确定扫描时的倾斜角度。 |
| virtual [Grayscale](../../aspose.psd/rasterimage/grayscale)() | 将图像转换为其灰度表示 |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels)(Rectangle) | 加载 32 位 ARGB 像素。 |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels)(Rectangle) | 加载 64 位 ARGB 像素。 |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels)(Rectangle) | 以 CMYK 格式加载像素。 |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | 部分按包加载 32 位 ARGB 像素。 |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | 部分按包加载像素。 |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels)(Rectangle) | 加载像素。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata#loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata#loadrawdata_1)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 加载原始数据。 |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle#normalizeangle)() | 标准化角度。 此方法适用于扫描的文本文档，以消除倾斜扫描。 此方法使用[`GetSkewAngle`](./getskewangle)和[`Rotate`](./rotate)方法。 |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle#normalizeangle_1)(bool, Color) | 标准化角度。 此方法适用于扫描的文本文档，以消除倾斜扫描。 此方法使用[`GetSkewAngle`](./getskewangle)和PSD。颜色）方法。 |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline)(int) | 按指定的扫描线索引读取整个扫描线。 |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline)(int) | 按指定的扫描线索引读取整个扫描线。 |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor#replacecolor)(Color, byte, Color) | 用允许的差异将一种颜色替换为另一种颜色，并保留原始 Alpha 值以保存平滑边缘。 |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor#replacecolor_1)(int, byte, int) | 用允许的差异将一种颜色替换为另一种颜色，并保留原始 Alpha 值以保存平滑边缘。 |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors#replacenontransparentcolors)(Color) | 用新颜色替换所有非透明颜色并保留原始 alpha 值以保存平滑边缘。 注意：如果您在没有透明度的图像上使用它，所有颜色都将替换为一种颜色。 |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors#replacenontransparentcolors_1)(int) | 用新颜色替换所有非透明颜色并保留原始 alpha 值以保存平滑边缘。 注意：如果您在没有透明度的图像上使用它，所有颜色都将替换为一种颜色。 |
| [Resize](../../aspose.psd/image/resize)(int, int) | 调整图像大小。使用默认的LeftTopToLeftTop。 |
| override [Resize](../../aspose.psd/rasterimage/resize#resize_1)(int, int, ImageResizeSettings) | 使用扩展选项调整图像大小。 |
| override [Resize](../../aspose.psd/rasterimage/resize#resize_2)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int, ResizeType) | 按比例调整宽度。 |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate#rotate)(float) | 围绕中心旋转图像。 |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate#rotate_1)(float, bool, Color) | 围绕中心旋转图像。 |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip)(RotateFlipType) | 旋转、翻转或旋转和翻转图像。 |
| [Save](../../aspose.psd/image/save)() | 将图像数据保存到底层流。 |
| [Save](../../aspose.psd/datastreamsupporter/save)(Stream) | 将对象的数据保存到指定的流中。 |
| [Save](../../aspose.psd/datastreamsupporter/save)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.psd/image/save)(Stream, ImageOptionsBase) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.psd/image/save)(string, ImageOptionsBase) | 根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。 |
| override [Save](../../aspose.psd/rasterimage/save#save_3)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.psd/image/save)(string, ImageOptionsBase, Rectangle) | 根据保存选项将对象的数据以指定的文件格式保存到指定的文件位置。 |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels)(Rectangle, int[]) | 保存 32 位 ARGB 像素。 |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels)(Rectangle, int[]) | 保存像素。 |
| [SavePixels](../../aspose.psd/rasterimage/savepixels)(Rectangle, Color[]) | 保存像素。 |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | 保存原始数据。 |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel)(int, int, int) | 为指定位置设置图像 32 位 ARGB 像素。 |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette)(IColorPalette, bool) | 设置图像调色板。 |
| [SetPixel](../../aspose.psd/rasterimage/setpixel)(int, int, Color) | 为指定位置设置图像像素。 |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution)(double, double) | 设置此[`RasterImage`](../rasterimage)的分辨率。 |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap)() | 将光栅图像转换为位图。 |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline)(int, int[]) | 将整个扫描线写入指定的扫描线索引。 |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline)(int, Color[]) | 将整个扫描线写入指定的扫描线索引。 |

### 例子

这个例子展示了如何在颜色类型的数组中加载像素信息，操作数组并将其设置回图像。为了执行这些操作，此示例使用 MemoryStream 对象创建一个新的图像文件（PSD 格式）。

```csharp
[C#]

//创建一个MemoryStream实例
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //创建 PsdOptions 的实例并设置其各种属性，包括 Source 属性
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //创建一个Image实例
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //通过指定区域为图像边界来获取图像的像素
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //遍历数组并设置alrenative索引像素的颜色
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //设置索引像素颜色为黄色
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //设置索引像素颜色为蓝色
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //将像素变化应用到图像
        image.SavePixels(image.Bounds, pixels);

        // 保存所有更改。
        image.Save();
    }

    //将MemoryStream写入文件
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### 也可以看看

* class [Image](../image)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader)
* 命名空间 [Aspose.PSD](../../aspose.psd)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
