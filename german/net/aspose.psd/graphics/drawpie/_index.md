---
title: "Graphics.DrawPie"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Graphics-Methode. Zeichnet eine Kuchenform, die durch eine Ellipse definiert ist, die durch eine RectangleF-Struktur angegeben wird, und zwei Radiallinien."
type: docs
weight: 290
url: /de/net/aspose.psd/graphics/drawpie/
---
{{< psd/tize >}}
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

Zeichnet eine Kuchenform, die durch eine Ellipse definiert ist, die durch eine [`RectangleF`](../../rectanglef/) Struktur angegeben wird, und zwei Radiallinien.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) der die Farbe, Breite und den Stil der Kuchenform bestimmt. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der die Kuchenform stammt. |
| startAngle | Single | Winkel in Grad gemessen, im Uhrzeigersinn von der x-Achse zur ersten Seite der Kuchenform. |
| sweepAngle | Single | Winkel in Grad gemessen, im Uhrzeigersinn vom *startAngle*-Parameter zur zweiten Seite der Kuchenform. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

Zeichnet eine Kuchenform, definiert durch eine Ellipse, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben ist.

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) der die Farbe, Breite und den Stil der Kuchenform bestimmt. |
| x | Single | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| y | Single | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| Breite | Single | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| Höhe | Single | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| startAngle | Single | Winkel in Grad gemessen, im Uhrzeigersinn von der x-Achse zur ersten Seite der Kuchenform. |
| sweepAngle | Single | Winkel in Grad gemessen, im Uhrzeigersinn vom *startAngle*-Parameter zur zweiten Seite der Kuchenform. |

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

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

Zeichnet eine Kuchenform, die durch eine Ellipse definiert ist, die durch eine [`Rectangle`](../../rectangle/) Struktur angegeben wird, und zwei Radiallinien.

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) der die Farbe, Breite und den Stil der Kuchenform bestimmt. |
| rect | Rectangle | [`Rectangle`](../../rectangle/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der die Kuchenform stammt. |
| startAngle | Single | Winkel in Grad gemessen, im Uhrzeigersinn von der x-Achse zur ersten Seite der Kuchenform. |
| sweepAngle | Single | Winkel in Grad gemessen, im Uhrzeigersinn vom *startAngle*-Parameter zur zweiten Seite der Kuchenform. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

Zeichnet eine Kuchenform, definiert durch eine Ellipse, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben ist.

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) der die Farbe, Breite und den Stil der Kuchenform bestimmt. |
| x | Int32 | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| y | Int32 | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| Breite | Int32 | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| Höhe | Int32 | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| startAngle | Int32 | Winkel in Grad gemessen, im Uhrzeigersinn von der x-Achse zur ersten Seite der Kuchenform. |
| sweepAngle | Int32 | Winkel in Grad gemessen, im Uhrzeigersinn vom *startAngle*-Parameter zur zweiten Seite der Kuchenform. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. |

### Siehe auch

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


