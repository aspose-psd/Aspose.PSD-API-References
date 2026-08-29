---
title: "Graphics.FillPie"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Graphics-Methode. Füllt das Innere eines Kuchenabschnitts, der durch eine Ellipse definiert ist, die durch eine RectangleF-Struktur und zwei Radiallinien angegeben wird."
type: docs
weight: 380
url: /de/net/aspose.psd/graphics/fillpie/
---
{{< psd/tize >}}
## FillPie(Brush, Rectangle, float, float) {#fillpie}

Füllt das Innere eines Kuchenabschnitts, der durch eine Ellipse definiert ist, die durch eine [`RectangleF`](../../rectanglef/) Struktur angegeben wird, und zwei Radiallinien.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) bestimmt die Eigenschaften der Füllung. |
| rect | Rectangle | [`Rectangle`](../../rectangle/) Struktur, die das begrenzende Rechteck darstellt, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| startAngle | Single | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zur ersten Seite des Kuchenabschnitts. |
| sweepAngle | Single | Winkel in Grad, gemessen im Uhrzeigersinn vom *startAngle*-Parameter zur zweiten Seite des Kuchenabschnitts. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. |

### Siehe auch

* class [Brush](../../brush/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

Füllt das Innere eines Kuchenabschnitts, der durch eine Ellipse definiert ist, die durch eine [`RectangleF`](../../rectanglef/) Struktur angegeben wird, und zwei Radiallinien.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) bestimmt die Eigenschaften der Füllung. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) Struktur, die das begrenzende Rechteck darstellt, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| startAngle | Single | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zur ersten Seite des Kuchenabschnitts. |
| sweepAngle | Single | Winkel in Grad, gemessen im Uhrzeigersinn vom *startAngle*-Parameter zur zweiten Seite des Kuchenabschnitts. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. |

### Siehe auch

* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben ist.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) bestimmt die Eigenschaften der Füllung. |
| x | Single | Die x-Koordinate der oberen linken Ecke des begrenzenden Rechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| y | Single | Die y-Koordinate der oberen linken Ecke des begrenzenden Rechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| Breite | Single | Breite des begrenzenden Rechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| Höhe | Single | Höhe des begrenzenden Rechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| startAngle | Single | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zur ersten Seite des Kuchenabschnitts. |
| sweepAngle | Single | Winkel in Grad, gemessen im Uhrzeigersinn vom *startAngle*-Parameter zur zweiten Seite des Kuchenabschnitts. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. |

### Siehe auch

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben ist.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) bestimmt die Eigenschaften der Füllung. |
| x | Int32 | Die x-Koordinate der oberen linken Ecke des begrenzenden Rechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| y | Int32 | Die y-Koordinate der oberen linken Ecke des begrenzenden Rechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| Breite | Int32 | Breite des begrenzenden Rechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| Höhe | Int32 | Höhe des begrenzenden Rechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| startAngle | Int32 | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zur ersten Seite des Kuchenabschnitts. |
| sweepAngle | Int32 | Winkel in Grad, gemessen im Uhrzeigersinn vom *startAngle*-Parameter zur zweiten Seite des Kuchenabschnitts. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. |

### Siehe auch

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


