---
title: "الفئة GifOptions"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.ImageOptions.GifOptions. خيارات إنشاء تنسيق ملف gif"
type: docs
weight: 5300
url: /ar/net/aspose.psd.imageoptions/gifoptions/
---
{{< psd/tize >}}
## GifOptions class

خيارات إنشاء صيغة ملف GIF.

```csharp
public class GifOptions : ImageOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | يُهيئ مثيلاً جديدًا من الفئة `GifOptions`. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | يُهيئ مثيلاً جديدًا من الفئة `GifOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | يحصل أو يضبط فهرس لون خلفية GIF. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution/) { get; set; } | يحصل أو يضبط دقة ألوان GIF. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | يحصل أو يعيّن الخط البديل الافتراضي (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD موجودًا في النظام). للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام المقتطف البرمجي التالي: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | يحصل أو يضبط قيمة تُشير إلى ما إذا كان تصحيح اللوحة يُطبق. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [الإطار الكامل]. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer/) { get; set; } | يحصل أو يضبط قيمة تُشير إلى ما إذا كان GIF يحتوي على مقطورة. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced/) { get; set; } | صحيح إذا كان يجب أن تكون الصورة متشابكة. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted/) { get; set; } | يحصل أو يضبط قيمة تُشير إلى ما إذا كانت مدخلات اللوحة مرتبة. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff/) { get; set; } | يحصل أو يضبط الحد الأقصى المسموح لاختلاف البكسل. إذا كان أكبر من الصفر، سيتم استخدام ضغط فقدان البيانات. القيمة الموصى بها لضغط فقدان البيانات المثالي هي 80. 30 يعني ضغط خفيف جدًا، و200 يعني ضغط ثقيل. يعمل بشكل أفضل عندما يُدخل فقدان قليل فقط، ونظرًا لقيود خوارزمية الضغط فإن مستويات الفقدان العالية جدًا لن تُعطي قدرًا كبيرًا من الفائدة. النطاق المسموح للقيم هو [0, 1000]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | خيارات الصفحات المتعددة |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | يحصل أو يضبط نسبة أبعاد بكسل GIF. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | يحصل أو يعيّن معالج حدث التقدم. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | يحصل أو يعيّن إعدادات الدقة. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | يحصل أو يعيّن المصدر لإنشاء الصورة فيه. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | يحصل أو يعيّن خيارات تحويل المتجه إلى نقطية. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata/) { get; set; } | يحصل أو يضبط حاوية بيانات التعريف XMP. |

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


