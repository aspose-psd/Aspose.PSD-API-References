---
title: JpegOptions
second_title: Aspose.PSD for .NET API 参考
description: jpeg 文件格式创建选项
type: docs
weight: 4720
url: /zh/net/aspose.psd.imageoptions/jpegoptions/
---
## JpegOptions class

jpeg 文件格式创建选项。

```csharp
public class JpegOptions : ImageOptionsBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [JpegOptions](jpegoptions#constructor)() | 初始化[`JpegOptions`](../jpegoptions)类的新实例。 |
| [JpegOptions](jpegoptions#constructor_1)(JpegOptions) | 初始化[`JpegOptions`](../jpegoptions)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel) { get; set; } | 获取或设置无损 jpeg 图像的每个通道的位。现在我们支持每通道 2 到 8 位。 |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile) { get; set; } | CMYK jpeg 图像的目标 CMYK 颜色配置文件。用于保存图像。必须与 RGBColorProfile 配对以进行正确的颜色转换。 |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype) { get; set; } | 获取或设置 jpeg 图像的颜色类型。 |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment) { get; set; } | 获取或设置 jpeg 文件注释。 |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype) { get; set; } | 获取或设置压缩类型。 |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | 获取或设置默认替换字体（如果系统中未显示 PSD 文件中的现有图层字体，则在导出为栅格时用于绘制文本的字体）。 下一个代码片段可以使用默认字体的正确名称： System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] 系列 = col.Families; 字符串 defaultFontName = family[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | 获取一个值，该值指示该实例是否被释放。 |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata) { get; set; } | 获取或设置 exif 数据容器 |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | 获取或设置一个值，指示是否[全帧]。 |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling) { get; set; } | 获取或设置每个分量的水平二次采样。 |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif) { get; set; } | 获取或设置 jfif。 |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror) { get; set; } | 获取或设置用于近无损编码的 JPEG-LS 差异界限（来自 JPEG-LS 规范的 NEAR 参数）。 |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode) { get; set; } | 获取或设置 JPEG-LS 交错模式。 |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset) { get; set; } | 获取或设置 JPEG-LS 预设参数。 |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | 多页选项 |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette) { get; set; } | 获取或设置调色板。 |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent) { get; set; } | 获取或设置一个值，该值指示红色、绿色和蓝色分量是否应与背景颜色混合（如果存在 Alpha 通道）。 |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | 获取或设置进度事件处理程序。 |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality) { get; set; } | 获取或设置图像质量。 |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings) { get; set; } | 获取或设置 RD 优化器设置。 |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings) { get; set; } | 获取或设置分辨率设置。 |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit) { get; set; } | 获取或设置分辨率单位。 |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile) { get; set; } | CMYK jpeg 图像的目标 RGB 颜色配置文件。用于保存图像。必须与 CMYKColorProfile 配对以进行正确的颜色转换。 |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode) { get; set; } | 获取或设置样本舍入模式以将 8 位值拟合为 n 位值。BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality) { get; } | 缩放质量。 |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | 获取或设置创建图像的源。 |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | 获取或设置矢量光栅化选项。 |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling) { get; set; } | 获取或设置每个分量的垂直二次采样。 |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata) { get; set; } | 获取或设置 XMP 元数据容器。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | 克隆此实例。 |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | 释放当前实例。 |

### 例子

这个例子演示了使用 Aspose.PSD for .Net API 将图像转换为 Jpeg 格式。为了实现这个目标，这个例子加载了一个现有的图像，然后将其转换为 Jpeg 文件格式。

```csharp
[C#]

//创建一个图像类的实例，并通过文件路径使用现有文件对其进行初始化
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //创建一个PsdOptions类的实例
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //将质量设置为 50% 以减小输出图像的大小。
    jpegOptions.Quality = 50;

    //设置exif注释。
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //使用提供的 JpegOptions 设置将图像保存到磁盘位置
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

这个例子演示了使用 System.IO.Stream 创建一个新的 Image 文件

```csharp
[C#]

//创建一个 PsdOptions 实例并设置它的各种属性
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//创建System.IO.Stream的实例
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//定义PsdOptions实例的源属性
//第二个布尔参数确定Stream一旦超出范围就被释放
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//创建一个Image实例，调用Create方法以PsdOptions为参数初始化Image对象   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //做一些图像处理
}
```

这个例子演示了不同类的使用用于导出目的的 SaveOptions 命名空间。 Psd 类型的图像被加载到 Image 的实例中，然后导出为多种格式。

```csharp
[C#]

//在Image类的实例中加载现有图像
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //使用默认选项导出为BMP文件格式
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //使用默认选项导出为JPEG文件格式
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //使用默认选项导出为JPEG 2000文件格式
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //使用默认选项导出为PNG文件格式
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //使用默认选项导出为 TIFF 文件格式
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### 也可以看看

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase)
* 命名空间 [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
