---
title: Struct RectangleF
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.RectangleF هيكل. يخزن مجموعة من أربعة أرقام فاصلة عائمة تمثل موقع وحجم المستطيل.
type: docs
weight: 5350
url: /ar/net/aspose.psd/rectanglef/
---
## RectangleF structure

يخزن مجموعة من أربعة أرقام فاصلة عائمة تمثل موقع وحجم المستطيل.

```csharp
public struct RectangleF
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | يقوم بتهيئة مثيل جديد لملف`RectangleF` هيكل بالموقع والحجم المحددين. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | يقوم بتهيئة مثيل جديد لملف`RectangleF` هيكل بالموقع والحجم المحددين. |

## الخصائص

| اسم | وصف |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | يحصل على مثيل جديد لملف`RectangleF` هيكل لديه[`X`](./x/) و[`Y`](./y/) و[`Width`](./width/) و[`Height`](./height/) تم ضبط القيم على الصفر. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | الحصول على أو تحديد إحداثي ص الذي يمثل مجموع[`Y`](./y/) و[`Height`](./height/) من هذا`RectangleF`هيكل . |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | الحصول على أو تحديد ارتفاع هذا`RectangleF`هيكل . |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان ملف[`Width`](./width/) أو[`Height`](./height/) ممتلكات هذا`RectangleF` بقيمة صفر . |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | الحصول على أو تحديد إحداثيات x للحافة اليسرى لهذا`RectangleF`هيكل . |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | الحصول على إحداثيات الزاوية اليسرى العلوية أو تحديدها`RectangleF`هيكل . |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | الحصول على أو تحديد الإحداثي x الذي يمثل مجموع[`X`](./x/) و[`Width`](./width/) من هذا`RectangleF`هيكل . |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | الحصول على أو تحديد حجم هذا`RectangleF` . |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | الحصول على أو تحديد إحداثيات y للحافة العلوية لهذا`RectangleF`هيكل . |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | الحصول على أو تحديد عرض هذا`RectangleF`هيكل . |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | الحصول على أو تحديد إحداثيات x للركن الأيسر العلوي لهذا`RectangleF`هيكل . |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | الحصول على أو تحديد إحداثيات y للركن الأيسر العلوي لهذا`RectangleF`هيكل . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | ينشئ ملف`RectangleF` هيكل مع الزاوية العلوية اليسرى والزاوية اليمنى السفلية في المواقع المحددة. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | ينشئ ملفًا جديدًا[`Rectangle`](../rectangle/) من نقطتين محددتين. رأسين من المخلوقات[`Rectangle`](../rectangle/) سوف تكون مساوية لتمريرها*point1* و*point2* . ستكون هذه عادةً الرؤوس المعاكسة. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | إنشاء وإرجاع نسخة مضخمة من المحدد`RectangleF`بناء. يتم تضخيم النسخة بالمبلغ المحدد. يظل المستطيل الأصلي غير معدل. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | إرجاع أ`RectangleF` الهيكل الذي يمثل تقاطع مستطيلين. إذا لم يكن هناك تقاطع وخالٍ`RectangleF` تم إرجاعه . |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | لإنشاء أصغر مستطيل ثالث ممكن يمكن أن يحتوي على كلا المستطيلين اللذين يشكلان اتحادًا. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | لتحديد ما إذا كانت النقطة المحددة متضمنة في هذا`RectangleF`هيكل . |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | لتحديد ما إذا كانت المنطقة المستطيلة ممثلة بـ*rect* موجود بالكامل في هذا`RectangleF`هيكل . |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | لتحديد ما إذا كانت النقطة المحددة متضمنة في هذا`RectangleF`هيكل . |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | اختبارات سواء*obj* هو`RectangleF` بنفس موقع وحجم هذا`RectangleF` . |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | يحصل على كود التجزئة لهذا`RectangleF`هيكل . |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | ينفخ هذا`RectangleF`بالمبلغ المحدد. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | ينفخ هذا`RectangleF` هيكل بالمبلغ المحدد. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | يستبدل هذا`RectangleF`هيكل مع تقاطع نفسه والمحددة`RectangleF`هيكل . |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | لتحديد ما إذا كان هذا المستطيل يتقاطع مع*rect* . |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | تسوية المستطيل بجعل عرضه وارتفاعه موجبين ، اليسار أقل من اليمين والجزء العلوي أقل من الأسفل . |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | تحويل سمات هذا`RectangleF` لسلسلة يمكن للبشر قراءتها. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | ينفذ المشغل /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | اختبار ما إذا كان اثنان`RectangleF` الهياكل لها موقع وحجم متساويين. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | تحويل المحدد[`Rectangle`](../rectangle/) هيكل ل`RectangleF`هيكل . |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | اختبار ما إذا كان اثنان`RectangleF` تختلف الهياكل في الموقع أو الحجم. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | تنفيذ عامل التشغيل * . |

### أنظر أيضا

* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


