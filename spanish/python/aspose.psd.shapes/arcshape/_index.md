---
title: "Clase ArcShape"
type: docs
weight: 10
url: /es/python-net/aspose.psd.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | Inicializa una nueva instancia de la clase [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | Inicializa una nueva instancia de la clase [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | Inicializa una nueva instancia de la clase [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtiene los límites del objeto. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el centro de la forma. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el punto final de la forma. |
| has_segments | bool | r | Obtiene un valor que indica si la forma tiene segmentos. |
| is_closed | bool | r/w | Obtiene o establece un valor que indica si la forma ordenada está cerrada. Al procesar una forma ordenada cerrada, los puntos de inicio y fin no tienen significado. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el punto inferior izquierdo del rectángulo. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el punto superior izquierdo del rectángulo. |
| rectangle_height | double | r | Obtiene la altura del rectángulo. |
| rectangle_width | double | r | Obtiene el ancho del rectángulo. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el punto inferior derecho del rectángulo. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el punto superior derecho del rectángulo. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Obtiene los segmentos de la forma. |
| start_angle | float | r/w | Obtiene o establece el ángulo inicial. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el punto inicial de la forma. |
| sweep_angle | float | r/w | Obtiene o establece el ángulo de barrido. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtiene los límites del objeto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtiene los límites del objeto. |
| reverse() | Invierte el orden de los puntos de esta forma. |
| [transform(transform)](#transform_transform_3) | Aplica la transformación especificada a la forma. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

Inicializa una nueva instancia de la clase [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

Inicializa una nueva instancia de la clase [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El rectángulo. |
| start_angle | float | El ángulo inicial. |
| sweep_angle | float | El ángulo de barrido. |

### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

Inicializa una nueva instancia de la clase [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El rectángulo. |
| start_angle | float | El ángulo inicial. |
| sweep_angle | float | El ángulo de barrido. |
| is_closed | bool | Si se establece en <c>true</c> el arco está cerrado. El arco cerrado en realidad se degenera en una elipse. |

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

