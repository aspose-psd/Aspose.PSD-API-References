---
title: "LinearGradientBrush Clase"
type: docs
weight: 20
url: /es/python-net/aspose.psd.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) con parámetros predeterminados.<br/>            El color inicial es negro, el color final es blanco, el ángulo es de 45 grados y el rectángulo está ubicado en (0,0) con tamaño (1,1). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) con los puntos y colores especificados. |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) con los puntos y colores especificados. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basada en un rectángulo, colores inicial y final, y un ángulo de orientación. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basada en un rectángulo, colores inicial y final, y un ángulo de orientación. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basada en un rectángulo, colores inicial y final, y un ángulo de orientación. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | Inicializa una nueva instancia de la clase [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basada en un rectángulo, colores inicial y final, y un ángulo de orientación. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| ángulo | float | r/w | Obtiene o establece el ángulo del degradado. |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Obtiene o establece un [Blend](/psd/python-net/aspose.psd/blend/) que especifica posiciones y factores que definen una caída personalizada para el degradado. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está descartada. |
| end_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtiene o establece el color final del degradado. |
| gamma_correction | bool | r/w | Obtiene o establece un valor que indica si la corrección gamma está habilitada para este [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Obtiene o establece un [ColorBlend](/psd/python-net/aspose.psd/colorblend/) que define un degradado lineal multicolor. |
| is_angle_scalable | bool | r/w | Obtiene o establece un valor que indica si [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) se cambia durante las transformaciones con este [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | Obtiene un valor que indica si las transformaciones fueron modificadas de alguna manera. Por ejemplo, al establecer la matriz de transformación o<br/>            al llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introduce para compatibilidad retroactiva con GDI+. |
| linear_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Obtiene o establece los colores inicial y final del degradado. |
| opacity | float | r/w | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | Obtiene o establece una región rectangular que define los puntos de inicio y fin del degradado. |
| start_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtiene o establece el color inicial del degradado. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Obtiene o establece una copia de [Matrix](/psd/python-net/aspose.psd/matrix/) que define una transformación geométrica local para este [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Obtiene o establece una enumeración [WrapMode](/psd/python-net/aspose.psd/wrapmode/) que indica el modo de ajuste para este [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Crea una nueva clonación profunda del [Brush](/psd/python-net/aspose.psd/brush/) actual. |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Multiplica la [Matrix](/psd/python-net/aspose.psd/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) por la [Matrix](/psd/python-net/aspose.psd/matrix/) especificada, anteponiendo la [Matrix](/psd/python-net/aspose.psd/matrix/) indicada. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Multiplica la [Matrix](/psd/python-net/aspose.psd/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) por la [Matrix](/psd/python-net/aspose.psd/matrix/) especificada en el orden indicado. |
| reset_transform() | Restablece la propiedad [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) a la identidad. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Rota la transformación geométrica local en la cantidad especificada en el orden especificado. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Escala la transformación geométrica local en las cantidades especificadas. Este método antepone la matriz de escala a la transformación. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Escala la transformación geométrica local en las cantidades especificadas en el orden especificado. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Crea una caída de degradado basada en una curva en forma de campana. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Crea una caída de degradado basada en una curva en forma de campana. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Traslada la transformación geométrica local en las dimensiones especificadas. Este método antepone la traslación a la transformación. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Traslada la transformación geométrica local en las dimensiones especificadas en el orden especificado. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) con parámetros predeterminados.<br/>            El color inicial es negro, el color final es blanco, el ángulo es de 45 grados y el rectángulo está ubicado en (0,0) con tamaño (1,1).

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) con los puntos y colores especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Una estructura [Point](/psd/python-net/aspose.psd/point/) que representa el punto inicial del degradado lineal. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Una estructura [Point](/psd/python-net/aspose.psd/point/) que representa el punto final del degradado lineal. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Una estructura [Color](/psd/python-net/aspose.psd/color/) que representa el color inicial del degradado lineal. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Una estructura [Color](/psd/python-net/aspose.psd/color/) que representa el color final del degradado lineal. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) con los puntos y colores especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Una estructura [Point](/psd/python-net/aspose.psd/point/) que representa el punto inicial del degradado lineal. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Una estructura [Point](/psd/python-net/aspose.psd/point/) que representa el punto final del degradado lineal. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Una estructura [Color](/psd/python-net/aspose.psd/color/) que representa el color inicial del degradado lineal. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Una estructura [Color](/psd/python-net/aspose.psd/color/) que representa el color final del degradado lineal. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basada en un rectángulo, colores inicial y final, y un ángulo de orientación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que especifica los límites del degradado lineal. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Una estructura [Color](/psd/python-net/aspose.psd/color/) que representa el color inicial para el degradado. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Una estructura [Color](/psd/python-net/aspose.psd/color/) que representa el color final del degradado. |
| ángulo | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basada en un rectángulo, colores inicial y final, y un ángulo de orientación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que especifica los límites del degradado lineal. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Una estructura [Color](/psd/python-net/aspose.psd/color/) que representa el color inicial para el degradado. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Una estructura [Color](/psd/python-net/aspose.psd/color/) que representa el color final del degradado. |
| ángulo | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basada en un rectángulo, colores inicial y final, y un ángulo de orientación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que especifica los límites del degradado lineal. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Una estructura [Color](/psd/python-net/aspose.psd/color/) que representa el color inicial para el degradado. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Una estructura [Color](/psd/python-net/aspose.psd/color/) que representa el color final del degradado. |
| ángulo | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |
| is_angle_scalable | bool | si se establece en <c>true</c> el ángulo se cambia durante las transformaciones con este [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/). |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Inicializa una nueva instancia de la clase [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basada en un rectángulo, colores inicial y final, y un ángulo de orientación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que especifica los límites del degradado lineal. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Una estructura [Color](/psd/python-net/aspose.psd/color/) que representa el color inicial para el degradado. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Una estructura [Color](/psd/python-net/aspose.psd/color/) que representa el color final del degradado. |
| ángulo | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |
| is_angle_scalable | bool | si se establece en <c>true</c> el ángulo se cambia durante las transformaciones con este [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Crea una nueva clonación profunda del [Brush](/psd/python-net/aspose.psd/brush/) actual.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | Un nuevo [Brush](/psd/python-net/aspose.psd/brush/) que es la clonación profunda de esta instancia de [Brush](/psd/python-net/aspose.psd/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Multiplica la [Matrix](/psd/python-net/aspose.psd/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) por la [Matrix](/psd/python-net/aspose.psd/matrix/) especificada, anteponiendo la [Matrix](/psd/python-net/aspose.psd/matrix/) indicada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La [Matrix](/psd/python-net/aspose.psd/matrix/) por la cual multiplicar la transformación geométrica. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Multiplica la [Matrix](/psd/python-net/aspose.psd/matrix/) que representa la transformación geométrica local de este [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) por la [Matrix](/psd/python-net/aspose.psd/matrix/) especificada en el orden indicado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La [Matrix](/psd/python-net/aspose.psd/matrix/) por la cual multiplicar la transformación geométrica. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) que especifica en qué orden multiplicar las dos matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ángulo | float | El ángulo de rotación. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Rota la transformación geométrica local en la cantidad especificada en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ángulo | float | El ángulo de rotación. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) que especifica si se debe anexar o anteponer la matriz de rotación. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Escala la transformación geométrica local en las cantidades especificadas. Este método antepone la matriz de escala a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | La cantidad por la cual escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección del eje y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Escala la transformación geométrica local en las cantidades especificadas en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | La cantidad por la cual escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección del eje y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) que especifica si se debe anexar o anteponer la matriz de escala. |

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_8}


```
 set_blend_triangular_shape(focus) 
```

Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| enfoque | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el degradado está compuesto solo por el color final). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| enfoque | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el degradado está compuesto solo por el color final). |
| scale | float | Un valor de 0 a 1 que especifica qué tan rápido disminuyen los colores desde el color inicial hasta <paramref name="focus" /> (color final) |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Crea una caída de degradado basada en una curva en forma de campana.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| enfoque | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el color inicial y el color final se mezclan por igual). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Crea una caída de degradado basada en una curva en forma de campana.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| enfoque | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el degradado está compuesto solo por el color final). |
| scale | float | Un valor de 0 a 1 que especifica qué tan rápido disminuyen los colores desde el <paramref name="focus" />. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Traslada la transformación geométrica local en las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traducción en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

Traslada la transformación geométrica local en las dimensiones especificadas en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traducción en y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | El orden (anteponer o anexar) en el que aplicar la traducción. |

