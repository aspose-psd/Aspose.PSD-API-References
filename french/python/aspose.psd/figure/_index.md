---
title: "Classe Figure"
type: docs
weight: 1220
url: /fr/python-net/aspose.psd/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Figure

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Figure()](#Figure__1) | Initialise une nouvelle instance de la classe Figure |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtient ou définit les limites de l'objet. |
| is_closed | bool | r/w | Obtient ou définit une valeur indiquant si cette figure est fermée. Une figure fermée ne fera une différence que dans le cas où<br/>            les formes de la première et de la dernière figure sont continues. Dans ce cas, le premier point de la première forme sera<br/>            relié par une ligne droite au dernier point de la dernière forme. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Obtient tous les segments de la figure. |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | r | Obtient les formes de la figure. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Ajoute une forme à la figure. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Ajoute une série de formes à la figure. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Obtient les limites de l'objet. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Obtient les limites de l'objet. |
| [remove_shape(shape)](#remove_shape_shape_5) | Supprime une forme de la figure. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Supprime une série de formes de la figure. |
| reverse() | Inverse l'ordre des formes de cette figure ainsi que l'ordre des points des formes. |
| [transform(transform)](#transform_transform_7) | Applique la transformation spécifiée à la forme. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Initialise une nouvelle instance de la classe Figure

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Ajoute une forme à la figure.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | La forme à ajouter. |

### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Ajoute une série de formes à la figure.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | Les formes à ajouter. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


```
 get_bounds(matrix) 
```

Obtient les limites de l'objet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La matrice à appliquer avant le calcul des limites sera calculée. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Les limites estimées de l'objet. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


```
 get_bounds(matrix, pen) 
```

Obtient les limites de l'objet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La matrice à appliquer avant le calcul des limites sera calculée. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Le crayon à utiliser pour l'objet. Cela peut influencer la taille des limites de l'objet. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Les limites estimées de l'objet. |


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Supprime une forme de la figure.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | La forme à supprimer. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Supprime une série de formes de la figure.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | La série de formes à supprimer. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

Applique la transformation spécifiée à la forme.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | La transformation à appliquer. |

