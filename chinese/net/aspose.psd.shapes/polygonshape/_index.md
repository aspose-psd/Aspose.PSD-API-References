---
title: Class PolygonShape
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Shapes.PolygonShape 班级. 代表多边形形状
type: docs
weight: 5510
url: /zh/net/aspose.psd.shapes/polygonshape/
---
## PolygonShape class

代表多边形形状。

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | 初始化一个新的实例`PolygonShape`类. |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | 初始化一个新的实例`PolygonShape`类. |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | 初始化一个新的实例`PolygonShape`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | 获取对象的边界。 |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | 获取形状的中心。 |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | 获取结束形状点。 |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | 获取一个值，表示形状是否有段。 |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | 获取或设置一个表示形状是否闭合的值。 |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | 获取或设置曲线点。 |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | 获取形状段。 |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | 获取起始形状点。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | 获取对象的边界。 |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | 反转此形状的点顺序。 |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | 将指定的变换应用于形状。 |

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

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* 命名空间 [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* 部件 [Aspose.PSD](../../)


