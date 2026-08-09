---
title: "هيكل Rectangle"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "بنية Aspose.PSD.Rectangle. تخزن مجموعة من أربعة أعداد صحيحة تمثل الموقع والحجم لمستطيل."
type: docs
weight: 5840
url: /ar/net/aspose.psd/rectangle/
---
{{< psd/tize >}}
## Rectangle structure

يخزن مجموعة من أربعة أعداد صحيحة تمثل موقع وحجم المستطيل.

```csharp
public struct Rectangle
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | يُهيئ نسخة جديدة من بنية `Rectangle` بالموقع والحجم المحددين. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | يُهيئ نسخة جديدة من بنية `Rectangle` بالموقع والحجم المحددين. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | يحصل على نسخة جديدة من بنية `Rectangle` التي لديها قيم [`X`](./x/)، [`Y`](./y/)، [`Width`](./width/) و [`Height`](./height/) مضبوطة على الصفر. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | يحصل أو يضبط الإحداثي الصادي الذي هو مجموع قيم خصائص [`Y`](./y/) و [`Height`](./height/) لهذه بنية `Rectangle`. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | يحصل أو يضبط ارتفاع هذه البنية `Rectangle`. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت جميع الخصائص الرقمية لهذه `Rectangle` لها قيم صفر. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | يحصل أو يضبط الإحداثي السيني للحافة اليسرى لهذه بنية `Rectangle`. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | يحصل أو يضبط إحداثيات الزاوية العليا اليسرى لهذه بنية `Rectangle`. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | يحصل أو يضبط الإحداثي السيني الذي هو مجموع قيم خصائص [`X`](./x/) و [`Width`](./width/) لهذه بنية `Rectangle`. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | يحصل أو يضبط حجم هذه `Rectangle`. |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | يحصل أو يعيّن إحداثي y للحافة العلوية لهذا الهيكل `Rectangle`. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | يحصل أو يعيّن عرض هذا الهيكل `Rectangle`. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | يحصل أو يعيّن إحداثي x للزاوية العلوية اليسرى لهذا الهيكل `Rectangle`. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | يحصل أو يعيّن إحداثي y للزاوية العلوية اليسرى لهذا الهيكل `Rectangle`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | يحوّل الهيكل [`RectangleF`](../rectanglef/) المحدد إلى هيكل `Rectangle` عن طريق تقريب قيم [`RectangleF`](../rectanglef/) إلى أقرب قيمة صحيحة أعلى. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | ينشئ هيكل `Rectangle` بالمواقع المحددة للحواف. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | ينشئ `Rectangle` جديد من نقطتين محددتين. ستكون العمودان الرأسيان للـ `Rectangle` المُنشأ مساويين للنقطتين *point1* و *point2*. عادةً ما تكون هاتان النقطتان الرؤوس المتقابلة. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | ينشئ ويعيد نسخة مُوسّعة من الهيكل `Rectangle` المحدد. تُوسّع النسخة بالمقدار المحدد. يظل الهيكل `Rectangle` الأصلي دون تعديل. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | يعيد هيكل `Rectangle` ثالث يمثل تقاطع هيكلين `Rectangle` الآخرين. إذا لم يكن هناك تقاطع، يتم إرجاع `Rectangle` فارغ. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | يحوّل [`RectangleF`](../rectanglef/) المحدد إلى `Rectangle` عن طريق تقريب قيم [`RectangleF`](../rectanglef/) إلى أقرب قيمة صحيحة. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | يحوّل [`RectangleF`](../rectanglef/) المحدد إلى `Rectangle` عن طريق حذف الجزء العشري من قيم [`RectangleF`](../rectanglef/). |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | يحصل على هيكل `Rectangle` يحتوي على اتحاد هيكلين `Rectangle`. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل `Rectangle`. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها *rect* موجودة بالكامل داخل هذا الهيكل `Rectangle`. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل `Rectangle`. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | يفحص ما إذا كان *obj* هيكل `Rectangle` بنفس الموقع والحجم لهذا الهيكل `Rectangle`. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | يعيد رمز التجزئة لهذا الهيكل `Rectangle`. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | يوسّع هذا الـ `Rectangle` بالمقدار المحدد. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | يوسّع هذا الـ `Rectangle` بالمقدار المحدد. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | يستبدل هذا الـ `Rectangle` بتقاطع نفسه والـ `Rectangle` المحدد. |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | يحدد ما إذا كان هذا المستطيل يتقاطع مع *rect*. |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | يُعَدِّل المستطيل بجعل عرضه وارتفاعه إيجابيين، واليسار أصغر من اليمين، والعلو أصغر من الأسفل. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | يحوّل خصائص هذا الـ `Rectangle` إلى سلسلة قابلة للقراءة من قبل الإنسان. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | يفحص ما إذا كان هيكلا `Rectangle` متساويين في الموقع والحجم. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | يفحص ما إذا كان هيكلا `Rectangle` يختلفان في الموقع أو الحجم. |

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


