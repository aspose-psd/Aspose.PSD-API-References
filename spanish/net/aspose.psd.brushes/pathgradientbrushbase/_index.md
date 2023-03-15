---
title: Class PathGradientBrushBase
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.Brushes.PathGradientBrushBase clase. Representa unBrush con funcionalidad de gradiente de ruta base.
type: docs
weight: 180
url: /es/net/aspose.psd.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

Representa un[`Brush`](../../aspose.psd/brush/) con funcionalidad de gradiente de ruta base.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Obtiene o establece el punto central del gradiente de la ruta. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Obtiene o establece el punto de enfoque para la disminución del gradiente. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Obtiene la ruta de gráficos sobre la que se creó este pincel. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Obtiene un valor que indica si las transformaciones se modificaron de alguna manera. Por ejemplo, establecer la matriz de transformación o llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introduce por compatibilidad con versiones anteriores de GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. El valor de 0 significa que el pincel es completamente visible, el valor de 1 significa que el pincel es completamente opaco. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Obtiene los puntos de ruta sobre los que se construyó este pincel. |
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

### Observaciones

Tenga en cuenta que al crear el`PathGradientBrushBase` class debe inicializarse con 2 puntos como mínimo. La ruta interna created siempre será una figura cerrada, el último punto conecta el primer punto. Esa forma está llena de esto.`PathGradientBrushBase`. La implementación de GDI+ genera unOutOfMemoryException al pasar matrices vacías o conjuntos de puntos que tienen las mismas coordenadas. El`PathGradientBrushBase` lanza una excepción cuando la matriz de puntos contiene menos de 2 puntos, elArgumentException is lanzado en lugar deOutOfMemoryException cuando la matriz de puntos es inaceptable. El punto central se calcula como un centro de masa para los puntos pasados de forma predeterminada. Un usuario puede cambiar este punto más tarde. La escala de enfoque es un punto vacío (0.0, 0.0) por defecto.

### Ver también

* class [TransformBrush](../transformbrush/)
* espacio de nombres [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* asamblea [Aspose.PSD](../../)


