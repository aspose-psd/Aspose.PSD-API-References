---
title: "Clase Point"
type: docs
weight: 3530
url: /es/python-net/aspose.psd/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Point

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Point()](#Point__1) | Inicializa una nueva instancia de la clase Point |
| [Point(dw)](#Point_dw_2) | Inicializa una nueva instancia de la estructura [Point](/psd/python-net/aspose.psd/point/) usando coordenadas especificadas por un valor entero. |
| [Point(size)](#Point_size_3) | Inicializa una nueva instancia de la estructura [Point](/psd/python-net/aspose.psd/point/) a partir de la estructura [Size](/psd/python-net/aspose.psd/size/). |
| [Point(x, y)](#Point_x_y_4) | Inicializa una nueva instancia de la estructura [Point](/psd/python-net/aspose.psd/point/) con las coordenadas especificadas. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| empty [static] | [Point](/psd/python-net/aspose.psd/point) | r | Obtiene una nueva instancia de la estructura [Point](/psd/python-net/aspose.psd/point/) que tiene los valores [Point.x](/psd/python-net/aspose.psd/point/) y [Point.y](/psd/python-net/aspose.psd/point/) establecidos a cero. |
| is_empty | bool | r | Obtiene un valor que indica si este [Point](/psd/python-net/aspose.psd/point/) está vacío. |
| x | int | r/w | Obtiene o establece la coordenada x de este [Point](/psd/python-net/aspose.psd/point/). |
| y | int | r/w | Obtiene o establece la coordenada y de este [Point](/psd/python-net/aspose.psd/point/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Agrega el [Size](/psd/python-net/aspose.psd/size/) especificado al [Point](/psd/python-net/aspose.psd/point/) especificado. |
| [ceiling(point)](#ceiling_point_2) | Convierte el [PointF](/psd/python-net/aspose.psd/pointf/) especificado a un [Point](/psd/python-net/aspose.psd/point/) redondeando los valores del [PointF](/psd/python-net/aspose.psd/pointf/) al siguiente entero superior. |
| [offset(dx, dy)](#offset_dx_dy_3) | Traslada este [Point](/psd/python-net/aspose.psd/point/) por la cantidad especificada. |
| [offset(point)](#offset_point_4) | Traslada este [Point](/psd/python-net/aspose.psd/point/) por el [Point](/psd/python-net/aspose.psd/point/) especificado. |
| [round(point)](#round_point_5) | Convierte el [PointF](/psd/python-net/aspose.psd/pointf/) especificado a un objeto [Point](/psd/python-net/aspose.psd/point/) redondeando los valores del [Point](/psd/python-net/aspose.psd/point/) al entero más cercano. |
| [subtract(point, size)](#subtract_point_size_6) | Devuelve el resultado de restar el [Size](/psd/python-net/aspose.psd/size/) especificado del [Point](/psd/python-net/aspose.psd/point/) especificado. |
| [truncate(point)](#truncate_point_7) | Convierte el [PointF](/psd/python-net/aspose.psd/pointf/) especificado a un [Point](/psd/python-net/aspose.psd/point/) truncando los valores del [Point](/psd/python-net/aspose.psd/point/). |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Inicializa una nueva instancia de la clase Point

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Inicializa una nueva instancia de la estructura [Point](/psd/python-net/aspose.psd/point/) usando coordenadas especificadas por un valor entero.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dw | int | Entero de 32 bits que especifica las coordenadas del nuevo punto. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

Inicializa una nueva instancia de la estructura [Point](/psd/python-net/aspose.psd/point/) a partir de la estructura [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | Contiene las coordenadas del nuevo punto. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Inicializa una nueva instancia de la estructura [Point](/psd/python-net/aspose.psd/point/) con las coordenadas especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La posición horizontal del punto. |
| y | int | La posición vertical del punto. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Agrega el [Size](/psd/python-net/aspose.psd/size/) especificado al [Point](/psd/python-net/aspose.psd/point/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | El [Point](/psd/python-net/aspose.psd/point/) al que se añadirá. |
| size | [Size](/psd/python-net/aspose.psd/size) | El [Size](/psd/python-net/aspose.psd/size/) que se añadirá al <paramref name="point" />. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | El [Point](/psd/python-net/aspose.psd/point/) que es el resultado de la operación de suma. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Convierte el [PointF](/psd/python-net/aspose.psd/pointf/) especificado a un [Point](/psd/python-net/aspose.psd/point/) redondeando los valores del [PointF](/psd/python-net/aspose.psd/pointf/) al siguiente entero superior.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | El [PointF](/psd/python-net/aspose.psd/pointf/) a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | El [Point](/psd/python-net/aspose.psd/point/) al que este método convierte. |


### Method: offset(dx, dy) {#offset_dx_dy_3}


```
 offset(dx, dy) 
```

Traslada este [Point](/psd/python-net/aspose.psd/point/) por la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | int | La cantidad para desplazar la coordenada x. |
| dy | int | La cantidad para desplazar la coordenada y. |

### Method: offset(point) {#offset_point_4}


```
 offset(point) 
```

Traslada este [Point](/psd/python-net/aspose.psd/point/) por el [Point](/psd/python-net/aspose.psd/point/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | El [Point](/psd/python-net/aspose.psd/point/) usado para desplazar este [Point](/psd/python-net/aspose.psd/point/). |

### Method: round(point)  [static] {#round_point_5}


```
 round(point) 
```

Convierte el [PointF](/psd/python-net/aspose.psd/pointf/) especificado a un objeto [Point](/psd/python-net/aspose.psd/point/) redondeando los valores del [Point](/psd/python-net/aspose.psd/point/) al entero más cercano.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | El [PointF](/psd/python-net/aspose.psd/pointf/) a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | El [Point](/psd/python-net/aspose.psd/point/) al que este método convierte. |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

Devuelve el resultado de restar el [Size](/psd/python-net/aspose.psd/size/) especificado del [Point](/psd/python-net/aspose.psd/point/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | El [Point](/psd/python-net/aspose.psd/point/) del cual se restará. |
| size | [Size](/psd/python-net/aspose.psd/size) | El [Size](/psd/python-net/aspose.psd/size/) que se restará del <paramref name="point" />. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | El [Point](/psd/python-net/aspose.psd/point/) que es el resultado de la operación de resta. |


### Method: truncate(point)  [static] {#truncate_point_7}


```
 truncate(point) 
```

Convierte el [PointF](/psd/python-net/aspose.psd/pointf/) especificado a un [Point](/psd/python-net/aspose.psd/point/) truncando los valores del [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | El [PointF](/psd/python-net/aspose.psd/pointf/) a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | El [Point](/psd/python-net/aspose.psd/point/) al que este método convierte. |


