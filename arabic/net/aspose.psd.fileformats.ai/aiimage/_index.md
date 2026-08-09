---
title: "الفئة AiImage"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.FileFormats.Ai.AiImage. صورة AI لبرنامج Adobe Illustrator"
type: docs
weight: 1270
url: /ar/net/aspose.psd.fileformats.ai/aiimage/
---
{{< psd/tize >}}
## AiImage class

صورة Adobe Illustrator (AI).

```csharp
public sealed class AiImage : Image
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [AiImage](aiimage/)() | يُنشئ مثلاً جديداً من الفئة `AiImage`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ActivePageIndex](../../aspose.psd.fileformats.ai/aiimage/activepageindex/) { get; set; } | يحصل أو يعيّن فهرس الصفحة النشطة. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | يحصل أو يعيّن قيمة للون الخلفية. |
| override [BitsPerPixel](../../aspose.psd.fileformats.ai/aiimage/bitsperpixel/) { get; } | يحصل على عدد البتات في كل بكسل للصورة. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | يحصل على حدود الصورة. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [Container](../../aspose.psd/image/container/) { get; } | يحصل على حاوية [`Image`](../../aspose.psd/image/). |
| [DataSection](../../aspose.psd.fileformats.ai/aiimage/datasection/) { get; } | يحصل على قسم البيانات. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | يحصل على تدفق بيانات الكائن. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| override [FileFormat](../../aspose.psd.fileformats.ai/aiimage/fileformat/) { get; } | يحصل على قيمة تنسيق الملف. |
| [FinalizeSection](../../aspose.psd.fileformats.ai/aiimage/finalizesection/) { get; } | يحصل على قسم الإنهاء. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| [Header](../../aspose.psd.fileformats.ai/aiimage/header/) { get; } | يحصل على الرأس. |
| override [Height](../../aspose.psd.fileformats.ai/aiimage/height/) { get; } | يحصل على ارتفاع الصورة. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | يحصل أو يضبط مراقب المقاطعة. |
| override [IsCached](../../aspose.psd.fileformats.ai/aiimage/iscached/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات. |
| [Layers](../../aspose.psd.fileformats.ai/aiimage/layers/) { get; } | يحصل على أقسام الطبقة. |
| [PageCount](../../aspose.psd.fileformats.ai/aiimage/pagecount/) { get; } | عدد الصفحات. بالنسبة للصور بتنسيق AI القديم يساوي دائماً 0. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | يحصل أو يضبط لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرة. |
| [SetupSection](../../aspose.psd.fileformats.ai/aiimage/setupsection/) { get; } | يحصل على قسم الإعداد. |
| [Size](../../aspose.psd/image/size/) { get; } | يحصل على حجم الصورة. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| [Version](../../aspose.psd.fileformats.ai/aiimage/version/) { get; } | يحصل على إصدار تنسيق Adobe Illustrator. |
| override [Width](../../aspose.psd.fileformats.ai/aiimage/width/) { get; } | يحصل على عرض الصورة. |
| [XmpData](../../aspose.psd.fileformats.ai/aiimage/xmpdata/) { get; } | يحصل على بيانات التعريف XMP. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.ai/aiimage/addlayer/)(AiLayerSection) | يضيف قسم طبقة AI. |
| override [CacheData](../../aspose.psd.fileformats.ai/aiimage/cachedata/)() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل أي بيانات إضافية من الـ [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد للملف الممثل بخيارات الحفظ الممررة. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../../aspose.psd/datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومرّرها إلى طريقة [`Save`](../../aspose.psd/image/save/) كمعامل ثانٍ. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | يعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_1)(int, int, ImageResizeSettings) | يعيد تحجيم الصورة. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_2)(int, int, ResizeType) | يعيد تحجيم الصورة. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | يعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | يعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | يعيد تحجيم الارتفاع بنسبية. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | يعيد تحجيم العرض بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | يعيد تحجيم العرض بنسبية. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | يعيد تحجيم العرض بنسبية. |
| override [RotateFlip](../../aspose.psd.fileformats.ai/aiimage/rotateflip/)(RotateFlipType) | يدور أو يقلب أو يدور ويقلب الصورة. |
| [Save](../../aspose.psd/image/save/)() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [SetPalette](../../aspose.psd.fileformats.ai/aiimage/setpalette/)(IColorPalette, bool) | يضبط لوحة ألوان الصورة. |

## أمثلة

المثال التالي يوضح كيف يمكنك تصدير ملفات Adobe Illustrator إلى تنسيق PDF في Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

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

المثال التالي يوضح دعم تصدير تنسيق Ai إلى صيغ PSD و PNG و JPG و GIF و TIF.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"34992OStroke",
    @"rect2_color",
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string name = sourcesFiles[i];
    string sourceFileName = name + ".ai";

    using (AiImage image = (AiImage)Image.Load(sourceFileName))
    {
        string outFileName = name + ".psd";
        ImageOptionsBase options = new PsdOptions();
        image.Save(outFileName, options);

        outFileName = name + ".png";
        options = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
        image.Save(outFileName, options);

        outFileName = name + ".jpg";
        options = new JpegOptions() { Quality = 85 };
        image.Save(outFileName, options);

        outFileName = name + ".gif";
        options = new GifOptions() { DoPaletteCorrection = false };
        image.Save(outFileName, options);

        outFileName = name + ".tif";
        options = new TiffOptions(TiffExpectedFormat.TiffDeflateRgba);
        image.Save(outFileName, options);
    }
}
```

### انظر أيضًا

* class [Image](../../aspose.psd/image/)
* namespace [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../)


