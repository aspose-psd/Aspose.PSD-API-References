---
title: Class JpegOptions
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.ImageOptions.JpegOptions فصل. خيارات إنشاء تنسيق ملف jpeg .
type: docs
weight: 4840
url: /ar/net/aspose.psd.imageoptions/jpegoptions/
---
## JpegOptions class

خيارات إنشاء تنسيق ملف jpeg .

```csharp
public class JpegOptions : ImageOptionsBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | يقوم بتهيئة مثيل جديد لملف`JpegOptions` فئة . |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | يقوم بتهيئة مثيل جديد لملف`JpegOptions` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | الحصول على أو تعيين وحدات بت لكل قناة لصورة jpeg بدون فقدان. نحن ندعم الآن من 2 إلى 8 بت لكل قناة. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | ملف تعريف الألوان CMYK الوجهة لصور CMYK jpeg. استخدم لحفظ الصور. يجب أن يكون مقترنًا بـ RGBColorProfile لتحويل اللون الصحيح. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | الحصول على أو تحديد نوع اللون لصورة jpeg . |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | الحصول على تعليق ملف jpeg أو تعيينه. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | الحصول على نوع الضغط أو تحديده. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | الحصول على الخط البديل الافتراضي أو تعيينه (الخط الذي سيتم استخدامه لرسم النص عند التصدير إلى خطوط المسح ، إذا لم يتم تقديم خط الطبقة الموجود في ملف PSD في النظام). : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection ()؛ System.Drawing.FontFamily [] Families = col.Families؛ string افتراضي PsdLoadOptions psdLoadOptions = new PsdLoadOptions () {DefaultReplacementFont = defaultFontName})؛ |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | الحصول على أو تعيين حاوية بيانات exif |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان [إطار كامل] . |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | الحصول على أو تعيين العينات الفرعية الأفقية لكل مكون. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | الحصول على أو تعيين jfif. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | الحصول على أو تعيين اختلاف JPEG-LS المرتبط بالتشفير شبه المفقود (معلمة NEAR من مواصفات JPEG-LS). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | الحصول على أو تعيين وضع تداخل JPEG-LS . |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | الحصول على أو تعيين معلمات الإعداد المسبق لـ JPEG-LS. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | خيارات متعدد الصفحات |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | الحصول على لوحة الألوان أو تعيينها . |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يجب خلط المكونات الحمراء والخضراء والزرقاء بلون الخلفية ، في حالة وجود قناة ألفا . |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | الحصول على معالج حدث التقدم أو تعيينه. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | الحصول على جودة الصورة أو تعيينها . |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | الحصول على أو تعيين إعدادات مُحسِّن RD. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | الحصول على إعدادات الدقة أو تعيينها . |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | الحصول على أو تعيين وحدة الدقة . |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | ملف تعريف ألوان RGB الوجهة لصور CMYK jpeg. استخدم لحفظ الصور. يجب أن يكون جنبًا إلى جنب مع CMYKColorProfile لتحويل اللون الصحيح. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | الحصول على أو تعيين نموذج التقريب ليناسب قيمة 8 بت إلى قيمة n بت.BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | الجودة المقاسة . |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | الحصول على أو تعيين المصدر لإنشاء الصورة فيه. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | الحصول على أو تعيين خيارات التحويل النقطي للمتجه. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | الحصول على أو تعيين العينات الفرعية الرأسية لكل مكون. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | الحصول على أو تعيين حاوية بيانات تعريف XMP. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | استنساخ هذا المثال . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | التخلص من المثيل الحالي. |

### أمثلة

يوضح هذا المثال استخدام Aspose.PSD لـ .Net API لتحويل الصور إلى تنسيق Jpeg. لتحقيق هذا الهدف ، يقوم هذا المثال بتحميل صورة موجودة ثم يحولها إلى تنسيق ملف Jpeg.

```csharp
[C#]

// ينشئ مثيلاً لفئة الصورة وتهيئته بملف موجود من خلال مسار الملف
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // إنشاء مثيل لفئة PsdOptions
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    // اضبط الجودة على 50٪ على حجم أقل لصورة الإخراج.
    jpegOptions.Quality = 50;

    // تعيين تعليقات exif.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    // احفظ الصورة في موقع القرص باستخدام إعدادات JpegOptions المتوفرة
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

يوضح هذا المثال استخدام System.IO.Stream لإنشاء ملف صورة جديد

```csharp
[C#]

// ينشئ مثيلاً من PsdOptions ويضبط خصائصه المختلفة
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// إنشاء مثيل System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

// حدد خاصية المصدر لمثيل PsdOptions
// تحدد المعلمة المنطقية الثانية ما إذا كان سيتم التخلص من الدفق بمجرد الخروج من النطاق
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

// ينشئ مثيلًا للصورة واستدعاء طريقة الإنشاء مع PsdOptions كمعامل لتهيئة كائن الصورة   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // القيام ببعض معالجة الصور
}
```

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


