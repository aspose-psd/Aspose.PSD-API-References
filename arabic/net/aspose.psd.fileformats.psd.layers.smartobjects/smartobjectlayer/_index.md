---
title: Class SmartObjectLayer
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.SmartObjects.SmartObjectLayer فصل. يحدد فئة SmartObjectLayer التي تحتوي على ملف PSD أو كائن ذكي مرتبط في الملف الخارجي. باستخدام الكائنات الذكية  يمكنك إجراء تحويلات غير مدمرة. يمكنك تغيير مقياس طبقة أو تدويرها أو إمالتها أو تشويهها أو تحويل منظورها أو التواء إلى layer دون فقد بيانات الصورة الأصلية أو جودتها لأن التحويلات لا تؤثر على البيانات الأصلية . العمل مع البيانات المتجهة  مثل العمل الفني المتجه من Illustrator  وإلا سيتم تنقيطه . إجراء تصفية غير مدمرة. يمكنك تحرير المرشحات المطبقة على Smart Objects في أي وقت. تحرير كائن ذكي واحد وتحديث جميع مثيلاته المرتبطة تلقائيًا . قم بتطبيق قناع طبقة مرتبط أو غير مرتبط بطبقة الكائن الذكي. صور العناصر النائبة للدقة التي قمت باستبدالها لاحقًا بالإصدارات النهائية . في Adobe Photoshop  يمكنك تضمين محتويات صورة في مستند PSD . مزيد من المعلومات هناhttps//helpx.adobe.com/photoshop/using/createsmartobjects.html تحتوي الطبقة التي تحتوي على كائن ذكي مضمن على موارد موضوعة PlLd و SoLd بخصائص كائن ذكية . يمكن أن يكون مورد PlLd منفردًا لإصدارات PSD الأقدم ثم 10. تحتوي هذه الموارد على UniqueId من LiFdDataSource في Lnk2Resource العام مع العنصر المضمن filename والمعلمات الأخرى  بما في ذلك محتويات الملف المضمنة في التنسيق الأصلي كمصفوفة بايت.
type: docs
weight: 3490
url: /ar/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---
## SmartObjectLayer class

