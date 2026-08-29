---
title: "Clase TextureBrush"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Brushes.TextureBrush. Cada propiedad de la clase TextureBrush es un objeto Brush que usa una imagen para rellenar el interior de una forma. Esta clase no se puede heredar"
type: docs
weight: 210
url: /es/net/aspose.psd.brushes/texturebrush/
---
{{< psd/tize >}}
## TextureBrush class

Cada propiedad de la clase `TextureBrush` es un [`Brush`](../../aspose.psd/brush/) que usa una imagen para rellenar el interior de una forma. Esta clase no se puede heredar.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | Inicializa una nueva instancia de la clase `TextureBrush` que usa la imagen especificada. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | Inicializa una nueva instancia de la clase `TextureBrush` que usa la imagen especificada y el rectángulo delimitador. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | Inicializa una nueva instancia de la clase `TextureBrush` que usa la imagen especificada y el rectángulo delimitador. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | Inicializa una nueva instancia de la clase `TextureBrush` que usa la imagen especificada y el modo de ajuste. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | Inicializa una nueva instancia de la clase `TextureBrush` que usa la imagen especificada, el rectángulo delimitador y los atributos de imagen. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | Inicializa una nueva instancia de la clase `TextureBrush` que usa la imagen especificada, el rectángulo delimitador y los atributos de imagen. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | Inicializa una nueva instancia de la clase `TextureBrush` que usa la imagen especificada, el modo de ajuste y el rectángulo delimitador. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | Inicializa una nueva instancia de la clase `TextureBrush` que usa la imagen especificada, el modo de ajuste y el rectángulo delimitador. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | Obtiene el objeto [`Image`](../../aspose.psd/image/) asociado a este objeto `TextureBrush`. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | Obtiene los [`ImageAttributes`](./imageattributes/) asociados a este `TextureBrush`. |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | Obtiene el [`Rectangle`](../../aspose.psd/rectangle/) asociado a este `TextureBrush`. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Obtiene un valor que indica si las transformaciones fueron modificadas de alguna manera. Por ejemplo, establecer la matriz de transformación o llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introdujo para compatibilidad retroactiva con GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Obtiene o establece una copia [`Matrix`](../../aspose.psd/matrix/) que define una transformación geométrica local para este [`TransformBrush`](../transformbrush/). |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Obtiene o establece una enumeración [`WrapMode`](../../aspose.psd/wrapmode/) que indica el modo de ajuste para este [`TransformBrush`](../transformbrush/). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Crea una nueva clonación profunda del [`Brush`](../../aspose.psd/brush/) actual. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Multiplica la [`Matrix`](../../aspose.psd/matrix/) que representa la transformación geométrica local de este [`LinearGradientBrush`](../lineargradientbrush/) por la [`Matrix`](../../aspose.psd/matrix/) especificada, anteponiendo la [`Matrix`](../../aspose.psd/matrix/) especificada. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multiplica la [`Matrix`](../../aspose.psd/matrix/) que representa la transformación geométrica local de este [`LinearGradientBrush`](../lineargradientbrush/) por la [`Matrix`](../../aspose.psd/matrix/) especificada en el orden indicado. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Restablece la propiedad [`Transform`](../transformbrush/transform/) a la identidad. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Rota la transformación geométrica local en la cantidad especificada en el orden indicado. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Escala la transformación geométrica local en las cantidades especificadas. Este método antepone la matriz de escala a la transformación. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Escala la transformación geométrica local en las cantidades especificadas en el orden indicado. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Traslada la transformación geométrica local en las dimensiones especificadas. Este método antepone la traslación a la transformación. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Traslada la transformación geométrica local en las dimensiones especificadas en el orden indicado. |

### Ver también

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


