---
title: Class RectangleShape
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Shapes.RectangleShape 班级. 代表一个矩形
type: docs
weight: 5530
url: /zh/net/aspose.psd.shapes/rectangleshape/
---
## RectangleShape class

代表一个矩形。

```csharp
public class RectangleShape : RectangleProjectedShape
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [RectangleShape](rectangleshape/#constructor)() | 初始化一个新的实例`RectangleShape`类. |
| [RectangleShape](rectangleshape/#constructor_1)(RectangleF) | 初始化一个新的实例`RectangleShape`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | 获取对象的边界。 |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | 获取形状的中心。 |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | 获取一个值，表示形状是否有段。 |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | 获取左下矩形点. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | 获取左上角矩形点。 |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | 获取矩形高度。 |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | 获取矩形宽度。 |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | 获取右下矩形点. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | 获取右上角矩形点。 |
| override [Segments](../../aspose.psd.shapes/rectangleshape/segments/) { get; } | 获取形状段。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | 获取对象的边界。 |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | 将指定的变换应用于形状。 |

### 例子

此示例创建一个新的 Image 并使用 Image 表面上的 Figures 和 GraphicsPath 绘制各种形状

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
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //将Shape添加到Figure对象
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //创建图类实例
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //将Shape添加到Figure对象
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //将Figure对象添加到GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //使用颜色为黑色的 Pen 对象绘制路径
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // 创建导出选项并初始化它们。
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // 保存所有更改。
    image.Save("c:\\temp\\output.bmp", options);
}
```

### 也可以看看

* class [RectangleProjectedShape](../rectangleprojectedshape/)
* 命名空间 [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* 部件 [Aspose.PSD](../../)


