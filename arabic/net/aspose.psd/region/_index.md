---
title: Class Region
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Region فصل. يصف الجزء الداخلي لشكل رسومي مكون من مستطيلات ومسارات. لا يمكن توريث هذه الفئة.
type: docs
weight: 5360
url: /ar/net/aspose.psd/region/
---
## Region class

يصف الجزء الداخلي لشكل رسومي مكون من مستطيلات ومسارات. لا يمكن توريث هذه الفئة.

```csharp
public sealed class Region
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Region](region/#constructor)() | يقوم بتهيئة ملف`Region` . |
| [Region](region/#constructor_1)(GraphicsPath) | يقوم بتهيئة ملف`Region` مع المحدد[`GraphicsPath`](../graphicspath/) . |
| [Region](region/#constructor_2)(Rectangle) | يقوم بتهيئة ملف`Region` من المحدد[`Rectangle`](../rectangle/)هيكل . |
| [Region](region/#constructor_3)(RectangleF) | يقوم بتهيئة ملف`Region` من المحدد[`RectangleF`](../rectanglef/)هيكل . |

## طُرق

| اسم | وصف |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | يقوم بتحديث هذا`Region` لاحتواء الجزء المحدد[`GraphicsPath`](../graphicspath/) هذا لا يتقاطع مع هذا`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | يقوم بتحديث هذا`Region` لاحتواء الجزء المحدد[`Rectangle`](../rectangle/) هيكل لا يتقاطع مع هذا`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | يقوم بتحديث هذا`Region` لاحتواء الجزء المحدد[`RectangleF`](../rectanglef/) هيكل لا يتقاطع مع هذا`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | يقوم بتحديث هذا`Region` لاحتواء الجزء المحدد`Region` هذا لا يتقاطع مع هذا`Region` . |
| [DeepClone](../../aspose.psd/region/deepclone/)() | لإنشاء نسخة مطابقة عميقة من هذا`Region` . |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | تختبر ما إذا كان الملف المحدد`Region` مطابق لهذا`Region` على سطح الرسم المحدد. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | يقوم بتحديث هذا`Region` لتحتوي فقط على جزء من الجزء الداخلي لا يتقاطع مع المحدد[`GraphicsPath`](../graphicspath/) . |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | يقوم بتحديث هذا`Region` لتحتوي فقط على جزء من الجزء الداخلي لا يتقاطع مع المحدد[`Rectangle`](../rectangle/)هيكل . |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | يقوم بتحديث هذا`Region` لتحتوي فقط على جزء من الجزء الداخلي لا يتقاطع مع المحدد[`RectangleF`](../rectanglef/)هيكل . |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | يقوم بتحديث هذا`Region` لتحتوي فقط على جزء من الجزء الداخلي لا يتقاطع مع المحدد`Region` . |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | يقوم بتحديث هذا`Region` إلى تقاطع نفسه مع المحدد[`GraphicsPath`](../graphicspath/) . |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | يقوم بتحديث هذا`Region` إلى تقاطع نفسه مع المحدد[`Rectangle`](../rectangle/)هيكل . |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | يقوم بتحديث هذا`Region` إلى تقاطع نفسه مع المحدد[`RectangleF`](../rectanglef/)هيكل . |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | يقوم بتحديث هذا`Region` إلى تقاطع نفسه مع المحدد`Region` . |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | اختبارات ما إذا كان هذا`Region` يحتوي على مساحة داخلية فارغة على سطح الرسم المحدد. |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | اختبارات ما إذا كان هذا`Region` له مساحة داخلية لا نهائية على سطح الرسم المحدد. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | تختبر ما إذا كان الملف المحدد[`Point`](../point/) هيكل وارد في هذا`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | تختبر ما إذا كان الملف المحدد[`PointF`](../pointf/) هيكل وارد في هذا`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | اختبارات ما إذا كان أي جزء من المحدد[`Rectangle`](../rectangle/) هيكل وارد في هذا`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | اختبارات ما إذا كان أي جزء من المحدد[`RectangleF`](../rectanglef/) هيكل وارد في هذا`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | يختبر ما إذا كانت النقطة المحددة متضمنة في هذا`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | تختبر ما إذا كان الملف المحدد[`Point`](../point/) هيكل وارد في هذا`Region` عند رسمها باستخدام المحدد[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | تختبر ما إذا كان الملف المحدد[`PointF`](../pointf/) هيكل وارد في هذا`Region` عند رسمها باستخدام المحدد[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | اختبارات ما إذا كان أي جزء من المحدد[`Rectangle`](../rectangle/) هيكل وارد في هذا`Region` عند رسمها باستخدام المحدد[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | اختبارات ما إذا كان أي جزء من المحدد[`RectangleF`](../rectanglef/) هيكل وارد في هذا`Region` عند رسمها باستخدام المحدد[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | يختبر ما إذا كانت النقطة المحددة متضمنة في هذا`Region` عند رسمها باستخدام المحدد[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | يختبر ما إذا كانت النقطة المحددة متضمنة في هذا`Region` الكائن عند رسمه باستخدام المحدد[`Graphics`](../graphics/) الكائن . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | يختبر ما إذا كان أي جزء من المستطيل المحدد متضمنًا في هذا`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | يختبر ما إذا كان أي جزء من المستطيل المحدد متضمنًا في هذا`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | يختبر ما إذا كان أي جزء من المستطيل المحدد متضمنًا في هذا`Region` عند رسمها باستخدام المحدد[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | يختبر ما إذا كان أي جزء من المستطيل المحدد متضمنًا في هذا`Region` عند رسمها باستخدام المحدد[`Graphics`](../graphics/) . |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | يقوم بتهيئة هذا`Region` إلى مساحة داخلية فارغة. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | يقوم بتهيئة هذا`Region` كائن داخلي لانهائي . |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | يحول هذا`Region` حسب المحدد[`Matrix`](../matrix/) . |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | يزيح إحداثيات هذا`Region`بالمبلغ المحدد. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | يزيح إحداثيات هذا`Region`بالمبلغ المحدد. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | يقوم بتحديث هذا`Region` لاتحاد نفسه والمحددة[`GraphicsPath`](../graphicspath/) . |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | يقوم بتحديث هذا`Region` لاتحاد نفسه والمحددة[`Rectangle`](../rectangle/)هيكل . |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | يقوم بتحديث هذا`Region` لاتحاد نفسه والمحددة[`RectangleF`](../rectanglef/)هيكل . |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | يقوم بتحديث هذا`Region` لاتحاد نفسه والمحددة`Region` . |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | يقوم بتحديث هذا`Region` إلى الاتحاد مطروحًا منه تقاطع نفسه مع المحدد[`GraphicsPath`](../graphicspath/) . |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | يقوم بتحديث هذا`Region` إلى الاتحاد مطروحًا منه تقاطع نفسه مع المحدد[`Rectangle`](../rectangle/)هيكل . |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | يقوم بتحديث هذا`Region` إلى الاتحاد مطروحًا منه تقاطع نفسه مع المحدد[`RectangleF`](../rectanglef/)هيكل . |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | يقوم بتحديث هذا`Region` إلى الاتحاد مطروحًا منه تقاطع نفسه مع المحدد`Region` . |

### أنظر أيضا

* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


