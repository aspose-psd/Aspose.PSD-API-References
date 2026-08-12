---
title: "Graphics.DrawBezier"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Graphics‑metod. Ritar en Bézier‑spline definierad av fyra ordnade koordinatpar som representerar punkter"
type: docs
weight: 180
url: /sv/net/aspose.psd/graphics/drawbezier/
---
{{< psd/tize >}}
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Ritar en Bézier-spline definierad av fyra ordnade koordinatpar som representerar punkter.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer färg, bredd och stil på kurvan. |
| x1 | Single | x‑koordinaten för kurvans startpunkt. |
| y1 | Single | y‑koordinaten för kurvans startpunkt. |
| x2 | Single | x‑koordinaten för kurvans första kontrollpunkt. |
| y2 | Single | y‑koordinaten för kurvans första kontrollpunkt. |
| x3 | Single | x‑koordinaten för kurvans andra kontrollpunkt. |
| y3 | Single | Y-koordinaten för den andra kontrollpunkten på kurvan. |
| x4 | Single | X-koordinaten för slutpunkten på kurvan. |
| y4 | Single | Y-koordinaten för slutpunkten på kurvan. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *pen* är null. |

### Se även

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Ritar en Bézier-spline definierad av fyra [`PointF`](../../pointf/) strukturer.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer färg, bredd och stil på kurvan. |
| pt1 | PointF | [`PointF`](../../pointf/) struktur som representerar startpunkten på kurvan. |
| pt2 | PointF | [`PointF`](../../pointf/) struktur som representerar den första kontrollpunkten för kurvan. |
| pt3 | PointF | [`PointF`](../../pointf/) struktur som representerar den andra kontrollpunkten för kurvan. |
| pt4 | PointF | [`PointF`](../../pointf/) struktur som representerar slutpunkten på kurvan. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *pen* är null. |

### Se även

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Ritar en Bézier-spline definierad av fyra [`Point`](../../point/) strukturer.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) struktur som bestämmer färgen, bredden och stilen på kurvan. |
| pt1 | Point | [`Point`](../../point/) struktur som representerar startpunkten på kurvan. |
| pt2 | Point | [`Point`](../../point/) struktur som representerar den första kontrollpunkten för kurvan. |
| pt3 | Point | [`Point`](../../point/) struktur som representerar den andra kontrollpunkten för kurvan. |
| pt4 | Point | [`Point`](../../point/) struktur som representerar slutpunkten på kurvan. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *pen* är null. |

### Se även

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


