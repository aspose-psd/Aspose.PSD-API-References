---
title: Class Jpeg2000Options
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.ImageOptions.Jpeg2000Options فصل. خيارات تنسيق ملف Jpeg2000
type: docs
weight: 4830
url: /ar/net/aspose.psd.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

خيارات تنسيق ملف Jpeg2000

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Jpeg2000Options](jpeg2000options/#constructor)() | يقوم بتهيئة مثيل جديد لملف`Jpeg2000Options` فئة . |
| [Jpeg2000Options](jpeg2000options/#constructor_1)(Jpeg2000Options) | يقوم بتهيئة مثيل جديد لملف`Jpeg2000Options` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [Codec](../../aspose.psd.imageoptions/jpeg2000options/codec/) { get; set; } | الحصول على أو تعيين برنامج ترميز JPEG2000 |
| [Comments](../../aspose.psd.imageoptions/jpeg2000options/comments/) { get; set; } | الحصول على أو تعيين علامات تعليق Jpeg . |
| [CompressionRatios](../../aspose.psd.imageoptions/jpeg2000options/compressionratios/) { get; set; } | الحصول على مصفوفة نسبة الضغط أو تعيينها . نسب ضغط مختلفة للطبقات المتتالية . المعدل المحدد لكل مستوى جودة هو عامل الضغط المطلوب . النسب المتناقصة المطلوبة. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | الحصول على الخط البديل الافتراضي أو تعيينه (الخط الذي سيتم استخدامه لرسم النص عند التصدير إلى خطوط المسح ، إذا لم يتم تقديم خط الطبقة الموجود في ملف PSD في النظام). : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection ()؛ System.Drawing.FontFamily [] Families = col.Families؛ string افتراضي PsdLoadOptions psdLoadOptions = new PsdLoadOptions () {DefaultReplacementFont = defaultFontName})؛ |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان [إطار كامل] . |
| [Irreversible](../../aspose.psd.imageoptions/jpeg2000options/irreversible/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى استخدام DWT 9-7 الذي لا رجعة فيه (صحيح) أو استخدام ضغط DWT 5-3 بدون خسارة (افتراضي) . |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | خيارات متعدد الصفحات |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | الحصول على لوحة الألوان أو تعيينها . |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | الحصول على معالج حدث التقدم أو تعيينه. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | الحصول على إعدادات الدقة أو تعيينها . |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | الحصول على أو تعيين المصدر لإنشاء الصورة فيه. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | الحصول على أو تعيين خيارات التحويل النقطي للمتجه. |
| override [XmpData](../../aspose.psd.imageoptions/jpeg2000options/xmpdata/) { get; set; } | الحصول على أو تعيين حاوية بيانات تعريف XMP. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | استنساخ هذا المثال . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | التخلص من المثيل الحالي. |

### أمثلة

يوضح هذا المثال استخدام فئات مختلفة من SaveOptions Namespace لأغراض التصدير. يتم تحميل صورة من نوع Psd في مثيل Image ثم تصديرها إلى عدة تنسيقات.

```csharp
[C#]

// تحميل صورة موجودة في مثيل لفئة الصورة
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // تصدير إلى تنسيق ملف BMP باستخدام الخيارات الافتراضية
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    // تصدير إلى تنسيق ملف JPEG باستخدام الخيارات الافتراضية
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    // تصدير إلى تنسيق ملف JPEG 2000 باستخدام الخيارات الافتراضية
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    // تصدير إلى تنسيق ملف PNG باستخدام الخيارات الافتراضية
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    // تصدير إلى تنسيق ملف TIFF باستخدام الخيارات الافتراضية
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### أنظر أيضا

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* مساحة الاسم [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* المجسم [Aspose.PSD](../../)


