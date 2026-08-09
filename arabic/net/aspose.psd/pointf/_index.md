---
title: "البنية PointF"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "البنية Aspose.PSD.PointF. تمثل زوجًا مرتبًا من إحداثيات x و y ذات الفاصلة العائمة التي تحدد نقطة في مستوى ثنائي الأبعاد."
type: docs
weight: 5770
url: /ar/net/aspose.psd/pointf/
---
{{< psd/tize >}}
## PointF structure

يمثل زوجًا مرتبًا من إحداثيات x و y ذات الفاصلة العائمة التي تحدد نقطة في مستوى ثنائي الأبعاد.

```csharp
public struct PointF
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PointF](pointf/)(float, float) | ينشئ مثيلًا جديدًا للهيكل `PointF` بالإحداثيات المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Empty](../../aspose.psd/pointf/empty/) { get; } | يحصل على نسخة جديدة من بنية `PointF` التي لديها قيم [`X`](./x/) و [`Y`](./y/) مضبوطة على الصفر. |
| [IsEmpty](../../aspose.psd/pointf/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا `PointF` فارغًا. |
| [X](../../aspose.psd/pointf/x/) { get; set; } | يحصل أو يضبط الإحداثي السيني لهذا `PointF`. |
| [Y](../../aspose.psd/pointf/y/) { get; set; } | يحصل أو يضبط الإحداثي الصادي لهذا `PointF`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Add](../../aspose.psd/pointf/add/#add)(PointF, Size) | ينقل `PointF` المعطى بمقدار [`Size`](../size/) المحدد. |
| static [Add](../../aspose.psd/pointf/add/#add_1)(PointF, SizeF) | ينقل `PointF` المعطى بمقدار [`SizeF`](../sizef/) المحدد. |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract)(PointF, Size) | ينقل `PointF` بالسالب لحجم محدد. |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract_1)(PointF, SizeF) | ينقل `PointF` بالسالب لحجم محدد. |
| override [Equals](../../aspose.psd/pointf/equals/)(object) | يحدد ما إذا كان هذا `PointF` يحتوي على نفس الإحداثيات كما في الكائن المحدد. |
| override [GetHashCode](../../aspose.psd/pointf/gethashcode/)() | يرجع رمز تجزئة لبنية `PointF` هذه. |
| override [ToString](../../aspose.psd/pointf/tostring/)() | يحوّل هذا `PointF` إلى سلسلة قابلة للقراءة من قبل الإنسان. |
| [operator +](../../aspose.psd/pointf/op_addition/#op_addition) | ينقل `PointF` بمقدار [`Size`](../size/) معطى. (عاملان) |
| [operator ==](../../aspose.psd/pointf/op_equality/) | يقارن بين بنيتين `PointF`. النتيجة تحدد ما إذا كانت قيم خصائص [`X`](./x/) و [`Y`](./y/) للبنيتين `PointF` متساوية. |
| [operator !=](../../aspose.psd/pointf/op_inequality/) | يحدد ما إذا كانت إحداثيات النقاط المحددة غير متساوية. |
| [operator -](../../aspose.psd/pointf/op_subtraction/#op_subtraction) | ينقل `PointF` بالسالب لمقدار [`Size`](../size/) معطى. (عاملان) |

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


