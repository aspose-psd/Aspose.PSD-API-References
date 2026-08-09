---
title: "فئة Region"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.Region. تصف داخل الشكل الرسومي المكوّن من مستطيلات ومسارات. لا يمكن وراثة هذه الفئة."
type: docs
weight: 5860
url: /ar/net/aspose.psd/region/
---
{{< psd/tize >}}
## Region class

يصف داخل الشكل الرسومي المكوّن من مستطيلات ومسارات. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class Region
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Region](region/#constructor)() | ينشئ `Region` جديدًا. |
| [Region](region/#constructor_1)(GraphicsPath) | ينشئ `Region` جديدًا بالـ[`GraphicsPath`](../graphicspath/) المحدد. |
| [Region](region/#constructor_2)(Rectangle) | ينشئ `Region` جديدًا من بنية [`Rectangle`](../rectangle/) المحددة. |
| [Region](region/#constructor_3)(RectangleF) | يُنشئ `Region` جديدًا من البنية المحددة [`RectangleF`](../rectanglef/). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | يُحدّث هذا `Region` ليحتوي على الجزء من [`GraphicsPath`](../graphicspath/) المحدد الذي لا يتقاطع مع هذا `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | يُحدّث هذا `Region` ليحتوي على الجزء من البنية المحددة [`Rectangle`](../rectangle/) الذي لا يتقاطع مع هذا `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | يُحدّث هذا `Region` ليحتوي على الجزء من البنية المحددة [`RectangleF`](../rectanglef/) الذي لا يتقاطع مع هذا `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | يُحدّث هذا `Region` ليحتوي على الجزء من `Region` المحدد الذي لا يتقاطع مع هذا `Region`. |
| [DeepClone](../../aspose.psd/region/deepclone/)() | ينشئ نسخة عميقة دقيقة من هذا `Region`. |
| override [Equals](../../aspose.psd/region/equals/#equals_1)(object) | تحقق مما إذا كانت الكائنات متساوية. |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | يفحص ما إذا كان `Region` المحدد مطابقًا لهذا `Region` على سطح الرسم المحدد. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | يُحدّث هذا `Region` ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع [`GraphicsPath`](../graphicspath/) المحدد. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | يُحدّث هذا `Region` ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع البنية المحددة [`Rectangle`](../rectangle/). |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | يُحدّث هذا `Region` ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع البنية المحددة [`RectangleF`](../rectanglef/). |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | يُحدّث هذا `Region` ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع `Region` المحدد. |
| override [GetHashCode](../../aspose.psd/region/gethashcode/)() | احصل على قيمة التجزئة للكائن الحالي. |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | يُحدّث هذا `Region` إلى تقاطعه مع [`GraphicsPath`](../graphicspath/) المحدد. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | يُحدّث هذا `Region` إلى تقاطعه مع البنية المحددة [`Rectangle`](../rectangle/). |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | يُحدّث هذا `Region` إلى تقاطعه مع البنية المحددة [`RectangleF`](../rectanglef/). |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | يُحدّث هذا `Region` إلى تقاطعه مع `Region` المحدد. |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | يفحص ما إذا كان لهذا `Region` داخل فارغ على سطح الرسم المحدد. |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | يفحص ما إذا كان لهذا `Region` داخل لا نهائي على سطح الرسم المحدد. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | يفحص ما إذا كانت البنية المحددة [`Point`](../point/) موجودة داخل هذا `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | يفحص ما إذا كانت البنية المحددة [`PointF`](../pointf/) موجودة داخل هذا `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | يفحص ما إذا كان أي جزء من البنية المحددة [`Rectangle`](../rectangle/) موجودًا داخل هذا `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | يفحص ما إذا كان أي جزء من البنية المحددة [`RectangleF`](../rectanglef/) موجودًا داخل هذا `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | يفحص ما إذا كانت البنية المحددة [`Point`](../point/) موجودة داخل هذا `Region` عند الرسم باستخدام [`Graphics`](../graphics/) المحدد. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | يفحص ما إذا كانت البنية المحددة [`PointF`](../pointf/) موجودة داخل هذا `Region` عند الرسم باستخدام [`Graphics`](../graphics/) المحدد. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | يفحص ما إذا كان أي جزء من البنية المحددة [`Rectangle`](../rectangle/) موجودًا داخل هذا `Region` عند الرسم باستخدام [`Graphics`](../graphics/) المحدد. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | يختبر ما إذا كان أي جزء من بنية [`RectangleF`](../rectanglef/) المحددة موجودًا داخل هذه `Region` عند رسمها باستخدام الـ[`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | يختبر ما إذا كانت النقطة المحددة موجودة داخل هذه `Region` عند رسمها باستخدام الـ[`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | يختبر ما إذا كانت النقطة المحددة موجودة داخل كائن `Region` هذا عند رسمه باستخدام كائن الـ[`Graphics`](../graphics/) المحدد. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | يختبر ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذه `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | يختبر ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذه `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | يختبر ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذه `Region` عند رسمها باستخدام الـ[`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | يختبر ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذه `Region` عند رسمها باستخدام الـ[`Graphics`](../graphics/). |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | يُهيئ هذه `Region` لتكون داخلية فارغة. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | يُهيئ كائن `Region` هذا لتكون داخلية لا نهائية. |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | يحوِّل هذه `Region` باستخدام الـ[`Matrix`](../matrix/) المحدد. |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | يُضيف إزاحة إلى إحداثيات هذه `Region` بالمقدار المحدد. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | يُضيف إزاحة إلى إحداثيات هذه `Region` بالمقدار المحدد. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | يُحدّث هذه `Region` لتصبح اتحادًا بينها وبين الـ[`GraphicsPath`](../graphicspath/) المحدد. |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | يُحدّث هذه `Region` لتصبح اتحادًا بينها وبين بنية الـ[`Rectangle`](../rectangle/) المحددة. |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | يُحدّث هذه `Region` لتصبح اتحادًا بينها وبين بنية الـ[`RectangleF`](../rectanglef/) المحددة. |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | يُحدّث هذه `Region` لتصبح اتحادًا بينها وبين الـ`Region` المحدد. |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | يُحدّث هذه `Region` لتصبح اتحادًا مطروحًا منه تقاطعها مع الـ[`GraphicsPath`](../graphicspath/) المحدد. |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | يُحدّث هذه `Region` لتصبح اتحادًا مطروحًا منه تقاطعها مع بنية الـ[`Rectangle`](../rectangle/) المحددة. |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | يُحدّث هذه `Region` لتصبح اتحادًا مطروحًا منه تقاطعها مع بنية الـ[`RectangleF`](../rectanglef/) المحددة. |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | يُحدّث هذه `Region` لتصبح اتحادًا مطروحًا منه تقاطعها مع الـ`Region` المحدد. |

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


