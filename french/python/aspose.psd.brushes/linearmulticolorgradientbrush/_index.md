---
title: "Classe LinearMulticolorGradientBrush"
type: docs
weight: 40
url: /fr/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/
---

**Summary:** Represents a [Brush](/psd/python-net/aspose.psd/brush/) with linear gradient defined by multiple colors and appropriate positions. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearMulticolorGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush__1) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) avec des paramètres par défaut.<br/>            La couleur de départ est noire, la couleur de fin est blanche, l'angle est de 45 degrés et le rectangle est situé en (0,0) avec une taille de (1,1). |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_2) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) avec les points spécifiés. |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_3) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) avec les points spécifiés. |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_4) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation. |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_5) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation. |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation. |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7) | Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angle | float | r/w | Obtient ou définit l'angle du dégradé. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| gamma_correction | bool | r/w | Obtient ou définit une valeur indiquant si la correction gamma est activée pour ce [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Obtient ou définit un [ColorBlend](/psd/python-net/aspose.psd/colorblend/) qui définit un dégradé linéaire multicolore. |
| is_angle_scalable | bool | r/w | Obtient ou définit une valeur indiquant si [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) est modifié pendant les transformations avec ce [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple en définissant la matrice de transformation ou<br/>            en appelant l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la compatibilité descendante avec GDI+. |
| opacity | float | r/w | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est totalement opaque. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | Obtient ou définit une région rectangulaire qui définit les points de départ et d'arrivée du dégradé. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Obtient ou définit une copie de la [Matrix](/psd/python-net/aspose.psd/matrix/) qui définit une transformation géométrique locale pour ce [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Obtient ou définit une énumération [WrapMode](/psd/python-net/aspose.psd/wrapmode/) qui indique le mode d'enroulement pour ce [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Crée un nouveau clone profond du [Brush](/psd/python-net/aspose.psd/brush/) actuel. |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Multiplie la [Matrix](/psd/python-net/aspose.psd/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) par la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée en préfixant la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Multiplie la [Matrix](/psd/python-net/aspose.psd/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) par la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée dans l'ordre spécifié. |
| reset_transform() | Réinitialise la propriété [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) à l'identité. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Fait pivoter la transformation géométrique locale du montant spécifié. Cette méthode préfixe la rotation à la transformation. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Fait pivoter la transformation géométrique locale du montant spécifié dans l'ordre spécifié. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Met à l'échelle la transformation géométrique locale des valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Met à l'échelle la transformation géométrique locale des valeurs spécifiées dans l'ordre spécifié. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Translater la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Translater la transformation géométrique locale des dimensions spécifiées dans l'ordre spécifié. |


### Constructor: LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush__1}


```
 LinearMulticolorGradientBrush() 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) avec des paramètres par défaut.<br/>            La couleur de départ est noire, la couleur de fin est blanche, l'angle est de 45 degrés et le rectangle est situé en (0,0) avec une taille de (1,1).

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_2}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) avec les points spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Une structure [Point](/psd/python-net/aspose.psd/point/) qui représente le point de départ du dégradé linéaire. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Une structure [Point](/psd/python-net/aspose.psd/point/) qui représente le point d'arrivée du dégradé linéaire. |

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_3}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) avec les points spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Une structure [Point](/psd/python-net/aspose.psd/point/) qui représente le point de départ du dégradé linéaire. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Une structure [Point](/psd/python-net/aspose.psd/point/) qui représente le point d'arrivée du dégradé linéaire. |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_4}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_5}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |
| is_angle_scalable | bool | si défini sur <c>true</c> l'angle est modifié lors des transformations avec ce [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/). |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

Initialise une nouvelle instance de la classe [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) basée sur un rectangle et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |
| is_angle_scalable | bool | si défini sur <c>true</c> l'angle est modifié lors des transformations avec ce [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Crée un nouveau clone profond du [Brush](/psd/python-net/aspose.psd/brush/) actuel.

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | Un nouveau [Brush](/psd/python-net/aspose.psd/brush/) qui est le clone profond de cette instance [Brush](/psd/python-net/aspose.psd/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Multiplie la [Matrix](/psd/python-net/aspose.psd/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) par la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée en préfixant la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La [Matrix](/psd/python-net/aspose.psd/matrix/) par laquelle multiplier la transformation géométrique. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Multiplie la [Matrix](/psd/python-net/aspose.psd/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) par la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La [Matrix](/psd/python-net/aspose.psd/matrix/) par laquelle multiplier la transformation géométrique. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) qui spécifie dans quel ordre multiplier les deux matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Fait pivoter la transformation géométrique locale du montant spécifié. Cette méthode préfixe la rotation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Fait pivoter la transformation géométrique locale du montant spécifié dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) qui spécifie s'il faut ajouter ou préfixer la matrice de rotation. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Met à l'échelle la transformation géométrique locale des valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | La quantité par laquelle mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | La quantité par laquelle mettre à l'échelle la transformation dans la direction de l'axe y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Met à l'échelle la transformation géométrique locale des valeurs spécifiées dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | La quantité par laquelle mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | La quantité par laquelle mettre à l'échelle la transformation dans la direction de l'axe y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) qui spécifie s'il faut ajouter ou préfixer la matrice d'échelle. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Translater la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la traduction en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Translater la transformation géométrique locale des dimensions spécifiées dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la traduction en y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordre (préfixer ou ajouter) dans lequel appliquer la traduction. |

