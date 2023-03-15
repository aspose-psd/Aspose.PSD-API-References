---
title: Graphics.DrawLines
second_title: Aspose.PSD voor .NET API-referentie
description: Graphics methode. Tekent een reeks lijnsegmenten die een reeks verbindenPoint structuren.
type: docs
weight: 260
url: /nl/net/aspose.psd/graphics/drawlines/
---
## DrawLines(Pen, Point[]) {#drawlines_1}

Tekent een reeks lijnsegmenten die een reeks verbinden[`Point`](../../point/) structuren.

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die de kleur, breedte en stijl van de lijnsegmenten bepaalt. |
| points | Point[] | Reeks van[`Point`](../../point/) structuren die de te verbinden punten vertegenwoordigen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *pen* is nul. -of- *points* is niets. |
| ArgumentException | De*points* matrix bevat minder dan 2 punten. |

### Zie ook

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Tekent een reeks lijnsegmenten die een reeks verbinden[`PointF`](../../pointf/) structuren.

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die de kleur, breedte en stijl van de lijnsegmenten bepaalt. |
| points | PointF[] | Reeks van[`PointF`](../../pointf/) structuren die de te verbinden punten vertegenwoordigen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *pen* is nul. -of- *points* is niets. |
| ArgumentException | De*points* matrix bevat minder dan 2 punten. |

### Zie ook

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)


