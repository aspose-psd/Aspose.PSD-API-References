---
title: "الفئة RawColor"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "Aspose.PSD.FileFormats.Psd.Core.RawColor.RawColor class. تساعد فئة Raw Color على تخزين الألوان بأي عدد قنوات وأي وضع لون وأي عمق بت. يرجى ملاحظة أن بعض الفئات الداخلية قد تواجه مشاكل في تحويل RawColor إلى تنسيقها الأصلي، لذا إذا قدمت لك الواجهة برمجة التطبيقات لون CMYK فمن الأكثر موثوقية استخدام الصيغة المقدمة. كما قد تكون هناك حالات يمكن فيها تحويل Raw Color."
type: docs
weight: 1650
url: /ar/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor class

تساعد فئة Raw Color على تخزين الألوان بأي عدد قنوات، وأي وضع لون، وأي عمق بت. يرجى ملاحظة أن بعض الفئات الداخلية قد تواجه مشكلات في تحويل RawColor إلى صيغتها الأصلية، لذا إذا قدمت لك API لون CMYK، فمن الأكثر موثوقية استخدام الصيغة المقدمة. أيضًا، قد تكون هناك بعض الحالات التي يمكن فيها تحويل Raw Color.

```csharp
public sealed class RawColor
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [RawColor](rawcolor/#constructor)(ColorComponent[]) | يُنشئ نسخة جديدة من الفئة `RawColor`. |
| [RawColor](rawcolor/#constructor_1)(PixelDataFormat, short) | يُنشئ مثيلاً جديدًا لفئة `RawColor` من تنسيق بيانات البكسل باستخدام أوضاع اللون المحددة مسبقًا |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ColorMode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/colormode/) { get; set; } | الوضع للون المتبع. |
| [Components](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/components/) { get; } | يحصل على مكونات اللون. كل مكوّن هو قناة منفصلة، وإذا كنت تستخدم نظام ألوان غير شائع، فمن الأفضل العمل مع كل قناة على حدة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/equals/)(object) | يحدد ما إذا كان الكائن المحدد يساوي هذا المثيل. |
| [GetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getasint/)() | يحصل على اللون كعدد صحيح في حال كان ذلك ممكنًا. |
| [GetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getaslong/)() | يحصل على اللون كعدد طويل في حال كان ذلك ممكنًا. |
| [GetBitDepth](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getbitdepth/)() | يحصل على عمق البت للون الخام. على سبيل المثال، لون ARGB بثمانية بتات لكل قناة/مكوّن يكون عمق بتاته 32، ولون ARGB كامل بستة عشر بت لكل قناة/مكوّن يكون عمق بتاته 64. يتم تجميع عمق البت من مجموع أعماق بتات القنوات. هذا ممكن إذا كانت القنوات المختلفة لها أعماق بت مختلفة. |
| [GetColorModeName](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getcolormodename/)() | يحصل على اسم وضع اللون. يُجمع اسم وضع اللون من أسماء القنوات/المكونات. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/gethashcode/)() | احصل على قيمة التجزئة للكائن الحالي. |
| [SetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setasint/)(int) | يضبط البيانات لجميع القنوات من معامل عدد صحيح إذا كان ذلك ممكنًا |
| [SetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setaslong/)(long) | يضبط البيانات لجميع القنوات من معامل عدد صحيح إذا كان ذلك ممكنًا |
| [operator ==](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_equality/) | ينفّذ العامل ==. |
| [operator !=](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_inequality/) | ينفّذ العامل !=. |

## أمثلة

الكود التالي يوضح دعم فئة RawColor بدلاً من بنية Color القديمة.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../)


