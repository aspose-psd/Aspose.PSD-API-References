---
title: "GifOptions"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "خيارات إنشاء صيغة ملف gif."
type: docs
weight: 12
url: /ar/java/com.aspose.psd.imageoptions/gifoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

خيارات إنشاء صيغة ملف gif.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GifOptions()](#GifOptions--) | ينشئ مثيلاً جديدًا من الفئة  GifOptions . |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.psd.imageoptions.GifOptions-) | ينشئ مثيلاً جديدًا من الفئة  GifOptions . |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | تنفذ واجهة Closable ويمكن استخدامها في عبارة try-with-resources منذ JDK 1.7. |
| [deepClone()](#deepClone--) | ينسخ هذه النسخة. |
| [deepClone_internalized()](#deepClone-internalized--) | ينسخ هذه النسخة. |
| [dispose()](#dispose--) | يحرر النسخة الحالية. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | يحصل أو يعيّن فهرس لون خلفية GIF. |
| [getBufferSizeHint()](#getBufferSizeHint--) | يحصل أو يضبط إشارة حجم المخزن المؤقت التي تُعرّف الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [getClass()](#getClass--) |  |
| [getColorResolution()](#getColorResolution--) | يحصل أو يعيّن دقة لون GIF. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | يحصل أو يضبط الخط الافتراضي البديل (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD متاحًا في النظام). |
| [getDisposed()](#getDisposed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | يحصل أو يعيّن قيمة تشير إلى ما إذا تم تطبيق تصحيح اللوحة. |
| [getFullFrame()](#getFullFrame--) | يحصل على قيمة تشير إلى ما إذا كان [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان التجاهل بعد حدث الإنشاء. |
| [getInterlaced()](#getInterlaced--) | True إذا كان يجب أن تكون الصورة متشابكة. |
| [getMaxDiff()](#getMaxDiff--) | يحصل أو يعيّن الحد الأقصى المسموح به لاختلاف البكسل. |
| [getMultiPageOptions()](#getMultiPageOptions--) | خيارات الصفحات المتعددة |
| [getPalette()](#getPalette--) | يحصل أو يضبط لوحة الألوان. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | يحصل أو يعيّن نسبة أبعاد بكسل GIF. |
| [getProgressEventHandler()](#getProgressEventHandler--) | يحصل أو يضبط معالج حدث التقدم. |
| [getResolutionSettings()](#getResolutionSettings--) | يحصل أو يضبط إعدادات الدقة. |
| [getSource()](#getSource--) | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | يحصل أو يضبط خيارات تمثيل المتجهات. |
| [getXmpData()](#getXmpData--) | يحصل أو يضبط حاوية بيانات التعريف XMP. |
| [hasTrailer()](#hasTrailer--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على مقطورة. |
| [hashCode()](#hashCode--) |  |
| [isPaletteSorted()](#isPaletteSorted--) | يحصل أو يعيّن قيمة تشير إلى ما إذا تم فرز مدخلات اللوحة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | يحصل أو يعيّن فهرس لون خلفية GIF. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | يحصل أو يضبط إشارة حجم المخزن المؤقت التي تُعرّف الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | يحصل أو يعيّن دقة لون GIF. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | يحصل أو يضبط الخط الافتراضي البديل (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD متاحًا في النظام). |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا تم تطبيق تصحيح اللوحة. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | يضبط قيمة تشير إلى ما إذا كان [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان التجاهل بعد حدث الإنشاء. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | True إذا كان يجب أن تكون الصورة متشابكة. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | يحصل أو يعيّن الحد الأقصى المسموح به لاختلاف البكسل. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | خيارات الصفحات المتعددة |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | يحصل أو يضبط لوحة الألوان. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا تم فرز مدخلات اللوحة. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | يحصل أو يعيّن نسبة أبعاد بكسل GIF. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | يحصل أو يضبط معالج حدث التقدم. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | يحصل أو يضبط إعدادات الدقة. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على مقطورة. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | يحصل أو يضبط خيارات تمثيل المتجهات. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | يحصل أو يضبط حاوية بيانات التعريف XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


ينشئ مثيلاً جديدًا من الفئة  GifOptions .

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.psd.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


ينشئ مثيلاً جديدًا من الفئة  GifOptions .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.psd.imageoptions/gifoptions) | خيارات GIF. |

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


تنفيذ واجهة Closable ويمكن استخدامها في بيان try-with-resources منذ JDK 1.7. هذه الطريقة تستدعي ببساطة طريقة dispose.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


ينسخ هذه النسخة.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


ينسخ هذه النسخة.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


يحرر النسخة الحالية.

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
### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


يحصل أو يعيّن فهرس لون خلفية GIF.

**Returns:**
byte - فهرس لون خلفية GIF.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


يحصل أو يضبط إشارة حجم المخزن المؤقت التي تُعرّف الحد الأقصى المسموح به لجميع المخازن الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الموجبة تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


يحصل أو يعيّن دقة لون GIF.

**Returns:**
byte - دقة اللون.

Color Resolution - عدد البتات لكل لون أساسي متاح في الصورة الأصلية، ناقص 1. تمثل هذه القيمة حجم اللوحة الكاملة التي تم اختيار الألوان منها في الرسم، وليس عدد الألوان المستخدمة فعليًا في الرسم. على سبيل المثال، إذا كانت القيمة في هذا الحقل هي 3، فإن لوحة الصورة الأصلية كان لديها 4 بتات لكل لون أساسي متاح لإنشاء الصورة. يجب ضبط هذه القيمة لتشير إلى غنى اللوحة الأصلية، حتى إذا لم يكن كل لون من اللوحة بالكامل متاحًا على الجهاز المصدر.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


يحصل أو يضبط الخط الافتراضي للاستبدال (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD موجودًا في النظام). للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام مقتطف الشيفرة التالي: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

القيمة: الخط الافتراضي للاستبدال.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه.

**Returns:**
boolean -  true  إذا تم التخلص؛ وإلا،  false .
### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا تم تطبيق تصحيح اللوحة.

**Returns:**
boolean -  true  إذا تم تطبيق تصحيح اللوحة؛ وإلا،  false .

تصحيح اللوحة يعني أنه كلما تم تصدير الصورة إلى GIF سيتم تحليل ألوان الصورة المصدر لبناء أفضل لوحة مطابقة (في حالة عدم وجود لوحة للصورة أو عدم تحديدها في الخيارات). تستغرق عملية التحليل بعض الوقت ولكن الصورة الناتجة ستحصل على أفضل لوحة ألوان مطابقة والنتيجة تكون بصريًا أفضل.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


يحصل على قيمة تشير إلى ما إذا كان [full frame].

القيمة:  true  إذا كان [full frame]؛ وإلا،  false .

**Returns:**
منطقي - قيمة تشير إلى ما إذا كان [full frame].
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان التجاهل بعد حدث الإنشاء.

القيمة:  true  إذا تم التجاهل بعد حدث الإنشاء؛ وإلا،  false .

**Returns:**
boolean
### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


True إذا كان يجب أن تكون الصورة متشابكة.

**Returns:**
boolean
### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


يحصل أو يحدد الحد الأقصى المسموح به لاختلاف البكسل. إذا كان أكبر من الصفر، سيتم استخدام ضغط فقدان. القيمة الموصى بها لضغط فقدان مثالي هي 80. 30 يعني ضغط خفيف جدًا، 200 يعني ضغط ثقيل. يعمل بأفضل شكل عندما يتم إدخال فقدان قليل فقط، وبسبب قيود خوارزمية الضغط لا تعطي مستويات الفقدان العالية جدًا الكثير من الفائدة. نطاق القيم المسموح بها هو [0, 1000].

**Returns:**
int - نطاق القيم المسموح بها.
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


خيارات الصفحات المتعددة

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


يحصل أو يضبط لوحة الألوان.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


يحصل أو يعيّن نسبة أبعاد بكسل GIF.

نسبة أبعاد البكسل - عامل يُستخدم لحساب تقريب لنسبة أبعاد البكسل في الصورة الأصلية. إذا لم تكن قيمة الحقل 0، يتم حساب هذا التقريب للنسبة بناءً على الصيغة: النسبة = (نسبة أبعاد البكسل + 15) / 64 تُعرّف نسبة أبعاد البكسل بأنها ناتج قسمة عرض البكسل على ارتفاعه. يتيح نطاق القيم في هذا الحقل تحديد أوسع بكسل بنسبة 4:1 إلى أطول بكسل بنسبة 1:4 بزيادات قدرها 1/64. القيم: 0 - لا توجد معلومات عن نسبة الأبعاد. 1..255 - القيمة المستخدمة في الحساب.

**Returns:**
byte - نسبة أبعاد بكسل GIF.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


يحصل أو يضبط معالج حدث التقدم.

القيمة: معالج حدث التقدم.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


يحصل أو يضبط إعدادات الدقة.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getSource() {#getSource--}
```
public final Source getSource()
```


يحصل أو يضبط المصدر لإنشاء الصورة فيه.

القيمة: المصدر لإنشاء الصورة فيه.

**Returns:**
[Source](../../com.aspose.psd/source)
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


يحصل أو يضبط خيارات تمثيل المتجهات.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


يحصل أو يضبط حاوية بيانات التعريف XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على مقطورة.

**Returns:**
boolean -  true  إذا كان GIF يحتوي على مقطع نهائي؛ وإلا،  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا تم فرز مدخلات اللوحة.

**Returns:**
boolean -  true  إذا كانت مدخلات اللوحة مرتبة؛ وإلا،  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


يحصل أو يعيّن فهرس لون خلفية GIF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte | فهرس لون خلفية GIF. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


يحصل أو يضبط إشارة حجم المخزن المؤقت التي تُعرّف الحد الأقصى المسموح به لجميع المخازن الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الموجبة تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


يحصل أو يعيّن دقة لون GIF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | byte | دقة اللون. |

دقة اللون - عدد البتات لكل لون أساسي متاح في الصورة الأصلية، ناقص 1. تمثل هذه القيمة حجم اللوحة الكاملة التي تم اختيار الألوان منها في الرسم، وليس عدد الألوان المستخدمة فعليًا في الرسم. على سبيل المثال، إذا كانت القيمة في هذا الحقل 3، فإن لوحة الصورة الأصلية كان لديها 4 بتات لكل لون أساسي متاح لإنشاء الصورة. يجب ضبط هذه القيمة للإشارة إلى غنى اللوحة الأصلية، حتى إذا لم يكن كل لون من اللوحة الكاملة متاحًا على الجهاز المصدر. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


يحصل أو يضبط الخط الافتراضي للاستبدال (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD موجودًا في النظام). للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام مقتطف الشيفرة التالي: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

القيمة: الخط الافتراضي للاستبدال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا تم تطبيق تصحيح اللوحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  إذا تم تطبيق تصحيح اللوحة؛ وإلا،  false . |

تصحيح اللوحة يعني أنه كلما تم تصدير الصورة إلى GIF سيتم تحليل ألوان الصورة المصدر لبناء أفضل لوحة مطابقة (في حالة عدم وجود لوحة للصورة أو عدم تحديدها في الخيارات). تستغرق عملية التحليل بعض الوقت ولكن الصورة الناتجة ستحصل على أفضل لوحة ألوان مطابقة والنتيجة تكون بصريًا أفضل. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان [full frame].

القيمة:  true  إذا كان [full frame]؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان [full frame]. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان التجاهل بعد حدث الإنشاء.

القيمة:  true  إذا تم التجاهل بعد حدث الإنشاء؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


True إذا كان يجب أن تكون الصورة متشابكة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


يحصل أو يحدد الحد الأقصى المسموح به لاختلاف البكسل. إذا كان أكبر من الصفر، سيتم استخدام ضغط فقدان. القيمة الموصى بها لضغط فقدان مثالي هي 80. 30 يعني ضغط خفيف جدًا، 200 يعني ضغط ثقيل. يعمل بأفضل شكل عندما يتم إدخال فقدان قليل فقط، وبسبب قيود خوارزمية الضغط لا تعطي مستويات الفقدان العالية جدًا الكثير من الفائدة. نطاق القيم المسموح بها هو [0, 1000].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | نطاق القيم المسموح بها. |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


خيارات الصفحات المتعددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


يحصل أو يضبط لوحة الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا تم فرز مدخلات اللوحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | true  إذا كانت مدخلات اللوحة مرتبة؛ وإلا،  false . |

### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


يحصل أو يعيّن نسبة أبعاد بكسل GIF.

نسبة أبعاد البكسل - عامل يُستخدم لحساب تقريب لنسبة أبعاد البكسل في الصورة الأصلية. إذا لم تكن قيمة الحقل 0، يتم حساب هذا التقريب للنسبة بناءً على الصيغة: النسبة = (نسبة أبعاد البكسل + 15) / 64 تُعرّف نسبة أبعاد البكسل بأنها ناتج قسمة عرض البكسل على ارتفاعه. يتيح نطاق القيم في هذا الحقل تحديد أوسع بكسل بنسبة 4:1 إلى أطول بكسل بنسبة 1:4 بزيادات قدرها 1/64. القيم: 0 - لا توجد معلومات عن نسبة الأبعاد. 1..255 - القيمة المستخدمة في الحساب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte | نسبة أبعاد بكسل GIF. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


يحصل أو يضبط معالج حدث التقدم.

القيمة: معالج حدث التقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


يحصل أو يضبط إعدادات الدقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


يحصل أو يضبط المصدر لإنشاء الصورة فيه.

القيمة: المصدر لإنشاء الصورة فيه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على مقطورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | true  إذا كان GIF يحتوي على مقطع نهائي؛ وإلا،  false . |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


يحصل أو يضبط خيارات تمثيل المتجهات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


يحصل أو يضبط حاوية بيانات التعريف XMP.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | حاوية بيانات XMP. |

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

