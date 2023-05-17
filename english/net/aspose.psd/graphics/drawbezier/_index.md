---
title: Graphics.DrawBezier
second_title: Aspose.PSD for .NET API Reference
description: Graphics method. Draws a Bézier spline defined by four ordered pairs of coordinates that represent points
type: docs
weight: 170
url: /net/aspose.psd/graphics/drawbezier/
---
{{< psd/tize >}}
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Draws a Bézier spline defined by four ordered pairs of coordinates that represent points.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the curve. |
| x1 | Single | The x-coordinate of the starting point of the curve. |
| y1 | Single | The y-coordinate of the starting point of the curve. |
| x2 | Single | The x-coordinate of the first control point of the curve. |
| y2 | Single | The y-coordinate of the first control point of the curve. |
| x3 | Single | The x-coordinate of the second control point of the curve. |
| y3 | Single | The y-coordinate of the second control point of the curve. |
| x4 | Single | The x-coordinate of the ending point of the curve. |
| y4 | Single | The y-coordinate of the ending point of the curve. |

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

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Draws a Bézier spline defined by four [`PointF`](../../pointf/) structures.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the curve. |
| pt1 | PointF | [`PointF`](../../pointf/) structure that represents the starting point of the curve. |
| pt2 | PointF | [`PointF`](../../pointf/) structure that represents the first control point for the curve. |
| pt3 | PointF | [`PointF`](../../pointf/) structure that represents the second control point for the curve. |
| pt4 | PointF | [`PointF`](../../pointf/) structure that represents the ending point of the curve. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. |

### See Also

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../graphics/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Draws a Bézier spline defined by four [`Point`](../../point/) structures.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) structure that determines the color, width, and style of the curve. |
| pt1 | Point | [`Point`](../../point/) structure that represents the starting point of the curve. |
| pt2 | Point | [`Point`](../../point/) structure that represents the first control point for the curve. |
| pt3 | Point | [`Point`](../../point/) structure that represents the second control point for the curve. |
| pt4 | Point | [`Point`](../../point/) structure that represents the ending point of the curve. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. |

### See Also

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../graphics/)
* assembly [Aspose.PSD](../../../)


