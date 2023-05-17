---
title: Graphics.DrawPolygon
second_title: Aspose.PSD for .NET API Reference
description: Graphics method. Draws a polygon defined by an array of PointF structures
type: docs
weight: 290
url: /net/aspose.psd/graphics/drawpolygon/
---
{{< psd/tize >}}
## DrawPolygon(Pen, PointF[]) {#drawpolygon}

Draws a polygon defined by an array of [`PointF`](../../pointf/) structures.

```csharp
public void DrawPolygon(Pen pen, PointF[] points)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the polygon. |
| points | PointF[] | Array of [`PointF`](../../pointf/) structures that represent the vertices of the polygon. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. -or- *points* is null. |

### See Also

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../graphics/)
* assembly [Aspose.PSD](../../../)

---

## DrawPolygon(Pen, Point[]) {#drawpolygon_1}

Draws a polygon defined by an array of [`Point`](../../point/) structures.

```csharp
public void DrawPolygon(Pen pen, Point[] points)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the polygon. |
| points | Point[] | Array of [`Point`](../../point/) structures that represent the vertices of the polygon. |

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


