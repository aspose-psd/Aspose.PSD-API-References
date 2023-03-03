---
title: Struct Rectangle
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Rectangle هيكل. يخزن مجموعة من أربعة أعداد صحيحة تمثل موقع وحجم المستطيل.
type: docs
weight: 5340
url: /ar/net/aspose.psd/rectangle/
---
## Rectangle structure

يخزن مجموعة من أربعة أعداد صحيحة تمثل موقع وحجم المستطيل.

```csharp
public struct Rectangle
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | يقوم بتهيئة مثيل جديد لملف`Rectangle` هيكل بالموقع والحجم المحددين. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | يقوم بتهيئة مثيل جديد لملف`Rectangle` هيكل بالموقع والحجم المحددين. |

## الخصائص

| اسم | وصف |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | يحصل على مثيل جديد لملف`Rectangle` هيكل لديه[`X`](./x/) و[`Y`](./y/) و[`Width`](./width/) و[`Height`](./height/) تم ضبط القيم على الصفر. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | الحصول على أو تحديد إحداثي ص الذي يمثل مجموع[`Y`](./y/) و[`Height`](./height/) قيم خاصية هذا`Rectangle`هيكل . |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | الحصول على أو تحديد ارتفاع هذا`Rectangle`هيكل . |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت جميع الخصائص الرقمية لهذا`Rectangle` لها قيم صفرية . |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | الحصول على أو تحديد إحداثيات x للحافة اليسرى لهذا`Rectangle`هيكل . |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | الحصول على إحداثيات الزاوية اليسرى العلوية أو تحديدها`Rectangle`هيكل . |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | الحصول على أو تحديد الإحداثي x الذي يمثل مجموع[`X`](./x/) و[`Width`](./width/) قيم خاصية هذا`Rectangle`هيكل . |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | الحصول على أو تحديد حجم هذا`Rectangle` . |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | الحصول على أو تحديد إحداثيات y للحافة العلوية لهذا`Rectangle`هيكل . |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | الحصول على أو تحديد عرض هذا`Rectangle`هيكل . |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | الحصول على أو تحديد إحداثيات x للركن الأيسر العلوي لهذا`Rectangle`هيكل . |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | الحصول على أو تحديد إحداثيات y للركن الأيسر العلوي لهذا`Rectangle`هيكل . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | تحويل المحدد[`RectangleF`](../rectanglef/) هيكل ل`Rectangle` هيكل عن طريق تقريب[`RectangleF`](../rectanglef/) القيم إلى قيم الأعداد الصحيحة الأعلى التالية. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | ينشئ ملف`Rectangle` هيكل مع مواقع الحافة المحددة. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | ينشئ ملفًا جديدًا`Rectangle` من نقطتين محددتين. عمودين من خلق`Rectangle` سوف تكون مساوية لتمريرها*point1* و*point2* . ستكون هذه عادةً الرؤوس المعاكسة. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | إنشاء وإرجاع نسخة مضخمة من المحدد`Rectangle`بناء. يتم تضخيم النسخة بالمبلغ المحدد. الأصلي`Rectangle` تظل البنية غير معدلة. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | إرجاع ثلث`Rectangle` الهيكل الذي يمثل تقاطع اثنين آخرين`Rectangle` الهياكل. إذا لم يكن هناك تقاطع ، فارغ`Rectangle` تم إرجاعه . |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | تحويل المحدد[`RectangleF`](../rectanglef/) إلى أ`Rectangle` عن طريق تقريب[`RectangleF`](../rectanglef/) القيم لأقرب قيم عدد صحيح. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | تحويل المحدد[`RectangleF`](../rectanglef/) إلى أ`Rectangle` عن طريق اقتطاع[`RectangleF`](../rectanglef/) القيم . |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | يحصل على أ`Rectangle` هيكل يحتوي على اتحاد اثنين`Rectangle` الهياكل . |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | لتحديد ما إذا كانت النقطة المحددة متضمنة في هذا`Rectangle`هيكل . |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | لتحديد ما إذا كانت المنطقة المستطيلة ممثلة بـ*rect* موجود بالكامل في هذا`Rectangle`هيكل . |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | لتحديد ما إذا كانت النقطة المحددة متضمنة في هذا`Rectangle`هيكل . |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | اختبارات سواء*obj* هو`Rectangle`هيكل مع نفس الموقع والحجم من هذا`Rectangle`هيكل . |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | إرجاع كود التجزئة لهذا`Rectangle`هيكل . |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | ينفخ هذا`Rectangle`بالمبلغ المحدد. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | ينفخ هذا`Rectangle`بالمبلغ المحدد. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | يستبدل هذا`Rectangle` مع تقاطع نفسها والمحددة`Rectangle` . |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | لتحديد ما إذا كان هذا المستطيل يتقاطع مع*rect* . |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | تسوية المستطيل بجعل عرضه وارتفاعه موجبين ، اليسار أقل من اليمين والجزء العلوي أقل من الأسفل . |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | تحويل سمات هذا`Rectangle` لسلسلة يمكن للبشر قراءتها. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | اختبار ما إذا كان اثنان`Rectangle` الهياكل لها موقع وحجم متساويين. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | اختبار ما إذا كان اثنان`Rectangle` تختلف الهياكل في الموقع أو الحجم. |

### أنظر أيضا

* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


