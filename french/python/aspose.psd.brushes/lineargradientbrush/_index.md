---
title: "Classe LinearGradientBrush"
type: docs
weight: 20
url: /fr/python-net/aspose.psd.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) avec les paramètres par défaut.<br/>            La couleur de départ est noire, la couleur finale est blanche, l'angle est de 45 degrés et le rectangle est situé en (0,0) avec une taille de (1,1). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) avec les points et couleurs spécifiés. |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) avec les points et couleurs spécifiés. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basée sur un rectangle, des couleurs de départ et d'arrivée, et un angle d'orientation. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basée sur un rectangle, des couleurs de départ et d'arrivée, et un angle d'orientation. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basée sur un rectangle, des couleurs de départ et d'arrivée, et un angle d'orientation. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | Initialise une nouvelle instance de la classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basée sur un rectangle, des couleurs de départ et d'arrivée, et un angle d'orientation. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angle | float | r/w | Obtient ou définit l'angle du dégradé. |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Obtient ou définit un [Blend](/psd/python-net/aspose.psd/blend/) qui spécifie les positions et les facteurs qui définissent une atténuation personnalisée pour le dégradé. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| end_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtient ou définit la couleur finale du dégradé. |
| gamma_correction | bool | r/w | Obtient ou définit une valeur indiquant si la correction gamma est activée pour ce [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Obtient ou définit un [ColorBlend](/psd/python-net/aspose.psd/colorblend/) qui définit un dégradé linéaire multicolore. |
| is_angle_scalable | bool | r/w | Obtient ou définit une valeur indiquant si [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) est modifié pendant les transformations avec ce [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple en définissant la matrice de transformation ou<br/>            en appelant l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la compatibilité descendante avec GDI+. |
| linear_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Obtient ou définit les couleurs de départ et de fin du dégradé. |
| opacity | float | r/w | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est totalement opaque. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | Obtient ou définit une région rectangulaire qui définit les points de départ et d'arrivée du dégradé. |
| start_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtient ou définit la couleur de départ du dégradé. |
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
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une seule couleur aux deux extrémités. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une seule couleur aux deux extrémités. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Crée une atténuation de dégradé basée sur une courbe en cloche. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Crée une atténuation de dégradé basée sur une courbe en cloche. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Translater la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Translater la transformation géométrique locale des dimensions spécifiées dans l'ordre spécifié. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) avec les paramètres par défaut.<br/>            La couleur de départ est noire, la couleur finale est blanche, l'angle est de 45 degrés et le rectangle est situé en (0,0) avec une taille de (1,1).

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) avec les points et couleurs spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Une structure [Point](/psd/python-net/aspose.psd/point/) qui représente le point de départ du dégradé linéaire. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Une structure [Point](/psd/python-net/aspose.psd/point/) qui représente le point d'arrivée du dégradé linéaire. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Une structure [Color](/psd/python-net/aspose.psd/color/) qui représente la couleur de départ du dégradé linéaire. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Une structure [Color](/psd/python-net/aspose.psd/color/) qui représente la couleur finale du dégradé linéaire. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) avec les points et couleurs spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Une structure [Point](/psd/python-net/aspose.psd/point/) qui représente le point de départ du dégradé linéaire. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Une structure [Point](/psd/python-net/aspose.psd/point/) qui représente le point d'arrivée du dégradé linéaire. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Une structure [Color](/psd/python-net/aspose.psd/color/) qui représente la couleur de départ du dégradé linéaire. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Une structure [Color](/psd/python-net/aspose.psd/color/) qui représente la couleur finale du dégradé linéaire. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basée sur un rectangle, des couleurs de départ et d'arrivée, et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Une structure [Color](/psd/python-net/aspose.psd/color/) qui représente la couleur de départ du dégradé. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Une structure [Color](/psd/python-net/aspose.psd/color/) qui représente la couleur finale du dégradé. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basée sur un rectangle, des couleurs de départ et d'arrivée, et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Une structure [Color](/psd/python-net/aspose.psd/color/) qui représente la couleur de départ du dégradé. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Une structure [Color](/psd/python-net/aspose.psd/color/) qui représente la couleur finale du dégradé. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basée sur un rectangle, des couleurs de départ et d'arrivée, et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Une structure [Color](/psd/python-net/aspose.psd/color/) qui représente la couleur de départ du dégradé. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Une structure [Color](/psd/python-net/aspose.psd/color/) qui représente la couleur finale du dégradé. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |
| is_angle_scalable | bool | si réglé sur <c>true</c> l'angle est modifié lors des transformations avec ce [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/). |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Initialise une nouvelle instance de la classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basée sur un rectangle, des couleurs de départ et d'arrivée, et un angle d'orientation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui spécifie les limites du dégradé linéaire. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Une structure [Color](/psd/python-net/aspose.psd/color/) qui représente la couleur de départ du dégradé. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Une structure [Color](/psd/python-net/aspose.psd/color/) qui représente la couleur finale du dégradé. |
| angle | float | L'angle, mesuré en degrés dans le sens horaire à partir de l'axe x, de la ligne d'orientation du dégradé. |
| is_angle_scalable | bool | si réglé sur <c>true</c> l'angle est modifié lors des transformations avec ce [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/). |

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

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_8}


```
 set_blend_triangular_shape(focus) 
```

Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une seule couleur aux deux extrémités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie le centre du dégradé (le point où le dégradé est composé uniquement de la couleur finale). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Crée un dégradé linéaire avec une couleur centrale et une atténuation linéaire vers une seule couleur aux deux extrémités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie le centre du dégradé (le point où le dégradé est composé uniquement de la couleur finale). |
| scale | float | Une valeur comprise entre 0 et 1 qui spécifie la rapidité avec laquelle les couleurs diminuent depuis la couleur de départ jusqu'à <paramref name=\"focus\" /> (couleur finale) |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Crée une atténuation de dégradé basée sur une courbe en cloche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie le centre du dégradé (le point où la couleur de départ et la couleur finale sont mélangées de manière égale). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Crée une atténuation de dégradé basée sur une courbe en cloche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie le centre du dégradé (le point où le dégradé est composé uniquement de la couleur finale). |
| scale | float | Une valeur comprise entre 0 et 1 qui spécifie la rapidité avec laquelle les couleurs diminuent depuis le <paramref name=\"focus\" />. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Translater la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la traduction en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


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

