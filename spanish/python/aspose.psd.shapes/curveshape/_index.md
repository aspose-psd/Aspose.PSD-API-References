---
title: "Clase CurveShape"
type: docs
weight: 30
url: /es/python-net/aspose.psd.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Inicializa una nueva instancia de la clase [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
| [CurveShape(points)](#CurveShape_points_2) | Inicializa una nueva instancia de la clase [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Se utiliza la tensión predeterminada de 0.5. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Inicializa una nueva instancia de la clase [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Se utiliza la tensión predeterminada de 0.5. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Inicializa una nueva instancia de la clase [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Inicializa una nueva instancia de la clase [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
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
| tensión | float | r/w | Obtiene o establece la tensión de la curva. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtiene los límites del objeto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtiene los límites del objeto. |
| reverse() | Invierte el orden de los puntos de esta forma. |
| [transform(transform)](#transform_transform_3) | Aplica la transformación especificada a la forma. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Inicializa una nueva instancia de la clase [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Inicializa una nueva instancia de la clase [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Se utiliza la tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | La matriz de puntos. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Inicializa una nueva instancia de la clase [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Se utiliza la tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | La matriz de puntos. |
| is_closed | bool | si se establece en <c>true</c> la curva está cerrada. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Inicializa una nueva instancia de la clase [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | La matriz de puntos. |
| tensión | float | La tensión de la curva. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Inicializa una nueva instancia de la clase [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | La matriz de puntos. |
| tensión | float | La tensión de la curva. |
| is_closed | bool | si se establece en <c>true</c> la curva está cerrada. |

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

