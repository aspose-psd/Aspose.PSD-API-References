---
title: "Clase Matrix"
type: docs
weight: 3000
url: /es/python-net/aspose.psd/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Matrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Matrix()](#Matrix__1) | Inicializa una nueva instancia de la clase Matrix como la matriz identidad. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | Inicializa una nueva instancia de la clase [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [Matrix(origin)](#Matrix_origin_3) | Crea una copia de la clase [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | Inicializa una nueva instancia de la clase [Matrix](/psd/python-net/aspose.psd/matrix/) al transformado geométrico definido por el rectángulo especificado y la matriz de puntos. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | Inicializa una nueva instancia de la clase [Matrix](/psd/python-net/aspose.psd/matrix/) al transformado geométrico definido por el rectángulo especificado y la matriz de puntos. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | This flag bit indicates that the transform defined by this object<br/>            performs a mirror image flip about some axis which changes the<br/>            normally right handed coordinate system into a left handed<br/>            system in addition to the conversions indicated by other flag bits.<br/>            A right handed coordinate system is one where the positive X<br/>            axis rotates counterclockwise to overlay the positive Y axis<br/>            similar to the direction that the fingers on your right hand<br/>            curl when you stare end on at your thumb.<br/>            A left handed coordinate system is one where the positive X<br/>            axis rotates clockwise to overlay the positive Y axis similar<br/>            to the direction that the fingers on your left hand curl.<br/>            There is no mathematical way to determine the angle of the<br/>            original flipping or mirroring transformation since all angles<br/>            of flip are identical given an appropriate adjusting rotation.<br/>            NOTE: TypeFlip was added after GENERAL_TRANSFORM was in public<br/>            circulation and the flag bits could no longer be conveniently<br/>            renumbered without introducing binary incompatibility in outside<br/>            code. |
| TYPE_GENERAL_ROTATION [static] | int | r | This flag bit indicates that the transform defined by this object<br/>            performs a rotation by an arbitrary angle in addition to the<br/>            conversions indicated by other flag bits.<br/>            A rotation changes the angles of vectors by the same amount<br/>            regardless of the original direction of the vector and without<br/>            changing the length of the vector.<br/>            This flag bit is mutually exclusive with the |
| TYPE_GENERAL_SCALE [static] | int | r | A general scale multiplies the length of vectors by different<br/>            amounts in the x and y directions without changing the angle<br/>            between perpendicular vectors.<br/>            This flag bit is mutually exclusive with the TypeUniformScale flag. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | This constant indicates that the transform defined by this object<br/>            performs an arbitrary conversion of the input coordinates.<br/>            If this transform can be classified by any of the above constants,<br/>            the type will either be the constant TypeIdentity or a<br/>            combination of the appropriate flag bits for the various coordinate<br/>            conversions that this transform performs. |
| TYPE_IDENTITY [static] | int | r | An identity transform is one in which the output coordinates are<br/>            always the same as the input coordinates.<br/>            If this transform is anything other than the identity transform,<br/>            the type will either be the constant GENERAL_TRANSFORM or a<br/>            combination of the appropriate flag bits for the various coordinate<br/>            conversions that this transform performs. |
| TYPE_MASK_ROTATION [static] | int | r | This constant is a bit mask for any of the rotation flag bits. |
| TYPE_MASK_SCALE [static] | int | r | This constant is a bit mask for any of the scale flag bits. |
| TYPE_QUADRANT_ROTATION [static] | int | r | This flag bit indicates that the transform defined by this object<br/>            performs a quadrant rotation by some multiple of 90 degrees in<br/>            addition to the conversions indicated by other flag bits.<br/>            A rotation changes the angles of vectors by the same amount<br/>            regardless of the original direction of the vector and without<br/>            changing the length of the vector.<br/>            This flag bit is mutually exclusive with the TypeGeneralRotation flag. |
| TYPE_TRANSLATION [static] | int | r | A translation moves the coordinates by a constant amount in x<br/>            and y without changing the length or angle of vectors. |
| TYPE_UNIFORM_SCALE [static] | int | r | Una escala uniforme multiplica la longitud de los vectores por la misma cantidad<br/>            en ambas direcciones x e y sin cambiar el ángulo entre<br/>            vectores.<br/>            Este bit de bandera es mutuamente excluyente con la bandera TypeGeneralScale. |
| elements | float | r | Obtiene una matriz de valores de punto flotante que representa los elementos de este [Matrix](/psd/python-net/aspose.psd/matrix/). |
| m11 | float | r | Obtiene el elemento de la matriz en la primera fila, primera columna. Representa la escala a lo largo del eje X. |
| m12 | float | r | Obtiene el elemento de la matriz en la primera fila, segunda columna. Representa el sesgo a lo largo del eje Y. |
| m21 | float | r | Obtiene el elemento de la matriz en la segunda fila, primera columna. Representa el sesgo a lo largo del eje X. |
| m22 | float | r | Obtiene el elemento de la matriz en la segunda fila, segunda columna. Representa la escala a lo largo del eje Y. |
| m31 | float | r | Obtiene el elemento de la matriz en la tercera fila, primera columna. Representa la traslación a lo largo del eje X. |
| m32 | float | r | Obtiene el elemento de la matriz en la tercera fila, primera columna. Representa la traslación a lo largo del eje Y. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_elements()](#get_elements__1) | Obtiene una copia de los elementos de la matriz. |
| [multiply(tx)](#multiply_tx_2) | Multiplica esta Matrix por la matriz especificada en el parámetro matrix usando el orden (predeterminado) Prepend. |
| [multiply(tx, order)](#multiply_tx_order_3) | Multiplica esta Matrix por la matriz especificada en el parámetro matrix, y en el orden especificado en el parámetro order. |
| reset() | Restablece esta Matrix para que tenga los elementos de la matriz identidad. |
| [rotate(angle)](#rotate_angle_4) | Aplica una rotación en sentido horario de una cantidad especificada en el parámetro ángulo, alrededor del origen (coordenadas x e y cero) para esta Matrix en el orden predeterminado (Prepend). |
| [rotate(angle, order)](#rotate_angle_order_5) | Aplica una rotación en sentido horario de una cantidad especificada en el parámetro ángulo, alrededor del origen (coordenadas x e y cero) para esta Matrix en el orden especificado. |
| [rotate_at(angle, point)](#rotate_at_angle_point_6) | Aplica una rotación en sentido horario alrededor del punto especificado a esta Matrix en el orden predeterminado (Prepend). |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_7) | Aplica una rotación en sentido horario alrededor del punto especificado a esta Matrix en el orden especificado. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_8) | Aplica el vector de escala especificado (scaleX y scaleY) a este [Matrix](/psd/python-net/aspose.psd/matrix/) usando el orden especificado. |
| [scale(sx, sy)](#scale_sx_sy_9) | Aplica el vector de escala especificado (scaleX y scaleY) a esta Matrix usando el orden (predeterminado) Prepend. |
| [transform_points(points)](#transform_points_points_10) | Aplica la transformación geométrica representada por este [Matrix](/psd/python-net/aspose.psd/matrix/) a una matriz especificada de puntos. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_11) | Aplica el vector de traslación especificado a esta Matriz en el orden especificado. |
| [translate(tx, ty)](#translate_tx_ty_12) | Aplica el vector de traslación especificado a esta [Matrix](/psd/python-net/aspose.psd/matrix/) usando el orden Prepend (predeterminado). |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Inicializa una nueva instancia de la clase Matrix como la matriz identidad.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

Inicializa una nueva instancia de la clase [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| m11 | float | m00     M11     Escala X |
| m12 | float | m10     M12     Cizalla Y |
| m21 | float | m01     M21     Cizalla X |
| m22 | float | m11     M22     Escala Y |
| m31 | float | m02     M31     Trasladar X |
| m32 | float | m12     M32     Trasladar Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

Crea una copia de la clase [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| origin | [Matrix](/psd/python-net/aspose.psd/matrix) | Una matriz base para copiar |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

Inicializa una nueva instancia de la clase [Matrix](/psd/python-net/aspose.psd/matrix/) al transformado geométrico definido por el rectángulo especificado y la matriz de puntos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que representa el rectángulo a transformar. |
| plgpts | [PointF[]](/psd/python-net/aspose.psd/pointf) | Una matriz de tres estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que representa los puntos de un paralelogramo al que se transformarán las esquinas superior izquierda, superior derecha e inferior izquierda del rectángulo. La esquina inferior derecha del paralelogramo se deduce de las tres primeras esquinas. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

Inicializa una nueva instancia de la clase [Matrix](/psd/python-net/aspose.psd/matrix/) al transformado geométrico definido por el rectángulo especificado y la matriz de puntos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que representa el rectángulo a transformar. |
| plgpts | [Point[]](/psd/python-net/aspose.psd/point) | Una matriz de tres estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que representa los puntos de un paralelogramo al que se transformarán las esquinas superior izquierda, superior derecha e inferior izquierda del rectángulo. La esquina inferior derecha del paralelogramo se deduce de las tres primeras esquinas. |

### Method: get_elements() {#get_elements__1}


```
 get_elements() 
```

Obtiene una copia de los elementos de la matriz.

**Returns**

| Tipo | Descripción |
| :- | :- |
| float | Una copia de los elementos de la matriz. |


### Method: multiply(tx) {#multiply_tx_2}


```
 multiply(tx) 
```

Multiplica esta Matrix por la matriz especificada en el parámetro matrix usando el orden (predeterminado) Prepend.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | La matriz con la que multiplicar. |

### Method: multiply(tx, order) {#multiply_tx_order_3}


```
 multiply(tx, order) 
```

Multiplica esta Matrix por la matriz especificada en el parámetro matrix, y en el orden especificado en el parámetro order.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | El tx. El tx. El tx. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | El orden. El orden. El orden. |

### Method: rotate(angle) {#rotate_angle_4}


```
 rotate(angle) 
```

Aplica una rotación en sentido horario de una cantidad especificada en el parámetro ángulo, alrededor del origen (coordenadas x e y cero) para esta Matrix en el orden predeterminado (Prepend).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ángulo | float | El ángulo de rotación. |

### Method: rotate(angle, order) {#rotate_angle_order_5}


```
 rotate(angle, order) 
```

Aplica una rotación en sentido horario de una cantidad especificada en el parámetro ángulo, alrededor del origen (coordenadas x e y cero) para esta Matrix en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ángulo | float | El ángulo de rotación. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | El orden de la matriz. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_6}


```
 rotate_at(angle, point) 
```

Aplica una rotación en sentido horario alrededor del punto especificado a esta Matrix en el orden predeterminado (Prepend).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ángulo | float | El ángulo. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | El punto. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_7}


```
 rotate_at(angle, point, order) 
```

Aplica una rotación en sentido horario alrededor del punto especificado a esta Matrix en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ángulo | float | El ángulo. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | El punto. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | El orden. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_8}


```
 scale(scale_x, scale_y, order) 
```

Aplica el vector de escala especificado (scaleX y scaleY) a este [Matrix](/psd/python-net/aspose.psd/matrix/) usando el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scale_x | float | La escala X. |
| scale_y | float | La escala Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | El orden. |

### Method: scale(sx, sy) {#scale_sx_sy_9}


```
 scale(sx, sy) 
```

Aplica el vector de escala especificado (scaleX y scaleY) a esta Matrix usando el orden (predeterminado) Prepend.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | El sx. El sx. El sx. |
| sy | float | El sy. El sy. El sy. |

### Method: transform_points(points) {#transform_points_points_10}


```
 transform_points(points) 
```

Aplica la transformación geométrica representada por este [Matrix](/psd/python-net/aspose.psd/matrix/) a una matriz especificada de puntos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Los puntos. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_11}


```
 translate(offset_x, offset_y, order) 
```

Aplica el vector de traslación especificado a esta Matriz en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| offset_x | float | El desplazamiento X. |
| offset_y | float | El desplazamiento Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | El orden. |

### Method: translate(tx, ty) {#translate_tx_ty_12}


```
 translate(tx, ty) 
```

Aplica el vector de traslación especificado a esta [Matrix](/psd/python-net/aspose.psd/matrix/) usando el orden Prepend (predeterminado).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tx | float | El tx. El tx. El tx. |
| ty | float | El ty. El ty. El ty. |

