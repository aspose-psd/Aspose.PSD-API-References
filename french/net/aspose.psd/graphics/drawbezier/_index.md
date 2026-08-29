---
title: "Graphics.DrawBezier"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Graphics. Trace une spline de Bézier définie par quatre paires ordonnées de coordonnées représentant des points."
type: docs
weight: 180
url: /fr/net/aspose.psd/graphics/drawbezier/
---
{{< psd/tize >}}
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Dessine une spline de Bézier définie par quatre paires ordonnées de coordonnées représentant des points.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| x1 | Single | La coordonnée x du point de départ de la courbe. |
| y1 | Single | La coordonnée y du point de départ de la courbe. |
| x2 | Single | La coordonnée x du premier point de contrôle de la courbe. |
| y2 | Single | La coordonnée y du premier point de contrôle de la courbe. |
| x3 | Single | La coordonnée x du deuxième point de contrôle de la courbe. |
| y3 | Single | La coordonnée y du deuxième point de contrôle de la courbe. |
| x4 | Single | La coordonnée x du point final de la courbe. |
| y4 | Single | La coordonnée y du point final de la courbe. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. |

### Voir aussi

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Trace une spline de Bézier définie par quatre structures [`PointF`](../../pointf/).

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| pt1 | PointF | `[`PointF`](../../pointf/) structure qui représente le point de départ de la courbe.` |
| pt2 | PointF | `[`PointF`](../../pointf/) structure qui représente le premier point de contrôle de la courbe.` |
| pt3 | PointF | `[`PointF`](../../pointf/) structure qui représente le deuxième point de contrôle de la courbe.` |
| pt4 | PointF | `[`PointF`](../../pointf/) structure qui représente le point final de la courbe.` |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. |

### Voir aussi

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Dessine une courbe de Bézier définie par quatre structures [`Point`](../../point/).

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | `[`Pen`](../../pen/) structure qui détermine la couleur, la largeur et le style de la courbe.` |
| pt1 | Point | `[`Point`](../../point/) structure qui représente le point de départ de la courbe.` |
| pt2 | Point | `[`Point`](../../point/) structure qui représente le premier point de contrôle de la courbe.` |
| pt3 | Point | `[`Point`](../../point/) structure qui représente le deuxième point de contrôle de la courbe.` |
| pt4 | Point | `[`Point`](../../point/) structure qui représente le point final de la courbe.` |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. |

### Voir aussi

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


