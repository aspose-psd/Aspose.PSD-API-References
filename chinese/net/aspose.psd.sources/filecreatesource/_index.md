---
title: Class FileCreateSource
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Sources.FileCreateSource 班级. 表示创建的文件源
type: docs
weight: 5590
url: /zh/net/aspose.psd.sources/filecreatesource/
---
## FileCreateSource class

表示创建的文件源。

```csharp
public sealed class FileCreateSource : FileSource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | 初始化一个新的实例`FileCreateSource`类. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | 初始化一个新的实例`FileCreateSource`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | 获取要创建的文件路径。 |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | 获取一个值，该值指示文件是否是临时的。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | 获取流容器。 |

### 例子

此示例演示了使用 Font 和 SolidBrush 类在 Image 表面上绘制字符串。该示例创建一个新图像并使用 Figures 和 GraphicsPath 绘制形状

```csharp
[C#]

//创建图像实例
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建并初始化Graphics类的实例
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //清除图形表面
    graphics.Clear(Color.Wheat);

    //创建字体实例
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //创建一个具有红色的 SolidBrush 实例
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //画一个字符串
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // 创建导出选项。
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // 保存所有更改
    image.Save("C:\\temp\\output.gif", options);
}
```

### 也可以看看

* class [FileSource](../filesource/)
* 命名空间 [Aspose.PSD.Sources](../../aspose.psd.sources/)
* 部件 [Aspose.PSD](../../)


