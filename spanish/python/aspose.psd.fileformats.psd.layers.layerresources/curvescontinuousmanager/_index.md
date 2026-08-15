---
title: "CurvesContinuousManager Clase"
type: docs
weight: 200
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates curves

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesContinuousManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [CurvesContinuousManager(max_channel_count)](#CurvesContinuousManager_max_channel_count_1) | Inicializa una nueva instancia de la clase [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Obtiene el número máximo de canales. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_curve_point(channel_index, x, y)](#add_curve_point_channel_index_x_y_1) | Agrega el punto de la curva. |
| [get_curve_point_by_index(channel_index, point_index)](#get_curve_point_by_index_channel_index_point_index_2) | Obtiene el punto de la curva por índice. |
| [get_curve_point_count(channel_index)](#get_curve_point_count_channel_index_3) | Obtiene el recuento de puntos de la curva. |
| [remove_curve_point(channel_index, point_index)](#remove_curve_point_channel_index_point_index_4) | Elimina el punto de la curva. |
| [update_curve_point(channel_index, point_index, x, y)](#update_curve_point_channel_index_point_index_x_y_5) | Actualiza el punto de la curva. |


### Constructor: CurvesContinuousManager(max_channel_count) {#CurvesContinuousManager_max_channel_count_1}


```
 CurvesContinuousManager(max_channel_count) 
```

Inicializa una nueva instancia de la clase [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| max_channel_count | int | El recuento máximo de canales. |

### Method: add_curve_point(channel_index, x, y) {#add_curve_point_channel_index_x_y_1}


```
 add_curve_point(channel_index, x, y) 
```

Agrega el punto de la curva.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| channel_index | int | Índice del canal. |
| x | byte | La ubicación x. |
| y | byte | La ubicación y. |

### Method: get_curve_point_by_index(channel_index, point_index) {#get_curve_point_by_index_channel_index_point_index_2}


```
 get_curve_point_by_index(channel_index, point_index) 
```

Obtiene el punto de la curva por índice.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| channel_index | int | Índice del canal. |
| point_index | int | Índice del punto. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Punto de curva por índice de canal |


### Method: get_curve_point_count(channel_index) {#get_curve_point_count_channel_index_3}


```
 get_curve_point_count(channel_index) 
```

Obtiene el recuento de puntos de la curva.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| channel_index | int | Índice del canal. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Recuento de puntos de curva en el canal |


### Method: remove_curve_point(channel_index, point_index) {#remove_curve_point_channel_index_point_index_4}


```
 remove_curve_point(channel_index, point_index) 
```

Elimina el punto de la curva.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| channel_index | int | Índice del canal. |
| point_index | int | Índice del punto. |

### Method: update_curve_point(channel_index, point_index, x, y) {#update_curve_point_channel_index_point_index_x_y_5}


```
 update_curve_point(channel_index, point_index, x, y) 
```

Actualiza el punto de la curva.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| channel_index | int | Índice del canal. |
| point_index | int | Índice del punto. |
| x | byte | La ubicación x. |
| y | byte | La ubicación y. |

