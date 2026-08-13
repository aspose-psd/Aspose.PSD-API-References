---
title: "PolygonShape Classe"
type: docs
weight: 60
url: /fr/python-net/aspose.psd.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | Initialise une nouvelle instance de la classe [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
| [PolygonShape(points)](#PolygonShape_points_2) | Initialise une nouvelle instance de la classe [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | Initialise une nouvelle instance de la classe [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtient les limites de l'objet. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le centre de la forme. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point final de la forme. |
| has_segments | bool | r | Obtient une valeur indiquant si la forme possède des segments. |
| is_closed | bool | r/w | Obtient ou définit une valeur indiquant si la forme est fermée. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | Obtient ou définit les points de la courbe. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Obtient les segments de la forme. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point de départ de la forme. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtient les limites de l'objet. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtient les limites de l'objet. |
| reverse() | Inverse l'ordre des points pour cette forme. |
| [transform(transform)](#transform_transform_3) | Applique la transformation spécifiée à la forme. |


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

Initialise une nouvelle instance de la classe [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

Initialise une nouvelle instance de la classe [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Le tableau de points. |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

Initialise une nouvelle instance de la classe [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Le tableau de points. |
| is_closed | bool | Si défini sur <c>true</c> le polygone est fermé. |

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

