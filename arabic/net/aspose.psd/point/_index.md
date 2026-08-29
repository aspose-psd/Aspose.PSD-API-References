---
title: "بنية Point"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "بنية Aspose.PSD.Point. تمثل زوجًا مرتبًا من إحداثيات صحيحة x و y يحدد نقطة في مستوى ثنائي الأبعاد."
type: docs
weight: 5760
url: /ar/net/aspose.psd/point/
---
{{< psd/tize >}}
## Point structure

يمثل زوجًا مرتبًا من إحداثيات x و y الصحيحة التي تحدد نقطة في مستوى ثنائي الأبعاد.

```csharp
public struct Point
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Point](point/#constructor_1)(int) | ينشئ مثيلًا جديدًا من بنية `Point` باستخدام إحداثيات محددة بقيمة صحيحة. |
| [Point](point/#constructor)(Size) | ينشئ مثيلًا جديدًا من بنية `Point` من بنية [`Size`](../size/). |
| [Point](point/#constructor_2)(int, int) | ينشئ مثيلًا جديدًا من بنية `Point` بالإحداثيات المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | يحصل على مثيل جديد من بنية `Point` تكون قيمتي [`X`](./x/) و [`Y`](./y/) فيها مضبوطة على الصفر. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه `Point` فارغة. |
| [X](../../aspose.psd/point/x/) { get; set; } | يحصل أو يعيّن الإحداثي x لهذه `Point`. |
| [Y](../../aspose.psd/point/y/) { get; set; } | يحصل أو يعيّن الإحداثي y لهذه `Point`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | يضيف الـ [`Size`](../size/) المحدد إلى الـ `Point` المحدد. |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | يحوّل الـ [`PointF`](../pointf/) المحدد إلى `Point` عن طريق تقريب قيم الـ [`PointF`](../pointf/) إلى القيم الصحيحة الأعلى التالية. |
| static [Round](../../aspose.psd/point/round/)(PointF) | يحوّل الـ [`PointF`](../pointf/) المحدد إلى كائن `Point` عن طريق تقريب قيم الـ `Point` إلى أقرب عدد صحيح. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | يعيد نتيجة طرح الـ [`Size`](../size/) المحدد من الـ `Point` المحدد. |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | يحوّل الـ [`PointF`](../pointf/) المحدد إلى `Point` عن طريق قطع قيم الـ `Point`. |
| override [Equals](../../aspose.psd/point/equals/)(object) | يحدد ما إذا كانت هذه `Point` تحتوي على نفس الإحداثيات كالكائن المحدد. |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | يعيد رمز تجزئة (hash code) لهذه `Point`. |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | ينقل هذه `Point` بالـ `Point` المحدد. |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | ينقل هذه `Point` بالمقدار المحدد. |
| override [ToString](../../aspose.psd/point/tostring/)() | يحوّل هذه `Point` إلى سلسلة قابلة للقراءة من قبل الإنسان. |
| [operator +](../../aspose.psd/point/op_addition/) | ينقل `Point` بمقدار [`Size`](../size/) معين. |
| [operator ==](../../aspose.psd/point/op_equality/) | يقارن كائنين `Point`. النتيجة تحدد ما إذا كانت قيم الخاصيتين [`X`](./x/) و[`Y`](./y/) لكائنين `Point` متساوية. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | يحوّل الهيكل `Point` المحدد إلى هيكل [`Size`](../size/). |
| [implicit operator](../../aspose.psd/point/op_implicit/) | يحوّل الهيكل `Point` المحدد إلى هيكل [`PointF`](../pointf/). |
| [operator !=](../../aspose.psd/point/op_inequality/) | يقارن كائنين `Point`. النتيجة تحدد ما إذا كانت قيم الخاصيتين [`X`](./x/) أو [`Y`](./y/) لكائنين `Point` غير متساوية. |
| [operator -](../../aspose.psd/point/op_subtraction/) | يُحرك `Point` بالسالب للـ [`Size`](../size/) المحدد. |

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


