---
title: Pen
second_title: Aspose.PSD for .NET API 参考
description: 定义用于绘制直线曲线和图形的对象
type: docs
weight: 5080
url: /zh/net/aspose.psd/pen/
---
## Pen class

定义用于绘制直线、曲线和图形的对象。

```csharp
public class Pen : TransparencySupporter
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Pen](pen#constructor)(Brush) | 使用指定的[`Brush`](./brush)初始化[`Pen`](../pen)类的新实例。 |
| [Pen](pen#constructor_2)(Color) | 使用指定颜色初始化[`Pen`](../pen)类的新实例。 |
| [Pen](pen#constructor_1)(Brush, float) | 使用指定的[`Brush`](./brush)初始化[`Pen`](../pen)类的新实例[`Width`](./width)。 |
| [Pen](pen#constructor_3)(Color, float) | 用指定的[`Color`](./color)初始化[`Pen`](../pen)类的新实例和[`Width`](./width)属性。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment) { get; set; } | 获取或设置此[`Pen`](../pen)的对齐方式。 |
| [Brush](../../aspose.psd/pen/brush) { get; set; } | 获取或设置确定此[`Pen`](../pen)属性的[`Brush`](./brush)。 |
| [Color](../../aspose.psd/pen/color) { get; set; } | 获取或设置此[`Pen`](../pen)的颜色。 |
| [CompoundArray](../../aspose.psd/pen/compoundarray) { get; set; } | 获取或设置指定复合笔的值数组。复合笔绘制由平行线和空格组成的复合线。 |
| [CustomEndCap](../../aspose.psd/pen/customendcap) { get; set; } | 获取或设置一个自定义上限以在使用此[`Pen`](../pen)绘制的线条的末尾使用。 |
| [CustomStartCap](../../aspose.psd/pen/customstartcap) { get; set; } | 获取或设置一个自定义上限以在使用此[`Pen`](../pen)绘制的线条的开头使用。 |
| [DashCap](../../aspose.psd/pen/dashcap) { get; set; } | 获取或设置在组成用此[`Pen`](../pen)绘制的虚线的虚线末尾使用的帽子样式。 |
| [DashOffset](../../aspose.psd/pen/dashoffset) { get; set; } | 获取或设置从线条起点到虚线图案起点的距离。 |
| [DashPattern](../../aspose.psd/pen/dashpattern) { get; set; } | 获取或设置自定义破折号和空格的数组。 |
| [DashStyle](../../aspose.psd/pen/dashstyle) { get; set; } | 获取或设置使用此[`Pen`](../pen)绘制的虚线的样式。 |
| [EndCap](../../aspose.psd/pen/endcap) { get; set; } | 获取或设置使用此[`Pen`](../pen)绘制的线条末端使用的帽子样式。 |
| [LineJoin](../../aspose.psd/pen/linejoin) { get; set; } | 获取或设置使用此[`Pen`](../pen)绘制的两条连续线的末端的连接样式。 |
| [MiterLimit](../../aspose.psd/pen/miterlimit) { get; set; } | 获取或设置斜接角上连接的厚度限制。 |
| [Opacity](../../aspose.psd/transparencysupporter/opacity) { get; set; } | 获取或设置对象的不透明度。该值应介于 0 和 1 之间。值 0 表示对象完全可见，值 1 表示对象完全不透明。 |
| [PenType](../../aspose.psd/pen/pentype) { get; } | 获取使用此[`Pen`](../pen)绘制的线条样式。 |
| [StartCap](../../aspose.psd/pen/startcap) { get; set; } | 获取或设置使用此[`Pen`](../pen)绘制的线条开头使用的帽子样式。 |
| [Transform](../../aspose.psd/pen/transform) { get; set; } | 获取或设置此[`Pen`](../pen)的几何变换的副本。 |
| [Width](../../aspose.psd/pen/width) { get; set; } | 获取或设置此[`Pen`](../pen)的宽度，以用于绘图的 Graphics 对象为单位。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform#multiplytransform)(Matrix) | 将此[`Pen`](../pen)的变换矩阵乘以指定的[`Matrix`](../matrix)。 |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | 以指定顺序将此[`Pen`](../pen)的变换矩阵乘以指定的[`Matrix`](../matrix). |
| [ResetTransform](../../aspose.psd/pen/resettransform)() | 将此[`Pen`](../pen)的几何变换矩阵重置为恒等式。 |
| [RotateTransform](../../aspose.psd/pen/rotatetransform#rotatetransform)(float) | 将局部几何变换旋转指定角度。此方法将旋转添加到变换中。 |
| [RotateTransform](../../aspose.psd/pen/rotatetransform#rotatetransform_1)(float, MatrixOrder) | 按指定顺序将局部几何变换旋转指定角度。 |
| [ScaleTransform](../../aspose.psd/pen/scaletransform#scaletransform)(float, float) | 按指定因子缩放局部几何变换。此方法将缩放矩阵添加到转换中。 |
| [ScaleTransform](../../aspose.psd/pen/scaletransform#scaletransform_1)(float, float, MatrixOrder) | 按指定顺序按指定因子缩放局部几何变换。 |
| [SetLineCap](../../aspose.psd/pen/setlinecap)(LineCap, LineCap, DashCap) | 设置确定用于结束此[`Pen`](../pen)绘制的线条的帽子样式的值。 |
| [TranslateTransform](../../aspose.psd/pen/translatetransform#translatetransform)(float, float) | 按指定尺寸平移局部几何变换。此方法将转换添加到转换之前。 |
| [TranslateTransform](../../aspose.psd/pen/translatetransform#translatetransform_1)(float, float, MatrixOrder) | 按指定顺序按指定尺寸平移局部几何变换。 |

### 例子

这个例子展示了 Pen 对象的创建和使用。该示例创建一个新图像并在图像表面上绘制矩形。

```csharp
[C#]

//创建一个Image实例
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建一个Graphics实例并用Image对象初始化
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //用白色清除图形表面
    graphics.Clear(Aspose.PSD.Color.White);

    //创建一个Pen实例，颜色为红色，宽度为5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //创建一个HatchBrush实例并设置它的属性
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //创建一个Pen实例
    //用 HatchBrush 对象和宽度初始化它
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //通过指定Pen对象绘制矩形
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //通过指定Pen对象绘制矩形
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // 创建导出选项并初始化它们。
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // 保存所有更改。
    image.Save("c:\\temp\\output.jp2", options);
}
```

### 也可以看看

* class [TransparencySupporter](../transparencysupporter)
* 命名空间 [Aspose.PSD](../../aspose.psd)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
