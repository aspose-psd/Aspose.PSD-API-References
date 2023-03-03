---
title: Graphics.DrawRectangles
second_title: Aspose.PSD for .NET API 参考
description: Graphics 方法. 绘制一系列指定的矩形RectangleF结构.
type: docs
weight: 310
url: /zh/net/aspose.psd/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

绘制一系列指定的矩形[`RectangleF`](../../rectanglef/)结构.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)确定矩形轮廓的颜色、宽度和样式。 |
| rects | RectangleF[] | 阵列的[`RectangleF`](../../rectanglef/)表示要绘制的矩形的结构。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *rects*一片空白。 |

### 也可以看看

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* 命名空间 [Aspose.PSD](../../graphics/)
* 部件 [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

绘制一系列指定的矩形[`Rectangle`](../../rectangle/)结构.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)确定矩形轮廓的颜色、宽度和样式。 |
| rects | Rectangle[] | 阵列的[`Rectangle`](../../rectangle/)表示要绘制的矩形的结构。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *rects*一片空白。 |

### 例子

这个例子展示了 Pen 对象的创建和使用。该示例创建一个新图像并在图像表面绘制矩形。

```csharp
[C#]

//创建图像实例
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建一个Graphics实例并用Image对象初始化它
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //用白色清除图形表面
    graphics.Clear(Aspose.PSD.Color.White);

    //创建一个颜色为红色，宽度为 5 的 Pen 实例
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //创建一个HatchBrush实例并设置它的属性
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //创建Pen实例
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

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* 命名空间 [Aspose.PSD](../../graphics/)
* 部件 [Aspose.PSD](../../../)


