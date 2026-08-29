---
title: "类 Figure"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Figure 类。图形。形状的容器"
type: docs
weight: 1210
url: /zh/net/aspose.psd/figure/
---
{{< psd/tize >}}
## Figure class

图形。形状的容器。

```csharp
public class Figure : ObjectWithBounds
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Figure](figure/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | 获取或设置对象的边界。 |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | 获取或设置一个值，指示此图形是否闭合。闭合图形仅在首个和最后一个图形的形状是连续形状的情况下才会产生差异。在这种情况下，首个形状的第一个点将通过一条直线与最后一个形状的最后一点相连。 |
| [Segments](../../aspose.psd/figure/segments/) { get; } | 获取整个图形的段。 |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | 获取图形的形状。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | 向图形添加形状。 |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | 向图形添加一系列形状。 |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | 获取对象的边界。 |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | 从图形中移除形状。 |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | 从图形中移除一系列形状。 |
| [Reverse](../../aspose.psd/figure/reverse/)() | 反转此图形的形状顺序和形状点顺序。 |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | 将指定的变换应用于形状。 |

## 示例

此示例使用 GraphicsPath 和 Graphics 类在图像表面上创建和操作图形。示例创建一个新 Image 并借助 GraphicsPath 类绘制路径。最后调用 Graphics 类公开的 DrawPath 方法在表面上渲染路径。最终图像导出为 Tiff 文件格式。

```csharp
[C#]

//创建 Image 的实例
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建并初始化 Graphics 类的实例
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //清除 Graphics 表面
    graphics.Clear(Color.Wheat);

    //创建 GraphicsPath 类的实例
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //创建 Figure 类的实例
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //向 Figure 对象添加形状
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //将 Figure 对象添加到 GraphicsPath
    graphicspath.AddFigure(figure);

    //使用颜色为 Black 的 Pen 对象绘制路径
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //创建 TiffOptions 的实例并设置其各种属性
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // 保存所有更改。
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### 另请参阅

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


