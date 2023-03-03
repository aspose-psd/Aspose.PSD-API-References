---
title: Figure.AddShapes
second_title: Aspose.PSD for .NET API 参考
description: Figure 方法. 向图中添加一系列形状
type: docs
weight: 70
url: /zh/net/aspose.psd/figure/addshapes/
---
## Figure.AddShapes method

向图中添加一系列形状。

```csharp
public void AddShapes(Shape[] shapes)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| shapes | Shape[] | 要添加的形状。 |

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

* class [Shape](../../shape/)
* class [Figure](../)
* 命名空间 [Aspose.PSD](../../figure/)
* 部件 [Aspose.PSD](../../../)


