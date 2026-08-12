---
title: "Clase PathMulticolorGradientBrush"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Brushes.PathMulticolorGradientBrush. Encapsula un objeto Brush con un degradado. Esta clase no puede heredarse"
type: docs
weight: 190
url: /es/net/aspose.psd.brushes/pathmulticolorgradientbrush/
---
{{< psd/tize >}}
## PathMulticolorGradientBrush class

Encapsula un objeto [`Brush`](../../aspose.psd/brush/) con un degradado. Esta clase no puede heredarse.

```csharp
public sealed class PathMulticolorGradientBrush : PathGradientBrushBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor)(GraphicsPath) | Inicializa una nueva instancia de la clase `PathMulticolorGradientBrush` con la ruta especificada. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_1)(PointF[]) | Inicializa una nueva instancia de la clase `PathMulticolorGradientBrush` con los puntos especificados. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_3)(Point[]) | Inicializa una nueva instancia de la clase `PathMulticolorGradientBrush` con los puntos especificados. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_2)(PointF[], WrapMode) | Inicializa una nueva instancia de la clase `PathMulticolorGradientBrush` con los puntos especificados y el modo de ajuste. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_4)(Point[], WrapMode) | Inicializa una nueva instancia de la clase `PathMulticolorGradientBrush` con los puntos especificados y el modo de ajuste. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Obtiene o establece el punto central del degradado de ruta. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Obtiene o establece el punto focal para la caída del degradado. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Obtiene la ruta gráfica sobre la que se construyó este brush. |
| [InterpolationColors](../../aspose.psd.brushes/pathmulticolorgradientbrush/interpolationcolors/) { get; set; } | Obtiene o establece un [`ColorBlend`](../../aspose.psd/colorblend/) que define un degradado lineal multicolor. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Obtiene un valor que indica si las transformaciones fueron modificadas de alguna manera. Por ejemplo, establecer la matriz de transformación o llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introdujo para compatibilidad retroactiva con GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Obtiene los puntos de ruta sobre los que se construyó este brush. |
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

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


