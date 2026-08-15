---
title: "Clase GraphicsPath"
type: docs
weight: 1570
url: /es/python-net/aspose.psd/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Inicializa una nueva instancia de la clase [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Inicializa una nueva instancia de la clase [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Inicializa una nueva instancia de la clase [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Inicializa una nueva instancia de la clase [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtiene o establece los límites del objeto. |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | r | Obtiene las figuras de la ruta. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | r/w | Obtiene o establece una enumeración [FillMode](/psd/python-net/aspose.psd/fillmode/) que determina cómo se rellenan los interiores de las formas en este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Agrega una figura nueva. |
| [add_figures(figures)](#add_figures_figures_2) | Agrega figuras nuevas. |
| [add_path(adding_path)](#add_path_adding_path_3) | Adjunta el [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) especificado a esta ruta. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Adjunta el [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) especificado a esta ruta. |
| [deep_clone()](#deep_clone__5) | Realiza una clonación profunda de esta ruta gráfica. |
| flatten() | Convierte cada curva en esta ruta en una secuencia de segmentos de línea conectados. |
| [flatten(matrix)](#flatten_matrix_6) | Aplica la transformación especificada y luego convierte cada curva en este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) en una secuencia de segmentos de línea conectados. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Convierte cada curva en este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) en una secuencia de segmentos de línea conectados. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Obtiene los límites del objeto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Obtiene los límites del objeto. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Indica si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con la [Pen](/psd/python-net/aspose.psd/pen/) especificada. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Indica si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con la [Pen](/psd/python-net/aspose.psd/pen/) especificada. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Indica si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con la [Pen](/psd/python-net/aspose.psd/pen/) especificada y usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Indica si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con la [Pen](/psd/python-net/aspose.psd/pen/) especificada y usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Indica si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con la [Pen](/psd/python-net/aspose.psd/pen/) especificada. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Indica si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con la [Pen](/psd/python-net/aspose.psd/pen/) especificada. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Indica si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con la [Pen](/psd/python-net/aspose.psd/pen/) especificada y usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Indica si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con la [Pen](/psd/python-net/aspose.psd/pen/) especificada y usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado. |
| [is_visible(point)](#is_visible_point_18) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(point)](#is_visible_point_19) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_20) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_21) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_22) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_23) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_24) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) en la región de recorte visible del [Graphics](/psd/python-net/aspose.psd/graphics/) especificado. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_25) | Indica si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) en la región de recorte visible del [Graphics](/psd/python-net/aspose.psd/graphics/) especificado. |
| [remove_figure(figure)](#remove_figure_figure_26) | Elimina una figura. |
| [remove_figures(figures)](#remove_figures_figures_27) | Elimina figuras. |
| reset() | Vacía la ruta gráfica y establece el [FillMode](/psd/python-net/aspose.psd/fillmode/) a [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| reverse() | Invierte el orden de figuras, formas y puntos en cada forma de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [transform(transform)](#transform_transform_28) | Aplica la transformación especificada a la forma. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_29) | Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_30) | Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_31) | Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_32) | Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen)](#widen_pen_33) | Agrega un contorno adicional a la ruta. |
| [widen(pen, matrix)](#widen_pen_matrix_34) | Agrega un contorno adicional al [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_35) | Sustituye este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) por curvas que encierran el área que se rellena cuando esta ruta se dibuja con el pen especificado. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Inicializa una nueva instancia de la clase [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Inicializa una nueva instancia de la clase [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Las figuras desde las que inicializar. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Inicializa una nueva instancia de la clase [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Las figuras desde las que inicializar. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | El modo de relleno. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Inicializa una nueva instancia de la clase [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | El modo de relleno. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Agrega una figura nueva.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | La figura a agregar. |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Agrega figuras nuevas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Las figuras a agregar. |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Adjunta el [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) especificado a esta ruta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | El [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) para agregar. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Adjunta el [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) especificado a esta ruta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | El [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) para agregar. |
| conectar | bool | Un valor booleano que indica si la primera figura en la ruta añadida forma parte de la última figura en esta ruta. Un valor true indica que la primera figura en la ruta añadida forma parte de la última figura en esta ruta. Un valor false indica que la primera figura en la ruta añadida está separada de la última figura en esta ruta. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Realiza una clonación profunda de esta ruta gráfica.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Una copia profunda de la ruta gráfica. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Aplica la transformación especificada y luego convierte cada curva en este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) en una secuencia de segmentos de línea conectados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Una [Matrix](/psd/python-net/aspose.psd/matrix/) mediante la cual transformar este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) antes de aplanar. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Convierte cada curva en este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) en una secuencia de segmentos de línea conectados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Una [Matrix](/psd/python-net/aspose.psd/matrix/) mediante la cual transformar este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) antes de aplanar. |
| planitud | float | Especifica el error máximo permitido entre la curva y su aproximación aplanada. Un valor de 0.25 es el predeterminado. Reducir el valor de planitud aumentará la cantidad de segmentos de línea en la aproximación. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


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


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Indica si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con la [Pen](/psd/python-net/aspose.psd/pen/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Un [PointF](/psd/python-net/aspose.psd/pointf/) que especifica la ubicación a probar. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | El [Pen](/psd/python-net/aspose.psd/pen/) para probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con el [Pen](/psd/python-net/aspose.psd/pen/) especificado; de lo contrario, false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Indica si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con la [Pen](/psd/python-net/aspose.psd/pen/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Un [PointF](/psd/python-net/aspose.psd/pointf/) que especifica la ubicación a probar. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | El [Pen](/psd/python-net/aspose.psd/pen/) para probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con el [Pen](/psd/python-net/aspose.psd/pen/) especificado; de lo contrario, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Indica si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con la [Pen](/psd/python-net/aspose.psd/pen/) especificada y usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Un [PointF](/psd/python-net/aspose.psd/pointf/) que especifica la ubicación a probar. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | El [Pen](/psd/python-net/aspose.psd/pen/) para probar. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | El [Graphics](/psd/python-net/aspose.psd/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) tal como se dibuja con el [Pen](/psd/python-net/aspose.psd/pen/) especificado; de lo contrario, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Indica si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con la [Pen](/psd/python-net/aspose.psd/pen/) especificada y usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Un [PointF](/psd/python-net/aspose.psd/pointf/) que especifica la ubicación a probar. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | El [Pen](/psd/python-net/aspose.psd/pen/) para probar. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | El [Graphics](/psd/python-net/aspose.psd/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) tal como se dibuja con el [Pen](/psd/python-net/aspose.psd/pen/) especificado; de lo contrario, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Indica si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con la [Pen](/psd/python-net/aspose.psd/pen/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | El [Pen](/psd/python-net/aspose.psd/pen/) para probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con el [Pen](/psd/python-net/aspose.psd/pen/) especificado; de lo contrario, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Indica si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con la [Pen](/psd/python-net/aspose.psd/pen/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | El [Pen](/psd/python-net/aspose.psd/pen/) para probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con el [Pen](/psd/python-net/aspose.psd/pen/) especificado; de lo contrario, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Indica si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con la [Pen](/psd/python-net/aspose.psd/pen/) especificada y usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | El [Pen](/psd/python-net/aspose.psd/pen/) para probar. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | El [Graphics](/psd/python-net/aspose.psd/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) tal como se dibuja con el [Pen](/psd/python-net/aspose.psd/pen/) especificado; de lo contrario, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Indica si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) cuando se dibuja con la [Pen](/psd/python-net/aspose.psd/pen/) especificada y usando el [Graphics](/psd/python-net/aspose.psd/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | El [Pen](/psd/python-net/aspose.psd/pen/) para probar. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | El [Graphics](/psd/python-net/aspose.psd/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro (bajo) del contorno de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) tal como se dibuja con el [Pen](/psd/python-net/aspose.psd/pen/) especificado; de lo contrario, false. |


### Method: is_visible(point) {#is_visible_point_18}


```
 is_visible(point) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Un [PointF](/psd/python-net/aspose.psd/pointf/) que representa el punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); de lo contrario, false. |


### Method: is_visible(point) {#is_visible_point_19}


```
 is_visible(point) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Un [PointF](/psd/python-net/aspose.psd/pointf/) que representa el punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); de lo contrario, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_20}


```
 is_visible(pt, graphics) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Un [PointF](/psd/python-net/aspose.psd/pointf/) que representa el punto a probar. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | El [Graphics](/psd/python-net/aspose.psd/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de esto; de lo contrario, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_21}


```
 is_visible(pt, graphics) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Un [PointF](/psd/python-net/aspose.psd/pointf/) que representa el punto a probar. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | El [Graphics](/psd/python-net/aspose.psd/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de esto; de lo contrario, false. |


### Method: is_visible(x, y) {#is_visible_x_y_22}


```
 is_visible(x, y) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); de lo contrario, false. |


### Method: is_visible(x, y) {#is_visible_x_y_23}


```
 is_visible(x, y) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); de lo contrario, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_24}


```
 is_visible(x, y, graphics) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) en la región de recorte visible del [Graphics](/psd/python-net/aspose.psd/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | El [Graphics](/psd/python-net/aspose.psd/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); de lo contrario, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_25}


```
 is_visible(x, y, graphics) 
```

Indica si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) en la región de recorte visible del [Graphics](/psd/python-net/aspose.psd/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | El [Graphics](/psd/python-net/aspose.psd/graphics/) para el cual probar la visibilidad. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Este método devuelve true si el punto especificado está contenido dentro de este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); de lo contrario, false. |


### Method: remove_figure(figure) {#remove_figure_figure_26}


```
 remove_figure(figure) 
```

Elimina una figura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | La figura a eliminar. |

### Method: remove_figures(figures) {#remove_figures_figures_27}


```
 remove_figures(figures) 
```

Elimina figuras.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Las figuras a eliminar. |

### Method: transform(transform) {#transform_transform_28}


```
 transform(transform) 
```

Aplica la transformación especificada a la forma.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | La transformación a aplicar. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_29}


```
 warp(dest_points, src_rect) 
```

Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen un paralelogramo al que se transforma el rectángulo definido por <paramref name="srcRect" />. La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los tres primeros puntos. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que representa el rectángulo que se transforma al paralelogramo definido por <paramref name="destPoints" />. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_30}


```
 warp(dest_points, src_rect, matrix) 
```

Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen un paralelogramo al que se transforma el rectángulo definido por <paramref name="srcRect" />. La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los tres primeros puntos. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que representa el rectángulo que se transforma al paralelogramo definido por <paramref name="destPoints" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Una [Matrix](/psd/python-net/aspose.psd/matrix/) que especifica una transformación geométrica para aplicar a la ruta. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_31}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que define un paralelogramo al que se transforma el rectángulo definido por <paramref name="srcRect" />. La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los tres primeros puntos. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que representa el rectángulo que se transforma al paralelogramo definido por <paramref name="destPoints" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Una [Matrix](/psd/python-net/aspose.psd/matrix/) que especifica una transformación geométrica para aplicar a la ruta. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Una enumeración [WarpMode](/psd/python-net/aspose.psd/warpmode/) que especifica si esta operación de deformación usa modo perspectiva o bilineal. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_32}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen un paralelogramo al que se transforma el rectángulo definido por <paramref name="srcRect" />. La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los tres primeros puntos. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que representa el rectángulo que se transforma al paralelogramo definido por <paramref name="destPoints" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Una [Matrix](/psd/python-net/aspose.psd/matrix/) que especifica una transformación geométrica para aplicar a la ruta. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Una enumeración [WarpMode](/psd/python-net/aspose.psd/warpmode/) que especifica si esta operación de deformación usa modo perspectiva o bilineal. |
| flatness | float | Un valor de 0 a 1 que especifica cuán plana es la ruta resultante. Para más información, consulte los métodos [GraphicsPath.flatten()](/psd/python-net/aspose.psd/graphicspath/). |

### Method: widen(pen) {#widen_pen_33}


```
 widen(pen) 
```

Agrega un contorno adicional a la ruta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) que especifica el ancho entre el contorno original de la ruta y el nuevo contorno que crea este método. |

### Method: widen(pen, matrix) {#widen_pen_matrix_34}


```
 widen(pen, matrix) 
```

Agrega un contorno adicional al [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) que especifica el ancho entre el contorno original de la ruta y el nuevo contorno que crea este método. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Una [Matrix](/psd/python-net/aspose.psd/matrix/) que especifica una transformación para aplicar a la ruta antes de ensanchar. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_35}


```
 widen(pen, matrix, flatness) 
```

Sustituye este [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) por curvas que encierran el área que se rellena cuando esta ruta se dibuja con el pen especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) que especifica el ancho entre el contorno original de la ruta y el nuevo contorno que crea este método. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Una [Matrix](/psd/python-net/aspose.psd/matrix/) que especifica una transformación para aplicar a la ruta antes de ensanchar. |
| planitud | float | Un valor que especifica la planitud para curvas. |

