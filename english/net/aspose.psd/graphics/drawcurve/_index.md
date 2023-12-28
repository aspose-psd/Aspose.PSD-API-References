---
title: Graphics.DrawCurve
second_title: Aspose.PSD for .NET API Reference
description: Graphics method. Draws a cardinal spline through a specified array of PointF structures. This method uses a default tension of 0.5
type: docs
weight: 210
url: /net/aspose.psd/graphics/drawcurve/
---
{{< psd/tize >}}
## DrawCurve(Pen, PointF[]) {#drawcurve}

Draws a cardinal spline through a specified array of [`PointF`](../../pointf/) structures. This method uses a default tension of 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and height of the curve. |
| points | PointF[] | Array of [`PointF`](../../pointf/) structures that define the spline. |

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

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Draws a cardinal spline through a specified array of [`PointF`](../../pointf/) structures using a specified tension.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and height of the curve. |
| points | PointF[] | Array of [`PointF`](../../pointf/) structures that represent the points that define the curve. |
| tension | Single | Value greater than or equal to 0.0F that specifies the tension of the curve. |

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

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Draws a cardinal spline through a specified array of [`PointF`](../../pointf/) structures. The drawing begins offset from the beginning of the array. This method uses a default tension of 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and height of the curve. |
| points | PointF[] | Array of [`PointF`](../../pointf/) structures that define the spline. |
| offset | Int32 | Offset from the first element in the array of the *points* parameter to the starting point in the curve. |
| numberOfSegments | Int32 | Number of segments after the starting point to include in the curve. |

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

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Draws a cardinal spline through a specified array of [`PointF`](../../pointf/) structures using a specified tension. The drawing begins offset from the beginning of the array.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and height of the curve. |
| points | PointF[] | Array of [`PointF`](../../pointf/) structures that define the spline. |
| offset | Int32 | Offset from the first element in the array of the *points* parameter to the starting point in the curve. |
| numberOfSegments | Int32 | Number of segments after the starting point to include in the curve. |
| tension | Single | Value greater than or equal to 0.0F that specifies the tension of the curve. |

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

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Draws a cardinal spline through a specified array of [`Point`](../../point/) structures.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and height of the curve. |
| points | Point[] | Array of [`Point`](../../point/) structures that define the spline. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. -or- *points* is null. |

### See Also

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../graphics/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Draws a cardinal spline through a specified array of [`Point`](../../point/) structures using a specified tension.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and height of the curve. |
| points | Point[] | Array of [`Point`](../../point/) structures that define the spline. |
| tension | Single | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. -or- *points* is null. |

### See Also

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../graphics/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Draws a cardinal spline through a specified array of [`Point`](../../point/) structures using a specified tension.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and height of the curve. |
| points | Point[] | Array of [`Point`](../../point/) structures that define the spline. |
| offset | Int32 | Offset from the first element in the array of the *points* parameter to the starting point in the curve. |
| numberOfSegments | Int32 | Number of segments after the starting point to include in the curve. |
| tension | Single | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. -or- *points* is null. |

### See Also

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../graphics/)
* assembly [Aspose.PSD](../../../)


