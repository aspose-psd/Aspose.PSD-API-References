---
title: "PsdLoadOptions"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "خيارات تحميل Psd"
type: docs
weight: 12
url: /ar/java/com.aspose.psd.imageloadoptions/psdloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PsdLoadOptions extends LoadOptions
```

خيارات تحميل Psd
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PsdLoadOptions()](#PsdLoadOptions--) | يُنشئ مثيلاً جديدًا للفئة [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | مصادر الخطوط المخصصة |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNonChangedLayerRepaint()](#getAllowNonChangedLayerRepaint--) | يحصل أو يضبط ما إذا كان يجب الحفاظ على بكسلات الطبقة الأصلية أثناء التصيير إذا لم يتم تعديل الطبقة. |
| [getAllowWarpRepaint()](#getAllowWarpRepaint--) | يحصل أو يضبط ما إذا كان يجب الحفظ مع الصورة المصدَّرة، مع أو بدون تحويل تشويه. |
| [getBufferSizeHint()](#getBufferSizeHint--) | يحصل على تلميح حجم المخزن المؤقت الذي يُعرّف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | يحصل على لون خلفية الصورة. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | يحصل على وضع استعادة البيانات. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | يحصل على قيمة تشير إلى ما إذا كان [ignore after load]. |
| [getIgnoreAlphaChannel()](#getIgnoreAlphaChannel--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [ignore alpha channel]. |
| [getIgnoreTextLayerWidthOnUpdate()](#getIgnoreTextLayerWidthOnUpdate--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان سيتم تجاهل عرض طبقة النص في PSD الثابت عند تنفيذ عملية UpdateText. |
| [getLoadEffectsResource()](#getLoadEffectsResource--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [load effects resource] (بحال الافتراضي لا يتم تحميل المورد). |
| [getProgressEventHandler()](#getProgressEventHandler--) | يحصل على معالج حدث التقدم. |
| [getReadOnlyMode()](#getReadOnlyMode--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [use read only mode]. |
| [getReadOnlyType()](#getReadOnlyType--) | يحصل أو يضبط وضع القراءة فقط المستخدم عند تحميل صورة PSD. |
| [getUseDiskForLoadEffectsResource()](#getUseDiskForLoadEffectsResource--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [use disk for load effects resource] (بحال الافتراضي يُستخدم القرص لتحميل موارد التأثيرات، لكن يمكن استخدام الذاكرة إذا كان ذلك كافيًا بتعيين هذه القيمة إلى false). |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | يحصل على قيمة تشير إلى ما إذا كان يجب تطبيق تحويل ملف تعريف ICC. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | هذا جزء من نمط ترخيص المشروع. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNonChangedLayerRepaint(boolean value)](#setAllowNonChangedLayerRepaint-boolean-) | يحصل أو يضبط ما إذا كان يجب الحفاظ على بكسلات الطبقة الأصلية أثناء التصيير إذا لم يتم تعديل الطبقة. |
| [setAllowWarpRepaint(boolean value)](#setAllowWarpRepaint-boolean-) | يحصل أو يضبط ما إذا كان يجب الحفظ مع الصورة المصدَّرة، مع أو بدون تحويل تشويه. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | يضبط لون خلفية الصورة. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | يضبط وضع استعادة البيانات. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | يضبط قيمة تشير إلى ما إذا كان سيتم [ignore after load]. |
| [setIgnoreAlphaChannel(boolean value)](#setIgnoreAlphaChannel-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [ignore alpha channel]. |
| [setIgnoreTextLayerWidthOnUpdate(boolean value)](#setIgnoreTextLayerWidthOnUpdate-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان سيتم تجاهل عرض طبقة النص في PSD الثابت عند تنفيذ عملية UpdateText. |
| [setLoadEffectsResource(boolean value)](#setLoadEffectsResource-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [load effects resource] (بحال الافتراضي لا يتم تحميل المورد). |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | يحصل أو يضبط مدير الذاكرة MGR. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | يضبط معالج حدث التقدم. |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [use read only mode]. |
| [setReadOnlyType(int value)](#setReadOnlyType-int-) | يحصل أو يضبط وضع القراءة فقط المستخدم عند تحميل صورة PSD. |
| [setUseDiskForLoadEffectsResource(boolean value)](#setUseDiskForLoadEffectsResource-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [use disk for load effects resource] (بحال الافتراضي يُستخدم القرص لتحميل موارد التأثيرات، لكن يمكن استخدام الذاكرة إذا كان ذلك كافيًا بتعيين هذه القيمة إلى false). |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | يضبط قيمة تشير إلى ما إذا كان يجب تطبيق تحويل ملف تعريف ICC. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | هذا جزء من نمط ترخيص المشروع. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdLoadOptions() {#PsdLoadOptions--}
```
public PsdLoadOptions()
```


يُنشئ مثيلاً جديدًا للفئة [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions).

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
### getAllowNonChangedLayerRepaint() {#getAllowNonChangedLayerRepaint--}
```
public final boolean getAllowNonChangedLayerRepaint()
```


يحصل أو يضبط ما إذا كان يجب الحفاظ على بكسلات الطبقة الأصلية أثناء التصيير إذا لم يتم تعديل الطبقة.

القيمة:  true  للاحتفاظ بالبكسلات الأصلية للطبقات غير المتغيّرة؛ وإلا،  false .

**Returns:**
boolean
### getAllowWarpRepaint() {#getAllowWarpRepaint--}
```
public final boolean getAllowWarpRepaint()
```


يحصل أو يضبط ما إذا كان يجب الحفظ مع الصورة المصدَّرة، مع أو بدون تحويل تشويه.

القيمة:  true  لتصوير الصورة مع تحويل تشويه؛  false .

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
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


يحصل على قيمة تشير إلى ما إذا كان [ignore after load].

**Returns:**
boolean -  true  إذا كان [ignore after load]; وإلا،  false .
### getIgnoreAlphaChannel() {#getIgnoreAlphaChannel--}
```
public final boolean getIgnoreAlphaChannel()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [ignore alpha channel].

