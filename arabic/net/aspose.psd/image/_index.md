---
title: Class Image
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Image فصل. الصورة هي الفئة الأساسية لجميع أنواع الصور.
type: docs
weight: 4590
url: /ar/net/aspose.psd/image/
---
## Image class

الصورة هي الفئة الأساسية لجميع أنواع الصور.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت لوحة الضبط التلقائي. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية . |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | الحصول على عدد بتات الصورة لكل بكسل . |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | يحصل على حدود الصورة . |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [Container](../../aspose.psd/image/container/) { get; } | يحصل على ملف`Image` حاوية . |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | يحصل على دفق بيانات الكائن. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | يحصل على قيمة تنسيق الملف |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | الحصول على ارتفاع الصورة . |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين شاشة المقاطعة. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا ولا يلزم قراءة البيانات. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | الحصول على لوحة الألوان أو تعيينها. لا يتم استخدام لوحة الألوان عندما يتم تمثيل وحدات البكسل مباشرةً. |
| [Size](../../aspose.psd/image/size/) { get; } | يحصل على حجم الصورة . |
| abstract [Width](../../aspose.psd/image/width/) { get; } | الحصول على عرض الصورة . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | لإنشاء صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | يتم تحميل صورة جديدة من التدفق المحدد. |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | يقوم بتحميل صورة جديدة من الملف المحدد. |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | يتم تحميل صورة جديدة من التدفق المحدد. |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | يقوم بتحميل صورة جديدة من الملف المحدد. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | يخزن البيانات ويضمن عدم إجراء أي تحميل إضافي للبيانات من الأساس[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بتنسيق الملف المحدد الذي تم تمثيله بواسطة خيارات الحفظ التي تم تمريرها. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | التخلص من المثيل الحالي. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | الحصول على الخيارات بناءً على إعدادات الملف الأصلية. يمكن أن يكون هذا مفيدًا في الحفاظ على عمق البت والمعلمات الأخرى للصورة الأصلية دون تغيير . على سبيل المثال ، إذا قمنا بتحميل صورة PNG أبيض وأسود مع 1 بت لكل بكسل ثم احفظه باستخدام the [`Save`](../datastreamsupporter/save/) الطريقة ، سيتم إنتاج صورة PNG الناتجة بمعدل 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بمعدل 1 بت لكل بكسل ، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة وتمريرها إلى[`Save`](./save/)الطريقة كمعامل ثاني. |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | يغير حجم الصورة. الافتراضيLeftTopToLeftTopيستخدم . |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | تغيير حجم الصورة . |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | تغيير حجم الصورة . |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | يغير حجم الارتفاع بشكل متناسب . |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | يغير حجم الارتفاع بشكل متناسب . |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | يغير حجم الارتفاع بشكل متناسب . |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | يغير حجم العرض بشكل متناسب . |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | يغير حجم العرض بشكل متناسب . |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | يغير حجم العرض بشكل متناسب . |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | يقوم بتدوير الصورة أو قلبها أو تدويرها وقلبها. |
| [Save](../../aspose.psd/image/save/#save)() | يحفظ بيانات الصورة في التدفق الأساسي. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | يحفظ بيانات الكائن في الدفق المحدد. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | يحفظ بيانات الكائن في موقع الملف المحدد. |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | يحفظ بيانات الكائن في موقع الملف المحدد. |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | يضبط لوحة الصور . |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | يحدد ما إذا كان يمكن تحميل الصورة من التدفق المحدد. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | لتحديد ما إذا كان يمكن تحميل الصورة من التدفق المحدد واختيارياً باستخدام المحدد*loadOptions* . |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واختيارياً باستخدام خيارات الفتح المحددة. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | يحصل على تنسيق الملف. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | يحصل على تنسيق الملف. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | يحصل على مستطيل يناسب الصورة الحالية. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | يحصل على مستطيل يناسب الصورة الحالية. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | الحصول على ارتفاع نسبي . |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | الحصول على عرض نسبي . |

### أمثلة

يقوم هذا المثال بإنشاء ملف صورة جديد في بعض مواقع القرص كما هو محدد بواسطة خاصية المصدر لمثيل PsdOptions. يتم تعيين العديد من الخصائص لمثيل PsdOptions قبل إنشاء الصورة الفعلية. خاصة خاصية المصدر ، التي تشير إلى موقع القرص الفعلي في هذه الحالة.

```csharp
[C#]

// أنشئ مثيلاً من PsdOptions وعيّن خصائصه المختلفة
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// قم بإنشاء مثيل لـ FileCreateSource وقم بتعيينه كمصدر لمثيل PsdOptions
// تحدد المعلمة المنطقية الثانية ما إذا كان الملف المراد إنشاؤه ثابتًا أم لا
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

// قم بإنشاء مثيل للصورة وقم بتهيئته باستخدام مثيل PsdOptions عن طريق استدعاء طريقة الإنشاء
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // القيام ببعض معالجة الصور

    // احفظ جميع التغييرات
    image.Save();
}
```

### أنظر أيضا

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


