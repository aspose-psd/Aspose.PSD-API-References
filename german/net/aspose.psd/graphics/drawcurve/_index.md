---
title: Graphics.DrawCurve
second_title: Aspose.PSD für .NET-API-Referenz
description: Graphics methode. Zeichnet einen kardinalen Spline durch ein angegebenes Array vonPointF Strukturen. Diese Methode verwendet eine Standardspannung von 05.
type: docs
weight: 200
url: /de/net/aspose.psd/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`PointF`](../../pointf/) Strukturen. Diese Methode verwendet eine Standardspannung von 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | PointF[] | Anordnung von[`PointF`](../../pointf/) Strukturen, die den Spline definieren. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist Null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`PointF`](../../pointf/) Strukturen mit einer bestimmten Spannung.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | PointF[] | Anordnung von[`PointF`](../../pointf/) Strukturen, die die Punkte darstellen, die die Kurve definieren. |
| tension | Single | Wert größer oder gleich 0,0 F, der die Spannung der Kurve angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist Null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`PointF`](../../pointf/) Strukturen. Die Zeichnung beginnt versetzt vom Anfang des Arrays. Diese Methode verwendet eine Standardspannung von 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | PointF[] | Anordnung von[`PointF`](../../pointf/) Strukturen, die den Spline definieren. |
| offset | Int32 | Versatz vom ersten Element im Array der*points* Parameter zum Anfangspunkt der Kurve. |
| numberOfSegments | Int32 | Anzahl der Segmente nach dem Startpunkt, die in die Kurve aufgenommen werden sollen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist Null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`PointF`](../../pointf/) Strukturen mit einer bestimmten Spannung. Die Zeichnung beginnt versetzt vom Anfang des Arrays.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | PointF[] | Anordnung von[`PointF`](../../pointf/) Strukturen, die den Spline definieren. |
| offset | Int32 | Versatz vom ersten Element im Array der*points* Parameter zum Anfangspunkt der Kurve. |
| numberOfSegments | Int32 | Anzahl der Segmente nach dem Startpunkt, die in die Kurve aufgenommen werden sollen. |
| tension | Single | Wert größer oder gleich 0,0 F, der die Spannung der Kurve angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist Null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`Point`](../../point/) Strukturen.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | Point[] | Anordnung von[`Point`](../../point/) Strukturen, die den Spline definieren. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist Null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`Point`](../../point/) Strukturen mit einer bestimmten Spannung.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | Point[] | Anordnung von[`Point`](../../point/) Strukturen, die den Spline definieren. |
| tension | Single | Wert größer oder gleich 0,0 F, der die Spannung der Kurve angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist Null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`Point`](../../point/) Strukturen mit einer bestimmten Spannung.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | Point[] | Anordnung von[`Point`](../../point/) Strukturen, die den Spline definieren. |
| offset | Int32 | Versatz vom ersten Element im Array der*points* Parameter zum Anfangspunkt der Kurve. |
| numberOfSegments | Int32 | Anzahl der Segmente nach dem Startpunkt, die in die Kurve aufgenommen werden sollen. |
| tension | Single | Wert größer oder gleich 0,0 F, der die Spannung der Kurve angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist Null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)


