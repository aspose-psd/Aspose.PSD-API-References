---
title: Graphics.DrawPie
second_title: Aspose.PSD for .NET API Reference
description: Graphics method. Draws a pie shape defined by an ellipse specified by a RectangleF structure and two radial lines
type: docs
weight: 280
url: /net/aspose.psd/graphics/drawpie/
---
{{< psd/tize >}}
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

Draws a pie shape defined by an ellipse specified by a [`RectangleF`](../../rectanglef/) structure and two radial lines.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the pie shape. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) structure that represents the bounding rectangle that defines the ellipse from which the pie shape comes. |
| startAngle | Single | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweepAngle | Single | Angle measured in degrees clockwise from the *startAngle* parameter to the second side of the pie shape. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. |

### See Also

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../graphics/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines.

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the pie shape. |
| x | Single | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| y | Single | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| width | Single | Width of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| height | Single | Height of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| startAngle | Single | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweepAngle | Single | Angle measured in degrees clockwise from the *startAngle* parameter to the second side of the pie shape. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. |

### See Also

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../graphics/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

Draws a pie shape defined by an ellipse specified by a [`Rectangle`](../../rectangle/) structure and two radial lines.

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the pie shape. |
| rect | Rectangle | [`Rectangle`](../../rectangle/) structure that represents the bounding rectangle that defines the ellipse from which the pie shape comes. |
| startAngle | Single | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweepAngle | Single | Angle measured in degrees clockwise from the *startAngle* parameter to the second side of the pie shape. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. |

### See Also

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../graphics/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines.

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the pie shape. |
| x | Int32 | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| y | Int32 | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| width | Int32 | Width of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| height | Int32 | Height of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| startAngle | Int32 | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweepAngle | Int32 | Angle measured in degrees clockwise from the *startAngle* parameter to the second side of the pie shape. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. |

### See Also

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../graphics/)
* assembly [Aspose.PSD](../../../)


