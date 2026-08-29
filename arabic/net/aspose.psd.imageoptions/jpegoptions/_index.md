---
title: "الفئة JpegOptions"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.ImageOptions.JpegOptions. خيارات إنشاء تنسيق ملف jpeg"
type: docs
weight: 5330
url: /ar/net/aspose.psd.imageoptions/jpegoptions/
---
{{< psd/tize >}}
## JpegOptions class

خيارات إنشاء تنسيق ملف jpeg.

```csharp
public class JpegOptions : ImageOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | يُهيئ مثيلاً جديدًا من الفئة `JpegOptions`. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | يُهيئ مثيلاً جديدًا من الفئة `JpegOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | يحصل أو يضبط عدد البتات لكل قناة في صورة jpeg غير مضغوطة. الآن ندعم من 2 إلى 8 بتات لكل قناة. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | ملف تعريف اللون CMYK الوجهة لصور jpeg بنظام CMYK. يُستخدم لحفظ الصور. يجب أن يكون مقترنًا بـ RGBColorProfile للتحويل اللوني الصحيح. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | يحصل أو يضبط نوع اللون لصورة jpeg. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | يحصل أو يضبط تعليق ملف jpeg. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | يحصل أو يضبط نوع الضغط. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/jpegoptions/defaultmemoryallocationlimit/) { get; set; } | يحصل أو يضبط حد تخصيص الذاكرة الافتراضي. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | يحصل أو يعيّن الخط البديل الافتراضي (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD موجودًا في النظام). للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام المقتطف البرمجي التالي: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | احصل أو اضبط حاوية بيانات exif |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [الإطار الكامل]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | يحصل أو يضبط العينات الفرعية الأفقية لكل مكوّن. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | يحصل أو يضبط jfif. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | يحصل أو يضبط حد الفرق في JPEG-LS للترميز شبه غير فقدان (معامل NEAR من مواصفة JPEG-LS). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | يحصل أو يضبط وضع التداخل في JPEG-LS. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | يحصل أو يضبط معلمات الإعداد المسبق لـ JPEG-LS. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | خيارات الصفحات المتعددة |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب خلط مكونات الأحمر والأخضر والأزرق مع لون الخلفية، إذا كان قناة ألفا موجودة. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | يحصل أو يعيّن معالج حدث التقدم. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | يحصل أو يضبط جودة الصورة. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | يحصل أو يضبط إعدادات مُحسّن RD. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | يحصل أو يعيّن إعدادات الدقة. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | يحصل أو يضبط وحدة الدقة. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | ملف تعريف اللون RGB الوجهة لصور JPEG بنظام CMYK. يُستخدم لحفظ الصور. يجب أن يكون مقترناً بـ CMYKColorProfile للتحويل اللوني الصحيح. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | يحصل أو يضبط وضع تقريب العينة لتلائم قيمة 8‑بت إلى قيمة n‑بت. BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | الجودة المُقاسة. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | يحصل أو يعيّن المصدر لإنشاء الصورة فيه. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | يحصل أو يعيّن خيارات تحويل المتجه إلى نقطية. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | يحصل أو يضبط عمليات التقسيم العمودي لكل مكوّن. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | يحصل أو يضبط حاوية بيانات التعريف XMP. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | ينسخ هذه المثيل. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |

## أمثلة

يوضح هذا المثال استخدام Aspose.PSD لواجهة برمجة التطبيقات .Net لتحويل الصور إلى صيغة JPEG. لتحقيق هذا الهدف، يقوم المثال بتحميل صورة موجودة ثم تحويلها إلى صيغة ملف JPEG.

```csharp
[C#]

//ينشئ مثيلاً من فئة الصورة ويُهيئه بملف موجود عبر مسار الملف.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //إنشاء مثيل من فئة PsdOptions.
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //ضبط الجودة إلى 50٪ لتقليل حجم الصورة الناتجة.
    jpegOptions.Quality = 50;

    //ضبط تعليقات EXIF.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //احفظ الصورة في موقع القرص مع إعدادات JpegOptions المقدمة.
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

يوضح هذا المثال استخدام System.IO.Stream لإنشاء ملف صورة جديد.

```csharp
[C#]

//ينشئ مثيلاً من PsdOptions ويضبط خصائصه المتنوعة.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//إنشاء مثيل من System.IO.Stream.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//تحديد خاصية المصدر للمثيل من PsdOptions.
//المعامل البولياني الثاني يحدد ما إذا كان سيتم التخلص من الـ Stream بمجرد الخروج من النطاق.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//ينشئ مثيلاً من Image ويستدعي طريقة Create مع PsdOptions كمعامل لتهيئة كائن Image.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //قم ببعض معالجة الصورة.
}
```

هذا المثال يوضح استخدام فئات مختلفة من مساحة الأسماء SaveOptions لأغراض التصدير. يتم تحميل صورة من النوع Psd في مثيل من Image ثم يتم تصديرها إلى عدة تنسيقات.

```csharp
[C#]

//تحميل صورة موجودة في مثيل من الفئة Image.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //تصدير إلى تنسيق ملف BMP باستخدام الخيارات الافتراضية.
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //تصدير إلى تنسيق ملف JPEG باستخدام الخيارات الافتراضية.
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //تصدير إلى تنسيق ملف JPEG 2000 باستخدام الخيارات الافتراضية.
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //تصدير إلى تنسيق ملف PNG باستخدام الخيارات الافتراضية.
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //تصدير إلى تنسيق ملف TIFF باستخدام الخيارات الافتراضية.
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### انظر أيضًا

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


