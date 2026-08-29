---
title: "Klass CurveShape"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Shapes.CurveShape-klass. Representerar en böjd splineform"
type: docs
weight: 5980
url: /sv/net/aspose.psd.shapes/curveshape/
---
{{< psd/tize >}}
## CurveShape class

Representerar en kurvad spline-form.

```csharp
public sealed class CurveShape : PolygonShape
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | Initierar en ny instans av `CurveShape`-klassen. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | Initierar en ny instans av `CurveShape`-klassen. Standardspänningen 0,5 används. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | Initierar en ny instans av `CurveShape`-klassen. Standardspänningen 0,5 används. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | Initierar en ny instans av `CurveShape`-klassen. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | Initierar en ny instans av `CurveShape`-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | Hämtar objektets gränser. |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | Hämtar formens centrum. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Hämtar den avslutande formpunkten. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Hämtar ett värde som indikerar om formen har segment. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Hämtar eller anger ett värde som indikerar om formen är sluten. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Hämtar eller anger kurvpunkterna. |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | Hämtar formens segment. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Hämtar den startande formpunkten. |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | Hämtar eller anger kurvspänningen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | Hämtar objektets gränser. |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | Hämtar objektets gränser. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Vänder ordningen på punkterna för denna form. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Tillämpar den angivna transformationen på formen. |

### Se även

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


