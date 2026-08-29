---
title: "Graphics.DrawRectangles"
second_title: "Aspose.PSD for .NET API 参考"
description: "Graphics 方法。绘制一系列由 RectangleF 结构指定的矩形。"
type: docs
weight: 320
url: /zh/net/aspose.psd/graphics/drawrectangles/
---
{{< psd/tize >}}
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

绘制一系列由 [`RectangleF`](../../rectanglef/) 结构指定的矩形。

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定矩形轮廓的颜色、宽度和样式。 |
| rects | RectangleF[] | [`RectangleF`](../../rectanglef/) 结构数组，表示要绘制的矩形。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *rects* 为 null。 |

### 另请参阅

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

绘制一系列由 [`Rectangle`](../../rectangle/) 结构指定的矩形。

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定矩形轮廓的颜色、宽度和样式。 |
| rects | Rectangle[] | [`Rectangle`](../../rectangle/) 结构数组，表示要绘制的矩形。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *rects* 为 null。 |

## 示例

此示例展示了 Pen 对象的创建和使用。示例创建了一个新 Image 并在 Image 表面上绘制 Rectangles。

```csharp
[C#]

//创建 Image 的实例
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建 Graphics 实例并使用 Image 对象进行初始化
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //使用白色清除 Graphics 表面
    graphics.Clear(Aspose.PSD.Color.White);

    //创建一个 Pen 实例，颜色为 红色，宽度为 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //创建一个 HatchBrush 实例并设置其属性
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //创建一个 Pen 实例
    //使用 HatchBrush 对象和宽度进行初始化
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //通过指定 Pen 对象绘制矩形
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //通过指定 Pen 对象绘制矩形
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // 创建导出选项并对其进行初始化。
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // 保存所有更改。
    image.Save("c:\\temp\\output.jp2", options);
}
```

### 另请参阅

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


