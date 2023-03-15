---
title: Class CurveShape
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Shapes.CurveShape classe. Rappresenta una forma spline curva.
type: docs
weight: 5480
url: /it/net/aspose.psd.shapes/curveshape/
---
## CurveShape class

Rappresenta una forma spline curva.

```csharp
public sealed class CurveShape : PolygonShape
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | Inizializza una nuova istanza di`CurveShape` classe. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | Inizializza una nuova istanza di`CurveShape` classe. Viene utilizzata la tensione predefinita di 0,5. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | Inizializza una nuova istanza di`CurveShape` classe. Viene utilizzata la tensione predefinita di 0,5. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | Inizializza una nuova istanza di`CurveShape` classe. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | Inizializza una nuova istanza di`CurveShape` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | Ottiene i limiti dell'oggetto. |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | Ottiene il centro della forma. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Ottiene il punto di forma finale. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Ottiene un valore che indica se la forma ha segmenti. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Ottiene o imposta un valore che indica se la forma è chiusa. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Ottiene o imposta i punti della curva. |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | Ottiene i segmenti della forma. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Ottiene il punto iniziale della forma. |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | Ottiene o imposta la tensione della curva. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | Ottiene i limiti dell'oggetto. |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | Ottiene i limiti dell'oggetto. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Inverte l'ordine dei punti per questa forma. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Applica la trasformazione specificata alla forma. |

### Guarda anche

* class [PolygonShape](../polygonshape/)
* spazio dei nomi [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assemblea [Aspose.PSD](../../)


