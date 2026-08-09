---
title: "الفئة TiffOptions"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.ImageOptions.TiffOptions. خيارات تنسيق ملف tiff. لاحظ أن علامات العرض والارتفاع سيتم استبدالها عند إنشاء الصورة بواسطة معلمات العرض والارتفاع لذا لا حاجة لتحديدها مباشرة. لاحظ أن العديد من الخيارات تُعيد قيمة افتراضية لكن هذا لا يعني أن هذا الخيار تم تعيينه صراحة كقيمة علامة. للتحقق من وجود العلامة استخدم خاصية Tags أو طريقة IsTagPresent."
type: docs
weight: 5430
url: /ar/net/aspose.psd.imageoptions/tiffoptions/
---
{{< psd/tize >}}
## TiffOptions class

خيارات تنسيق ملف tiff. لاحظ أن وسوم العرض والارتفاع سيتم استبدالها عند إنشاء الصورة بواسطة معلمات العرض والارتفاع لذا لا حاجة لتحديدها مباشرة. لاحظ أن العديد من الخيارات تُعيد قيمة افتراضية لكن هذا لا يعني أن هذا الخيار تم تعيينه صراحةً كقيمة للوسم. للتحقق من وجود الوسم استخدم خاصية Tags أو الطريقة المقابلة IsTagPresent.

