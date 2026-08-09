---
title: "类 Pen"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Pen 类。定义用于绘制线条、曲线和图形的对象。"
type: docs
weight: 5690
url: /zh/net/aspose.psd/pen/
---
{{< psd/tize >}}
## Pen class

定义用于绘制直线、曲线和图形的对象。

```csharp
public class Pen : TransparencySupporter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | 使用指定的[`Brush`](./brush/)初始化 `Pen` 类的新实例。 |
| [Pen](pen/#constructor_2)(Color) | 使用指定的颜色初始化 `Pen` 类的新实例。 |
| [Pen](pen/#constructor_1)(Brush, float) | 使用指定的[`Brush`](./brush/)和[`Width`](./width/)初始化 `Pen` 类的新实例。 |
| [Pen](pen/#constructor_3)(Color, float) | 使用指定的[`Color`](./color/)和[`Width`](./width/)属性初始化 `Pen` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | 获取或设置此 `Pen` 的对齐方式。 |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | 获取或设置决定此 `Pen` 属性的[`Brush`](./brush/)。 |
| [Color](../../aspose.psd/pen/color/) { get; set; } | 获取或设置此 `Pen` 的颜色。 |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | 获取或设置指定复合笔的值数组。复合笔绘制由平行线段和间隔组成的复合线。 |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | 获取或设置使用此 `Pen` 绘制的线条末端的自定义帽。 |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | 获取或设置使用此 `Pen` 绘制的线条起始端的自定义帽。 |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | 获取或设置此 `Pen` 绘制的虚线末端的帽样式。 |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | 获取或设置从线条起点到虚线模式起始的距离。 |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | 获取或设置自定义虚线和间隔的数组。 |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | 获取或设置此 `Pen` 绘制的虚线的样式。 |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | 获取或设置此 `Pen` 绘制的线条末端的帽样式。 |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | 获取或设置此 `Pen` 绘制的两条连续线段端点的连接样式。 |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | 获取或设置斜接角处连接的厚度限制。 |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | 获取或设置对象的不透明度。该值应在 0 到 1 之间。0 表示对象完全可见，1 表示对象完全不透明。 |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | 获取使用此 `Pen` 绘制的线条样式。 |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | 获取或设置使用此 `Pen` 绘制的线条起点的端帽样式。 |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | 获取或设置此 `Pen` 的几何变换的副本。 |
| [Width](../../aspose.psd/pen/width/) { get; set; } | 获取或设置此 `Pen` 的宽度，单位为用于绘图的 Graphics 对象的单位。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | 将此 `Pen` 的变换矩阵乘以指定的 [`Matrix`](../matrix/)。 |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | 按指定顺序将此 `Pen` 的变换矩阵乘以指定的 [`Matrix`](../matrix/)。 |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | 将此 `Pen` 的几何变换矩阵重置为单位矩阵。 |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | 按指定角度旋转本地几何变换。此方法将在变换前预先添加旋转。 |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | 按指定顺序以指定角度旋转本地几何变换。 |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | 按指定因子缩放本地几何变换。此方法将在变换前预先添加缩放矩阵。 |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | 按指定顺序以指定因子缩放本地几何变换。 |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | 设置决定此 `Pen` 绘制的线条结束端帽样式的值。 |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | 按指定尺寸平移本地几何变换。此方法将在变换前预先添加平移。 |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | 按指定顺序以指定尺寸平移本地几何变换。 |

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

* class [TransparencySupporter](../transparencysupporter/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


