---
title: Class CurveShape
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.Shapes.CurveShape clase. Representa una forma de spline curva.
type: docs
weight: 5480
url: /es/net/aspose.psd.shapes/curveshape/
---
## CurveShape class

Representa una forma de spline curva.

```csharp
public sealed class CurveShape : PolygonShape
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | Inicializa una nueva instancia del`CurveShape` clase. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | Inicializa una nueva instancia del`CurveShape` clase. Se utiliza la tensión predeterminada de 0,5. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | Inicializa una nueva instancia del`CurveShape` clase. Se utiliza la tensión predeterminada de 0,5. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | Inicializa una nueva instancia del`CurveShape` clase. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | Inicializa una nueva instancia del`CurveShape` clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | Obtiene los límites del objeto. |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | Obtiene el centro de la forma. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Obtiene el punto de forma final. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Obtiene un valor que indica si la forma tiene segmentos. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Obtiene o establece un valor que indica si la forma está cerrada. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Obtiene o establece los puntos de la curva. |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | Obtiene los segmentos de forma. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Obtiene el punto de forma inicial. |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | Obtiene o establece la tensión de la curva. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | Obtiene los límites del objeto. |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | Obtiene los límites del objeto. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Invierte el orden de los puntos de esta forma. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Aplica la transformación especificada a la forma. |

### Ver también

* class [PolygonShape](../polygonshape/)
* espacio de nombres [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* asamblea [Aspose.PSD](../../)


