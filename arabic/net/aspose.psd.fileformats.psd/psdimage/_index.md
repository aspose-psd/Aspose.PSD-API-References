---
title: "الفئة PsdImage"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.PsdImage. تُعرّف فئة PsdImage التي توفر القدرة على تحميل وتحرير وحفظ ملفات PSD بالإضافة إلى تحديث الخصائص وإضافة العلامات المائية وإجراء عمليات رسومية أو تحويل تنسيق ملف إلى آخر. يدعم Aspose.PSD الاستيراد كطبقة والتصدير إلى الصيغ التالية Png Jpeg Jpeg2000 Gif Bmp Tiff Psd Psb بالإضافة إلى التصدير إلى Pdf مع نص قابل للتحديد."
type: docs
weight: 4050
url: /ar/net/aspose.psd.fileformats.psd/psdimage/
---
{{< psd/tize >}}
## PsdImage class

يحدد فئة PsdImage التي توفر القدرة على تحميل وتحرير وحفظ ملفات PSD بالإضافة إلى تحديث الخصائص، إضافة علامات مائية، تنفيذ عمليات رسومية أو تحويل تنسيق ملف إلى آخر. يدعم Aspose.PSD الاستيراد كطبقة والتصدير إلى الصيغ التالية: PNG، JPEG، JPEG2000، GIF، BMP، TIFF، PSD، PSB بالإضافة إلى التصدير إلى PDF مع نص قابل للتحديد

