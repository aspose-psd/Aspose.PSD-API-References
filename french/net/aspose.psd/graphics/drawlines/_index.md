---
title: "Graphics.DrawLines"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Graphics. Dessine une série de segments de ligne qui relient un tableau de structures Point"
type: docs
weight: 270
url: /fr/net/aspose.psd/graphics/drawlines/
---
{{< psd/tize >}}
## DrawLines(Pen, Point[]) {#drawlines_1}

Dessine une série de segments de ligne qui relient un tableau de structures [`Point`](../../point/).

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style des segments de ligne. |
| points | Point[] | Tableau de structures [`Point`](../../point/) qui représentent les points à connecter. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |
| ArgumentException | Le tableau *points* contient moins de 2 points. |

### Voir aussi

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Dessine une série de segments de ligne qui relient un tableau de structures [`PointF`](../../pointf/).

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style des segments de ligne. |
| points | PointF[] | Tableau de structures [`PointF`](../../pointf/) qui représentent les points à connecter. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |
| ArgumentException | Le tableau *points* contient moins de 2 points. |

### Voir aussi

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


