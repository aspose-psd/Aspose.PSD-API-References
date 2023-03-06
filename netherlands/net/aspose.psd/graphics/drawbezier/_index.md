---
title: Graphics.DrawBezier
second_title: Aspose.PSD voor .NET API-referentie
description: Graphics methode. Tekent een Bézierspline gedefinieerd door vier geordende paar coördinaten die punten vertegenwoordigen.
type: docs
weight: 170
url: /nl/net/aspose.psd/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Tekent een Bézier-spline gedefinieerd door vier geordende paar coördinaten die punten vertegenwoordigen.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die de kleur, breedte en stijl van de curve bepaalt. |
| x1 | Single | De x-coördinaat van het startpunt van de kromme. |
| y1 | Single | De y-coördinaat van het startpunt van de curve. |
| x2 | Single | De x-coördinaat van het eerste controlepunt van de curve. |
| y2 | Single | De y-coördinaat van het eerste controlepunt van de curve. |
| x3 | Single | De x-coördinaat van het tweede controlepunt van de curve. |
| y3 | Single | De y-coördinaat van het tweede controlepunt van de curve. |
| x4 | Single | De x-coördinaat van het eindpunt van de kromme. |
| y4 | Single | De y-coördinaat van het eindpunt van de kromme. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *pen* is niets. |

### Zie ook

* class [Pen](../../pen/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Tekent een Bézier-spline gedefinieerd door vier[`PointF`](../../pointf/) structuren.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die de kleur, breedte en stijl van de curve bepaalt. |
| pt1 | PointF | [`PointF`](../../pointf/) structuur die het startpunt van de curve vertegenwoordigt. |
| pt2 | PointF | [`PointF`](../../pointf/) structuur die het eerste controlepunt voor de curve vertegenwoordigt. |
| pt3 | PointF | [`PointF`](../../pointf/) structuur die het tweede controlepunt voor de curve vertegenwoordigt. |
| pt4 | PointF | [`PointF`](../../pointf/) structuur die het eindpunt van de curve vertegenwoordigt. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *pen* is niets. |

### Zie ook

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Tekent een Bézier-spline gedefinieerd door vier[`Point`](../../point/) structuren.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) structuur die de kleur, breedte en stijl van de curve bepaalt. |
| pt1 | Point | [`Point`](../../point/) structuur die het startpunt van de curve vertegenwoordigt. |
| pt2 | Point | [`Point`](../../point/) structuur die het eerste controlepunt voor de curve vertegenwoordigt. |
| pt3 | Point | [`Point`](../../point/) structuur die het tweede controlepunt voor de curve vertegenwoordigt. |
| pt4 | Point | [`Point`](../../point/) structuur die het eindpunt van de curve vertegenwoordigt. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *pen* is niets. |

### Zie ook

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)


