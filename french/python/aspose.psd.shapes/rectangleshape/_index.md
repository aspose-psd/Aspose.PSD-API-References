---
title: "RectangleShape Classe"
type: docs
weight: 80
url: /fr/python-net/aspose.psd.shapes/rectangleshape/
---

**Summary:** Represents a rectangular shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.RectangleShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RectangleShape()](#RectangleShape__1) | Initialise une nouvelle instance de la classe [RectangleShape](/psd/python-net/aspose.psd.shapes/rectangleshape/). |
| [RectangleShape(rectangle)](#RectangleShape_rectangle_2) | Initialise une nouvelle instance de la classe [RectangleShape](/psd/python-net/aspose.psd.shapes/rectangleshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtient les limites de l'objet. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le centre de la forme. |
| has_segments | bool | r | Obtient une valeur indiquant si la forme possède des segments. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point inférieur gauche du rectangle. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point supérieur gauche du rectangle. |
| rectangle_height | double | r | Obtient la hauteur du rectangle. |
| rectangle_width | double | r | Obtient la largeur du rectangle. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point inférieur droit du rectangle. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point supérieur droit du rectangle. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Obtient les segments de la forme. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtient les limites de l'objet. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtient les limites de l'objet. |
| [transform(transform)](#transform_transform_3) | Applique la transformation spécifiée à la forme. |


### Constructor: RectangleShape() {#RectangleShape__1}


```
 RectangleShape() 
```

Initialise une nouvelle instance de la classe [RectangleShape](/psd/python-net/aspose.psd.shapes/rectangleshape/).

### Constructor: RectangleShape(rectangle) {#RectangleShape_rectangle_2}


```
 RectangleShape(rectangle) 
```

Initialise une nouvelle instance de la classe [RectangleShape](/psd/python-net/aspose.psd.shapes/rectangleshape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le rectangle. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


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


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Applique la transformation spécifiée à la forme.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | La transformation à appliquer. |

