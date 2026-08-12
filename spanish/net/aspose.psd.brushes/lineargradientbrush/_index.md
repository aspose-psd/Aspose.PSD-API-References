---
title: "Clase LinearGradientBrush"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Brushes.LinearGradientBrush. Encapsula un Brush con un degradado lineal. Esta clase no puede ser heredada"
type: docs
weight: 140
url: /es/net/aspose.psd.brushes/lineargradientbrush/
---
{{< psd/tize >}}
## LinearGradientBrush class

Encapsula un [`Brush`](../../aspose.psd/brush/) con un degradado lineal. Esta clase no puede ser heredada.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | Inicializa una nueva instancia de la clase `LinearGradientBrush` con parámetros predeterminados. El color inicial es black, el color final es white, el ángulo es 45 grados y el rectángulo está ubicado en (0,0) con tamaño (1,1). |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | Inicializa una nueva instancia de la clase `LinearGradientBrush` con los puntos y colores especificados. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | Inicializa una nueva instancia de la clase `LinearGradientBrush` con los puntos y colores especificados. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | Inicializa una nueva instancia de la clase `LinearGradientBrush` basada en un rectángulo, colores inicial y final, y un ángulo de orientación. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | Inicializa una nueva instancia de la clase `LinearGradientBrush` basada en un rectángulo, colores inicial y final, y un ángulo de orientación. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | Inicializa una nueva instancia de la clase `LinearGradientBrush` basada en un rectángulo, colores inicial y final, y un ángulo de orientación. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | Inicializa una nueva instancia de la clase `LinearGradientBrush` basada en un rectángulo, colores inicial y final, y un ángulo de orientación. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Obtiene o establece el ángulo del degradado. |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | Obtiene o establece un [`Blend`](../../aspose.psd/blend/) que especifica posiciones y factores que definen una caída personalizada para el degradado. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | Obtiene o establece el color final del degradado. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Obtiene o establece un valor que indica si la corrección gamma está habilitada para este [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [InterpolationColors](../../aspose.psd.brushes/lineargradientbrush/interpolationcolors/) { get; set; } | Obtiene o establece un [`ColorBlend`](../../aspose.psd/colorblend/) que define un degradado lineal multicolor. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Obtiene o establece un valor que indica si [`Angle`](../lineargradientbrushbase/angle/) se cambia durante las transformaciones con este [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Obtiene un valor que indica si las transformaciones fueron modificadas de alguna manera. Por ejemplo, establecer la matriz de transformación o llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introdujo para compatibilidad retroactiva con GDI+. |
| [LinearColors](../../aspose.psd.brushes/lineargradientbrush/linearcolors/) { get; set; } | Obtiene o establece los colores inicial y final del degradado. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Obtiene o establece una región rectangular que define los puntos de inicio y fin del degradado. |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | Obtiene o establece el color inicial del degradado. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Obtiene o establece una copia [`Matrix`](../../aspose.psd/matrix/) que define una transformación geométrica local para este [`TransformBrush`](../transformbrush/). |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Obtiene o establece una enumeración [`WrapMode`](../../aspose.psd/wrapmode/) que indica el modo de ajuste para este [`TransformBrush`](../transformbrush/). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Crea una nueva clonación profunda del [`Brush`](../../aspose.psd/brush/) actual. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Multiplica la [`Matrix`](../../aspose.psd/matrix/) que representa la transformación geométrica local de este `LinearGradientBrush` por la [`Matrix`](../../aspose.psd/matrix/) especificada, anteponiendo la [`Matrix`](../../aspose.psd/matrix/) especificada. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multiplica la [`Matrix`](../../aspose.psd/matrix/) que representa la transformación geométrica local de este `LinearGradientBrush` por la [`Matrix`](../../aspose.psd/matrix/) en el orden especificado. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Restablece la propiedad [`Transform`](../transformbrush/transform/) a la identidad. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Rota la transformación geométrica local en la cantidad especificada en el orden indicado. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Escala la transformación geométrica local en las cantidades especificadas. Este método antepone la matriz de escala a la transformación. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Escala la transformación geométrica local en las cantidades especificadas en el orden indicado. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Crea una caída de degradado basada en una curva en forma de campana. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Crea una caída de degradado basada en una curva en forma de campana. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Traslada la transformación geométrica local en las dimensiones especificadas. Este método antepone la traslación a la transformación. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Traslada la transformación geométrica local en las dimensiones especificadas en el orden indicado. |

### Ver también

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


