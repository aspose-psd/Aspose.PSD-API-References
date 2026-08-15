---
title: "Clase Figure"
type: docs
weight: 1220
url: /es/python-net/aspose.psd/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Figure

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Figure()](#Figure__1) | Inicializa una nueva instancia de la clase Figure |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtiene o establece los límites del objeto. |
| is_closed | bool | r/w | Obtiene o establece un valor que indica si esta figura está cerrada. Una figura cerrada solo hará una diferencia en el caso en que<br/>            las formas primera y última de la figura sean formas continuas. En tal caso, el primer punto de la primera forma será<br/>            conectado por una línea recta desde el último punto de la última forma. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Obtiene todos los segmentos de la figura. |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | r | Obtiene las formas de la figura. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Agrega una forma a la figura. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Agrega un rango de formas a la figura. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Obtiene los límites del objeto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Obtiene los límites del objeto. |
| [remove_shape(shape)](#remove_shape_shape_5) | Elimina una forma de la figura. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Elimina un rango de formas de la figura. |
| reverse() | Invierte el orden de las formas de esta figura y el orden de los puntos de las formas. |
| [transform(transform)](#transform_transform_7) | Aplica la transformación especificada a la forma. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Inicializa una nueva instancia de la clase Figure

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Agrega una forma a la figura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | La forma a agregar. |

### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Agrega un rango de formas a la figura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | Las formas a agregar. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Elimina una forma de la figura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | La forma a eliminar. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Elimina un rango de formas de la figura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | El rango de formas a eliminar. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

Aplica la transformación especificada a la forma.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | La transformación a aplicar. |

