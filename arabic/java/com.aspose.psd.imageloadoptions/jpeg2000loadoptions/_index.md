---
title: "Jpeg2000LoadOptions"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "خيارات تحميل JPEG2000"
type: docs
weight: 10
url: /ar/java/com.aspose.psd.imageloadoptions/jpeg2000loadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class Jpeg2000LoadOptions extends LoadOptions
```

خيارات تحميل JPEG2000
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Jpeg2000LoadOptions()](#Jpeg2000LoadOptions--) | ينشئ مثيلاً جديداً من الفئة Jpeg2000LoadOptions. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | مصادر الخطوط المخصصة |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | يحصل على تلميح حجم المخزن المؤقت الذي يُعرّف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | يحصل على لون خلفية الصورة. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | يحصل على وضع استعادة البيانات. |
| [getDefaultMaximumDecodingTime_internalized()](#getDefaultMaximumDecodingTime-internalized--) | يحصل على الحد الأقصى الافتراضي لوقت فك الترميز. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | يحصل على قيمة تشير إلى ما إذا كان [ignore after load]. |
| [getMaximumDecodingTime()](#getMaximumDecodingTime--) | يحصل على الحد الأقصى لوقت فك الترميز بالثواني (يمكن استخدام هذا الخيار على الأجهزة البطيئة جداً أو ذات الذاكرة المحدودة لمنع التوقف أثناء معالجة الصور الكبيرة - الدقة أكثر من 5500x6500 بكسل). |
| [getMaximumDecodingTimeForTile()](#getMaximumDecodingTimeForTile--) | يحصل على الحد الأقصى لوقت فك الترميز للقطعة. |
| [getProgressEventHandler()](#getProgressEventHandler--) | يحصل على معالج حدث التقدم. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | يحصل على قيمة تشير إلى ما إذا كان يجب تطبيق تحويل ملف تعريف ICC. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | هذا جزء من نمط ترخيص المشروع. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | يضبط لون خلفية الصورة. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | يضبط وضع استعادة البيانات. |
| [setDefaultMaximumDecodingTime_internalized(int value)](#setDefaultMaximumDecodingTime-internalized-int-) | يضبط الوقت الأقصى الافتراضي لفك الترميز. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | يضبط قيمة تشير إلى ما إذا كان سيتم [ignore after load]. |
| [setMaximumDecodingTime(int value)](#setMaximumDecodingTime-int-) | يضبط الوقت الأقصى لفك الترميز بالثواني (يمكن استخدام هذا الخيار على الأجهزة البطيئة ذات الذاكرة القليلة لمنع توقف العملية عند معالجة صور كبيرة جدًا - دقة أكثر من 5500×6500 بكسل). |
| [setMaximumDecodingTimeForTile(int value)](#setMaximumDecodingTimeForTile-int-) | يضبط الوقت الأقصى لفك الترميز للبلاطة. |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | يحصل أو يضبط مدير الذاكرة MGR. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | يضبط معالج حدث التقدم. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | يضبط قيمة تشير إلى ما إذا كان يجب تطبيق تحويل ملف تعريف ICC. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | هذا جزء من نمط ترخيص المشروع. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Jpeg2000LoadOptions() {#Jpeg2000LoadOptions--}
```
public Jpeg2000LoadOptions()
```


ينشئ مثيلاً جديداً من الفئة Jpeg2000LoadOptions.

### CustomFontSources_internalized {#CustomFontSources-internalized}
```
public System.Collections.Generic.List<CustomFontSource> CustomFontSources_internalized
```


مصادر الخطوط المخصصة

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
### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


يحصل على لون خلفية الصورة.

**Returns:**
[Color](../../com.aspose.psd/color) - The background color.

عادةً ما يتم تعيين لون الخلفية عندما لا يمكن استعادة قيمة البكسل بسبب تلف البيانات.
### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


يحصل على وضع استعادة البيانات.

**Returns:**
int - وضع استعادة البيانات.
### getDefaultMaximumDecodingTime_internalized() {#getDefaultMaximumDecodingTime-internalized--}
```
public static int getDefaultMaximumDecodingTime_internalized()
```


يحصل على الحد الأقصى الافتراضي لوقت فك الترميز.

**Returns:**
int - الوقت الأقصى الافتراضي لفك الترميز.
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


يحصل على قيمة تشير إلى ما إذا كان [ignore after load].

**Returns:**
boolean -  true  إذا كان [ignore after load]; وإلا،  false .
### getMaximumDecodingTime() {#getMaximumDecodingTime--}
```
public int getMaximumDecodingTime()
```


يحصل على الحد الأقصى لوقت فك الترميز بالثواني (يمكن استخدام هذا الخيار على الأجهزة البطيئة جداً أو ذات الذاكرة المحدودة لمنع التوقف أثناء معالجة الصور الكبيرة - الدقة أكثر من 5500x6500 بكسل).

**Returns:**
int - الوقت الأقصى لفك الترميز.
### getMaximumDecodingTimeForTile() {#getMaximumDecodingTimeForTile--}
```
public final int getMaximumDecodingTimeForTile()
```


يحصل على الحد الأقصى لوقت فك الترميز للقطعة.

القيمة: الوقت الأقصى لفك الترميز للبلاطة.

**Returns:**
int - الوقت الأقصى لفك الترميز للبلاطة.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


يحصل على معالج حدث التقدم.

القيمة: معالج حدث التقدم.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


يحصل على قيمة تشير إلى ما إذا كان يجب تطبيق تحويل ملف تعريف ICC.

**Returns:**
boolean
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


هذا جزء من نمط ترخيص المشروع. سيتم تعيين هذه القيمة بواسطة VentureLicenser إذا مررنا كائن LoadOptions من المشروع.

**Returns:**
java.lang.Object
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

### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.psd.Color-}
```
public void setDataBackgroundColor(Color value)
```


يضبط لون خلفية الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.psd/color) | لون الخلفية. |

عادةً ما يتم تعيين لون الخلفية عندما لا يمكن استعادة قيمة البكسل بسبب تلف البيانات. |

### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


يضبط وضع استعادة البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | وضع استعادة البيانات. |

### setDefaultMaximumDecodingTime_internalized(int value) {#setDefaultMaximumDecodingTime-internalized-int-}
```
public static void setDefaultMaximumDecodingTime_internalized(int value)
```


يضبط الوقت الأقصى الافتراضي لفك الترميز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الوقت الأقصى الافتراضي لفك الترميز. |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان سيتم [ignore after load].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | true  إذا كان [ignore after load]; وإلا،  false . |

### setMaximumDecodingTime(int value) {#setMaximumDecodingTime-int-}
```
public void setMaximumDecodingTime(int value)
```


يضبط الوقت الأقصى لفك الترميز بالثواني (يمكن استخدام هذا الخيار على الأجهزة البطيئة ذات الذاكرة القليلة لمنع توقف العملية عند معالجة صور كبيرة جدًا - دقة أكثر من 5500×6500 بكسل).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الوقت الأقصى لفك الترميز. |

### setMaximumDecodingTimeForTile(int value) {#setMaximumDecodingTimeForTile-int-}
```
public final void setMaximumDecodingTimeForTile(int value)
```


يضبط الوقت الأقصى لفك الترميز للبلاطة.

القيمة: الوقت الأقصى لفك الترميز للبلاطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الوقت الأقصى لفك الترميز للبلاطة. |

### setMemMgr_internalized(MemMgr value) {#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-}
```
public final void setMemMgr_internalized(MemMgr value)
```


يحصل أو يضبط مدير الذاكرة MGR.

القيمة: مدير الذاكرة MGR.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.internal.memorymanagement.MemMgr |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


يضبط معالج حدث التقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | معالج حدث التقدم. |

### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان يجب تطبيق تحويل ملف تعريف ICC.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setVentureLicense_internalized(Object value) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object value)
```


هذا جزء من نمط ترخيص المشروع. سيتم تعيين هذه القيمة بواسطة VentureLicenser إذا مررنا كائن LoadOptions من المشروع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.Object |  |

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

