---
title: "Clase SizeF"
type: docs
weight: 4090
url: /es/python-net/aspose.psd/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SizeF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [SizeF()](#SizeF__1) | Inicializa una nueva instancia de la clase SizeF |
| [SizeF(point)](#SizeF_point_2) | Inicializa una nueva instancia de la estructura [SizeF](/psd/python-net/aspose.psd/sizef/) a partir del [PointF](/psd/python-net/aspose.psd/pointf/) especificado. |
| [SizeF(size)](#SizeF_size_3) | Inicializa una nueva instancia de la estructura [SizeF](/psd/python-net/aspose.psd/sizef/) a partir del [SizeF](/psd/python-net/aspose.psd/sizef/) especificado. |
| [SizeF(width, height)](#SizeF_width_height_4) | Inicializa una nueva instancia de la estructura [SizeF](/psd/python-net/aspose.psd/sizef/) a partir de las dimensiones especificadas. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/psd/python-net/aspose.psd/sizef) | r | Obtiene una nueva instancia de la estructura [SizeF](/psd/python-net/aspose.psd/sizef/) que tiene los valores [SizeF.width](/psd/python-net/aspose.psd/sizef/) y [SizeF.height](/psd/python-net/aspose.psd/sizef/) establecidos en cero. |
| height | float | r/w | Obtiene o establece el componente vertical de este [SizeF](/psd/python-net/aspose.psd/sizef/). |
| is_empty | bool | r | Obtiene un valor que indica si este [SizeF](/psd/python-net/aspose.psd/sizef/) tiene ancho y alto cero. |
| width | float | r/w | Obtiene o establece el componente horizontal de este [SizeF](/psd/python-net/aspose.psd/sizef/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Añade el ancho y alto de una estructura [SizeF](/psd/python-net/aspose.psd/sizef/) al ancho y alto de otra estructura [SizeF](/psd/python-net/aspose.psd/sizef/). |
| [subtract(size1, size2)](#subtract_size1_size2_2) | Resta el ancho y alto de una estructura [SizeF](/psd/python-net/aspose.psd/sizef/) del ancho y alto de otra estructura [SizeF](/psd/python-net/aspose.psd/sizef/). |
| [to_point_f()](#to_point_f__3) | Convierte un [SizeF](/psd/python-net/aspose.psd/sizef/) a un [PointF](/psd/python-net/aspose.psd/pointf/). |
| [to_size()](#to_size__4) | Convierte un [SizeF](/psd/python-net/aspose.psd/sizef/) a una estructura [Size](/psd/python-net/aspose.psd/size/) con valores de tamaño truncados. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Inicializa una nueva instancia de la clase SizeF

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Inicializa una nueva instancia de la estructura [SizeF](/psd/python-net/aspose.psd/sizef/) a partir del [PointF](/psd/python-net/aspose.psd/pointf/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | El [PointF](/psd/python-net/aspose.psd/pointf/) del cual inicializar este [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Inicializa una nueva instancia de la estructura [SizeF](/psd/python-net/aspose.psd/sizef/) a partir del [SizeF](/psd/python-net/aspose.psd/sizef/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | El [SizeF](/psd/python-net/aspose.psd/sizef/) del cual crear el nuevo [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Inicializa una nueva instancia de la estructura [SizeF](/psd/python-net/aspose.psd/sizef/) a partir de las dimensiones especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | float | El componente de ancho del nuevo [SizeF](/psd/python-net/aspose.psd/sizef/). |
| height | float | El componente de alto del nuevo [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Añade el ancho y alto de una estructura [SizeF](/psd/python-net/aspose.psd/sizef/) al ancho y alto de otra estructura [SizeF](/psd/python-net/aspose.psd/sizef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | El primer [SizeF](/psd/python-net/aspose.psd/sizef/) para agregar. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | El segundo [SizeF](/psd/python-net/aspose.psd/sizef/) para agregar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Una estructura [SizeF](/psd/python-net/aspose.psd/sizef/) que es el resultado de la operación de suma. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_2}


```
 subtract(size1, size2) 
```

Resta el ancho y alto de una estructura [SizeF](/psd/python-net/aspose.psd/sizef/) del ancho y alto de otra estructura [SizeF](/psd/python-net/aspose.psd/sizef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | La estructura [SizeF](/psd/python-net/aspose.psd/sizef/) en el lado izquierdo del operador de resta. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | La estructura [SizeF](/psd/python-net/aspose.psd/sizef/) en el lado derecho del operador de resta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | La [SizeF](/psd/python-net/aspose.psd/sizef/) que es el resultado de la operación de resta. |


### Method: to_point_f() {#to_point_f__3}


```
 to_point_f() 
```

Convierte un [SizeF](/psd/python-net/aspose.psd/sizef/) a un [PointF](/psd/python-net/aspose.psd/pointf/).

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Devuelve una estructura [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: to_size() {#to_size__4}


```
 to_size() 
```

Convierte un [SizeF](/psd/python-net/aspose.psd/sizef/) a una estructura [Size](/psd/python-net/aspose.psd/size/) con valores de tamaño truncados.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Devuelve una estructura [Size](/psd/python-net/aspose.psd/size/). |


