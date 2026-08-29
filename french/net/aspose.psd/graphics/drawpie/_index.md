---
title: "Graphics.DrawPie"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Graphics. Dessine une forme de secteur définie par une ellipse spécifiée par une structure RectangleF et deux lignes radiales."
type: docs
weight: 290
url: /fr/net/aspose.psd/graphics/drawpie/
---
{{< psd/tize >}}
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

Dessine une forme de secteur définie par une ellipse spécifiée par une structure [`RectangleF`](../../rectanglef/) et deux lignes radiales.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style du secteur. |
| rect | RectangleF | Structure [`RectangleF`](../../rectanglef/) qui représente le rectangle englobant définissant l'ellipse dont provient le secteur. |
| startAngle | Single | Angle mesuré en degrés dans le sens horaire depuis l'axe x jusqu'au premier côté du secteur. |
| sweepAngle | Single | Angle mesuré en degrés dans le sens horaire depuis le paramètre *startAngle* jusqu'au deuxième côté du secteur. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. |

### Voir aussi

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style du secteur. |
| x | Single | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient le secteur. |
| y | Single | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| largeur | Single | Largeur du rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| hauteur | Single | Hauteur du rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| startAngle | Single | Angle mesuré en degrés dans le sens horaire depuis l'axe x jusqu'au premier côté du secteur. |
| sweepAngle | Single | Angle mesuré en degrés dans le sens horaire depuis le paramètre *startAngle* jusqu'au deuxième côté du secteur. |

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

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

Dessine une forme de tarte définie par une ellipse spécifiée par une structure [`Rectangle`](../../rectangle/) et deux lignes radiales.

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style du secteur. |
| rect | Rectangle | Structure [`Rectangle`](../../rectangle/) qui représente le rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| startAngle | Single | Angle mesuré en degrés dans le sens horaire depuis l'axe x jusqu'au premier côté du secteur. |
| sweepAngle | Single | Angle mesuré en degrés dans le sens horaire depuis le paramètre *startAngle* jusqu'au deuxième côté du secteur. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. |

### Voir aussi

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style du secteur. |
| x | Int32 | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient le secteur. |
| y | Int32 | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| largeur | Int32 | Largeur du rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| hauteur | Int32 | Hauteur du rectangle englobant qui définit l'ellipse dont provient la forme de tarte. |
| startAngle | Int32 | Angle mesuré en degrés dans le sens horaire depuis l'axe x jusqu'au premier côté du secteur. |
| sweepAngle | Int32 | Angle mesuré en degrés dans le sens horaire depuis le paramètre *startAngle* jusqu'au deuxième côté du secteur. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. |

### Voir aussi

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


