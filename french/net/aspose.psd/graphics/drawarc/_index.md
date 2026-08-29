---
title: "Graphics.DrawArc"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Graphics. Dessine un arc représentant une partie d’une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur."
type: docs
weight: 170
url: /fr/net/aspose.psd/graphics/drawarc/
---
{{< psd/tize >}}
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur.

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style de l’arc. |
| x | Single | La coordonnée x du coin supérieur gauche du rectangle qui définit l'ellipse. |
| y | Single | La coordonnée y du coin supérieur gauche du rectangle qui définit l'ellipse. |
| largeur | Single | Largeur du rectangle qui définit l'ellipse. |
| hauteur | Single | Hauteur du rectangle qui définit l'ellipse. |
| startAngle | Single | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweepAngle | Single | Angle en degrés mesuré dans le sens horaire depuis le paramètre *startAngle* jusqu'au point final de l'arc. |

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

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

Dessine un arc représentant une partie d'une ellipse spécifiée par une structure [`RectangleF`](../../rectanglef/).

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style de l’arc. |
| rect | RectangleF | Structure [`RectangleF`](../../rectanglef/) qui définit les limites de l'ellipse. |
| startAngle | Single | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweepAngle | Single | Angle en degrés mesuré dans le sens horaire depuis le paramètre *startAngle* jusqu'au point final de l'arc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul |

### Voir aussi

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur.

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style de l’arc. |
| x | Int32 | La coordonnée x du coin supérieur gauche du rectangle qui définit l'ellipse. |
| y | Int32 | La coordonnée y du coin supérieur gauche du rectangle qui définit l'ellipse. |
| largeur | Int32 | Largeur du rectangle qui définit l'ellipse. |
| hauteur | Int32 | Hauteur du rectangle qui définit l'ellipse. |
| startAngle | Int32 | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweepAngle | Int32 | Angle en degrés mesuré dans le sens horaire depuis le paramètre *startAngle* jusqu'au point final de l'arc. |

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

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

Dessine un arc représentant une partie d'une ellipse spécifiée par une structure [`Rectangle`](../../rectangle/).

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style de l’arc. |
| rect | Rectangle | Structure [`RectangleF`](../../rectanglef/) qui définit les limites de l'ellipse. |
| startAngle | Single | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweepAngle | Single | Angle en degrés mesuré dans le sens horaire depuis le paramètre *startAngle* jusqu'au point final de l'arc. |

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


