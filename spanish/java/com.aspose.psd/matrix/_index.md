---
title: "Matrix"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Reemplaza la GDI Matrix."
type: docs
weight: 69
url: /es/java/com.aspose.psd/matrix/
---

**Inheritance:**
java.lang.Object
```
public class Matrix
```

Reemplaza la matriz GDI+.

La mayoría de los algoritmos provienen de AffineTransform.java de Sun. Nombres de Java para los elementos de la matriz usados internamente. Mapa de nombres de Java a los de .net con descripción: m00 M11 Escala X m10 M12 Cizallado Y m01 M21 Cizallado X m11 M22 Escala Y m02 M31 Traslación X m12 M32 Traslación Y
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Matrix()](#Matrix--) | Inicializa una nueva instancia de la clase Matrix como la matriz identidad. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Inicializa una nueva instancia de la clase Matrix. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.psd.Matrix-) | Crea una copia de la clase Matrix. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---) | Inicializa una nueva instancia de la clase Aspose.Imaging.Matrix al transformado geométrico definido por el rectángulo especificado y la matriz de puntos. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---) | Inicializa una nueva instancia de la clase Aspose.Imaging.Matrix al transformado geométrico definido por el rectángulo especificado y la matriz de puntos. |
## Campos

| Campo | Descripción |
| --- | --- |
| [TYPE_FLIP](#TYPE-FLIP) | Este bit de bandera indica que la transformación definida por este objeto realiza una inversión de imagen espejo alrededor de algún eje, lo que cambia el sistema de coordenadas normalmente de mano derecha a uno de mano izquierda, además de las conversiones indicadas por otros bits de bandera. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Este bit de bandera indica que la transformación definida por este objeto realiza una rotación por un ángulo arbitrario, además de las conversiones indicadas por otros bits de bandera. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | Una escala general multiplica la longitud de los vectores por diferentes cantidades en las direcciones x e y sin cambiar el ángulo entre vectores perpendiculares. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Esta constante indica que la transformación definida por este objeto realiza una conversión arbitraria de las coordenadas de entrada. |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | Una transformación de identidad es aquella en la que las coordenadas de salida son siempre las mismas que las coordenadas de entrada. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Esta constante es una máscara de bits para cualquiera de los bits de bandera de rotación. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Esta constante es una máscara de bits para cualquiera de los bits de bandera de escala. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Este bit de bandera indica que la transformación definida por este objeto realiza una rotación de cuadrante por un múltiplo de 90 grados además de las conversiones indicadas por otros bits de bandera. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | Una traslación mueve las coordenadas una cantidad constante en x e y sin cambiar la longitud o el ángulo de los vectores. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | Una escala uniforme multiplica la longitud de los vectores por la misma cantidad en ambas direcciones x e y sin cambiar el ángulo entre los vectores. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el System.Object especificado es igual a esta instancia. |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) | Obtiene una copia de los elementos de la matriz. |
| [getM11()](#getM11--) | Obtiene el elemento de la matriz en la primera fila, primera columna. |
| [getM12()](#getM12--) | Obtiene el elemento de la matriz en la primera fila, segunda columna. |
| [getM21()](#getM21--) | Obtiene el elemento de la matriz en la segunda fila, primera columna. |
| [getM22()](#getM22--) | Obtiene el elemento de la matriz en la segunda fila, segunda columna. |
| [getM31()](#getM31--) | Obtiene el elemento de la matriz en la tercera fila, primera columna. |
| [getM32()](#getM32--) | Obtiene el elemento de la matriz en la tercera fila, primera columna. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-) | Determina si dos matrices son iguales. |
| [isIdentity()](#isIdentity--) | Devuelve `true` si este `AffineTransform` es una transformación de identidad. |
| [multiply(Matrix Tx)](#multiply-com.aspose.psd.Matrix-) | Multiplica esta Matrix por la matriz especificada en el parámetro matrix usando el orden (predeterminado) Prepend. |
| [multiply(Matrix Tx, int order)](#multiply-com.aspose.psd.Matrix-int-) | Multiplica esta Matrix por la matriz especificada en el parámetro matrix, y en el orden especificado en el parámetro order. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Restablece esta Matrix para que tenga los elementos de la matriz de identidad. |
| [rotate(float angle)](#rotate-float-) | Aplica una rotación en sentido horario de una cantidad especificada en el parámetro ángulo, alrededor del origen (coordenadas x e y cero) para esta Matrix en el orden predeterminado (Prepend). |
| [rotate(float angle, int order)](#rotate-float-int-) | Aplica una rotación en sentido horario de una cantidad especificada en el parámetro ángulo, alrededor del origen (coordenadas x e y cero) para esta Matrix en el orden especificado. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.psd.PointF-) | Aplica una rotación en sentido horario alrededor del punto especificado a esta Matrix en el orden predeterminado (Prepend). |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.psd.PointF-int-) | Aplica una rotación en sentido horario alrededor del punto especificado a esta Matrix en el orden especificado. |
| [scale(float sx, float sy)](#scale-float-float-) | Aplica el vector de escala especificado (scaleX y scaleY) a esta Matrix usando el orden (predeterminado) Prepend. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Aplica el vector de escala especificado (scaleX y scaleY) a esta  Matrix  usando el orden especificado. |
| [toString()](#toString--) | Devuelve un  System.String  que representa esta instancia. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.psd.PointF---) | Aplica la transformación geométrica representada por esta  Matrix  a una matriz especificada de puntos. |
| [translate(float tx, float ty)](#translate-float-float-) | Aplica el vector de traslación especificado a esta Matrix usando el orden Prepend (predeterminado). |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Aplica el vector de traslación especificado a esta Matrix en el orden especificado. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


Inicializa una nueva instancia de la clase Matrix como la matriz identidad.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Inicializa una nueva instancia de la clase Matrix.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| m11 | float | m00 M11 Scale X |
| m12 | float | m10 M12 Shear Y |
| m21 | float | m01 M21 Shear X |
| m22 | float | m11 M22 Scale Y |
| m31 | float | m02 M31 Translate X |
| m32 | float | m12 M32 Translate Y |

### Matrix(Matrix origin) {#Matrix-com.aspose.psd.Matrix-}
```
public Matrix(Matrix origin)
```


Crea una copia de la clase Matrix.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.psd/matrix) | la matriz base para la copia |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Inicializa una nueva instancia de la clase Aspose.Imaging.Matrix al transformado geométrico definido por el rectángulo especificado y la matriz de puntos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Una estructura Aspose.Imaging.RectangleF que representa el rectángulo a transformar. |
| plgpts | [PointF\[\]](../../com.aspose.psd/pointf) | Una matriz de tres estructuras Aspose.Imaging.PointF que representa los puntos de un paralelogramo al que se transformarán las esquinas superior izquierda, superior derecha e inferior izquierda del rectángulo. La esquina inferior derecha del paralelogramo se deduce de las tres primeras esquinas. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Inicializa una nueva instancia de la clase Aspose.Imaging.Matrix al transformado geométrico definido por el rectángulo especificado y la matriz de puntos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Una estructura Aspose.Imaging.Rectangle que representa el rectángulo a transformar. |
| plgpts | [Point\[\]](../../com.aspose.psd/point) | Una matriz de tres estructuras Aspose.Imaging.Point que representa los puntos de un paralelogramo al que se transformarán las esquinas superior izquierda, superior derecha e inferior izquierda del rectángulo. La esquina inferior derecha del paralelogramo se deduce de las tres primeras esquinas. |

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Este bit de bandera indica que la transformación definida por este objeto realiza una inversión de imagen espejo alrededor de algún eje, lo que cambia el sistema de coordenadas normalmente derecho a uno izquierdo, además de las conversiones indicadas por otros bits de bandera. Un sistema de coordenadas derecho es aquel donde el eje X positivo gira en sentido antihorario para superponerse al eje Y positivo, similar a la dirección en que los dedos de la mano derecha se curvan cuando miras de frente tu pulgar. Un sistema de coordenadas izquierdo es aquel donde el eje X positivo gira en sentido horario para superponerse al eje Y positivo, similar a la dirección en que los dedos de la mano izquierda se curvan. No existe una forma matemática de determinar el ángulo de la transformación original de volteo o espejo, ya que todos los ángulos de volteo son idénticos dado una rotación de ajuste apropiada. NOTA: TypeFlip se añadió después de que GENERAL\_TRANSFORM estuviera en circulación pública y los bits de bandera ya no pudieron renumerarse convenientemente sin introducir incompatibilidad binaria en código externo.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Este bit de bandera indica que la transformación definida por este objeto realiza una rotación por un ángulo arbitrario además de las conversiones indicadas por otros bits de bandera. Una rotación cambia los ángulos de los vectores en la misma cantidad sin importar la dirección original del vector y sin cambiar la longitud del vector. Este bit de bandera es mutuamente excluyente con el

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


Una escala general multiplica la longitud de los vectores por diferentes cantidades en las direcciones x e y sin cambiar el ángulo entre vectores perpendiculares. Este bit de bandera es mutuamente excluyente con la bandera TypeUniformScale.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Esta constante indica que la transformación definida por este objeto realiza una conversión arbitraria de las coordenadas de entrada. Si esta transformación puede clasificarse mediante cualquiera de las constantes anteriores, el tipo será la constante TypeIdentity o una combinación de los bits de bandera apropiados para las diversas conversiones de coordenadas que realiza esta transformación.

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


Una transformación de identidad es aquella en la que las coordenadas de salida son siempre las mismas que las coordenadas de entrada. Si esta transformación es distinta de la transformación de identidad, el tipo será la constante GENERAL\_TRANSFORM o una combinación de los bits de bandera apropiados para las diversas conversiones de coordenadas que realiza esta transformación.

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Esta constante es una máscara de bits para cualquiera de los bits de bandera de rotación.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Esta constante es una máscara de bits para cualquiera de los bits de bandera de escala.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Este bit de bandera indica que la transformación definida por este objeto realiza una rotación de cuadrante en múltiplos de 90 grados además de las conversiones indicadas por otros bits de bandera. Una rotación cambia los ángulos de los vectores en la misma cantidad sin importar la dirección original del vector y sin cambiar la longitud del vector. Este bit de bandera es mutuamente excluyente con la bandera TypeGeneralRotation.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


Una traslación mueve las coordenadas una cantidad constante en x e y sin cambiar la longitud o el ángulo de los vectores.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


Una escala uniforme multiplica la longitud de los vectores por la misma cantidad en ambas direcciones x e y sin cambiar el ángulo entre los vectores. Este bit de bandera es mutuamente excluyente con la bandera TypeGeneralScale.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el System.Object especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El  System.Object  para comparar con esta instancia. |

**Returns:**
boolean - true si el System.Object especificado es igual a esta instancia; de lo contrario, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements() {#getElements--}
```
public float[] getElements()
```


Obtiene una copia de los elementos de la matriz.

**Returns:**
float[] - Una copia de los elementos de la matriz.
### getM11() {#getM11--}
```
public float getM11()
```


Obtiene el elemento de la matriz en la primera fila y primera columna. Representa la escala a lo largo del eje X.

**Returns:**
float
### getM12() {#getM12--}
```
public float getM12()
```


Obtiene el elemento de la matriz en la primera fila y segunda columna. Representa el sesgo a lo largo del eje Y.

**Returns:**
float
### getM21() {#getM21--}
```
public float getM21()
```


Obtiene el elemento de la matriz en la segunda fila y primera columna. Representa el sesgo a lo largo del eje X.

**Returns:**
float
### getM22() {#getM22--}
```
public float getM22()
```


Obtiene el elemento de la matriz en la segunda fila y segunda columna. Representa la escala a lo largo del eje Y.

**Returns:**
float
### getM31() {#getM31--}
```
public float getM31()
```


Obtiene el elemento de la matriz en la tercera fila y primera columna. Representa la traslación a lo largo del eje X.

**Returns:**
float
### getM32() {#getM32--}
```
public float getM32()
```


Obtiene el elemento de la matriz en la tercera fila y primera columna. Representa la traslación a lo largo del eje Y.

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


Determina si dos matrices son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.psd/matrix) | La primera matriz a comparar. |
| b | [Matrix](../../com.aspose.psd/matrix) | La segunda matriz a comparar. |

**Returns:**
boolean - Verdadero si las matrices son iguales.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Devuelve `true` si este `AffineTransform` es una transformación de identidad.

**Returns:**
boolean - `true` si este `AffineTransform` es una transformación identidad; `false` en caso contrario.
### multiply(Matrix Tx) {#multiply-com.aspose.psd.Matrix-}
```
public void multiply(Matrix Tx)
```


Multiplica esta Matrix por la matriz especificada en el parámetro matrix usando el orden (predeterminado) Prepend.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | La matriz con la que multiplicar. |

### multiply(Matrix Tx, int order) {#multiply-com.aspose.psd.Matrix-int-}
```
public void multiply(Matrix Tx, int order)
```


Multiplica esta Matrix por la matriz especificada en el parámetro matrix, y en el orden especificado en el parámetro order.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | El tx. El tx. El tx. |
| orden | int | El orden. El orden. El orden. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


Restablece esta Matrix para que tenga los elementos de la matriz de identidad.

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Aplica una rotación en sentido horario de una cantidad especificada en el parámetro ángulo, alrededor del origen (coordenadas x e y cero) para esta Matrix en el orden predeterminado (Prepend).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Aplica una rotación en sentido horario de una cantidad especificada en el parámetro ángulo, alrededor del origen (coordenadas x e y cero) para esta Matrix en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación. |
| orden | int | El orden de la matriz. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.psd.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Aplica una rotación en sentido horario alrededor del punto especificado a esta Matrix en el orden predeterminado (Prepend).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo. |
| point | [PointF](../../com.aspose.psd/pointf) | El punto. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.psd.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Aplica una rotación en sentido horario alrededor del punto especificado a esta Matrix en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo. |
| point | [PointF](../../com.aspose.psd/pointf) | El punto. |
| orden | int | El orden. |

### scale(float sx, float sy) {#scale-float-float-}
```
public void scale(float sx, float sy)
```


Aplica el vector de escala especificado (scaleX y scaleY) a esta Matrix usando el orden (predeterminado) Prepend.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | El sx. El sx. El sx. |
| sy | float | El sy. El sy. El sy. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Aplica el vector de escala especificado (scaleX y scaleY) a esta  Matrix  usando el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scaleX | float | La escala X. |
| scaleY | float | La escala Y. |
| orden | int | El orden. |

### toString() {#toString--}
```
public String toString()
```


Devuelve un  System.String  que representa esta instancia.

**Returns:**
java.lang.String - Un  System.String  que representa esta instancia.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.psd.PointF---}
```
public void transformPoints(PointF[] points)
```


Aplica la transformación geométrica representada por esta  Matrix  a una matriz especificada de puntos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Los puntos. |

### translate(float tx, float ty) {#translate-float-float-}
```
public void translate(float tx, float ty)
```


Aplica el vector de traslación especificado a esta Matrix usando el orden Prepend (predeterminado).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tx | float | El tx. El tx. El tx. |
| ty | float | El ty. El ty. El ty. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Aplica el vector de traslación especificado a esta Matrix en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| offsetX | float | El desplazamiento X. |
| offsetY | float | El desplazamiento Y. |
| orden | int | El orden. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

