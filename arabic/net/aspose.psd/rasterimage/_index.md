---
title: "الفئة RasterImage"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.RasterImage. تمثل صورة نقطية تدعم عمليات الرسومات النقطية"
type: docs
weight: 5820
url: /ar/net/aspose.psd/rasterimage/
---
{{< psd/tize >}}
## RasterImage class

يمثل صورة نقطية تدعم عمليات الرسومات النقطية.

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
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
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة تحتوي على ألفا. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | يحصل على قيمة تشير إلى ما إذا كانت الصورة لها لون شفاف. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | يحصل على ارتفاع الصورة. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | يحصل أو يضبط الدقة الأفقية، بوحدة البكسل لكل بوصة، لهذا `RasterImage`. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | يحصل على شفافية هذه الصورة. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | يحصل أو يضبط مراقب المقاطعة. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | يحصل أو يضبط لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرة. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | يحصل أو يضبط محول اللون المخصص |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | يحصل على تنسيق البيانات الخام. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | يحصل على إعدادات البيانات الخام الحالية. ملاحظة عند استخدام هذه الإعدادات يتم تحميل البيانات دون تحويل. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | يحصل أو يضبط فهرس الاحتياطي للاستخدام عندما يكون فهرس لوحة الألوان خارج النطاق |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | يحصل أو يضبط محول اللون المفهرس |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | يحصل على حجم السطر الخام بالبايت. |
| [Size](../../aspose.psd/image/size/) { get; } | يحصل على حجم الصورة. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | يحصل على لون شفافية الصورة. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب تحديث بيانات التعريف XMP. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | يحصل أو يضبط الدقة العمودية، بوحدة البكسل لكل بوصة، لهذا `RasterImage`. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | يحصل على عرض الصورة. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | يحصل أو يضبط بيانات التعريف XMP. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [AdjustBrightness](../../aspose.psd/rasterimage/adjustbrightness/)(int) | ضبط السطوع للصورة. |
| virtual [AdjustContrast](../../aspose.psd/rasterimage/adjustcontrast/)(float) | تباين الصورة |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma)(float) | تصحيح غاما للصورة. |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma_1)(float, float, float) | تصحيح غاما للصورة. |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley)(double) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley_1)(double, int) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة |
| virtual [BinarizeFixed](../../aspose.psd/rasterimage/binarizefixed/)(byte) | تحويل الصورة إلى ثنائية باستخدام عتبة معرفة مسبقًا |
| virtual [BinarizeOtsu](../../aspose.psd/rasterimage/binarizeotsu/)() | تحويل الصورة إلى ثنائية باستخدام تحديد العتبة بطريقة أوتسو |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) الأساسي. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد للملف الممثل بخيارات الحفظ الممررة. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop)(Rectangle) | يقص المستطيل المحدد. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop_1)(int, int, int, int) | قص الصورة مع إزاحات. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [Dither](../../aspose.psd/rasterimage/dither/#dither)(DitheringMethod, int) | يقوم بتطبيق التدرج النقطي على الصورة الحالية. |
| abstract [Dither](../../aspose.psd/rasterimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | يقوم بتطبيق التدرج النقطي على الصورة الحالية. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | يفلتر المستطيل المحدد. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | يحصل على بكسل صورة 32-بت ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | يحصل على مصفوفة بكسلات 32-بت ARGB الافتراضية. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل بكسل جزئي. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata_1)(Rectangle, IPartialRawDataLoader, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل بكسل جزئي. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومرّرها إلى طريقة [`Save`](../image/save/) كمعامل ثانٍ. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | يحصل على بكسل صورة. تحذير أداء: تجنّب استخدام هذه الطريقة للتنقل عبر جميع بكسلات الصورة لأنها قد تؤدي إلى مشاكل أداء كبيرة. للحصول على معالجة بكسلات أكثر كفاءة، استخدم طريقة `LoadArgb32Pixels` لاسترجاع مصفوفة البكسلات بالكامل في آن واحد. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | يحصل على زاوية الميل. تُطبق هذه الطريقة على مستندات النص الممسوحة ضوئيًا لتحديد زاوية الميل أثناء المسح. |
| virtual [Grayscale](../../aspose.psd/rasterimage/grayscale/)() | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | يقوم بتحميل بكسلات ARGB 32‑بت. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | يقوم بتحميل بكسلات ARGB 64‑بت. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | يقوم بتحميل البكسلات بتنسيق CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | يقوم بتحميل البكسلات بتنسيق CMYK. هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فعالية [`LoadCmyk32Pixels`](./loadcmyk32pixels/). |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | يقوم بتحميل بكسلات ARGB 32‑بت جزئياً عن طريق الحزم. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | يقوم بتحميل البكسلات جزئياً عن طريق الحزم. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | يقوم بتحميل البكسلات. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | يقوم بتحميل البيانات الخام. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata_1)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | يقوم بتحميل البيانات الخام. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle)() | يقوم بتطبيع الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئيًا للتخلص من الانحراف في المسح. تستخدم هذه الطريقة الأساليب [`GetSkewAngle`](./getskewangle/) و[`Rotate`](./rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle_1)(bool, Color) | يقوم بتطبيع الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئيًا للتخلص من الانحراف في المسح. تستخدم هذه الطريقة الأساليب [`GetSkewAngle`](./getskewangle/) و[`Rotate`](./rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | يقرأ كامل سطر المسح وفق فهرس سطر المسح المحدد. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | يقرأ كامل سطر المسح وفق فهرس سطر المسح المحدد. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor)(Color, byte, Color) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor_1)(int, byte, int) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors)(Color) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | يعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_1)(int, int, ImageResizeSettings) | يعيد تحجيم الصورة مع خيارات موسعة. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_2)(int, int, ResizeType) | يعيد تحجيم الصورة. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | يعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | يعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | يعيد تحجيم الارتفاع بنسبية. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | يعيد تحجيم العرض بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | يعيد تحجيم العرض بنسبية. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | يعيد تحجيم العرض بنسبية. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate)(float) | يدور الصورة حول المركز. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate_1)(float, bool, Color) | يدور الصورة حول المركز. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | يدور أو يقلب أو يدور ويقلب الصورة. |
| [Save](../../aspose.psd/image/save/)() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [Save](../../aspose.psd/rasterimage/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | يحفظ بكسلات ARGB 32-بت. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | يحفظ البكسلات. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | يقوم بحفظ البكسلات. هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فعالية [`SaveCmyk32Pixels`](./savecmyk32pixels/). |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | يحفظ البكسلات. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | يحفظ البيانات الخام. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | يضبط بكسل صورة ARGB 32-بت للموقع المحدد. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | يضبط لوحة ألوان الصورة. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | يضبط بكسل صورة للموقع المحدد. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | يضبط الدقة لهذا `RasterImage`. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | يحوّل الصورة النقطية إلى الـ bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | يكتب السطر الكامل للمسح إلى الفهرس المحدد لسطر المسح. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | يكتب السطر الكامل للمسح إلى الفهرس المحدد لسطر المسح. |

## أمثلة

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

### انظر أيضًا

* class [Image](../image/)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


