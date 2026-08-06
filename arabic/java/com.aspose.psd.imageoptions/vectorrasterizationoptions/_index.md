---
title: "VectorRasterizationOptions"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "خيارات تحويل المتجه إلى نقطية."
type: docs
weight: 29
url: /ar/java/com.aspose.psd.imageoptions/vectorrasterizationoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class VectorRasterizationOptions extends ImageOptionsBase
```

خيارات تحويل المتجه إلى نقطية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions--) |  |
| [VectorRasterizationOptions(VectorRasterizationOptions imageOptions)](#VectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | تنفذ واجهة Closable ويمكن استخدامها في عبارة try-with-resources منذ JDK 1.7. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | ينسخ إلى. |
| [deepClone()](#deepClone--) | ينسخ هذه النسخة. |
| [deepClone_internalized()](#deepClone-internalized--) | ينسخ هذه النسخة. |
| [dispose()](#dispose--) | يحرر النسخة الحالية. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على لون الخلفية. |
| [getBorderX()](#getBorderX--) | يحصل أو يعيّن حد X. |
| [getBorderY()](#getBorderY--) | يحصل أو يعيّن حد Y. |
| [getBufferSizeHint()](#getBufferSizeHint--) | يحصل أو يضبط إشارة حجم المخزن المؤقت التي تُعرّف الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [getCenterDrawing()](#getCenterDrawing--) | يحصل على قيمة تشير إلى ما إذا كان الرسم مركزيًا. |
| [getClass()](#getClass--) |  |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | يحصل أو يضبط الخط الافتراضي البديل (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD متاحًا في النظام). |
| [getDisposed()](#getDisposed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [getDrawColor()](#getDrawColor--) | يحصل على لون المقدمة. |
| [getFullFrame()](#getFullFrame--) | يحصل على قيمة تشير إلى ما إذا كان [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان التجاهل بعد حدث الإنشاء. |
| [getMultiPageOptions()](#getMultiPageOptions--) | خيارات الصفحات المتعددة |
| [getPageHeight()](#getPageHeight--) | يحصل على ارتفاع الصفحة. |
| [getPageSize()](#getPageSize--) | يحصل على حجم الصفحة. |
| [getPageWidth()](#getPageWidth--) | يحصل على عرض الصفحة. |
| [getPalette()](#getPalette--) | يحصل أو يضبط لوحة الألوان. |
| [getPositioning()](#getPositioning--) | يحصل على التموضع. |
| [getProgressEventHandler()](#getProgressEventHandler--) | يحصل أو يضبط معالج حدث التقدم. |
| [getResolutionSettings()](#getResolutionSettings--) | يحصل أو يضبط إعدادات الدقة. |
| [getSmoothingMode()](#getSmoothingMode--) | يحصل على وضع التنعيم. |
| [getSource()](#getSource--) | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| [getTextRenderingHint()](#getTextRenderingHint--) | يحصل على تلميح عرض النص. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | يحصل أو يضبط خيارات تمثيل المتجهات. |
| [getXmpData()](#getXmpData--) | يحصل أو يضبط حاوية بيانات التعريف XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | يضبط لون الخلفية. |
| [setBorderX(float value)](#setBorderX-float-) | يحصل أو يعيّن حد X. |
| [setBorderY(float value)](#setBorderY-float-) | يحصل أو يعيّن حد Y. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | يحصل أو يضبط إشارة حجم المخزن المؤقت التي تُعرّف الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | يضبط قيمة تشير إلى ما إذا كان الرسم مركزيًا. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | يحصل أو يضبط الخط الافتراضي البديل (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD متاحًا في النظام). |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.psd.Color-) | يضبط لون المقدمة. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | يضبط قيمة تشير إلى ما إذا كان [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان التجاهل بعد حدث الإنشاء. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | خيارات الصفحات المتعددة |
| [setPageHeight(float value)](#setPageHeight-float-) | يضبط ارتفاع الصفحة. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.psd.SizeF-) | يضبط حجم الصفحة. |
| [setPageWidth(float value)](#setPageWidth-float-) | يضبط عرض الصفحة. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | يحصل أو يضبط لوحة الألوان. |
| [setPositioning(int value)](#setPositioning-int-) | يضبط التموضع. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | يحصل أو يضبط معالج حدث التقدم. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | يحصل أو يضبط إعدادات الدقة. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | يضبط وضع التنعيم. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | يضبط تلميح عرض النص. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | يحصل أو يضبط خيارات تمثيل المتجهات. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | يحصل أو يضبط حاوية بيانات التعريف XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorRasterizationOptions() {#VectorRasterizationOptions--}
```
public VectorRasterizationOptions()
```


### VectorRasterizationOptions(VectorRasterizationOptions imageOptions) {#VectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public VectorRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


ينسخ إلى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | خيارات تحويل المتجه إلى نقطية. |

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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


يحصل على لون الخلفية.

**Returns:**
[Color](../../com.aspose.psd/color) - a background color.
### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


يحصل أو يعيّن حد X.

**Returns:**
float - الحد X.
### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


يحصل أو يعيّن حد Y.

**Returns:**
float - الحد Y.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


يحصل أو يضبط إشارة حجم المخزن المؤقت التي تُعرّف الحد الأقصى المسموح به لجميع المخازن الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الموجبة تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Returns:**
int
### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


يحصل على قيمة تشير إلى ما إذا كان الرسم مركزيًا.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان الرسم مركزيًا.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


يحصل على لون المقدمة.

**Returns:**
[Color](../../com.aspose.psd/color) - a foreground color.
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
### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


يحصل على ارتفاع الصفحة.

**Returns:**
float - ارتفاع الصفحة.
### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


يحصل على حجم الصفحة.

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - the page size.
### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


يحصل على عرض الصفحة.

**Returns:**
float - عرض الصفحة.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


يحصل أو يضبط لوحة الألوان.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


يحصل على التموضع.

القيمة: التموضع.

**Returns:**
int - التموضع.
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
### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


يحصل على وضع التنعيم.

**Returns:**
int - وضع التنعيم.
### getSource() {#getSource--}
```
public final Source getSource()
```


يحصل أو يضبط المصدر لإنشاء الصورة فيه.

القيمة: المصدر لإنشاء الصورة فيه.

**Returns:**
[Source](../../com.aspose.psd/source)
### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


يحصل على تلميح عرض النص.

القيمة: تلميح عرض النص.

**Returns:**
int - تلميح عرض النص.
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

القيمة: حاوية بيانات XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


يضبط لون الخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | لون خلفية. |

### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


يحصل أو يعيّن حد X.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | الحد X. |

### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


يحصل أو يعيّن حد Y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | الحد Y. |

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

### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان الرسم مركزيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان الرسم في المركز. |

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

### setDrawColor(Color value) {#setDrawColor-com.aspose.psd.Color-}
```
public void setDrawColor(Color value)
```


يضبط لون المقدمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | لون المقدمة. |

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

### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


يضبط ارتفاع الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | ارتفاع الصفحة. |

### setPageSize(SizeF value) {#setPageSize-com.aspose.psd.SizeF-}
```
public void setPageSize(SizeF value)
```


يضبط حجم الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) | حجم الصفحة. |

### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


يضبط عرض الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | عرض الصفحة. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


يحصل أو يضبط لوحة الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


يضبط التموضع.

القيمة: التموضع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الموضع. |

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

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


يضبط وضع التنعيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | وضع التنعيم. |

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

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


يضبط تلميح عرض النص.

القيمة: تلميح عرض النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تلميح عرض النص. |

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

القيمة: حاوية بيانات XMP.

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

