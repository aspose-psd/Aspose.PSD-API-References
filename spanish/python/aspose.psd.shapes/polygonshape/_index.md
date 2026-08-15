---
title: "Clase PolygonShape"
type: docs
weight: 60
url: /es/python-net/aspose.psd.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | Inicializa una nueva instancia de la clase [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
| [PolygonShape(points)](#PolygonShape_points_2) | Inicializa una nueva instancia de la clase [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | Inicializa una nueva instancia de la clase [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtiene los límites del objeto. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el centro de la forma. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el punto final de la forma. |
| has_segments | bool | r | Obtiene un valor que indica si la forma tiene segmentos. |
| is_closed | bool | r/w | Obtiene o establece un valor que indica si la forma está cerrada. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | Obtiene o establece los puntos de la curva. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Obtiene los segmentos de la forma. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el punto inicial de la forma. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtiene los límites del objeto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtiene los límites del objeto. |
| reverse() | Invierte el orden de los puntos de esta forma. |
| [transform(transform)](#transform_transform_3) | Aplica la transformación especificada a la forma. |


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

Inicializa una nueva instancia de la clase [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

Inicializa una nueva instancia de la clase [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | La matriz de puntos. |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

Inicializa una nueva instancia de la clase [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | La matriz de puntos. |
| is_closed | bool | Si se establece en <c>true</c> el polígono está cerrado. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Obtiene los límites del objeto.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La matriz a aplicar antes de los límites será calculada. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Los límites estimados del objeto. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Obtiene los límites del objeto.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La matriz a aplicar antes de los límites será calculada. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | El lápiz a usar para el objeto. Esto puede influir en el tamaño de los límites del objeto. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Los límites estimados del objeto. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Aplica la transformación especificada a la forma.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | La transformación a aplicar. |

