---
title: "الهيكل RectangleF"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الهيكل Aspose.PSD.RectangleF. يخزن مجموعة من أربعة أعداد ذات نقطة عائمة تمثل موقع وحجم المستطيل."
type: docs
weight: 5850
url: /ar/net/aspose.psd/rectanglef/
---
{{< psd/tize >}}
## RectangleF structure

يخزن مجموعة من أربعة أعداد عائمة تمثل موقع وحجم المستطيل.

```csharp
public struct RectangleF
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | يُهيئ نسخة جديدة من هيكل `RectangleF` بالموقع والحجم المحددين. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | يُهيئ نسخة جديدة من هيكل `RectangleF` بالموقع والحجم المحددين. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | يحصل على نسخة جديدة من هيكل `RectangleF` التي تحتوي على قيم [`X`](./x/), [`Y`](./y/), [`Width`](./width/) و[`Height`](./height/) مضبوطة على الصفر. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | يحصل أو يعيّن إحداثي y الذي هو مجموع [`Y`](./y/) و [`Height`](./height/) لهذا الهيكل `RectangleF`. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | يحصل أو يعيّن ارتفاع هذا الهيكل `RectangleF`. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت خاصية [`Width`](./width/) أو [`Height`](./height/) لهذا `RectangleF` لها قيمة صفرًا. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | يحصل أو يعيّن إحداثي x للحافة اليسرى لهذا الهيكل `RectangleF`. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | يحصل أو يعيّن إحداثيات الزاوية العلوية اليسرى لهذا الهيكل `RectangleF`. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | يحصل أو يعيّن إحداثي x الذي هو مجموع [`X`](./x/) و [`Width`](./width/) لهذا الهيكل `RectangleF`. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | يحصل أو يعيّن حجم هذا `RectangleF`. |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | يحصل أو يعيّن إحداثي y للحافة العلوية لهذا الهيكل `RectangleF`. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | يحصل أو يعيّن عرض هذا الهيكل `RectangleF`. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | يحصل أو يعيّن إحداثي x للزاوية العلوية اليسرى لهذا الهيكل `RectangleF`. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | يحصل أو يعيّن إحداثي y للزاوية العلوية اليسرى لهذا الهيكل `RectangleF`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | ينشئ هيكل `RectangleF` مع الزاوية العلوية اليسرى والزاوية السفلية اليمنى في المواقع المحددة. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | ينشئ [`Rectangle`](../rectangle/) جديدًا من نقطتين محددتين. سيكون رُؤوس الـ [`Rectangle`](../rectangle/) المُنشأ مساوية للنقطتين *point1* و *point2* الممرّتين. عادةً ما تكون هذه الرؤوس هي القمم المتقابلة. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | ينشئ ويعيد نسخة مُوسّعة من الهيكل `RectangleF` المحدد. تُوسّع النسخة بالمقدار المحدد. يظل المستطيل الأصلي دون تعديل. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | يعيد هيكل `RectangleF` يمثل تقاطع مستطيلين. إذا لم يكن هناك تقاطع، يتم إرجاع `RectangleF` فارغ. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | ينشئ أصغر مستطيل ثالث ممكن يمكنه احتواء المستطيلين الذين يشكلان اتحادًا. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل `RectangleF`. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها *rect* موجودة بالكامل داخل هذا الهيكل `RectangleF`. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل `RectangleF`. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | يفحص ما إذا كان *obj* هو `RectangleF` بنفس الموقع والحجم لهذا `RectangleF`. |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | يحصل على رمز التجزئة لهذا الهيكل `RectangleF`. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | يوسّع هذا `RectangleF` بالمقدار المحدد. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | يوسّع هيكل `RectangleF` هذا بالمقدار المحدد. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | يستبدل هيكل `RectangleF` هذا بتقاطع نفسه مع الهيكل `RectangleF` المحدد. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | يحدد ما إذا كان هذا المستطيل يتقاطع مع *rect*. |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | يُعَدِّل المستطيل بجعل عرضه وارتفاعه إيجابيين، واليسار أصغر من اليمين، والعلو أصغر من الأسفل. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | يحوّل خصائص هذا `RectangleF` إلى سلسلة قابلة للقراءة البشرية. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | ينفّذ العملية /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | يفحص ما إذا كان هيكلا `RectangleF` الاثنين لهما موقع وحجم متساويين. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | يحوّل الهيكل المحدد [`Rectangle`](../rectangle/) إلى هيكل `RectangleF`. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | يفحص ما إذا كان هيكلا `RectangleF` الاثنين يختلفان في الموقع أو الحجم. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | ينفّذ العملية *. |

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


