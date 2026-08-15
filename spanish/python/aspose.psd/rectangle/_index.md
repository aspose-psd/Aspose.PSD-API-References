---
title: "Clase Rectangle"
type: docs
weight: 3810
url: /es/python-net/aspose.psd/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Rectangle

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Inicializa una nueva instancia de la clase Rectangle |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Inicializa una nueva instancia de la estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) con la ubicación y el tamaño especificados. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Inicializa una nueva instancia de la estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) con la ubicación y el tamaño especificados. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bottom | int | r/w | Obtiene o establece la coordenada y que es la suma de los valores de las propiedades [Rectangle.y](/psd/python-net/aspose.psd/rectangle/) y [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| empty [static] | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Obtiene una nueva instancia de la estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) que tiene los valores [Rectangle.x](/psd/python-net/aspose.psd/rectangle/), [Rectangle.y](/psd/python-net/aspose.psd/rectangle/), [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) y [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) establecidos en cero. |
| height | int | r/w | Obtiene o establece la altura de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| is_empty | bool | r | Obtiene un valor que indica si todas las propiedades numéricas de este [Rectangle](/psd/python-net/aspose.psd/rectangle/) tienen valores cero. |
| left | int | r/w | Obtiene o establece la coordenada x del borde izquierdo de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| location | [Point](/psd/python-net/aspose.psd/point) | r/w | Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| right | int | r/w | Obtiene o establece la coordenada x que es la suma de los valores de las propiedades [Rectangle.x](/psd/python-net/aspose.psd/rectangle/) y [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| size | [Size](/psd/python-net/aspose.psd/size) | r/w | Obtiene o establece el tamaño de este [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| top | int | r/w | Obtiene o establece la coordenada y del borde superior de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| width | int | r/w | Obtiene o establece el ancho de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| x | int | r/w | Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| y | int | r/w | Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Convierte la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada a una estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) redondeando los valores de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) al siguiente entero superior. |
| [contains(point)](#contains_point_2) | Determina si el punto especificado está contenido dentro de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [contains(rect)](#contains_rect_3) | Determina si la región rectangular representada por <paramref name="rect" /> está completamente contenida dentro de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [contains(x, y)](#contains_x_y_4) | Determina si el punto especificado está contenido dentro de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_5) | Crea una estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) con las ubicaciones de los bordes especificadas. |
| [from_points(point1, point2)](#from_points_point1_point2_6) | Crea un nuevo [Rectangle](/psd/python-net/aspose.psd/rectangle/) a partir de dos puntos especificados. Los dos bordes verticales del [Rectangle] creado serán iguales a los valores de <paramref name="point1" /> y <paramref name="point2" />. Estos suelen ser los vértices opuestos. |
| [inflate(rect, x, y)](#inflate_rect_x_y_7) | Crea y devuelve una copia inflada de la estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) especificada. La copia se infla en la cantidad especificada. La estructura original [Rectangle](/psd/python-net/aspose.psd/rectangle/) permanece sin modificar. |
| [inflate(size)](#inflate_size_8) | Infla este [Rectangle](/psd/python-net/aspose.psd/rectangle/) en la cantidad especificada. |
| [inflate(width, height)](#inflate_width_height_9) | Infla este [Rectangle](/psd/python-net/aspose.psd/rectangle/) en la cantidad especificada. |
| [intersect(a, b)](#intersect_a_b_10) | Devuelve una tercera estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) que representa la intersección de dos estructuras [Rectangle](/psd/python-net/aspose.psd/rectangle/) adicionales. Si no hay intersección, se devuelve un [Rectangle](/psd/python-net/aspose.psd/rectangle/) vacío. |
| [intersect(rect)](#intersect_rect_11) | Reemplaza este [Rectangle](/psd/python-net/aspose.psd/rectangle/) con la intersección de sí mismo y el [Rectangle](/psd/python-net/aspose.psd/rectangle/) especificado. |
| [intersects_with(rect)](#intersects_with_rect_12) | Determina si este rectángulo intersecta con <paramref name="rect" />. |
| normalize() | Normaliza el rectángulo haciendo que su ancho y alto sean positivos, que la izquierda sea menor que la derecha y que la parte superior sea menor que la inferior. |
| [offset(pos)](#offset_pos_13) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [offset(x, y)](#offset_x_y_14) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [round(value)](#round_value_15) | Convierte el [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificado a un [Rectangle](/psd/python-net/aspose.psd/rectangle/) redondeando los valores del [RectangleF](/psd/python-net/aspose.psd/rectanglef/) al entero más cercano. |
| [truncate(value)](#truncate_value_16) | Convierte el [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificado a un [Rectangle](/psd/python-net/aspose.psd/rectangle/) truncando los valores del [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [union(a, b)](#union_a_b_17) | Obtiene una estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) que contiene la unión de dos estructuras [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Inicializa una nueva instancia de la clase Rectangle

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Inicializa una nueva instancia de la estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) con la ubicación y el tamaño especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | Un [Point](/psd/python-net/aspose.psd/point/) que representa la esquina superior izquierda de la región rectangular. |
| size | [Size](/psd/python-net/aspose.psd/size) | Un [Size](/psd/python-net/aspose.psd/size/) que representa el ancho y la altura de la región rectangular. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Inicializa una nueva instancia de la estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) con la ubicación y el tamaño especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo. |
| width | int | El ancho del rectángulo. |
| altura | int | La altura del rectángulo. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Convierte la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada a una estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) redondeando los valores de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) al siguiente entero superior.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Devuelve un [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Determina si el punto especificado está contenido dentro de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | El [Point](/psd/python-net/aspose.psd/point/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto representado por <paramref name="point" /> está contenido dentro de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/); de lo contrario, false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Determina si la región rectangular representada por <paramref name="rect" /> está completamente contenida dentro de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El [Rectangle](/psd/python-net/aspose.psd/rectangle/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si la región rectangular representada por <paramref name="rect" /> está completamente contenida dentro de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/); de lo contrario, false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Determina si el punto especificado está contenido dentro de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto definido por <paramref name="x" /> y <paramref name="y" /> está contenido dentro de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/); de lo contrario, false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_5}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Crea una estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) con las ubicaciones de los bordes especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| left | int | La coordenada x de la esquina superior izquierda de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| top | int | La coordenada y de la esquina superior izquierda de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| right | int | La coordenada x de la esquina inferior derecha de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| bottom | int | La coordenada y de la esquina inferior derecha de esta estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | El nuevo [Rectangle](/psd/python-net/aspose.psd/rectangle/) que crea este método. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_6}


```
 from_points(point1, point2) 
```

Crea un nuevo [Rectangle](/psd/python-net/aspose.psd/rectangle/) a partir de dos puntos especificados. Los dos bordes verticales del [Rectangle] creado serán iguales a los valores de <paramref name="point1" /> y <paramref name="point2" />. Estos suelen ser los vértices opuestos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | El primer [Point](/psd/python-net/aspose.psd/point/) para el nuevo rectángulo. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | El segundo [Point](/psd/python-net/aspose.psd/point/) para el nuevo rectángulo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un [Rectangle](/psd/python-net/aspose.psd/rectangle/) recién creado. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_7}


```
 inflate(rect, x, y) 
```

Crea y devuelve una copia inflada de la estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) especificada. La copia se infla en la cantidad especificada. La estructura original [Rectangle](/psd/python-net/aspose.psd/rectangle/) permanece sin modificar.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El [Rectangle](/psd/python-net/aspose.psd/rectangle/) con el que iniciar. Este rectángulo no se modifica. |
| x | int | La cantidad para inflar horizontalmente este [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| y | int | La cantidad para inflar verticalmente este [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | El [Rectangle](/psd/python-net/aspose.psd/rectangle/) inflado. |


### Method: inflate(size) {#inflate_size_8}


```
 inflate(size) 
```

Infla este [Rectangle](/psd/python-net/aspose.psd/rectangle/) en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | La cantidad para inflar este rectángulo. |

### Method: inflate(width, height) {#inflate_width_height_9}


```
 inflate(width, height) 
```

Infla este [Rectangle](/psd/python-net/aspose.psd/rectangle/) en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | La cantidad para inflar horizontalmente este [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| height | int | La cantidad para inflar verticalmente este [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

### Method: intersect(a, b)  [static] {#intersect_a_b_10}


```
 intersect(a, b) 
```

Devuelve una tercera estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) que representa la intersección de dos estructuras [Rectangle](/psd/python-net/aspose.psd/rectangle/) adicionales. Si no hay intersección, se devuelve un [Rectangle](/psd/python-net/aspose.psd/rectangle/) vacío.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un primer rectángulo para intersectar. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un segundo rectángulo para intersectar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un [Rectangle](/psd/python-net/aspose.psd/rectangle/) que representa la intersección de <paramref name="a" /> y <paramref name="b" />. |


### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Reemplaza este [Rectangle](/psd/python-net/aspose.psd/rectangle/) con la intersección de sí mismo y el [Rectangle](/psd/python-net/aspose.psd/rectangle/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El [Rectangle](/psd/python-net/aspose.psd/rectangle/) con el que intersectar. |

### Method: intersects_with(rect) {#intersects_with_rect_12}


```
 intersects_with(rect) 
```

Determina si este rectángulo intersecta con <paramref name="rect" />.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo para probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si hay alguna intersección, de lo contrario false. |


### Method: offset(pos) {#offset_pos_13}


```
 offset(pos) 
```

Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pos | [Point](/psd/python-net/aspose.psd/point) | Cantidad para desplazar la ubicación. |

### Method: offset(x, y) {#offset_x_y_14}


```
 offset(x, y) 
```

Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | El desplazamiento horizontal. |
| y | int | El desplazamiento vertical. |

### Method: round(value)  [static] {#round_value_15}


```
 round(value) 
```

Convierte el [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificado a un [Rectangle](/psd/python-net/aspose.psd/rectangle/) redondeando los valores del [RectangleF](/psd/python-net/aspose.psd/rectanglef/) al entero más cercano.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El [RectangleF](/psd/python-net/aspose.psd/rectanglef/) a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un nuevo [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_16}


```
 truncate(value) 
```

Convierte el [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificado a un [Rectangle](/psd/python-net/aspose.psd/rectangle/) truncando los valores del [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El [RectangleF](/psd/python-net/aspose.psd/rectanglef/) a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un nuevo [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_17}


```
 union(a, b) 
```

Obtiene una estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) que contiene la unión de dos estructuras [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un primer rectángulo para la unión. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un segundo rectángulo para la unión. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Una estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) que delimita la unión de las dos estructuras [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


