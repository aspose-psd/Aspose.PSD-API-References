---
title: "صورة"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "الصورة هي الفئة الأساسية لجميع أنواع الصور."
type: docs
weight: 54
url: /ar/java/com.aspose.psd/image/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter)

**All Implemented Interfaces:**
[com.aspose.psd.IObjectWithBounds](../../com.aspose.psd/iobjectwithbounds), com.aspose.internal.progressmanagement.IProgressInformer, com.aspose.internal.progressmanagement.IProgressEventHandler
```
public abstract class Image extends DataStreamSupporter implements IObjectWithBounds, IProgressInformer, IProgressEventHandler
```

الصورة هي الفئة الأساسية لجميع أنواع الصور.
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
| [cacheData()](#cacheData--) | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من DataStreamSupporter.DataStreamContainer الأساسي. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واختياريًا باستخدام loadOptions المحدد. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واستخدام خيارات الفتح المحددة اختياريًا. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | يحدد ما إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة. |
| [close()](#close--) | تنفذ واجهة Closable ويمكن استخدامها في عبارة try-with-resources منذ JDK 1.7. |
| [convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | يحول إلى aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| [dispose()](#dispose--) | يحرر النسخة الحالية. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | يحصل على قيمة تشير إلى ما إذا كان تعديل اللوحة تلقائيًا. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على أو يعيّن قيمة للون الخلفية. |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد البتات لكل بكسل في الصورة. |
| [getBounds()](#getBounds--) | يحصل على حدود الصورة. |
| [getBufferSizeHint()](#getBufferSizeHint--) | يحصل على تلميح حجم المخزن المؤقت الذي يُعرّف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | يحصل على حاوية الصورة. |
| [getDataStreamContainer()](#getDataStreamContainer--) | يحصل على تدفق بيانات الكائن. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | يحصل على تعديل عميق للوحة الألوان. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | يحصل على الخيارات الافتراضية. |
| [getDisposed()](#getDisposed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [getFileFormat()](#getFileFormat--) | يحصل على قيمة تنسيق الملف |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | يحصل على تنسيق الملف. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | يحصل على تنسيق الملف. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | يحصل على تنسيق الملف. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصورة. |
| [getInterruptMonitor()](#getInterruptMonitor--) | يحصل على مراقب المقاطعة. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | يحصل على مدير الذاكرة. |
| [getOriginalOptions()](#getOriginalOptions--) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | يحصل على الصورة القابلة للرسم. |
| [getPalette()](#getPalette--) | يحصل على لوحة الألوان. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | ينشئ ذاكرة التخزين المؤقت للخطوط الخاصة. |
| [getProgressEventHandler()](#getProgressEventHandler--) | يحصل على معلومات معالج حدث التقدم. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | يحصل على معلومات معالج حدث التقدم. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | يحصل على ارتفاع نسبي. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | يحصل على عرض نسبي. |
| [getSize()](#getSize--) | يحصل على حجم الصورة. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | يحصل على مسار ملف الصورة المصدر إذا كان موجودًا. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | يحصل على قيمة تشير إلى ما إذا كان الكائن يستخدم استراتيجية تحسين الذاكرة |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | يحصل على رخصة المشروع. |
| [getWidth()](#getWidth--) | يحصل على عرض الصورة. |
| [hasBackgroundColor()](#hasBackgroundColor--) | يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت نسخة الصورة هذه قد تغيرت بعد التحميل. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | يحصل أو يعيّن القيمة القصوى للتقدم |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | يشير إلى التقدم. |
| [isCached()](#isCached--) | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات. |
| [isUsePalette()](#isUsePalette--) | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| [load(InputStream stream)](#load-java.io.InputStream-) | يحمّل صورة جديدة من الدفق المحدد. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | يحمّل صورة جديدة من الدفق المحدد. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | يحمّل صورة جديدة من الدفق المحدد. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | يحمّل صورة جديدة من الدفق المحدد. |
| [load(String filePath)](#load-java.lang.String-) | يحمّل صورة جديدة من الملف المحدد. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | يحمّل صورة جديدة من الملف المحدد. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | يحمّل صورة جديدة من الدفق المحدد. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | يحمّل صورة جديدة من الدفق المحدد. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | استدعاء عندما تم تعيين حاوية هذا [Image](../../com.aspose.psd/image). |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | يغير حجم الصورة. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | يغير حجم الصورة. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | يغير حجم الصورة. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | يعيد تحجيم الارتفاع بنسبة متناسبة. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | يعيد تحجيم الارتفاع بنسبة متناسبة. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | يعيد تحجيم الارتفاع بنسبة متناسبة. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | يعيد تحجيم العرض بنسبة متناسبة. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | يعيد تحجيم العرض بنسبة متناسبة. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | يعيد تحجيم العرض بنسبة متناسبة. |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) |  |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | يضبط قيمة تشير إلى ما إذا كان يتم تعديل لوحة الألوان تلقائيًا. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | يحصل على أو يعيّن قيمة للون الخلفية. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | يضبط حاوية الصورة. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | يضبط دفق بيانات الكائن. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | يضبط قيمة تشير إلى ما إذا كان [تجاهل بعد الحفظ]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت نسخة الصورة هذه قد تغيرت بعد التحميل. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | يضبط مراقب المقاطعة. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | يضبط مدير الذاكرة. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | يضبط لوحة الألوان. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | يضبط لوحة ألوان الصورة. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | يجب على جميع منتجات Aspose تنفيذ هذه الطريقة. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public abstract ApsPage convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)
```


يحول إلى aps.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | خيارات الصورة. |
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
### dispose() {#dispose--}
```
public final void dispose()
```


يحرر النسخة الحالية.

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
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


يحصل على ارتفاع الصورة.

**Returns:**
int - ارتفاع الصورة.
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
### getSize() {#getSize--}
```
public Size getSize()
```


يحصل على حجم الصورة.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


يحصل على مسار ملف الصورة المصدر إذا كان موجودًا. يعيد سلسلة فارغة إذا تعذر العثور على المسار المصدر.

**Returns:**
java.lang.String - مسار ملف الصورة المصدر.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


يحصل على قيمة تشير إلى ما إذا كان الكائن يستخدم استراتيجية تحسين الذاكرة

القيمة:  true  إذا كان الكائن يستخدم استراتيجية تحسين الذاكرة؛ وإلا،  false .

**Returns:**
boolean - قيمة تشير إلى ما إذا كان الكائن يستخدم استراتيجية تحسين الذاكرة
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


يحصل على رخصة المشروع.

**Returns:**
java.lang.Object - رخصة المشروع ككائن.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


يحصل على عرض الصورة.

**Returns:**
int - عرض الصورة.
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
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
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
public abstract void resize(int newWidth, int newHeight, int resizeType)
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




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


يضبط دفق بيانات الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | دفق بيانات الكائن. |

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
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


يضبط لوحة ألوان الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | لوحة الألوان لتعيينها. |
| updateColors | boolean | إذا تم تعيينه إلى  صحيح  سيتم تحديث الألوان وفقًا للوحة الجديدة؛ وإلا ستبقى مؤشرات الألوان دون تغيير. ملاحظة أن المؤشرات غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض المؤشرات إدخالات لوحة مقابلة. |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


يجب على جميع منتجات Aspose تنفيذ هذه الطريقة. يتم استدعاؤها من قبل منتج GroupDocs للإشارة إلى ما إذا كان GroupDocs نفسه مرخصًا أم لا وتحديد علامة مائية مخصصة. عندما يكون GroupDocs مرخصًا، يجب أن يتصرف كائن المستند هذا كمرخص أيضًا حتى إذا لم يكن منتج Aspose مرخصًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ventureLicense | java.lang.Object |  |

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

