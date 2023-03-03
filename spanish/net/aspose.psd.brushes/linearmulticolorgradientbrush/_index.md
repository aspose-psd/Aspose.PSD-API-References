---
title: Class LinearMulticolorGradientBrush
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.Brushes.LinearMulticolorGradientBrush clase. Representa unBrush con degradado lineal definido por múltiples colores y posiciones apropiadas. Esta clase no se puede heredar.
type: docs
weight: 160
url: /es/net/aspose.psd.brushes/linearmulticolorgradientbrush/
---
## LinearMulticolorGradientBrush class

Representa un[`Brush`](../../aspose.psd/brush/) con degradado lineal definido por múltiples colores y posiciones apropiadas. Esta clase no se puede heredar.

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor)() | Inicializa una nueva instancia del`LinearMulticolorGradientBrush` clase con parámetros por defecto. El color inicial es negro, el color final es blanco, el ángulo es de 45 grados y el rectángulo está ubicado en (0,0) con tamaño (1,1). |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_1)(Point, Point) | Inicializa una nueva instancia del`LinearMulticolorGradientBrush` clase con los puntos especificados. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_2)(PointF, PointF) | Inicializa una nueva instancia del`LinearMulticolorGradientBrush` clase con los puntos especificados. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_3)(Rectangle, float) | Inicializa una nueva instancia del`LinearMulticolorGradientBrush` clase basada en un rectángulo y un ángulo de orientación. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_5)(RectangleF, float) | Inicializa una nueva instancia del`LinearMulticolorGradientBrush` clase basada en un rectángulo y un ángulo de orientación. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_4)(Rectangle, float, bool) | Inicializa una nueva instancia del`LinearMulticolorGradientBrush` clase basada en un rectángulo y un ángulo de orientación. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_6)(RectangleF, float, bool) | Inicializa una nueva instancia del`LinearMulticolorGradientBrush` clase basada en un rectángulo y un ángulo de orientación. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Obtiene o establece el ángulo de gradiente. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Obtiene o establece un valor que indica si la corrección gamma está habilitada para este[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [InterpolationColors](../../aspose.psd.brushes/linearmulticolorgradientbrush/interpolationcolors/) { get; set; } | Obtiene o establece un[`ColorBlend`](../../aspose.psd/colorblend/) que define un degradado lineal multicolor. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Obtiene o establece un valor que indica si[`Angle`](../lineargradientbrushbase/angle/) se cambia durante las transformaciones con este[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Obtiene un valor que indica si las transformaciones se modificaron de alguna manera. Por ejemplo, establecer la matriz de transformación o llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introduce por compatibilidad con versiones anteriores de GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. El valor de 0 significa que el pincel es completamente visible, el valor de 1 significa que el pincel es completamente opaco. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Obtiene o establece una región rectangular que define los puntos inicial y final del degradado. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Obtiene o establece una copia[`Matrix`](../../aspose.psd/matrix/) que define una transformación geométrica local para este[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Obtiene o establece un[`WrapMode`](../../aspose.psd/wrapmode/) enumeración que indica el modo de ajuste para este[`TransformBrush`](../transformbrush/) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Crea un nuevo clon profundo del actual[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina la instancia actual. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Multiplica el[`Matrix`](../../aspose.psd/matrix/) que representa la transformada geométrica local de este[`LinearGradientBrush`](../lineargradientbrush/) por el especificado[`Matrix`](../../aspose.psd/matrix/) anteponiendo el especificado[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multiplica el[`Matrix`](../../aspose.psd/matrix/) que representa la transformada geométrica local de este[`LinearGradientBrush`](../lineargradientbrush/) por el especificado[`Matrix`](../../aspose.psd/matrix/) en el orden especificado. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Restablece el[`Transform`](../transformbrush/transform/) propiedad a identidad. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Gira la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a transform. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Gira la transformación geométrica local en la cantidad especificada en el orden especificado. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Escala la transformación geométrica local en las cantidades especificadas. Este método antepone la matriz de escala al transform. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Escala la transformación geométrica local en las cantidades especificadas en el orden especificado. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Traduce la transformación geométrica local por las dimensiones especificadas. Este método antepone la traducción a transform. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Traduce la transformación geométrica local por las dimensiones especificadas en el orden especificado. |

### Ver también

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* espacio de nombres [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* asamblea [Aspose.PSD](../../)


