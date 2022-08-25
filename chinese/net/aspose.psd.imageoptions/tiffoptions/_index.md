---
title: TiffOptions
second_title: Aspose.PSD for .NET API 参考
description: tiff 文件格式选项 请注意宽度和高度标签将在创建图像时被宽度和高度参数覆盖因此无需直接指定它们 请注意许多选项返回默认值但这并不意味着此选项明确设置为标记值要验证标签是否存在请使用 Tags 属性或相应的 IsTagPresent 方法
type: docs
weight: 4870
url: /zh/net/aspose.psd.imageoptions/tiffoptions/
---
## TiffOptions class

tiff 文件格式选项。 请注意，宽度和高度标签将在创建图像时被宽度和高度参数覆盖，因此无需直接指定它们。 请注意，许多选项返回默认值，但这并不意味着此选项明确设置为标记值。要验证标签是否存在，请使用 Tags 属性或相应的 IsTagPresent 方法。

```csharp
public class TiffOptions : ImageOptionsBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TiffOptions](tiffoptions#constructor_2)(TiffDataType[]) | 初始化[`TiffOptions`](../tiffoptions)类. |
| [TiffOptions](tiffoptions#constructor)(TiffExpectedFormat) | 初始化[`TiffOptions`](../tiffoptions)班级。默认情况下使用小端约定。 |
| [TiffOptions](tiffoptions#constructor_3)(TiffOptions) | 初始化[`TiffOptions`](../tiffoptions)类. |
| [TiffOptions](tiffoptions#constructor_1)(TiffExpectedFormat, TiffByteOrder) | 初始化[`TiffOptions`](../tiffoptions)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage) { get; set; } | 获取或设置 alpha 存储选项。以外的选项Unspecified 多于 3 个时使用[`SamplesPerPixel`](./samplesperpixel)定义. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist) { get; set; } | 获取或设置艺术家。 |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel) { get; } | 获取每个像素的位数。 |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample) { get; set; } | 获取或设置每个样本的位数。 |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder) { get; set; } | 获取或设置一个表示tiff字节顺序的值。 |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap) { get; set; } | 获取或设置颜色图。 |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality) { get; set; } | 获取或设置压缩图像质量。 与 Jpeg 压缩一起使用。 |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression) { get; set; } | 获取或设置压缩。 |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright) { get; set; } | 获取或设置版权。 |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime) { get; set; } | 获取或设置日期和时间。 |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | 获取或设置默认替换字体（导出到光栅时将用于绘制文本的字体，如果 PSD 文件中的现有图层字体未在系统中显示）。 可以使用下一个代码片段来获取默认字体的正确名称: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] family = col.Families; string defaultFontName = family[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | 获取一个值，该值指示此实例是否被释放。 |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname) { get; set; } | 获取或设置文档的名称。 |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd) { get; } | 获取或设置指向 EXIF IFD 的指针。 |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options) { get; set; } | 获取或设置传真 t4 选项。 |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard) { get; set; } | 获取或设置 TIFF 文件标准。 |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder) { get; set; } | 获取或设置字节位填充顺序。 |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | 获取或设置一个值，指示是否[全帧]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints) { get; set; } | 获取或设置半色调提示。 |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile) { get; set; } | 获取或设置 Icc 配置文件流。 |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription) { get; set; } | 获取或设置图片描述。 |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength) { get; set; } | 获取或设置图像长度。 |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth) { get; set; } | 获取或设置图像宽度。 |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames) { get; set; } | 获取或设置墨迹名称。 |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent) { get; } | 获取指示是否存在额外样本的值。 |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled) { get; } | 获取一个表示图像是否平铺的值。 |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid) { get; } | 获取一个值，该值指示是否[`TiffOptions`](../tiffoptions)已正确配置。使用 Validate 方法查找失败原因。 |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue) { get; set; } | 获取或设置最大样本值。 |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue) { get; set; } | 获取或设置最小样本值。 |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | 多页选项 |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation) { get; set; } | 获取或设置方向。 |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename) { get; set; } | 获取或设置页面名称。 |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber) { get; set; } | 获取或设置页码标签。 |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette) { get; set; } | 获取或设置调色板。 |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric) { get; set; } | 获取或设置光度。 |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration) { get; set; } | 获取或设置平面配置。 |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor) { get; set; } | 获取或设置 LZW 压缩的预测器。 |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents) { get; set; } | 获取或设置一个值，该值指示是否必须对分量进行预乘。 |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | 获取或设置进度事件处理程序。 |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings) { get; set; } | 获取或设置分辨率设置。 |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit) { get; set; } | 获取或设置分辨率单位。 |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip) { get; set; } | 获取或设置每个条带的行数。 |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat) { get; set; } | 获取或设置样本格式。 |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel) { get; } | 获取每个像素的样本。要更改此属性值，请使用[`BitsPerSample`](./bitspersample)属性设置器. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer) { get; set; } | 获取或设置扫描仪制造商。 |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel) { get; set; } | 获取或设置扫描仪型号。 |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue) { get; set; } | 获取或设置最大样本值。该值具有与样本数据最匹配的字段类型（字节、短或长类型）。 |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue) { get; set; } | 获取或设置最小样本值。该值具有与样本数据最匹配的字段类型（字节、短或长类型）。 |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype) { get; set; } | 获取或设置软件类型。 |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | 获取或设置要在其中创建图像的源。 |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts) { get; set; } | 获取或设置条带字节数。 |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets) { get; set; } | 获取或设置条带偏移量。 |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype) { get; set; } | 获取或设置此子文件中包含的数据类型的一般指示。 |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags) { get; set; } | 获取或设置标签。 |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter) { get; set; } | 获取或设置目标打印机。 |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding) { get; set; } | 获取或设置阈值。 |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts) { get; set; } | 获取或设置图块字节数。 |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength) { get; set; } | 获取 ot 设置图块长度。 |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets) { get; set; } | 获取或设置瓦片偏移量。 |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth) { get; set; } | 获取 ot 设置图块宽度。 |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages) { get; } | 获取总页数。 |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount) { get; } | 获取有效标签计数。这不是标签总数，而是可以保留的标签数量。 |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | 获取或设置矢量光栅化选项。 |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata) { get; set; } | 获取或设置 XMP 元数据容器。 |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor) { get; set; } | 获取或设置图片作者，供 Windows Explorer 使用。 |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment) { get; set; } | 获取或设置图像的注释，供 Windows 资源管理器使用。 |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords) { get; set; } | 获取或设置主题图像，供 Windows Explorer 使用。 |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition) { get; set; } | 获取或设置 x 位置。 |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject) { get; set; } | 获取或设置图像信息，供 Windows Explorer 使用。 |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle) { get; set; } | 获取或设置图像信息，供 Windows Explorer 使用。 |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution) { get; set; } | 获取或设置 x 分辨率。 |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients) { get; set; } | 获取或设置 YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling) { get; set; } | 获取或设置 YCbCr 光度计的子采样因子。 |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition) { get; set; } | 获取或设置 y 位置。 |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution) { get; set; } | 获取或设置 y 分辨率。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag)(TiffDataType) | 添加一个新标签。 |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags)(TiffDataType[]) | 添加标签。 |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | 克隆此实例。 |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | 处理当前实例。 |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype)(TiffTags) | 按类型获取标签的实例。 |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent)(TiffTags) | 确定选项中是否存在标签。 |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag)(TiffTags) | 删除标签。 |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate)() | 验证选项是否具有有效的标签组合 |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount)(TiffDataType[]) | 获取有效标签计数。 |

### 例子

此示例演示了将 SaveOptions 命名空间中的不同类用于导出目的。 Psd 类型的图像被加载到 Image 的实例中，然后导出为多种格式。

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

此示例使用 GraphicsPath 和 Graphics 类在图像表面上创建和操作图形。示例在 GraphicsPath 类的帮助下创建一个新图像并绘制路径。最后调用 Graphics 类公开的 DrawPath 方法来渲染表面上的路径。最后将图像导出为 Tiff 文件格式。

```csharp
[C#]

//创建一个Image实例 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建并初始化一个Graphics类的实例
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //清除图形表面
    graphics.Clear(Color.Wheat);

    //创建GraphicsPath类的实例
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //创建一个Figure类的实例
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //将形状添加到图形对象
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //将Figure对象添加到GraphicsPath
    graphicspath.AddFigure(figure);

    //使用颜色为黑色的 Pen 对象绘制路径
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //创建一个TiffOptions实例并设置它的各种属性
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // 保存所有更改。
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### 也可以看看

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase)
* 命名空间 [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
