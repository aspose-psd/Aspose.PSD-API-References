---
title: "فئة Jpeg2000Options"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.ImageOptions.Jpeg2000Options. خيارات تنسيق ملف Jpeg2000"
type: docs
weight: 5320
url: /ar/net/aspose.psd.imageoptions/jpeg2000options/
---
{{< psd/tize >}}
## Jpeg2000Options class

خيارات تنسيق ملف Jpeg2000.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Jpeg2000Options](jpeg2000options/#constructor)() | يُنشئ مثيلاً جديداً من الفئة `Jpeg2000Options`. |
| [Jpeg2000Options](jpeg2000options/#constructor_1)(Jpeg2000Options) | يُنشئ مثيلاً جديداً من الفئة `Jpeg2000Options`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [Codec](../../aspose.psd.imageoptions/jpeg2000options/codec/) { get; set; } | يحصل أو يعيّن برنامج الترميز JPEG2000 |
| [Comments](../../aspose.psd.imageoptions/jpeg2000options/comments/) { get; set; } | يحصل أو يعيّن علامات تعليقات Jpeg. |
| [CompressionRatios](../../aspose.psd.imageoptions/jpeg2000options/compressionratios/) { get; set; } | يحصل أو يعيّن مصفوفة نسب الضغط. نسب ضغط مختلفة للطبقات المتتالية. المعدل المحدد لكل مستوى جودة هو عامل الضغط المطلوب. النسب المتناقصة مطلوبة. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | يحصل أو يعيّن الخط البديل الافتراضي (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD موجودًا في النظام). للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام المقتطف البرمجي التالي: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [الإطار الكامل]. |
| [Irreversible](../../aspose.psd.imageoptions/jpeg2000options/irreversible/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يستخدم DWT غير القابل للعكس 9-7 (true) أو يستخدم ضغط DWT غير فقدان البيانات 5-3 (الافتراضي). |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | خيارات الصفحات المتعددة |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | يحصل أو يعيّن معالج حدث التقدم. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | يحصل أو يعيّن إعدادات الدقة. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | يحصل أو يعيّن المصدر لإنشاء الصورة فيه. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | يحصل أو يعيّن خيارات تحويل المتجه إلى نقطية. |
| override [XmpData](../../aspose.psd.imageoptions/jpeg2000options/xmpdata/) { get; set; } | يحصل أو يضبط حاوية بيانات التعريف XMP. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | ينسخ هذه المثيل. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |

## أمثلة

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


