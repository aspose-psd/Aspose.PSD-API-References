---
title: "Classe PathMulticolorGradientBrush"
type: docs
weight: 70
url: /fr/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathMulticolorGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PathMulticolorGradientBrush(path)](#PathMulticolorGradientBrush_path_1) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) avec le chemin spécifié. |
| [PathMulticolorGradientBrush(points)](#PathMulticolorGradientBrush_points_2) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) avec les points spécifiés. |
| [PathMulticolorGradientBrush(points)](#PathMulticolorGradientBrush_points_3) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) avec les points spécifiés. |
| [PathMulticolorGradientBrush(points, wrap_mode)](#PathMulticolorGradientBrush_points_wrap_mode_4) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) avec les points spécifiés et le mode d'habillage. |
| [PathMulticolorGradientBrush(points, wrap_mode)](#PathMulticolorGradientBrush_points_wrap_mode_5) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) avec les points spécifiés et le mode d'habillage. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Obtient ou définit le point central du dégradé de chemin. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Obtient ou définit le point de focalisation pour la diminution du dégradé. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | Obtient le chemin graphique sur lequel ce pinceau a été construit. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Obtient ou définit un [ColorBlend](/psd/python-net/aspose.psd/colorblend/) qui définit un dégradé linéaire multicolore. |
| is_transform_changed | bool | r | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple en définissant la matrice de transformation ou<br/>            en appelant l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la compatibilité descendante avec GDI+. |
| opacity | float | r/w | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est totalement opaque. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | Obtient les points du chemin sur lequel ce pinceau a été construit. |
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


### Constructor: PathMulticolorGradientBrush(path) {#PathMulticolorGradientBrush_path_1}


```
 PathMulticolorGradientBrush(path) 
```

Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) avec le chemin spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) qui définit la zone remplie par ce [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/). |

### Constructor: PathMulticolorGradientBrush(points) {#PathMulticolorGradientBrush_points_2}


```
 PathMulticolorGradientBrush(points) 
```

Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) avec les points spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représente les points constituant les sommets du chemin. |

### Constructor: PathMulticolorGradientBrush(points) {#PathMulticolorGradientBrush_points_3}


```
 PathMulticolorGradientBrush(points) 
```

Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) avec les points spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représente les points constituant les sommets du chemin. |

### Constructor: PathMulticolorGradientBrush(points, wrap_mode) {#PathMulticolorGradientBrush_points_wrap_mode_4}


```
 PathMulticolorGradientBrush(points, wrap_mode) 
```

Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) avec les points spécifiés et le mode d'habillage.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représente les points constituant les sommets du chemin. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Un [WrapMode](/psd/python-net/aspose.psd/wrapmode/) qui spécifie comment les remplissages dessinés avec ce [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) sont juxtaposés. |

### Constructor: PathMulticolorGradientBrush(points, wrap_mode) {#PathMulticolorGradientBrush_points_wrap_mode_5}


```
 PathMulticolorGradientBrush(points, wrap_mode) 
```

Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) avec les points spécifiés et le mode d'habillage.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représente les points constituant les sommets du chemin. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Un [WrapMode](/psd/python-net/aspose.psd/wrapmode/) qui spécifie comment les remplissages dessinés avec ce [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) sont juxtaposés. |

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

