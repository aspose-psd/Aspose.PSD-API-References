---
title: Struct Point
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Point هيكل. يمثل زوجًا مرتبًا من إحداثيات x و y الصحيحة التي تحدد نقطة في مستوى ثنائي الأبعاد.
type: docs
weight: 5260
url: /ar/net/aspose.psd/point/
---
## Point structure

يمثل زوجًا مرتبًا من إحداثيات x و y الصحيحة التي تحدد نقطة في مستوى ثنائي الأبعاد.

```csharp
public struct Point
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Point](point/#constructor_1)(int) | يقوم بتهيئة مثيل جديد لملف`Point` هيكل باستخدام الإحداثيات المحددة بواسطة قيمة عدد صحيح. |
| [Point](point/#constructor)(Size) | يقوم بتهيئة مثيل جديد لملف`Point` هيكل من[`Size`](../size/)هيكل . |
| [Point](point/#constructor_2)(int, int) | يقوم بتهيئة مثيل جديد لملف`Point` هيكل مع الإحداثيات المحددة. |

## الخصائص

| اسم | وصف |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | يحصل على مثيل جديد لملف`Point` هيكل لديه[`X`](./x/) و[`Y`](./y/) تم ضبط القيم على الصفر. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا`Point` فارغ . |
| [X](../../aspose.psd/point/x/) { get; set; } | الحصول على أو تحديد إحداثيات x لهذا`Point` . |
| [Y](../../aspose.psd/point/y/) { get; set; } | الحصول على أو تحديد إحداثيات y لهذا`Point` . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | إضافة المحدد[`Size`](../size/) إلى المحدد`Point` . |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | تحويل المحدد[`PointF`](../pointf/) إلى أ`Point` عن طريق تقريب قيم[`PointF`](../pointf/) إلى قيم الأعداد الصحيحة الأعلى التالية. |
| static [Round](../../aspose.psd/point/round/)(PointF) | تحويل المحدد[`PointF`](../pointf/) إلى أ`Point` كائن عن طريق تقريب`Point` القيم لأقرب عدد صحيح. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | إرجاع نتيجة الطرح المحددة[`Size`](../size/) من المحدد`Point` . |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | تحويل المحدد[`PointF`](../pointf/) إلى أ`Point` عن طريق اقتطاع قيم`Point` . |
| override [Equals](../../aspose.psd/point/equals/)(object) | يحدد ما إذا كان هذا`Point` يحتوي على نفس الإحداثيات المحددةObject . |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | إرجاع رمز تجزئة لهذا الغرض`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | يترجم هذا`Point` حسب المحدد`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | يترجم هذا`Point`بالمبلغ المحدد. |
| override [ToString](../../aspose.psd/point/tostring/)() | يحول هذا`Point` لسلسلة يمكن للبشر قراءتها. |
| [operator +](../../aspose.psd/point/op_addition/) | يترجم أ`Point` من خلال معين[`Size`](../size/) . |
| [operator ==](../../aspose.psd/point/op_equality/) | يقارن اثنين`Point` أشياء. تحدد النتيجة ما إذا كانت قيم ملف[`X`](./x/) و[`Y`](./y/) خصائص الاثنين`Point` الكائنات متساوية . |
| [explicit operator](../../aspose.psd/point/op_explicit/) | تحويل المحدد`Point` هيكل ل[`Size`](../size/)هيكل . |
| [implicit operator](../../aspose.psd/point/op_implicit/) | تحويل المحدد`Point` هيكل ل[`PointF`](../pointf/)هيكل . |
| [operator !=](../../aspose.psd/point/op_inequality/) | يقارن اثنين`Point` أشياء. تحدد النتيجة ما إذا كانت قيم ملف[`X`](./x/) أو[`Y`](./y/) خصائص الاثنين`Point` الكائنات غير متساوية. |
| [operator -](../../aspose.psd/point/op_subtraction/) | يترجم أ`Point` من سالب معين[`Size`](../size/) . |

### أنظر أيضا

* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


