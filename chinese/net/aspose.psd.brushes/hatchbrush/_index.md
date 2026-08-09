---
title: "类 HatchBrush"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Brushes.HatchBrush 类。定义具有 hatch style、前景色和背景色的矩形刷。此类不能被继承"
type: docs
weight: 130
url: /zh/net/aspose.psd.brushes/hatchbrush/
---
{{< psd/tize >}}
## HatchBrush class

定义具有交叉线样式、前景色和背景色的矩形画笔。此类不可继承。

```csharp
public sealed class HatchBrush : Brush
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [HatchBrush](hatchbrush/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | 获取或设置 hatch 线之间空间的颜色。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | 获取或设置 hatch 线的颜色。 |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | 获取或设置此刷的 hatch 样式。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 获取或设置画刷的不透明度。值应在 0 到 1 之间。0 表示画刷完全可见，1 表示画刷完全不透明。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 创建当前 [`Brush`](../../aspose.psd/brush/) 的新深度克隆。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 释放当前实例。 |

## 示例

此示例展示了 Pen 对象的创建和使用。示例创建了一个新 Image 并在 Image 表面上绘制 Rectangles。

```csharp
[C#]

//创建 Image 的实例
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建 Graphics 实例并使用 Image 对象进行初始化
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //使用白色清除 Graphics 表面
    graphics.Clear(Aspose.PSD.Color.White);

    //创建一个 Pen 实例，颜色为 红色，宽度为 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //创建一个 HatchBrush 实例并设置其属性
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //创建一个 Pen 实例
    //使用 HatchBrush 对象和宽度进行初始化
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //通过指定 Pen 对象绘制矩形
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //通过指定 Pen 对象绘制矩形
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // 创建导出选项并对其进行初始化。
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // 保存所有更改。
    image.Save("c:\\temp\\output.jp2", options);
}
```

### 另请参阅

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


