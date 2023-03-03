---
title: Class AiImage
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Ai.AiImage 班级. Adobe Illustrator AI 图像
type: docs
weight: 1260
url: /zh/net/aspose.psd.fileformats.ai/aiimage/
---
## AiImage class

Adobe Illustrator (AI) 图像

```csharp
public sealed class AiImage : Image
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [AiImage](aiimage/)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 获取或设置一个值，指示是否自动调整调色板。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.psd.fileformats.ai/aiimage/bitsperpixel/) { get; } | 获取每像素计数的图像位数。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 获取图像边界。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，它是为所有内部缓冲区定义的最大允许大小。 |
| [Container](../../aspose.psd/image/container/) { get; } | 获取[`Image`](../../aspose.psd/image/)容器. |
| [DataSection](../../aspose.psd.fileformats.ai/aiimage/datasection/) { get; } | 获取数据部分。 |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| override [FileFormat](../../aspose.psd.fileformats.ai/aiimage/fileformat/) { get; } | 获取文件格式 的值 |
| [FinalizeSection](../../aspose.psd.fileformats.ai/aiimage/finalizesection/) { get; } | 获取最终部分。 |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 获取或设置图像是否有背景色的值。 |
| [Header](../../aspose.psd.fileformats.ai/aiimage/header/) { get; } | 获取标题。 |
| override [Height](../../aspose.psd.fileformats.ai/aiimage/height/) { get; } | 获取图像高度。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.psd.fileformats.ai/aiimage/iscached/) { get; } | 获取对象数据当前是否缓存，不需要读取数据的值。 |
| [Layers](../../aspose.psd.fileformats.ai/aiimage/layers/) { get; } | 获取图层部分。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | 获取或设置调色板。直接表示像素时不使用调色板。 |
| [SetupSection](../../aspose.psd.fileformats.ai/aiimage/setupsection/) { get; } | 获取设置部分。 |
| [Size](../../aspose.psd/image/size/) { get; } | 获取图像大小。 |
| [Version](../../aspose.psd.fileformats.ai/aiimage/version/) { get; } | 获取 Adobe Illustrator format 的版本 |
| override [Width](../../aspose.psd.fileformats.ai/aiimage/width/) { get; } | 获取图像宽度。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.ai/aiimage/addlayer/)(AiLayerSection) | 添加 AI 层部分。 |
| override [CacheData](../../aspose.psd.fileformats.ai/aiimage/cachedata/)() | 缓存数据并确保不会从底层执行额外的数据加载[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传递的保存选项所代表的指定文件格式。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 处理当前实例。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | 获取默认选项。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 获取基于原始文件设置的选项。 这有助于保持原始图像的位深度和其他参数不变。 例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用 the 保存[`Save`](../../aspose.psd/datastreamsupporter/save/)方法，将生成每像素 8 位的输出 PNG 图像。 要避免它并保存每像素 1 位的 PNG 图像，请使用此方法获取相应的保存选项并将它们 传递给[`Save`](../../aspose.psd/image/save/)方法作为第二个参数. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 调整图像大小。默认值LeftTopToLeftTop使用. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_1)(int, int, ImageResizeSettings) | 调整图像大小。 |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_2)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | 按比例调整宽度。 |
| override [RotateFlip](../../aspose.psd.fileformats.ai/aiimage/rotateflip/)(RotateFlipType) | 旋转、翻转或旋转并翻转图像。 |
| [Save](../../aspose.psd/image/save/)() | 将图像数据保存到底层流中。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流中。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | 将对象的数据保存到指定的文件位置。 |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 根据保存选项以指定文件格式将图像数据保存到指定流。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | 根据保存选项以指定的文件格式将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项以指定文件格式将图像数据保存到指定流。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | 根据保存选项以指定的文件格式将对象的数据保存到指定的文件位置。 |
| override [SetPalette](../../aspose.psd.fileformats.ai/aiimage/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |

### 例子

以下示例演示如何在 Aspose.PSD 中将 Adobe Illustrator 文件导出为 PDF 格式

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

以下示例演示如何在 Aspose.PSD 中将 AI 文件导出为 PSD 和 PNG 格式

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

以下示例演示支持将 Ai 格式导出为 PSD、PNG、JPG、GIF 和 TIF 格式。

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"34992OStroke",
    @"rect2_color",
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string name = sourcesFiles[i];
    string sourceFileName = name + ".ai";

    using (AiImage image = (AiImage)Image.Load(sourceFileName))
    {
        string outFileName = name + ".psd";
        ImageOptionsBase options = new PsdOptions();
        image.Save(outFileName, options);

        outFileName = name + ".png";
        options = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
        image.Save(outFileName, options);

        outFileName = name + ".jpg";
        options = new JpegOptions() { Quality = 85 };
        image.Save(outFileName, options);

        outFileName = name + ".gif";
        options = new GifOptions() { DoPaletteCorrection = false };
        image.Save(outFileName, options);

        outFileName = name + ".tif";
        options = new TiffOptions(TiffExpectedFormat.TiffDeflateRgba);
        image.Save(outFileName, options);
    }
}
```

### 也可以看看

* class [Image](../../aspose.psd/image/)
* 命名空间 [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* 部件 [Aspose.PSD](../../)


