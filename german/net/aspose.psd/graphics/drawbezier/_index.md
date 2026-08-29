---
title: "Graphics.DrawBezier"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Graphics-Methode. Zeichnet eine Bézier-Kurve, definiert durch vier geordnete Koordinatenpaare, die Punkte darstellen"
type: docs
weight: 180
url: /de/net/aspose.psd/graphics/drawbezier/
---
{{< psd/tize >}}
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Zeichnet eine Bézier‑Kurve, die durch vier geordnete Koordinatenpaare definiert ist, die Punkte darstellen.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) der die Farbe, Breite und den Stil der Kurve bestimmt. |
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
| ArgumentNullException | *pen* ist null. |

### Siehe auch

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Zeichnet einen Bézier‑Spline, der durch vier [`PointF`](../../pointf/) Strukturen definiert ist.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) der die Farbe, Breite und den Stil der Kurve bestimmt. |
| pt1 | PointF | [`PointF`](../../pointf/) Struktur, die den Startpunkt der Kurve darstellt. |
| pt2 | PointF | [`PointF`](../../pointf/) Struktur, die den ersten Kontrollpunkt der Kurve darstellt. |
| pt3 | PointF | [`PointF`](../../pointf/) Struktur, die den zweiten Kontrollpunkt der Kurve darstellt. |
| pt4 | PointF | [`PointF`](../../pointf/) Struktur, die den Endpunkt der Kurve darstellt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Zeichnet einen Bézier‑Spline, der durch vier [`Point`](../../point/) Strukturen definiert ist.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) Struktur, die Farbe, Breite und Stil der Kurve bestimmt. |
| pt1 | Point | [`Point`](../../point/) Struktur, die den Startpunkt der Kurve darstellt. |
| pt2 | Point | [`Point`](../../point/) Struktur, die den ersten Kontrollpunkt der Kurve darstellt. |
| pt3 | Point | [`Point`](../../point/) Struktur, die den zweiten Kontrollpunkt der Kurve darstellt. |
| pt4 | Point | [`Point`](../../point/) Struktur, die den Endpunkt der Kurve darstellt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


