---
title: Graphics.DrawRectangles
second_title: Aspose.PSD for .NET API Reference
description: Graphics method. Draws a series of rectangles specified by RectangleF structures
type: docs
weight: 320
url: /net/aspose.psd/graphics/drawrectangles/
---
{{< psd/tize >}}
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Draws a series of rectangles specified by [`RectangleF`](../../rectanglef/) structures.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the outlines of the rectangles. |
| rects | RectangleF[] | Array of [`RectangleF`](../../rectanglef/) structures that represent the rectangles to draw. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. -or- *rects* is null. |

### See Also

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Draws a series of rectangles specified by [`Rectangle`](../../rectangle/) structures.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the outlines of the rectangles. |
| rects | Rectangle[] | Array of [`Rectangle`](../../rectangle/) structures that represent the rectangles to draw. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. -or- *rects* is null. |

## Examples

This example shows the creation and usage Pen objects. The example creates a new Image and draws Rectangles on Image surface.

```csharp
[C#]

//Create an instance of Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Create an instance of Graphics and initialize it with Image object
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Clear the Graphics sutface with White Color
    graphics.Clear(Aspose.PSD.Color.White);

    //Create an instance of Pen with color Red and width 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Create an instance of HatchBrush and set its properties
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Create an instance of Pen
    //initialize it with HatchBrush object and width
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Draw Rectangles by specifying Pen object
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Draw Rectangles by specifying Pen object
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Create export options and initialize them.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // save all changes.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### See Also

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


