---
title: Class VectorImage
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.VectorImage فصل. الصورة المتجهة هي الفئة الأساسية لجميع أنواع الصور المتجهة.
type: docs
weight: 5720
url: /ar/net/aspose.psd/vectorimage/
---
## VectorImage class

الصورة المتجهة هي الفئة الأساسية لجميع أنواع الصور المتجهة.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت لوحة الضبط التلقائي. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية . |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | الحصول على عدد بتات الصورة لكل بكسل . |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | يحصل على حدود الصورة . |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [Container](../../aspose.psd/image/container/) { get; } | يحصل على ملف[`Image`](../image/) حاوية . |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | يحصل على دفق بيانات الكائن. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | يحصل على قيمة تنسيق الملف |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | الحصول على ارتفاع الصورة . |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | الحصول على ارتفاع الكائن بالبوصة . |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين شاشة المقاطعة. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا ولا يلزم قراءة البيانات. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | الحصول على لوحة الألوان أو تعيينها. لا يتم استخدام لوحة الألوان عندما يتم تمثيل وحدات البكسل مباشرةً. |
| [Size](../../aspose.psd/image/size/) { get; } | يحصل على حجم الصورة . |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | الحصول على حجم الكائن بالبوصة . |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | الحصول على عرض الصورة . |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | الحصول على عرض الكائن بالبوصة . |

## طُرق

| اسم | وصف |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | يخزن البيانات ويضمن عدم إجراء أي تحميل إضافي للبيانات من الأساس[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بتنسيق الملف المحدد الذي تم تمثيله بواسطة خيارات الحفظ التي تم تمريرها. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | التخلص من المثيل الحالي. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | الحصول على الخيارات بناءً على إعدادات الملف الأصلية. يمكن أن يكون هذا مفيدًا في الحفاظ على عمق البت والمعلمات الأخرى للصورة الأصلية دون تغيير . على سبيل المثال ، إذا قمنا بتحميل صورة PNG أبيض وأسود مع 1 بت لكل بكسل ثم احفظه باستخدام the [`Save`](../datastreamsupporter/save/) الطريقة ، سيتم إنتاج صورة PNG الناتجة بمعدل 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بمعدل 1 بت لكل بكسل ، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة وتمريرها إلى[`Save`](../image/save/)الطريقة كمعامل ثاني. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | يغير حجم الصورة. الافتراضيLeftTopToLeftTopيستخدم . |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | تغيير حجم الصورة . |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | تغيير حجم الصورة . |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | يغير حجم الارتفاع بشكل متناسب . |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | يغير حجم الارتفاع بشكل متناسب . |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | يغير حجم الارتفاع بشكل متناسب . |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | يغير حجم العرض بشكل متناسب . |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | يغير حجم العرض بشكل متناسب . |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | يغير حجم العرض بشكل متناسب . |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | يقوم بتدوير الصورة أو قلبها أو تدويرها وقلبها. |
| [Save](../../aspose.psd/image/save/)() | يحفظ بيانات الصورة في التدفق الأساسي. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | يحفظ بيانات الكائن في الدفق المحدد. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | يحفظ بيانات الكائن في موقع الملف المحدد. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | يحفظ بيانات الكائن في موقع الملف المحدد. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | يضبط لوحة الصور . |

### أنظر أيضا

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


