---
title: Graphics.DrawBezier
second_title: Référence de l'API Aspose.PSD pour .NET
description: Graphics méthode. Dessine une spline de Bézier définie par quatre paires ordonnées de coordonnées qui représentent des points.
type: docs
weight: 170
url: /fr/net/aspose.psd/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Dessine une spline de Bézier définie par quatre paires ordonnées de coordonnées qui représentent des points.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| x1 | Single | Coordonnée x du point de départ de la courbe. |
| y1 | Single | Coordonnée y du point de départ de la courbe. |
| x2 | Single | Coordonnée x du premier point de contrôle de la courbe. |
| y2 | Single | Coordonnée y du premier point de contrôle de la courbe. |
| x3 | Single | Coordonnée x du deuxième point de contrôle de la courbe. |
| y3 | Single | Coordonnée y du deuxième point de contrôle de la courbe. |
| x4 | Single | Coordonnée x du point d'arrivée de la courbe. |
| y4 | Single | Coordonnée y du point d'arrivée de la courbe. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. |

### Voir également

* class [Pen](../../pen/)
* class [Graphics](../)
* espace de noms [Aspose.PSD](../../graphics/)
* Assemblée [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Dessine une spline de Bézier définie par quatre[`PointF`](../../pointf/) structures.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| pt1 | PointF | [`PointF`](../../pointf/) structure qui représente le point de départ de la courbe. |
| pt2 | PointF | [`PointF`](../../pointf/) structure qui représente le premier point de contrôle de la courbe. |
| pt3 | PointF | [`PointF`](../../pointf/) structure qui représente le deuxième point de contrôle de la courbe. |
| pt4 | PointF | [`PointF`](../../pointf/) structure qui représente le point final de la courbe. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. |

### Voir également

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* espace de noms [Aspose.PSD](../../graphics/)
* Assemblée [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Dessine une spline de Bézier définie par quatre[`Point`](../../point/) structures.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) structure qui détermine la couleur, la largeur et le style de la courbe. |
| pt1 | Point | [`Point`](../../point/) structure qui représente le point de départ de la courbe. |
| pt2 | Point | [`Point`](../../point/) structure qui représente le premier point de contrôle de la courbe. |
| pt3 | Point | [`Point`](../../point/) structure qui représente le deuxième point de contrôle de la courbe. |
| pt4 | Point | [`Point`](../../point/) structure qui représente le point final de la courbe. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. |

### Voir également

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* espace de noms [Aspose.PSD](../../graphics/)
* Assemblée [Aspose.PSD](../../../)


