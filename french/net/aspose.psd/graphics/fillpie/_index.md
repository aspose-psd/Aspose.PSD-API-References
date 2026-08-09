---
title: "Graphics.FillPie"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Graphics. Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure RectangleF et deux lignes radiales."
type: docs
weight: 380
url: /fr/net/aspose.psd/graphics/fillpie/
---
{{< psd/tize >}}
## FillPie(Brush, Rectangle, float, float) {#fillpie}

Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure [`RectangleF`](../../rectanglef/) et deux lignes radiales.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) qui détermine les caractéristiques du remplissage. |
| rect | Rectangle | Structure [`Rectangle`](../../rectangle/) qui représente le rectangle de délimitation qui définit l'ellipse d'où provient la part de tarte. |
| startAngle | Single | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la part de tarte. |
| sweepAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du paramètre *startAngle* jusqu'au deuxième côté de la section de tarte. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. |

### Voir aussi

* class [Brush](../../brush/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure [`RectangleF`](../../rectanglef/) et deux lignes radiales.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) qui détermine les caractéristiques du remplissage. |
| rect | RectangleF | Structure [`RectangleF`](../../rectanglef/) qui représente le rectangle englobant définissant l'ellipse dont provient la section de tarte. |
| startAngle | Single | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la part de tarte. |
| sweepAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du paramètre *startAngle* jusqu'au deuxième côté de la section de tarte. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. |

### Voir aussi

* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) qui détermine les caractéristiques du remplissage. |
| x | Single | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| y | Single | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| largeur | Single | Largeur du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| hauteur | Single | Hauteur du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| startAngle | Single | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la part de tarte. |
| sweepAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du paramètre *startAngle* jusqu'au deuxième côté de la section de tarte. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. |

### Voir aussi

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) qui détermine les caractéristiques du remplissage. |
| x | Int32 | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| y | Int32 | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| largeur | Int32 | Largeur du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| hauteur | Int32 | Hauteur du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| startAngle | Int32 | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la part de tarte. |
| sweepAngle | Int32 | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du paramètre *startAngle* jusqu'au deuxième côté de la section de tarte. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. |

### Voir aussi

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


