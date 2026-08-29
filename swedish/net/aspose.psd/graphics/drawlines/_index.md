---
title: "Graphics.DrawLines"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Graphics-metod. Ritar en serie linjesegment som kopplar ihop en array av Point-strukturer"
type: docs
weight: 270
url: /sv/net/aspose.psd/graphics/drawlines/
---
{{< psd/tize >}}
## DrawLines(Pen, Point[]) {#drawlines_1}

Ritar en serie linjesegment som kopplar ihop en array av [`Point`](../../point/) strukturer.

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer färgen, bredden och stilen på linjesegmenten. |
| points | Point[] | Array av [`Point`](../../point/) strukturer som representerar punkterna som ska kopplas ihop. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är null. |
| ArgumentException | Arrayen *points* innehåller färre än 2 punkter. |

### Se även

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Ritar en serie linjesegment som kopplar ihop en array av [`PointF`](../../pointf/) strukturer.

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer färgen, bredden och stilen på linjesegmenten. |
| points | PointF[] | Array av [`PointF`](../../pointf/) strukturer som representerar punkterna som ska kopplas ihop. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är null. |
| ArgumentException | Arrayen *points* innehåller färre än 2 punkter. |

### Se även

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


