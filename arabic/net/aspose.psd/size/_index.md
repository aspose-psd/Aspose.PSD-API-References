---
title: Struct Size
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Size هيكل. يمثل الحجم .
type: docs
weight: 5550
url: /ar/net/aspose.psd/size/
---
## Size structure

يمثل الحجم .

```csharp
public struct Size
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Size](size/#constructor)(Point) | يقوم بتهيئة مثيل جديد لملف`Size` هيكل من المحدد[`Point`](../point/) . |
| [Size](size/#constructor_1)(int, int) | يقوم بتهيئة مثيل جديد لملف`Size` هيكل من الأبعاد المحددة. |

## الخصائص

| اسم | وصف |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | يحصل على مثيل جديد لملف`Size` هيكل لديه[`Width`](./width/) و[`Height`](./height/) تم ضبط القيم على الصفر. |
| [Height](../../aspose.psd/size/height/) { get; set; } | الحصول على أو تحديد المكون الرأسي لهذا`Size` . |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا`Size` يبلغ عرضه وارتفاعه 0. |
| [Width](../../aspose.psd/size/width/) { get; set; } | الحصول على أو تحديد المكون الأفقي لهذا`Size` . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | إضافة عرض وارتفاع واحد`Size` هيكل لعرض وارتفاع آخر`Size`هيكل . |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | تحويل المحدد[`SizeF`](../sizef/) هيكل ل`Size` عن طريق تقريب قيم`Size` بنية لقيم الأعداد الصحيحة الأعلى التالية. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | تحويل المحدد[`SizeF`](../sizef/) هيكل ل`Size` عن طريق تقريب قيم[`SizeF`](../sizef/) بنية لأقرب قيم عدد صحيح. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | طرح عرض وارتفاع واحد`Size` هيكل من عرض وارتفاع آخر`Size`هيكل . |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | تحويل المحدد[`SizeF`](../sizef/) هيكل ل`Size` هيكل عن طريق اقتطاع قيم[`SizeF`](../sizef/) هيكل لقيم الأعداد الصحيحة التالية. |
| override [Equals](../../aspose.psd/size/equals/)(object) | اختبارات لمعرفة ما إذا كان الكائن المحدد بتنسيق`Size` بنفس أبعاد هذا`Size` . |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | إرجاع رمز تجزئة لهذا الغرض`Size`هيكل . |
| override [ToString](../../aspose.psd/size/tostring/)() | لإنشاء سلسلة يمكن للبشر قراءتها تمثل هذا`Size` . |
| [operator +](../../aspose.psd/size/op_addition/) | إضافة عرض وارتفاع واحد`Size` هيكل لعرض وارتفاع آخر`Size`هيكل . |
| [operator ==](../../aspose.psd/size/op_equality/) | اختبار ما إذا كان اثنان`Size` الهياكل متساوية. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | تحويل المحدد`Size` إلى أ[`Point`](../point/) . |
| [implicit operator](../../aspose.psd/size/op_implicit/) | تحويل المحدد`Size` إلى أ[`SizeF`](../sizef/) . |
| [operator !=](../../aspose.psd/size/op_inequality/) | اختبار ما إذا كان اثنان`Size` الهياكل مختلفة. |
| [operator -](../../aspose.psd/size/op_subtraction/) | طرح عرض وارتفاع واحد`Size` هيكل من عرض وارتفاع آخر`Size`هيكل . |

### أنظر أيضا

* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


