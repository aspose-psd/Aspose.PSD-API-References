---
title: "Clase Region"
type: docs
weight: 3870
url: /es/python-net/aspose.psd/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Region

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Region()](#Region__1) | Inicializa un nuevo [Region](/psd/python-net/aspose.psd/region/). |
| [Region(path)](#Region_path_2) | Inicializa un nuevo [Region](/psd/python-net/aspose.psd/region/) con el [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) especificado. |
| [Region(rect)](#Region_rect_3) | Inicializa un nuevo [Region](/psd/python-net/aspose.psd/region/) a partir de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada. |
| [Region(rect)](#Region_rect_4) | Inicializa un nuevo [Region](/psd/python-net/aspose.psd/region/) a partir de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [complement(path)](#complement_path_1) | Actualiza este [Region](/psd/python-net/aspose.psd/region/) para que contenga la porción del [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) especificado que no intersecta con este [Region](/psd/python-net/aspose.psd/region/). |
| [complement(rect)](#complement_rect_2) | Actualiza este [Region](/psd/python-net/aspose.psd/region/) para que contenga la porción de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada que no intersecta con este [Region](/psd/python-net/aspose.psd/region/). |
| [complement(rect)](#complement_rect_3) | Actualiza este [Region](/psd/python-net/aspose.psd/region/) para que contenga la porción de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada que no intersecta con este [Region](/psd/python-net/aspose.psd/region/). |
| [complement(region)](#complement_region_4) | Actualiza este [Region](/psd/python-net/aspose.psd/region/) para que contenga la porción del [Region](/psd/python-net/aspose.psd/region/) especificado que no intersecta con este [Region](/psd/python-net/aspose.psd/region/). |
| [deep_clone()](#deep_clone__5) | Crea una copia profunda exacta de este [Region](/psd/python-net/aspose.psd/region/). |
| [exclude(path)](#exclude_path_6) | Actualiza este [Region](/psd/python-net/aspose.psd/region/) para que contenga solo la porción de su interior que no intersecta con el [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) especificado. |
| [exclude(rect)](#exclude_rect_7) | Actualiza este [Region](/psd/python-net/aspose.psd/region/) para que contenga solo la porción de su interior que no intersecta con la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada. |
| [exclude(rect)](#exclude_rect_8) | Actualiza este [Region](/psd/python-net/aspose.psd/region/) para que contenga solo la porción de su interior que no intersecta con la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada. |
| [exclude(region)](#exclude_region_9) | Actualiza este [Region](/psd/python-net/aspose.psd/region/) para que contenga solo la porción de su interior que no intersecta con el [Region](/psd/python-net/aspose.psd/region/) especificado. |
| [intersect(path)](#intersect_path_10) | Actualiza este [Region](/psd/python-net/aspose.psd/region/) a la intersección de sí mismo con el [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) especificado. |
| [intersect(rect)](#intersect_rect_11) | Actualiza este [Region](/psd/python-net/aspose.psd/region/) a la intersección de sí mismo con la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada. |
| [intersect(rect)](#intersect_rect_12) | Actualiza este [Region](/psd/python-net/aspose.psd/region/) a la intersección de sí mismo con la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada. |
| [intersect(region)](#intersect_region_13) | Actualiza este [Region](/psd/python-net/aspose.psd/region/) a la intersección de sí mismo con el [Region](/psd/python-net/aspose.psd/region/) especificado. |
| [is_empty(g)](#is_empty_g_14) | Comprueba si este [Region](/psd/python-net/aspose.psd/region/) tiene un interior vacío en la superficie de dibujo especificada. |
| [is_infinite(g)](#is_infinite_g_15) | Comprueba si este [Region](/psd/python-net/aspose.psd/region/) tiene un interior infinito en la superficie de dibujo especificada. |
| [is_visible(point)](#is_visible_point_16) | Comprueba si la estructura [PointF](/psd/python-net/aspose.psd/pointf/) especificada está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(point)](#is_visible_point_17) | Comprueba si la estructura [PointF](/psd/python-net/aspose.psd/pointf/) especificada está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(point, g)](#is_visible_point_g_18) | Comprueba si la estructura [PointF](/psd/python-net/aspose.psd/pointf/) especificada está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/) cuando se dibuja usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado. |
| [is_visible(point, g)](#is_visible_point_g_19) | Comprueba si la estructura [PointF](/psd/python-net/aspose.psd/pointf/) especificada está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/) cuando se dibuja usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado. |
| [is_visible(rect)](#is_visible_rect_20) | Comprueba si alguna porción de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(rect)](#is_visible_rect_21) | Comprueba si alguna porción de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(rect, g)](#is_visible_rect_g_22) | Comprueba si alguna porción de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/) cuando se dibuja usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado. |
| [is_visible(rect, g)](#is_visible_rect_g_23) | Comprueba si alguna porción de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/) cuando se dibuja usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado. |
| [is_visible(x, y)](#is_visible_x_y_24) | Comprueba si el punto especificado está contenido dentro de este [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_25) | Comprueba si el punto especificado está contenido dentro de este [Region](/psd/python-net/aspose.psd/region/) cuando se dibuja usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado. |
| [is_visible(x, y, g)](#is_visible_x_y_g_26) | Comprueba si el punto especificado está contenido dentro de este [Region](/psd/python-net/aspose.psd/region/) cuando se dibuja usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado. |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_27) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de esta [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_28) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de esta [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_29) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de esta [Region](/psd/python-net/aspose.psd/region/) cuando se dibuja usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado. |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_30) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de esta [Region](/psd/python-net/aspose.psd/region/) cuando se dibuja usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado. |
| make_empty() | Inicializa esta [Region](/psd/python-net/aspose.psd/region/) con un interior vacío. |
| make_infinite() | Inicializa este objeto [Region](/psd/python-net/aspose.psd/region/) con un interior infinito. |
| [transform(matrix)](#transform_matrix_31) | Transforma esta [Region](/psd/python-net/aspose.psd/region/) mediante la [Matrix](/psd/python-net/aspose.psd/matrix/) especificada. |
| [translate(dx, dy)](#translate_dx_dy_32) | Desplaza las coordenadas de esta [Region](/psd/python-net/aspose.psd/region/) en la cantidad especificada. |
| [translate(dx, dy)](#translate_dx_dy_33) | Desplaza las coordenadas de esta [Region](/psd/python-net/aspose.psd/region/) en la cantidad especificada. |
| [union(path)](#union_path_34) | Actualiza esta [Region](/psd/python-net/aspose.psd/region/) a la unión de ella misma y el [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) especificado. |
| [union(rect)](#union_rect_35) | Actualiza esta [Region](/psd/python-net/aspose.psd/region/) a la unión de ella misma y la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada. |
| [union(rect)](#union_rect_36) | Actualiza esta [Region](/psd/python-net/aspose.psd/region/) a la unión de ella misma y la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada. |
| [union(region)](#union_region_37) | Actualiza esta [Region](/psd/python-net/aspose.psd/region/) a la unión de ella misma y la [Region](/psd/python-net/aspose.psd/region/) especificada. |
| [xor(path)](#xor_path_38) | Actualiza esta [Region](/psd/python-net/aspose.psd/region/) a la unión menos la intersección de ella misma con el [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) especificado. |
| [xor(rect)](#xor_rect_39) | Actualiza esta [Region](/psd/python-net/aspose.psd/region/) a la unión menos la intersección de ella misma con la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada. |
| [xor(rect)](#xor_rect_40) | Actualiza esta [Region](/psd/python-net/aspose.psd/region/) a la unión menos la intersección de ella misma con la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada. |
| [xor(region)](#xor_region_41) | Actualiza esta [Region](/psd/python-net/aspose.psd/region/) a la unión menos la intersección de ella misma con la [Region](/psd/python-net/aspose.psd/region/) especificada. |


### Constructor: Region() {#Region__1}


```
 Region() 
```

Inicializa un nuevo [Region](/psd/python-net/aspose.psd/region/).

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

Inicializa un nuevo [Region](/psd/python-net/aspose.psd/region/) con el [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) que define la nueva [Region](/psd/python-net/aspose.psd/region/). |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

Inicializa un nuevo [Region](/psd/python-net/aspose.psd/region/) a partir de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que define el interior de la nueva [Region](/psd/python-net/aspose.psd/region/). |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

Inicializa un nuevo [Region](/psd/python-net/aspose.psd/region/) a partir de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que define el interior de la nueva [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

Actualiza este [Region](/psd/python-net/aspose.psd/region/) para que contenga la porción del [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) especificado que no intersecta con este [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | El [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) para complementar esta [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

Actualiza este [Region](/psd/python-net/aspose.psd/region/) para que contenga la porción de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada que no intersecta con este [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) para complementar esta [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

Actualiza este [Region](/psd/python-net/aspose.psd/region/) para que contenga la porción de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada que no intersecta con este [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) para complementar esta [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

Actualiza este [Region](/psd/python-net/aspose.psd/region/) para que contenga la porción del [Region](/psd/python-net/aspose.psd/region/) especificado que no intersecta con este [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | El objeto [Region](/psd/python-net/aspose.psd/region/) para complementar este objeto [Region](/psd/python-net/aspose.psd/region/). |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Crea una copia profunda exacta de este [Region](/psd/python-net/aspose.psd/region/).

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Region](/psd/python-net/aspose.psd/region) | La [Region](/psd/python-net/aspose.psd/region/) que crea este método. |


### Method: exclude(path) {#exclude_path_6}


```
 exclude(path) 
```

Actualiza este [Region](/psd/python-net/aspose.psd/region/) para que contenga solo la porción de su interior que no intersecta con el [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | El [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) a excluir de esta [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_7}


```
 exclude(rect) 
```

Actualiza este [Region](/psd/python-net/aspose.psd/region/) para que contenga solo la porción de su interior que no intersecta con la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) a excluir de esta [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_8}


```
 exclude(rect) 
```

Actualiza este [Region](/psd/python-net/aspose.psd/region/) para que contenga solo la porción de su interior que no intersecta con la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) a excluir de esta [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(region) {#exclude_region_9}


```
 exclude(region) 
```

Actualiza este [Region](/psd/python-net/aspose.psd/region/) para que contenga solo la porción de su interior que no intersecta con el [Region](/psd/python-net/aspose.psd/region/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | La [Region](/psd/python-net/aspose.psd/region/) a excluir de esta [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(path) {#intersect_path_10}


```
 intersect(path) 
```

Actualiza este [Region](/psd/python-net/aspose.psd/region/) a la intersección de sí mismo con el [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | El [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) para intersectar con esta [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Actualiza este [Region](/psd/python-net/aspose.psd/region/) a la intersección de sí mismo con la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) para intersectar con esta [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_12}


```
 intersect(rect) 
```

Actualiza este [Region](/psd/python-net/aspose.psd/region/) a la intersección de sí mismo con la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) para intersectar con esta [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(region) {#intersect_region_13}


```
 intersect(region) 
```

Actualiza este [Region](/psd/python-net/aspose.psd/region/) a la intersección de sí mismo con el [Region](/psd/python-net/aspose.psd/region/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | La [Region](/psd/python-net/aspose.psd/region/) para intersectar con esta [Region](/psd/python-net/aspose.psd/region/). |

### Method: is_empty(g) {#is_empty_g_14}


```
 is_empty(g) 
```

Comprueba si este [Region](/psd/python-net/aspose.psd/region/) tiene un interior vacío en la superficie de dibujo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) que representa una superficie de dibujo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true si el interior de este [Region](/psd/python-net/aspose.psd/region/) está vacío cuando se aplica la transformación asociada con <paramref name="g" />; de lo contrario, false. |


### Method: is_infinite(g) {#is_infinite_g_15}


```
 is_infinite(g) 
```

Comprueba si este [Region](/psd/python-net/aspose.psd/region/) tiene un interior infinito en la superficie de dibujo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) que representa una superficie de dibujo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true si el interior de este [Region](/psd/python-net/aspose.psd/region/) es infinito cuando se aplica la transformación asociada con <paramref name="g" />; de lo contrario, false. |


### Method: is_visible(point) {#is_visible_point_16}


```
 is_visible(point) 
```

Comprueba si la estructura [PointF](/psd/python-net/aspose.psd/pointf/) especificada está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | La estructura [PointF](/psd/python-net/aspose.psd/pointf/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true cuando <paramref name="point" /> está contenido dentro de este [Region](/psd/python-net/aspose.psd/region/); de lo contrario, false. |


### Method: is_visible(point) {#is_visible_point_17}


```
 is_visible(point) 
```

Comprueba si la estructura [PointF](/psd/python-net/aspose.psd/pointf/) especificada está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | La estructura [PointF](/psd/python-net/aspose.psd/pointf/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true cuando <paramref name="point" /> está contenido dentro de este [Region](/psd/python-net/aspose.psd/region/); de lo contrario, false. |


### Method: is_visible(point, g) {#is_visible_point_g_18}


```
 is_visible(point, g) 
```

Comprueba si la estructura [PointF](/psd/python-net/aspose.psd/pointf/) especificada está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/) cuando se dibuja usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | La estructura [PointF](/psd/python-net/aspose.psd/pointf/) a probar. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true cuando <paramref name="point" /> está contenido dentro de este [Region](/psd/python-net/aspose.psd/region/); de lo contrario, false. |


### Method: is_visible(point, g) {#is_visible_point_g_19}


```
 is_visible(point, g) 
```

Comprueba si la estructura [PointF](/psd/python-net/aspose.psd/pointf/) especificada está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/) cuando se dibuja usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | La estructura [PointF](/psd/python-net/aspose.psd/pointf/) a probar. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true cuando <paramref name="point" /> está contenido dentro de este [Region](/psd/python-net/aspose.psd/region/); de lo contrario, false. |


### Method: is_visible(rect) {#is_visible_rect_20}


```
 is_visible(rect) 
```

Comprueba si alguna porción de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true cuando cualquier parte de <paramref name="rect" /> está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/); de lo contrario, false. |


### Method: is_visible(rect) {#is_visible_rect_21}


```
 is_visible(rect) 
```

Comprueba si alguna porción de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true cuando cualquier parte de <paramref name="rect" /> está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/); de lo contrario, false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_22}


```
 is_visible(rect, g) 
```

Comprueba si alguna porción de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/) cuando se dibuja usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) a probar. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true cuando <paramref name="rect" /> está contenido dentro de este [Region](/psd/python-net/aspose.psd/region/); de lo contrario, false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_23}


```
 is_visible(rect, g) 
```

Comprueba si alguna porción de la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/) cuando se dibuja usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) a probar. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true cuando <paramref name="rect" /> está contenido dentro de este [Region](/psd/python-net/aspose.psd/region/); de lo contrario, false. |


### Method: is_visible(x, y) {#is_visible_x_y_24}


```
 is_visible(x, y) 
```

Comprueba si el punto especificado está contenido dentro de este [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | True cuando el punto especificado está contenido dentro de este [Region](/psd/python-net/aspose.psd/region/); de lo contrario, false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_25}


```
 is_visible(x, y, g) 
```

Comprueba si el punto especificado está contenido dentro de este [Region](/psd/python-net/aspose.psd/region/) cuando se dibuja usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | True cuando el punto especificado está contenido dentro de este [Region](/psd/python-net/aspose.psd/region/); de lo contrario, false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_26}


```
 is_visible(x, y, g) 
```

Comprueba si el punto especificado está contenido dentro de este [Region](/psd/python-net/aspose.psd/region/) cuando se dibuja usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | True cuando el punto especificado está contenido dentro de este [Region](/psd/python-net/aspose.psd/region/); de lo contrario, false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_27}


```
 is_visible(x, y, width, height) 
```

Comprueba si alguna parte del rectángulo especificado está contenida dentro de esta [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| width | float | El ancho del rectángulo a probar. |
| altura | float | La altura del rectángulo a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true cuando cualquier parte del rectángulo especificado está contenida dentro de este objeto [Region](/psd/python-net/aspose.psd/region/); de lo contrario, false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_28}


```
 is_visible(x, y, width, height) 
```

Comprueba si alguna parte del rectángulo especificado está contenida dentro de esta [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| width | int | El ancho del rectángulo a probar. |
| altura | int | La altura del rectángulo a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true cuando cualquier parte del rectángulo especificado está contenida dentro de este objeto [Region](/psd/python-net/aspose.psd/region/); de lo contrario, false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_29}


```
 is_visible(x, y, width, height, g) 
```

Comprueba si alguna parte del rectángulo especificado está contenida dentro de esta [Region](/psd/python-net/aspose.psd/region/) cuando se dibuja usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| width | float | El ancho del rectángulo a probar. |
| altura | float | La altura del rectángulo a probar. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true cuando cualquier parte del rectángulo especificado está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/); de lo contrario, false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_30}


```
 is_visible(x, y, width, height, g) 
```

Comprueba si alguna parte del rectángulo especificado está contenida dentro de esta [Region](/psd/python-net/aspose.psd/region/) cuando se dibuja usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| width | int | El ancho del rectángulo a probar. |
| altura | int | La altura del rectángulo a probar. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true cuando cualquier parte del rectángulo especificado está contenida dentro de este [Region](/psd/python-net/aspose.psd/region/); de lo contrario, false. |


### Method: transform(matrix) {#transform_matrix_31}


```
 transform(matrix) 
```

Transforma esta [Region](/psd/python-net/aspose.psd/region/) mediante la [Matrix](/psd/python-net/aspose.psd/matrix/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La [Matrix](/psd/python-net/aspose.psd/matrix/) con la que transformar este [Region](/psd/python-net/aspose.psd/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_32}


```
 translate(dx, dy) 
```

Desplaza las coordenadas de esta [Region](/psd/python-net/aspose.psd/region/) en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | La cantidad para desplazar horizontalmente este [Region](/psd/python-net/aspose.psd/region/). |
| dy | float | La cantidad para desplazar verticalmente este [Region](/psd/python-net/aspose.psd/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_33}


```
 translate(dx, dy) 
```

Desplaza las coordenadas de esta [Region](/psd/python-net/aspose.psd/region/) en la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | int | La cantidad para desplazar horizontalmente este [Region](/psd/python-net/aspose.psd/region/). |
| dy | int | La cantidad para desplazar verticalmente este [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(path) {#union_path_34}


```
 union(path) 
```

Actualiza esta [Region](/psd/python-net/aspose.psd/region/) a la unión de ella misma y el [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | El [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) para unir con este [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(rect) {#union_rect_35}


```
 union(rect) 
```

Actualiza esta [Region](/psd/python-net/aspose.psd/region/) a la unión de ella misma y la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) para unir con este [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(rect) {#union_rect_36}


```
 union(rect) 
```

Actualiza esta [Region](/psd/python-net/aspose.psd/region/) a la unión de ella misma y la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) para unir con este [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(region) {#union_region_37}


```
 union(region) 
```

Actualiza esta [Region](/psd/python-net/aspose.psd/region/) a la unión de ella misma y la [Region](/psd/python-net/aspose.psd/region/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | El [Region](/psd/python-net/aspose.psd/region/) para unir con este [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(path) {#xor_path_38}


```
 xor(path) 
```

Actualiza esta [Region](/psd/python-net/aspose.psd/region/) a la unión menos la intersección de ella misma con el [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | El [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) para xor con este [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(rect) {#xor_rect_39}


```
 xor(rect) 
```

Actualiza esta [Region](/psd/python-net/aspose.psd/region/) a la unión menos la intersección de ella misma con la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) para xor con este [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(rect) {#xor_rect_40}


```
 xor(rect) 
```

Actualiza esta [Region](/psd/python-net/aspose.psd/region/) a la unión menos la intersección de ella misma con la estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) para xor con este [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(region) {#xor_region_41}


```
 xor(region) 
```

Actualiza esta [Region](/psd/python-net/aspose.psd/region/) a la unión menos la intersección de ella misma con la [Region](/psd/python-net/aspose.psd/region/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | El [Region](/psd/python-net/aspose.psd/region/) para xor con este [Region](/psd/python-net/aspose.psd/region/). |

