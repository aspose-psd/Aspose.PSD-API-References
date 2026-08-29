---
title: "Classe Pen"
type: docs
weight: 3360
url: /fr/python-net/aspose.psd/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Pen

**Inheritance:** TransparencySupporter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Initialise une nouvelle instance de la classe [Pen](/psd/python-net/aspose.psd/pen/) avec le [Pen.brush](/psd/python-net/aspose.psd/pen/) spécifié. |
| [Pen(brush, width)](#Pen_brush_width_2) | Initialise une nouvelle instance de la classe [Pen](/psd/python-net/aspose.psd/pen/) avec le [Pen.brush](/psd/python-net/aspose.psd/pen/) et le [Pen.width](/psd/python-net/aspose.psd/pen/) spécifiés. |
| [Pen(color)](#Pen_color_3) | Initialise une nouvelle instance de la classe [Pen](/psd/python-net/aspose.psd/pen/) avec la couleur spécifiée. |
| [Pen(color, width)](#Pen_color_width_4) | Initialise une nouvelle instance de la classe [Pen](/psd/python-net/aspose.psd/pen/) avec les propriétés [Pen.color](/psd/python-net/aspose.psd/pen/) et [Pen.width](/psd/python-net/aspose.psd/pen/) spécifiées. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/psd/python-net/aspose.psd/penalignment) | r/w | Obtient ou définit l'alignement pour ce [Pen](/psd/python-net/aspose.psd/pen/). |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | r/w | Obtient ou définit le [Pen.brush](/psd/python-net/aspose.psd/pen/) qui détermine les attributs de ce [Pen](/psd/python-net/aspose.psd/pen/). |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtient ou définit la couleur de ce [Pen](/psd/python-net/aspose.psd/pen/). |
| compound_array | float | r/w | Obtient ou définit un tableau de valeurs qui spécifie un stylo composé. Un stylo composé trace une ligne composée constituée de lignes parallèles et d'espaces. |
| custom_end_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Obtient ou définit un bouchon personnalisé à utiliser à l'extrémité des lignes tracées avec ce [Pen](/psd/python-net/aspose.psd/pen/). |
| custom_start_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Obtient ou définit un bouchon personnalisé à utiliser au début des lignes tracées avec ce [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | r/w | Obtient ou définit le style de bouchon utilisé à l'extrémité des tirets qui composent les lignes pointillées tracées avec ce [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_offset | float | r/w | Obtient ou définit la distance du début d'une ligne jusqu'au commencement d'un motif de tirets. |
| dash_pattern | float | r/w | Obtient ou définit un tableau de tirets et d'espaces personnalisés. |
| dash_style | [DashStyle](/psd/python-net/aspose.psd/dashstyle) | r/w | Obtient ou définit le style utilisé pour les lignes pointillées tracées avec ce [Pen](/psd/python-net/aspose.psd/pen/). |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Obtient ou définit le style de bouchon utilisé à l'extrémité des lignes tracées avec ce [Pen](/psd/python-net/aspose.psd/pen/). |
| line_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Obtient ou définit le style de jointure pour les extrémités de deux lignes consécutives tracées avec ce [Pen](/psd/python-net/aspose.psd/pen/). |
| miter_limit | float | r/w | Obtient ou définit la limite de l'épaisseur de la jointure sur un coin en onglet. |
| opacity | float | r/w | Obtient ou définit l'opacité de l'objet. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que l'objet est entièrement visible, une valeur de 1 signifie que l'objet est totalement opaque. |
| pen_type | [PenType](/psd/python-net/aspose.psd/pentype) | r | Obtient le style des lignes tracées avec ce [Pen](/psd/python-net/aspose.psd/pen/). |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Obtient ou définit le style de bouchon utilisé au début des lignes tracées avec ce [Pen](/psd/python-net/aspose.psd/pen/). |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Obtient ou définit une copie de la transformation géométrique pour ce [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | r/w | Obtient ou définit la largeur de ce [Pen](/psd/python-net/aspose.psd/pen/), en unités de l'objet Graphics utilisé pour le dessin. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [multiply_transform(matrix)](#multiply_transform_matrix_1) | Multiplie la matrice de transformation de ce [Pen](/psd/python-net/aspose.psd/pen/) par la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_2) | Multiplie la matrice de transformation de ce [Pen](/psd/python-net/aspose.psd/pen/) par la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée dans l'ordre indiqué. |
| reset_transform() | Réinitialise la matrice de transformation géométrique de ce [Pen](/psd/python-net/aspose.psd/pen/) à l'identité. |
| [rotate_transform(angle)](#rotate_transform_angle_3) | Fait pivoter la transformation géométrique locale de l'angle spécifié. Cette méthode préfixe la rotation à la transformation. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_4) | Fait pivoter la transformation géométrique locale de l'angle spécifié dans l'ordre indiqué. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_5) | Mise à l'échelle de la transformation géométrique locale par les facteurs spécifiés. Cette méthode préfixe la matrice d'échelle à la transformation. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_6) | Mise à l'échelle de la transformation géométrique locale par les facteurs spécifiés dans l'ordre spécifié. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_7) | Définit les valeurs qui déterminent le style de terminaison utilisé pour finir les lignes tracées par ce [Pen](/psd/python-net/aspose.psd/pen/). |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Translater la transformation géométrique locale selon les dimensions spécifiées. Cette méthode préfixe la translation à la transformation. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Translater la transformation géométrique locale selon les dimensions spécifiées dans l'ordre spécifié. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Initialise une nouvelle instance de la classe [Pen](/psd/python-net/aspose.psd/pen/) avec le [Pen.brush](/psd/python-net/aspose.psd/pen/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Un [Pen.brush](/psd/python-net/aspose.psd/pen/) qui détermine les propriétés de remplissage de ce [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Initialise une nouvelle instance de la classe [Pen](/psd/python-net/aspose.psd/pen/) avec le [Pen.brush](/psd/python-net/aspose.psd/pen/) et le [Pen.width](/psd/python-net/aspose.psd/pen/) spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Un [Pen.brush](/psd/python-net/aspose.psd/pen/) qui détermine les caractéristiques de ce [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | La largeur du nouveau [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Initialise une nouvelle instance de la classe [Pen](/psd/python-net/aspose.psd/pen/) avec la couleur spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Une structure [Pen.color](/psd/python-net/aspose.psd/pen/) qui indique la couleur de ce [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Initialise une nouvelle instance de la classe [Pen](/psd/python-net/aspose.psd/pen/) avec les propriétés [Pen.color](/psd/python-net/aspose.psd/pen/) et [Pen.width](/psd/python-net/aspose.psd/pen/) spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Une structure [Pen.color](/psd/python-net/aspose.psd/pen/) qui indique la couleur de ce [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | Une valeur indiquant la largeur de ce [Pen](/psd/python-net/aspose.psd/pen/). |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_1}


```
 multiply_transform(matrix) 
```

Multiplie la matrice de transformation de ce [Pen](/psd/python-net/aspose.psd/pen/) par la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | L'objet [Matrix](/psd/python-net/aspose.psd/matrix/) par lequel multiplier la matrice de transformation. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_2}


```
 multiply_transform(matrix, order) 
```

Multiplie la matrice de transformation de ce [Pen](/psd/python-net/aspose.psd/pen/) par la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Le [Matrix](/psd/python-net/aspose.psd/matrix/) par lequel multiplier la matrice de transformation. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordre dans lequel effectuer l'opération de multiplication. |

### Method: rotate_transform(angle) {#rotate_transform_angle_3}


```
 rotate_transform(angle) 
```

Fait pivoter la transformation géométrique locale de l'angle spécifié. Cette méthode préfixe la rotation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_4}


```
 rotate_transform(angle, order) 
```

Fait pivoter la transformation géométrique locale de l'angle spécifié dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) qui spécifie s'il faut ajouter ou préfixer la matrice de rotation. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_5}


```
 scale_transform(sx, sy) 
```

Mise à l'échelle de la transformation géométrique locale par les facteurs spécifiés. Cette méthode préfixe la matrice d'échelle à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_6}


```
 scale_transform(sx, sy, order) 
```

Mise à l'échelle de la transformation géométrique locale par les facteurs spécifiés dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) qui spécifie s'il faut ajouter ou préfixer la matrice d'échelle. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_7}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Définit les valeurs qui déterminent le style de terminaison utilisé pour finir les lignes tracées par ce [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Un [LineCap](/psd/python-net/aspose.psd/linecap/) qui représente le style de terminaison à utiliser au début des lignes tracées avec ce [Pen](/psd/python-net/aspose.psd/pen/). |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Un [LineCap](/psd/python-net/aspose.psd/linecap/) qui représente le style de terminaison à utiliser à la fin des lignes tracées avec ce [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | Un [LineCap](/psd/python-net/aspose.psd/linecap/) qui représente le style de terminaison à utiliser au début ou à la fin des lignes pointillées tracées avec ce [Pen](/psd/python-net/aspose.psd/pen/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Translater la transformation géométrique locale selon les dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la traduction en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Translater la transformation géométrique locale selon les dimensions spécifiées dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la traduction en y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordre (préfixer ou ajouter) dans lequel appliquer la traduction. |

