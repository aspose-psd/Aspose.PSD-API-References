---
title: "类 PieShape"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Shapes.PieShape 类。表示饼形"
type: docs
weight: 6000
url: /zh/net/aspose.psd.shapes/pieshape/
---
{{< psd/tize >}}
## PieShape class

表示饼形。

```csharp
public class PieShape : EllipseShape
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PieShape](pieshape/#constructor)() | 初始化 `PieShape` 类的新实例。 |
| [PieShape](pieshape/#constructor_1)(RectangleF, float, float) | 初始化 `PieShape` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | 获取对象的边界。 |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | 获取形状的中心。 |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | 获取指示形状是否具有段的值。 |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | 获取左下矩形点。 |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | 获取左上矩形点。 |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | 获取矩形高度。 |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | 获取矩形的宽度。 |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | 获取矩形右下角点。 |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | 获取矩形右上角点。 |
| override [Segments](../../aspose.psd.shapes/pieshape/segments/) { get; } | 获取形状段。 |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | 获取或设置起始角度。 |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | 获取或设置扫掠角度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | 获取对象的边界。 |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | 将指定的变换应用于形状。 |

## 示例

此示例在 Image 表面上创建一个新 Image，并使用 Figures 和 GraphicsPath 绘制各种形状。

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
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //将 Shape 添加到 Figure 对象。
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //创建 Figure 类的实例
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //将 Shape 添加到 Figure 对象。
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //将 Figure 对象添加到 GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //使用颜色为 Black 的 Pen 对象绘制路径
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // 创建导出选项并对其进行初始化。
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // 保存所有更改。
    image.Save("c:\\temp\\output.bmp", options);
}
```

### 另请参阅

* class [EllipseShape](../ellipseshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


