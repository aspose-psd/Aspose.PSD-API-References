---
title: Graphics.DrawLines
second_title: Référence de l'API Aspose.PSD pour .NET
description: Graphics méthode. Dessine une série de segments de ligne qui relient un tableau dePoint structures.
type: docs
weight: 260
url: /fr/net/aspose.psd/graphics/drawlines/
---
## DrawLines(Pen, Point[]) {#drawlines_1}

Dessine une série de segments de ligne qui relient un tableau de[`Point`](../../point/) structures.

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style des segments de ligne. |
| points | Point[] | Tableau de[`Point`](../../point/) structures qui représentent les points à connecter. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |
| ArgumentException | Le*points* tableau contient moins de 2 points. |

### Voir également

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* espace de noms [Aspose.PSD](../../graphics/)
* Assemblée [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Dessine une série de segments de ligne qui relient un tableau de[`PointF`](../../pointf/) structures.

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style des segments de ligne. |
| points | PointF[] | Tableau de[`PointF`](../../pointf/) structures qui représentent les points à connecter. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |
| ArgumentException | Le*points* tableau contient moins de 2 points. |

### Voir également

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* espace de noms [Aspose.PSD](../../graphics/)
* Assemblée [Aspose.PSD](../../../)


