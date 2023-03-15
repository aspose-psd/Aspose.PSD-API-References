---
title: Class StringFormat
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.StringFormat فصل. يحتوي على معلومات تخطيط النص مثل المحاذاة والاتجاه وعلامات الجدولة معالجات العرض مثل إدراج القطع واستبدال الأرقام الوطنية وميزات OpenType. لا يمكن توريث هذه الفئة.
type: docs
weight: 5670
url: /ar/net/aspose.psd/stringformat/
---
## StringFormat class

يحتوي على معلومات تخطيط النص (مثل المحاذاة والاتجاه وعلامات الجدولة) معالجات العرض (مثل إدراج القطع واستبدال الأرقام الوطنية) وميزات OpenType. لا يمكن توريث هذه الفئة.

```csharp
public sealed class StringFormat : DisposableObject
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | يقوم بتهيئة ملف`StringFormat` الكائن . |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | يقوم بتهيئة ملف`StringFormat` كائن من المحدد الموجود`StringFormat` الكائن . |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | يقوم بتهيئة ملف`StringFormat` كائن مع المحدد[`StringFormatFlags`](../stringformatflags/) التعداد واللغة. |

## الخصائص

| اسم | وصف |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | يحصل على افتراضي عام`StringFormat` الكائن . |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | يحصل على طباعة عامة`StringFormat` الكائن . |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | الحصول على معلومات محاذاة النص على المستوى العمودي أو تعيينها. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | الحصول على أو تعيين اللغة المستخدمة عند استبدال الأرقام المحلية بالأرقام الغربية. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | الحصول على أو تعيين الطريقة التي سيتم استخدامها لاستبدال الأرقام. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | الحصول على عدد المسافات بين بداية سطر من النص وعلامة الجدولة الأولى. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | يحصل أو يحدد أ[`StringFormatFlags`](../stringformatflags/) التعداد الذي يحتوي على معلومات التنسيق. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | يحصل أو يحدد ملف[`HotkeyPrefix`](../hotkeyprefix/) كائن لهذا`StringFormat` الكائن . |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | الحصول على محاذاة الخط على المستوى الأفقي أو تعيينها. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | الحصول على صفيف من المسافات بين علامات الجدولة في الوحدات المحددة بواسطة[`PageUnit`](../graphics/pageunit/) الملكية . |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | يحصل أو يحدد ملف[`StringTrimming`](../stringtrimming/) تعداد لهذا`StringFormat` الكائن . |

## طُرق

| اسم | وصف |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | لإنشاء نسخة عميقة من هذا`StringFormat` الكائن . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | التخلص من المثيل الحالي. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | تعيين علامات الجدولة لهذا الغرض`StringFormat` الكائن . |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | يحول هذا`StringFormat` كائن لسلسلة يمكن للبشر قراءتها . |

### أنظر أيضا

* class [DisposableObject](../disposableobject/)
* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


