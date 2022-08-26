---
title: Matrix
second_title: Referencia de API de Aspose.PSD para .NET
description: Reemplaza la Matriz GDI.
type: docs
weight: 5020
url: /es/net/aspose.psd/matrix/
---
## Matrix class

Reemplaza la Matriz GDI+.

```csharp
public class Matrix
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Matrix](matrix#constructor)() | Inicializa una nueva instancia de la clase Matrix como matriz de identidad. |
| [Matrix](matrix#constructor_1)(Matrix) | Hace una copia del[`Matrix`](../matrix) clase. |
| [Matrix](matrix#constructor_2)(Rectangle, Point[]) | Inicializa una nueva instancia del[`Matrix`](../matrix) clase a la transformación geométrica definida por el rectángulo especificado y la matriz de puntos. |
| [Matrix](matrix#constructor_3)(RectangleF, PointF[]) | Inicializa una nueva instancia del[`Matrix`](../matrix) clase a la transformación geométrica definida por el rectángulo especificado y la matriz de puntos. |
| [Matrix](matrix#constructor_4)(float, float, float, float, float, float) | Inicializa una nueva instancia del[`Matrix`](../matrix) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements) { get; } | Obtiene una matriz de valores de punto flotante que representa los elementos de este[`Matrix`](../matrix) . |
| [M11](../../aspose.psd/matrix/m11) { get; } | Obtiene el elemento de la matriz en la primera columna de la primera fila. Representa la escala a lo largo del eje X. |
| [M12](../../aspose.psd/matrix/m12) { get; } | Obtiene el elemento de matriz en la primera fila, segunda columna. Representa cortante a lo largo del eje Y. |
| [M21](../../aspose.psd/matrix/m21) { get; } | Obtiene el elemento de la matriz en la primera columna de la segunda fila. Representa cortante a lo largo del eje X. |
| [M22](../../aspose.psd/matrix/m22) { get; } | Obtiene el elemento de matriz en la segunda columna de la segunda fila. Representa la escala a lo largo del eje Y. |
| [M31](../../aspose.psd/matrix/m31) { get; } | Obtiene el elemento de la matriz en la primera columna de la tercera fila. Representa la traslación a lo largo del eje X. |
| [M32](../../aspose.psd/matrix/m32) { get; } | Obtiene el elemento de la matriz en la primera columna de la tercera fila. Representa la traslación a lo largo del eje Y. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals)(object) | Determina si el especificadoObject es igual a esta instancia. |
| [GetElements](../../aspose.psd/matrix/getelements)() | Obtiene la copia de los elementos de la matriz. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode)() | Devuelve un código hash para esta instancia. |
| [Multiply](../../aspose.psd/matrix/multiply#multiply)(Matrix) | Multiplica esta Matriz por la matriz especificada en el parámetro de matriz usando (predeterminado) Orden antepuesto. |
| [Multiply](../../aspose.psd/matrix/multiply#multiply_1)(Matrix, MatrixOrder) | Multiplica esta Matriz por la matriz especificada en el parámetro de matriz, y en el orden especificado en el parámetro de orden. |
| [Reset](../../aspose.psd/matrix/reset)() | Restablece esta Matriz para tener los elementos de la matriz identidad. |
| [Rotate](../../aspose.psd/matrix/rotate#rotate)(float) | Aplica una rotación en el sentido de las agujas del reloj de una cantidad especificada en el parámetro de ángulo, alrededor del origen (coordenadas x e y cero) para esta matriz en el orden predeterminado (anteponer). |
| [Rotate](../../aspose.psd/matrix/rotate#rotate_1)(float, MatrixOrder) | Aplica una rotación en el sentido de las agujas del reloj de una cantidad especificada en el parámetro de ángulo, alrededor del origen (coordenadas x e y cero) para esta Matriz en el orden especificado. |
| [RotateAt](../../aspose.psd/matrix/rotateat#rotateat)(float, PointF) | Aplica una rotación en el sentido de las agujas del reloj sobre el punto especificado a esta matriz en el orden predeterminado (anteponer). |
| [RotateAt](../../aspose.psd/matrix/rotateat#rotateat_1)(float, PointF, MatrixOrder) | Aplica una rotación en el sentido de las agujas del reloj sobre el punto especificado a esta Matriz en el orden especificado. |
| [Scale](../../aspose.psd/matrix/scale#scale)(float, float) | Aplica el vector de escala especificado (escalaX y escalaY) a esta Matriz usando (predeterminado) orden antepuesto. |
| [Scale](../../aspose.psd/matrix/scale#scale_1)(float, float, MatrixOrder) | Aplica el vector de escala especificado (scaleX y scaleY) a este[`Matrix`](../matrix) utilizando el orden especificado. |
| override [ToString](../../aspose.psd/matrix/tostring)() | Devuelve unString que representa esta instancia. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints)(PointF[]) | Aplica la transformación geométrica representada por este[`Matrix`](../matrix) a una matriz especificada de puntos. |
| [Translate](../../aspose.psd/matrix/translate#translate)(float, float) | Aplica el vector de traducción especificado a este[`Matrix`](../matrix) usando (predeterminado) Orden antepuesto. |
| [Translate](../../aspose.psd/matrix/translate#translate_1)(float, float, MatrixOrder) | Aplica el vector de traducción especificado a esta Matriz en el orden especificado. |
| static [Equals](../../aspose.psd/matrix/equals)(Matrix, Matrix) | Determina si dos matrices son iguales. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip) | Este bit indicador indica que la transformación definida por este objeto realiza un giro de imagen especular sobre algún eje que cambia el sistema de coordenadas normalmente de mano derecha a un sistema zurdo además de las conversiones indicadas por otros bits de bandera. Un sistema de coordenadas de mano derecha es uno en el que el eje X positivo gira en sentido contrario a las agujas del reloj para superponerse al eje Y positivo similar a la dirección en la que los dedos de la mano derecha se curvan cuando miras el extremo del pulgar. Un sistema de coordenadas para zurdos es aquel en el que el eje X positivo gira en el sentido de las agujas del reloj para superponer el eje Y positivo similar a la dirección en la que se curvan los dedos de la mano izquierda. No existe una forma matemática de determinar el ángulo de la transformación de volteo o espejo original de ya que todos los ángulos de volteo son idénticos dada una rotación de ajuste adecuada. NOTA: TypeFlip se agregó después de GENERAL_TRANSFORM estaba en circulación pública y los bits de la bandera ya no podían volver a numerarse convenientemente sin introducir una incompatibilidad binaria en el código exterior . |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation) | Este bit indicador indica que la transformación definida por este objeto realiza una rotación en un ángulo arbitrario además de las conversiones indicadas por otros bits indicadores. Una rotación cambia los ángulos de los vectores en la misma cantidad independientemente de la dirección original del vector y sin cambiando la longitud del vector. Este bit indicador es mutuamente excluyente con el |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale) | Una escala general multiplica la longitud de los vectores por diferentes cantidades en las direcciones x e y sin cambiar el ángulo entre vectores perpendiculares. Este bit indicador es mutuamente excluyente con el indicador TypeUniformScale. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform) | Esta constante indica que la transformación definida por este objeto realiza una conversión arbitraria de las coordenadas de entrada. Si esta transformación se puede clasificar mediante cualquiera de las constantes anteriores, el tipo será la constante TypeIdentity o una combinación de la bandera adecuada bits para las distintas conversiones de coordenadas que realiza esta transformación. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity) | Una transformación de identidad es aquella en la que las coordenadas de salida son siempre las mismas que las coordenadas de entrada. Si esta transformación es diferente a la transformación de identidad, el tipo será la constante GENERAL_TRANSFORM o una combinación de los bits de marca apropiados para las diversas conversiones de coordenadas que realiza esta transformación. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation) | Esta constante es una máscara de bits para cualquiera de los bits del indicador de rotación. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale) | Esta constante es una máscara de bits para cualquiera de los bits de bandera de escala. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation) | Este bit indicador indica que la transformación definida por este objeto realiza una rotación de cuadrante por algún múltiplo de 90 grados en además de las conversiones indicadas por otros bits indicadores. Una rotación cambia los ángulos de los vectores en la misma cantidad independientemente de la dirección original del vector y sin cambiando la longitud del vector. Este bit indicador es mutuamente excluyente con el indicador TypeGeneralRotation. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation) | Una traslación mueve las coordenadas en una cantidad constante en x e y sin cambiar la longitud o el ángulo de los vectores. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale) | Una escala uniforme multiplica la longitud de los vectores por la misma cantidad en las direcciones x e y sin cambiar el ángulo entre los vectores . Este bit indicador se excluye mutuamente con el indicador TypeGeneralScale. |

### Observaciones

La mayoría de los algoritmos tomados de Sun's AffineTransform.java. Nombres de Java para los elementos de la matriz usados internamente. Mapa de los nombres de Java a los de .net a la descripción: m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear X m11 M22 Scaled1_m11 M22 Scaled1_m020 Trasladar X m12 M32 Trasladar Y

### Ver también

* espacio de nombres [Aspose.PSD](../../aspose.psd)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
