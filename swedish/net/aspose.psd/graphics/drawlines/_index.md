---
title: Graphics.DrawLines
second_title: Aspose.PSD för .NET API-referens
description: Graphics metod. Ritar en serie linjesegment som förbinder en array avPoint strukturer.
type: docs
weight: 260
url: /sv/net/aspose.psd/graphics/drawlines/
---
## DrawLines(Pen, Point[]) {#drawlines_1}

Ritar en serie linjesegment som förbinder en array av[`Point`](../../point/) strukturer.

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som avgör linjesegmentens färg, bredd och stil. |
| points | Point[] | Uppsättning av[`Point`](../../point/) strukturer som representerar de punkter som ska anslutas. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är inget. |
| ArgumentException | De*points* array innehåller mindre än 2 punkter. |

### Se även

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Ritar en serie linjesegment som förbinder en array av[`PointF`](../../pointf/) strukturer.

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som avgör linjesegmentens färg, bredd och stil. |
| points | PointF[] | Uppsättning av[`PointF`](../../pointf/) strukturer som representerar de punkter som ska anslutas. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är inget. |
| ArgumentException | De*points* array innehåller mindre än 2 punkter. |

### Se även

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)