القيمة:  true  إذا كان [ignore alpha channel]؛ وإلا،  false .

**Returns:**
boolean
### getIgnoreTextLayerWidthOnUpdate() {#getIgnoreTextLayerWidthOnUpdate--}
```
public final boolean getIgnoreTextLayerWidthOnUpdate()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان سيتم تجاهل عرض طبقة النص في PSD الثابت عند تنفيذ عملية UpdateText.

القيمة:  true  إذا كان [ignore text layer width]؛ وإلا،  false .

**Returns:**
boolean
### getLoadEffectsResource() {#getLoadEffectsResource--}
```
public final boolean getLoadEffectsResource()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [load effects resource] (بحال الافتراضي لا يتم تحميل المورد). عند ضبط هذا الخيار سيتم تصيير التأثيرات المدعومة فقط إلى الصورة المدمجة النهائية.

القيمة:  true  إذا كان [load effects resource]؛ وإلا،  false .

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


يحصل على معالج حدث التقدم.

القيمة: معالج حدث التقدم.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getReadOnlyMode() {#getReadOnlyMode--}
```
public final boolean getReadOnlyMode()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [use read only mode]. هذا هو وضع القراءة فقط، مدعوم لتوافق مطابق مع Adobe Photoshop. عندما يتم ضبط هذا الخيار، لن يتم حفظ أي تغييرات تُطبق على الطبقات في الصورة النهائية. جميع البيانات تُستخدم من قسم ImageData، لذا فهو مطابق لـ Photoshop. بشكل افتراضي، جميع الصور المحمَّلة ليست متوافقة تمامًا مع Adobe Photoshop.

القيمة:  true  إذا كان [use photoshop compatibility mode]؛ وإلا،  false .

**Returns:**
boolean
### getReadOnlyType() {#getReadOnlyType--}
```
public final int getReadOnlyType()
```


يحصل أو يضبط وضع القراءة فقط المستخدم عند تحميل صورة PSD.

القيمة: أحد قيم ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)).

 *  
 *  
 *  

**Returns:**
int
### getUseDiskForLoadEffectsResource() {#getUseDiskForLoadEffectsResource--}
```
public final boolean getUseDiskForLoadEffectsResource()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [use disk for load effects resource] (بحال الافتراضي يُستخدم القرص لتحميل موارد التأثيرات، لكن يمكن استخدام الذاكرة إذا كان ذلك كافيًا بتعيين هذه القيمة إلى false).

القيمة:  true  إذا كان [use disk for load effects resource]؛ وإلا،  false .

**Returns:**
boolean
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




### setAllowNonChangedLayerRepaint(boolean value) {#setAllowNonChangedLayerRepaint-boolean-}
```
public final void setAllowNonChangedLayerRepaint(boolean value)
```


يحصل أو يضبط ما إذا كان يجب الحفاظ على بكسلات الطبقة الأصلية أثناء التصيير إذا لم يتم تعديل الطبقة.

القيمة:  true  للاحتفاظ بالبكسلات الأصلية للطبقات غير المتغيّرة؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setAllowWarpRepaint(boolean value) {#setAllowWarpRepaint-boolean-}
```
public final void setAllowWarpRepaint(boolean value)
```


يحصل أو يضبط ما إذا كان يجب الحفظ مع الصورة المصدَّرة، مع أو بدون تحويل تشويه.

القيمة:  true  لتصوير الصورة مع تحويل تشويه؛  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان سيتم [ignore after load].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | true  إذا كان [ignore after load]; وإلا،  false . |

### setIgnoreAlphaChannel(boolean value) {#setIgnoreAlphaChannel-boolean-}
```
public final void setIgnoreAlphaChannel(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [ignore alpha channel].

القيمة:  true  إذا كان [ignore alpha channel]؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setIgnoreTextLayerWidthOnUpdate(boolean value) {#setIgnoreTextLayerWidthOnUpdate-boolean-}
```
public final void setIgnoreTextLayerWidthOnUpdate(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان سيتم تجاهل عرض طبقة النص في PSD الثابت عند تنفيذ عملية UpdateText.

القيمة:  true  إذا كان [ignore text layer width]؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setLoadEffectsResource(boolean value) {#setLoadEffectsResource-boolean-}
```
public final void setLoadEffectsResource(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [load effects resource] (بحال الافتراضي لا يتم تحميل المورد). عند ضبط هذا الخيار سيتم تصيير التأثيرات المدعومة فقط إلى الصورة المدمجة النهائية.

القيمة:  true  إذا كان [load effects resource]؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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

### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [use read only mode]. هذا هو وضع القراءة فقط، مدعوم لتوافق مطابق مع Adobe Photoshop. عندما يتم ضبط هذا الخيار، لن يتم حفظ أي تغييرات تُطبق على الطبقات في الصورة النهائية. جميع البيانات تُستخدم من قسم ImageData، لذا فهو مطابق لـ Photoshop. بشكل افتراضي، جميع الصور المحمَّلة ليست متوافقة تمامًا مع Adobe Photoshop.

القيمة:  true  إذا كان [use photoshop compatibility mode]؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setReadOnlyType(int value) {#setReadOnlyType-int-}
```
public final void setReadOnlyType(int value)
```


يحصل أو يضبط وضع القراءة فقط المستخدم عند تحميل صورة PSD.

القيمة: أحد قيم ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)).

 *  
 *  
 *  

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setUseDiskForLoadEffectsResource(boolean value) {#setUseDiskForLoadEffectsResource-boolean-}
```
public final void setUseDiskForLoadEffectsResource(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [use disk for load effects resource] (بحال الافتراضي يُستخدم القرص لتحميل موارد التأثيرات، لكن يمكن استخدام الذاكرة إذا كان ذلك كافيًا بتعيين هذه القيمة إلى false).

القيمة:  true  إذا كان [use disk for load effects resource]؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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

