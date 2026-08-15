---
title: "Clase ObjectWithBounds"
type: docs
weight: 3170
url: /es/python-net/aspose.psd/objectwithbounds/
---

**Summary:** The object having bounds.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtiene los límites del objeto. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtiene los límites del objeto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtiene los límites del objeto. |
| [transform(transform)](#transform_transform_3) | Aplica la transformación especificada a la forma. |


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

