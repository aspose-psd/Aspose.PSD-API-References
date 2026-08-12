---
title: "Clase LinearMulticolorGradientBrush"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Brushes.LinearMulticolorGradientBrush. Representa un Brush con un degradado lineal definido por múltiples colores y posiciones apropiadas. Esta clase no puede ser heredada"
type: docs
weight: 160
url: /es/net/aspose.psd.brushes/linearmulticolorgradientbrush/
---
{{< psd/tize >}}
## LinearMulticolorGradientBrush class

Representa un [`Brush`](../../aspose.psd/brush/) con un degradado lineal definido por múltiples colores y posiciones apropiadas. Esta clase no puede ser heredada.

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor)() | Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` con parámetros predeterminados. El color inicial es negro, el color final es blanco, el ángulo es de 45 grados y el rectángulo está ubicado en (0,0) con tamaño (1,1). |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_1)(Point, Point) | Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` con los puntos especificados. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_2)(PointF, PointF) | Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` con los puntos especificados. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_3)(Rectangle, float) | Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` basada en un rectángulo y un ángulo de orientación. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_5)(RectangleF, float) | Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` basada en un rectángulo y un ángulo de orientación. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_4)(Rectangle, float, bool) | Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` basada en un rectángulo y un ángulo de orientación. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_6)(RectangleF, float, bool) | Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` basada en un rectángulo y un ángulo de orientación. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Obtiene o establece el ángulo del degradado. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Obtiene o establece un valor que indica si la corrección gamma está habilitada para este [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [InterpolationColors](../../aspose.psd.brushes/linearmulticolorgradientbrush/interpolationcolors/) { get; set; } | Obtiene o establece un [`ColorBlend`](../../aspose.psd/colorblend/) que define un degradado lineal multicolor. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Obtiene o establece un valor que indica si [`Angle`](../lineargradientbrushbase/angle/) se cambia durante las transformaciones con este [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Obtiene un valor que indica si las transformaciones fueron modificadas de alguna manera. Por ejemplo, establecer la matriz de transformación o llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introdujo para compatibilidad retroactiva con GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Obtiene o establece una región rectangular que define los puntos de inicio y fin del degradado. |
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

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


