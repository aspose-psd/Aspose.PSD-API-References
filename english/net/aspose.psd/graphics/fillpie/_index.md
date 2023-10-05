---
title: Graphics.FillPie
second_title: Aspose.PSD for .NET API Reference
description: Graphics method. Fills the interior of a pie section defined by an ellipse specified by a RectangleF structure and two radial lines
type: docs
weight: 380
url: /net/aspose.psd/graphics/fillpie/
---
{{< psd/tize >}}
## FillPie(Brush, Rectangle, float, float) {#fillpie}

Fills the interior of a pie section defined by an ellipse specified by a [`RectangleF`](../../rectanglef/) structure and two radial lines.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) that determines the characteristics of the fill. |
| rect | Rectangle | [`Rectangle`](../../rectangle/) structure that represents the bounding rectangle that defines the ellipse from which the pie section comes. |
| startAngle | Single | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweepAngle | Single | Angle in degrees measured clockwise from the *startAngle* parameter to the second side of the pie section. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. |

### See Also

* class [Brush](../../brush/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

Fills the interior of a pie section defined by an ellipse specified by a [`RectangleF`](../../rectanglef/) structure and two radial lines.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) that determines the characteristics of the fill. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) structure that represents the bounding rectangle that defines the ellipse from which the pie section comes. |
| startAngle | Single | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweepAngle | Single | Angle in degrees measured clockwise from the *startAngle* parameter to the second side of the pie section. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. |

### See Also

* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) that determines the characteristics of the fill. |
| x | Single | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| y | Single | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| width | Single | Width of the bounding rectangle that defines the ellipse from which the pie section comes. |
| height | Single | Height of the bounding rectangle that defines the ellipse from which the pie section comes. |
| startAngle | Single | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweepAngle | Single | Angle in degrees measured clockwise from the *startAngle* parameter to the second side of the pie section. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. |

### See Also

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) that determines the characteristics of the fill. |
| x | Int32 | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| y | Int32 | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| width | Int32 | Width of the bounding rectangle that defines the ellipse from which the pie section comes. |
| height | Int32 | Height of the bounding rectangle that defines the ellipse from which the pie section comes. |
| startAngle | Int32 | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweepAngle | Int32 | Angle in degrees measured clockwise from the *startAngle* parameter to the second side of the pie section. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. |

### See Also

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


