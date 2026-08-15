---
title: "Clase Size"
type: docs
weight: 4080
url: /es/python-net/aspose.psd/size/
---

**Summary:** Represents size.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Size

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Size()](#Size__1) | Inicializa una nueva instancia de la clase Size |
| [Size(point)](#Size_point_2) | Inicializa una nueva instancia de la estructura [Size](/psd/python-net/aspose.psd/size/) a partir del [Point](/psd/python-net/aspose.psd/point/) especificado. |
| [Size(width, height)](#Size_width_height_3) | Inicializa una nueva instancia de la estructura [Size](/psd/python-net/aspose.psd/size/) a partir de las dimensiones especificadas. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| empty [static] | [Size](/psd/python-net/aspose.psd/size) | r | Obtiene una nueva instancia de la estructura [Size](/psd/python-net/aspose.psd/size/) que tiene los valores [Size.width](/psd/python-net/aspose.psd/size/) y [Size.height](/psd/python-net/aspose.psd/size/) establecidos en cero. |
| height | int | r/w | Obtiene o establece el componente vertical de este [Size](/psd/python-net/aspose.psd/size/). |
| is_empty | bool | r | Obtiene un valor que indica si este [Size](/psd/python-net/aspose.psd/size/) tiene ancho y alto de 0. |
| width | int | r/w | Obtiene o establece el componente horizontal de este [Size](/psd/python-net/aspose.psd/size/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Añade el ancho y alto de una estructura [Size](/psd/python-net/aspose.psd/size/) al ancho y alto de otra estructura [Size](/psd/python-net/aspose.psd/size/). |
| [ceiling(size)](#ceiling_size_2) | Convierte la estructura [SizeF](/psd/python-net/aspose.psd/sizef/) especificada a una estructura [Size](/psd/python-net/aspose.psd/size/) redondeando los valores de la estructura [Size](/psd/python-net/aspose.psd/size/) al siguiente entero superior. |
| [round(size)](#round_size_3) | Convierte la estructura [SizeF] especificada a una estructura [Size] redondeando los valores de la estructura [SizeF] al entero más cercano. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Resta el ancho y la altura de una estructura [Size] del ancho y la altura de otra estructura [Size]. |
| [truncate(size)](#truncate_size_5) | Convierte la estructura [SizeF] especificada a una estructura [Size] truncando los valores de la estructura [SizeF] al entero inferior más próximo. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Inicializa una nueva instancia de la clase Size

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

Inicializa una nueva instancia de la estructura [Size](/psd/python-net/aspose.psd/size/) a partir del [Point](/psd/python-net/aspose.psd/point/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | El [Point] desde el cual inicializar este [Size]. |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Inicializa una nueva instancia de la estructura [Size](/psd/python-net/aspose.psd/size/) a partir de las dimensiones especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El componente de ancho del nuevo [Size]. |
| height | int | El componente de altura del nuevo [Size]. |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Añade el ancho y alto de una estructura [Size](/psd/python-net/aspose.psd/size/) al ancho y alto de otra estructura [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | El primer [Size] a añadir. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | El segundo [Size] a añadir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Una estructura [Size] que es el resultado de la operación de suma. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Convierte la estructura [SizeF](/psd/python-net/aspose.psd/sizef/) especificada a una estructura [Size](/psd/python-net/aspose.psd/size/) redondeando los valores de la estructura [Size](/psd/python-net/aspose.psd/size/) al siguiente entero superior.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | La estructura [SizeF] a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | La estructura [Size] a la que este método convierte. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Convierte la estructura [SizeF] especificada a una estructura [Size] redondeando los valores de la estructura [SizeF] al entero más cercano.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | La estructura [SizeF] a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | La estructura [Size] a la que este método convierte. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Resta el ancho y la altura de una estructura [Size] del ancho y la altura de otra estructura [Size].

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | La estructura [Size] en el lado izquierdo del operador de resta. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | La estructura [Size] en el lado derecho del operador de resta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | La [Size] que es el resultado de la operación de resta. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Convierte la estructura [SizeF] especificada a una estructura [Size] truncando los valores de la estructura [SizeF] al entero inferior más próximo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | La estructura [SizeF] a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | La estructura [Size] a la que este método convierte. |


