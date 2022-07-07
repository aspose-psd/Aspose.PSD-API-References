---
title: PngOptions
second_title: Aspose.PSD for .NET API 参考
description: png 文件格式创建选项
type: docs
weight: 4760
url: /zh/net/aspose.psd.imageoptions/pngoptions/
---
## PngOptions class

png 文件格式创建选项。

```csharp
public class PngOptions : ImageOptionsBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PngOptions](pngoptions#constructor)() | 初始化[`PngOptions`](../pngoptions)类的新实例。 |
| [PngOptions](pngoptions#constructor_1)(PngOptions) | 初始化[`PngOptions`](../pngoptions)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BitDepth](../../aspose.psd.imageoptions/pngoptions/bitdepth) { get; set; } | 位深度。 |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ColorType](../../aspose.psd.imageoptions/pngoptions/colortype) { get; set; } | 获取或设置颜色的类型。 |
| [CompressionLevel](../../aspose.psd.imageoptions/pngoptions/compressionlevel) { get; set; } | png 图像压缩级别在 0-9 范围内，其中 9 为最大压缩，0 为存储模式。 |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | 获取或设置默认替换字体（如果系统中未显示 PSD 文件中的现有图层字体，则在导出为栅格时用于绘制文本的字体）。 下一个代码片段可以使用默认字体的正确名称： System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] 系列 = col.Families; 字符串 defaultFontName = family[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | 获取一个值，该值指示该实例是否被释放。 |
| [FilterType](../../aspose.psd.imageoptions/pngoptions/filtertype) { get; set; } | 获取或设置 png 文件保存过程中使用的过滤器类型。 |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | 获取或设置一个值，指示是否[全帧]。 |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | 多页选项 |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette) { get; set; } | 获取或设置调色板。 |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | 获取或设置进度事件处理程序。 |
| [Progressive](../../aspose.psd.imageoptions/pngoptions/progressive) { get; set; } | 获取或设置一个值，该值指示此[`PngOptions`](../pngoptions)是否为渐进式。 |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings) { get; set; } | 获取或设置分辨率设置。 |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | 获取或设置创建图像的源。 |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | 获取或设置矢量光栅化选项。 |
| override [XmpData](../../aspose.psd.imageoptions/pngoptions/xmpdata) { get; set; } | 获取或设置 XMP 元数据容器。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | 克隆此实例。 |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | 释放当前实例。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [DefaultCompressionLevel](../../aspose.psd.imageoptions/pngoptions/defaultcompressionlevel) | 默认压缩级别。 |

### 例子

以下示例演示了如何将 AI 文件导出为 Aspose.PSD 中的 PSD 和 PNG 格式

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

本示例演示如何使用 SaveOptions 命名空间中的不同类进行导出。 Psd 类型的图像被加载到 Image 的实例中，然后导出为多种格式。

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

以下示例演示如何在 Aspose.PSD 中使用 PassThrough 图层混合模式

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

以下示例演示文档转换进度正常工作，无一例外。

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

此示例使用 Graphics 类在 Image 表面上创建原始形状。为了演示该操作，该示例创建一个 PSD 格式的新图像，并使用 Graphics 类公开的 Draw 方法在图像表面绘制原始形状，然后将其导出为 PSD 文件格式。

```csharp
[C#]

//创建一个Image实例 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建并初始化一个Graphics类的实例
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //清除图形表面
    graphics.Clear(Color.Wheat);

    //通过指定具有黑色颜色的Pen对象来绘制弧线， 
    //一个围绕圆弧的矩形，起始角和扫角
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //通过指定具有蓝色和坐标点的 Pen 对象来绘制 Bezier。
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //通过指定具有绿色的 Pen 对象和点数组来绘制曲线
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //使用 Pen 对象和周围的 Rectangle 绘制一个椭圆
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //画一条线 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //画一个饼段
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //通过指定具有红色的 Pen 对象和点数组来绘制多边形
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //画一个矩形
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //创建一个SolidBrush对象并设置它的各种属性
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //使用 SolidBrush 对象和字体在特定点绘制一个字符串
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //创建一个PngOptions实例并设置它的各种属性
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // 保存所有更改。
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### 也可以看看

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase)
* 命名空间 [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
