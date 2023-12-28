---
title: Graphics.DrawArc
second_title: Aspose.PSD for .NET API Reference
description: Graphics method. Draws an arc representing a portion of an ellipse specified by a pair of coordinates a width and a height
type: docs
weight: 170
url: /net/aspose.psd/graphics/drawarc/
---
{{< psd/tize >}}
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the arc. |
| x | Single | The x-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| y | Single | The y-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| width | Single | Width of the rectangle that defines the ellipse. |
| height | Single | Height of the rectangle that defines the ellipse. |
| startAngle | Single | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | Single | Angle in degrees measured clockwise from the *startAngle* parameter to ending point of the arc. |

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

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

Draws an arc representing a portion of an ellipse specified by a [`RectangleF`](../../rectanglef/) structure.

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the arc. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) structure that defines the boundaries of the ellipse. |
| startAngle | Single | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | Single | Angle in degrees measured clockwise from the *startAngle* parameter to ending point of the arc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null |

### See Also

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../graphics/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the arc. |
| x | Int32 | The x-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| y | Int32 | The y-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| width | Int32 | Width of the rectangle that defines the ellipse. |
| height | Int32 | Height of the rectangle that defines the ellipse. |
| startAngle | Int32 | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | Int32 | Angle in degrees measured clockwise from the *startAngle* parameter to ending point of the arc. |

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

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

Draws an arc representing a portion of an ellipse specified by a [`Rectangle`](../../rectangle/) structure.

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the arc. |
| rect | Rectangle | [`RectangleF`](../../rectanglef/) structure that defines the boundaries of the ellipse. |
| startAngle | Single | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | Single | Angle in degrees measured clockwise from the *startAngle* parameter to ending point of the arc. |

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


