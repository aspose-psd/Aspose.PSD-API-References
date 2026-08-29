---
title: "类 FileCreateSource"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Sources.FileCreateSource 类。表示用于创建的文件源"
type: docs
weight: 6090
url: /zh/net/aspose.psd.sources/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource class

表示用于创建的文件源。

```csharp
public sealed class FileCreateSource : FileSource
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | 初始化 `FileCreateSource` 类的新实例。 |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | 初始化 `FileCreateSource` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | 获取要创建的文件路径。 |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | 获取指示文件是否为临时的值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | 获取流容器。 |

## 示例

此示例演示了使用 Font 和 SolidBrush 类在 Image 表面上绘制字符串。示例创建了一个新 Image 并使用 Figures 和 GraphicsPath 绘制形状。

```csharp
[C#]

//创建 Image 的实例
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建并初始化 Graphics 类的实例
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //清除 Graphics 表面
    graphics.Clear(Color.Wheat);

    //创建 Font 的实例
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //创建具有红色的 SolidBrush 实例
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //绘制字符串
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // 创建导出选项。
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // 保存所有更改
    image.Save("C:\\temp\\output.gif", options);
}
```

### 另请参阅

* class [FileSource](../filesource/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