```csharp
public class TiffOptions : ImageOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | يُنشئ مثيلاً جديدًا من الفئة `TiffOptions`. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | يُنشئ مثيلاً جديدًا من الفئة `TiffOptions`. بشكل افتراضي يتم استخدام نظام النهاية الصغيرة. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | يُنشئ مثيلاً جديدًا من الفئة `TiffOptions`. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | يُنشئ مثيلاً جديدًا من الفئة `TiffOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | يحصل أو يضبط خيار تخزين ألفا. تُستخدم الخيارات غير Unspecified عندما يكون هناك أكثر من 3 [`SamplesPerPixel`](./samplesperpixel/) معرفة. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | يحصل أو يضبط الفنان. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | يحصل على عدد البتات لكل بكسل. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | يحصل أو يضبط عدد البتات لكل عينة. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ترتيب بايتات tiff. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | يحصل أو يعيّن خريطة الألوان. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | يحصل أو يعيّن جودة الصورة المضغوطة. يُستخدم مع ضغط Jpeg. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | يحصل أو يضبط الضغط. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | يحصل أو يعيّن حقوق النشر. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | يحصل أو يعيّن التاريخ والوقت. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/tiffoptions/defaultmemoryallocationlimit/) { get; set; } | يحصل أو يضبط حد تخصيص الذاكرة الافتراضي. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | يحصل أو يعيّن الخط البديل الافتراضي (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD موجودًا في النظام). للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام المقتطف البرمجي التالي: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | يحصل أو يعيّن اسم المستند. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | يحصل أو يضبط المؤشر إلى EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | يحصل أو يعيّن خيارات الفاكس t4. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | يحصل أو يعيّن معيار ملف TIFF. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | يحصل أو يعيّن ترتيب تعبئة بتات البايت. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [الإطار الكامل]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | يحصل أو يعيّن تلميحات نصف النغمة. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | يحصل أو يعيّن تدفق ملف تعريف Icc. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | يحصل أو يعيّن وصف الصورة. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | يحصل أو يعيّن طول الصورة. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | يحصل أو يعيّن عرض الصورة. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | يحصل أو يعيّن أسماء الحبر. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت العينات الإضافية موجودة. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت الصورة مقسمة إلى بلاطات. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا تم تكوين `TiffOptions` بشكل صحيح. استخدم طريقة Validate للعثور على سبب الفشل. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | يحصل أو يعيّن قيمة العينة القصوى. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | يحصل أو يعيّن قيمة العينة الدنيا. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | خيارات الصفحات المتعددة |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | يحصل أو يعيّن الاتجاه. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | يحصل أو يعيّن اسم الصفحة. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | يحصل أو يعيّن علامة رقم الصفحة. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | يحصل أو يعيّن الخصائص الضوئية. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | يحصل أو يعيّن تكوين المستوى. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | يحصل أو يعيّن المتنبئ لضغط LZW. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ضرب المكوّنات مسبقًا. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | يحصل أو يعيّن معالج حدث التقدم. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | يحصل أو يعيّن إعدادات الدقة. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | يحصل أو يضبط وحدة الدقة. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | يحصل أو يعيّن عدد الصفوف لكل شريط. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | يحصل أو يعيّن تنسيق العينة. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | يحصل على العينات لكل بكسل. لتغيير قيمة هذه الخاصية استخدم مُعيّن الخاصية [`BitsPerSample`](./bitspersample/). |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | يحصل أو يعيّن الشركة المصنعة للمسح الضوئي. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | يحصل أو يعيّن طراز المسح الضوئي. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | يحصل أو يعيّن القيمة القصوى للعينة. القيمة لها نوع حقل يتطابق بأفضل شكل مع بيانات العينة (نوع Byte أو Short أو Long). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | يحصل أو يعيّن القيمة الدنيا للعينة. القيمة لها نوع حقل يتطابق بأفضل شكل مع بيانات العينة (نوع Byte أو Short أو Long). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | يحصل أو يعيّن نوع البرنامج. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | يحصل أو يعيّن المصدر لإنشاء الصورة فيه. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | يحصل أو يعيّن عدد بايتات الشريط. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | يحصل أو يعيّن إزاحات الشريط. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | يحصل أو يعيّن إشارة عامة لنوع البيانات الموجودة في هذا الملف الفرعي. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | يحصل أو يعيّن العلامات. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | يحصل أو يعيّن الطابعة المستهدفة. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | يحصل أو يعيّن العتبة. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | يحصل أو يعيّن عدد بايتات البلاطة. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | يحصل أو يعيّن طول البلاطة. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | يحصل أو يعيّن إزاحات البلاطة. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | يحصل أو يعيّن عرض البلاطة. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | يحصل على إجمالي الصفحات. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | يحصل على عدد العلامات الصالحة. هذا ليس إجمالي عدد العلامات بل عدد العلامات التي يمكن حفظها. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | يحصل أو يعيّن خيارات تحويل المتجه إلى نقطية. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | يحصل أو يضبط حاوية بيانات التعريف XMP. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | يحصل أو يعيّن مؤلف الصورة، والذي يستخدمه Windows Explorer. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | يحصل أو يعيّن تعليقًا على الصورة، والذي يستخدمه Windows Explorer. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | يحصل أو يعيّن موضوع الصورة، والذي يستخدمه Windows Explorer. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | يحصل أو يعيّن موضع x. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | يحصل أو يضبط معلومات حول الصورة التي يستخدمها Windows Explorer. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | يحصل أو يضبط معلومات حول الصورة التي يستخدمها Windows Explorer. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | يحصل أو يضبط دقة x. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | يحصل أو يضبط YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | يحصل أو يضبط عوامل أخذ العينات الفرعية للـ YCbCr الفوتومتري. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | يحصل أو يضبط موضع y. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | يحصل أو يضبط دقة y. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | يضيف علامة جديدة. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | يضيف العلامات. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | ينسخ هذه المثيل. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | يحصل على نسخة العلامة حسب النوع. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | يحدد ما إذا كانت العلامة موجودة في الخيارات أم لا. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | يزيل العلامة. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | يتحقق مما إذا كانت الخيارات تحتوي على تركيبة صالحة من العلامات. |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | يحصل على عدد العلامات الصالحة. |

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

تستخدم هذه الأمثلة فئة GraphicsPath وفئة Graphics لإنشاء وتعديل الأشكال على سطح صورة. ينشئ المثال صورة جديدة ويرسم المسارات بمساعدة فئة GraphicsPath. في النهاية يتم استدعاء طريقة DrawPath التي توفرها فئة Graphics لرسم المسارات على السطح. أخيرًا يتم تصدير الصورة إلى تنسيق ملف Tiff.

```csharp
[C#]

//إنشاء نسخة من Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //إنشاء وتهيئة نسخة من فئة Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //مسح سطح Graphics
    graphics.Clear(Color.Wheat);

    //إنشاء نسخة من فئة GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //إنشاء نسخة من فئة Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //إضافة أشكال إلى كائن Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //إضافة كائن Figure إلى GraphicsPath
    graphicspath.AddFigure(figure);

    //رسم المسار باستخدام كائن Pen بلون أسود
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //إنشاء نسخة من TiffOptions وضبط خصائصه المتنوعة
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // احفظ جميع التغييرات.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### انظر أيضًا

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


