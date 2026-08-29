---
title: "Classe PathGradientBrush"
type: docs
weight: 50
url: /fr/python-net/aspose.psd.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | Initialise une nouvelle instance de la classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) avec le chemin spécifié. |
| [PathGradientBrush(points)](#PathGradientBrush_points_2) | Initialise une nouvelle instance de la classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) avec les points spécifiés. |
| [PathGradientBrush(points)](#PathGradientBrush_points_3) | Initialise une nouvelle instance de la classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) avec les points spécifiés. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_4) | Initialise une nouvelle instance de la classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) avec les points spécifiés et le mode d'enroulement. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_5) | Initialise une nouvelle instance de la classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) avec les points spécifiés et le mode d'enroulement. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Obtient ou définit un [Blend](/psd/python-net/aspose.psd/blend/) qui spécifie les positions et les facteurs qui définissent une atténuation personnalisée pour le dégradé. |
| center_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtient ou définit la couleur au centre du dégradé de chemin. |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Obtient ou définit le point central du dégradé de chemin. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Obtient ou définit le point de focalisation pour la diminution du dégradé. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | Obtient le chemin graphique sur lequel ce pinceau a été construit. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Obtient ou définit un [ColorBlend](/psd/python-net/aspose.psd/colorblend/) qui définit un dégradé linéaire multicolore. |
| is_transform_changed | bool | r | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple en définissant la matrice de transformation ou<br/>            en appelant l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la compatibilité descendante avec GDI+. |
| opacity | float | r/w | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est totalement opaque. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | Obtient les points du chemin sur lequel ce pinceau a été construit. |
| surround_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Obtient ou définit un tableau de couleurs correspondant aux points du chemin que remplit ce [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/). |
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
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Crée un dégradé avec une couleur centrale et une décroissance linéaire vers une couleur environnante. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Crée un dégradé avec une couleur centrale et une décroissance linéaire vers chaque couleur environnante. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Crée un pinceau de dégradé qui change de couleur en partant du centre du chemin vers la bordure du chemin. La transition d'une couleur à l'autre est basée sur une courbe en forme de cloche. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Crée un pinceau de dégradé qui change de couleur en partant du centre du chemin vers la bordure du chemin. La transition d'une couleur à l'autre est basée sur une courbe en forme de cloche. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Translater la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Translater la transformation géométrique locale des dimensions spécifiées dans l'ordre spécifié. |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

Initialise une nouvelle instance de la classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) avec le chemin spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) qui définit la zone remplie par ce [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/). |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_2}


```
 PathGradientBrush(points) 
```

Initialise une nouvelle instance de la classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) avec les points spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représente les points constituant les sommets du chemin. |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_3}


```
 PathGradientBrush(points) 
```

Initialise une nouvelle instance de la classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) avec les points spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représente les points constituant les sommets du chemin. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_4}


```
 PathGradientBrush(points, wrap_mode) 
```

Initialise une nouvelle instance de la classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) avec les points spécifiés et le mode d'enroulement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représente les points constituant les sommets du chemin. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Un [WrapMode](/psd/python-net/aspose.psd/wrapmode/) qui spécifie comment les remplissages dessinés avec ce [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) sont carrelés. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_5}


```
 PathGradientBrush(points, wrap_mode) 
```

Initialise une nouvelle instance de la classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) avec les points spécifiés et le mode d'enroulement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représente les points constituant les sommets du chemin. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Un [WrapMode](/psd/python-net/aspose.psd/wrapmode/) qui spécifie comment les remplissages dessinés avec ce [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) sont carrelés. |

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

Crée un dégradé avec une couleur centrale et une décroissance linéaire vers une couleur environnante.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie où, le long de tout rayon du centre du chemin jusqu'à la bordure du chemin, la couleur centrale atteindra son intensité maximale. Une valeur de 1 (la valeur par défaut) place l'intensité maximale au centre du chemin. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Crée un dégradé avec une couleur centrale et une décroissance linéaire vers chaque couleur environnante.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie où, le long de tout rayon du centre du chemin jusqu'à la bordure du chemin, la couleur centrale atteindra son intensité maximale. Une valeur de 1 (la valeur par défaut) place l'intensité maximale au centre du chemin. |
| scale | float | Une valeur comprise entre 0 et 1 qui spécifie l'intensité maximale de la couleur centrale qui se mélange avec la couleur de la bordure. Une valeur de 1 entraîne l'intensité maximale possible de la couleur centrale, et c'est la valeur par défaut. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Crée un pinceau de dégradé qui change de couleur en partant du centre du chemin vers la bordure du chemin. La transition d'une couleur à l'autre est basée sur une courbe en forme de cloche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie où, le long de tout rayon du centre du chemin jusqu'à la bordure du chemin, la couleur centrale atteindra son intensité maximale. Une valeur de 1 (la valeur par défaut) place l'intensité maximale au centre du chemin. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Crée un pinceau de dégradé qui change de couleur en partant du centre du chemin vers la bordure du chemin. La transition d'une couleur à l'autre est basée sur une courbe en forme de cloche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| focus | float | Une valeur comprise entre 0 et 1 qui spécifie où, le long de tout rayon du centre du chemin jusqu'à la bordure du chemin, la couleur centrale atteindra son intensité maximale. Une valeur de 1 (la valeur par défaut) place l'intensité maximale au centre du chemin. |
| scale | float | Une valeur comprise entre 0 et 1 qui spécifie l'intensité maximale de la couleur centrale qui se mélange avec la couleur de la bordure. Une valeur de 1 entraîne l'intensité maximale possible de la couleur centrale, et c'est la valeur par défaut. |

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

