---
title: "الفئة Layer"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.Layer. طبقة الـ psd"
type: docs
weight: 2270
url: /ar/net/aspose.psd.fileformats.psd.layers/layer/
---
{{< psd/tize >}}
## Layer class

طبقة psd.

```csharp
public class Layer : RasterCachedImage
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Layer](layer/#constructor)() | ينشئ نسخة جديدة من الفئة `Layer`. مُنشئ للتهيئة الكسولة. |
| [Layer](layer/#constructor_3)(Stream) | ينشئ نسخة جديدة من الفئة `Layer`. |
| [Layer](layer/#constructor_1)(RasterImage, bool) | ينشئ نسخة جديدة من الفئة `Layer`. |
| [Layer](layer/#constructor_2)(Rectangle, byte[], byte[], byte[], string) | ينشئ نسخة جديدة من الفئة `Layer` من مصفوفات البايت. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | يحصل أو يعيّن قيمة للون الخلفية. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | يحصل على عدد البتات في كل بكسل للصورة. |
| [BlendClippedElements](../../aspose.psd.fileformats.psd.layers/layer/blendclippedelements/) { get; set; } | يحصل أو يعيّن دمج العنصر المقصوص. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | يحصل على خيارات الدمج. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | يحصل أو يعيّن مفتاح وضع الدمج. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | يحصل على توقيع وضع الدمج. |
| virtual [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | يحصل أو يعيّن موضع الطبقة السفلية. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | يحصل على حدود الصورة. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | يحصل أو يعيّن معلومات القناة. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | يحصل على عدد قنوات الطبقة. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | يحصل أو يعيّن قص الطبقة. 0 = أساسي، 1 = غير أساسي. |
| [Container](../../aspose.psd/image/container/) { get; } | يحصل على حاوية [`Image`](../../aspose.psd/image/). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | يحصل على تدفق بيانات الكائن. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | يحصل أو يعيّن الاسم المعروض للطبقة. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | يحصل على طول معلومات الطبقة الإضافية بالبايت. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | يحصل على قيمة تنسيق الملف |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | يحصل أو يعيّن ملء الطبقة. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | يحصل أو يعيّن شفافية التعبئة. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | يحصل أو يضبط أعلام الطبقة. البت 0 = حماية الشفافية؛ البت 1 = مرئي؛ البت 2 = مهمل؛ البت 3 = 1 لبرنامج Photoshop 5.0 وما بعده، يوضح إذا كان للبت 4 معلومات مفيدة؛ البت 4 = بيانات البكسل غير ذات صلة بمظهر المستند. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة تحتوي على ألفا. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | يحصل على قيمة تشير إلى ما إذا كانت الصورة لها لون شفاف. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | يحصل على ارتفاع الصورة. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | يحصل أو يضبط الدقة الأفقية، بوحدة بكسل لكل بوصة، لهذه [`RasterImage`](../../aspose.psd/rasterimage/). |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | يحصل على شفافية هذه الصورة. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | يحصل أو يضبط مراقب المقاطعة. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الطبقة مرئية |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة مرئية في المجموعة (إذا لم تكن الطبقة في مجموعة فهذا يعني مجموعة الجذر). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | يحصل أو يضبط بيانات نطاقات دمج الطبقة. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | يحصل أو يضبط تاريخ ووقت إنشاء الطبقة. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | يحصل أو يضبط قفل الطبقة. لاحظ أنه إذا تم تعيين العلم LayerFlags.TransparencyProtected فسيتم استبداله بعلم قفل الطبقة. لإرجاع علم LayerFlags.TransparencyProtected تحتاج إلى تطبيقه على خيار الطبقة layer.Flags &#x7C;= LayerFlags.TransparencyProtected |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | يحصل أو يضبط بيانات قناع الطبقة. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | يحصل على خيارات الطبقة. |
| virtual [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | يحصل أو يضبط موضع الطبقة اليسرى. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | يحصل على الطول الكلي للطبقة بالبايت. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | يحصل أو يضبط اسم الطبقة. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | يحصل أو يضبط شفافية الطبقة. 0 = شفاف، 255 = غير شفاف. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | يحصل أو يضبط لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرة. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | يحصل أو يضبط محول اللون المخصص |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | يحصل على تنسيق البيانات الخام. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | يحصل على إعدادات البيانات الخام الحالية. ملاحظة عند استخدام هذه الإعدادات يتم تحميل البيانات دون تحويل. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | يحصل أو يضبط فهرس الاحتياطي للاستخدام عندما يكون فهرس لوحة الألوان خارج النطاق |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | يحصل أو يضبط محول اللون المفهرس |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | يحصل على حجم السطر الخام بالبايت. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | يحصل أو يضبط موارد الطبقة. |
| virtual [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | يحصل أو يضبط موضع الطبقة اليمنى. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | يحصل أو يضبط تمييز لون الورقة الزخرفية في قائمة الطبقات |
| [Size](../../aspose.psd/image/size/) { get; } | يحصل على حجم الصورة. |
| virtual [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | يحصل أو يضبط موضع الطبقة العليا. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | يحصل على لون شفافية الصورة. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب تحديث بيانات التعريف XMP. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | يحصل أو يضبط الدقة العمودية، بوحدات البكسل لكل بوصة، لهذا [`RasterImage`](../../aspose.psd/rasterimage/). |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | يحصل على عرض الصورة. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | يحصل أو يضبط بيانات التعريف XMP. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | يضيف القناع إلى الطبقة الحالية. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | ضبط السطوع للصورة. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | تباين الصورة |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | تصحيح غاما للصورة. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | تصحيح غاما للصورة. |
| [ApplyLayerMask](../../aspose.psd.fileformats.psd.layers/layer/applylayermask/)() | يطبق قناع الطبقة على الطبقة، ثم يحذف القناع. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | تحويل الصورة إلى ثنائية باستخدام عتبة معرفة مسبقًا |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | تحويل الصورة إلى ثنائية باستخدام تحديد العتبة بطريقة أوتسو |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل أي بيانات إضافية من الـ [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد للملف الممثل بخيارات الحفظ الممررة. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | قص الصورة. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | قص الصورة مع إزاحات. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | يقوم بتطبيق التدرج النقطي على الصورة الحالية. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | يقوم بتطبيق التدرج النقطي على الصورة الحالية. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | يرسم الصورة على الطبقة. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | يفلتر المستطيل المحدد. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | يحصل على بكسل صورة 32-بت ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | يحصل على مصفوفة بكسلات 32-بت ARGB الافتراضية. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل بكسل جزئي. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل بكسل جزئي. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | يرجع رمز تجزئة لهذه المثيلة. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../../aspose.psd/datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومرّرها إلى طريقة [`Save`](../../aspose.psd/image/save/) كمعامل ثانٍ. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | يحصل على بكسل صورة. تحذير أداء: تجنّب استخدام هذه الطريقة للتنقل عبر جميع بكسلات الصورة لأنها قد تؤدي إلى مشاكل أداء كبيرة. للحصول على معالجة بكسلات أكثر كفاءة، استخدم طريقة `LoadArgb32Pixels` لاسترجاع مصفوفة البكسلات بالكامل في آن واحد. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | يحصل على زاوية الميل. تُطبق هذه الطريقة على مستندات النص الممسوحة ضوئيًا لتحديد زاوية الميل أثناء المسح. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | يقوم بتحميل بكسلات ARGB 32‑بت. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | يقوم بتحميل بكسلات ARGB 64‑بت. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | يقوم بتحميل البكسلات بتنسيق CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | يقوم بتحميل البكسلات بتنسيق CMYK. هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فاعلية [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/). |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | يقوم بتحميل بكسلات ARGB 32‑بت جزئياً عن طريق الحزم. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | يقوم بتحميل البكسلات جزئياً عن طريق الحزم. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | يقوم بتحميل البكسلات. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | يقوم بتحميل البيانات الخام. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | يقوم بتحميل البيانات الخام. |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto/)(Layer) | يدمج الطبقة إلى الطبقة المحددة |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | يقوم بتطبيع الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف. تستخدم هذه الطريقة الطرق [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) و [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | يقوم بتطبيع الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف. تستخدم هذه الطريقة الطرق [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) و [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | يقرأ كامل سطر المسح وفق فهرس سطر المسح المحدد. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | يقرأ كامل سطر المسح وفق فهرس سطر المسح المحدد. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | يعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | يعيد تحجيم الصورة. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | يعيد تحجيم الصورة. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | يعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | يعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | يعيد تحجيم الارتفاع بنسبية. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | يعيد تحجيم العرض بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | يعيد تحجيم العرض بنسبية. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | يعيد تحجيم العرض بنسبية. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | يدور الصورة حول المركز. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | يدور الصورة حول المركز. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | يدور أو يقلب أو يدور ويقلب الصورة. |
| [Save](../../aspose.psd/image/save/)() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/#save_1)(Stream) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/#save_7)(string, bool) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/#save_5)(string, ImageOptionsBase) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/#save_6)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | يحفظ بكسلات ARGB 32-بت. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | يحفظ البكسلات. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | يحفظ البكسلات. هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فعالية [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/) . |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | يحفظ البكسلات. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | يحفظ البيانات الخام. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | يضبط بكسل صورة ARGB 32-بت للموقع المحدد. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | يضبط لوحة ألوان الصورة. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | يضبط بكسل صورة للموقع المحدد. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | يضبط الدقة لهذا [`RasterImage`](../../aspose.psd/rasterimage/). |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | ينشئ نسخة سطحية من الطبقة الحالية. يرجى زيارة [https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) للحصول على شرح. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | يحوّل الصورة النقطية إلى الـ bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | يكتب السطر الكامل للمسح إلى الفهرس المحدد لسطر المسح. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | يكتب السطر الكامل للمسح إلى الفهرس المحدد لسطر المسح. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [BlendSignature](../../aspose.psd.fileformats.psd.layers/layer/blendsignature/) | يمثل توقيع وضع الدمج. |
| const [LayerHeaderSize](../../aspose.psd.fileformats.psd.layers/layer/layerheadersize/) | حجم رأس الطبقة. |

### انظر أيضًا

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


