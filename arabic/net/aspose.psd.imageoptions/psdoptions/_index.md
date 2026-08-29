---
title: "الفئة PsdOptions."
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.ImageOptions.PsdOptions. خيارات إنشاء تنسيق ملف PSD."
type: docs
weight: 5390
url: /ar/net/aspose.psd.imageoptions/psdoptions/
---
{{< psd/tize >}}
## PsdOptions class

خيارات إنشاء تنسيق ملف psd.

```csharp
public class PsdOptions : ImageOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PsdOptions](psdoptions/#constructor)() | تهيئ مثيلاً جديداً من الفئة `PsdOptions`. |
| [PsdOptions](psdoptions/#constructor_1)(PsdImage) | تهيئ مثيلاً جديداً من الفئة `PsdOptions`. |
| [PsdOptions](psdoptions/#constructor_2)(PsdOptions) | تهيئ مثيلاً جديداً من الفئة `PsdOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundContents](../../aspose.psd.imageoptions/psdoptions/backgroundcontents/) { get; set; } | يحصل أو يضبط لون الخلفية. يمكن رؤيته تحت الكائنات الشفافة. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [ChannelBitsCount](../../aspose.psd.imageoptions/psdoptions/channelbitscount/) { get; set; } | يحصل أو يضبط عدد البتات لكل قناة لونية. |
| [ChannelsCount](../../aspose.psd.imageoptions/psdoptions/channelscount/) { get; set; } | يحصل أو يضبط عدد قنوات اللون. |
| [ColorMode](../../aspose.psd.imageoptions/psdoptions/colormode/) { get; set; } | يحصل أو يضبط وضع اللون في PSD. |
| [CompressionMethod](../../aspose.psd.imageoptions/psdoptions/compressionmethod/) { get; set; } | يحصل أو يضبط طريقة ضغط PSD. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | يحصل أو يعيّن الخط البديل الافتراضي (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD موجودًا في النظام). للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام المقتطف البرمجي التالي: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [الإطار الكامل]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | خيارات الصفحات المتعددة |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | يحصل أو يعيّن معالج حدث التقدم. |
| [PsdVersion](../../aspose.psd.imageoptions/psdoptions/psdversion/) { get; set; } | يحصل أو يضبط إصدار تنسيق الملف. يمكن أن يكون PSD أو PSB. |
| [RefreshImagePreviewData](../../aspose.psd.imageoptions/psdoptions/refreshimagepreviewdata/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [refresh image preview data] - خيار يُستخدم لتعزيز التوافق مع عارضات صور PSD الأخرى. يرجى ملاحظة أن رسم طبقات النص إلى التخطيط النهائي غير مدعوم على منصة Compact Framework. |
| [RemoveGlobalTextEngineResource](../../aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان - إزالة مورد محرك النص العالمي - يُستخدم لبعض ملفات PSD ذات الطبقات النصية، في الحالة الوحيدة التي لا يمكن فتحها في Adobe Photoshop بعد المعالجة (غالبًا ما يتعلق بطبقات النص التي تفتقد الخطوط). بعد استخدام هذا الخيار، يحتاج المستخدم إلى القيام بما يلي في الملف المفتوح في Photoshop: القائمة "Text" -> "Process absent fonts". بعد تلك العملية سيظهر جميع النص مرة أخرى. يرجى ملاحظة أن هذه العملية قد تتسبب في بعض تغييرات التخطيط النهائي. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | يحصل أو يعيّن إعدادات الدقة. |
| [Resources](../../aspose.psd.imageoptions/psdoptions/resources/) { get; set; } | يحصل أو يضبط موارد PSD. إذا كانت القيمة: NULL - فاحفظ موارد ImageResources الأصلية (السلوك الافتراضي) غير فارغ - فاحفظ الموارد الممررة إلى هذه الخاصية + [required resources] فارغ - فاحفظ فقط [required resources]. الموارد المطلوبة: ResolutionInfoResource, XmpResource |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | يحصل أو يعيّن المصدر لإنشاء الصورة فيه. |
| [UpdateMetadata](../../aspose.psd.imageoptions/psdoptions/updatemetadata/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [update metadata]. إذا كانت القيمة true، سيتم تحديث البيانات الوصفية أثناء حفظ الصورة. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | يحصل أو يعيّن خيارات تحويل المتجه إلى نقطية. |
| [Version](../../aspose.psd.imageoptions/psdoptions/version/) { get; set; } | يحصل أو يضبط إصدار ملف PSD. |
| override [XmpData](../../aspose.psd.imageoptions/psdoptions/xmpdata/) { get; set; } | احصل أو اضبط حاوية بيانات XMP |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | ينسخ هذه المثيل. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |

## أمثلة

المثال التالي يوضح كيف يمكنك تصدير ملف AI إلى صيغة PSD و PNG في Aspose.PSD

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

هذا المثال ينشئ ملف Image جديد في موقع على القرص كما هو محدد بخصية Source لكائن PsdOptions. يتم تعيين عدة خصائص لكائن PsdOptions قبل إنشاء الصورة الفعلية. خاصة خاصية Source التي تشير إلى موقع القرص الفعلي في هذه الحالة.

```csharp
[C#]

//إنشاء مثال من PsdOptions وتعيين خصائصه المتنوعة
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//إنشاء مثال من FileCreateSource وتعيينه كـ Source لكائن PsdOptions
//المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه مؤقتًا أم لا
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//إنشاء مثال من Image وتهيئته بمثال من PsdOptions عن طريق استدعاء طريقة Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //قم ببعض معالجة الصورة.

    // احفظ جميع التغييرات
    image.Save();
}
```

المثال التالي يوضح أن قراءة وحفظ ملفات PSD ذات 16 بت رمادية إلى 16 بت لكل قناة RGB يعمل بشكل صحيح دون أي استثناء.

```csharp
[C#]

string sourceFilePath = "grayscale5x5.psd";
string exportFilePath = "rgb16bit5x5.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Rgb,
    ChannelBitsCount = 16,
    ChannelsCount = 4
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // هنا لا ينبغي أن يكون هناك أي استثناء.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

المثال التالي يوضح أن قراءة وحفظ ملفات PSD ذات 16 بت رمادية إلى 8 بت لكل قناة رمادية يعمل بشكل صحيح دون أي استثناء.

```csharp
[C#]

string sourceFilePath = "grayscale16bit.psd";
string exportFilePath = "grayscale16bit_Grayscale8_2_RLE.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Grayscale,
    ChannelBitsCount = 8,
    ChannelsCount = 2
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // هنا لا ينبغي أن يكون هناك أي استثناء.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

المثال التالي يوضح كيف يمكنك استخدام وضع دمج الطبقة PassThrough في Aspose.PSD

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

المثال التالي يوضح أن تقدم تحويل المستند يعمل بشكل صحيح وبدون استثناء.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

هذا المثال يوضح كيفية تحميل معلومات البكسل في مصفوفة من نوع Color، تعديل المصفوفة وإعادتها إلى الصورة. لتنفيذ هذه العمليات، ينشئ هذا المثال ملف Image جديد (بتنسيق PSD) باستخدام كائن MemoryStream.

```csharp
[C#]

//إنشاء مثال من MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //إنشاء مثال من PsdOptions وتعيين خصائصه المتنوعة بما في ذلك خاصية Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //إنشاء مثال من Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //احصل على بكسلات الصورة عن طريق تحديد المنطقة كحدود الصورة
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //تكرار عبر المصفوفة وتعيين لون البكسل المفهرس البديل
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //تعيين لون البكسل المفهرس إلى الأصفر
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //تعيين لون البكسل المفهرس إلى الأزرق
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //تطبيق تغييرات البكسل على الصورة
        image.SavePixels(image.Bounds, pixels);

        // احفظ جميع التغييرات.
        image.Save();
    }

    //اكتب MemoryStream إلى ملف
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

المثال التالي يوضح أن قراءة وحفظ ملفات PSD ذات 16 بت بالدرجات الرمادية يعمل بشكل صحيح وبدون استثناء.

```csharp
[C#]

Stack<string> outputFilePathStack = new Stack<string>();

void SaveToPsdThenLoadAndSaveToPng(
    string file,
    ColorModes colorMode,
    short channelBitsCount,
    short channelsCount,
    CompressionMethod compression,
    int layerNumber)
{
    string filePath = file + ".psd";
    string postfix = colorMode.ToString() + channelBitsCount + "_" + channelsCount + "_" + compression;
    string exportPath = file + postfix + ".psd";
    PsdOptions psdOptions = new PsdOptions()
    {
        ColorMode = colorMode,
        ChannelBitsCount = channelBitsCount,
        ChannelsCount = channelsCount,
        CompressionMethod = compression
    };

    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        RasterCachedImage raster = layerNumber >= 0 ? (RasterCachedImage)image.Layers[layerNumber] : image;

        Aspose.PSD.Graphics graphics = new Graphics(raster);
        int width = raster.Width;
        int height = raster.Height;
        Rectangle rect = new Rectangle(
            width / 3,
            height / 3,
            width - (2 * (width / 3)) - 1,
            height - (2 * (height / 3)) - 1);
        graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);

        image.Save(exportPath, psdOptions);
    }

    string pngExportPath = Path.ChangeExtension(exportPath, "png");
    using (PsdImage image = (PsdImage)Image.Load(exportPath))
    {
        // هنا لا ينبغي أن يكون هناك أي استثناء.
        image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
    }

    outputFilePathStack.Push(exportPath);
}

SaveToPsdThenLoadAndSaveToPng("grayscale5x5", ColorModes.Cmyk, 16, 5, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("cmyk16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("index8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
```

### انظر أيضًا

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


