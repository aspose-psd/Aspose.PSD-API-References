---
title: Class CurveShape
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Shapes.CurveShape sınıf. Eğri bir spline şeklini temsil eder.
type: docs
weight: 5480
url: /tr/net/aspose.psd.shapes/curveshape/
---
## CurveShape class

Eğri bir spline şeklini temsil eder.

```csharp
public sealed class CurveShape : PolygonShape
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | Yeni bir örneğini başlatır.`CurveShape` sınıf. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | Yeni bir örneğini başlatır.`CurveShape` sınıf. 0,5'lik varsayılan gerilim kullanılır. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | Yeni bir örneğini başlatır.`CurveShape` sınıf. 0,5'lik varsayılan gerilim kullanılır. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | Yeni bir örneğini başlatır.`CurveShape` sınıf. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | Yeni bir örneğini başlatır.`CurveShape` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | Nesnenin sınırlarını alır. |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | Şeklin merkezini alır. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Bitiş şekil noktasını alır. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Şeklin segmentleri olup olmadığını gösteren bir değer alır. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Şeklin kapalı olup olmadığını gösteren bir değer alır veya ayarlar. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Eğri noktalarını alır veya ayarlar. |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | Şekil segmentlerini alır. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Başlangıç şekil noktasını alır. |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | Eğri gerilimini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | Nesnenin sınırlarını alır. |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | Nesnenin sınırlarını alır. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Bu şekil için noktaların sırasını tersine çevirir. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Belirtilen dönüşümü şekle uygular. |

### Ayrıca bakınız

* class [PolygonShape](../polygonshape/)
* ad alanı [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* toplantı [Aspose.PSD](../../)


