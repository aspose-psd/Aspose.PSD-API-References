---
title: "Graphics.DrawArc"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Graphics-Methode. Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch ein Koordinatenpaar sowie Breite und Höhe angegeben ist."
type: docs
weight: 170
url: /de/net/aspose.psd/graphics/drawarc/
---
{{< psd/tize >}}
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe.

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), das die Farbe, Breite und den Stil des Bogens bestimmt. |
| x | Single | Die x-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| y | Single | Die y-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| Breite | Single | Breite des Rechtecks, das die Ellipse definiert. |
| Höhe | Single | Höhe des Rechtecks, das die Ellipse definiert. |
| startAngle | Single | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweepAngle | Single | Winkel in Grad, gemessen im Uhrzeigersinn vom *startAngle*-Parameter zum Endpunkt des Bogens. |

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

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine [`RectangleF`](../../rectanglef/)-Struktur angegeben ist.

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), das die Farbe, Breite und den Stil des Bogens bestimmt. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) Struktur, die die Grenzen der Ellipse definiert. |
| startAngle | Single | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweepAngle | Single | Winkel in Grad, gemessen im Uhrzeigersinn vom *startAngle*-Parameter zum Endpunkt des Bogens. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null |

### Siehe auch

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe.

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), das die Farbe, Breite und den Stil des Bogens bestimmt. |
| x | Int32 | Die x-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| y | Int32 | Die y-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| Breite | Int32 | Breite des Rechtecks, das die Ellipse definiert. |
| Höhe | Int32 | Höhe des Rechtecks, das die Ellipse definiert. |
| startAngle | Int32 | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweepAngle | Int32 | Winkel in Grad, gemessen im Uhrzeigersinn vom *startAngle*-Parameter zum Endpunkt des Bogens. |

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

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine [`Rectangle`](../../rectangle/)-Struktur angegeben ist.

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), das die Farbe, Breite und den Stil des Bogens bestimmt. |
| rect | Rectangle | [`RectangleF`](../../rectanglef/) Struktur, die die Grenzen der Ellipse definiert. |
| startAngle | Single | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweepAngle | Single | Winkel in Grad, gemessen im Uhrzeigersinn vom *startAngle*-Parameter zum Endpunkt des Bogens. |

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


