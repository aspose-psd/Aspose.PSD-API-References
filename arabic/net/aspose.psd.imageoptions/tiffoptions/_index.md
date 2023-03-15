---
title: Class TiffOptions
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.ImageOptions.TiffOptions فصل. خيارات تنسيق ملف tiff . لاحظ أنه سيتم الكتابة فوق علامات العرض والارتفاع عند إنشاء الصورة بواسطة معلمات العرض والارتفاع  لذلك ليست هناك حاجة لتحديدها مباشرة. لاحظ أن العديد من الخيارات ترجع قيمة افتراضية ولكن هذا لا يعني ذلك يتم تعيين هذا الخيار بشكل صريح كقيمة علامة. للتحقق من وجود العلامة  استخدم خاصية العلامات أو طريقة IsTagPresent المقابلة.
type: docs
weight: 4940
url: /ar/net/aspose.psd.imageoptions/tiffoptions/
---
## TiffOptions class

خيارات تنسيق ملف tiff . لاحظ أنه سيتم الكتابة فوق علامات العرض والارتفاع عند إنشاء الصورة بواسطة معلمات العرض والارتفاع ، لذلك ليست هناك حاجة لتحديدها مباشرة. لاحظ أن العديد من الخيارات ترجع قيمة افتراضية ولكن هذا لا يعني ذلك يتم تعيين هذا الخيار بشكل صريح كقيمة علامة. للتحقق من وجود العلامة ، استخدم خاصية العلامات أو طريقة IsTagPresent المقابلة.