يحدد فئة SmartObjectLayer التي تحتوي على ملف PSD أو كائن ذكي مرتبط في الملف الخارجي. باستخدام الكائنات الذكية ، يمكنك: إجراء تحويلات غير مدمرة. يمكنك تغيير مقياس طبقة أو تدويرها أو إمالتها أو تشويهها أو تحويل منظورها أو التواء إلى layer دون فقد بيانات الصورة الأصلية أو جودتها لأن التحويلات لا تؤثر على البيانات الأصلية . العمل مع البيانات المتجهة ، مثل العمل الفني المتجه من Illustrator ، وإلا سيتم تنقيطه . إجراء تصفية غير مدمرة. يمكنك تحرير المرشحات المطبقة على Smart Objects في أي وقت. تحرير كائن ذكي واحد وتحديث جميع مثيلاته المرتبطة تلقائيًا . قم بتطبيق قناع طبقة مرتبط أو غير مرتبط بطبقة الكائن الذكي. صور العناصر النائبة للدقة التي قمت باستبدالها لاحقًا بالإصدارات النهائية . في Adobe� Photoshop� ، يمكنك تضمين محتويات صورة في مستند PSD . مزيد من المعلومات هنا:[https://helpx.adobe.com/photoshop/using/create-smart-objects.html](https://helpx.adobe.com/photoshop/using/create-smart-objects.html) تحتوي الطبقة التي تحتوي على كائن ذكي مضمن على موارد موضوعة (PlLd) و SoLd بخصائص كائن ذكية . يمكن أن يكون مورد PlLd منفردًا لإصدارات PSD الأقدم ثم 10. تحتوي هذه الموارد على UniqueId من LiFdDataSource في Lnk2Resource العام مع العنصر المضمن filename والمعلمات الأخرى ، بما في ذلك محتويات الملف المضمنة في التنسيق الأصلي كمصفوفة بايت.

```csharp
public class SmartObjectLayer : Layer
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت لوحة الضبط التلقائي. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية . |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | الحصول على عدد بتات الصورة لكل بكسل . |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | يحصل على خيارات المزج . |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | الحصول على أو تعيين مفتاح وضع المزج. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | الحصول على توقيع وضع المزج. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | الحصول على أو تحديد موضع الطبقة السفلية. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | يحصل على حدود الصورة . |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | الحصول على معلومات القناة أو تعيينها . |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | الحصول على عدد قنوات الطبقة . |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | الحصول على أو تعيين قص الطبقة. 0 = قاعدة ، 1 = غير أساسية . |
| [Container](../../aspose.psd/image/container/) { get; } | يحصل على ملف[`Image`](../../aspose.psd/image/) حاوية . |
| [Contents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/) { get; set; } | الحصول على أو تعيين محتويات طبقة الكائن الذكي. محتويات الكائن الذكي المضمنة هي ملف الصورة الخام المضمن:[`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) وخصائصه . محتويات الكائن الذكي المرتبط هي المحتوى الأولي لملف الصورة المرتبط إذا كان متاحًا وخصائصه:[`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . لا ندعم التحميل من Adobe� Photoshop� �� مكتبة الرسومات عندما[`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) هو true . بالنسبة لملفات الارتباط العادية ، نستخدم في البداية[`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) للبحث عن الملف نسبيًا في مسار الصورة المصدرSourceImagePath ، إذا لم يكن متوفرًا ننظر إليه[`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) ، إذا لم يكن كذلك ، فنحن نبحث عن ملف الارتباط في نفس الدليل حيث توجد صورتنا:SourceImagePath . |
| [ContentsBounds](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentsbounds/) { get; set; } | الحصول على أو تعيين حدود محتوى الكائن الذكي. |
| [ContentsSource](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentssource/) { get; set; } | الحصول على أو تعيين مصدر محتوى الكائن الذكي. |
| [ContentType](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contenttype/) { get; } | يحصل على نوع محتوى طبقة الكائن الذكي . محتويات الكائن الذكي المضمنة هي ملف الصورة الخام المضمن:[`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) . محتويات الكائن الذكي المرتبط هي المحتويات الأولية لملف الصورة المرتبط إذا كان متاحًا:[`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . لا ندعم التحميل من Adobe� Photoshop� �� مكتبة الرسومات عندما[`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) هو true . بالنسبة لملفات الارتباط العادية ، نستخدم في البداية[`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) للبحث عن الملف نسبيًا في مسار الصورة المصدرSourceImagePath ، إذا لم يكن متوفرًا ننظر إليه[`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) ، إذا لم يكن كذلك ، فنحن نبحث عن ملف الارتباط في نفس الدليل حيث توجد صورتنا:SourceImagePath . |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | يحصل على دفق بيانات الكائن. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | الحصول على أو تحديد اسم عرض الطبقة. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | الحصول على طول معلومات الطبقة الإضافي بالبايت. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | يحصل على قيمة تنسيق الملف |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | الحصول على أو تعيين حشو الطبقة. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | الحصول على أو تعيين تعتيم التعبئة. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | الحصول على إشارات الطبقة أو تعيينها. بت 0 = الشفافية المحمية ؛ بت 1 = مرئي ؛ بت 2 = عفا عليها الزمن ؛ بت 3 = 1 لـ Photoshop 5.0 والإصدارات الأحدث ، تخبر ما إذا كانت البتة 4 تحتوي على معلومات مفيدة ؛ بت 4 = بيانات البكسل غير ذات الصلة بمظهر المستند. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل يحتوي على alpha. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | يحصل على قيمة تشير إلى ما إذا كانت الصورة ذات لون شفاف. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | الحصول على ارتفاع الصورة . |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | الحصول على أو تعيين الدقة الأفقية ، بالبكسل في البوصة ، لهذا[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | يحصل على عتامة هذه الصورة . |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين شاشة المقاطعة. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الأولية متاحًا. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الطبقة مرئية |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل مرئيًا في المجموعة (إذا لم تكن الطبقة في مجموعة فهذا يعني مجموعة الجذر). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | الحصول على أو تعيين بيانات نطاقات مزج الطبقة. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | الحصول على أو تحديد وقت تاريخ إنشاء الطبقة. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | الحصول على قفل الطبقة أو تعيينه. لاحظ أنه إذا تم تعيين العلامة LayerFlags.TransparencyProtected ، فسيتم استبدالها بعلامة قفل الطبقة. |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | الحصول على أو تعيين بيانات قناع الطبقة. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | يحصل على خيارات الطبقة . |
| [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | الحصول على أو تحديد موضع الطبقة اليسرى. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | الحصول على الطول الكلي للطبقة بالبايت. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | الحصول على أو تحديد اسم الطبقة. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | الحصول على أو تحديد عتامة الطبقة. 0 = شفاف ، 255 = معتم . |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | الحصول على لوحة الألوان أو تعيينها. لا يتم استخدام لوحة الألوان عندما يتم تمثيل وحدات البكسل مباشرةً. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يجب مضاعفة مكونات الصورة مسبقًا. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | الحصول على أو تعيين محول الألوان المخصص |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | يحصل على تنسيق البيانات الأولية . |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | يحصل على إعدادات البيانات الأولية الحالية. ملاحظة عند استخدام هذه الإعدادات ، يتم تحميل البيانات بدون تحويل. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | الحصول على الفهرس الاحتياطي أو تعيينه لاستخدامه عندما يكون فهرس اللوحة خارج الحدود |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | الحصول على أو تعيين محول الألوان المفهرس |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | الحصول على حجم الخط الخام بالبايت. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | الحصول على موارد الطبقة أو تعيينها. |
| [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | الحصول على أو تحديد موضع الطبقة الصحيح. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | الحصول على أو تعيين تمييز لون الورقة الزخرفية في قائمة الطبقات |
| [Size](../../aspose.psd/image/size/) { get; } | يحصل على حجم الصورة . |
| [SmartFilters](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartfilters/) { get; } | الحصول على المرشحات الذكية. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartobjectprovider/) { get; } | يحصل على موفر الكائن الذكي. |
| [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | الحصول على أو تحديد موضع الطبقة العليا. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | الحصول على لون شفاف للصورة . |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان سيتم تحديث بيانات تعريف XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان سيتم استخدام تحميل البيانات الأولية عند توفر تحميل البيانات الأولية. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | الحصول على أو تحديد الدقة الرأسية ، بالبكسل في البوصة ، لهذا[`RasterImage`](../../aspose.psd/rasterimage/) . |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | الحصول على عرض الصورة . |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | الحصول على بيانات تعريف XMP أو تعيينها. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | يضيف القناع إلى الطبقة الحالية. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | ضبط سطوع الصورة . |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | تباين الصورة |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | تصحيح جاما لصورة . |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | تصحيح جاما لصورة . |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | ثنائية الصورة باستخدام خوارزمية العتبة التكيفية لبرادلي باستخدام عتبة الصورة المتكاملة |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | ثنائية الصورة باستخدام خوارزمية العتبة التكيفية لبرادلي باستخدام عتبة الصورة المتكاملة |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | ثنائية الصورة مع عتبة محددة مسبقًا |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | ثنائية الصورة مع عتبة Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | يخزن البيانات ويضمن عدم إجراء أي تحميل إضافي للبيانات من الأساس[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بتنسيق الملف المحدد الذي تم تمثيله بواسطة خيارات الحفظ التي تم تمريرها. |
| [ConvertToLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/converttolinked/)(string) | يحول هذا الكائن الذكي المضمن إلى كائن ذكي مرتبط. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | قص الصورة. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | اقتصاص الصورة مع التحولات . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | التخلص من المثيل الحالي. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | يقوم بالتردد على الصورة الحالية. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | يقوم بالتردد على الصورة الحالية. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | يرسم الصورة على الطبقة . |
| [DuplicateLayer](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/)() | ينشئ طبقة كائن ذكية جديدة عن طريق نسخ هذه الطبقة. لاحظ أنه بالنسبة للكائنات الذكية المضمنة ، تتم مشاركة الصورة المضمنة. إذا كنت تريد نسخ استخدام الصورة المضمنة[`NewSmartObjectViaCopy`](./newsmartobjectviacopy/) طريقة . |
| [EmbedLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/embedlinked/)() | يدمج الكائن الذكي المرتبط في هذه الطبقة. |
| [ExportContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/exportcontents/)(string) | لتصدير المحتويات المضمنة أو المرتبطة إلى ملف. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | يقوم بتصفية المستطيل المحدد . |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | الحصول على صورة ARGB بكسل 32 بت . |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | الحصول على صفيف ARGB بكسل الافتراضي 32 بت. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | الحصول على مصفوفة البكسل الافتراضية باستخدام محمل البكسل الجزئي. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الأولية الافتراضية. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | يحصل على مصفوفة البيانات الأولية الافتراضية باستخدام محمل البكسل الجزئي. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | إرجاع رمز تجزئة لهذا المثال. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | الحصول على تاريخ ووقت آخر تعديل لصورة المورد. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | الحصول على الخيارات بناءً على إعدادات الملف الأصلية. يمكن أن يكون هذا مفيدًا في الحفاظ على عمق البت والمعلمات الأخرى للصورة الأصلية دون تغيير . على سبيل المثال ، إذا قمنا بتحميل صورة PNG أبيض وأسود مع 1 بت لكل بكسل ثم احفظه باستخدام the [`Save`](../../aspose.psd/datastreamsupporter/save/) الطريقة ، سيتم إنتاج صورة PNG الناتجة بمعدل 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بمعدل 1 بت لكل بكسل ، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة وتمريرها إلى[`Save`](../../aspose.psd/image/save/)الطريقة كمعامل ثاني. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | الحصول على بكسل صورة . |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | الحصول على زاوية الانحراف. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا ، لتحديد زاوية الانحراف عند المسح. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | تحويل الصورة إلى تمثيلها بالتدرج الرمادي |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | تحميل 32 بت ARGB بكسل . |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | تحميل 64 بت ARGB بكسل . |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | تحميل وحدات البكسل بتنسيق CMYK . |
| [LoadContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/loadcontents/)(LoadOptions) | الحصول على محتويات الصورة المضمنة أو المرتبطة لطبقة الكائن الذكي. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | تحميل 32 بت ARGB بكسل جزئيًا بواسطة الحزم. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | تحميل وحدات البكسل جزئيًا بالحزم . |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | تحميل بكسل . |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | تحميل البيانات الأولية . |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | تحميل البيانات الأولية . |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto/)(Layer) | يدمج الطبقة في layer |
| [NewSmartObjectViaCopy](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/)() | يُنشئ طبقة كائن ذكية جديدة من خلال التعامل مع هذه الطبقة. إعادة إنتاج `Layer -&gt; Smart Objects -&gt; New Smart Object عبر وظيفة Copy` في Adobe� Photoshop�. لاحظ أنه تم تمكينها فقط للكائنات الذكية المضمنة لأن الصورة المضمنة يتم أيضًا نسخه . إذا كنت تريد مشاركة استخدام الصورة المضمنة[`DuplicateLayer`](./duplicatelayer/) طريقة . |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | تطبيع الزاوية. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من المسح المنحرف . تستخدم هذه الطريقة[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) و[`Rotate`](../../aspose.psd/rasterimage/rotate/) الأساليب . |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | تطبيع الزاوية. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من المسح المنحرف . تستخدم هذه الطريقة[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) و[`Rotate`](../../aspose.psd/rasterimage/rotate/) الأساليب . |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | يقرأ خط المسح بالكامل بواسطة فهرس خط المسح المحدد. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | يقرأ خط المسح بالكامل بواسطة فهرس خط المسح المحدد. |
| [RelinkToFile](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/relinktofile/)(string) | إعادة ربط الكائن الذكي المرتبط بملف جديد. ليست هناك حاجة لاستدعاء طريقة UpdateModifiedContent بعد ذلك. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | يستبدل لونًا بآخر بالاختلاف المسموح به ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف المتجانسة. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | يستبدل لونًا بآخر بالاختلاف المسموح به ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف المتجانسة. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents)(Image) | يستبدل محتويات الكائن الذكي المضمنة في طبقة الكائن الذكي. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_2)(string) | يستبدل المحتويات بملف . ليست هناك حاجة لاستدعاء طريقة UpdateModifiedContent بعد ذلك. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_1)(Image, ResolutionSetting) | يستبدل محتويات الكائن الذكي المضمنة في طبقة الكائن الذكي. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_3)(string, ResolutionSetting) | يستبدل المحتويات بملف . ليست هناك حاجة لاستدعاء طريقة UpdateModifiedContent بعد ذلك. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | يستبدل كل الألوان غير الشفافة بلون جديد ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف الناعمة . ملاحظة: إذا كنت تستخدمها على صور بدون شفافية ، فسيتم استبدال كل الألوان بأخرى. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | يستبدل كل الألوان غير الشفافة بلون جديد ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف الناعمة . ملاحظة: إذا كنت تستخدمها على صور بدون شفافية ، فسيتم استبدال كل الألوان بأخرى. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | يغير حجم الصورة. الافتراضيLeftTopToLeftTopيستخدم . |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | تغيير حجم الصورة . |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | تغيير حجم الصورة . |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | يغير حجم الارتفاع بشكل متناسب . |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | يغير حجم الارتفاع بشكل متناسب . |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | يغير حجم الارتفاع بشكل متناسب . |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | يغير حجم العرض بشكل متناسب . |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | يغير حجم العرض بشكل متناسب . |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | يغير حجم العرض بشكل متناسب . |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | تدوير الصورة حول المركز . |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | تدوير الصورة حول المركز . |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | يقوم بتدوير الصورة أو قلبها أو تدويرها وقلبها. |
| [Save](../../aspose.psd/image/save/)() | يحفظ بيانات الصورة في التدفق الأساسي. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | يحفظ بيانات الكائن في الدفق المحدد. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | يحفظ بيانات الكائن في موقع الملف المحدد. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | يحفظ بيانات الكائن في موقع الملف المحدد. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | يحفظ 32 بت ARGB بكسل . |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | يحفظ البكسل . |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | يحفظ البكسل . |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | يحفظ البيانات الأولية . |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | يضبط صورة ARGB بكسل 32 بت للوضع المحدد. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | يضبط لوحة الصور . |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | يضبط بكسل الصورة للوضع المحدد. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | يضبط الدقة لهذا الغرض[`RasterImage`](../../aspose.psd/rasterimage/) . |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | لإنشاء نسخة سطحية من الطبقة الحالية. من فضلك[https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) للشرح . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | تحويل الصورة النقطية إلى الصورة النقطية. |
| [UpdateModifiedContent](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/updatemodifiedcontent/)() | يقوم بتحديث ذاكرة التخزين المؤقت لصورة طبقة الكائن الذكي بالمحتوى المعدل. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | يكتب خط المسح بالكامل إلى فهرس خط المسح المحدد. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | يكتب خط المسح بالكامل إلى فهرس خط المسح المحدد. |

### أمثلة

يوضح الكود التالي دعم الكائنات الذكية المضمنة.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// يوضح هذا المثال كيفية تغيير طبقة الكائن الذكي في ملف PSD وتصدير / تحديث المحتويات المضمنة الأصلية للكائن الذكي.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // لنقوم بتصدير صورة الكائن الذكي المضمنة من طبقة الكائن الذكي PSD
        smartObjectLayer.ExportContents(exportPath);

        // دعنا نتحقق مما إذا تم حفظ الصورة الأصلية بشكل صحيح
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // لنقلب صورة الكائن الذكية الأصلية
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // لنستبدل صورة الكائن الذكي المضمنة في طبقة PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // دعنا نتحقق مما إذا تم حفظ الصورة المحدثة بشكل صحيح
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### أنظر أيضا

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* class [SmartObjectProvider](../../aspose.psd.fileformats.psd/smartobjectprovider/)
* class [LinkDataSource](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../aspose.psd.fileformats.psd.layers.smartobjects/)
* المجسم [Aspose.PSD](../../)


