---
title: Class CurveShape
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Shapes.CurveShape klass. Representerar en krökt splineform.
type: docs
weight: 5480
url: /sv/net/aspose.psd.shapes/curveshape/
---
## CurveShape class

Representerar en krökt splineform.

```csharp
public sealed class CurveShape : PolygonShape
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | Initierar en ny instans av`CurveShape` class. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | Initierar en ny instans av`CurveShape` klass. Standardspänningen på 0,5 används. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | Initierar en ny instans av`CurveShape` klass. Standardspänningen på 0,5 används. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | Initierar en ny instans av`CurveShape` class. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | Initierar en ny instans av`CurveShape` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | Hämtar objektets gränser. |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | Hämtar formens centrum. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Får slutformpunkten. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Får ett värde som indikerar om formen har segment. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Hämtar eller ställer in ett värde som anger om formen är stängd. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Hämtar eller ställer in kurvpunkterna. |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | Hämtar formsegmenten. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Får startpunkten för formen. |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | Får eller ställer in kurvspänningen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | Hämtar objektets gränser. |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | Hämtar objektets gränser. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Vänder om ordningen på punkterna för denna form. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Tillämpar den angivna transformationen på formen. |

### Se även

* class [PolygonShape](../polygonshape/)
* namnutrymme [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* hopsättning [Aspose.PSD](../../)


