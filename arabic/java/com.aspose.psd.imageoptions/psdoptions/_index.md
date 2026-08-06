---
title: "PsdOptions"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "خيارات إنشاء صيغة ملف psd."
type: docs
weight: 21
url: /ar/java/com.aspose.psd.imageoptions/psdoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

خيارات إنشاء صيغة ملف psd.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | ينشئ مثيلاً جديداً من الفئة [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-) | ينشئ مثيلاً جديداً من الفئة [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
| [PsdOptions(PsdImage image)](#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-) | ينشئ مثيلاً جديداً من الفئة [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | تنفذ واجهة Closable ويمكن استخدامها في عبارة try-with-resources منذ JDK 1.7. |
| [deepClone()](#deepClone--) | ينسخ هذه النسخة. |
| [deepClone_internalized()](#deepClone-internalized--) | ينسخ هذه النسخة. |
| [dispose()](#dispose--) | يحرر النسخة الحالية. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundContents()](#getBackgroundContents--) | يحصل أو يعيّن لون الخلفية. |
| [getBufferSizeHint()](#getBufferSizeHint--) | يحصل أو يضبط إشارة حجم المخزن المؤقت التي تُعرّف الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [getChannelBitsCount()](#getChannelBitsCount--) | يحصل أو يضبط عدد البتات لكل قناة لون. |
| [getChannelsCount()](#getChannelsCount--) | يحصل أو يضبط عدد قنوات اللون. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | يحصل أو يضبط وضع لون PSD. |
| [getCompressionMethod()](#getCompressionMethod--) | يحصل أو يضبط طريقة ضغط PSD. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | يحصل أو يضبط الخط الافتراضي البديل (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD متاحًا في النظام). |
| [getDisposed()](#getDisposed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [getFullFrame()](#getFullFrame--) | يحصل على قيمة تشير إلى ما إذا كان [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان التجاهل بعد حدث الإنشاء. |
| [getMultiPageOptions()](#getMultiPageOptions--) | خيارات الصفحات المتعددة |
| [getPalette()](#getPalette--) | يحصل أو يضبط لوحة الألوان. |
| [getProgressEventHandler()](#getProgressEventHandler--) | يحصل أو يضبط معالج حدث التقدم. |
| [getPsdVersion()](#getPsdVersion--) | يحصل أو يعيّن نسخة تنسيق الملف. |
| [getRefreshImagePreviewData()](#getRefreshImagePreviewData--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [refresh image preview data] - خيار يُستخدم لتعزيز التوافق مع عارضات صور PSD أخرى. |
| [getRemoveGlobalTextEngineResource()](#getRemoveGlobalTextEngineResource--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان - إزالة مورد محرك النص العالمي - يُستخدم لبعض ملفات PSD ذات الطبقات النصية، في الحالة الوحيدة التي لا يمكن فيها فتحها في Adobe Photoshop بعد المعالجة (غالبًا ما يتعلق بطبقات النص التي تفتقد الخطوط). |
| [getResolutionSettings()](#getResolutionSettings--) | يحصل أو يضبط إعدادات الدقة. |
| [getResources()](#getResources--) | يحصل أو يعيّن موارد PSD. |
| [getSource()](#getSource--) | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| [getUpdateMetadata()](#getUpdateMetadata--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [update metadata]. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | يحصل أو يضبط خيارات تمثيل المتجهات. |
| [getVersion()](#getVersion--) | يحصل أو يعيّن نسخة ملف PSD. |
| [getXmpData()](#getXmpData--) | احصل أو اضبط حاوية بيانات XMP |
| [hashCode()](#hashCode--) |  |
| [isColorModeSet()](#isColorModeSet--) | يعرض ما إذا تم تعيين خاصية ColorMode. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundContents(RawColor value)](#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | يحصل أو يعيّن لون الخلفية. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | يحصل أو يضبط إشارة حجم المخزن المؤقت التي تُعرّف الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | يحصل أو يضبط عدد البتات لكل قناة لون. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | يحصل أو يضبط عدد قنوات اللون. |
| [setColorMode(short value)](#setColorMode-short-) | يحصل أو يضبط وضع لون PSD. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | يحصل أو يضبط طريقة ضغط PSD. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | يحصل أو يضبط الخط الافتراضي البديل (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD متاحًا في النظام). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | يضبط قيمة تشير إلى ما إذا كان [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان التجاهل بعد حدث الإنشاء. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | خيارات الصفحات المتعددة |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | يحصل أو يضبط لوحة الألوان. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | يحصل أو يضبط معالج حدث التقدم. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | يحصل أو يعيّن نسخة تنسيق الملف. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [refresh image preview data] - خيار يُستخدم لتعزيز التوافق مع عارضات صور PSD أخرى. |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان - إزالة مورد محرك النص العالمي - يُستخدم لبعض ملفات PSD ذات الطبقات النصية، في الحالة الوحيدة التي لا يمكن فيها فتحها في Adobe Photoshop بعد المعالجة (غالبًا ما يتعلق بطبقات النص التي تفتقد الخطوط). |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | يحصل أو يضبط إعدادات الدقة. |
| [setResources(ResourceBlock[] value)](#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | يحصل أو يعيّن موارد PSD. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| [setUpdateMetadata(boolean value)](#setUpdateMetadata-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [update metadata]. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | يحصل أو يضبط خيارات تمثيل المتجهات. |
| [setVersion(int value)](#setVersion-int-) | يحصل أو يعيّن نسخة ملف PSD. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | احصل أو اضبط حاوية بيانات XMP |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


ينشئ مثيلاً جديداً من الفئة [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


ينشئ مثيلاً جديداً من الفئة [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | الخيارات. |

### PsdOptions(PsdImage image) {#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-}
```
public PsdOptions(PsdImage image)
```


ينشئ مثيلاً جديداً من الفئة [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | الصورة. |

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
### getBackgroundContents() {#getBackgroundContents--}
```
public final RawColor getBackgroundContents()
```


يحصل أو يضبط لون الخلفية. يمكن رؤيته تحت الكائنات الشفافة.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


يحصل أو يضبط إشارة حجم المخزن المؤقت التي تُعرّف الحد الأقصى المسموح به لجميع المخازن الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الموجبة تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Returns:**
int
### getChannelBitsCount() {#getChannelBitsCount--}
```
public final short getChannelBitsCount()
```


يحصل أو يضبط عدد البتات لكل قناة لون.

القيمة: عدد البتات لكل قناة لون.

**Returns:**
short
### getChannelsCount() {#getChannelsCount--}
```
public final short getChannelsCount()
```


يحصل أو يضبط عدد قنوات اللون.

القيمة: عدد قنوات اللون.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


يحصل أو يضبط وضع لون PSD.

القيمة: وضع اللون.

**Returns:**
short
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


يحصل أو يضبط طريقة ضغط PSD.

القيمة: طريقة الضغط.

**Returns:**
short
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
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


يحصل أو يضبط معالج حدث التقدم.

القيمة: معالج حدث التقدم.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


يحصل أو يعيّن نسخة تنسيق الملف. يمكن أن تكون PSD أو PSB.

القيمة: نسخة تنسيق الملف.

**Returns:**
byte
### getRefreshImagePreviewData() {#getRefreshImagePreviewData--}
```
public final boolean getRefreshImagePreviewData()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [refresh image preview data] - خيار يُستخدم لتعزيز التوافق مع عارضات صور PSD أخرى. يرجى ملاحظة أن رسم طبقات النص إلى التخطيط النهائي غير مدعوم لمنصة Compact Framework.

القيمة:  true  إذا كان [refresh image preview data]؛ وإلا،  false .

**Returns:**
boolean
### getRemoveGlobalTextEngineResource() {#getRemoveGlobalTextEngineResource--}
```
public final boolean getRemoveGlobalTextEngineResource()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان - إزالة مورد محرك النص العالمي - يُستخدم لبعض ملفات PSD ذات الطبقات النصية، في الحالة الوحيدة التي لا يمكن فيها فتحها في Adobe Photoshop بعد المعالجة (غالبًا ما يتعلق بطبقات النص التي تفتقد الخطوط). بعد استخدام هذا الخيار، يحتاج المستخدم إلى تنفيذ التالي في الملف المفتوح في Photoshop: القائمة "Text" -> "Process absent fonts". بعد تلك العملية سيظهر كل النص مرة أخرى. يرجى ملاحظة أن هذه العملية قد تسبب بعض التغييرات في التخطيط النهائي.

القيمة:  true  إذا كان [remove global text engine resource]؛ وإلا،  false .

**Returns:**
boolean
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


يحصل أو يضبط إعدادات الدقة.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResources() {#getResources--}
```
public final ResourceBlock[] getResources()
```


يحصل أو يعيّن موارد PSD. إذا كانت القيمة: NULL - يتم حفظ ImageResources الأصلية (السلوك الافتراضي) غير فارغة - يتم حفظ الموارد الممررة إلى هذه الخاصية + [required resources] فارغة - يتم حفظ [required resources] فقط. الموارد المطلوبة: ResolutionInfoResource, XmpResource

القيمة: موارد PSD.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getSource() {#getSource--}
```
public final Source getSource()
```


يحصل أو يضبط المصدر لإنشاء الصورة فيه.

القيمة: المصدر لإنشاء الصورة فيه.

**Returns:**
[Source](../../com.aspose.psd/source)
### getUpdateMetadata() {#getUpdateMetadata--}
```
public final boolean getUpdateMetadata()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [update metadata]. إذا كانت القيمة true، سيتم تحديث البيانات الوصفية أثناء حفظ الصورة.

القيمة:  true  إذا كان [update metadata]؛ وإلا،  false .

**Returns:**
boolean
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


يحصل أو يضبط خيارات تمثيل المتجهات.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVersion() {#getVersion--}
```
public final int getVersion()
```


يحصل أو يعيّن نسخة ملف PSD.

القيمة: نسخة ملف PSD.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


احصل أو اضبط حاوية بيانات XMP

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorModeSet() {#isColorModeSet--}
```
public final boolean isColorModeSet()
```


يعرض ما إذا تم تعيين خاصية ColorMode.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundContents(RawColor value) {#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents(RawColor value)
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


يحصل أو يضبط إشارة حجم المخزن المؤقت التي تُعرّف الحد الأقصى المسموح به لجميع المخازن الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الموجبة تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public final void setChannelBitsCount(short value)
```


يحصل أو يضبط عدد البتات لكل قناة لون.

القيمة: عدد البتات لكل قناة لون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setChannelsCount(short value) {#setChannelsCount-short-}
```
public final void setChannelsCount(short value)
```


يحصل أو يضبط عدد قنوات اللون.

القيمة: عدد قنوات اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


يحصل أو يضبط وضع لون PSD.

القيمة: وضع اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


يحصل أو يضبط طريقة ضغط PSD.

القيمة: طريقة الضغط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

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

### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


يحصل أو يعيّن نسخة تنسيق الملف. يمكن أن تكون PSD أو PSB.

القيمة: نسخة تنسيق الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public final void setRefreshImagePreviewData(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [refresh image preview data] - خيار يُستخدم لتعزيز التوافق مع عارضات صور PSD أخرى. يرجى ملاحظة أن رسم طبقات النص إلى التخطيط النهائي غير مدعوم لمنصة Compact Framework.

القيمة:  true  إذا كان [refresh image preview data]؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public final void setRemoveGlobalTextEngineResource(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان - إزالة مورد محرك النص العالمي - يُستخدم لبعض ملفات PSD ذات الطبقات النصية، في الحالة الوحيدة التي لا يمكن فيها فتحها في Adobe Photoshop بعد المعالجة (غالبًا ما يتعلق بطبقات النص التي تفتقد الخطوط). بعد استخدام هذا الخيار، يحتاج المستخدم إلى تنفيذ التالي في الملف المفتوح في Photoshop: القائمة "Text" -> "Process absent fonts". بعد تلك العملية سيظهر كل النص مرة أخرى. يرجى ملاحظة أن هذه العملية قد تسبب بعض التغييرات في التخطيط النهائي.

القيمة:  true  إذا كان [remove global text engine resource]؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


يحصل أو يضبط إعدادات الدقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResources(ResourceBlock[] value) {#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setResources(ResourceBlock[] value)
```


يحصل أو يعيّن موارد PSD. إذا كانت القيمة: NULL - يتم حفظ ImageResources الأصلية (السلوك الافتراضي) غير فارغة - يتم حفظ الموارد الممررة إلى هذه الخاصية + [required resources] فارغة - يتم حفظ [required resources] فقط. الموارد المطلوبة: ResolutionInfoResource, XmpResource

القيمة: موارد PSD.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

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

### setUpdateMetadata(boolean value) {#setUpdateMetadata-boolean-}
```
public final void setUpdateMetadata(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [update metadata]. إذا كانت القيمة true، سيتم تحديث البيانات الوصفية أثناء حفظ الصورة.

القيمة:  true  إذا كان [update metadata]؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


يحصل أو يضبط خيارات تمثيل المتجهات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


يحصل أو يعيّن نسخة ملف PSD.

القيمة: نسخة ملف PSD.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


احصل أو اضبط حاوية بيانات XMP

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

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

