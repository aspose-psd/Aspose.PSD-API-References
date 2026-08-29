---
title: "RasterImage"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل صورة نقطية تدعم عمليات الرسومات النقطية."
type: docs
weight: 86
url: /ar/java/com.aspose.psd/rasterimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image)

**All Implemented Interfaces:**
[com.aspose.psd.IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader), com.aspose.internal.IPixelsSaver
```
public abstract class RasterImage extends Image implements IRasterImageArgb32PixelLoader, IPixelsSaver
```

يمثل صورة نقطية تدعم عمليات الرسومات النقطية.
## الحقول

| حقل | الوصف |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | يحدث عندما تم تحميل الصورة |
| [OnLoad_internalized](#OnLoad-internalized) | يحدث عندما تم تحميل الصورة بواسطة createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | يحدث عندما تم تحميل الصورة أو حفظها |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | يحدث عندما تم استخدام الرصيد |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | ضبط السطوع للصورة. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | تباين الصورة |
| [adjustGamma(float gamma)](#adjustGamma-float-) | تصحيح غاما للصورة. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | تصحيح غاما للصورة. |
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
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | يقص المستطيل المحدد. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | قص الصورة مع الإزاحات. |
| [dispose()](#dispose--) | يحرر النسخة الحالية. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | ينفذ تمويه (dithering) على الصورة الحالية. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | ينفذ تمويه (dithering) على الصورة الحالية. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | يفلتر المستطيل المحدد. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | يحصل على بكسل صورة 32-بت ARGB. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | يحصل على قيمة تشير إلى ما إذا كان تعديل اللوحة تلقائيًا. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على أو يعيّن قيمة للون الخلفية. |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد البتات لكل بكسل في الصورة. |
| [getBounds()](#getBounds--) | يحصل على حدود الصورة. |
| [getBufferSizeHint()](#getBufferSizeHint--) | يحصل على تلميح حجم المخزن المؤقت الذي يُعرّف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | يحصل على حاوية الصورة. |
| [getDataStreamContainer()](#getDataStreamContainer--) | يحصل على تدفق بيانات الكائن. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | يحصل على تعديل عميق للوحة الألوان. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | يحصل على مصفوفة بكسلات ARGB 32-بت الافتراضية. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | يحصل على الخيارات الافتراضية. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمّل بكسل جزئي. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمّل بكسل جزئي. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [getDisposed()](#getDisposed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [getFileFormat()](#getFileFormat--) | يحصل على قيمة تنسيق الملف |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | يحصل على تنسيق الملف. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | يحصل على تنسيق الملف. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | يحصل على تنسيق الملف. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | يحصل على لوحة الألوان من أماكن خاصة بالتنسيق |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصورة. |
| [getHorizontalResolution()](#getHorizontalResolution--) | يحصل أو يضبط الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذا  RasterImage . |
| [getImageOpacity()](#getImageOpacity--) | يحصل على شفافية هذه الصورة. |
| [getInterruptMonitor()](#getInterruptMonitor--) | يحصل على مراقب المقاطعة. |
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
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | يحصل أو يضبط محول اللون المخصص |
| [getRawDataFormat()](#getRawDataFormat--) | يحصل على تنسيق البيانات الخام. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | يحصل أو يضبط فهرس الاحتياطي للاستخدام عندما يكون فهرس اللوحة خارج النطاق |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | يحصل أو يضبط محول اللون المفهرس |
| [getRawLineSize()](#getRawLineSize--) | يحصل على حجم السطر الخام بالبايت. |
| [getSize()](#getSize--) | يحصل على حجم الصورة. |
| [getSkewAngle()](#getSkewAngle--) | يحصل على زاوية الانحراف. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | يحصل على مسار ملف الصورة المصدر إذا كان موجودًا. |
| [getTransparentColor()](#getTransparentColor--) | يحصل على لون شفافية الصورة. |
| [getUpdateXmpData()](#getUpdateXmpData--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | يحصل على قيمة تشير إلى ما إذا كان الكائن يستخدم استراتيجية تحسين الذاكرة |
| [getUseRawData()](#getUseRawData--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | يحصل على اللوحة المستخدمة. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | يحصل على رخصة المشروع. |
| [getVerticalResolution()](#getVerticalResolution--) | يحصل أو يعيّن الدقة العمودية، بوحدة البكسل لكل بوصة، لهذه RasterImage. |
| [getWidth()](#getWidth--) | يحصل على عرض الصورة. |
| [getXmpData()](#getXmpData--) | يحصل أو يعيّن بيانات XMP الوصفية. |
| [grayscale()](#grayscale--) | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| [hasAlpha()](#hasAlpha--) | يحصل على قيمة تشير إلى ما إذا كانت هذه النسخة تحتوي على قناة ألفا. |
| [hasBackgroundColor()](#hasBackgroundColor--) | يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت نسخة الصورة هذه قد تغيرت بعد التحميل. |
| [hasTransparentColor()](#hasTransparentColor--) | يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | يحصل أو يعيّن القيمة القصوى للتقدم |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | يشير إلى التقدم. |
| [isCached()](#isCached--) | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات. |
| [isRawDataAvailable()](#isRawDataAvailable--) | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| [isUsePalette()](#isUsePalette--) | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
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
| [normalizeAngle()](#normalizeAngle--) | يُعَدِّل الزاوية إلى قيمتها الطبيعية. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | يُعَدِّل الزاوية إلى قيمتها الطبيعية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | استدعاء عندما تم تعيين حاوية هذا [Image](../../com.aspose.psd/image). |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | يقرأ السطر الكامل للمسح وفقًا لمؤشر سطر المسح المحدد. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | يقرأ السطر الكامل للمسح وفقًا لمؤشر سطر المسح المحدد. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | يغير حجم الصورة. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | يعيد تحجيم الصورة باستخدام خيارات موسعة. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | يغير حجم الصورة. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | يعيد تحجيم الارتفاع بنسبة متناسبة. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | يعيد تحجيم الارتفاع بنسبة متناسبة. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | يعيد تحجيم الارتفاع بنسبة متناسبة. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | يعيد تحجيم العرض بنسبة متناسبة. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | يعيد تحجيم العرض بنسبة متناسبة. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | يعيد تحجيم العرض بنسبة متناسبة. |
| [rotate(float angle)](#rotate-float-) | تدوير الصورة حول المركز. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | تدوير الصورة حول المركز. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | يدور، يقلب، أو يدور ويقلب الصورة. |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | يضبط بكسل صورة ARGB 32-بت للموقع المحدد. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | يضبط قيمة تشير إلى ما إذا كان يتم تعديل لوحة الألوان تلقائيًا. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | يحصل على أو يعيّن قيمة للون الخلفية. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | يضبط حاوية الصورة. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | يضبط محمل البيانات مباشرة. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | يضبط دفق بيانات الكائن. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | يضبط لوحة الألوان في الأماكن الخاصة بالتنسيق |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | يحصل أو يضبط الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذا  RasterImage . |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | يضبط قيمة تشير إلى ما إذا كان [تجاهل بعد الحفظ]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت نسخة الصورة هذه قد تغيرت بعد التحميل. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | يضبط مراقب المقاطعة. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | يضبط مدير الذاكرة. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | يضبط لوحة الألوان. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | يضبط لوحة ألوان الصورة. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | يضبط بكسل الصورة للموقع المحدد. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | يحصل أو يضبط محول اللون المخصص |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | يحصل أو يضبط فهرس الاحتياطي للاستخدام عندما يكون فهرس اللوحة خارج النطاق |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | يحصل أو يضبط محول اللون المفهرس |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | يضبط الدقة لهذا  RasterImage . |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | يحصل على لون شفافية الصورة. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحديث بيانات XMP الوصفية. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | يجب على جميع منتجات Aspose تنفيذ هذه الطريقة. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | يحصل أو يعيّن الدقة العمودية، بوحدة البكسل لكل بوصة، لهذه RasterImage. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | يحصل أو يعيّن بيانات XMP الوصفية. |
| [toBitmap()](#toBitmap--) | يحول الصورة النقطية إلى bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | يكتب السطر الكامل للمسح إلى فهرس سطر المسح المحدد. |
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
public abstract void cacheData()
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
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


يقص المستطيل المحدد.

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
public abstract void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
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
public abstract int getBitsPerPixel()
```


يحصل على عدد البتات لكل بكسل في الصورة.

**Returns:**
int - عدد بتات الصورة لكل بكسل.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public Image getContainer()
```


يحصل على حاوية الصورة.

القيمة: حاوية الصورة.

إذا لم تكن هذه الخاصية فارغة، فهذا يدل على أن الصورة مضمَّنة داخل صورة أخرى.

**Returns:**
[Image](../../com.aspose.psd/image)
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
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


يحصل على ارتفاع الصورة.

**Returns:**
int - ارتفاع الصورة.
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
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


يحصل على مراقب المقاطعة.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
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
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


يحصل على مسار ملف الصورة المصدر إذا كان موجودًا. يعيد سلسلة فارغة إذا تعذر العثور على المسار المصدر.

**Returns:**
java.lang.String - مسار ملف الصورة المصدر.
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
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


يحصل على عرض الصورة.

**Returns:**
int - عرض الصورة.
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

**Returns:**
boolean -  true  إذا كان لهذا الكائن ألفا؛ وإلا،  false .
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

### isCached() {#isCached--}
```
public abstract boolean isCached()
```


يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات.
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


يعيد تحجيم الصورة باستخدام خيارات موسعة.

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
public abstract void rotateFlip(int rotateFlipType)
```


يدور، يقلب، أو يدور ويقلب الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع التدوير والقلب | int | نوع التدوير أو القلب. |

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

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


يضبط مراقب المقاطعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | مراقب المقاطعة. |

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


يضبط الدقة لهذا  RasterImage .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dpiX | double | دقة الأفقية، بوحدات النقاط في البوصة، لصورة  RasterImage . |
| dpiY | double | دقة العمودية، بوحدات النقاط في البوصة، لصورة  RasterImage . |

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

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


يحصل أو يعيّن بيانات XMP الوصفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | بيانات XMP الوصفية. |

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

