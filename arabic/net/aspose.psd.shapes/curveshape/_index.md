---
title: "الفئة CurveShape"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.Shapes.CurveShape. تمثل شكلاً منحنيًا من نوع spline"
type: docs
weight: 5980
url: /ar/net/aspose.psd.shapes/curveshape/
---
{{< psd/tize >}}
## CurveShape class

يمثل شكل منحنى منحنٍ.

```csharp
public sealed class CurveShape : PolygonShape
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | ينشئ مثيلاً جديداً من الفئة `CurveShape`. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | ينشئ مثيلاً جديداً من الفئة `CurveShape`. يتم استخدام الشد الافتراضي بقيمة 0.5. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | ينشئ مثيلاً جديداً من الفئة `CurveShape`. يتم استخدام الشد الافتراضي بقيمة 0.5. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | ينشئ مثيلاً جديداً من الفئة `CurveShape`. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | ينشئ مثيلاً جديداً من الفئة `CurveShape`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | يحصل على حدود الكائن. |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | يحصل على مركز الشكل. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | يحصل على نقطة النهاية للشكل. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل مغلقاً. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | يحصل أو يعيّن نقاط المنحنى. |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | يحصل على مقاطع الشكل. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | يحصل على نقطة بداية الشكل. |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | يحصل أو يعيّن شد المنحنى. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | يحصل على حدود الكائن. |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | يحصل على حدود الكائن. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | يعكس ترتيب النقاط لهذا الشكل. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | يطبق التحويل المحدد على الشكل. |

### انظر أيضًا

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


