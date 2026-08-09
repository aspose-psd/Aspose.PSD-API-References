---
title: "فئة StringFormat"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.StringFormat. تُغلف معلومات تخطيط النص مثل اتجاه المحاذاة وإيقافات الجدولة وتعديلات العرض مثل إدراج الثلاث نقاط واستبدال الأرقام الوطنية وميزات OpenType. لا يمكن وراثة هذه الفئة."
type: docs
weight: 6170
url: /ar/net/aspose.psd/stringformat/
---
{{< psd/tize >}}
## StringFormat class

يحتوي على معلومات تخطيط النص (مثل المحاذاة، الاتجاه وإيقافات الجدولة) وتعديلات العرض (مثل إدراج الحذف والاستبدال الرقمي الوطني) وميزات OpenType. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class StringFormat : DisposableObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | ينشئ كائن `StringFormat` جديد. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | ينشئ كائن `StringFormat` جديد من كائن `StringFormat` الموجود المحدد. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | ينشئ كائن `StringFormat` جديد باستخدام تعداد [`StringFormatFlags`](../stringformatflags/) المحدد واللغة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | يحصل على كائن `StringFormat` افتراضي عام. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | يحصل على كائن `StringFormat` طباعي عام. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | يحصل أو يضبط معلومات محاذاة النص على المستوى العمودي. |
| [CustomCharIdent](../../aspose.psd/stringformat/customcharident/) { get; set; } | يحصل أو يضبط معرف الحرف المخصص. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | يحصل أو يضبط اللغة المستخدمة عندما يتم استبدال الأرقام المحلية بالأرقام الغربية. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | يحصل أو يضبط الطريقة المستخدمة لاستبدال الأرقام. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | يحصل على عدد المسافات بين بداية سطر النص وأول موضع تبويب. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | يحصل أو يضبط تعداد [`StringFormatFlags`](../stringformatflags/) الذي يحتوي على معلومات التنسيق. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | يحصل أو يضبط كائن [`HotkeyPrefix`](../hotkeyprefix/) لهذا الكائن `StringFormat`. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | يحصل أو يضبط محاذاة السطر على المستوى الأفقي. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | يحصل على مصفوفة من المسافات بين مواضع التبويب بالوحدات المحددة بواسطة الخاصية [`PageUnit`](../graphics/pageunit/). |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | يحصل أو يضبط تعداد [`StringTrimming`](../stringtrimming/) لهذا الكائن `StringFormat`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | ينشئ نسخة عميقة من هذا الكائن `StringFormat`. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| override [Equals](../../aspose.psd/stringformat/equals/)(object) | تحقق مما إذا كانت الكائنات متساوية. |
| override [GetHashCode](../../aspose.psd/stringformat/gethashcode/)() | احصل على قيمة التجزئة للكائن الحالي. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | يضبط مواضع التبويب لهذا الكائن `StringFormat`. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | يحول هذا الكائن `StringFormat` إلى سلسلة قابلة للقراءة البشرية. |

### انظر أيضًا

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


