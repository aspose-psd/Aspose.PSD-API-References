---
title: TextureBrush
second_title: Referencia de API de Aspose.PSD para .NET
description: Cada propiedad delTextureBrush./texturebrush la clase es unBrush../aspose.psd/brush objeto que usa una imagen para llenar el interior de una forma. Esta clase no se puede heredar.
type: docs
weight: 210
url: /es/net/aspose.psd.brushes/texturebrush/
---
## TextureBrush class

Cada propiedad del[`TextureBrush`](../texturebrush) la clase es un[`Brush`](../../aspose.psd/brush) objeto que usa una imagen para llenar el interior de una forma. Esta clase no se puede heredar.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextureBrush](texturebrush#constructor)(Image) | Inicializa una nueva instancia del[`TextureBrush`](../texturebrush) clase que usa la imagen especificada. |
| [TextureBrush](texturebrush#constructor_1)(Image, Rectangle) | Inicializa una nueva instancia del[`TextureBrush`](../texturebrush) clase que usa la imagen especificada y el rectángulo delimitador. |
| [TextureBrush](texturebrush#constructor_3)(Image, RectangleF) | Inicializa una nueva instancia del[`TextureBrush`](../texturebrush) clase que usa la imagen especificada y el rectángulo delimitador. |
| [TextureBrush](texturebrush#constructor_5)(Image, WrapMode) | Inicializa una nueva instancia del[`TextureBrush`](../texturebrush) clase que utiliza la imagen especificada y el modo de ajuste. |
| [TextureBrush](texturebrush#constructor_2)(Image, Rectangle, ImageAttributes) | Inicializa una nueva instancia del[`TextureBrush`](../texturebrush) clase que utiliza la imagen, el rectángulo delimitador y los atributos de imagen especificados. |
| [TextureBrush](texturebrush#constructor_4)(Image, RectangleF, ImageAttributes) | Inicializa una nueva instancia del[`TextureBrush`](../texturebrush) clase que utiliza la imagen, el rectángulo delimitador y los atributos de imagen especificados. |
| [TextureBrush](texturebrush#constructor_6)(Image, WrapMode, Rectangle) | Inicializa una nueva instancia del[`TextureBrush`](../texturebrush)clase que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador. |
| [TextureBrush](texturebrush#constructor_7)(Image, WrapMode, RectangleF) | Inicializa una nueva instancia del[`TextureBrush`](../texturebrush)clase que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [Image](../../aspose.psd.brushes/texturebrush/image) { get; } | Obtiene el[`Image`](../../aspose.psd/image) objeto asociado con este[`TextureBrush`](../texturebrush) objeto. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes) { get; } | Obtiene el[`ImageAttributes`](./imageattributes) asociado con este[`TextureBrush`](../texturebrush) . |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle) { get; } | Obtiene el[`Rectangle`](../../aspose.psd/rectangle) asociado con este[`TextureBrush`](../texturebrush) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged) { get; } | Obtiene un valor que indica si las transformaciones se modificaron de alguna manera. Por ejemplo, establecer la matriz de transformación o llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introduce por compatibilidad con versiones anteriores de GDI+. |
| [Opacity](../../aspose.psd/brush/opacity) { get; set; } | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. El valor de 0 significa que el pincel es completamente visible, el valor de 1 significa que el pincel es completamente opaco. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform) { get; set; } | Obtiene o establece una copia[`Matrix`](../../aspose.psd/matrix) que define una transformación geométrica local para este[`TransformBrush`](../transformbrush) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode) { get; set; } | Obtiene o establece un[`WrapMode`](../../aspose.psd/wrapmode) enumeración que indica el modo de ajuste para este[`TransformBrush`](../transformbrush) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone)() | Crea un nuevo clon profundo del actual[`Brush`](../../aspose.psd/brush) . |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Elimina la instancia actual. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform)(Matrix) | Multiplica el[`Matrix`](../../aspose.psd/matrix) que representa la transformada geométrica local de este[`LinearGradientBrush`](../lineargradientbrush) por el especificado[`Matrix`](../../aspose.psd/matrix) anteponiendo el especificado[`Matrix`](../../aspose.psd/matrix) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | Multiplica el[`Matrix`](../../aspose.psd/matrix) que representa la transformada geométrica local de este[`LinearGradientBrush`](../lineargradientbrush) por el especificado[`Matrix`](../../aspose.psd/matrix) en el orden especificado. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform)() | Restablece el[`Transform`](../transformbrush/transform) propiedad a identidad. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform)(float) | Gira la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a transform. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | Gira la transformación geométrica local en la cantidad especificada en el orden especificado. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform)(float, float) | Escala la transformación geométrica local en las cantidades especificadas. Este método antepone la matriz de escala al transform. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | Escala la transformación geométrica local en las cantidades especificadas en el orden especificado. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float) | Traduce la transformación geométrica local por las dimensiones especificadas. Este método antepone la traducción a transform. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Traduce la transformación geométrica local por las dimensiones especificadas en el orden especificado. |

### Ver también

* class [TransformBrush](../transformbrush)
* espacio de nombres [Aspose.PSD.Brushes](../../aspose.psd.brushes)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
