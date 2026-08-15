---
title: "Clase Pen"
type: docs
weight: 3360
url: /es/python-net/aspose.psd/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Pen

**Inheritance:** TransparencySupporter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Inicializa una nueva instancia de la clase [Pen](/psd/python-net/aspose.psd/pen/) con el [Pen.brush](/psd/python-net/aspose.psd/pen/) especificado. |
| [Pen(brush, width)](#Pen_brush_width_2) | Inicializa una nueva instancia de la clase [Pen](/psd/python-net/aspose.psd/pen/) con el [Pen.brush](/psd/python-net/aspose.psd/pen/) y el [Pen.width](/psd/python-net/aspose.psd/pen/) especificados. |
| [Pen(color)](#Pen_color_3) | Inicializa una nueva instancia de la clase [Pen](/psd/python-net/aspose.psd/pen/) con el color especificado. |
| [Pen(color, width)](#Pen_color_width_4) | Inicializa una nueva instancia de la clase [Pen](/psd/python-net/aspose.psd/pen/) con las propiedades [Pen.color](/psd/python-net/aspose.psd/pen/) y [Pen.width](/psd/python-net/aspose.psd/pen/) especificadas. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/psd/python-net/aspose.psd/penalignment) | r/w | Obtiene o establece la alineación para este [Pen](/psd/python-net/aspose.psd/pen/). |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | r/w | Obtiene o establece el [Pen.brush](/psd/python-net/aspose.psd/pen/) que determina los atributos de este [Pen](/psd/python-net/aspose.psd/pen/). |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtiene o establece el color de este [Pen](/psd/python-net/aspose.psd/pen/). |
| compound_array | float | r/w | Obtiene o establece una matriz de valores que especifica un Pen compuesto. Un Pen compuesto dibuja una línea compuesta formada por líneas paralelas y espacios. |
| custom_end_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Obtiene o establece una tapa personalizada para usar al final de las líneas dibujadas con este [Pen](/psd/python-net/aspose.psd/pen/). |
| custom_start_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Obtiene o establece una tapa personalizada para usar al comienzo de las líneas dibujadas con este [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | r/w | Obtiene o establece el estilo de tapa usado al final de los guiones que forman líneas discontinuas dibujadas con este [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_offset | float | r/w | Obtiene o establece la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones. |
| dash_pattern | float | r/w | Obtiene o establece una matriz de guiones y espacios personalizados. |
| dash_style | [DashStyle](/psd/python-net/aspose.psd/dashstyle) | r/w | Obtiene o establece el estilo usado para líneas discontinuas dibujadas con este [Pen](/psd/python-net/aspose.psd/pen/). |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Obtiene o establece el estilo de tapa usado al final de las líneas dibujadas con este [Pen](/psd/python-net/aspose.psd/pen/). |
| line_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Obtiene o establece el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este [Pen](/psd/python-net/aspose.psd/pen/). |
| miter_limit | float | r/w | Obtiene o establece el límite del grosor de la unión en una esquina biselada. |
| opacity | float | r/w | Obtiene o establece la opacidad del objeto. El valor debe estar entre 0 y 1. Un valor de 0 significa que el objeto es totalmente visible, un valor de 1 significa que el objeto es totalmente opaco. |
| pen_type | [PenType](/psd/python-net/aspose.psd/pentype) | r | Obtiene el estilo de las líneas dibujadas con este [Pen](/psd/python-net/aspose.psd/pen/). |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Obtiene o establece el estilo de tapa usado al comienzo de las líneas dibujadas con este [Pen](/psd/python-net/aspose.psd/pen/). |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Obtiene o establece una copia de la transformación geométrica para este [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | r/w | Obtiene o establece el ancho de este [Pen](/psd/python-net/aspose.psd/pen/), en unidades del objeto Graphics utilizado para dibujar. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [multiply_transform(matrix)](#multiply_transform_matrix_1) | Multiplica la matriz de transformación de este [Pen](/psd/python-net/aspose.psd/pen/) por la [Matrix](/psd/python-net/aspose.psd/matrix/) especificada. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_2) | Multiplica la matriz de transformación de este [Pen](/psd/python-net/aspose.psd/pen/) por la [Matrix](/psd/python-net/aspose.psd/matrix/) especificada en el orden indicado. |
| reset_transform() | Restablece la matriz de transformación geométrica de este [Pen](/psd/python-net/aspose.psd/pen/) a la identidad. |
| [rotate_transform(angle)](#rotate_transform_angle_3) | Rota la transformación geométrica local por el ángulo especificado. Este método antepone la rotación a la transformación. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_4) | Rota la transformación geométrica local por el ángulo especificado en el orden indicado. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_5) | Escala la transformación geométrica local por los factores especificados. Este método antepone la matriz de escala a la transformación. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_6) | Escala la transformación geométrica local por los factores especificados en el orden especificado. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_7) | Establece los valores que determinan el estilo de extremo usado para terminar líneas dibujadas por este [Pen](/psd/python-net/aspose.psd/pen/). |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Inicializa una nueva instancia de la clase [Pen](/psd/python-net/aspose.psd/pen/) con el [Pen.brush](/psd/python-net/aspose.psd/pen/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Un [Pen.brush](/psd/python-net/aspose.psd/pen/) que determina las propiedades de relleno de este [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Inicializa una nueva instancia de la clase [Pen](/psd/python-net/aspose.psd/pen/) con el [Pen.brush](/psd/python-net/aspose.psd/pen/) y el [Pen.width](/psd/python-net/aspose.psd/pen/) especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Un [Pen.brush](/psd/python-net/aspose.psd/pen/) que determina las características de este [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | El ancho del nuevo [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Inicializa una nueva instancia de la clase [Pen](/psd/python-net/aspose.psd/pen/) con el color especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Una estructura [Pen.color](/psd/python-net/aspose.psd/pen/) que indica el color de este [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Inicializa una nueva instancia de la clase [Pen](/psd/python-net/aspose.psd/pen/) con las propiedades [Pen.color](/psd/python-net/aspose.psd/pen/) y [Pen.width](/psd/python-net/aspose.psd/pen/) especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Una estructura [Pen.color](/psd/python-net/aspose.psd/pen/) que indica el color de este [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | Un valor que indica el ancho de este [Pen](/psd/python-net/aspose.psd/pen/). |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_1}


```
 multiply_transform(matrix) 
```

Multiplica la matriz de transformación de este [Pen](/psd/python-net/aspose.psd/pen/) por la [Matrix](/psd/python-net/aspose.psd/matrix/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | El objeto [Matrix](/psd/python-net/aspose.psd/matrix/) por el cual multiplicar la matriz de transformación. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_2}


```
 multiply_transform(matrix, order) 
```

Multiplica la matriz de transformación de este [Pen](/psd/python-net/aspose.psd/pen/) por la [Matrix](/psd/python-net/aspose.psd/matrix/) especificada en el orden indicado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | El [Matrix](/psd/python-net/aspose.psd/matrix/) por el cual multiplicar la matriz de transformación. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | El orden en el que realizar la operación de multiplicación. |

### Method: rotate_transform(angle) {#rotate_transform_angle_3}


```
 rotate_transform(angle) 
```

Rota la transformación geométrica local por el ángulo especificado. Este método antepone la rotación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ángulo | float | El ángulo de rotación. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_4}


```
 rotate_transform(angle, order) 
```

Rota la transformación geométrica local por el ángulo especificado en el orden indicado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ángulo | float | El ángulo de rotación. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) que especifica si se debe anexar o anteponer la matriz de rotación. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_5}


```
 scale_transform(sx, sy) 
```

Escala la transformación geométrica local por los factores especificados. Este método antepone la matriz de escala a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | El factor por el cual escalar la transformación en la dirección del eje x. |
| sy | float | El factor por el cual escalar la transformación en la dirección del eje y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_6}


```
 scale_transform(sx, sy, order) 
```

Escala la transformación geométrica local por los factores especificados en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | El factor por el cual escalar la transformación en la dirección del eje x. |
| sy | float | El factor por el cual escalar la transformación en la dirección del eje y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) que especifica si se debe anexar o anteponer la matriz de escala. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_7}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Establece los valores que determinan el estilo de extremo usado para terminar líneas dibujadas por este [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Un [LineCap](/psd/python-net/aspose.psd/linecap/) que representa el estilo de extremo a usar al inicio de líneas dibujadas con este [Pen](/psd/python-net/aspose.psd/pen/). |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Un [LineCap](/psd/python-net/aspose.psd/linecap/) que representa el estilo de extremo a usar al final de líneas dibujadas con este [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | Un [LineCap](/psd/python-net/aspose.psd/linecap/) que representa el estilo de extremo a usar al inicio o al final de líneas discontinuas dibujadas con este [Pen](/psd/python-net/aspose.psd/pen/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traducción en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traducción en y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | El orden (anteponer o anexar) en el que aplicar la traducción. |

