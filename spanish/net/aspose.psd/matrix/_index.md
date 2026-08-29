---
title: "Clase Matrix"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Matrix. Reemplaza la Matrix GDI"
type: docs
weight: 5580
url: /es/net/aspose.psd/matrix/
---
{{< psd/tize >}}
## Matrix class

Reemplaza la matriz GDI+.

```csharp
public class Matrix
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Matrix](matrix/#constructor)() | Inicializa una nueva instancia de la clase Matrix como la matriz identidad. |
| [Matrix](matrix/#constructor_1)(Matrix) | Crea una copia de la clase `Matrix`. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | Inicializa una nueva instancia de la clase `Matrix` con la transformación geométrica definida por el rectángulo especificado y la matriz de puntos. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | Inicializa una nueva instancia de la clase `Matrix` con la transformación geométrica definida por el rectángulo especificado y la matriz de puntos. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | Inicializa una nueva instancia de la clase `Matrix`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | Obtiene una matriz de valores de punto flotante que representa los elementos de este `Matrix`. |
| [M11](../../aspose.psd/matrix/m11/) { get; } | Obtiene el elemento de la matriz en la primera fila, primera columna. Representa la escala a lo largo del eje X. |
| [M12](../../aspose.psd/matrix/m12/) { get; } | Obtiene el elemento de la matriz en la primera fila, segunda columna. Representa el cizallamiento a lo largo del eje Y. |
| [M21](../../aspose.psd/matrix/m21/) { get; } | Obtiene el elemento de la matriz en la segunda fila, primera columna. Representa el cizallamiento a lo largo del eje X. |
| [M22](../../aspose.psd/matrix/m22/) { get; } | Obtiene el elemento de la matriz en la segunda fila, segunda columna. Representa la escala a lo largo del eje Y. |
| [M31](../../aspose.psd/matrix/m31/) { get; } | Obtiene el elemento de la matriz en la tercera fila, primera columna. Representa la traslación a lo largo del eje X. |
| [M32](../../aspose.psd/matrix/m32/) { get; } | Obtiene el elemento de la matriz en la tercera fila, primera columna. Representa la traslación a lo largo del eje Y. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | Determina si el objeto especificado es igual a esta instancia. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | Obtiene la copia de los elementos de la matriz. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | Devuelve un código hash para esta instancia. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | Multiplica esta Matrix por la matriz especificada en el parámetro matrix usando el orden (predeterminado) Prepend. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | Multiplica esta Matrix por la matriz especificada en el parámetro matrix, y en el orden especificado en el parámetro order. |
| [Reset](../../aspose.psd/matrix/reset/)() | Restablece esta Matrix para que tenga los elementos de la matriz identidad. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | Aplica una rotación en sentido horario de una cantidad especificada en el parámetro angle, alrededor del origen (coordenadas x e y cero) para esta Matrix en el orden predeterminado (Prepend). |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | Aplica una rotación en sentido horario de una cantidad especificada en el parámetro angle, alrededor del origen (coordenadas x e y cero) para esta Matrix en el orden especificado. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | Aplica una rotación en sentido horario alrededor del punto especificado a esta Matrix en el orden predeterminado (Prepend). |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | Aplica una rotación en sentido horario alrededor del punto especificado a esta Matrix en el orden especificado. |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | Aplica el vector de escala especificado (scaleX y scaleY) a esta Matrix usando el orden (predeterminado) Prepend. |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | Aplica el vector de escala especificado (scaleX y scaleY) a este `Matrix` usando el orden especificado. |
| override [ToString](../../aspose.psd/matrix/tostring/)() | Devuelve una String que representa esta instancia. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | Aplica la transformación geométrica representada por este `Matrix` a una matriz especificada de puntos. |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | Aplica el vector de traslación especificado a este `Matrix` usando el orden (predeterminado) Prepend. |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | Aplica el vector de traslación especificado a esta Matrix en el orden especificado. |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | Determina si dos matrices son iguales. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | Este bit de bandera indica que la transformación definida por este objeto realiza una inversión de imagen espejo alrededor de algún eje, lo que cambia el sistema de coordenadas normalmente derecho a uno izquierdo, además de las conversiones indicadas por otros bits de bandera. Un sistema de coordenadas derecho es aquel donde el eje X positivo gira en sentido antihorario para superponerse al eje Y positivo, similar a la dirección en que los dedos de tu mano derecha se curvan cuando miras de frente tu pulgar. Un sistema de coordenadas izquierdo es aquel donde el eje X positivo gira en sentido horario para superponerse al eje Y positivo, similar a la dirección en que los dedos de tu mano izquierda se curvan. No hay forma matemática de determinar el ángulo de la transformación original de volteo o espejo, ya que todos los ángulos de volteo son idénticos dado una rotación de ajuste apropiada. NOTA: TypeFlip se añadió después de que GENERAL_TRANSFORM estuviera en circulación pública y los bits de bandera ya no pudieron renumerarse convenientemente sin introducir incompatibilidad binaria en código externo. |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | Este bit de bandera indica que la transformación definida por este objeto realiza una rotación por un ángulo arbitrario, además de las conversiones indicadas por otros bits de bandera. Una rotación cambia los ángulos de los vectores en la misma cantidad sin importar la dirección original del vector y sin cambiar la longitud del vector. Este bit de bandera es mutuamente excluyente con el |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | Una escala general multiplica la longitud de los vectores por diferentes cantidades en las direcciones x e y sin cambiar el ángulo entre vectores perpendiculares. Este bit de bandera es mutuamente excluyente con la bandera TypeUniformScale. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | Esta constante indica que la transformación definida por este objeto realiza una conversión arbitraria de las coordenadas de entrada. Si esta transformación puede clasificarse mediante cualquiera de las constantes anteriores, el tipo será la constante TypeIdentity o una combinación de los bits de bandera apropiados para las diversas conversiones de coordenadas que realiza esta transformación. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | Una transformación identidad es aquella en la que las coordenadas de salida son siempre las mismas que las coordenadas de entrada. Si esta transformación es diferente de la transformación identidad, el tipo será la constante GENERAL_TRANSFORM o una combinación de los bits de bandera apropiados para las diversas conversiones de coordenadas que realiza esta transformación. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | Esta constante es una máscara de bits para cualquiera de los bits de bandera de rotación. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | Esta constante es una máscara de bits para cualquiera de los bits de bandera de escala. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | Este bit de bandera indica que la transformación definida por este objeto realiza una rotación de cuadrante en un múltiplo de 90 grados, además de las conversiones indicadas por otros bits de bandera. Una rotación cambia los ángulos de los vectores en la misma cantidad sin importar la dirección original del vector y sin cambiar la longitud del vector. Este bit de bandera es mutuamente excluyente con la bandera TypeGeneralRotation. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | Una traslación mueve las coordenadas una cantidad constante en x e y sin cambiar la longitud o el ángulo de los vectores. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | Una escala uniforme multiplica la longitud de los vectores por la misma cantidad en las direcciones x e y sin cambiar el ángulo entre los vectores. Este bit de bandera es mutuamente excluyente con la bandera TypeGeneralScale. |

## Observaciones

La mayoría de los algoritmos se tomaron de AffineTransform.java de Sun. Nombres de Java para los elementos de la matriz usados internamente. Mapa de nombres de java a los de .net con descripción: m00 M11 Escala X m10 M12 Cizalla Y m01 M21 Cizalla X m11 M22 Escala Y m02 M31 Trasladar X m12 M32 Trasladar Y

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


