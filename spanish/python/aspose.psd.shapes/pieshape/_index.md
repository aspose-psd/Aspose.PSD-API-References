---
title: "Clase PieShape"
type: docs
weight: 50
url: /es/python-net/aspose.psd.shapes/pieshape/
---

**Summary:** Represents a pie shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.PieShape

**Inheritance:** EllipseShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PieShape()](#PieShape__1) | Inicializa una nueva instancia de la clase [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/). |
| [PieShape(rectangle, start_angle, sweep_angle)](#PieShape_rectangle_start_angle_sweep_angle_2) | Inicializa una nueva instancia de la clase [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtiene los límites del objeto. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el centro de la forma. |
| has_segments | bool | r | Obtiene un valor que indica si la forma tiene segmentos. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el punto inferior izquierdo del rectángulo. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el punto superior izquierdo del rectángulo. |
| rectangle_height | double | r | Obtiene la altura del rectángulo. |
| rectangle_width | double | r | Obtiene el ancho del rectángulo. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el punto inferior derecho del rectángulo. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtiene el punto superior derecho del rectángulo. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Obtiene los segmentos de la forma. |
| start_angle | float | r/w | Obtiene o establece el ángulo inicial. |
| sweep_angle | float | r/w | Obtiene o establece el ángulo de barrido. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtiene los límites del objeto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtiene los límites del objeto. |
| [transform(transform)](#transform_transform_3) | Aplica la transformación especificada a la forma. |


### Constructor: PieShape() {#PieShape__1}


```
 PieShape() 
```

Inicializa una nueva instancia de la clase [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/).

### Constructor: PieShape(rectangle, start_angle, sweep_angle) {#PieShape_rectangle_start_angle_sweep_angle_2}


```
 PieShape(rectangle, start_angle, sweep_angle) 
```

Inicializa una nueva instancia de la clase [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El rectángulo. |
| start_angle | float | El ángulo inicial. |
| sweep_angle | float | El ángulo de barrido. |

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

