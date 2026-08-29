---
title: "SmartObjectLayer"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يحدد فئة SmartObjectLayer التي تحتوي على كائن ذكي مدمج في ملف PSD أو كائن ذكي مرتبط في الملف الخارجي."
type: docs
weight: 10
url: /ar/java/com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage), [com.aspose.psd.fileformats.psd.layers.Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
```
public class SmartObjectLayer extends Layer
```

يعرّف فئة SmartObjectLayer التي تحتوي على كائن ذكي مضمّن في ملف PSD أو كائن ذكي مرتبط في ملف خارجي. باستخدام Smart Objects، يمكنك: إجراء تحويلات غير مدمرة. يمكنك التحجيم، الدوران، الإمالة، التشويه، التحويل المنظوري، أو تشويه طبقة دون فقدان بيانات الصورة الأصلية أو الجودة لأن التحويلات don\ufffdt لا تؤثر على البيانات الأصلية. العمل مع بيانات المتجهات، مثل الرسومات المتجهية من Illustrator، التي كانت ستتحول إلى نقطية otherwise. إجراء تصفية غير مدمرة. يمكنك تعديل الفلاتر المطبقة على Smart Objects في أي وقت. تعديل كائن ذكي واحد وتحديث جميع النسخ المرتبطة تلقائيًا. تطبيق قناع طبقة يكون that\ufffds إما مرتبطًا أو غير مرتبط بطبقة Smart Object. تجربة تصاميم مختلفة باستخدام صور placeholder منخفضة الدقة يمكنك استبدالها لاحقًا بالإصدارات النهائية. في Adobe\ufffd Photoshop\ufffd، يمكنك تضمين محتويات صورة داخل مستند PSD. المزيد من المعلومات هنا:   طبقة تحتوي على كائن ذكي مضمّن تحتوي على موارد placed (PlLd) و SoLd مع خصائص الكائن الذكي. يمكن أن يكون مورد PlLd منفردًا لإصدارات PSD الأقدم من 10. هذه الموارد تحتوي على UniqueId لـ LiFdDataSource في Lnk2Resource العالمي مع اسم الملف المضمّن ومعلمات أخرى، بما في ذلك محتويات الملف المضمّن بالتنسيق الأصلي كمصفوفة بايت.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SmartObjectLayer(System.IO.Stream stream)](#SmartObjectLayer-com.aspose.ms.System.IO.Stream-) | يُهيئ مثالًا جديدًا من الفئة [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [BlendSignature](#BlendSignature) | يمثل توقيع وضع المزج. |
| [BothPlacedAndSmartObjectResourcesFoundMessage_internalized](#BothPlacedAndSmartObjectResourcesFoundMessage-internalized) | رسالة العثور على كل من موارد placed و smart object. |
| [CanOnlyCopyEmbeddedSmartObjectMessage_internalized](#CanOnlyCopyEmbeddedSmartObjectMessage-internalized) | الرسالة: لا يمكنك سوى نسخ smart object مضمّن. |
| [LayerHeaderSize](#LayerHeaderSize) | حجم رأس الطبقة. |
| [NoPlacedOrSmartObjectResourceFoundMessage_internalized](#NoPlacedOrSmartObjectResourceFoundMessage-internalized) | رسالة عدم العثور على مورد placed أو smart object. |
| [OnCreate_internalized](#OnCreate-internalized) | يحدث عندما تم تحميل الصورة |
| [OnLoad_internalized](#OnLoad-internalized) | يحدث عندما تم تحميل الصورة بواسطة createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | يحدث عندما تم تحميل الصورة أو حفظها |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | يحدث عندما تم استخدام الرصيد |
| [WrongPlacedResourceIndicesMessage_internalized](#WrongPlacedResourceIndicesMessage-internalized) | رسالة مؤشرات مورد placed غير صحيحة. |
| [resources_internalized](#resources-internalized) | الموارد |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [<T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)](#-T-tryGetResource-internalized-java.lang.Class-T--T---) | يحصل على المورد المرتبط بالنوع المحدد. |
| [addLayerMask(LayerMaskData layerMask)](#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | يضيف القناع إلى الطبقة الحالية. |
| [addResource_internalized(LayerResource resource)](#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | يضيف المورد. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | ضبط السطوع للصورة. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | تباين الصورة |
| [adjustGamma(float gamma)](#adjustGamma-float-) | تصحيح غاما للصورة. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | تصحيح غاما للصورة. |
| [applyLayerMask()](#applyLayerMask--) | يطبق قناع الطبقة على الطبقة، ثم يحذف القناع. |
| [applyLayerState_internalized(LayerState layerState)](#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-) | يطبق إعداد نمط الطبقة من [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) إلى نسخة [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) الحالية. |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | يبدأ عملية تغيير الحجم. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | تحويل الصورة إلى ثنائية بعتبة محددة مسبقًا. |
| [binarizeOtsu()](#binarizeOtsu--) | تحويل الصورة إلى ثنائية باستخدام عتبة أوتو. |
| [cacheData()](#cacheData--) | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من DataStreamSupporter.DataStreamContainer الأساسي. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واختياريًا باستخدام loadOptions المحدد. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واستخدام خيارات الفتح المحددة اختياريًا. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | يحدد ما إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة. |
| [close()](#close--) | تنفذ واجهة Closable ويمكن استخدامها في عبارة try-with-resources منذ JDK 1.7. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | يحول إلى aps. |
| [convertToLinked(String linkedPath)](#convertToLinked-java.lang.String-) | يحوّل هذا smart object المضمّن إلى smart object مرتبط. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| [createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) | ينشئ النسخة الجديدة من الفئة [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [createLayerState_internalized()](#createLayerState-internalized--) | ينشئ نسخة [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) الجديدة بناءً على قيم [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) الحالية. |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(PsdHeader header, IColorPalette colorPalette, LinkedLayersRegistry linkedLayersRegistry, LayerResource[] resources)](#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-com.aspose.psd.fileformats.psd.layers.LayerResource---) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | قص الصورة. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | قص الصورة مع الإزاحات. |
| [dispose()](#dispose--) | يحرر النسخة الحالية. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | ينفذ تمويه (dithering) على الصورة الحالية. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | ينفذ تمويه (dithering) على الصورة الحالية. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [doCrop_internalized(Rectangle rectangle)](#doCrop-internalized-com.aspose.psd.Rectangle-) | قص الصورة. |
| [doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)](#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-) | يغير حجم الصورة. |
| [doResize_internalized(int newWidth, int newHeight, int resizeType)](#doResize-internalized-int-int-int-) |  |
| [doRotate(float angle, boolean resizeProportionally, Color backgroundColor)](#doRotate-float-boolean-com.aspose.psd.Color-) |  |
| [doRotateFlip_internalized(int rotateFlipType)](#doRotateFlip-internalized-int-) | يدور، يقلب، أو يدور ويقلب الصورة. |
| [drawImage(Point location, RasterImage image)](#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-) | يرسم الصورة على الطبقة. |
| [duplicateLayer()](#duplicateLayer--) | ينشئ طبقة smart object جديدة عن طريق نسخ هذه. |
| [embedLinked()](#embedLinked--) | يقوم بدمج الكائن الذكي المرتبط في هذه الطبقة. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد يساوي هذه النسخة. |
| [exportContents(String filePath)](#exportContents-java.lang.String-) | يصدّر المحتويات المدمجة أو المرتبطة إلى ملف. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | يفلتر المستطيل المحدد. |
| [findAssignableResource_internalized(System.Type type)](#findAssignableResource-internalized-com.aspose.ms.System.Type-) | يجد المورد القابل للتعيين. |
| [findPattResource_internalized()](#findPattResource-internalized--) | يجد PattResource |
| [findResource_internalized(int typeToolKey)](#findResource-internalized-int-) | يجد المورد بالمفتاح الفريد |
| [getAbsoluteBounds_internalized()](#getAbsoluteBounds-internalized--) | يحصل أو يضبط الحدود المطلقة. |
| [getAllowWarpRepaint_internalized()](#getAllowWarpRepaint-internalized--) | يحصل أو يعيّن تشويه العرض أو يستخدم صورة PS. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | يحصل على بكسل صورة 32-بت ARGB. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | يحصل على قيمة تشير إلى ما إذا كان تعديل اللوحة تلقائيًا. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على أو يعيّن قيمة للون الخلفية. |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد البتات لكل بكسل في الصورة. |
| [getBlendClippedElements()](#getBlendClippedElements--) | يحصل على أو يعيّن دمج العنصر المقصوص. |
| [getBlendModeKey()](#getBlendModeKey--) | يحصل على أو يعيّن مفتاح وضع الدمج. |
| [getBlendModeSignature()](#getBlendModeSignature--) | يحصل على توقيع وضع الدمج. |
| [getBlendingOptions()](#getBlendingOptions--) | يحصل على خيارات الدمج. |
| [getBottom()](#getBottom--) | يحصل على أو يعيّن موضع الطبقة السفلية. |
| [getBounds()](#getBounds--) | يحصل على حدود الصورة. |
| [getBufferSizeHint()](#getBufferSizeHint--) | يحصل على تلميح حجم المخزن المؤقت الذي يُعرّف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [getBytesPerRowForFullMask_internalized(int bitDepth)](#getBytesPerRowForFullMask-internalized-int-) | يحصل على عدد البايتات لكل صف في وضع القناع الكامل. |
| [getBytesPerRowForMask_internalized(int bitDepth)](#getBytesPerRowForMask-internalized-int-) | يحصل على عدد البايتات لكل صف. |
| [getBytesPerRow_internalized(int bitDepth)](#getBytesPerRow-internalized-int-) | يحصل على عدد البايتات لكل صف. |
| [getChannelInformation()](#getChannelInformation--) | يحصل على أو يعيّن معلومات القناة. |
| [getChannelsCount()](#getChannelsCount--) | يحصل على عدد قنوات الطبقة. |
| [getClass()](#getClass--) |  |
| [getClipping()](#getClipping--) | يحصل على أو يعيّن قص الطبقة. |
| [getContainer()](#getContainer--) | يحصل على حاوية الصورة. |
| [getContentType()](#getContentType--) | يحصل على نوع محتوى طبقة الكائن الذكي. |
| [getContents()](#getContents--) | يحصل أو يعيّن محتويات طبقة الكائن الذكي. |
| [getContentsBounds()](#getContentsBounds--) | يحصل أو يعيّن حدود محتوى الكائن الذكي. |
| [getContentsSource()](#getContentsSource--) | يحصل أو يعيّن مصدر محتوى الكائن الذكي. |
| [getDataStreamContainer()](#getDataStreamContainer--) | يحصل على تدفق بيانات الكائن. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | يحصل على تعديل عميق للوحة الألوان. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | يحصل على مصفوفة بكسلات ARGB 32-بت الافتراضية. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | يحصل على الخيارات الافتراضية. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمّل بكسل جزئي. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمّل بكسل جزئي. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [getDisplayName()](#getDisplayName--) | يحصل على الاسم المعروض للطبقة. |
| [getDisposed()](#getDisposed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [getExtraLength()](#getExtraLength--) | يحصل على طول معلومات الطبقة الإضافية بالبايت. |
| [getFileFormat()](#getFileFormat--) | يحصل على قيمة تنسيق الملف |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | يحصل على تنسيق الملف. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | يحصل على تنسيق الملف. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | يحصل على تنسيق الملف. |
| [getFillOpacity()](#getFillOpacity--) | يحصل أو يضبط شفافية التعبئة. |
| [getFiller()](#getFiller--) | يحصل أو يضبط ملء الطبقة. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [getFlags()](#getFlags--) | يحصل أو يضبط أعلام الطبقة. |
| [getFoldersHierarchy_internalized()](#getFoldersHierarchy-internalized--) | يحصل على قائمة هرمية مجلدات [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) للطبقة الحالية. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | يحصل على لوحة الألوان من أماكن خاصة بالتنسيق |
| [getGUID_internalized()](#getGUID-internalized--) | يحصل على المعرف الفريد لهذا الكائن Layer. |
| [getHeader_internalized()](#getHeader-internalized--) | يحصل أو يضبط الرأس. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصورة. |
| [getHorizontalResolution()](#getHorizontalResolution--) | يحصل أو يضبط الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذا  RasterImage . |
| [getImageOpacity()](#getImageOpacity--) | يحصل على شفافية هذه الصورة. |
| [getImageSizeBeforeChange_internalized()](#getImageSizeBeforeChange-internalized--) | يحصل أو يعيّن الحجم الأخير للصورة لتشويهها |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | يحصل على محول البيانات الداخلي. |
| [getInterruptMonitor()](#getInterruptMonitor--) | يحصل على مراقب المقاطعة. |
| [getLayerBlendingRangesData()](#getLayerBlendingRangesData--) | يحصل أو يضبط بيانات نطاقات دمج الطبقة. |
| [getLayerCreationDateTime()](#getLayerCreationDateTime--) | يحصل أو يضبط تاريخ ووقت إنشاء الطبقة. |
| [getLayerCreationDateTime_internalized()](#getLayerCreationDateTime-internalized--) |  |
| [getLayerLock()](#getLayerLock--) | يحصل أو يضبط قفل الطبقة. |
| [getLayerMaskData()](#getLayerMaskData--) | يحصل أو يضبط بيانات قناع الطبقة. |
| [getLayerOptions()](#getLayerOptions--) | يحصل على خيارات الطبقة. |
| [getLayerPalette_internalized()](#getLayerPalette-internalized--) | يحصل أو يضبط لوحة ألوان الطبقة. |
| [getLayerType_internalized()](#getLayerType-internalized--) | يحصل على نوع الطبقة. |
| [getLeft()](#getLeft--) | يحصل أو يضبط موضع الطبقة اليسرى. |
| [getLength()](#getLength--) | يحصل على الطول الكلي للطبقة بالبايت. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | يحصل أو يضبط الحد الأقصى المسموح به للتخصيص لحفظ الدوران الجزئي. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | يحصل على مدير الذاكرة. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getName()](#getName--) | يحصل أو يضبط اسم الطبقة. |
| [getOpacity()](#getOpacity--) | يحصل أو يضبط شفافية الطبقة. |
| [getOpacityTotal_internalized()](#getOpacityTotal-internalized--) | يحصل على الشفافية الكلية. |
| [getOriginalOptions()](#getOriginalOptions--) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. |
| [getOriginalQuadrilateral_internalized()](#getOriginalQuadrilateral-internalized--) | يحصل أو يعيّن الشكل الرباعي الأصلي. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | يحصل على الصورة القابلة للرسم. |
| [getPalette()](#getPalette--) | يحصل على لوحة الألوان. |
| [getPixel(int x, int y)](#getPixel-int-int-) | يحصل على بكسل الصورة. |
| [getPlacedLayerResource_internalized(LayerResource[] resources, int[] placedResourceIndex, int[] smartResourceIndex)](#getPlacedLayerResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource---int---int---) | يحصل على مؤشرات موارد الطبقة الموضوعة والذكية والموارد الموضوعة المناسبة. |
| [getPlacedResource_internalized()](#getPlacedResource-internalized--) | يحصل على مورد الطبقة الموضوعة. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | ينشئ ذاكرة التخزين المؤقت للخطوط الخاصة. |
| [getProgressEventHandler()](#getProgressEventHandler--) | يحصل على معلومات معالج حدث التقدم. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | يحصل على معلومات معالج حدث التقدم. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | يحصل على ارتفاع نسبي. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | يحصل على عرض نسبي. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | يحصل أو يضبط محول اللون المخصص |
| [getRawDataFormat()](#getRawDataFormat--) | يحصل على تنسيق البيانات الخام. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | يحصل أو يضبط فهرس الاحتياطي للاستخدام عندما يكون فهرس اللوحة خارج النطاق |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | يحصل أو يضبط محول اللون المفهرس |
| [getRawLineSize()](#getRawLineSize--) | يحصل على حجم السطر الخام بالبايت. |
| [getResources()](#getResources--) | يحصل أو يضبط موارد الطبقة. |
| [getRight()](#getRight--) | يحصل أو يضبط موضع الطبقة اليمنى. |
| [getRotateMode()](#getRotateMode--) | يحصل أو يعيّن وضع الدوران. |
| [getSheetColorHighlight()](#getSheetColorHighlight--) | يحصل أو يعيّن تمييز لون الورقة الزخرفية في قائمة الطبقات |
| [getSize()](#getSize--) | يحصل على حجم الصورة. |
| [getSkewAngle()](#getSkewAngle--) | يحصل على زاوية الانحراف. |
| [getSmartFilters()](#getSmartFilters--) | يحصل على الفلاتر الذكية. |
| [getSmartObjectProvider()](#getSmartObjectProvider--) | الحصول على موفر الكائن الذكي. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | يحصل على مسار ملف الصورة المصدر إذا كان موجودًا. |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | يحصل على جذر المزامنة. |
| [getTop()](#getTop--) | يحصل أو يعيّن موضع الطبقة العليا. |
| [getTransformedQuadrilateral_internalized()](#getTransformedQuadrilateral-internalized--) | يحصل أو يعيّن الشكل الرباعي للتحويل. |
| [getTransparentColor()](#getTransparentColor--) | يحصل على لون شفافية الصورة. |
| [getUpdateXmpData()](#getUpdateXmpData--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | يحصل على قيمة تشير إلى ما إذا كان الكائن يستخدم استراتيجية تحسين الذاكرة |
| [getUseRawData()](#getUseRawData--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | يحصل على اللوحة المستخدمة. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | يحصل على رخصة المشروع. |
| [getVerticalResolution()](#getVerticalResolution--) | يحصل أو يعيّن الدقة العمودية، بوحدة البكسل لكل بوصة، لهذه RasterImage. |
| [getWarpProvider_internalized()](#getWarpProvider-internalized--) | يحصل على وظائف تساعد في التشويه |
| [getWarpSettings()](#getWarpSettings--) | يحصل أو يضبط معلمات التشويه التي تم ضبطها أو الحصول عليها من المورد (افتراضي) |
| [getWidth()](#getWidth--) | يحصل على عرض الصورة. |
| [getXmpData()](#getXmpData--) | يحصل أو يعيّن بيانات XMP الوصفية. |
| [grayscale()](#grayscale--) | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| [hasAlpha()](#hasAlpha--) | يحصل على قيمة تشير إلى ما إذا كانت هذه النسخة تحتوي على قناة ألفا. |
| [hasBackgroundColor()](#hasBackgroundColor--) | يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت نسخة الصورة هذه قد تغيرت بعد التحميل. |
| [hasTransparentColor()](#hasTransparentColor--) | يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة لهذا الكائن. |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | يحصل أو يعيّن القيمة القصوى للتقدم |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | يشير إلى التقدم. |
| [insertResource_internalized(int index, LayerResource resource)](#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-) | إدراج مورد إلى مجموعة الموارد. |
| [isCached()](#isCached--) | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [isLayerValid_internalized()](#isLayerValid-internalized--) | يكشف ما إذا كانت الطبقة صالحة للحفظ في ملف. |
| [isRawDataAvailable()](#isRawDataAvailable--) | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| [isUsePalette()](#isUsePalette--) | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| [isVisible()](#isVisible--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الطبقة مرئية |
| [isVisibleInGroup()](#isVisibleInGroup--) | يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة مرئية في المجموعة (إذا لم تكن الطبقة في مجموعة فهذا يعني مجموعة الجذر). |
| [load(InputStream stream)](#load-java.io.InputStream-) | يحمّل صورة جديدة من الدفق المحدد. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | يحمّل صورة جديدة من الدفق المحدد. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | يحمّل صورة جديدة من الدفق المحدد. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | يحمّل صورة جديدة من الدفق المحدد. |
| [load(String filePath)](#load-java.lang.String-) | يحمّل صورة جديدة من الملف المحدد. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | يحمّل صورة جديدة من الملف المحدد. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.psd.Rectangle-) | يحمّل بكسلات ARGB 32‑بت. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.psd.Rectangle-) | يحمّل بكسلات ARGB 64‑بت. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.psd.Rectangle-) | يحمّل البكسلات بتنسيق CMYK. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.psd.Rectangle-) | يحمّل البكسلات بتنسيق CMYK. |
| [loadContents(LoadOptions options)](#loadContents-com.aspose.psd.LoadOptions-) | يحصل على محتويات الصورة المدمجة أو المرتبطة بطبقة الكائن الذكي. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | يحمّل بكسلات ARGB 32‑بت جزئياً عن طريق الحزم. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | يحمّل البكسلات جزئياً عن طريق الحزم. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.psd.Rectangle-) | يحمّل البكسلات. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | يحمّل بيانات الصورة الخام باستخدام آلية المعالجة الجزئية. |
| [loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | يحمّل البيانات الخام. |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | يحمّل صورة جديدة من الدفق المحدد. |
| [mergeLayerTo(Layer layerToMergeInto)](#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-) | يدمج الطبقة مع الطبقة المحددة |
| [newSmartObjectViaCopy()](#newSmartObjectViaCopy--) | ينشئ طبقة smart object جديدة عن طريق نسخ هذه. |
| [normalizeAngle()](#normalizeAngle--) | يُعَدِّل الزاوية إلى قيمتها الطبيعية. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | يُعَدِّل الزاوية إلى قيمتها الطبيعية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | يتم الاستدعاء عندما تم تعيين حاوية هذا [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | يقرأ السطر الكامل للمسح وفقًا لمؤشر سطر المسح المحدد. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | يقرأ السطر الكامل للمسح وفقًا لمؤشر سطر المسح المحدد. |
| [relinkToFile(String linkedPath)](#relinkToFile-java.lang.String-) | يعيد ربط الكائن الذكي المرتبط بملف جديد. |
| [removeResource_internalized(LayerResource resource)](#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | يزيل المورد. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [replaceContents(Image image)](#replaceContents-com.aspose.psd.Image-) | يستبدل محتويات الكائن الذكي المدمجة في طبقة الكائن الذكي. |
| [replaceContents(Image image, ResolutionSetting resolution)](#replaceContents-com.aspose.psd.Image-com.aspose.psd.ResolutionSetting-) | يستبدل محتويات الكائن الذكي المدمجة في طبقة الكائن الذكي. |
| [replaceContents(String linkedPath)](#replaceContents-java.lang.String-) | يستبدل المحتويات بملف. |
| [replaceContents(String linkedPath, boolean isReplaceOnlyThis)](#replaceContents-java.lang.String-boolean-) | يستبدل المحتويات بملف. |
| [replaceContents(String linkedPath, ResolutionSetting resolution)](#replaceContents-java.lang.String-com.aspose.psd.ResolutionSetting-) | يستبدل المحتويات بملف. |
| [replaceContents(String linkedPath, ResolutionSetting resolution, boolean isReplaceOnlyThis)](#replaceContents-java.lang.String-com.aspose.psd.ResolutionSetting-boolean-) | يستبدل المحتويات بملف. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | يغير حجم الصورة. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | يغير حجم الصورة. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | يغير حجم الصورة. |
| [resizeChannelsData_internalized(Rectangle rect)](#resizeChannelsData-internalized-com.aspose.psd.Rectangle-) | يعيد تحجيم بيانات القنوات |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | يعيد تحجيم الارتفاع بنسبة متناسبة. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | يعيد تحجيم الارتفاع بنسبة متناسبة. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | يعيد تحجيم الارتفاع بنسبة متناسبة. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | يعيد تحجيم العرض بنسبة متناسبة. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | يعيد تحجيم العرض بنسبة متناسبة. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | يعيد تحجيم العرض بنسبة متناسبة. |
| [resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)](#resizeWithScale-internalized-double-double-int-) | يعيد تحجيم الطبقة باستخدام المقياس العكسي المحدد. |
| [rotate(float angle)](#rotate-float-) | تدوير الصورة حول المركز. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | تدوير الصورة حول المركز. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) |  |
| [save()](#save--) | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| [save(System.IO.Stream stream)](#save-com.aspose.ms.System.IO.Stream-) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | يحفظ بيانات الكائن إلى الموقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [save(String filePath)](#save-java.lang.String-) | يحفظ بيانات الكائن إلى الموقع الملف المحدد. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | يحفظ بيانات الكائن إلى الموقع الملف المحدد. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | يحفظ بيانات الكائن إلى الموقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | يحفظ بيانات الكائن إلى الموقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | يحفظ بكسلات ARGB 32-بت. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | يحفظ البكسلات. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | يحفظ البكسلات. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | يحفظ البكسلات. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | يحفظ البيانات الخام. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)](#save-internalized-com.aspose.psd.StreamContainer-int-int-) | يحفظ البيانات إلى حاوية الدفق المحددة. |
| [setAbsoluteBounds_internalized(Rectangle value)](#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-) | يحصل أو يضبط الحدود المطلقة. |
| [setAllowWarpRepaint_internalized(boolean value)](#setAllowWarpRepaint-internalized-boolean-) | يحصل أو يعيّن تشويه العرض أو يستخدم صورة PS. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | يضبط بكسل صورة ARGB 32-بت للموقع المحدد. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | يضبط قيمة تشير إلى ما إذا كان يتم تعديل لوحة الألوان تلقائيًا. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | يحصل على أو يعيّن قيمة للون الخلفية. |
| [setBlendClippedElements(boolean value)](#setBlendClippedElements-boolean-) | يحصل على أو يعيّن دمج العنصر المقصوص. |
| [setBlendModeKey(long value)](#setBlendModeKey-long-) | يحصل على أو يعيّن مفتاح وضع الدمج. |
| [setBottom(int value)](#setBottom-int-) | يحصل على أو يعيّن موضع الطبقة السفلية. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [setChannelInformation(ChannelInformation[] value)](#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | يحصل على أو يعيّن معلومات القناة. |
| [setClipping(byte value)](#setClipping-byte-) | يحصل على أو يعيّن قص الطبقة. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | يضبط حاوية الصورة. |
| [setContents(byte[] value)](#setContents-byte---) | يحصل أو يعيّن محتويات طبقة الكائن الذكي. |
| [setContentsBounds(Rectangle value)](#setContentsBounds-com.aspose.psd.Rectangle-) | يحصل أو يعيّن حدود محتوى الكائن الذكي. |
| [setContentsSource(LinkDataSource value)](#setContentsSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | يحصل أو يعيّن مصدر محتوى الكائن الذكي. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | يضبط محمل البيانات مباشرة. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | يضبط دفق بيانات الكائن. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | يحصل أو يضبط الاسم المعروض للطبقة. |
| [setFillOpacity(int value)](#setFillOpacity-int-) | يحصل على شفافية التعبئة. |
| [setFiller(byte value)](#setFiller-byte-) | يحصل أو يضبط ملء الطبقة. |
| [setFlags(byte value)](#setFlags-byte-) | يحصل أو يضبط أعلام الطبقة. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | يضبط لوحة الألوان في الأماكن الخاصة بالتنسيق |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | يحصل أو يضبط الرأس. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | يحصل أو يضبط الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذا  RasterImage . |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | يضبط قيمة تشير إلى ما إذا كان [تجاهل بعد الحفظ]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت نسخة الصورة هذه قد تغيرت بعد التحميل. |
| [setImageSizeBeforeChange_internalized(Size value)](#setImageSizeBeforeChange-internalized-com.aspose.psd.Size-) | يحصل أو يعيّن الحجم الأخير للصورة لتشويهها |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | يضبط محول البيانات الداخلي. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | يضبط مراقب المقاطعة. |
| [setLayerBlendingRangesData(LayerBlendingRangesData value)](#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-) | يحصل أو يضبط بيانات نطاقات دمج الطبقة. |
| [setLayerCreationDateTime(Date value)](#setLayerCreationDateTime-java.util.Date-) | يحصل أو يضبط تاريخ ووقت إنشاء الطبقة. |
| [setLayerCreationDateTime_internalized(System.DateTime value)](#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-) |  |
| [setLayerLock(int value)](#setLayerLock-int-) | يحصل أو يضبط قفل الطبقة (ملاحظة أنه إذا تم تعيين العلامة LayerFlags.TransparencyProtected فستُستبدل بعلامة قفل الطبقة). |
| [setLayerMaskData(LayerMaskData value)](#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | يحصل أو يضبط بيانات قناع الطبقة. |
| [setLayerPalette_internalized(IColorPalette value)](#setLayerPalette-internalized-com.aspose.psd.IColorPalette-) | يحصل أو يضبط لوحة ألوان الطبقة. |
| [setLeft(int value)](#setLeft-int-) | يحصل أو يضبط موضع الطبقة اليسرى. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | يحصل أو يضبط الحد الأقصى المسموح به للتخصيص لحفظ الدوران الجزئي. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | يضبط مدير الذاكرة. |
| [setName(String name)](#setName-java.lang.String-) | يضبط اسم الطبقة. |
| [setName_internalized(String value)](#setName-internalized-java.lang.String-) | يحصل أو يضبط اسم الطبقة. |
| [setOpacity(byte value)](#setOpacity-byte-) | يحصل أو يضبط شفافية الطبقة. |
| [setOriginalQuadrilateral_internalized(Quadrilateral value)](#setOriginalQuadrilateral-internalized-com.aspose.internal.fileformats.psd.projective.Quadrilateral-) | يحصل أو يعيّن الشكل الرباعي الأصلي. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | يضبط لوحة الألوان. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | يضبط لوحة ألوان الصورة. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | يضبط بكسل الصورة للموقع المحدد. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | يحصل أو يضبط محول اللون المخصص |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | يحصل أو يضبط فهرس الاحتياطي للاستخدام عندما يكون فهرس اللوحة خارج النطاق |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | يحصل أو يضبط محول اللون المفهرس |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | يضبط الدقة لهذا  RasterImage . |
| [setResources(LayerResource[] value)](#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | يحصل أو يضبط موارد الطبقة. |
| [setRight(int value)](#setRight-int-) | يحصل أو يضبط موضع الطبقة اليمنى. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | يحصل أو يعيّن وضع الدوران. |
| [setSheetColorHighlight(short value)](#setSheetColorHighlight-short-) | يحصل أو يعيّن تمييز لون الورقة الزخرفية في قائمة الطبقات |
| [setSmartObjectProvider_internalized(SmartObjectProvider value)](#setSmartObjectProvider-internalized-com.aspose.psd.fileformats.psd.SmartObjectProvider-) | الحصول على موفر الكائن الذكي. |
| [setTop(int value)](#setTop-int-) | يحصل أو يعيّن موضع الطبقة العليا. |
| [setTransformedQuadrilateral_internalized(Quadrilateral value)](#setTransformedQuadrilateral-internalized-com.aspose.internal.fileformats.psd.projective.Quadrilateral-) | يحصل أو يعيّن الشكل الرباعي للتحويل. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | يحصل على لون شفافية الصورة. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | يجب على جميع منتجات Aspose تنفيذ هذه الطريقة. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | يحصل أو يعيّن الدقة العمودية، بوحدة البكسل لكل بوصة، لهذه RasterImage. |
| [setVisible(boolean value)](#setVisible-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الطبقة مرئية |
| [setWarpSettings(WarpSettings value)](#setWarpSettings-com.aspose.psd.fileformats.psd.layers.warp.structs.WarpSettings-) | يحصل أو يضبط معلمات التشويه التي تم ضبطها أو الحصول عليها من المورد (افتراضي) |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | يحصل أو يعيّن بيانات XMP الوصفية. |
| [shallowCopy()](#shallowCopy--) | ينشئ نسخة سطحية من الطبقة الحالية. |
| [toBitmap()](#toBitmap--) | يحول الصورة النقطية إلى bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [updateBlendingOptions_internalized(PattResource pattResource)](#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | يقوم بتحديث خيارات الدمج بعد تغيير الطبقة أو الموارد العامة. |
| [updateDataSourceId_internalized(System.Guid sourceId)](#updateDataSourceId-internalized-com.aspose.ms.System.Guid-) | يحدّث معرف مصدر البيانات. |
| [updateModifiedContent()](#updateModifiedContent--) | يحدّث ذاكرة التخزين المؤقت لصورة طبقة الكائن الذكي بالمحتوى المعدل. |
| [updateModifiedContentWithImage_internalized(Image image, ResolutionSetting resolution, boolean skipBoundsUpdate)](#updateModifiedContentWithImage-internalized-com.aspose.psd.Image-com.aspose.psd.ResolutionSetting-boolean-) | يحدّث ذاكرة التخزين المؤقت لصورة طبقة الكائن الذكي بالمحتوى المعدل. |
| [updatePlacedResources_internalized(boolean toEmbedded)](#updatePlacedResources-internalized-boolean-) | يحدّث الموارد الموضوعة / الذكية عندما يتم تغيير placedResource أو عندما تكون التحويلة مطلوبة. |
| [updatePreview_internalized(PixelsData targetWarpedPixels)](#updatePreview-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-) | إنه غلاف لـ "IWarpSupport" لتحديث معاينة الطبقة. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد. |
### SmartObjectLayer(System.IO.Stream stream) {#SmartObjectLayer-com.aspose.ms.System.IO.Stream-}
```
public SmartObjectLayer(System.IO.Stream stream)
```


يُهيئ مثالًا جديدًا من الفئة [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | تدفق العناصر. |

### BlendSignature {#BlendSignature}
```
public static final int BlendSignature
```


يمثل توقيع وضع المزج.

### BothPlacedAndSmartObjectResourcesFoundMessage_internalized {#BothPlacedAndSmartObjectResourcesFoundMessage-internalized}
```
public static final String BothPlacedAndSmartObjectResourcesFoundMessage_internalized
```


رسالة العثور على كل من موارد placed و smart object.

### CanOnlyCopyEmbeddedSmartObjectMessage_internalized {#CanOnlyCopyEmbeddedSmartObjectMessage-internalized}
```
public static final String CanOnlyCopyEmbeddedSmartObjectMessage_internalized
```


الرسالة: لا يمكنك سوى نسخ smart object مضمّن.

### LayerHeaderSize {#LayerHeaderSize}
```
public static final int LayerHeaderSize
```


حجم رأس الطبقة.

### NoPlacedOrSmartObjectResourceFoundMessage_internalized {#NoPlacedOrSmartObjectResourceFoundMessage-internalized}
```
public static final String NoPlacedOrSmartObjectResourceFoundMessage_internalized
```


رسالة عدم العثور على مورد placed أو smart object.

### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


يحدث عندما تم تحميل الصورة

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


يحدث عندما تم تحميل الصورة بواسطة createFirstSupportedLoader

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


يحدث عندما تم تحميل الصورة أو حفظها

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


يحدث عندما تم استخدام الرصيد

### WrongPlacedResourceIndicesMessage_internalized {#WrongPlacedResourceIndicesMessage-internalized}
```
public static final String WrongPlacedResourceIndicesMessage_internalized
```


رسالة مؤشرات مورد placed غير صحيحة.

### resources_internalized {#resources-internalized}
```
public ResourceNest resources_internalized
```


الموارد

### <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource) {#-T-tryGetResource-internalized-java.lang.Class-T--T---}
```
public final boolean <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)
```


يحصل على المورد المرتبط بالنوع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | resource | T[] | عند عودة هذه الطريقة، يحتوي على المورد المرتبط بنوع المفتاح المحدد، إذا تم العثور على المفتاح؛ وإلا، يرجع null. |

T : نوع المفتاح للقيمة المراد الحصول عليها. |

**Returns:**
boolean -   إذا كان يحتوي على مورد بالنوع المحدد؛ وإلا،  .
### addLayerMask(LayerMaskData layerMask) {#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void addLayerMask(LayerMaskData layerMask)
```


يضيف القناع إلى الطبقة الحالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| layerMask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | قناع الطبقة. |

### addResource_internalized(LayerResource resource) {#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void addResource_internalized(LayerResource resource)
```


يضيف المورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | المورد. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


ضبط السطوع للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| السطوع | int | قيمة السطوع. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


تباين الصورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التباين | float | قيمة التباين (في النطاق [-100; 100]) |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


تصحيح غاما للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| جاما | float | معامل جاما للقنوات الحمراء والخضراء والزرقاء |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


تصحيح غاما للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| gammaRed | float | معامل Gamma للقناة الحمراء |
| gammaGreen | float | معامل Gamma للقناة الخضراء |
| gammaBlue | float | معامل Gamma للقناة الزرقاء |

### applyLayerMask() {#applyLayerMask--}
```
public final void applyLayerMask()
```


يطبق قناع الطبقة على الطبقة، ثم يحذف القناع.

### applyLayerState_internalized(LayerState layerState) {#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-}
```
public final void applyLayerState_internalized(LayerState layerState)
```


يطبق إعداد نمط الطبقة من [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) إلى نسخة [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) الحالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| layerState | [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) | حالة الطبقة مع النمط الجديد. |

### beginResize_internalized(int newWidth, int newHeight) {#beginResize-internalized-int-int-}
```
public IResizeController beginResize_internalized(int newWidth, int newHeight)
```


يبدأ عملية تغيير الحجم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | عرض الصورة الجديد. |
| newHeight | int | ارتفاع الصورة الجديد. |

**Returns:**
com.aspose.internal.IResizeController - وحدة التحكم في تغيير الحجم.
### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | double | فرق السطوع بين البكسل ومتوسط نافذة s x s من البكسلات المتمركزة حول هذا البكسل. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | double | فرق السطوع بين البكسل ومتوسط نافذة s x s من البكسلات المتمركزة حول هذا البكسل. |
| windowSize | int | حجم نافذة s x s من البكسلات المتمركزة حول هذا البكسل |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


تحويل الصورة إلى ثنائية بعتبة محددة مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | byte | قيمة العتبة. إذا كانت القيمة الرمادية المقابلة لبكسل أكبر من العتبة، سيتم تعيين القيمة 255 له، وإلا 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


تحويل الصورة إلى ثنائية باستخدام عتبة أوتو.

### cacheData() {#cacheData--}
```
public void cacheData()
```


يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من DataStreamSupporter.DataStreamContainer الأساسي.

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | الدفق للتحميل منه. |

**Returns:**
boolean -  true  إذا كان يمكن تحميل الصورة من الدفق المحدد؛ وإلا،  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واختياريًا باستخدام loadOptions المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | الدفق للتحميل منه. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | خيارات التحميل. |

**Returns:**
boolean -  true  إذا كان يمكن تحميل الصورة من الدفق المحدد؛ وإلا،  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف. |

**Returns:**
منطقي -  true  إذا كان يمكن تحميل الصورة من الملف المحدد؛ وإلا،  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واستخدام خيارات الفتح المحددة اختياريًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | خيارات التحميل. |

**Returns:**
منطقي -  true  إذا كان يمكن تحميل الصورة من الملف المحدد؛ وإلا،  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


يحدد ما إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | خيارات الحفظ التي سيتم استخدامها. |

**Returns:**
منطقي -  true  إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة؛ وإلا،  false .
### close() {#close--}
```
public void close()
```


تنفيذ واجهة Closable ويمكن استخدامها في بيان try-with-resources منذ JDK 1.7. هذه الطريقة تستدعي ببساطة طريقة dispose.

### convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)
```


يحول إلى aps.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | الخيارات. |
| الوضع | int | الوضع. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل القص. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - صفحة APS.
### convertToLinked(String linkedPath) {#convertToLinked-java.lang.String-}
```
public final void convertToLinked(String linkedPath)
```


يحوّل هذا smart object المضمّن إلى smart object مرتبط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| linkedPath | java.lang.String | المسار المرتبط. |

### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | خيارات الصورة. |
| العرض | int | العرض. |
| الارتفاع | int | الارتفاع. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


ينشئ صورة جديدة باستخدام الصور المحددة كصفحات

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | الصور. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


ينشئ صورة جديدة باستخدام الصور المحددة كصفحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | الصور. |
| disposeImages | boolean | إذا تم تعيينه إلى  true  [dispose images]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static Layer createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)
```


ينشئ النسخة الجديدة من الفئة [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الرأس | com.aspose.internal.fileformats.psd.sections.PsdHeader | الرأس. |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | لوحة الألوان. |
| linkedLayersRegistry | com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry | سجل LinkedLayersRegistry. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Returns the new instance of the [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) class.
### createLayerState_internalized() {#createLayerState-internalized--}
```
public final LayerState createLayerState_internalized()
```


ينشئ نسخة [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) الجديدة بناءً على قيم [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) الحالية.

**Returns:**
[LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) - The new [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instance based on current [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) values.
### createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height) {#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-}
```
public static IPartialProcessor createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resizer | com.aspose.internal.rotaters.PartialRotater |  |
| pixelsSaver | com.aspose.internal.IPixelsSaver |  |
| العرض | int |  |
| الارتفاع | int |  |

**Returns:**
com.aspose.internal.IPartialProcessor
### create_internalized(PsdHeader header, IColorPalette colorPalette, LinkedLayersRegistry linkedLayersRegistry, LayerResource[] resources) {#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public static SmartObjectLayer create_internalized(PsdHeader header, IColorPalette colorPalette, LinkedLayersRegistry linkedLayersRegistry, LayerResource[] resources)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الرأس | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |
| linkedLayersRegistry | com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry |  |
| resources | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer)
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Layer create_internalized(System.IO.Stream stream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


قص الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


قص الصورة مع الإزاحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| leftShift | int | الإزاحة اليسرى. |
| rightShift | int | الإزاحة اليمنى. |
| topShift | int | الإزاحة العلوية. |
| bottomShift | int | الإزاحة السفلية. |

### dispose() {#dispose--}
```
public final void dispose()
```


يحرر النسخة الحالية.

### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


ينفذ تمويه (dithering) على الصورة الحالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ditheringMethod | int | طريقة التمويه. |
| bitsCount | int | عدد البتات النهائي للتمويه. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.psd.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


ينفذ تمويه (dithering) على الصورة الحالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ditheringMethod | int | طريقة التمويه. |
| bitsCount | int | عدد البتات النهائي للتمويه. |
| customPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | لوحة الألوان المخصصة للتمويه. |

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### doCrop_internalized(Rectangle rectangle) {#doCrop-internalized-com.aspose.psd.Rectangle-}
```
public void doCrop_internalized(Rectangle rectangle)
```


قص الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل. |

### doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings) {#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)
```


يغير حجم الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | إعدادات تغيير الحجم. |

### doResize_internalized(int newWidth, int newHeight, int resizeType) {#doResize-internalized-int-int-int-}
```
public void doResize_internalized(int newWidth, int newHeight, int resizeType)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int |  |
| newHeight | int |  |
| resizeType | int |  |

### doRotate(float angle, boolean resizeProportionally, Color backgroundColor) {#doRotate-float-boolean-com.aspose.psd.Color-}
```
public void doRotate(float angle, boolean resizeProportionally, Color backgroundColor)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float |  |
| تغيير الحجم بشكل متناسب | boolean |  |
| backgroundColor | [Color](../../com.aspose.psd/color) |  |

### doRotateFlip_internalized(int rotateFlipType) {#doRotateFlip-internalized-int-}
```
public void doRotateFlip_internalized(int rotateFlipType)
```


يدور، يقلب، أو يدور ويقلب الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع التدوير والقلب | int | نوع التدوير والقلب. |

### drawImage(Point location, RasterImage image) {#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-}
```
public final void drawImage(Point location, RasterImage image)
```


يرسم الصورة على الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | الموقع. |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | الصورة. |

### duplicateLayer() {#duplicateLayer--}
```
public final SmartObjectLayer duplicateLayer()
```


ينشئ طبقة كائن ذكي جديدة بنسخ هذه الطبقة. لاحظ أنه بالنسبة للكائنات الذكية المدمجة تُشارك الصورة المدمجة. إذا كنت تريد نسخ الصورة المدمجة استخدم طريقة [.newSmartObjectViaCopy](../../null/\#newSmartObjectViaCopy) method.

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The cloned [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### embedLinked() {#embedLinked--}
```
public final void embedLinked()
```


يقوم بدمج الكائن الذكي المرتبط في هذه الطبقة.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الكائن المحدد يساوي هذه النسخة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة مع هذه الحالة. |

**Returns:**
منطقي -  true  إذا كان الكائن المحدد مساويًا لهذه الحالة؛ وإلا،  false .
### exportContents(String filePath) {#exportContents-java.lang.String-}
```
public final void exportContents(String filePath)
```


يصدّر المحتويات المدمجة أو المرتبطة إلى ملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف التصدير. |

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


يفلتر المستطيل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل. |
| options | [FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase) | الخيارات. |

### findAssignableResource_internalized(System.Type type) {#findAssignableResource-internalized-com.aspose.ms.System.Type-}
```
public final LayerResource findAssignableResource_internalized(System.Type type)
```


يجد المورد القابل للتعيين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع | com.aspose.ms.System.Type | النوع. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - 
### findPattResource_internalized() {#findPattResource-internalized--}
```
public final PattResource findPattResource_internalized()
```


يجد PattResource

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - The found resource or null
### findResource_internalized(int typeToolKey) {#findResource-internalized-int-}
```
public final LayerResource findResource_internalized(int typeToolKey)
```


يجد المورد بالمفتاح الفريد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مفتاح أداة النوع | int | مفتاح أداة النوع. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - Found resource or null
### getAbsoluteBounds_internalized() {#getAbsoluteBounds-internalized--}
```
public final Rectangle getAbsoluteBounds_internalized()
```


يحصل أو يضبط الحدود المطلقة.

القيمة: الحدود المطلقة.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getAllowWarpRepaint_internalized() {#getAllowWarpRepaint-internalized--}
```
public final boolean getAllowWarpRepaint_internalized()
```


يحصل أو يعيّن تشويه العرض أو يستخدم صورة PS.

**Returns:**
boolean
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


يحصل على بكسل صورة 32-بت ARGB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | موقع بكسل س. |
| ص | int | موقع بكسل ص. |

**Returns:**
int - بكسل ARGB 32-بت للموقع المحدد.
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


يحصل على قيمة تشير إلى ما إذا كان تعديل اللوحة تلقائيًا.

**Returns:**
منطقي -  true  إذا تم تمكين تعديل اللوحة التلقائي؛ وإلا،  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


يحصل على أو يعيّن قيمة للون الخلفية.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يحصل على عدد البتات لكل بكسل في الصورة.

القيمة: عدد بتات الصورة لكل بكسل.

**Returns:**
int
### getBlendClippedElements() {#getBlendClippedElements--}
```
public final boolean getBlendClippedElements()
```


يحصل على أو يعيّن دمج العنصر المقصوص.

القيمة: دمج العنصر المقصوص.

**Returns:**
boolean
### getBlendModeKey() {#getBlendModeKey--}
```
public long getBlendModeKey()
```


يحصل على أو يعيّن مفتاح وضع الدمج.

القيمة: مفتاح وضع الدمج.

**Returns:**
long
### getBlendModeSignature() {#getBlendModeSignature--}
```
public final int getBlendModeSignature()
```


يحصل على توقيع وضع الدمج.

القيمة: توقيع وضع الدمج.

**Returns:**
int
### getBlendingOptions() {#getBlendingOptions--}
```
public final BlendingOptions getBlendingOptions()
```


يحصل على خيارات الدمج.

القيمة: خيارات الدمج.

**Returns:**
[BlendingOptions](../../com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions)
### getBottom() {#getBottom--}
```
public int getBottom()
```


يحصل على أو يعيّن موضع الطبقة السفلية.

القيمة: موضع الطبقة السفلية.

**Returns:**
int
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل على حدود الصورة.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


يحصل على تلميح حجم المخزن المؤقت الذي يُعرّف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الموجبة تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Returns:**
int - تلميح حجم المخزن المؤقت الذي يُعرّف الحد الأقصى المسموح به لجميع المخازن المؤقتة الداخلية.
### getBytesPerRowForFullMask_internalized(int bitDepth) {#getBytesPerRowForFullMask-internalized-int-}
```
public final int getBytesPerRowForFullMask_internalized(int bitDepth)
```


يحصل على عدد البايتات لكل صف في وضع القناع الكامل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitDepth | int | عمق البت. |

**Returns:**
int - عدد البايتات المطلوبة لتخزين صف واحد
### getBytesPerRowForMask_internalized(int bitDepth) {#getBytesPerRowForMask-internalized-int-}
```
public final int getBytesPerRowForMask_internalized(int bitDepth)
```


يحصل على عدد البايتات لكل صف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitDepth | int | عمق البت. |

**Returns:**
int - عدد البايتات المطلوبة لتخزين صف واحد
### getBytesPerRow_internalized(int bitDepth) {#getBytesPerRow-internalized-int-}
```
public final int getBytesPerRow_internalized(int bitDepth)
```


يحصل على عدد البايتات لكل صف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitDepth | int | عمق البت. |

**Returns:**
int - عدد البايتات المطلوبة لتخزين صف واحد
### getChannelInformation() {#getChannelInformation--}
```
public final ChannelInformation[] getChannelInformation()
```


يحصل على أو يعيّن معلومات القناة.

القيمة: معلومات القناة.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[]
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


يحصل على عدد قنوات الطبقة.

القيمة: عدد قنوات الطبقة.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClipping() {#getClipping--}
```
public final byte getClipping()
```


يحصل أو يعيّن قص الطبقة. 0 = أساسي، 1 = غير أساسي.

القيمة: قص الطبقة.

**Returns:**
byte
### getContainer() {#getContainer--}
```
public Image getContainer()
```


يحصل على حاوية الصورة.

القيمة: حاوية الصورة.

إذا لم تكن هذه الخاصية فارغة، فهذا يدل على أن الصورة مضمَّنة داخل صورة أخرى.

**Returns:**
[Image](../../com.aspose.psd/image)
### getContentType() {#getContentType--}
```
public final int getContentType()
```


يحصل على نوع محتوى طبقة الكائن الذكي. محتويات الكائن الذكي المضمنة هي ملف الصورة الخام المضمن:  LiFdDataSource.Data . محتويات الكائن الذكي المرتبط هي المحتويات الخام لملف الصورة المرتبطة إذا كان متاحًا: [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource). لا ندعم التحميل من مكتبة الرسومات Adobe\\ufffd Photoshop\\ufffd \\ufffd\\ufffd عندما تكون  LinkDataSource.IsLibraryLink ([LinkDataSource.isLibraryLink()](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource\#isLibraryLink--)/[LinkDataSource.setLibraryLink(boolean)](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource\#setLibraryLink-boolean-)) صحيحة. بالنسبة لملفات الارتباط العادية، في البداية نستخدم  LiFeDataSource.RelativePath ([LiFeDataSource.getRelativePath](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource\#getRelativePath)/[LiFeDataSource.setRelativePath(String)](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource\#setRelativePath-String-)) للبحث عن الملف نسبةً إلى مسار صورة المصدر  DataStreamSupporter.SourceImagePath ، إذا لم يكن متاحًا نبحث في  LiFeDataSource.FullPath ([LiFeDataSource.getFullPath](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource\#getFullPath)/[LiFeDataSource.setFullPath(String)](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource\#setFullPath-String-))، وإذا لم يكن كذلك نبحث عن ملف الارتباط في نفس الدليل الذي توجد فيه صورتنا:  DataStreamSupporter.SourceImagePath .

القيمة: نوع محتوى طبقة الكائن الذكي.

**Returns:**
int
### getContents() {#getContents--}
```
public final byte[] getContents()
```


يحصل أو يضبط محتويات طبقة الكائن الذكي. محتويات الكائن الذكي المضمنة هي ملف الصورة الخام المضمن:  LiFdDataSource.Data  وخصائصه. محتويات الكائن الذكي المرتبط هي المحتوى الخام لملف الصورة المرتبطة إذا كان متاحًا وخصائصه: [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource). لا ندعم التحميل من مكتبة الرسومات Adobe\\ufffd Photoshop\\ufffd \\ufffd\\ufffd عندما تكون  LinkDataSource.IsLibraryLink ([LinkDataSource.isLibraryLink()](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource\#isLibraryLink--)/[LinkDataSource.setLibraryLink(boolean)](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource\#setLibraryLink-boolean-)) صحيحة. بالنسبة لملفات الارتباط العادية، في البداية نستخدم  LiFeDataSource.RelativePath ([LiFeDataSource.getRelativePath](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource\#getRelativePath)/[LiFeDataSource.setRelativePath(String)](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource\#setRelativePath-String-)) للبحث عن الملف نسبةً إلى مسار صورة المصدر  DataStreamSupporter.SourceImagePath ، إذا لم يكن متاحًا نبحث في  LiFeDataSource.FullPath ([LiFeDataSource.getFullPath](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource\#getFullPath)/[LiFeDataSource.setFullPath(String)](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource\#setFullPath-String-))، وإذا لم يكن كذلك نبحث عن ملف الارتباط في نفس الدليل الذي توجد فيه صورتنا:  DataStreamSupporter.SourceImagePath .

**Returns:**
byte[]
### getContentsBounds() {#getContentsBounds--}
```
public final Rectangle getContentsBounds()
```


يحصل أو يعيّن حدود محتوى الكائن الذكي.

القيمة: حدود الكائن الذكي.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getContentsSource() {#getContentsSource--}
```
public final LinkDataSource getContentsSource()
```


يحصل أو يعيّن مصدر محتوى الكائن الذكي.

القيمة: مصدر بيانات الكائن الذكي.

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


يحصل على تدفق بيانات الكائن.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


يحصل على تعديل عميق للوحة الألوان.

**Returns:**
boolean - تعديل عميق للوحة الألوان.
### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


يحصل على مصفوفة بكسلات ARGB 32-بت الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل للحصول على البكسلات. |

**Returns:**
int[] - مصفوفة البكسلات الافتراضية.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


يحصل على الخيارات الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| args | java.lang.Object[] | المعلمات. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


يحصل على مصفوفة البكسلات الافتراضية باستخدام محمّل بكسل جزئي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل للحصول على البكسلات. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | محمل البكسلات الجزئي. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمّل بكسل جزئي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل للحصول على البكسلات. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | محمل البيانات الخام الجزئي. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | إعدادات البيانات الخام. |

### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


يحصل على مصفوفة البيانات الخام الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل للحصول على البيانات الخام. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | إعدادات البيانات الخام. |

**Returns:**
byte[] - مصفوفة البيانات الخام الافتراضية.
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


يحصل على الاسم المعروض للطبقة.

القيمة: الاسم المعروض للطبقة.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه.

**Returns:**
boolean -  true  إذا تم التخلص؛ وإلا،  false .
### getExtraLength() {#getExtraLength--}
```
public final int getExtraLength()
```


يحصل على طول معلومات الطبقة الإضافية بالبايت.

القيمة: طول الطبقة الإضافية.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


يحصل على قيمة تنسيق الملف

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


يحصل على تنسيق الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | التدفق. |

--------------------

تنسيق الملف المحدد لا يعني أن الصورة المحددة يمكن تحميلها. استخدم أحد التحميلات الزائدة لطريقة CanLoad لتحديد ما إذا كان يمكن تحميل التدفق. |

**Returns:**
long - تنسيق الملف المحدد.
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


يحصل على تنسيق الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | stream | java.io.InputStream | التدفق. |

تنسيق الملف المحدد لا يعني أن الصورة المحددة يمكن تحميلها. استخدم أحد التحميلات الزائدة لطريقة CanLoad لتحديد ما إذا كان يمكن تحميل التدفق. |

**Returns:**
long - تنسيق الملف المحدد.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


يحصل على تنسيق الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف. |

تنسيق الملف المحدد لا يعني أن الصورة المحددة يمكن تحميلها. استخدم أحد التحميلات الزائدة لطريقة CanLoad لتحديد ما إذا كان يمكن تحميل الملف. |

**Returns:**
long - تنسيق الملف المحدد.
### getFillOpacity() {#getFillOpacity--}
```
public final int getFillOpacity()
```


يحصل أو يضبط شفافية التعبئة.

**Returns:**
int
### getFiller() {#getFiller--}
```
public final byte getFiller()
```


يحصل أو يضبط ملء الطبقة.

القيمة: مملئ الطبقة.

**Returns:**
byte
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


يحصل على المستطيل الذي يناسب الصورة الحالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل للحصول على المستطيل المناسب له. |
| العرض | int | عرض الكائن. |
| الارتفاع | int | ارتفاع الكائن. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


يحصل على المستطيل الذي يناسب الصورة الحالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل للحصول على المستطيل المناسب له. |
| بكسلات | int[] | بكسلات ARGB 32-بت. |
| العرض | int | عرض الكائن. |
| الارتفاع | int | ارتفاع الكائن. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


الحصول على أو تعيين أعلام الطبقة. البت 0 = حماية الشفافية؛ البت 1 = مرئي؛ البت 2 = مهمل؛ البت 3 = 1 لبرنامج Photoshop 5.0 وما بعده، يوضح ما إذا كان البت 4 يحتوي على معلومات مفيدة؛ البت 4 = بيانات البكسل غير ذات صلة بمظهر المستند.

القيمة: أعلام الطبقة.

**Returns:**
byte
### getFoldersHierarchy_internalized() {#getFoldersHierarchy-internalized--}
```
public final System.Collections.Generic.List<Layer> getFoldersHierarchy_internalized()
```


يحصل على قائمة هرمية مجلدات [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) للطبقة الحالية.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.Layer> - إرجاع قائمة مجلدات [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) الهرمية للطبقة الحالية.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


يحصل على لوحة الألوان من أماكن خاصة بالتنسيق

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGUID_internalized() {#getGUID-internalized--}
```
public final String getGUID_internalized()
```


يحصل على المعرف الفريد لهذا الكائن Layer.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


يحصل أو يضبط الرأس.

القيمة: الترويسة.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل على ارتفاع الصورة.

القيمة: ارتفاع الصورة.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


يحصل أو يضبط الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذا  RasterImage .

**Returns:**
double - الدقة الأفقية.

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيمتي الدقة معًا في استدعاء واحد.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


يحصل على شفافية هذه الصورة.

**Returns:**
float - قيمة الشفافية بين 0.0 (شفافة تمامًا) و 1.0 (معتمة تمامًا).
### getImageSizeBeforeChange_internalized() {#getImageSizeBeforeChange-internalized--}
```
public final Size getImageSizeBeforeChange_internalized()
```


يحصل أو يعيّن الحجم الأخير للصورة لتشويهها

**Returns:**
[Size](../../com.aspose.psd/size)
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


يحصل على محول البيانات الداخلي.

القيمة: محول البيانات الداخلي.

**Returns:**
com.aspose.internal.IInnerDataTransformer - محول البيانات الداخلي.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


يحصل على مراقب المقاطعة.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayerBlendingRangesData() {#getLayerBlendingRangesData--}
```
public final LayerBlendingRangesData getLayerBlendingRangesData()
```


يحصل أو يضبط بيانات نطاقات دمج الطبقة.

القيمة: بيانات نطاقات دمج الطبقة.

**Returns:**
[LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata)
### getLayerCreationDateTime() {#getLayerCreationDateTime--}
```
public final Date getLayerCreationDateTime()
```


يحصل أو يضبط تاريخ ووقت إنشاء الطبقة.

القيمة: تاريخ ووقت إنشاء الطبقة. إذا لم تتوفر بيانات حول تاريخ ووقت الإنشاء فستُرجع زمن يونكس من البداية.

**Returns:**
java.util.Date
### getLayerCreationDateTime_internalized() {#getLayerCreationDateTime-internalized--}
```
public final System.DateTime getLayerCreationDateTime_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getLayerLock() {#getLayerLock--}
```
public final int getLayerLock()
```


يحصل أو يعيّن قفل الطبقة. لاحظ أنه إذا تم تعيين العلامة LayerFlags.TransparencyProtected فستُستبدل بعلامة قفل الطبقة. لإرجاع علامة LayerFlags.TransparencyProtected تحتاج إلى تطبيقها على خيار الطبقة layer.Flags |= LayerFlags.TransparencyProtected

القيمة: قفل الطبقة.

**Returns:**
int
### getLayerMaskData() {#getLayerMaskData--}
```
public final LayerMaskData getLayerMaskData()
```


يحصل أو يضبط بيانات قناع الطبقة.

القيمة: بيانات قناع الطبقة.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
### getLayerOptions() {#getLayerOptions--}
```
public final PsdOptions getLayerOptions()
```


يحصل على خيارات الطبقة.

القيمة: خيارات الطبقة.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)
### getLayerPalette_internalized() {#getLayerPalette-internalized--}
```
public final IColorPalette getLayerPalette_internalized()
```


يحصل أو يضبط لوحة ألوان الطبقة.

القيمة: لوحة ألوان الطبقة.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getLayerType_internalized() {#getLayerType-internalized--}
```
public byte getLayerType_internalized()
```


يحصل على نوع الطبقة.

القيمة: نوع الطبقة.

**Returns:**
byte
### getLeft() {#getLeft--}
```
public int getLeft()
```


يحصل أو يضبط موضع الطبقة اليسرى.

القيمة: موضع الطبقة اليسرى.

**Returns:**
int
### getLength() {#getLength--}
```
public final long getLength()
```


يحصل على الطول الكلي للطبقة بالبايت.

**Returns:**
long
### getMaxAllowedAllocationForPartialRotateSave_internalized() {#getMaxAllowedAllocationForPartialRotateSave-internalized--}
```
public static int getMaxAllowedAllocationForPartialRotateSave_internalized()
```


يحصل أو يضبط الحد الأقصى المسموح به للتخصيص لحفظ الدوران الجزئي.

**Returns:**
int - الحد الأقصى المسموح به للتخصيص لحفظ التدوير الجزئي.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


يحصل على مدير الذاكرة.

القيمة: مدير الذاكرة.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - مدير الذاكرة.
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


يحصل على تاريخ ووقت آخر تعديل لصورة المورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| useDefault | boolean | إذا تم تعيينه إلى  true  يستخدم المعلومات من FileInfo كقيمة افتراضية. |

**Returns:**
java.util.Date - التاريخ والوقت الذي تم فيه تعديل صورة المورد آخر مرة.
### getModifyDate_internalized(boolean useDefault) {#getModifyDate-internalized-boolean-}
```
public System.DateTime getModifyDate_internalized(boolean useDefault)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| useDefault | boolean |  |

**Returns:**
com.aspose.ms.System.DateTime
### getName() {#getName--}
```
public final String getName()
```


يحصل أو يضبط اسم الطبقة.

القيمة: اسم الطبقة.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


يحصل أو يعيّن شفافية الطبقة. 0 = شفاف، 255 = معتم.

القيمة: شفافية الطبقة.

**Returns:**
byte
### getOpacityTotal_internalized() {#getOpacityTotal-internalized--}
```
public final byte getOpacityTotal_internalized()
```


يحصل على الشفافية الكلية. الشفافية الكلية هي حاصل ضرب شفافية الطبقة وشفافية تعبئة الطبقة. تُستخدم لدمج الطبقة.

القيمة: الشفافية الكلية.

**Returns:**
byte
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة  DataStreamSupporter.Save(string)  ، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومرّرها إلى طريقة  Image.Save(string, ImageOptionsBase)  كمعامل ثانٍ.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getOriginalQuadrilateral_internalized() {#getOriginalQuadrilateral-internalized--}
```
public final Quadrilateral getOriginalQuadrilateral_internalized()
```


يحصل أو يعيّن الشكل الرباعي الأصلي.

القيمة: رباعي الأضلاع الأصلي.

**Returns:**
com.aspose.internal.fileformats.psd.projective.Quadrilateral
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


يحصل على الصورة القابلة للرسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


يحصل على لوحة الألوان. لا يتم استخدام لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


يحصل على بكسل الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | موقع بكسل س. |
| ص | int | موقع بكسل ص. |

**Returns:**
[Color](../../com.aspose.psd/color) - The pixel color for the specified location.
### getPlacedLayerResource_internalized(LayerResource[] resources, int[] placedResourceIndex, int[] smartResourceIndex) {#getPlacedLayerResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource---int---int---}
```
public static PlacedResource getPlacedLayerResource_internalized(LayerResource[] resources, int[] placedResourceIndex, int[] smartResourceIndex)
```


يحصل على مؤشرات موارد الطبقة الموضوعة والذكية والموارد الموضوعة المناسبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resources | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) | الموارد. |
| placedResourceIndex | int[] | فهرس المورد الموضوع. |
| smartResourceIndex | int[] | فهرس المورد الذكي. |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - The proper placed or smart [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) instance.
### getPlacedResource_internalized() {#getPlacedResource-internalized--}
```
public final PlacedResource getPlacedResource_internalized()
```


يحصل على مورد الطبقة الموضوعة.

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource)
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا.

**Returns:**
boolean -  true  إذا كان يجب ضرب مكونات الصورة مسبقًا؛ وإلا،  false .
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


ينشئ ذاكرة التخزين المؤقت للخطوط الخاصة.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - ذاكرة التخزين المؤقت للخطوط الخاصة.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


يحصل على معلومات معالج حدث التقدم.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


يحصل على معلومات معالج حدث التقدم.

القيمة: معلومات معالج حدث التقدم.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


يحصل على ارتفاع نسبي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | العرض. |
| الارتفاع | int | الارتفاع. |
| newWidth | int | العرض الجديد. |

**Returns:**
int - الارتفاع النسبي.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


يحصل على عرض نسبي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | العرض. |
| الارتفاع | int | الارتفاع. |
| newHeight | int | الارتفاع الجديد. |

**Returns:**
int - العرض النسبي.
### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


يحصل أو يضبط محول اللون المخصص

**Returns:**
[IColorConverter](../../com.aspose.psd/icolorconverter) - The custom color converter
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


يحصل على تنسيق البيانات الخام.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The raw data format.
### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


يحصل على إعدادات البيانات الخام الحالية. لاحظ أنه عند استخدام هذه الإعدادات يتم تحميل البيانات دون تحويل.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings)
### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


يحصل أو يضبط فهرس الاحتياطي للاستخدام عندما يكون فهرس اللوحة خارج النطاق

**Returns:**
int - الفهرس الاحتياطي للاستخدام عندما يكون فهرس لوحة الألوان خارج النطاق
### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


يحصل أو يضبط محول اللون المفهرس

**Returns:**
[IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) - The indexed color converter
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


يحصل على حجم السطر الخام بالبايت.

**Returns:**
int - حجم السطر الخام بالبايت.
### getResources() {#getResources--}
```
public final LayerResource[] getResources()
```


يحصل أو يضبط موارد الطبقة.

القيمة: موارد الطبقة.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getRight() {#getRight--}
```
public int getRight()
```


يحصل أو يضبط موضع الطبقة اليمنى.

القيمة: موضع الطبقة اليمنى.

**Returns:**
int
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


يحصل أو يعيّن وضع الدوران.

**Returns:**
int - وضع الدوران.
### getSheetColorHighlight() {#getSheetColorHighlight--}
```
public final short getSheetColorHighlight()
```


يحصل أو يعيّن تمييز لون الورقة الزخرفية في قائمة الطبقات

القيمة: تمييز لون الورقة.

**Returns:**
short
### getSize() {#getSize--}
```
public Size getSize()
```


يحصل على حجم الصورة.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


يحصل على زاوية الانحراف. هذه الطريقة تنطبق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف عند المسح.

**Returns:**
float - زاوية الانحراف، بالدرجات.
### getSmartFilters() {#getSmartFilters--}
```
public final SmartFilters getSmartFilters()
```


يحصل على الفلاتر الذكية.

**Returns:**
[SmartFilters](../../com.aspose.psd.fileformats.psd.layers.smartfilters/smartfilters)
### getSmartObjectProvider() {#getSmartObjectProvider--}
```
public final SmartObjectProvider getSmartObjectProvider()
```


الحصول على موفر الكائن الذكي.

القيمة: موفر الكائن الذكي.

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


يحصل على مسار ملف الصورة المصدر إذا كان موجودًا. يعيد سلسلة فارغة إذا تعذر العثور على المسار المصدر.

**Returns:**
java.lang.String - مسار ملف الصورة المصدر.
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


يحصل على جذر المزامنة.

القيمة: جذر المزامنة.

**Returns:**
java.lang.Object
### getTop() {#getTop--}
```
public int getTop()
```


يحصل أو يعيّن موضع الطبقة العليا.

القيمة: موضع الطبقة العليا.

**Returns:**
int
### getTransformedQuadrilateral_internalized() {#getTransformedQuadrilateral-internalized--}
```
public final Quadrilateral getTransformedQuadrilateral_internalized()
```


يحصل أو يعيّن الشكل الرباعي للتحويل.

القيمة: رباعي الأضلاع التحويلي.

**Returns:**
com.aspose.internal.fileformats.psd.projective.Quadrilateral
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


يحصل على لون شفافية الصورة.

**Returns:**
[Color](../../com.aspose.psd/color)
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية.

**Returns:**
boolean -  true  إذا تم تحديث بيانات XMP الوصفية؛ وإلا،  false .
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


يحصل على قيمة تشير إلى ما إذا كان الكائن يستخدم استراتيجية تحسين الذاكرة

القيمة:  true  إذا كان الكائن يستخدم استراتيجية تحسين الذاكرة؛ وإلا،  false .

**Returns:**
boolean - قيمة تشير إلى ما إذا كان الكائن يستخدم استراتيجية تحسين الذاكرة
### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا.

**Returns:**
boolean -  true  إذا تم استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا؛ وإلا،  false .
### getUsedPalette_internalized() {#getUsedPalette-internalized--}
```
public final IColorPalette getUsedPalette_internalized()
```


يحصل على اللوحة المستخدمة.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - the used palette.
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


يحصل على رخصة المشروع.

**Returns:**
java.lang.Object - رخصة المشروع ككائن.
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


يحصل أو يعيّن الدقة العمودية، بوحدة البكسل لكل بوصة، لهذه RasterImage.

**Returns:**
double - الدقة العمودية.

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيمتي الدقة معًا في استدعاء واحد.
### getWarpProvider_internalized() {#getWarpProvider-internalized--}
```
public final SmartObjectWarpProvider getWarpProvider_internalized()
```


يحصل على وظائف تساعد في التشويه

**Returns:**
com.aspose.internal.fileformats.psd.layers.warp.SmartObjectWarpProvider
### getWarpSettings() {#getWarpSettings--}
```
public final WarpSettings getWarpSettings()
```


يحصل أو يضبط معلمات التشويه التي تم ضبطها أو الحصول عليها من المورد (افتراضي)

**Returns:**
[WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings)
### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل على عرض الصورة.

القيمة: عرض الصورة.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


يحصل أو يعيّن بيانات XMP الوصفية.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP metadata.
### grayscale() {#grayscale--}
```
public void grayscale()
```


تحويل الصورة إلى تمثيلها بتدرج الرمادي

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


يحصل على قيمة تشير إلى ما إذا كانت هذه النسخة تحتوي على قناة ألفا.

القيمة:  true  إذا كان لهذا الكائن ألفا؛ وإلا،  false .

**Returns:**
boolean
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية.

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت نسخة الصورة هذه قد تغيرت بعد التحميل.

**Returns:**
boolean -  true  إذا كان لهذا الكائن تم تغيير الصورة؛ وإلا،  false .
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة لهذا الكائن.

**Returns:**
int - رمز تجزئة لهذا الكائن، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
### incrementProgressMaxValue_internalized(int value) {#incrementProgressMaxValue-internalized-int-}
```
public final void incrementProgressMaxValue_internalized(int value)
```


يحصل أو يعيّن القيمة القصوى للتقدم

القيمة: الحد الأقصى للتقدم

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


يشير إلى التقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### insertResource_internalized(int index, LayerResource resource) {#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void insertResource_internalized(int index, LayerResource resource)
```


إدراج مورد إلى مجموعة الموارد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الفهرس | int | فهرس المورد الذي يجب إدراجه. |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | المورد الذي يجب إدراجه. |

### isCached() {#isCached--}
```
public boolean isCached()
```


يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا.

**Returns:**
boolean -  true  إذا تم تخزين بيانات الصورة مؤقتًا؛ وإلا،  false .
### isLayerValid_internalized() {#isLayerValid-internalized--}
```
public boolean isLayerValid_internalized()
```


يكشف ما إذا كانت الطبقة صالحة للحفظ في ملف.

**Returns:**
boolean -
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا.

**Returns:**
boolean -  true  إذا كان تحميل البيانات الخام متاحًا؛ وإلا،  false .
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة.

القيمة:  true  إذا تم استخدام لوحة الألوان في الصورة؛ وإلا،  false .

**Returns:**
boolean - قيمة تشير إلى ما إذا تم استخدام لوحة ألوان الصورة.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الطبقة مرئية

القيمة:  true  إذا كان هذا الكائن مرئيًا؛ وإلا،  false .

**Returns:**
boolean
### isVisibleInGroup() {#isVisibleInGroup--}
```
public boolean isVisibleInGroup()
```


يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة مرئية في المجموعة (إذا لم تكن الطبقة في مجموعة فهذا يعني مجموعة الجذر).

القيمة:  true  إذا كان هذا الكائن مرئيًا في المجموعة؛ وإلا،  false .

**Returns:**
boolean
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


يحمّل صورة جديدة من الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | الدفق لتحميل الصورة منه. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


يحمّل صورة جديدة من الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | الدفق لتحميل الصورة منه. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | خيارات التحميل. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


يحمّل صورة جديدة من الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ملف | java.io.RandomAccessFile | الملف لتحميل الصورة منه. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


يحمّل صورة جديدة من الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ملف | java.io.RandomAccessFile | الملف لتحميل الصورة منه. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | خيارات التحميل. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


يحمّل صورة جديدة من الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف لتحميل الصورة منه. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


يحمّل صورة جديدة من الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف لتحميل الصورة منه. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | خيارات التحميل. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


يحمّل بكسلات ARGB 32‑بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل لتحميل البكسلات منه. |

**Returns:**
int[] - مصفوفة البكسلات ARGB 32-بت المحملة.
### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.psd.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


يحمّل بكسلات ARGB 64‑بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل لتحميل البكسلات منه. |

**Returns:**
long[] - مصفوفة البكسلات ARGB 64-بت المحملة.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


يحمّل البكسلات بتنسيق CMYK.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل لتحميل البكسلات منه. |

**Returns:**
int[] - مصفوفة البكسلات CMYK المحملة كقيم صحيحة 32-بت.
### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.psd.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


يقوم بتحميل البكسلات بتنسيق CMYK. هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فاعلية loadCmyk32Pixels(Rectangle).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل لتحميل البكسلات منه. |

**Returns:**
com.aspose.psd.CmykColor[] - مصفوفة البكسلات CMYK المحملة.
### loadContents(LoadOptions options) {#loadContents-com.aspose.psd.LoadOptions-}
```
public final Image loadContents(LoadOptions options)
```


يحصل على محتويات الصورة المدمجة أو المرتبطة بطبقة الكائن الذكي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [LoadOptions](../../com.aspose.psd/loadoptions) | الخيارات. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded  Image  smart object instance.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


يحمّل بكسلات ARGB 32‑بت جزئياً عن طريق الحزم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل المطلوب. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | محمل بكسل ARGB 32-بت. |

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


يحمّل البكسلات جزئياً عن طريق الحزم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل المطلوب. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | محمل البكسل. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.psd.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


يحمّل البكسلات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل لتحميل البكسلات منه. |

**Returns:**
com.aspose.psd.Color[] - مصفوفة البكسلات المحملة.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


يحمّل بيانات الصورة الخام باستخدام آلية المعالجة الجزئية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المنطقة المستطيلة المطلوبة في الصورة لتحميل البيانات منها. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | إعدادات البيانات الخام. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | محمل البيانات الخام. |

### loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


يحمّل البيانات الخام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل لتحميل البيانات الخام منه. |
| destImageBounds | [Rectangle](../../com.aspose.psd/rectangle) | حدود الصورة الوجهة. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | إعدادات البيانات الخام لاستخدامها مع البيانات المحملة. ملاحظة: إذا لم تكن البيانات بالتنسيق المحدد فسيتم إجراء تحويل للبيانات. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | محمل البيانات الخام. |

### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


يحمّل صورة جديدة من الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | الدفق لتحميل الصورة منه. |
| startPosition | long | موضع البداية لتحميل الصورة منه. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


يحمّل صورة جديدة من الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | الدفق لتحميل الصورة منه. |
| startPosition | long | موضع البداية لتحميل الصورة منه. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | خيارات التحميل. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### mergeLayerTo(Layer layerToMergeInto) {#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public void mergeLayerTo(Layer layerToMergeInto)
```


يدمج الطبقة مع الطبقة المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| layerToMergeInto | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | الطبقة التي سيتم الدمج فيها. |

### newSmartObjectViaCopy() {#newSmartObjectViaCopy--}
```
public final SmartObjectLayer newSmartObjectViaCopy()
```


إنشاء طبقة كائن ذكي جديدة بنسخ هذه الطبقة. يعيد إنتاج Layer -> Smart Objects -> New Smart Object عبر وظيفة النسخ في Adobe\ufffd Photoshop\ufffd. لاحظ أنه مفعل فقط للكائنات الذكية المدمجة لأن الصورة المدمجة تُنسخ أيضًا. إذا كنت تريد مشاركة الصورة المدمجة استخدم طريقة [.duplicateLayer](../../null/\#duplicateLayer).

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The cloned [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


يقوم بتطبيع الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف في المسح. تستخدم هذه الطريقة [.getSkewAngle](../../null/\#getSkewAngle) و [.rotate(float)](../../null/\#rotate-float-).

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.psd.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


يقوم بتطبيع الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف في المسح. تستخدم هذه الطريقة [.getSkewAngle](../../null/\#getSkewAngle) و [.rotate(float, boolean, Color)](../../null/\#rotate-float--boolean--Color-).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تغيير الحجم بشكل متناسب | boolean | إذا تم تعيينه إلى  true  سيتغير حجم الصورة وفقاً لإسقاطات المستطيل المدور (نقاط الزوايا)؛ وفي الحالة الأخرى تُترك الأبعاد دون تغيير وتُدور محتويات الصورة الداخلية فقط. |
| backgroundColor | [Color](../../com.aspose.psd/color) | لون الخلفية. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onContainerSet_internalized() {#onContainerSet-internalized--}
```
public void onContainerSet_internalized()
```


يتم الاستدعاء عندما تم تعيين حاوية هذا [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


يقرأ السطر الكامل للمسح وفقًا لمؤشر سطر المسح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scanLineIndex | int | فهرس الصف الماسح يبدأ من الصفر. |

**Returns:**
int[] - مصفوفة قيم ألوان ARGB 32-bit لصف المسح.
### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


يقرأ السطر الكامل للمسح وفقًا لمؤشر سطر المسح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scanLineIndex | int | فهرس الصف الماسح يبدأ من الصفر. |

**Returns:**
com.aspose.psd.Color[] - مصفوفة قيم ألوان بكسل صف المسح.
### relinkToFile(String linkedPath) {#relinkToFile-java.lang.String-}
```
public final void relinkToFile(String linkedPath)
```


إعادة ربط الكائن الذكي المرتبط بملف جديد. لا حاجة لاستدعاء طريقة UpdateModifiedContent بعد ذلك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| linkedPath | java.lang.String | المسار المرتبط. |

### removeResource_internalized(LayerResource resource) {#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void removeResource_internalized(LayerResource resource)
```


يزيل المورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | المورد. |

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.psd/color) | اللون القديم الذي سيتم استبداله. |
| oldColorDiff | byte | الفرق المسموح به في اللون القديم لتمكين توسيع نغمة اللون المستبدل. |
| newColor | [Color](../../com.aspose.psd/color) | اللون الجديد لاستبدال اللون القديم به. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| oldColorArgb | int | قيمة ARGB للون القديم التي سيتم استبدالها. |
| oldColorDiff | byte | الفرق المسموح به في اللون القديم لتمكين توسيع نغمة اللون المستبدل. |
| newColorArgb | int | قيمة ARGB للون الجديد لاستبدال اللون القديم بها. |

### replaceContents(Image image) {#replaceContents-com.aspose.psd.Image-}
```
public final void replaceContents(Image image)
```


يستبدل محتويات الكائن الذكي المدمجة في طبقة الكائن الذكي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | الصورة. |

### replaceContents(Image image, ResolutionSetting resolution) {#replaceContents-com.aspose.psd.Image-com.aspose.psd.ResolutionSetting-}
```
public final void replaceContents(Image image, ResolutionSetting resolution)
```


يستبدل محتويات الكائن الذكي المدمجة في طبقة الكائن الذكي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | الصورة. |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | إعدادات الدقة. إذا كانت القيمة null سيتم استخدام دقة الصورة. |

### replaceContents(String linkedPath) {#replaceContents-java.lang.String-}
```
public final void replaceContents(String linkedPath)
```


يستبدل المحتوى بملف. لا حاجة لاستدعاء طريقة UpdateModifiedContent بعد ذلك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| linkedPath | java.lang.String | المسار المرتبط. |

### replaceContents(String linkedPath, boolean isReplaceOnlyThis) {#replaceContents-java.lang.String-boolean-}
```
public final void replaceContents(String linkedPath, boolean isReplaceOnlyThis)
```


يستبدل المحتوى بملف. لا حاجة لاستدعاء طريقة UpdateModifiedContent بعد ذلك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| linkedPath | java.lang.String | المسار المرتبط. |
| isReplaceOnlyThis | boolean | العلم يُظهر استبدال المحتوى من هذه الطبقة الذكية أو لجميع الطبقات الذكية بهذا المحتوى. |

### replaceContents(String linkedPath, ResolutionSetting resolution) {#replaceContents-java.lang.String-com.aspose.psd.ResolutionSetting-}
```
public final void replaceContents(String linkedPath, ResolutionSetting resolution)
```


يستبدل المحتوى بملف. لا حاجة لاستدعاء طريقة UpdateModifiedContent بعد ذلك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| linkedPath | java.lang.String | المسار المرتبط. |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | إعدادات الدقة. إذا كانت القيمة null سيتم استخدام دقة الصورة. |

### replaceContents(String linkedPath, ResolutionSetting resolution, boolean isReplaceOnlyThis) {#replaceContents-java.lang.String-com.aspose.psd.ResolutionSetting-boolean-}
```
public final void replaceContents(String linkedPath, ResolutionSetting resolution, boolean isReplaceOnlyThis)
```


يستبدل المحتوى بملف. لا حاجة لاستدعاء طريقة UpdateModifiedContent بعد ذلك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| linkedPath | java.lang.String | المسار المرتبط. |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | إعدادات الدقة. إذا كانت القيمة null سيتم استخدام دقة الصورة. |
| isReplaceOnlyThis | boolean | العلم يُظهر استبدال المحتوى من هذه الطبقة الذكية أو لجميع الطبقات الذكية بهذا المحتوى. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.psd.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


يستبدل جميع الألوان غير الشفافة باللون الجديد ويحافظ على قيمة ألفا الأصلية للحفاظ على الحواف الناعمة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.psd/color) | اللون الجديد لاستبدال الألوان غير الشفافة به. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


يستبدل جميع الألوان غير الشفافة باللون الجديد ويحافظ على قيمة ألفا الأصلية للحفاظ على الحواف الناعمة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorArgb | int | قيمة ARGB للون الجديد لاستبدال الألوان غير الشفافة به. |

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


يعيد تحجيم الصورة. يتم استخدام القيمة الافتراضية ResizeType.LeftTopToLeftTop.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


يغير حجم الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | إعدادات تغيير الحجم. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


يغير حجم الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع التحجيم. |

### resizeChannelsData_internalized(Rectangle rect) {#resizeChannelsData-internalized-com.aspose.psd.Rectangle-}
```
public void resizeChannelsData_internalized(Rectangle rect)
```


يعيد تحجيم بيانات القنوات

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


يعيد تحجيم الارتفاع بنسبة متناسبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newHeight | int | الارتفاع الجديد. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


يعيد تحجيم الارتفاع بنسبة متناسبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newHeight | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | إعدادات تحجيم الصورة. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


يعيد تحجيم الارتفاع بنسبة متناسبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع التحجيم. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


يعيد تحجيم العرض بنسبة متناسبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


يعيد تحجيم العرض بنسبة متناسبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | إعدادات تحجيم الصورة. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


يعيد تحجيم العرض بنسبة متناسبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| resizeType | int | نوع التحجيم. |

### resizeWithScale_internalized(double scaleX, double scaleY, int resizeType) {#resizeWithScale-internalized-double-double-int-}
```
public final void resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)
```


يعيد تحجيم الطبقة باستخدام المقياس العكسي المحدد. (العرض الجديد = العرض القديم / المقياس؛ الارتفاع الجديد = الارتفاع القديم / المقياس)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scaleX | double | المقياس X. |
| scaleY | double | المقياس Y. |
| resizeType | int | نوع التحجيم. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


تدوير الصورة حول المركز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران بالدرجات. القيم الموجبة تدور باتجاه عقارب الساعة. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.psd.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


تدوير الصورة حول المركز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران بالدرجات. القيم الموجبة تدور باتجاه عقارب الساعة. |
| تغيير الحجم بشكل متناسب | boolean | إذا تم تعيينه إلى  true  سيتغير حجم الصورة وفقاً لإسقاطات المستطيل المدور (نقاط الزوايا)؛ وفي الحالة الأخرى تُترك الأبعاد دون تغيير وتُدور محتويات الصورة الداخلية فقط. |
| backgroundColor | [Color](../../com.aspose.psd/color) | لون الخلفية. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


يدور، يقلب، أو يدور ويقلب الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع التدوير والقلب | int |  |

### save() {#save--}
```
public final void save()
```


يحفظ بيانات الصورة إلى الدفق الأساسي.

### save(System.IO.Stream stream) {#save-com.aspose.ms.System.IO.Stream-}
```
public void save(System.IO.Stream stream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | المجرى لحفظ بيانات الكائن إليه. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | المجرى لحفظ بيانات الصورة إليه. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | خيارات الحفظ. |

### save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dstStream | java.io.OutputStream | المجرى لحفظ بيانات الصورة إليه. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | خيارات الحفظ. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل حدود الصورة الهدف. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ملف | java.io.RandomAccessFile | المجرى لحفظ بيانات الكائن إليه. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


يحفظ بيانات الكائن إلى الموقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ملف | java.io.RandomAccessFile | الملف لحفظ بيانات الصورة إليه. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | الخيارات. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ملف | java.io.RandomAccessFile | الملف لحفظ بيانات الصورة إليه. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | خيارات الحفظ. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل حدود الصورة الهدف. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


يحفظ بيانات الكائن إلى الموقع الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف لحفظ بيانات الكائن فيه. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


يحفظ بيانات الكائن إلى الموقع الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف لحفظ بيانات الكائن فيه. |
| overWrite | boolean | إذا تم تعيينه إلى  true  فستتم كتابة محتويات الملف، وإلا سيحدث الإلحاق. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


يحفظ بيانات الكائن إلى الموقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | الخيارات. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


يحفظ بيانات الكائن إلى الموقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | الخيارات. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل حدود الصورة الهدف. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


يحفظ بكسلات ARGB 32-بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل لحفظ البكسلات فيه. |
| بكسلات | int[] | مصفوفة بكسلات ARGB 32-بت. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


يحفظ البكسلات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل لحفظ البكسلات فيه. |
| بكسلات | int[] | بكسلات CMYK مقدمة كقيم صحيحة 32-بت. |

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


يحفظ البكسلات. هذه الطريقة مهجورة. يرجى استخدام الطريقة الأكثر فعالية  saveCmyk32Pixels(Rectangle, int[]) .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل لحفظ البكسلات فيه. |
| pixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | مصفوفة بكسلات CMYK. |

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


يحفظ البكسلات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل لحفظ البكسلات فيه. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | مصفوفة البكسلات. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


يحفظ البيانات الخام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | byte[] | البيانات الخام. |
| dataOffset | int | إزاحة بدء البيانات الخام. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل البيانات الخام. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | إعدادات البيانات الخام التي توجد فيها البيانات. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | المجرى لحفظ بيانات الصورة إليه. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | خيارات الحفظ. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth) {#save-internalized-com.aspose.psd.StreamContainer-int-int-}
```
public final void save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)
```


يحفظ البيانات إلى حاوية الدفق المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |
| psdVersion | int | إصدار PSD. |
| bitDepth | int | عمق البت. |

### setAbsoluteBounds_internalized(Rectangle value) {#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setAbsoluteBounds_internalized(Rectangle value)
```


يحصل أو يضبط الحدود المطلقة.

القيمة: الحدود المطلقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setAllowWarpRepaint_internalized(boolean value) {#setAllowWarpRepaint-internalized-boolean-}
```
public final void setAllowWarpRepaint_internalized(boolean value)
```


يحصل أو يعيّن تشويه العرض أو يستخدم صورة PS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


يضبط بكسل صورة ARGB 32-بت للموقع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | موقع بكسل س. |
| ص | int | موقع بكسل ص. |
| argb32Color | int | بكسل ARGB 32-بت للموقع المحدد. |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان يتم تعديل لوحة الألوان تلقائيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | true  إذا تم تمكين تعديل لوحة الألوان تلقائيًا؛ وإلا،  false . |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


يحصل على أو يعيّن قيمة للون الخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBlendClippedElements(boolean value) {#setBlendClippedElements-boolean-}
```
public final void setBlendClippedElements(boolean value)
```


يحصل على أو يعيّن دمج العنصر المقصوص.

القيمة: دمج العنصر المقصوص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setBlendModeKey(long value) {#setBlendModeKey-long-}
```
public void setBlendModeKey(long value)
```


يحصل على أو يعيّن مفتاح وضع الدمج.

القيمة: مفتاح وضع الدمج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


يحصل على أو يعيّن موضع الطبقة السفلية.

القيمة: موضع الطبقة السفلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الموجبة تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |

### setChannelInformation(ChannelInformation[] value) {#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public final void setChannelInformation(ChannelInformation[] value)
```


يحصل على أو يعيّن معلومات القناة.

القيمة: معلومات القناة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) |  |

### setClipping(byte value) {#setClipping-byte-}
```
public final void setClipping(byte value)
```


يحصل أو يعيّن قص الطبقة. 0 = أساسي، 1 = غير أساسي.

القيمة: قص الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


يضبط حاوية الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | حاوية  Image . |

### setContents(byte[] value) {#setContents-byte---}
```
public final void setContents(byte[] value)
```


يحصل أو يضبط محتويات طبقة الكائن الذكي. محتويات الكائن الذكي المضمنة هي ملف الصورة الخام المضمن:  LiFdDataSource.Data  وخصائصه. محتويات الكائن الذكي المرتبط هي المحتوى الخام لملف الصورة المرتبطة إذا كان متاحًا وخصائصه: [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource). لا ندعم التحميل من مكتبة الرسومات Adobe\\ufffd Photoshop\\ufffd \\ufffd\\ufffd عندما تكون  LinkDataSource.IsLibraryLink ([LinkDataSource.isLibraryLink()](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource\#isLibraryLink--)/[LinkDataSource.setLibraryLink(boolean)](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource\#setLibraryLink-boolean-)) صحيحة. بالنسبة لملفات الارتباط العادية، في البداية نستخدم  LiFeDataSource.RelativePath ([LiFeDataSource.getRelativePath](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource\#getRelativePath)/[LiFeDataSource.setRelativePath(String)](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource\#setRelativePath-String-)) للبحث عن الملف نسبةً إلى مسار صورة المصدر  DataStreamSupporter.SourceImagePath ، إذا لم يكن متاحًا نبحث في  LiFeDataSource.FullPath ([LiFeDataSource.getFullPath](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource\#getFullPath)/[LiFeDataSource.setFullPath(String)](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource\#setFullPath-String-))، وإذا لم يكن كذلك نبحث عن ملف الارتباط في نفس الدليل الذي توجد فيه صورتنا:  DataStreamSupporter.SourceImagePath .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### setContentsBounds(Rectangle value) {#setContentsBounds-com.aspose.psd.Rectangle-}
```
public final void setContentsBounds(Rectangle value)
```


يحصل أو يعيّن حدود محتوى الكائن الذكي.

القيمة: حدود الكائن الذكي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setContentsSource(LinkDataSource value) {#setContentsSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void setContentsSource(LinkDataSource value)
```


يحصل أو يعيّن مصدر محتوى الكائن الذكي.

القيمة: مصدر بيانات الكائن الذكي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) |  |

### setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader) {#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-}
```
public void setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)
```


يضبط محمل البيانات مباشرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) | محمل البيانات. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


يضبط دفق بيانات الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | دفق بيانات الكائن. |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


يحصل أو يضبط الاسم المعروض للطبقة.

القيمة: الاسم المعروض للطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setFillOpacity(int value) {#setFillOpacity-int-}
```
public final void setFillOpacity(int value)
```


يحصل على شفافية التعبئة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setFiller(byte value) {#setFiller-byte-}
```
public final void setFiller(byte value)
```


يحصل أو يضبط ملء الطبقة.

القيمة: مملئ الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


الحصول على أو تعيين أعلام الطبقة. البت 0 = حماية الشفافية؛ البت 1 = مرئي؛ البت 2 = مهمل؛ البت 3 = 1 لبرنامج Photoshop 5.0 وما بعده، يوضح ما إذا كان البت 4 يحتوي على معلومات مفيدة؛ البت 4 = بيانات البكسل غير ذات صلة بمظهر المستند.

القيمة: أعلام الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### setFormatSpecificPalette_internalized(IColorPalette newPalette) {#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-}
```
public boolean setFormatSpecificPalette_internalized(IColorPalette newPalette)
```


يضبط لوحة الألوان في الأماكن الخاصة بالتنسيق

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | لوحة ألوان ARGB 32-بت جديدة. |

**Returns:**
boolean
### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


يحصل أو يضبط الرأس.

القيمة: الترويسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


يحصل أو يضبط الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذا  RasterImage .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | double | الدقة الأفقية. |

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان [تجاهل بعد الحفظ].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | صحيح إذا [ignore after save]؛ وإلا، خطأ. |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت نسخة الصورة هذه قد تغيرت بعد التحميل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | صحيح إذا كان هذا الكائن قد غيّر الصورة؛ وإلا، خطأ. |

### setImageSizeBeforeChange_internalized(Size value) {#setImageSizeBeforeChange-internalized-com.aspose.psd.Size-}
```
public final void setImageSizeBeforeChange_internalized(Size value)
```


يحصل أو يعيّن الحجم الأخير للصورة لتشويهها

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setInnerDataTransformer_internalized(IInnerDataTransformer value) {#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-}
```
public final void setInnerDataTransformer_internalized(IInnerDataTransformer value)
```


يضبط محول البيانات الداخلي.

القيمة: محول البيانات الداخلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.internal.IInnerDataTransformer | محول البيانات الداخلي. |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


يضبط مراقب المقاطعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | مراقب المقاطعة. |

### setLayerBlendingRangesData(LayerBlendingRangesData value) {#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-}
```
public final void setLayerBlendingRangesData(LayerBlendingRangesData value)
```


يحصل أو يضبط بيانات نطاقات دمج الطبقة.

القيمة: بيانات نطاقات دمج الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata) |  |

### setLayerCreationDateTime(Date value) {#setLayerCreationDateTime-java.util.Date-}
```
public final void setLayerCreationDateTime(Date value)
```


يحصل أو يضبط تاريخ ووقت إنشاء الطبقة.

القيمة: تاريخ ووقت إنشاء الطبقة. إذا لم تتوفر بيانات حول تاريخ ووقت الإنشاء فستُرجع زمن يونكس من البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.Date |  |

### setLayerCreationDateTime_internalized(System.DateTime value) {#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-}
```
public final void setLayerCreationDateTime_internalized(System.DateTime value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.ms.System.DateTime |  |

### setLayerLock(int value) {#setLayerLock-int-}
```
public final void setLayerLock(int value)
```


يحصل أو يعيّن قفل الطبقة (ملاحظة أنه إذا تم تعيين العلامة LayerFlags.TransparencyProtected فستُستبدل بعلامة قفل الطبقة. لإرجاع علامة LayerFlags.TransparencyProtected تحتاج إلى تطبيقها على خيار الطبقة layer.Flags |= LayerFlags.TransparencyProtected

القيمة: قفل الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setLayerMaskData(LayerMaskData value) {#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void setLayerMaskData(LayerMaskData value)
```


يحصل أو يضبط بيانات قناع الطبقة.

القيمة: بيانات قناع الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) |  |

### setLayerPalette_internalized(IColorPalette value) {#setLayerPalette-internalized-com.aspose.psd.IColorPalette-}
```
public final void setLayerPalette_internalized(IColorPalette value)
```


يحصل أو يضبط لوحة ألوان الطبقة.

القيمة: لوحة ألوان الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


يحصل أو يضبط موضع الطبقة اليسرى.

القيمة: موضع الطبقة اليسرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setMaxAllowedAllocationForPartialRotateSave_internalized(int value) {#setMaxAllowedAllocationForPartialRotateSave-internalized-int-}
```
public static void setMaxAllowedAllocationForPartialRotateSave_internalized(int value)
```


يحصل أو يضبط الحد الأقصى المسموح به للتخصيص لحفظ الدوران الجزئي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الحد الأقصى المسموح به للتخصيص لحفظ الدوران الجزئي. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


يضبط مدير الذاكرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | مدير الذاكرة. |
| needDispose | boolean | إذا تم تعيينه إلى  صحيح  [need dispose]. |

### setName(String name) {#setName-java.lang.String-}
```
public final void setName(String name)
```


يضبط اسم الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم الطبقة. |

### setName_internalized(String value) {#setName-internalized-java.lang.String-}
```
public final void setName_internalized(String value)
```


يحصل أو يضبط اسم الطبقة.

القيمة: اسم الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


يحصل أو يعيّن شفافية الطبقة. 0 = شفاف، 255 = معتم.

القيمة: شفافية الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### setOriginalQuadrilateral_internalized(Quadrilateral value) {#setOriginalQuadrilateral-internalized-com.aspose.internal.fileformats.psd.projective.Quadrilateral-}
```
public final void setOriginalQuadrilateral_internalized(Quadrilateral value)
```


يحصل أو يعيّن الشكل الرباعي الأصلي.

القيمة: رباعي الأضلاع الأصلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.internal.fileformats.psd.projective.Quadrilateral |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


يضبط لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | لوحة الألوان. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


يضبط لوحة ألوان الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | لوحة الألوان لتعيينها. |
| updateColors | boolean | إذا تم تعيينه إلى  صحيح  سيتم تحديث الألوان وفقًا للوحة الجديدة؛ وإلا ستبقى مؤشرات الألوان دون تغيير. ملاحظة أن المؤشرات غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض المؤشرات إدخالات لوحة مقابلة. |

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.psd.Color-}
```
public void setPixel(int x, int y, Color color)
```


يضبط بكسل الصورة للموقع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | موقع بكسل س. |
| ص | int | موقع بكسل ص. |
| color | [Color](../../com.aspose.psd/color) | لون البكسل للموقع المحدد. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | صحيح إذا كان يجب ضرب مكونات الصورة مسبقًا؛ وإلا، خطأ. |

### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.psd.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


يحصل أو يضبط محول اللون المخصص

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.psd/icolorconverter) | محول الألوان المخصص |

### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


يحصل أو يضبط فهرس الاحتياطي للاستخدام عندما يكون فهرس اللوحة خارج النطاق

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الفهرس الاحتياطي لاستخدامه عندما يكون فهرس اللوحة خارج النطاق |

### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


يحصل أو يضبط محول اللون المفهرس

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) | محول الألوان المفهرسة |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


يضبط الدقة لهذا  RasterImage .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dpiX | double | دقة الأفقية، بوحدات النقاط في البوصة، لصورة  RasterImage . |
| dpiY | double | دقة العمودية، بوحدات النقاط في البوصة، لصورة  RasterImage . |

### setResources(LayerResource[] value) {#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setResources(LayerResource[] value)
```


يحصل أو يضبط موارد الطبقة.

القيمة: موارد الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


يحصل أو يضبط موضع الطبقة اليمنى.

القيمة: موضع الطبقة اليمنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


يحصل أو يعيّن وضع الدوران.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | وضع الدوران. |

### setSheetColorHighlight(short value) {#setSheetColorHighlight-short-}
```
public final void setSheetColorHighlight(short value)
```


يحصل أو يعيّن تمييز لون الورقة الزخرفية في قائمة الطبقات

القيمة: تمييز لون الورقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setSmartObjectProvider_internalized(SmartObjectProvider value) {#setSmartObjectProvider-internalized-com.aspose.psd.fileformats.psd.SmartObjectProvider-}
```
public final void setSmartObjectProvider_internalized(SmartObjectProvider value)
```


الحصول على موفر الكائن الذكي.

القيمة: موفر الكائن الذكي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider) |  |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


يحصل أو يعيّن موضع الطبقة العليا.

القيمة: موضع الطبقة العليا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setTransformedQuadrilateral_internalized(Quadrilateral value) {#setTransformedQuadrilateral-internalized-com.aspose.internal.fileformats.psd.projective.Quadrilateral-}
```
public final void setTransformedQuadrilateral_internalized(Quadrilateral value)
```


يحصل أو يعيّن الشكل الرباعي للتحويل.

القيمة: رباعي الأضلاع التحويلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.internal.fileformats.psd.projective.Quadrilateral |  |

### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.psd.Color-}
```
public void setTransparentColor(Color value)
```


يحصل على لون شفافية الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | صحيح  إذا تم تحديث بيانات XMP الوصفية؛ وإلا،  خطأ . |

### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | صحيح  إذا تم استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا؛ وإلا،  خطأ . |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


يجب على جميع منتجات Aspose تنفيذ هذه الطريقة. يتم استدعاؤها من قبل منتج GroupDocs للإشارة إلى ما إذا كان GroupDocs نفسه مرخصًا أم لا وتحديد علامة مائية مخصصة. عندما يكون GroupDocs مرخصًا، يجب أن يتصرف كائن المستند هذا كمرخص أيضًا حتى إذا لم يكن منتج Aspose مرخصًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ventureLicense | java.lang.Object | license |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


يحصل أو يعيّن الدقة العمودية، بوحدة البكسل لكل بوصة، لهذه RasterImage.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | double | دقة العمودية. |

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد. |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الطبقة مرئية

القيمة:  true  إذا كان هذا الكائن مرئيًا؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setWarpSettings(WarpSettings value) {#setWarpSettings-com.aspose.psd.fileformats.psd.layers.warp.structs.WarpSettings-}
```
public final void setWarpSettings(WarpSettings value)
```


يحصل أو يضبط معلمات التشويه التي تم ضبطها أو الحصول عليها من المورد (افتراضي)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


يحصل أو يعيّن بيانات XMP الوصفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | بيانات XMP الوصفية. |

### shallowCopy() {#shallowCopy--}
```
public final Layer shallowCopy()
```


ينشئ نسخة سطحية من الطبقة الحالية. يرجى   للشرح.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - A shallow copy of the current Layer.
### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


يحول الصورة النقطية إلى bitmap.

**Returns:**
java.awt.image.BufferedImage - الصورة النقطية
### toBitmap_internalized() {#toBitmap-internalized--}
```
public System.Drawing.Bitmap toBitmap_internalized()
```




**Returns:**
com.aspose.ms.System.Drawing.Bitmap
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateBlendingOptions_internalized(PattResource pattResource) {#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public final void updateBlendingOptions_internalized(PattResource pattResource)
```


يقوم بتحديث خيارات الدمج بعد تغيير الطبقة أو الموارد العامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) |  |

### updateDataSourceId_internalized(System.Guid sourceId) {#updateDataSourceId-internalized-com.aspose.ms.System.Guid-}
```
public final void updateDataSourceId_internalized(System.Guid sourceId)
```


يحدّث معرف مصدر البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceId | com.aspose.ms.System.Guid | معرّف مصدر البيانات. |

### updateModifiedContent() {#updateModifiedContent--}
```
public final void updateModifiedContent()
```


يحدّث ذاكرة التخزين المؤقت لصورة طبقة الكائن الذكي بالمحتوى المعدل.

### updateModifiedContentWithImage_internalized(Image image, ResolutionSetting resolution, boolean skipBoundsUpdate) {#updateModifiedContentWithImage-internalized-com.aspose.psd.Image-com.aspose.psd.ResolutionSetting-boolean-}
```
public final void updateModifiedContentWithImage_internalized(Image image, ResolutionSetting resolution, boolean skipBoundsUpdate)
```


يحدّث ذاكرة التخزين المؤقت لصورة طبقة الكائن الذكي بالمحتوى المعدل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | الصورة. |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | الدقة. |
| skipBoundsUpdate | boolean | إذا تم تعيينه إلى true [تخطي تحديث الحدود]. |

### updatePlacedResources_internalized(boolean toEmbedded) {#updatePlacedResources-internalized-boolean-}
```
public final void updatePlacedResources_internalized(boolean toEmbedded)
```


يحدّث الموارد الموضوعة / الذكية عندما يتم تغيير placedResource أو عندما تكون التحويلة مطلوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| toEmbedded | boolean | إذا تم تعيينه إلى true يتحول إلى مورد مدمج إذا لزم الأمر، وإلا إلى مورد مرتبط. |

### updatePreview_internalized(PixelsData targetWarpedPixels) {#updatePreview-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-}
```
public final void updatePreview_internalized(PixelsData targetWarpedPixels)
```


إنه غلاف لـ "IWarpSupport" لتحديث معاينة الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| targetWarpedPixels | [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) | البكسلات وحجم صورة المعاينة الجديدة |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scanLineIndex | int | فهرس الصف الماسح يبدأ من الصفر. |
| argb32Pixels | int[] | مصفوفة ألوان ARGB 32-بت للكتابة. |

### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.psd.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scanLineIndex | int | فهرس الصف الماسح يبدأ من الصفر. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | مصفوفة ألوان البكسل للكتابة. |

