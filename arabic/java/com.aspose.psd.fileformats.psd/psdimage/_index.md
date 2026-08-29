---
title: "PsdImage"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يحدد فئة PsdImage التي توفر القدرة على تحميل وتحرير وحفظ ملفات PSD بالإضافة إلى تحديث الخصائص وإضافة العلامات المائية وإجراء عمليات رسومية أو تحويل تنسيق ملف إلى آخر."
type: docs
weight: 14
url: /ar/java/com.aspose.psd.fileformats.psd/psdimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage)
```
public final class PsdImage extends RasterCachedImage
```

يحدد فئة PsdImage التي توفر القدرة على تحميل وتحرير وحفظ ملفات PSD بالإضافة إلى تحديث الخصائص وإضافة العلامات المائية وإجراء عمليات رسومية أو تحويل تنسيق ملف إلى آخر. يدعم Aspose.PSD الاستيراد كطبقة والتصدير إلى الصيغ التالية: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb بالإضافة إلى التصدير إلى Pdf مع نص قابل للتحديد.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PsdImage(String path)](#PsdImage-java.lang.String-) | يُنشئ مثلاً جديداً من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) من المسار المحدد لصورة نقطية (ليس صورة PSD في المسار). |
| [PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.lang.String-short-short-short-int-short-) | يُنشئ مثلاً جديداً من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) من المسار المحدد لصورة نقطية (ليس صورة PSD في المسار) مع معلمات المُنشئ. |
| [PsdImage(InputStream stream)](#PsdImage-java.io.InputStream-) | يُنشئ مثلاً جديداً من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) من المسار المحدد لصورة نقطية (ليس صورة PSD في الدفق). |
| [PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.io.InputStream-short-short-short-int-short-) | يُنشئ مثلاً جديداً من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) من المسار المحدد لصورة نقطية (ليس صورة PSD في الدفق) مع معلمات المُنشئ. |
| [PsdImage(RasterImage rasterImage)](#PsdImage-com.aspose.psd.RasterImage-) | يُنشئ مثلاً جديداً من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) من صورة نقطية موجودة (ليس صورة PSD) بنمط ألوان RGB مع 4 قنوات 8 بت/قناة وبدون ضغط. |
| [PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-) | يُنشئ مثلاً جديداً من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) من صورة نقطية موجودة (ليس صورة PSD) مع معلمات المُنشئ. |
| [PsdImage(int width, int height)](#PsdImage-int-int-) | يُنشئ مثلاً جديداً من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) بعرض وارتفاع محددين. |
| [PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-) | يُنشئ مثلاً جديداً من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) بالعرض، الارتفاع، لوحة الألوان، نمط اللون، عدد القنوات وطول بت القنوات، ومعلمات وضع الضغط المحددة. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [DefaultStubEncodingName_internalized](#DefaultStubEncodingName-internalized) | اسم الترميز الافتراضي |
| [DefaultVersion](#DefaultVersion) | إصدار PSD الافتراضي. |
| [OnCreate_internalized](#OnCreate-internalized) | يحدث عندما تم تحميل الصورة |
| [OnLoad_internalized](#OnLoad-internalized) | يحدث عندما تم تحميل الصورة بواسطة createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | يحدث عندما تم تحميل الصورة أو حفظها |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | يحدث عندما تم استخدام الرصيد |
| [SyncLayersRoot_internalized](#SyncLayersRoot-internalized) | الكائن الذي يمكن استخدامه لمزامنة الوصول إلى الطبقات. |
| [horizontalResolution](#horizontalResolution) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addBlackWhiteAdjustmentLayer()](#addBlackWhiteAdjustmentLayer--) | يضيف طبقة تعديل بالأبيض والأسود. |
| [addBrightnessContrastAdjustmentLayer(int brightness, int contrast)](#addBrightnessContrastAdjustmentLayer-int-int-) | يضيف طبقة تعديل السطوع/التباين. |
| [addChannelMixerAdjustmentLayer()](#addChannelMixerAdjustmentLayer--) | يضيف طبقة تعديل خالط القنوات مع المعلمات الافتراضية. |
| [addColorBalanceAdjustmentLayer()](#addColorBalanceAdjustmentLayer--) | يضيف طبقة تعديل توازن الألوان. |
| [addCurvesAdjustmentLayer()](#addCurvesAdjustmentLayer--) | يضيف طبقة تعديل المنحنيات. |
| [addExposureAdjustmentLayer()](#addExposureAdjustmentLayer--) |  |
| [addExposureAdjustmentLayer(float exposure)](#addExposureAdjustmentLayer-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset)](#addExposureAdjustmentLayer-float-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)](#addExposureAdjustmentLayer-float-float-float-) | يضيف طبقة تعديل التعرض. |
| [addGradientMapAdjustmentLayer()](#addGradientMapAdjustmentLayer--) | يضيف طبقة تعديل خريطة التدرج. |
| [addHueSaturationAdjustmentLayer()](#addHueSaturationAdjustmentLayer--) | يضيف طبقة تعديل الصبغة/التشبع. |
| [addInvertAdjustmentLayer()](#addInvertAdjustmentLayer--) | يضيف طبقة تعديل عكس. |
| [addLayer(Layer layer)](#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | يضيف الطبقة. |
| [addLayerGroup(String groupName, int index, boolean startBehaviour)](#addLayerGroup-java.lang.String-int-boolean-) | يضيف مجموعة الطبقات. |
| [addLayer_internalized(Layer layer, int index)](#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-) | يضيف الطبقة عند الفهرس. |
| [addLevelsAdjustmentLayer()](#addLevelsAdjustmentLayer--) | يضيف طبقة تعديل المستويات. |
| [addPhotoFilterLayer(Color color)](#addPhotoFilterLayer-com.aspose.psd.Color-) | يضيف طبقة مرشح الصورة. |
| [addPosterizeAdjustmentLayer()](#addPosterizeAdjustmentLayer--) | يضيف طبقة تعديل Posterize. |
| [addRegularLayer()](#addRegularLayer--) | يضيف طبقة عادية جديدة. |
| [addSelectiveColorAdjustmentLayer()](#addSelectiveColorAdjustmentLayer--) | يضيف طبقة تعديل اللون الانتقائي. |
| [addShapeLayer()](#addShapeLayer--) | أضف طبقة شكل فارغة. |
| [addTextLayer(String text, Rectangle rect)](#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-) | يضيف طبقة نص جديدة. |
| [addThresholdAdjustmentLayer()](#addThresholdAdjustmentLayer--) | يضيف طبقة تعديل العتبة. |
| [addVibranceAdjustmentLayer()](#addVibranceAdjustmentLayer--) | يضيف طبقة تعديل الحيوية. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | ضبط السطوع للصورة. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | تباين الصورة |
| [adjustGamma(float gamma)](#adjustGamma-float-) | تصحيح غاما للصورة. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | تصحيح غاما للصورة. |
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
| [convert(PsdOptions newOptions)](#convert-com.aspose.psd.imageoptions.PsdOptions-) | يحوّل تنسيق هذه الصورة إلى التنسيق المحدد في الخيارات. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | يحول إلى aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| [createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-) | ينشئ نسخة جديدة من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-) |  |
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | يفلتر المستطيل المحدد. |
| [flattenImage()](#flattenImage--) | يقوم بدمج جميع الطبقات. |
| [getActiveLayer()](#getActiveLayer--) | يحصل أو يعيّن الطبقة النشطة. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | يحصل على بكسل صورة 32-بت ARGB. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | يحصل على قيمة تشير إلى ما إذا كان تعديل اللوحة تلقائيًا. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على أو يعيّن قيمة للون الخلفية. |
| [getBackgroundContents_internalized()](#getBackgroundContents-internalized--) | يحصل أو يعيّن لون الخلفية. |
| [getBitsPerChannel()](#getBitsPerChannel--) | يحصل على عدد البتات لكل قناة. |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد البتات لكل بكسل في الصورة. |
| [getBounds()](#getBounds--) | يحصل على حدود الصورة. |
| [getBufferSizeHint()](#getBufferSizeHint--) | يحصل على تلميح حجم المخزن المؤقت الذي يُعرّف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [getChannelsCount()](#getChannelsCount--) | يحصل على عدد قنوات PSD. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | يحصل أو يعيّن ملف تعريف اللون CMYK لصور PSD بنظام CMYK. |
| [getColorMode()](#getColorMode--) | يحصل أو يعيّن وضع اللون. |
| [getCompression()](#getCompression--) | يحصل على طريقة الضغط. |
| [getContainer()](#getContainer--) | يحصل على حاوية الصورة. |
| [getCurrentOptions_internalized()](#getCurrentOptions-internalized--) | يحصل على خيارات الصورة الحالية. |
| [getDataStreamContainer()](#getDataStreamContainer--) | يحصل على تدفق بيانات الكائن. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | يحصل على تعديل عميق للوحة الألوان. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | يحصل على مصفوفة بكسلات ARGB 32-بت الافتراضية. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | يحصل على الخيارات الافتراضية. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمّل بكسل جزئي. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمّل بكسل جزئي. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [getDefaultReplacementFont_internalized()](#getDefaultReplacementFont-internalized--) | يحصل أو يعيّن الخط الافتراضي للاستبدال. |
| [getDisposed()](#getDisposed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [getFileFormat()](#getFileFormat--) | يحصل على قيمة تنسيق الملف |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | يحصل على تنسيق الملف. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | يحصل على تنسيق الملف. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | يحصل على تنسيق الملف. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | يحصل على لوحة الألوان من أماكن خاصة بالتنسيق |
| [getGlobalAngle()](#getGlobalAngle--) | يحصل أو يعيّن الزاوية العامة. |
| [getGlobalLayerMaskInfo()](#getGlobalLayerMaskInfo--) | يحصل على معلومات القناع العام للطبقة. |
| [getGlobalLayerResources()](#getGlobalLayerResources--) | يحصل أو يعيّن موارد الطبقة العامة. |
| [getGrayColorProfile()](#getGrayColorProfile--) | يحصل أو يعيّن ملف تعريف اللون GRAY (أحادي اللون) لصور PSD بالدرجات الرمادية. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصورة. |
| [getHorizontalResolution()](#getHorizontalResolution--) | الحصول أو تعيين الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذا [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getImageLayers_internalized()](#getImageLayers-internalized--) | الحصول أو تعيين طبقات PSD. |
| [getImageOpacity()](#getImageOpacity--) | يحصل على شفافية هذه الصورة. |
| [getImageResources()](#getImageResources--) | الحصول أو تعيين موارد صورة PSD. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | يحصل على محول البيانات الداخلي. |
| [getInterruptMonitor()](#getInterruptMonitor--) | يحصل على مراقب المقاطعة. |
| [getLayerAndMask_internalized()](#getLayerAndMask-internalized--) | الحصول على الطبقة والقناع. |
| [getLayers()](#getLayers--) | الحصول أو تعيين طبقات PSD. |
| [getLinkedLayersManager()](#getLinkedLayersManager--) | الحصول على مدير الطبقات المرتبطة. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | يحصل أو يضبط الحد الأقصى المسموح به للتخصيص لحفظ الدوران الجزئي. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | يحصل على مدير الذاكرة. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getOriginalOptions()](#getOriginalOptions--) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | يحصل على الصورة القابلة للرسم. |
| [getPalette()](#getPalette--) | يحصل على لوحة الألوان. |
| [getPixel(int x, int y)](#getPixel-int-int-) | يحصل على بكسل الصورة. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | ينشئ ذاكرة التخزين المؤقت للخطوط الخاصة. |
| [getProgressEventHandler()](#getProgressEventHandler--) | يحصل على معلومات معالج حدث التقدم. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | يحصل على معلومات معالج حدث التقدم. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | يحصل على ارتفاع نسبي. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | يحصل على عرض نسبي. |
| [getPsdHeader_internalized()](#getPsdHeader-internalized--) | الحصول أو تعيين رأس PSD. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | يحصل أو يضبط محول اللون المخصص |
| [getRawDataFormat()](#getRawDataFormat--) | يحصل على تنسيق البيانات الخام. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | يحصل أو يضبط فهرس الاحتياطي للاستخدام عندما يكون فهرس اللوحة خارج النطاق |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | يحصل أو يضبط محول اللون المفهرس |
| [getRawLineSize()](#getRawLineSize--) | يحصل على حجم السطر الخام بالبايت. |
| [getRgbColorProfile()](#getRgbColorProfile--) | الحصول أو تعيين ملف تعريف اللون RGB لصور PSD بنظام CMYK. |
| [getRotateMode()](#getRotateMode--) | يحصل أو يعيّن وضع الدوران. |
| [getSize()](#getSize--) | يحصل على حجم الصورة. |
| [getSkewAngle()](#getSkewAngle--) | يحصل على زاوية الانحراف. |
| [getSmartObjectProvider()](#getSmartObjectProvider--) | الحصول على موفر الكائن الذكي. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | يحصل على مسار ملف الصورة المصدر إذا كان موجودًا. |
| [getSyncExclusiveOperation_internalized()](#getSyncExclusiveOperation-internalized--) |  |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | يحصل على جذر المزامنة. |
| [getTimeline()](#getTimeline--) | الحصول على الـ Timeline ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) لهذا [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getTransparentColor()](#getTransparentColor--) | يحصل على لون شفافية الصورة. |
| [getUpdateXmpData()](#getUpdateXmpData--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية. |
| [getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)](#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-) | الحصول على الموارد المحدثة مع كتلة موارد جديدة تمامًا. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | يحصل على قيمة تشير إلى ما إذا كان الكائن يستخدم استراتيجية تحسين الذاكرة |
| [getUseRawData()](#getUseRawData--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | يحصل على اللوحة المستخدمة. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | يحصل على رخصة المشروع. |
| [getVersion()](#getVersion--) | يحصل على أو يعيّن الإصدار. |
| [getVerticalResolution()](#getVerticalResolution--) | الحصول أو تعيين الدقة العمودية، بوحدات البكسل لكل بوصة، لهذا [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getWidth()](#getWidth--) | يحصل على عرض الصورة. |
| [getXmpData()](#getXmpData--) | يحصل أو يعيّن بيانات XMP الوصفية. |
| [grayscale()](#grayscale--) | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| [hasAlpha()](#hasAlpha--) | يحصل أو يعيّن الدقة العمودية، بوحدة البكسل لكل بوصة، لهذه RasterImage. |
| [hasBackgroundColor()](#hasBackgroundColor--) | يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت نسخة الصورة هذه قد تغيرت بعد التحميل. |
| [hasTransparencyData()](#hasTransparencyData--) | الحصول أو تعيين قيمة تشير إلى ما إذا كانت قناة ألفا الأولى تحتوي على بيانات الشفافية للنتيجة المدمجة عند تحديد بيانات الطبقات. |
| [hasTransparentColor()](#hasTransparentColor--) | يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | يحصل أو يعيّن القيمة القصوى للتقدم |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | يشير إلى التقدم. |
| [insertLayerAfter_internalized(Layer layer, Layer layerToInsert)](#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | إدراج الطبقة بعد الطبقة المحددة مع جميع التحضيرات. |
| [isCached()](#isCached--) | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [isFlatten()](#isFlatten--) | الحصول على قيمة تشير إلى ما إذا كانت صورة PSD مسطحة. |
| [isRawDataAvailable()](#isRawDataAvailable--) | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| [isUsePalette()](#isUsePalette--) | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| [isUsePhotoshopCompatibilityMode_internalized()](#isUsePhotoshopCompatibilityMode-internalized--) |  |
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
| [mergeLayers(Layer bottomLayer, Layer topLayer)](#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | دمج الطبقات. |
| [normalizeAngle()](#normalizeAngle--) | يُعَدِّل الزاوية إلى قيمتها الطبيعية. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | يُعَدِّل الزاوية إلى قيمتها الطبيعية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | استدعاء عندما تم تعيين حاوية هذا [Image](../../com.aspose.psd/image). |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | يقرأ السطر الكامل للمسح وفقًا لمؤشر سطر المسح المحدد. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | يقرأ السطر الكامل للمسح وفقًا لمؤشر سطر المسح المحدد. |
| [removeGlobalTextEngineResource_internalized()](#removeGlobalTextEngineResource-internalized--) | إزالة مورد محرك النص العالمي - تُستخدم الطريقة لبعض ملفات PSD ذات الطبقات النصية، التي لا يمكن فتحها في Adobe Photoshop بعد المعالجة (غالبًا بسبب طبقات النص المرتبطة بخطوط غير موجودة). |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | يغير حجم الصورة. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | يغير حجم الصورة. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | يغير حجم الصورة. |
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
| [save(OutputStream stream)](#save-java.io.OutputStream-) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
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
| [saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)](#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---) | حفظ بيانات الصورة إلى الدفق المحدد باستخدام خيارات الحفظ والحدود المحددة. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [setActiveLayer(Layer value)](#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | يحصل أو يعيّن الطبقة النشطة. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | يضبط بكسل صورة ARGB 32-بت للموقع المحدد. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | يضبط قيمة تشير إلى ما إذا كان يتم تعديل لوحة الألوان تلقائيًا. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | يحصل على أو يعيّن قيمة للون الخلفية. |
| [setBackgroundContents_internalized(RawColor value)](#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | يحصل أو يعيّن لون الخلفية. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | يحصل أو يعيّن ملف تعريف اللون CMYK لصور PSD بنظام CMYK. |
| [setColorMode(short value)](#setColorMode-short-) | يحصل أو يعيّن وضع اللون. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | يضبط حاوية الصورة. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | يضبط محمل البيانات مباشرة. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | يضبط دفق بيانات الكائن. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | يضبط لوحة الألوان في الأماكن الخاصة بالتنسيق |
| [setGlobalAngle(int value)](#setGlobalAngle-int-) | الزاوية العالمية. |
| [setGlobalLayerResources(LayerResource[] value)](#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | يحصل أو يعيّن موارد الطبقة العامة. |
| [setGrayColorProfile(StreamSource value)](#setGrayColorProfile-com.aspose.psd.sources.StreamSource-) | ملف تعريف اللون GRAY (أحادي اللون) لصور PSD بتدرج الرمادي. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | الحصول أو تعيين الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذا [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | يضبط قيمة تشير إلى ما إذا كان [تجاهل بعد الحفظ]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت نسخة الصورة هذه قد تغيرت بعد التحميل. |
| [setImageResources(ResourceBlock[] value)](#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | الحصول أو تعيين موارد صورة PSD. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | يضبط محول البيانات الداخلي. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | يضبط مراقب المقاطعة. |
| [setLayers(Layer[] value)](#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | الحصول أو تعيين طبقات PSD. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | يحصل أو يضبط الحد الأقصى المسموح به للتخصيص لحفظ الدوران الجزئي. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | يضبط مدير الذاكرة. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | يضبط لوحة الألوان. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | يضبط لوحة ألوان الصورة. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | يضبط بكسل الصورة للموقع المحدد. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | يحصل أو يضبط محول اللون المخصص |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | يحصل أو يضبط فهرس الاحتياطي للاستخدام عندما يكون فهرس اللوحة خارج النطاق |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | يحصل أو يضبط محول اللون المفهرس |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | تعيين الدقة لهذا [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | الحصول أو تعيين ملف تعريف اللون RGB لصور PSD بنظام CMYK. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | يحصل أو يعيّن وضع الدوران. |
| [setTransparencyData(boolean value)](#setTransparencyData-boolean-) | الحصول أو تعيين قيمة تشير إلى ما إذا كانت قناة ألفا الأولى تحتوي على بيانات الشفافية للنتيجة المدمجة عند تحديد بيانات الطبقات. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | يحصل على لون شفافية الصورة. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية. |
| [setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)](#setUsePhotoshopCompatibilityMode-internalized-boolean-) |  |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | تعيين رخصة المشروع. |
| [setVersion(int value)](#setVersion-int-) | يحصل على أو يعيّن الإصدار. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | الحصول أو تعيين الدقة العمودية، بوحدات البكسل لكل بوصة، لهذا [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | يحصل أو يعيّن بيانات XMP الوصفية. |
| [toBitmap()](#toBitmap--) | يحول الصورة النقطية إلى bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد. |
### PsdImage(String path) {#PsdImage-java.lang.String-}
```
public PsdImage(String path)
```


إنشاء نسخة جديدة من فئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) من المسار المحدد لصورة نقطية (ليس صورة PSD في المسار). تُستخدم لتهيئة صورة PSD بالمعلمات الافتراضية - وضع اللون - rgb، 4 قنوات، 8 بت لكل قناة، الضغط - Raw.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | المسار لتحميل بيانات البكسل واللوحة منه والتهيئة به. |

### PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.lang.String-short-short-short-int-short-}
```
public PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


يُنشئ مثلاً جديداً من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) من المسار المحدد لصورة نقطية (ليس صورة PSD في المسار) مع معلمات المُنشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | المسار لتحميل بيانات البكسل واللوحة منه والتهيئة به. |
| colorMode | short | وضع اللون. |
| channelBitDepth | short | عمق البت لكل قناة في PSD. |
| channels | short | عدد قنوات PSD. |
| psdVersion | int | إصدار PSD. |
| compression | short | ضغط الاستخدام. |

### PsdImage(InputStream stream) {#PsdImage-java.io.InputStream-}
```
public PsdImage(InputStream stream)
```


ينشئ مثيلاً جديداً من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) من المسار المحدد لصورة نقطية (ليس صورة PSD في الدفق). يُستخدم لتهيئة صورة PSD بالمعلمات الافتراضية - وضع اللون - rgb، 4 قنوات، 8 بت لكل قناة، الضغط - Raw.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | الدفق لتحميل بيانات البكسل واللوحة وتتهيئتها. |

### PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.io.InputStream-short-short-short-int-short-}
```
public PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


يُنشئ مثلاً جديداً من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) من المسار المحدد لصورة نقطية (ليس صورة PSD في الدفق) مع معلمات المُنشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | الدفق لتحميل بيانات البكسل واللوحة وتتهيئتها. |
| colorMode | short | وضع اللون. |
| channelBitDepth | short | عمق البت لكل قناة في PSD. |
| channels | short | عدد قنوات PSD. |
| psdVersion | int | إصدار PSD. |
| compression | short | ضغط الاستخدام. |

### PsdImage(RasterImage rasterImage) {#PsdImage-com.aspose.psd.RasterImage-}
```
public PsdImage(RasterImage rasterImage)
```


يُنشئ مثلاً جديداً من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) من صورة نقطية موجودة (ليس صورة PSD) بنمط ألوان RGB مع 4 قنوات 8 بت/قناة وبدون ضغط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | الصورة لتحميل بيانات البكسل واللوحة وتتهيئتها. |

### PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-}
```
public PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


يُنشئ مثلاً جديداً من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) من صورة نقطية موجودة (ليس صورة PSD) مع معلمات المُنشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | الصورة لتحميل بيانات البكسل واللوحة وتتهيئتها. |
| colorMode | short | وضع اللون. |
| channelBitDepth | short | عمق البت لكل قناة في PSD. |
| channels | short | عدد قنوات PSD. |
| psdVersion | int | إصدار PSD. |
| compression | short | ضغط الاستخدام. |

### PsdImage(int width, int height) {#PsdImage-int-int-}
```
public PsdImage(int width, int height)
```


ينشئ مثيلاً جديداً من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) بالعرض والارتفاع. يُستخدم لتهيئة صورة PSD فارغة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | عرض الصورة. |
| الارتفاع | int | ارتفاع الصورة. |

### PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-}
```
public PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


ينشئ مثيلاً جديداً من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) بالعرض والارتفاع والـpaletter، وضع اللون، عدد القنوات وطول البت لكل قناة، ومعلمات وضع الضغط المحددة. يُستخدم لتهيئة صورة PSD فارغة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | عرض الصورة. |
| الارتفاع | int | ارتفاع الصورة. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | لوحة الألوان. |
| colorMode | short | وضع اللون. |
| channelBitDepth | short | عمق البت لكل قناة في PSD. |
| channels | short | عدد قنوات PSD. |
| psdVersion | int | إصدار PSD. |
| compression | short | ضغط الاستخدام. |

### DefaultStubEncodingName_internalized {#DefaultStubEncodingName-internalized}
```
public static final String DefaultStubEncodingName_internalized
```


اسم الترميز الافتراضي

### DefaultVersion {#DefaultVersion}
```
public static final int DefaultVersion
```


إصدار PSD الافتراضي.

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

### SyncLayersRoot_internalized {#SyncLayersRoot-internalized}
```
public final Object SyncLayersRoot_internalized
```


الكائن الذي يمكن استخدامه لمزامنة الوصول إلى الطبقات.

### horizontalResolution {#horizontalResolution}
```
public double horizontalResolution
```


### addBlackWhiteAdjustmentLayer() {#addBlackWhiteAdjustmentLayer--}
```
public final BlackWhiteAdjustmentLayer addBlackWhiteAdjustmentLayer()
```


يضيف طبقة تعديل بالأبيض والأسود.

**Returns:**
[BlackWhiteAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer) - The created black white adjustment layer.
### addBrightnessContrastAdjustmentLayer(int brightness, int contrast) {#addBrightnessContrastAdjustmentLayer-int-int-}
```
public final BrightnessContrastLayer addBrightnessContrastAdjustmentLayer(int brightness, int contrast)
```


يضيف طبقة تعديل السطوع/التباين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| السطوع | int | السطوع. |
| التباين | int | التباين. |

**Returns:**
[BrightnessContrastLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer) - Created brightness/contrast layer
### addChannelMixerAdjustmentLayer() {#addChannelMixerAdjustmentLayer--}
```
public final ChannelMixerLayer addChannelMixerAdjustmentLayer()
```


يضيف طبقة تعديل خالط القنوات مع المعلمات الافتراضية.

**Returns:**
[ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer) - Added Channel Mixer Layer
### addColorBalanceAdjustmentLayer() {#addColorBalanceAdjustmentLayer--}
```
public final ColorBalanceAdjustmentLayer addColorBalanceAdjustmentLayer()
```


يضيف طبقة تعديل توازن الألوان.

**Returns:**
[ColorBalanceAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer) - A newly created color balance layer.
### addCurvesAdjustmentLayer() {#addCurvesAdjustmentLayer--}
```
public final CurvesLayer addCurvesAdjustmentLayer()
```


يضيف طبقة تعديل المنحنيات.

**Returns:**
[CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) - Created [CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) Layer
### addExposureAdjustmentLayer() {#addExposureAdjustmentLayer--}
```
public final ExposureLayer addExposureAdjustmentLayer()
```




**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure) {#addExposureAdjustmentLayer-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exposure | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset) {#addExposureAdjustmentLayer-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exposure | float |  |
| الإزاحة | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection) {#addExposureAdjustmentLayer-float-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)
```


يضيف طبقة تعديل التعرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exposure | float | التعريض. |
| الإزاحة | float | الإزاحة. |
| gammaCorrection | float | تصحيح غاما. |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer) - Created Exposure Adjustment Layer
### addGradientMapAdjustmentLayer() {#addGradientMapAdjustmentLayer--}
```
public final GradientMapLayer addGradientMapAdjustmentLayer()
```


يضيف طبقة تعديل خريطة التدرج.

**Returns:**
[GradientMapLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer) - GradientMap instance.
### addHueSaturationAdjustmentLayer() {#addHueSaturationAdjustmentLayer--}
```
public final HueSaturationLayer addHueSaturationAdjustmentLayer()
```


يضيف طبقة تعديل الصبغة/التشبع.

**Returns:**
[HueSaturationLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer) - A newly created hue/saturation layer.
### addInvertAdjustmentLayer() {#addInvertAdjustmentLayer--}
```
public final InvertAdjustmentLayer addInvertAdjustmentLayer()
```


يضيف طبقة تعديل عكس.

**Returns:**
[InvertAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer) - The created invert layer
### addLayer(Layer layer) {#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void addLayer(Layer layer)
```


يضيف الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | الطبقة. |

### addLayerGroup(String groupName, int index, boolean startBehaviour) {#addLayerGroup-java.lang.String-int-boolean-}
```
public final LayerGroup addLayerGroup(String groupName, int index, boolean startBehaviour)
```


يضيف مجموعة الطبقات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| groupName | java.lang.String | اسم المجموعة. |
| الفهرس | int | فهرس الطبقة التي سيتم الإدراج بعده. |
| startBehaviour | boolean | إذا تم تعيينه إلى  true  [start behaviour] فإن المجموعة ستكون في حالة مفتوحة عند بدء التشغيل، وإلا ستكون في حالة مصغرة. |

**Returns:**
[LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) - Opening group layer
### addLayer_internalized(Layer layer, int index) {#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-}
```
public void addLayer_internalized(Layer layer, int index)
```


يضيف الطبقة عند الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | الطبقة. |
| الفهرس | int | الفهرس. |

### addLevelsAdjustmentLayer() {#addLevelsAdjustmentLayer--}
```
public final LevelsLayer addLevelsAdjustmentLayer()
```


يضيف طبقة تعديل المستويات.

**Returns:**
[LevelsLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer) - A newly created Levels layer
### addPhotoFilterLayer(Color color) {#addPhotoFilterLayer-com.aspose.psd.Color-}
```
public final PhotoFilterLayer addPhotoFilterLayer(Color color)
```


يضيف طبقة مرشح الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | اللون. |

**Returns:**
[PhotoFilterLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer) - Created PhotoFilter Layer
### addPosterizeAdjustmentLayer() {#addPosterizeAdjustmentLayer--}
```
public final PosterizeLayer addPosterizeAdjustmentLayer()
```


يضيف طبقة تعديل Posterize.

**Returns:**
[PosterizeLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer) - PosterizeLayer instance.
### addRegularLayer() {#addRegularLayer--}
```
public final Layer addRegularLayer()
```


يضيف طبقة عادية جديدة.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Created regular layer.
### addSelectiveColorAdjustmentLayer() {#addSelectiveColorAdjustmentLayer--}
```
public final SelectiveColorLayer addSelectiveColorAdjustmentLayer()
```


يضيف طبقة تعديل اللون الانتقائي.

**Returns:**
[SelectiveColorLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer) - The created selective color adjustment layer.
### addShapeLayer() {#addShapeLayer--}
```
public final ShapeLayer addShapeLayer()
```


أضف طبقة شكل فارغة. بدون مسارات. يجب إضافتها إلى طبقة الشكل قبل الحفظ.

**Returns:**
[ShapeLayer](../../com.aspose.psd.fileformats.psd.layers/shapelayer) - ShapeLayer instance.
### addTextLayer(String text, Rectangle rect) {#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-}
```
public final TextLayer addTextLayer(String text, Rectangle rect)
```


يضيف طبقة نص جديدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | نص الطبقة. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل الطبقة. |

**Returns:**
[TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) - Created text layer.
### addThresholdAdjustmentLayer() {#addThresholdAdjustmentLayer--}
```
public final ThresholdLayer addThresholdAdjustmentLayer()
```


يضيف طبقة تعديل العتبة.

**Returns:**
[ThresholdLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer) - The created Threshold adjustment layer.
### addVibranceAdjustmentLayer() {#addVibranceAdjustmentLayer--}
```
public final VibranceLayer addVibranceAdjustmentLayer()
```


يضيف طبقة تعديل الحيوية.

**Returns:**
[VibranceLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer) - A newly created Vibrance layer.
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

### convert(PsdOptions newOptions) {#convert-com.aspose.psd.imageoptions.PsdOptions-}
```
public final void convert(PsdOptions newOptions)
```


يحوّل تنسيق هذه الصورة إلى التنسيق المحدد في الخيارات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newOptions | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | الخيارات الجديدة. |

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
### createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-}
```
public static PsdImage createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)
```


ينشئ نسخة جديدة من الفئة [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader | رأس PSD. |
| colorData | com.aspose.internal.fileformats.psd.sections.ColorData | بيانات اللون. |
| imageResources | com.aspose.internal.fileformats.psd.sections.ImageResources | موارد الصورة. |
| layerAndMaskInfo | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo | معلومات الطبقة والقناع. |
| imageData | com.aspose.internal.fileformats.psd.sections.ImageData | بيانات الصورة. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | لوحة الألوان. |
| version | int | إصدار PSD. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | خيارات التحميل. |
| noLayerLoad | boolean | عدم تحميل الطبقة |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) - Returns the new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class.
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
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static PsdImage create_internalized(System.IO.Stream stream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-}
```
public static PsdImage create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| colorMode | short |  |
| channelBitDepth | short |  |
| channels | short |  |
| psdVersion | int |  |
| compression | short |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
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

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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

### flattenImage() {#flattenImage--}
```
public final void flattenImage()
```


يقوم بدمج جميع الطبقات.

### getActiveLayer() {#getActiveLayer--}
```
public final Layer getActiveLayer()
```


يحصل أو يعيّن الطبقة النشطة.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
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
### getBackgroundContents_internalized() {#getBackgroundContents-internalized--}
```
public final RawColor getBackgroundContents_internalized()
```


يحصل أو يضبط لون الخلفية. يمكن رؤيته تحت الكائنات الشفافة.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBitsPerChannel() {#getBitsPerChannel--}
```
public final int getBitsPerChannel()
```


يحصل على عدد البتات لكل قناة.

القيمة: عدد البتات لكل قناة.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يحصل على عدد البتات لكل بكسل في الصورة.

القيمة: عدد بتات الصورة لكل بكسل.

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
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


يحصل على عدد قنوات PSD.

القيمة: عدد قنوات PSD.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmykColorProfile() {#getCmykColorProfile--}
```
public final StreamSource getCmykColorProfile()
```


يحصل أو يضبط ملف تعريف اللون CMYK لصور PSD بنظام CMYK. يجب أن يكون مقترناً بـ RgbColorProfile للتحويل اللوني الصحيح.

القيمة: ملف تعريف اللون CMYK.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


يحصل أو يعيّن وضع اللون.

القيمة: وضع اللون.

**Returns:**
short
### getCompression() {#getCompression--}
```
public final short getCompression()
```


يحصل على طريقة الضغط.

القيمة: الضغط.

**Returns:**
short
### getContainer() {#getContainer--}
```
public Image getContainer()
```


يحصل على حاوية الصورة.

القيمة: حاوية الصورة.

إذا لم تكن هذه الخاصية فارغة، فهذا يدل على أن الصورة مضمَّنة داخل صورة أخرى.

**Returns:**
[Image](../../com.aspose.psd/image)
### getCurrentOptions_internalized() {#getCurrentOptions-internalized--}
```
public final PsdOptions getCurrentOptions_internalized()
```


يحصل على خيارات الصورة الحالية.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) - Current options for PSD image
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
### getDefaultReplacementFont_internalized() {#getDefaultReplacementFont-internalized--}
```
public final String getDefaultReplacementFont_internalized()
```


يحصل أو يضبط الخط الافتراضي البديل. إذا تم تعيين Replacement font فسيتم استخدامه في العرض. نحتاج هذه الطريقة للدعم الداخلي

**Returns:**
java.lang.String - اسم Replacement font
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه.

**Returns:**
boolean -  true  إذا تم التخلص؛ وإلا،  false .
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
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


يحصل على لوحة الألوان من أماكن خاصة بالتنسيق

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGlobalAngle() {#getGlobalAngle--}
```
public final int getGlobalAngle()
```


يحصل أو يعيّن الزاوية العامة.

**Returns:**
int
### getGlobalLayerMaskInfo() {#getGlobalLayerMaskInfo--}
```
public final GlobalLayerMaskInfo getGlobalLayerMaskInfo()
```


يحصل على معلومات القناع العام للطبقة.

**Returns:**
[GlobalLayerMaskInfo](../../com.aspose.psd.fileformats.psd.layers/globallayermaskinfo)
### getGlobalLayerResources() {#getGlobalLayerResources--}
```
public final LayerResource[] getGlobalLayerResources()
```


يحصل أو يعيّن موارد الطبقة العامة.

القيمة: موارد الطبقة العامة.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getGrayColorProfile() {#getGrayColorProfile--}
```
public final StreamSource getGrayColorProfile()
```


يحصل أو يعيّن ملف تعريف اللون GRAY (أحادي اللون) لصور PSD بالدرجات الرمادية.

القيمة: ملف تعريف اللون GRAY (أحادي اللون).

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
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


الحصول أو تعيين الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذا [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
double
### getImageLayers_internalized() {#getImageLayers-internalized--}
```
public final Layer[] getImageLayers_internalized()
```


الحصول أو تعيين طبقات PSD.

القيمة: طبقات PSD.

--------------------

لاحظ أنه إذا لم تكن هناك طبقات، فإن المعلومات الأخرى المتعلقة ضمن قسم معلومات الطبقة والقناع لن يتم حفظها (أقنعة الطبقة، الموارد وما إلى ذلك).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


يحصل على شفافية هذه الصورة.

**Returns:**
float - قيمة الشفافية بين 0.0 (شفافة تمامًا) و 1.0 (معتمة تمامًا).
### getImageResources() {#getImageResources--}
```
public final ResourceBlock[] getImageResources()
```


الحصول أو تعيين موارد صورة PSD.

القيمة: موارد صورة PSD.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
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
### getLayerAndMask_internalized() {#getLayerAndMask-internalized--}
```
public final LayerAndMaskInfo getLayerAndMask_internalized()
```


الحصول على الطبقة والقناع.

القيمة: الطبقة والقناع.

**Returns:**
com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo
### getLayers() {#getLayers--}
```
public final Layer[] getLayers()
```


الحصول أو تعيين طبقات PSD.

القيمة: طبقات PSD.

--------------------

لاحظ أنه إذا لم تكن هناك طبقات، فإن المعلومات الأخرى المتعلقة ضمن قسم معلومات الطبقة والقناع لن يتم حفظها (أقنعة الطبقة، الموارد وما إلى ذلك).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getLinkedLayersManager() {#getLinkedLayersManager--}
```
public final LinkedLayersManager getLinkedLayersManager()
```


الحصول على مدير الطبقات المرتبطة.

**Returns:**
[LinkedLayersManager](../../com.aspose.psd.fileformats.psd.layers/linkedlayersmanager)
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
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة  DataStreamSupporter.Save(string)  ، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومرّرها إلى طريقة  Image.Save(string, ImageOptionsBase)  كمعامل ثانٍ.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
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
### getPsdHeader_internalized() {#getPsdHeader-internalized--}
```
public final PsdHeader getPsdHeader_internalized()
```


الحصول أو تعيين رأس PSD.

القيمة: رأس PSD.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
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

القيمة: تنسيق البيانات الخام.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
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
### getRgbColorProfile() {#getRgbColorProfile--}
```
public final StreamSource getRgbColorProfile()
```


يحصل أو يضبط ملف تعريف اللون RGB لصور PSD بنظام CMYK. يجب أن يكون مقترنًا بـ CmykColorProfile للتحويل اللوني الصحيح.

القيمة: ملف تعريف اللون RGB.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


يحصل أو يعيّن وضع الدوران.

**Returns:**
int - وضع الدوران.
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
### getSyncExclusiveOperation_internalized() {#getSyncExclusiveOperation-internalized--}
```
public Object getSyncExclusiveOperation_internalized()
```




**Returns:**
java.lang.Object
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


يحصل على جذر المزامنة.

القيمة: جذر المزامنة.

**Returns:**
java.lang.Object
### getTimeline() {#getTimeline--}
```
public Timeline getTimeline()
```


الحصول على الـ Timeline ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) لهذا [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
[Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)
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
### getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates) {#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-}
```
public static ResourceBlock[] getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)
```


الحصول على الموارد المحدثة مع كتلة موارد جديدة تمامًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resources | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) | الموارد. |
| resource | [ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock) | المورد لإضافته إلى الموارد الموجودة. |
| removeDuplicates | boolean | إذا تم تعيينه إلى  true  يزيل الموارد ذات المعرفات المتطابقة. |

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[] - يُرجع مصفوفة تحتوي على كتل موارد محدثة.
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
### getVersion() {#getVersion--}
```
public final int getVersion()
```


يحصل على أو يعيّن الإصدار.

القيمة: الإصدار.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


الحصول أو تعيين الدقة العمودية، بوحدات البكسل لكل بوصة، لهذا [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
double
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

القيمة: بيانات التعريف XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### grayscale() {#grayscale--}
```
public void grayscale()
```


تحويل الصورة إلى تمثيلها بتدرج الرمادي

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


يحصل أو يعيّن الدقة العمودية، بوحدة البكسل لكل بوصة، لهذه RasterImage.

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

القيمة:  true  إذا كان هذا الكائن قد تغيرت صورته؛ وإلا،  false .

**Returns:**
boolean
### hasTransparencyData() {#hasTransparencyData--}
```
public final boolean hasTransparencyData()
```


الحصول أو تعيين قيمة تشير إلى ما إذا كانت قناة ألفا الأولى تحتوي على بيانات الشفافية للنتيجة المدمجة عند تحديد بيانات الطبقات.

القيمة:  true  إذا كان قناة ألفا الأولى تحتوي على بيانات الشفافية للنتيجة المدمجة عند تحديد بيانات الطبقات؛ وإلا،  false .

**Returns:**
boolean
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### insertLayerAfter_internalized(Layer layer, Layer layerToInsert) {#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void insertLayerAfter_internalized(Layer layer, Layer layerToInsert)
```


إدراج الطبقة بعد الطبقة المحددة مع جميع التحضيرات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | الطبقة. |
| layerToInsert | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | الطبقة لإدراجها. |

### isCached() {#isCached--}
```
public boolean isCached()
```


يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا.

**Returns:**
boolean -  true  إذا تم تخزين بيانات الصورة مؤقتًا؛ وإلا،  false .
### isFlatten() {#isFlatten--}
```
public final boolean isFlatten()
```


الحصول على قيمة تشير إلى ما إذا كانت صورة PSD مسطحة.

القيمة:  true  إذا كان هذا الكائن مسطحًا؛ وإلا،  false .

**Returns:**
boolean
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
### isUsePhotoshopCompatibilityMode_internalized() {#isUsePhotoshopCompatibilityMode-internalized--}
```
public boolean isUsePhotoshopCompatibilityMode_internalized()
```




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
### mergeLayers(Layer bottomLayer, Layer topLayer) {#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final Layer mergeLayers(Layer bottomLayer, Layer topLayer)
```


دمج الطبقات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bottomLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | الطبقة السفلية. |
| topLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | الطبقة العلوية. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Bottom layer after the merge
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


استدعاء عندما تم تعيين حاوية هذا [Image](../../com.aspose.psd/image).

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
### removeGlobalTextEngineResource_internalized() {#removeGlobalTextEngineResource-internalized--}
```
public final void removeGlobalTextEngineResource_internalized()
```


يزيل مورد محرك النص العالمي - تُستخدم الطريقة لبعض ملفات PSD ذات الطبقات النصية، التي لا يمكن فتحها في Adobe Photoshop بعد المعالجة (غالبًا ما يتعلق ذلك بطبقات النص التي تفتقر إلى الخطوط). بعد استخدام هذا الخيار، يحتاج المستخدم إلى تنفيذ التالي في الملف المفتوح في Photoshop: القائمة "Text" -> "Process absent fonts". بعد هذه العملية سيظهر جميع النص مرة أخرى. يرجى ملاحظة أن هذه العملية قد تسبب بعض تغييرات التخطيط النهائية.

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

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | المجرى لحفظ بيانات الصورة إليه. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | خيارات الحفظ. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

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

### saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport) {#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)
```


يحفظ بيانات الصورة إلى الدفق المحدد باستخدام خيارات الحفظ والحدود المحددة. يمكن اختياريًا تصدير الطبقات المحددة فقط لعرض معاينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | الدفق الذي سيتم حفظ بيانات الصورة إليه. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | خيارات الحفظ التي سيتم استخدامها. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل حدود الصورة الوجهة. اضبطه إلى  Rectangle.Empty  لاستخدام حدود المصدر. |
| layersToExport | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | الطبقات المحددة للتصدير. قيمة  null  تشير إلى السلوك الافتراضي مع جميع الطبقات. |

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

### setActiveLayer(Layer value) {#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void setActiveLayer(Layer value)
```


يحصل أو يعيّن الطبقة النشطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

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

### setBackgroundContents_internalized(RawColor value) {#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents_internalized(RawColor value)
```


يحصل أو يضبط لون الخلفية. يمكن رؤيته تحت الكائنات الشفافة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setCmykColorProfile(StreamSource value)
```


يحصل أو يضبط ملف تعريف اللون CMYK لصور PSD بنظام CMYK. يجب أن يكون مقترناً بـ RgbColorProfile للتحويل اللوني الصحيح.

القيمة: ملف تعريف اللون CMYK.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


يحصل أو يعيّن وضع اللون.

القيمة: وضع اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


يضبط حاوية الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | حاوية  Image . |

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
### setGlobalAngle(int value) {#setGlobalAngle-int-}
```
public final void setGlobalAngle(int value)
```


الزاوية العالمية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setGlobalLayerResources(LayerResource[] value) {#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setGlobalLayerResources(LayerResource[] value)
```


يحصل أو يعيّن موارد الطبقة العامة.

القيمة: موارد الطبقة العامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setGrayColorProfile(StreamSource value) {#setGrayColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setGrayColorProfile(StreamSource value)
```


ملف تعريف اللون GRAY (أحادي اللون) لصور PSD بتدرج الرمادي.

القيمة: ملف تعريف اللون GRAY (أحادي اللون).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


الحصول أو تعيين الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذا [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

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

### setImageResources(ResourceBlock[] value) {#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setImageResources(ResourceBlock[] value)
```


الحصول أو تعيين موارد صورة PSD.

القيمة: موارد صورة PSD.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

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

### setLayers(Layer[] value) {#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void setLayers(Layer[] value)
```


الحصول أو تعيين طبقات PSD.

القيمة: طبقات PSD.

--------------------

لاحظ أنه إذا لم تكن هناك طبقات، فإن المعلومات الأخرى المتعلقة ضمن قسم معلومات الطبقة والقناع لن يتم حفظها (أقنعة الطبقة، الموارد وما إلى ذلك).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

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


تعيين الدقة لهذا [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dpiX | double | دقة الأفقية، بوحدات النقاط في البوصة، لصورة  RasterImage . |
| dpiY | double | دقة العمودية، بوحدات النقاط في البوصة، لصورة  RasterImage . |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setRgbColorProfile(StreamSource value)
```


يحصل أو يضبط ملف تعريف اللون RGB لصور PSD بنظام CMYK. يجب أن يكون مقترنًا بـ CmykColorProfile للتحويل اللوني الصحيح.

القيمة: ملف تعريف اللون RGB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


يحصل أو يعيّن وضع الدوران.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | وضع الدوران. |

### setTransparencyData(boolean value) {#setTransparencyData-boolean-}
```
public final void setTransparencyData(boolean value)
```


الحصول أو تعيين قيمة تشير إلى ما إذا كانت قناة ألفا الأولى تحتوي على بيانات الشفافية للنتيجة المدمجة عند تحديد بيانات الطبقات.

القيمة:  true  إذا كان قناة ألفا الأولى تحتوي على بيانات الشفافية للنتيجة المدمجة عند تحديد بيانات الطبقات؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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

### setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized) {#setUsePhotoshopCompatibilityMode-internalized-boolean-}
```
public void setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| usePhotoshopCompatibilityMode_internalized | boolean |  |

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


تعيين رخصة المشروع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ventureLicense | java.lang.Object | رخصة المشروع. |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


يحصل على أو يعيّن الإصدار.

القيمة: الإصدار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


الحصول أو تعيين الدقة العمودية، بوحدات البكسل لكل بوصة، لهذا [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


يحصل أو يعيّن بيانات XMP الوصفية.

القيمة: بيانات التعريف XMP.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

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