```csharp
public class TiffOptions : ImageOptionsBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | يقوم بتهيئة مثيل جديد لملف`TiffOptions` فئة . |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | يقوم بتهيئة مثيل جديد لملف`TiffOptions` فصل. بشكل افتراضي ، يتم استخدام اصطلاح Endian الصغير. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | يقوم بتهيئة مثيل جديد لملف`TiffOptions` فئة . |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | يقوم بتهيئة مثيل جديد لملف`TiffOptions` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | الحصول على أو تحديد خيار تخزين ألفا. خيارات أخرى غيرUnspecified يتم استخدام عندما يكون هناك أكثر من 3[`SamplesPerPixel`](./samplesperpixel/) محددة . |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | الحصول على الفنان أو تعيينه . |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | يحصل على وحدات البت لكل بكسل . |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | الحصول على أو تعيين وحدات البت لكل عينة. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ترتيب tiff بايت. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | الحصول على أو تعيين خريطة الألوان . |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | الحصول على جودة الصورة المضغوطة أو تعيينها. يستخدم مع ضغط Jpeg . |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | الحصول على الضغط أو تعيينه . |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | الحصول على حقوق النشر أو تعيينها. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | الحصول على أو تحديد التاريخ والوقت. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | الحصول على الخط البديل الافتراضي أو تعيينه (الخط الذي سيتم استخدامه لرسم النص عند التصدير إلى خطوط المسح ، إذا لم يتم تقديم خط الطبقة الموجود في ملف PSD في النظام). : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection ()؛ System.Drawing.FontFamily [] Families = col.Families؛ string افتراضي PsdLoadOptions psdLoadOptions = new PsdLoadOptions () {DefaultReplacementFont = defaultFontName})؛ |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | الحصول على أو تحديد اسم المستند. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | الحصول على المؤشر أو تعيينه إلى EXIF IFD . |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | الحصول على أو تعيين خيارات الفاكس t4. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | الحصول على أو تحديد معيار ملف TIFF. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | الحصول على أو تعيين ترتيب ملء بتات البايت. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان [إطار كامل] . |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | الحصول على تلميحات الألوان النصفية أو تعيينها. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | الحصول على دفق ملف تعريف Icc أو تعيينه. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | الحصول على أو تحديد وصف الصورة. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | الحصول على أو تحديد طول الصورة . |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | الحصول على عرض الصورة أو تحديده . |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | الحصول على أسماء الحبر أو تعيينها. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | الحصول على قيمة تشير إلى وجود العينات الإضافية . |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت الصورة مقسمة. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كان ملف`TiffOptions` تم تكوينه بشكل صحيح. استخدم طريقة التحقق من الصحة للعثور على سبب الفشل. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | الحصول على الحد الأقصى لقيمة العينة أو تعيينها. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | الحصول على الحد الأدنى لقيمة العينة أو تعيينها. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | خيارات متعدد الصفحات |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | الحصول على الاتجاه أو تحديده. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | الحصول على اسم الصفحة أو تعيينه . |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | الحصول على علامة رقم الصفحة أو تعيينها. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | الحصول على لوحة الألوان أو تعيينها . |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | الحصول على القياس الضوئي أو تعيينه. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | الحصول على التكوين المستوي أو تعيينه. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | الحصول على أو تعيين المتنبئ لضغط LZW . |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يجب مضاعفة المكونات مسبقًا. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | الحصول على معالج حدث التقدم أو تعيينه. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | الحصول على إعدادات الدقة أو تعيينها . |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | الحصول على أو تعيين وحدة الدقة . |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | الحصول على أو تعيين الصفوف لكل شريط . |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | الحصول على تنسيق العينة أو تعيينه. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | يحصل على عينات لكل بكسل. لتغيير قيمة هذه الخاصية ، استخدم ملحق[`BitsPerSample`](./bitspersample/) واضع الممتلكات. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | الحصول على أو تعيين الشركة المصنعة للماسح الضوئي. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | الحصول على أو تحديد طراز الماسح . |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | الحصول على الحد الأقصى لقيمة العينة أو تعيينها. تحتوي القيمة على نوع حقل يتطابق بشكل أفضل مع بيانات العينة (نوع بايت أو قصير أو طويل). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | الحصول على القيمة الدنيا للعينة أو تعيينها. تحتوي القيمة على نوع حقل يتطابق بشكل أفضل مع بيانات العينة (نوع بايت أو قصير أو طويل). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | يحصل أو يحدد نوع البرنامج. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | الحصول على أو تعيين المصدر لإنشاء الصورة فيه. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | الحصول على عدد بايتات الشريط أو تعيينه. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | يحصل أو يحدد إزاحة الشريط . |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | الحصول على أو تعيين إشارة عامة لنوع البيانات الموجودة في هذا الملف الفرعي. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | الحصول على العلامات أو تعيينها. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | الحصول على الطابعة المستهدفة أو تعيينها . |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | الحصول على العتبة أو تعيينها . |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | الحصول على عدد بايتات التجانب أو تعيينه. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | يحصل على تعيين طول البلاط. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | الحصول على تعويضات التجانب أو تعيينها. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | يحصل على تعيينات عرض البلاط . |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | الحصول على إجمالي الصفحات . |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | يحصل على عدد العلامات الصالح. هذا ليس إجمالي عدد العلامات ولكن عدد العلامات التي يمكن الاحتفاظ بها. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | الحصول على أو تعيين خيارات التحويل النقطي للمتجه. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | الحصول على أو تعيين حاوية بيانات تعريف XMP. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | الحصول على أو تعيين مؤلف الصورة ، والذي يستخدمه مستكشف Windows. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | الحصول على تعليق على الصورة أو تعيينه ، والذي يستخدمه مستكشف Windows. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | الحصول على أو تعيين صورة الموضوع ، والتي يستخدمها مستكشف Windows. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | الحصول على موضع x أو تحديده . |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | الحصول على معلومات حول الصورة أو تعيينها ، والتي يستخدمها مستكشف Windows. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | الحصول على معلومات حول الصورة أو تعيينها ، والتي يستخدمها مستكشف Windows. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | الحصول على دقة x أو تعيينها . |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | الحصول على أو تعيين YCbCrCoefficients . |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | الحصول على أو تعيين عوامل أخذ العينات الفرعية لمقاييس الضوء YCbCr . |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | الحصول على أو تحديد الموضع y . |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | الحصول على دقة y أو تعيينها . |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | يضيف علامة جديدة . |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | يضيف العلامات . |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | استنساخ هذا المثال . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | التخلص من المثيل الحالي. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | الحصول على مثيل العلامة حسب النوع. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | لتحديد ما إذا كانت العلامة موجودة في الخيارات أم لا. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | يزيل العلامة . |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | يتحقق مما إذا كانت الخيارات تحتوي على مجموعة صالحة من العلامات |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | الحصول على عدد العلامات الصالحة . |

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

تستخدم هذه الأمثلة فئة GraphicsPath و Graphics لإنشاء الأشكال ومعالجتها على سطح الصورة. مثال ينشئ صورة جديدة ويرسم المسارات بمساعدة فئة GraphicsPath. في النهاية ، يتم استدعاء طريقة DrawPath المعروضة بواسطة فئة الرسومات لعرض المسارات على السطح. أخيرًا يتم تصدير الصورة إلى تنسيق ملف Tiff.

```csharp
[C#]

// إنشاء مثيل للصورة 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // إنشاء وتهيئة مثيل لفئة الرسومات
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // مسح سطح الرسومات
    graphics.Clear(Color.Wheat);

    // إنشاء مثيل لفئة GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    // إنشاء مثيل لفئة الشكل
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    // إضافة أشكال إلى كائن الشكل
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    // إضافة كائن الشكل إلى GraphicsPath
    graphicspath.AddFigure(figure);

    // رسم المسار باستخدام كائن القلم من اللون الأسود
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // قم بإنشاء مثيل لـ TiffOptions وعيّن خصائصه المتنوعة
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // احفظ جميع التغييرات.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### أنظر أيضا

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* مساحة الاسم [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* المجسم [Aspose.PSD](../../)