```csharp
public sealed class PsdImage : RasterCachedImage
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | ينشئ مثيلًا جديدًا من الفئة `PsdImage` من صورة نقطية موجودة (ليست صورة psd) باستخدام وضع اللون RGB مع 4 قنوات 8 بت/قناة دون ضغط. |
| [PsdImage](psdimage/#constructor_4)(Stream) | ينشئ مثيلًا جديدًا من الفئة `PsdImage` من المسار المحدد لصورة نقطية (ليست صورة psd في تدفق). يُستخدم لتهيئة صورة psd بالمعلمات الافتراضية - وضع اللون - rgb، 4 قنوات، 8 بت لكل قناة، الضغط - Raw. |
| [PsdImage](psdimage/#constructor_6)(string) | ينشئ مثيلًا جديدًا من الفئة `PsdImage` من المسار المحدد لصورة نقطية (ليست صورة psd في المسار). يُستخدم لتهيئة صورة psd بالمعلمات الافتراضية - وضع اللون - rgb، 4 قنوات، 8 بت لكل قناة، الضغط - Raw. |
| [PsdImage](psdimage/#constructor_2)(int, int) | ينشئ مثيلًا جديدًا من الفئة `PsdImage` بالعرض والارتفاع المحددين. يُستخدم لتهيئة صورة psd فارغة. |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | ينشئ مثيلًا جديدًا من الفئة `PsdImage` من صورة نقطية موجودة (ليست صورة psd) باستخدام معلمات المُنشئ. |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | ينشئ مثيلًا جديدًا من الفئة `PsdImage` من المسار المحدد لصورة نقطية (ليست صورة psd في تدفق) باستخدام معلمات المُنشئ. |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | ينشئ مثيلًا جديدًا من الفئة `PsdImage` من المسار المحدد لصورة نقطية (ليست صورة psd في المسار) باستخدام معلمات المُنشئ. |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | ينشئ مثيلًا جديدًا من الفئة `PsdImage` بالعرض والارتفاع والـ paletter ووضع اللون وعدد القنوات وطول بت القنوات ومعلمات وضع الضغط المحددة. يُستخدم لتهيئة صورة psd فارغة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | يحصل أو يعيّن الطبقة النشطة. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | يحصل أو يعيّن قيمة للون الخلفية. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | يحصل على عدد البتات لكل قناة. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | يحصل على عدد البتات في كل بكسل للصورة. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | يحصل على حدود الصورة. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | يحصل على عدد قنوات PSD. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | يحصل أو يعيّن ملف تعريف اللون CMYK لصور PSD بنظام CMYK. يجب أن يكون مقترنًا بـ RgbColorProfile للتحويل اللوني الصحيح. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | يحصل أو يعيّن وضع اللون. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | يحصل على طريقة الضغط. |
| [Container](../../aspose.psd/image/container/) { get; } | يحصل على حاوية [`Image`](../../aspose.psd/image/). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | يحصل على تدفق بيانات الكائن. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | يحصل على قيمة تنسيق الملف |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | يحصل أو يضبط الزاوية العامة. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | يحصل على معلومات قناع الطبقة العامة. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | يحصل أو يعيّن موارد الطبقة العامة. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | يحصل أو يعيّن ملف تعريف اللون GRAY (أحادي اللون) لصور PSD بتدرج الرمادي. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | يحصل أو يضبط الدقة العمودية، بوحدات البكسل لكل بوصة، لهذا [`RasterImage`](../../aspose.psd/rasterimage/). |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت قناة ألفا الأولى تحتوي على بيانات الشفافية للنتيجة المدمجة عند تحديد بيانات الطبقات. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | يحصل على قيمة تشير إلى ما إذا كانت الصورة لها لون شفاف. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | يحصل على ارتفاع الصورة. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | يحصل أو يعيّن الدقة الأفقية، بوحدة بكسل لكل بوصة، لهذا `PsdImage`. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | يحصل على شفافية هذه الصورة. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | يحصل أو يعيّن موارد صورة PSD. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | يحصل أو يضبط مراقب المقاطعة. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت صورة psd مسطحة. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | يحصل أو يضبط طبقات PSD. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | يحصل على مدير الطبقات المرتبطة. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | يحصل أو يضبط لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرة. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | يحصل أو يضبط محول اللون المخصص |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | يحصل على تنسيق البيانات الخام. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | يحصل على إعدادات البيانات الخام الحالية. ملاحظة عند استخدام هذه الإعدادات يتم تحميل البيانات دون تحويل. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | يحصل أو يضبط فهرس الاحتياطي للاستخدام عندما يكون فهرس لوحة الألوان خارج النطاق |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | يحصل أو يضبط محول اللون المفهرس |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | يحصل على حجم السطر الخام بالبايت. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | يحصل أو يضبط ملف تعريف اللون RGB لصور PSD بنظام CMYK. يجب أن يكون مقترناً بـ CmykColorProfile للتحويل اللوني الصحيح. |
| [Size](../../aspose.psd/image/size/) { get; } | يحصل على حجم الصورة. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | يحصل على موفر الكائن الذكي. |
| [Timeline](../../aspose.psd.fileformats.psd/psdimage/timeline/) { get; } | يحصل على [`Timeline`](./timeline/) لهذا `PsdImage`. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | يحصل على لون شفافية الصورة. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب تحديث بيانات التعريف XMP. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | يحصل أو يضبط الإصدار. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | يحصل أو يضبط الدقة العمودية، بوحدة البكسل لكل بوصة، لهذا `PsdImage`. |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | يحصل على عرض الصورة. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | يحصل أو يضبط بيانات التعريف XMP. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | يضيف طبقة تعديل الأبيض والأسود. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | يضيف طبقة تعديل السطوع/التباين. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | يضيف طبقة تعديل خالط القنوات بالمعلمات الافتراضية |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | يضيف طبقة تعديل توازن الألوان. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | يضيف طبقة تعديل المنحنيات. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | يضيف طبقة تعديل التعرض. |
| [AddGradientMapAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/)() | يضيف طبقة تعديل خريطة التدرج. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | يضيف طبقة تعديل الصبغة/التشبع. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | يضيف طبقة تعديل عكس. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | يضيف الطبقة. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | يضيف مجموعة الطبقة. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | يضيف طبقة تعديل المستويات. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | يضيف طبقة مرشح الصورة. |
| [AddPosterizeAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/)() | يضيف طبقة تعديل تقليل الألوان. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | يضيف طبقة عادية جديدة. |
| [AddSelectiveColorAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addselectivecoloradjustmentlayer/)() | يضيف طبقة تعديل اللون الانتقائي. |
| [AddShapeLayer](../../aspose.psd.fileformats.psd/psdimage/addshapelayer/)() | أضف طبقة شكل فارغة. بدون مسارات. يجب إضافتها إلى طبقة الشكل قبل الحفظ. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | يضيف طبقة نص جديدة. |
| [AddThresholdAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/)() | يضيف طبقة تعديل العتبة. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | يضيف طبقة تعديل الحيوية. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | ضبط السطوع للصورة. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | تباين الصورة |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | تصحيح غاما للصورة. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | تصحيح غاما للصورة. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | تحويل الصورة إلى ثنائية باستخدام عتبة معرفة مسبقًا |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | تحويل الصورة إلى ثنائية باستخدام تحديد العتبة بطريقة أوتسو |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل أي بيانات إضافية من الـ [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد للملف الممثل بخيارات الحفظ الممررة. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | يحوّل تنسيق هذه الصورة إلى التنسيق المحدد في الخيارات. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | قص الصورة. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | قص الصورة مع إزاحات. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | يقوم بتطبيق التدرج النقطي على الصورة الحالية. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | يقوم بتطبيق التدرج النقطي على الصورة الحالية. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | يفلتر المستطيل المحدد. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | يقوم بتسوية جميع الطبقات. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | يحصل على بكسل صورة 32-بت ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | يحصل على مصفوفة بكسلات 32-بت ARGB الافتراضية. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل بكسل جزئي. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل بكسل جزئي. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../../aspose.psd/datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومرّرها إلى طريقة [`Save`](../../aspose.psd/image/save/) كمعامل ثانٍ. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | يحصل على بكسل صورة. تحذير أداء: تجنّب استخدام هذه الطريقة للتنقل عبر جميع بكسلات الصورة لأنها قد تؤدي إلى مشاكل أداء كبيرة. للحصول على معالجة بكسلات أكثر كفاءة، استخدم طريقة `LoadArgb32Pixels` لاسترجاع مصفوفة البكسلات بالكامل في آن واحد. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | يحصل على زاوية الميل. تُطبق هذه الطريقة على مستندات النص الممسوحة ضوئيًا لتحديد زاوية الميل أثناء المسح. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | يقوم بتحميل بكسلات ARGB 32‑بت. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | يقوم بتحميل بكسلات ARGB 64‑بت. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | يقوم بتحميل البكسلات بتنسيق CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | يقوم بتحميل البكسلات بتنسيق CMYK. هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فاعلية [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/). |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | يقوم بتحميل بكسلات ARGB 32‑بت جزئياً عن طريق الحزم. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | يقوم بتحميل البكسلات جزئياً عن طريق الحزم. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | يقوم بتحميل البكسلات. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | يقوم بتحميل البيانات الخام. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | يقوم بتحميل البيانات الخام. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | يدمج الطبقات. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | يقوم بتطبيع الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف. تستخدم هذه الطريقة الطرق [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) و [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | يقوم بتطبيع الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف. تستخدم هذه الطريقة الطرق [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) و [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | يقرأ كامل سطر المسح وفق فهرس سطر المسح المحدد. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | يقرأ كامل سطر المسح وفق فهرس سطر المسح المحدد. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | يعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | يعيد تحجيم الصورة. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | يعيد تحجيم الصورة. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | يعيد تحجيم الارتفاع بنسبية. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | يعيد تحجيم الارتفاع بنسبية. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | يعيد تحجيم الارتفاع بنسبية. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | يعيد تحجيم العرض بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | يعيد تحجيم العرض بنسبية. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | يعيد تحجيم العرض بنسبية. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | يدور الصورة حول المركز. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | يدور الصورة حول المركز. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | يدور أو يقلب أو يدور ويقلب الصورة. |
| [Save](../../aspose.psd/image/save/)() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | يحفظ بكسلات ARGB 32-بت. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | يحفظ البكسلات. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | يحفظ البكسلات. هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فعالية [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/) . |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | يحفظ البكسلات. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | يحفظ البيانات الخام. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | يضبط بكسل صورة ARGB 32-بت للموقع المحدد. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | يضبط لوحة ألوان الصورة. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | يضبط بكسل صورة للموقع المحدد. |
| override [SetResolution](../../aspose.psd.fileformats.psd/psdimage/setresolution/)(double, double) | يضبط الدقة لهذا `PsdImage`. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | يحوّل الصورة النقطية إلى الـ bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | يكتب السطر الكامل للمسح إلى الفهرس المحدد لسطر المسح. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | يكتب السطر الكامل للمسح إلى الفهرس المحدد لسطر المسح. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | إصدار PSD الافتراضي. |

## أمثلة

الكود التالي يوضح القدرة على تدوير الصورة بزاوية محددة.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// تدوير الصورة بالكامل
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// تدوير الطبقة
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### انظر أيضًا

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


