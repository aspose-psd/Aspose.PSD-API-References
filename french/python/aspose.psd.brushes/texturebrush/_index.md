---
title: "Classe TextureBrush"
type: docs
weight: 90
url: /fr/python-net/aspose.psd.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class is a [Brush](/psd/python-net/aspose.psd/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.TextureBrush

**Inheritance:** TransformBrush

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Initialise une nouvelle instance de la classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) qui utilise l'image spécifiée. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Initialise une nouvelle instance de la classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) qui utilise l'image spécifiée et le rectangle englobant. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Initialise une nouvelle instance de la classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) qui utilise l'image spécifiée et le rectangle englobant. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Initialise une nouvelle instance de la classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) qui utilise l'image spécifiée, le rectangle englobant et les attributs d'image. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Initialise une nouvelle instance de la classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) qui utilise l'image spécifiée, le rectangle englobant et les attributs d'image. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Initialise une nouvelle instance de la classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) qui utilise l'image spécifiée et le mode d'habillage. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Initialise une nouvelle instance de la classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) qui utilise l'image spécifiée, le mode d'habillage et le rectangle englobant. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Initialise une nouvelle instance de la classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) qui utilise l'image spécifiée, le mode d'habillage et le rectangle englobant. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Obtient l'objet [Image](/psd/python-net/aspose.psd/image/) associé à cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | r | Obtient les [TextureBrush.image_attributes](/psd/python-net/aspose.psd.brushes/texturebrush/) associés à ce [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtient le [Rectangle](/psd/python-net/aspose.psd/rectangle/) associé à ce [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| is_transform_changed | bool | r | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple en définissant la matrice de transformation ou<br/>            en appelant l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la compatibilité descendante avec GDI+. |
| opacity | float | r/w | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est totalement opaque. |
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


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) qui utilise l'image spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'objet [Image](/psd/python-net/aspose.psd/image/) avec lequel cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) remplit les intérieurs. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) qui utilise l'image spécifiée et le rectangle englobant.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'objet [Image](/psd/python-net/aspose.psd/image/) avec lequel cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) remplit les intérieurs. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente le rectangle englobant pour cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) qui utilise l'image spécifiée et le rectangle englobant.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'objet [Image](/psd/python-net/aspose.psd/image/) avec lequel cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) remplit les intérieurs. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente le rectangle englobant pour cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) qui utilise l'image spécifiée, le rectangle englobant et les attributs d'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'objet [Image](/psd/python-net/aspose.psd/image/) avec lequel cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) remplit les intérieurs. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente le rectangle englobant pour cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Un objet [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) qui contient des informations supplémentaires sur l'image utilisée par cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) qui utilise l'image spécifiée, le rectangle englobant et les attributs d'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'objet [Image](/psd/python-net/aspose.psd/image/) avec lequel cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) remplit les intérieurs. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente le rectangle englobant pour cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Un objet [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) qui contient des informations supplémentaires sur l'image utilisée par cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) qui utilise l'image spécifiée et le mode d'habillage.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'objet [Image](/psd/python-net/aspose.psd/image/) avec lequel cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) remplit les intérieurs. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Une énumération [WrapMode](/psd/python-net/aspose.psd/wrapmode/) qui spécifie comment cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) est carrelé. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) qui utilise l'image spécifiée, le mode d'habillage et le rectangle englobant.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'objet [Image](/psd/python-net/aspose.psd/image/) avec lequel cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) remplit les intérieurs. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Une énumération [WrapMode](/psd/python-net/aspose.psd/wrapmode/) qui spécifie comment cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) est carrelé. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente le rectangle englobant pour cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initialise une nouvelle instance de la classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) qui utilise l'image spécifiée, le mode d'habillage et le rectangle englobant.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'objet [Image](/psd/python-net/aspose.psd/image/) avec lequel cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) remplit les intérieurs. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Une énumération [WrapMode](/psd/python-net/aspose.psd/wrapmode/) qui spécifie comment cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) est carrelé. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente le rectangle englobant pour cet objet [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

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

