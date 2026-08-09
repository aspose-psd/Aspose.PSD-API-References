---
title: "Graphics.DrawPath"
second_title: "Aspose.PSD for .NET API 参考"
description: "Graphics 方法。绘制一个 GraphicsPath"
type: docs
weight: 280
url: /zh/net/aspose.psd/graphics/drawpath/
---
{{< psd/tize >}}
## Graphics.DrawPath method

绘制一个 [`GraphicsPath`](../../graphicspath/)。

```csharp
public void DrawPath(Pen pen, GraphicsPath path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定路径的颜色、宽度和样式。 |
| path | GraphicsPath | 用于绘制的 [`GraphicsPath`](../../graphicspath/)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *path* 为 null。 |

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

* class [Pen](../../pen/)
* class [GraphicsPath](../../graphicspath/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


