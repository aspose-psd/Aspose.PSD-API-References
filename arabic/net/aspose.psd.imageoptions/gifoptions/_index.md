---
title: Class GifOptions
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.ImageOptions.GifOptions فصل. خيارات إنشاء تنسيق ملف gif .
type: docs
weight: 4810
url: /ar/net/aspose.psd.imageoptions/gifoptions/
---
## GifOptions class

خيارات إنشاء تنسيق ملف gif .

```csharp
public class GifOptions : ImageOptionsBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | يقوم بتهيئة مثيل جديد لملف`GifOptions` فئة . |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | يقوم بتهيئة مثيل جديد لملف`GifOptions` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | الحصول على فهرس لون خلفية GIF أو تعيينه. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution/) { get; set; } | الحصول على دقة ألوان GIF أو تعيينها. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | الحصول على الخط البديل الافتراضي أو تعيينه (الخط الذي سيتم استخدامه لرسم النص عند التصدير إلى خطوط المسح ، إذا لم يتم تقديم خط الطبقة الموجود في ملف PSD في النظام). : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection ()؛ System.Drawing.FontFamily [] Families = col.Families؛ string افتراضي PsdLoadOptions psdLoadOptions = new PsdLoadOptions () {DefaultReplacementFont = defaultFontName})؛ |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان قد تم تطبيق تصحيح لوح الألوان . |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان [إطار كامل] . |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان GIF يحتوي على مقطع دعائي . |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced/) { get; set; } | صحيح إذا كان يجب تشابك الصورة . |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت مدخلات اللوحة مرتبة أم لا. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff/) { get; set; } | الحصول على أو تحديد أقصى فرق بكسل مسموح به. إذا كانت القيمة أكبر من الصفر ، فسيتم استخدام ضغط الفقد . القيمة الموصى بها للضغط الأمثل مع فقدان البيانات هي 80. 30 ضغط خفيف للغاية ، و 200 ثقيل. مستويات الخسارة العالية جدًا لن تعطي قدرًا كبيرًا من المكاسب . نطاق القيم المسموح بها هو [0 ، 1000] . |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | خيارات متعدد الصفحات |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | الحصول على لوحة الألوان أو تعيينها . |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | الحصول على أو تعيين نسبة العرض إلى الارتفاع بتنسيق GIF بكسل. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | الحصول على معالج حدث التقدم أو تعيينه. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | الحصول على إعدادات الدقة أو تعيينها . |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | الحصول على أو تعيين المصدر لإنشاء الصورة فيه. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | الحصول على أو تعيين خيارات التحويل النقطي للمتجه. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata/) { get; set; } | الحصول على أو تعيين حاوية بيانات تعريف XMP. |

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


