---
title: "Clase RectangleF"
type: docs
weight: 3830
url: /es/python-net/aspose.psd/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RectangleF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | Inicializa una nueva instancia de la clase RectangleF |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Inicializa una nueva instancia de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) con la ubicación y el tamaño especificados. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Inicializa una nueva instancia de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) con la ubicación y el tamaño especificados. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bottom | float | r/w | Obtiene o establece la coordenada y que es la suma de [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/) y [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| empty [static] | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtiene una nueva instancia de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que tiene los valores [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) y [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) establecidos en cero. |
| height | float | r/w | Obtiene o establece la altura de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| is_empty | bool | r | Obtiene un valor que indica si la propiedad [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) o [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) de esta [RectangleF](/psd/python-net/aspose.psd/rectanglef/) tiene un valor de cero. |
| left | float | r/w | Obtiene o establece la coordenada x del borde izquierdo de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| right | float | r/w | Obtiene o establece la coordenada x que es la suma de [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/) y [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Obtiene o establece el tamaño de esta [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| top | float | r/w | Obtiene o establece la coordenada y del borde superior de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| width | float | r/w | Obtiene o establece el ancho de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| x | float | r/w | Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| y | float | r/w | Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [contains(point)](#contains_point_1) | Determina si el punto especificado está contenido dentro de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [contains(rect)](#contains_rect_2) | Determina si la región rectangular representada por <paramref name="rect" /> está completamente contenida dentro de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [contains(x, y)](#contains_x_y_3) | Determina si el punto especificado está contenido dentro de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_4) | Crea una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) con la esquina superior izquierda y la esquina inferior derecha en las ubicaciones especificadas. |
| [from_points(point1, point2)](#from_points_point1_point2_5) | Crea un nuevo [Rectangle](/psd/python-net/aspose.psd/rectangle/) a partir de dos puntos especificados. Dos vértices del [Rectangle](/psd/python-net/aspose.psd/rectangle/) creado serán iguales a los pasados <paramref name="point1" /> y <paramref name="point2" />. Estos suelen ser los vértices opuestos. |
| [inflate(rect, x, y)](#inflate_rect_x_y_6) | Crea y devuelve una copia inflada de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada. La copia se infla en la cantidad especificada. El rectángulo original permanece sin modificar. |
| [inflate(size)](#inflate_size_7) | Infla este [RectangleF](/psd/python-net/aspose.psd/rectanglef/) en la cantidad especificada. |
| [inflate(x, y)](#inflate_x_y_8) | Infla esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) en la cantidad especificada. |
| [intersect(a, b)](#intersect_a_b_9) | Devuelve una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que representa la intersección de dos rectángulos. Si no hay intersección, se devuelve un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) vacío. |
| [intersect(rect)](#intersect_rect_10) | Reemplaza esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) con la intersección de ella misma y la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada. |
| [intersects_with(rect)](#intersects_with_rect_11) | Determina si este rectángulo intersecta con <paramref name="rect" />. |
| normalize() | Normaliza el rectángulo haciendo que su ancho y alto sean positivos, que la izquierda sea menor que la derecha y que la parte superior sea menor que la inferior. |
| [offset(pos)](#offset_pos_12) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [offset(x, y)](#offset_x_y_13) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [union(a, b)](#union_a_b_14) | Crea el tercer rectángulo más pequeño posible que pueda contener a ambos rectángulos que forman una unión. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

Inicializa una nueva instancia de la clase RectangleF

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Inicializa una nueva instancia de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) con la ubicación y el tamaño especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | Un [PointF](/psd/python-net/aspose.psd/pointf/) que representa la esquina superior izquierda de la región rectangular. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Un [SizeF](/psd/python-net/aspose.psd/sizef/) que representa el ancho y la altura de la región rectangular. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Inicializa una nueva instancia de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) con la ubicación y el tamaño especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo. |
| width | float | El ancho del rectángulo. |
| altura | float | La altura del rectángulo. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Determina si el punto especificado está contenido dentro de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | El [PointF](/psd/python-net/aspose.psd/pointf/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto representado por el parámetro <paramref name="point" /> está contenido dentro de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/); de lo contrario, false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Determina si la región rectangular representada por <paramref name="rect" /> está completamente contenida dentro de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El [RectangleF](/psd/python-net/aspose.psd/rectanglef/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si la región rectangular representada por <paramref name="rect" /> está completamente contenida dentro de la región rectangular representada por este [RectangleF](/psd/python-net/aspose.psd/rectanglef/); de lo contrario, false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Determina si el punto especificado está contenido dentro de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto definido por <paramref name="x" /> y <paramref name="y" /> está contenido dentro de esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/); de lo contrario false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_4}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Crea una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) con la esquina superior izquierda y la esquina inferior derecha en las ubicaciones especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| left | float | La coordenada x de la esquina superior izquierda de la región rectangular. |
| top | float | La coordenada y de la esquina superior izquierda de la región rectangular. |
| right | float | La coordenada x de la esquina inferior derecha de la región rectangular. |
| inferior | float | La coordenada y de la esquina inferior derecha de la región rectangular. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El nuevo [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que crea este método. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_5}


```
 from_points(point1, point2) 
```

Crea un nuevo [Rectangle](/psd/python-net/aspose.psd/rectangle/) a partir de dos puntos especificados. Dos vértices del [Rectangle](/psd/python-net/aspose.psd/rectangle/) creado serán iguales a los pasados <paramref name="point1" /> y <paramref name="point2" />. Estos suelen ser los vértices opuestos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | El primer [Point](/psd/python-net/aspose.psd/point/) para el nuevo rectángulo. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | El segundo [Point](/psd/python-net/aspose.psd/point/) para el nuevo rectángulo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un [Rectangle](/psd/python-net/aspose.psd/rectangle/) recién creado. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_6}


```
 inflate(rect, x, y) 
```

Crea y devuelve una copia inflada de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada. La copia se infla en la cantidad especificada. El rectángulo original permanece sin modificar.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El [RectangleF](/psd/python-net/aspose.psd/rectanglef/) a copiar. Este rectángulo no se modifica. |
| x | float | La cantidad para inflar la copia del rectángulo horizontalmente. |
| y | float | La cantidad para inflar la copia del rectángulo verticalmente. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El [RectangleF](/psd/python-net/aspose.psd/rectanglef/) inflado. |


### Method: inflate(size) {#inflate_size_7}


```
 inflate(size) 
```

Infla este [RectangleF](/psd/python-net/aspose.psd/rectanglef/) en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | La cantidad para inflar este rectángulo. |

### Method: inflate(x, y) {#inflate_x_y_8}


```
 inflate(x, y) 
```

Infla esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La cantidad para inflar esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) horizontalmente. |
| y | float | La cantidad para inflar esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) verticalmente. |

### Method: intersect(a, b)  [static] {#intersect_a_b_9}


```
 intersect(a, b) 
```

Devuelve una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que representa la intersección de dos rectángulos. Si no hay intersección, se devuelve un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) vacío.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un primer rectángulo para intersectar. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un segundo rectángulo para intersectar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una tercera estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) cuyo tamaño representa el área superpuesta de los dos rectángulos especificados. |


### Method: intersect(rect) {#intersect_rect_10}


```
 intersect(rect) 
```

Reemplaza esta estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) con la intersección de ella misma y la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El rectángulo para intersectar. |

### Method: intersects_with(rect) {#intersects_with_rect_11}


```
 intersects_with(rect) 
```

Determina si este rectángulo intersecta con <paramref name="rect" />.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El rectángulo para probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si hay alguna intersección. |


### Method: offset(pos) {#offset_pos_12}


```
 offset(pos) 
```

Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pos | [PointF](/psd/python-net/aspose.psd/pointf) | La cantidad para desplazar la ubicación. |

### Method: offset(x, y) {#offset_x_y_13}


```
 offset(x, y) 
```

Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La cantidad para desplazar la ubicación horizontalmente. |
| y | float | La cantidad para desplazar la ubicación verticalmente. |

### Method: union(a, b)  [static] {#union_a_b_14}


```
 union(a, b) 
```

Crea el tercer rectángulo más pequeño posible que pueda contener a ambos rectángulos que forman una unión.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un primer rectángulo para la unión. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un segundo rectángulo para la unión. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una tercera estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que contiene los dos rectángulos que forman la unión. |


