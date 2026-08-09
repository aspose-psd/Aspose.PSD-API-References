---
title: "Graphics.DrawCurve"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Graphics-Methode. Zeichnet eine kardinale Spline durch ein angegebenes Array von PointF-Strukturen. Diese Methode verwendet eine Standardspannung von 0.5."
type: docs
weight: 210
url: /de/net/aspose.psd/graphics/drawcurve/
---
{{< psd/tize >}}
## DrawCurve(Pen, PointF[]) {#drawcurve}

Zeichnet eine kardinale Spline durch ein angegebenes Array von [`PointF`](../../pointf/) Strukturen. Diese Methode verwendet eine Standardspannung von 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | PointF[] | Array von [`PointF`](../../pointf/) Strukturen, die die Spline definieren. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Zeichnet eine kardinale Spline durch ein angegebenes Array von [`PointF`](../../pointf/) Strukturen unter Verwendung einer angegebenen Spannung.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | PointF[] | Array von [`PointF`](../../pointf/) Strukturen, die die Punkte darstellen, die die Kurve definieren. |
| Spannung | Single | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Zeichnet eine kardinale Spline durch ein angegebenes Array von [`PointF`](../../pointf/) Strukturen. Die Zeichnung beginnt versetzt vom Anfang des Arrays. Diese Methode verwendet eine Standardspannung von 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | PointF[] | Array von [`PointF`](../../pointf/) Strukturen, die die Spline definieren. |
| offset | Int32 | Versatz vom ersten Element im Array des *points*-Parameters zum Startpunkt der Kurve. |
| numberOfSegments | Int32 | Anzahl der Segmente nach dem Ausgangspunkt, die in die Kurve einbezogen werden sollen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Zeichnet eine kardinale Spline durch ein angegebenes Array von [`PointF`](../../pointf/) Strukturen unter Verwendung einer angegebenen Spannung. Die Zeichnung beginnt versetzt vom Anfang des Arrays.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | PointF[] | Array von [`PointF`](../../pointf/) Strukturen, die die Spline definieren. |
| offset | Int32 | Versatz vom ersten Element im Array des *points*-Parameters zum Startpunkt der Kurve. |
| numberOfSegments | Int32 | Anzahl der Segmente nach dem Ausgangspunkt, die in die Kurve einbezogen werden sollen. |
| Spannung | Single | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Zeichnet eine kardinale Spline durch ein angegebenes Array von [`Point`](../../point/) Strukturen.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | Point[] | Array von [`Point`](../../point/) Strukturen, die die Spline definieren. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Zeichnet eine kardinale Spline durch ein angegebenes Array von [`Point`](../../point/) Strukturen unter Verwendung einer angegebenen Spannung.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | Point[] | Array von [`Point`](../../point/) Strukturen, die die Spline definieren. |
| Spannung | Single | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Zeichnet eine kardinale Spline durch ein angegebenes Array von [`Point`](../../point/) Strukturen unter Verwendung einer angegebenen Spannung.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | Point[] | Array von [`Point`](../../point/) Strukturen, die die Spline definieren. |
| offset | Int32 | Versatz vom ersten Element im Array des *points*-Parameters zum Startpunkt der Kurve. |
| numberOfSegments | Int32 | Anzahl der Segmente nach dem Ausgangspunkt, die in die Kurve einbezogen werden sollen. |
| Spannung | Single | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


