---
title: Class PdfOptions
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.ImageOptions.PdfOptions 班级. PDF 选项
type: docs
weight: 4870
url: /zh/net/aspose.psd.imageoptions/pdfoptions/
---
## PdfOptions class

PDF 选项。

```csharp
public class PdfOptions : ImageOptionsBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PdfOptions](pdfoptions/)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，它是为所有内部缓冲区定义的最大允许大小。 |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | 获取或设置默认替换字体（导出到光栅时将用于绘制文本的字体，如果系统中未显示 PSD 文件中的现有图层字体）。 可以使用下一个代码片段来获取默认字体的正确名称: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); 复制代码 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | 获取或设置一个值，表示是否[全帧]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | 多页选项 |
| [PageSize](../../aspose.psd.imageoptions/pdfoptions/pagesize/) { get; set; } | 获取或设置页面的大小。 |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | 获取或设置调色板。 |
| [PdfCoreOptions](../../aspose.psd.imageoptions/pdfoptions/pdfcoreoptions/) { get; set; } | PDF 核心选项 |
| [PdfDocumentInfo](../../aspose.psd.imageoptions/pdfoptions/pdfdocumentinfo/) { get; set; } | 获取或设置文档的元数据。 |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 获取或设置进度事件处理程序。 |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 获取或设置分辨率设置。 |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 获取或设置创建图像的来源. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 获取或设置矢量光栅化选项。 |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | 获取或设置 XMP 元数据容器。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | 克隆此实例。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 处理当前实例。 |

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

下面的例子演示了 AsposePSD 支持将 PSB 文件导出为 PSD 格式。

```csharp
[C#]

// 支持将PSB保存为PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

以下代码将 PsdImage 保存为带有可选文本的 PDF 文档。

```csharp
[C#]

// 将 PSD 保存为 PDF 不提供可选择的文本
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

以下示例演示支持将 PsdImage 导出为 Pdf 格式。

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"1.psd",
    @"little.psb",
    @"psb3.psb",
    @"inRgb16.psd",
    @"ALotOfElementTypes.psd",
    @"ColorOverlayAndShadowAndMask.psd",
    @"ThreeRegularLayersSemiTransparent.psd"
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string sourceFileName = sourcesFiles[i];
    using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
    {
        string outFileName = "PsdToPdf" + i + ".pdf";
        image.Save(outFileName, new PdfOptions());
    }
}
```

### 也可以看看

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* 命名空间 [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* 部件 [Aspose.PSD](../../)


