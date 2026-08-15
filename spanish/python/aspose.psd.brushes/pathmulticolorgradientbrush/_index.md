---
title: "Clase PathMulticolorGradientBrush"
type: docs
weight: 70
url: /es/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathMulticolorGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PathMulticolorGradientBrush(path)](#PathMulticolorGradientBrush_path_1) | Inicializa una nueva instancia de la clase [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con la ruta especificada. |
| [PathMulticolorGradientBrush(points)](#PathMulticolorGradientBrush_points_2) | Inicializa una nueva instancia de la clase [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con los puntos especificados. |
| [PathMulticolorGradientBrush(points)](#PathMulticolorGradientBrush_points_3) | Inicializa una nueva instancia de la clase [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con los puntos especificados. |
| [PathMulticolorGradientBrush(points, wrap_mode)](#PathMulticolorGradientBrush_points_wrap_mode_4) | Inicializa una nueva instancia de la clase [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con los puntos especificados y el modo de ajuste. |
| [PathMulticolorGradientBrush(points, wrap_mode)](#PathMulticolorGradientBrush_points_wrap_mode_5) | Inicializa una nueva instancia de la clase [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con los puntos especificados y el modo de ajuste. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Obtiene o establece el punto central del degradado de ruta. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está descartada. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Obtiene o establece el punto focal para la disminución del degradado. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | Obtiene la ruta gráfica sobre la que se construyó este pincel. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Obtiene o establece un [ColorBlend](/psd/python-net/aspose.psd/colorblend/) que define un degradado lineal multicolor. |
| is_transform_changed | bool | r | Obtiene un valor que indica si las transformaciones fueron modificadas de alguna manera. Por ejemplo, al establecer la matriz de transformación o<br/>            al llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introduce para compatibilidad retroactiva con GDI+. |
| opacity | float | r/w | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | Obtiene los puntos de la ruta sobre los que se construyó este pincel. |
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
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Traslada la transformación geométrica local en las dimensiones especificadas. Este método antepone la traslación a la transformación. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Traslada la transformación geométrica local en las dimensiones especificadas en el orden especificado. |


### Constructor: PathMulticolorGradientBrush(path) {#PathMulticolorGradientBrush_path_1}


```
 PathMulticolorGradientBrush(path) 
```

Inicializa una nueva instancia de la clase [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con la ruta especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | El [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) que define el área rellenada por este [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/). |

### Constructor: PathMulticolorGradientBrush(points) {#PathMulticolorGradientBrush_points_2}


```
 PathMulticolorGradientBrush(points) 
```

Inicializa una nueva instancia de la clase [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con los puntos especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que representa los puntos que forman los vértices de la ruta. |

### Constructor: PathMulticolorGradientBrush(points) {#PathMulticolorGradientBrush_points_3}


```
 PathMulticolorGradientBrush(points) 
```

Inicializa una nueva instancia de la clase [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con los puntos especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que representa los puntos que forman los vértices de la ruta. |

### Constructor: PathMulticolorGradientBrush(points, wrap_mode) {#PathMulticolorGradientBrush_points_wrap_mode_4}


```
 PathMulticolorGradientBrush(points, wrap_mode) 
```

Inicializa una nueva instancia de la clase [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con los puntos especificados y el modo de ajuste.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que representa los puntos que forman los vértices de la ruta. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Un [WrapMode](/psd/python-net/aspose.psd/wrapmode/) que especifica cómo se mosaican los rellenos dibujados con este [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/). |

### Constructor: PathMulticolorGradientBrush(points, wrap_mode) {#PathMulticolorGradientBrush_points_wrap_mode_5}


```
 PathMulticolorGradientBrush(points, wrap_mode) 
```

Inicializa una nueva instancia de la clase [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con los puntos especificados y el modo de ajuste.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que representa los puntos que forman los vértices de la ruta. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Un [WrapMode](/psd/python-net/aspose.psd/wrapmode/) que especifica cómo se mosaican los rellenos dibujados con este [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/). |

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

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Traslada la transformación geométrica local en las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traducción en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


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

