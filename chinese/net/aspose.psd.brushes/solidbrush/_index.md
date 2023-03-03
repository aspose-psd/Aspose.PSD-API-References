---
title: Class SolidBrush
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Brushes.SolidBrush 班级. 实心画笔用于连续绘制特定颜色此类不能被继承
type: docs
weight: 200
url: /zh/net/aspose.psd.brushes/solidbrush/
---
## SolidBrush class

实心画笔用于连续绘制特定颜色。此类不能被继承。

```csharp
public sealed class SolidBrush : Brush
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | 初始化一个新的实例`SolidBrush`类. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | 初始化一个新的实例`SolidBrush`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | 获取或设置画笔颜色。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 获取或设置画笔不透明度。该值应介于 0 和 1 之间。值为 0 表示画笔完全可见，值为 1 表示画笔完全不透明。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 创建当前的新深度克隆[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 处理当前实例。 |

### 例子

此示例使用 Graphics 类在 Image 表面上创建原始形状。为了演示该操作，该示例创建了一个 PSD 格式的新图像，并使用 Graphics 类公开的 Draw 方法在图像表面绘制原始形状，然后将其导出为 PSD 文件格式。

```csharp
[C#]

//创建图像实例 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建并初始化Graphics类的实例
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //清除图形表面
    graphics.Clear(Color.Wheat);

    //通过指定具有黑色的 Pen 对象绘制弧形， 
    //围绕圆弧、起始角和扫描角的矩形
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //通过指定具有蓝色和坐标点的 Pen 对象来绘制贝塞尔曲线。
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //通过指定具有绿色和点数组的 Pen 对象来绘制曲线
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //使用 Pen 对象和周围的矩形绘制一个椭圆
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //画一条线 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //绘制饼图
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //通过指定具有红色和点数组的 Pen 对象来绘制多边形
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //画一个矩形
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //创建一个SolidBrush对象并设置它的各种属性
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //在特定点使用 SolidBrush 对象和字体绘制字符串
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //创建一个PngOptions实例并设置它的各种属性
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // 保存所有更改。
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### 也可以看看

* class [Brush](../../aspose.psd/brush/)
* 命名空间 [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* 部件 [Aspose.PSD](../../)


