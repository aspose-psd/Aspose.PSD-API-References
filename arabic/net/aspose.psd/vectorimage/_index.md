---
title: "الفئة VectorImage"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.VectorImage. الصورة المتجهة هي الفئة الأساسية لجميع أنواع الصور المتجهة."
type: docs
weight: 6220
url: /ar/net/aspose.psd/vectorimage/
---
{{< psd/tize >}}
## VectorImage class

الصورة المتجهة هي الفئة الأساسية لجميع أنواع الصور المتجهة.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | يحصل أو يعيّن قيمة للون الخلفية. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | يحصل على عدد البتات في كل بكسل للصورة. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | يحصل على حدود الصورة. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [Container](../../aspose.psd/image/container/) { get; } | يحصل على حاوية [`Image`](../image/). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | يحصل على تدفق بيانات الكائن. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | يحصل على قيمة تنسيق الملف |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | يحصل على ارتفاع الصورة. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | يحصل على ارتفاع الكائن، بالبوصة. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | يحصل أو يضبط مراقب المقاطعة. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | يحصل أو يضبط لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرة. |
| [Size](../../aspose.psd/image/size/) { get; } | يحصل على حجم الصورة. |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | يحصل على حجم الكائن، بالبوصة. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | يحصل على عرض الصورة. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | يحصل على عرض الكائن، بالبوصة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) الأساسي. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد للملف الممثل بخيارات الحفظ الممررة. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومرّرها إلى طريقة [`Save`](../image/save/) كمعامل ثانٍ. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | يعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | يعيد تحجيم الصورة. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | يعيد تحجيم الصورة. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | يعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | يعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | يعيد تحجيم الارتفاع بنسبية. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | يعيد تحجيم العرض بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | يعيد تحجيم العرض بنسبية. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | يعيد تحجيم العرض بنسبية. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | يدور أو يقلب أو يدور ويقلب الصورة. |
| [Save](../../aspose.psd/image/save/)() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | يضبط لوحة ألوان الصورة. |

### انظر أيضًا

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


