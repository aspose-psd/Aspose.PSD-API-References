---
title: Class ImageOptionsBase
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.ImageOptionsBase 班级. 图像基础选项
type: docs
weight: 4990
url: /zh/net/aspose.psd/imageoptionsbase/
---
## ImageOptionsBase class

图像基础选项。

```csharp
public abstract class ImageOptionsBase : DisposableObject
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，它是为所有内部缓冲区定义的最大允许大小。 |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | 获取或设置默认替换字体（导出到光栅时将用于绘制文本的字体，如果系统中未显示 PSD 文件中的现有图层字体）。 可以使用下一个代码片段来获取默认字体的正确名称: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); 复制代码 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | 获取或设置一个值，表示是否[全帧]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | 多页选项 |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | 获取或设置调色板。 |
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

### 也可以看看

* class [DisposableObject](../disposableobject/)
* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


