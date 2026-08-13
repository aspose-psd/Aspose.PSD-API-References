---
title: "Sınıf CurveShape"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Shapes.CurveShape sınıfı. Eğri bir spline şekli temsil eder"
type: docs
weight: 6010
url: /tr/net/aspose.psd.shapes/curveshape/
---
{{< psd/tize >}}
## CurveShape class

Eğri bir spline şekli temsil eder.

```csharp
public sealed class CurveShape : PolygonShape
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | `CurveShape` sınıfının yeni bir örneğini başlatır. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | `CurveShape` sınıfının yeni bir örneğini başlatır. Varsayılan 0.5 gerilimi kullanılır. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | `CurveShape` sınıfının yeni bir örneğini başlatır. Varsayılan 0.5 gerilimi kullanılır. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | `CurveShape` sınıfının yeni bir örneğini başlatır. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | `CurveShape` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | Nesnenin sınırlarını alır. |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | Şeklin merkezini alır. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Şeklin son noktasını alır. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Şeklin segmentlere sahip olup olmadığını gösteren bir değeri alır. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Eğri noktalarını alır veya ayarlar. |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | Şekil segmentlerini alır. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Şeklin başlangıç noktasını alır. |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | Eğri gerilimini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | Nesnenin sınırlarını alır. |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | Nesnenin sınırlarını alır. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Bu şekil için nokta sırasını tersine çevirir. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Belirtilen dönüşümü şekle uygular. |

### Ayrıca Bakınız

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


