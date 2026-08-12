---
title: "Clase LinearGradientBrushBase"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Brushes.LinearGradientBrushBase. Representa un Brush con capacidades de degradado y propiedades apropiadas."
type: docs
weight: 150
url: /es/net/aspose.psd.brushes/lineargradientbrushbase/
---
{{< psd/tize >}}
## LinearGradientBrushBase class

Representa un [`Brush`](../../aspose.psd/brush/) con capacidades de degradado y propiedades apropiadas.

```csharp
public abstract class LinearGradientBrushBase : TransformBrush
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Obtiene o establece el ángulo del degradado. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Obtiene o establece un valor que indica si la corrección gamma está habilitada para este `LinearGradientBrushBase`. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Obtiene o establece un valor que indica si [`Angle`](./angle/) se cambia durante las transformaciones con este `LinearGradientBrushBase`. |
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

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


