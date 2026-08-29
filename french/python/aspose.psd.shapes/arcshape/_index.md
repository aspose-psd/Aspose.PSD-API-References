---
title: "ArcShape Classe"
type: docs
weight: 10
url: /fr/python-net/aspose.psd.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | Initialise une nouvelle instance de la classe [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | Initialise une nouvelle instance de la classe [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | Initialise une nouvelle instance de la classe [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtient les limites de l'objet. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le centre de la forme. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point final de la forme. |
| has_segments | bool | r | Obtient une valeur indiquant si la forme possède des segments. |
| is_closed | bool | r/w | Obtient ou définit une valeur indiquant si la forme ordonnée est fermée. Lors du traitement d'une forme ordonnée fermée, les points de départ et d'arrivée n'ont aucune signification. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point inférieur gauche du rectangle. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point supérieur gauche du rectangle. |
| rectangle_height | double | r | Obtient la hauteur du rectangle. |
| rectangle_width | double | r | Obtient la largeur du rectangle. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point inférieur droit du rectangle. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point supérieur droit du rectangle. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Obtient les segments de la forme. |
| start_angle | float | r/w | Obtient ou définit l'angle de départ. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point de départ de la forme. |
| sweep_angle | float | r/w | Obtient ou définit l'angle de balayage. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtient les limites de l'objet. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtient les limites de l'objet. |
| reverse() | Inverse l'ordre des points pour cette forme. |
| [transform(transform)](#transform_transform_3) | Applique la transformation spécifiée à la forme. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

Initialise une nouvelle instance de la classe [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

Initialise une nouvelle instance de la classe [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le rectangle. |
| start_angle | float | L'angle de départ. |
| sweep_angle | float | L'angle de balayage. |

### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

Initialise une nouvelle instance de la classe [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le rectangle. |
| start_angle | float | L'angle de départ. |
| sweep_angle | float | L'angle de balayage. |
| is_closed | bool | Si défini sur <c>true</c> l'arc est fermé. L'arc fermé dégénère en fait en une ellipse. |

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

