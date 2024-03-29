---
title: Graphics.DrawBezier
second_title: Aspose.PSD für .NET-API-Referenz
description: Graphics methode. Zeichnet einen BézierSpline der durch vier geordnete Koordinatenpaare definiert ist die Punkte darstellen.
type: docs
weight: 170
url: /de/net/aspose.psd/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Zeichnet einen Bézier-Spline, der durch vier geordnete Koordinatenpaare definiert ist, die Punkte darstellen.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die die Farbe, Breite und den Stil der Kurve bestimmt. |
| x1 | Single | Die x-Koordinate des Startpunkts der Kurve. |
| y1 | Single | Die y-Koordinate des Startpunkts der Kurve. |
| x2 | Single | Die x-Koordinate des ersten Kontrollpunkts der Kurve. |
| y2 | Single | Die y-Koordinate des ersten Kontrollpunkts der Kurve. |
| x3 | Single | Die x-Koordinate des zweiten Kontrollpunkts der Kurve. |
| y3 | Single | Die y-Koordinate des zweiten Kontrollpunkts der Kurve. |
| x4 | Single | Die x-Koordinate des Endpunkts der Kurve. |
| y4 | Single | Die y-Koordinate des Endpunkts der Kurve. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist Null. |

### Siehe auch

* class [Pen](../../pen/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Zeichnet einen durch vier definierten Bézier-Spline[`PointF`](../../pointf/) Strukturen.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die die Farbe, Breite und den Stil der Kurve bestimmt. |
| pt1 | PointF | [`PointF`](../../pointf/) Struktur, die den Startpunkt der Kurve darstellt. |
| pt2 | PointF | [`PointF`](../../pointf/) Struktur, die den ersten Kontrollpunkt für die Kurve darstellt. |
| pt3 | PointF | [`PointF`](../../pointf/) Struktur, die den zweiten Kontrollpunkt für die Kurve darstellt. |
| pt4 | PointF | [`PointF`](../../pointf/) Struktur, die den Endpunkt der Kurve darstellt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist Null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Zeichnet einen durch vier definierten Bézier-Spline[`Point`](../../point/) Strukturen.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) Struktur, die Farbe, Breite und Stil der Kurve bestimmt. |
| pt1 | Point | [`Point`](../../point/) Struktur, die den Startpunkt der Kurve darstellt. |
| pt2 | Point | [`Point`](../../point/) Struktur, die den ersten Kontrollpunkt für die Kurve darstellt. |
| pt3 | Point | [`Point`](../../point/) Struktur, die den zweiten Kontrollpunkt für die Kurve darstellt. |
| pt4 | Point | [`Point`](../../point/) Struktur, die den Endpunkt der Kurve darstellt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist Null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)


