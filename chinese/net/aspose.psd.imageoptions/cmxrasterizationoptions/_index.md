---
title: Class CmxRasterizationOptions
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.ImageOptions.CmxRasterizationOptions 班级. CMX 导出器选项
type: docs
weight: 4800
url: /zh/net/aspose.psd.imageoptions/cmxrasterizationoptions/
---
## CmxRasterizationOptions class

CMX 导出器选项。

```csharp
public class CmxRasterizationOptions : VectorRasterizationOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [CmxRasterizationOptions](cmxrasterizationoptions/)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/backgroundcolor/) { get; set; } | 获取或设置背景颜色。 |
| [BorderX](../../aspose.psd.imageoptions/vectorrasterizationoptions/borderx/) { get; set; } | 获取或设置边框 X. |
| [BorderY](../../aspose.psd.imageoptions/vectorrasterizationoptions/bordery/) { get; set; } | 获取或设置边框 Y. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，它是为所有内部缓冲区定义的最大允许大小。 |
| [CenterDrawing](../../aspose.psd.imageoptions/vectorrasterizationoptions/centerdrawing/) { get; set; } | 获取或设置一个值，该值指示绘图是否居中。 |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | 获取或设置默认替换字体（导出到光栅时将用于绘制文本的字体，如果系统中未显示 PSD 文件中的现有图层字体）。 可以使用下一个代码片段来获取默认字体的正确名称: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); 复制代码 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| [DrawColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/drawcolor/) { get; set; } | 获取或设置前景颜色。 |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | 获取或设置一个值，表示是否[全帧]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | 多页选项 |
| [PageHeight](../../aspose.psd.imageoptions/vectorrasterizationoptions/pageheight/) { get; set; } | 获取或设置页面高度。 |
| [PageSize](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagesize/) { get; set; } | 获取或设置页面大小。 |
| [PageWidth](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagewidth/) { get; set; } | 获取或设置页面宽度。 |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | 获取或设置调色板。 |
| [Positioning](../../aspose.psd.imageoptions/cmxrasterizationoptions/positioning/) { get; set; } | 获取或设置定位。 |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 获取或设置进度事件处理程序。 |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 获取或设置分辨率设置。 |
| [SmoothingMode](../../aspose.psd.imageoptions/vectorrasterizationoptions/smoothingmode/) { get; set; } | 获取或设置平滑模式。 |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 获取或设置创建图像的来源. |
| [TextRenderingHint](../../aspose.psd.imageoptions/vectorrasterizationoptions/textrenderinghint/) { get; set; } | 获取或设置文本渲染提示。 |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 获取或设置矢量光栅化选项。 |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | 获取或设置 XMP 元数据容器。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | 克隆此实例。 |
| [CopyTo](../../aspose.psd.imageoptions/vectorrasterizationoptions/copyto/)(VectorRasterizationOptions) | 复制到. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 处理当前实例。 |

### 也可以看看

* class [VectorRasterizationOptions](../vectorrasterizationoptions/)
* 命名空间 [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* 部件 [Aspose.PSD](../../)


