---
title: Graphics.DrawArc
second_title: Référence de l'API Aspose.PSD pour .NET
description: Graphics méthode. Dessine un arc représentant une portion dellipse spécifiée par une paire de coordonnées une largeur et une hauteur.
type: docs
weight: 160
url: /fr/net/aspose.psd/graphics/drawarc/
---
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

Dessine un arc représentant une portion d'ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur.

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style de l'arc. |
| x | Single | Coordonnée x du coin supérieur gauche du rectangle qui définit l'ellipse. |
| y | Single | Coordonnée y du coin supérieur gauche du rectangle qui définit l'ellipse. |
| width | Single | Largeur du rectangle qui définit l'ellipse. |
| height | Single | Hauteur du rectangle qui définit l'ellipse. |
| startAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre entre l'axe des x et le point de départ de l'arc. |
| sweepAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du*startAngle* paramètre au point final de l'arc. |

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

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

Dessine un arc représentant une portion d'ellipse spécifiée par un[`RectangleF`](../../rectanglef/)structure.

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style de l'arc. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) structure qui définit les limites de l'ellipse. |
| startAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre entre l'axe des x et le point de départ de l'arc. |
| sweepAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du*startAngle* paramètre au point final de l'arc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul |

### Voir également

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* espace de noms [Aspose.PSD](../../graphics/)
* Assemblée [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

Dessine un arc représentant une portion d'ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur.

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style de l'arc. |
| x | Int32 | Coordonnée x du coin supérieur gauche du rectangle qui définit l'ellipse. |
| y | Int32 | Coordonnée y du coin supérieur gauche du rectangle qui définit l'ellipse. |
| width | Int32 | Largeur du rectangle qui définit l'ellipse. |
| height | Int32 | Hauteur du rectangle qui définit l'ellipse. |
| startAngle | Int32 | Angle en degrés mesuré dans le sens des aiguilles d'une montre entre l'axe des x et le point de départ de l'arc. |
| sweepAngle | Int32 | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du*startAngle* paramètre au point final de l'arc. |

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

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

Dessine un arc représentant une portion d'ellipse spécifiée par un[`Rectangle`](../../rectangle/)structure.

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style de l'arc. |
| rect | Rectangle | [`RectangleF`](../../rectanglef/) structure qui définit les limites de l'ellipse. |
| startAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre entre l'axe des x et le point de départ de l'arc. |
| sweepAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du*startAngle* paramètre au point final de l'arc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. |

### Voir également

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* espace de noms [Aspose.PSD](../../graphics/)
* Assemblée [Aspose.PSD](../../../)


