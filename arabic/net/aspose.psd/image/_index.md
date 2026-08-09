---
title: "الفئة Image"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.Image. الصورة هي الفئة الأساسية لجميع أنواع الصور"
type: docs
weight: 5060
url: /ar/net/aspose.psd/image/
---
{{< psd/tize >}}
## Image class

الصورة هي الفئة الأساسية لجميع أنواع الصور.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | يحصل أو يعيّن قيمة للون الخلفية. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | يحصل على عدد البتات في كل بكسل للصورة. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | يحصل على حدود الصورة. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [Container](../../aspose.psd/image/container/) { get; } | يحصل على حاوية `Image`. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | يحصل على تدفق بيانات الكائن. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | يحصل على قيمة تنسيق الملف |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | يحصل على ارتفاع الصورة. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | يحصل أو يضبط مراقب المقاطعة. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | يحصل أو يضبط لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرة. |
| [Size](../../aspose.psd/image/size/) { get; } | يحصل على حجم الصورة. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | يحصل على عرض الصورة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | يحمّل صورة جديدة من الدفق المحدد. |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | يحمّل صورة جديدة من الملف المحدد. |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | يحمّل صورة جديدة من الدفق المحدد. |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | يحمّل صورة جديدة من الملف المحدد. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) الأساسي. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد للملف الممثل بخيارات الحفظ الممررة. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون ذلك مفيداً للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومرّرها إلى طريقة [`Save`](./save/) كمعامل ثانٍ. |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | يعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | يعيد تحجيم الصورة. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | يعيد تحجيم الصورة. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | يعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | يعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | يعيد تحجيم الارتفاع بنسبية. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | يعيد تحجيم العرض بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | يعيد تحجيم العرض بنسبية. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | يعيد تحجيم العرض بنسبية. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | يدور أو يقلب أو يدور ويقلب الصورة. |
| [Save](../../aspose.psd/image/save/#save)() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | يضبط لوحة ألوان الصورة. |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واستخدام *loadOptions* المحدد اختياريًا. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واستخدام خيارات الفتح المحددة اختياريًا. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | يحصل على تنسيق الملف. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | يحصل على تنسيق الملف. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | يحصل على ارتفاع متناسب. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | يحصل على عرض متناسب. |

## أمثلة

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

### انظر أيضًا

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


