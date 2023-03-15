---
title: Class Font
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Font فصل. يحدد تنسيقًا معينًا للنص  بما في ذلك سمات الخط والحجم والنمط. لا يمكن توريث هذه الفئة.
type: docs
weight: 4280
url: /ar/net/aspose.psd/font/
---
## Font class

يحدد تنسيقًا معينًا للنص ، بما في ذلك سمات الخط والحجم والنمط. لا يمكن توريث هذه الفئة.

```csharp
public sealed class Font
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | يقوم بتهيئة ملف`Font` يستخدم المحدد الموجود`Font` و[`FontStyle`](../fontstyle/) التعداد . |
| [Font](font/#constructor_1)(string, float) | يقوم بتهيئة ملف`Font` باستخدام حجم محدد. تم تعيين مجموعة الأحرف علىDefault ، وحدة الرسوماتPoint ، نمط الخط إلىRegular . |
| [Font](font/#constructor_2)(string, float, FontStyle) | يقوم بتهيئة ملف`Font` باستخدام حجم وأسلوب محددين. تم تعيين مجموعة الأحرف علىDefault ، وحدة الرسوماتPoint . |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | يقوم بتهيئة ملف`Font` باستخدام حجم ووحدة محددين. تم تعيين مجموعة الأحرف علىDefault، تم تعيين النمط علىRegular . |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | يقوم بتهيئة ملف`Font` باستخدام حجم ونمط ووحدة محددة. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | يقوم بتهيئة ملف`Font` باستخدام حجم ونمط ووحدة ومجموعة أحرف محددة. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا`Font` جريئة . |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | يحصل على قيمة البايت التي تحدد مجموعة الأحرف لهذا`Font` يستخدم . |
| [Italic](../../aspose.psd/font/italic/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا`Font`مائل . |
| [Name](../../aspose.psd/font/name/) { get; } | يحصل على اسم الوجه لهذا`Font` . |
| [Size](../../aspose.psd/font/size/) { get; } | يحصل على حجم em لهذا`Font` تقاس بالوحدات المحددة بواسطة[`Unit`](./unit/) الملكية . |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا`Font` يحدد خطًا أفقيًا من خلال الخط. |
| [Style](../../aspose.psd/font/style/) { get; } | يحصل على معلومات عن النمط لهذا الغرض`Font` . |
| [Underline](../../aspose.psd/font/underline/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا`Font` مسطر . |
| [Unit](../../aspose.psd/font/unit/) { get; } | الحصول على وحدة القياس لهذا`Font` . |

## طُرق

| اسم | وصف |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | لإنشاء نسخة مطابقة عميقة من هذا`Font` . |
| override [Equals](../../aspose.psd/font/equals/)(object) | يشير إلى ما إذا كان الكائن المحدد`Font` ولها نفس قيم الخصائص مثل هذا`Font` . |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | يحصل على كود التجزئة لهذا`Font` . |
| override [ToString](../../aspose.psd/font/tostring/)() | إرجاع تمثيل سلسلة يمكن قراءته بواسطة الإنسان`Font` . |

### أمثلة

يوضح هذا المثال استخدام فئة Font و SolidBrush لرسم سلاسل على سطح الصورة. يقوم المثال بإنشاء صورة جديدة ورسم الأشكال باستخدام Figures و GraphicsPath

```csharp
[C#]

// ينشئ مثيلاً للصورة
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // يقوم بإنشاء وتهيئة مثيل لفئة الرسومات
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // مسح سطح الرسومات
    graphics.Clear(Color.Wheat);

    // ينشئ مثيلاً للخط
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    // أنشئ مثيلاً من SolidBrush باللون الأحمر
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // ارسم سلسلة
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // إنشاء خيارات التصدير.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // احفظ جميع التغييرات
    image.Save("C:\\temp\\output.gif", options);
}
```

### أنظر أيضا

* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


