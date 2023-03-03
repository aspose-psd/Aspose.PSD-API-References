---
title: Class Figure
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Figure 班级. 图形状的容器.
type: docs
weight: 1200
url: /zh/net/aspose.psd/figure/
---
## Figure class

图。形状的容器.

```csharp
public class Figure : ObjectWithBounds
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Figure](figure/)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | 获取或设置对象的边界。 |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | 获取或设置一个值，该值指示该图形是否闭合。只有在 where 第一个和最后一个图形的形状是连续形状的情况下，闭合图形才会有所不同。在这种情况下，第一个形状的第一个点将被 与最后一个形状的最后一个点连接起来。 |
| [Segments](../../aspose.psd/figure/segments/) { get; } | 获取整个图形段。 |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | 获取图形形状。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | 向图中添加形状。 |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | 向图中添加一系列形状。 |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | 获取对象的边界。 |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | 从图中删除形状。 |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | 从图中删除一系列形状。 |
| [Reverse](../../aspose.psd/figure/reverse/)() | 反转此图形形状顺序和形状点顺序。 |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | 将指定的变换应用于形状。 |

### 例子

此示例使用 GraphicsPath 和 Graphics 类在图像表面上创建和操作图形。示例创建一个新图像并在 GraphicsPath 类的帮助下绘制路径。最后调用 Graphics 类公开的 DrawPath 方法以在表面上呈现路径。最后将图像导出为 Tiff 文件格式。

```csharp
[C#]

//创建图像实例 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建并初始化Graphics类的实例
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //清除图形表面
    graphics.Clear(Color.Wheat);

    //创建GraphicsPath类的一个实例
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //创建图类实例
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //将Shapes添加到Figure对象
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //将Figure对象添加到GraphicsPath
    graphicspath.AddFigure(figure);

    //使用颜色为黑色的 Pen 对象绘制路径
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //创建一个 TiffOptions 实例并设置它的各种属性
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // 保存所有更改。
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### 也可以看看

* class [ObjectWithBounds](../objectwithbounds/)
* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


