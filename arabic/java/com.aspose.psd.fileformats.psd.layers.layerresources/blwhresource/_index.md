---
title: "BlwhResource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "الفئة BlwhResource هي مورد لطبقة تعديل الأسود والأبيض."
type: docs
weight: 15
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlwhResource extends AdjustmentLayerResource
```

الفئة BlwhResource هي مورد لطبقة تعديل الأسود والأبيض.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [BlwhResource()](#BlwhResource--) | ينشئ مثيلاً جديدًا للفئة [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | إصدار رأس PSB |
| [PsbResourceSignature](#PsbResourceSignature) | توقيع المورد الخاص بـ PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | إصدار رأس PSD |
| [ResourceSignature](#ResourceSignature) | توقيع المورد المشترك. |
| [TypeToolKey](#TypeToolKey) | مفتاح معلومات أداة النوع. |
| [ventureLicense_internalized](#ventureLicense-internalized) | رخصة المشروع. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | يتحقق من ويضبط ما إذا كان المورد خاصًا بـ PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlackAndWhitePresetFileName()](#getBlackAndWhitePresetFileName--) | يحصل أو يضبط اسم ملف الإعداد المسبق للونين الأسود والأبيض. |
| [getBlues()](#getBlues--) | يحصل أو يضبط قيمة اللون الأزرق. |
| [getBwPresetKind()](#getBwPresetKind--) | يحصل أو يضبط قيمة نوع الإعداد المسبق للونين الأسود والأبيض. |
| [getClass()](#getClass--) |  |
| [getCyans()](#getCyans--) | يحصل أو يضبط قيمة اللون السيان. |
| [getData()](#getData--) | يحصل أو يضبط البيانات. |
| [getGreens()](#getGreens--) | يحصل أو يعيّن قيمة الأخضر. |
| [getHeader_internalized()](#getHeader-internalized--) | يحصل أو يضبط الرأس. |
| [getKey()](#getKey--) | يحصل على مفتاح مورد الطبقة. |
| [getLength()](#getLength--) | يحصل على طول مورد الطبقة بالبايت. |
| [getMagentas()](#getMagentas--) | يحصل أو يعيّن قيمة الماجنتا. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | يحصل على طول البادئة. |
| [getPsdVersion()](#getPsdVersion--) | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. |
| [getReds()](#getReds--) | يحصل أو يعيّن قيمة الأحمر. |
| [getSignature()](#getSignature--) | يحصل على توقيع مورد الطبقة. |
| [getTintColor()](#getTintColor--) | يحصل على لون الصبغة ARGB. |
| [getTintColorBlue_internalized()](#getTintColorBlue-internalized--) | يحصل أو يعيّن القيمة المزدوجة للون الصبغ الأزرق. |
| [getTintColorGreen_internalized()](#getTintColorGreen-internalized--) | يحصل أو يعيّن القيمة المزدوجة للون الصبغ الأخضر. |
| [getTintColorRed_internalized()](#getTintColorRed-internalized--) | يحصل أو يعيّن القيمة المزدوجة للون الصبغ الأحمر. |
| [getUseTint()](#getUseTint--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [tint color] مستخدمًا. |
| [getYellows()](#getYellows--) | يحصل أو يعيّن قيمة الأصفر. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | يحدد ما إذا كان المورد خاصًا بـ PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن خاصًا بـ PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | يحفظ المورد إلى حاوية الدفق المحددة. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | يحفظ رأس المورد المخصص. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | يحفظ توقيع الرأس، المعرف والطول. |
| [setBlackAndWhitePresetFileName(String value)](#setBlackAndWhitePresetFileName-java.lang.String-) | يحصل أو يضبط اسم ملف الإعداد المسبق للونين الأسود والأبيض. |
| [setBlues(int value)](#setBlues-int-) | يحصل أو يضبط قيمة اللون الأزرق. |
| [setBwPresetKind(int value)](#setBwPresetKind-int-) | يحصل أو يضبط قيمة نوع الإعداد المسبق للونين الأسود والأبيض. |
| [setCyans(int value)](#setCyans-int-) | يحصل أو يضبط قيمة اللون السيان. |
| [setGreens(int value)](#setGreens-int-) | يحصل أو يعيّن قيمة الأخضر. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | يحصل أو يضبط الرأس. |
| [setMagentas(int value)](#setMagentas-int-) | يحصل أو يعيّن قيمة الماجنتا. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | يعيّن قيمة الخاصية وفقًا للهيكل النوعي. |
| [setReds(int value)](#setReds-int-) | يحصل أو يعيّن قيمة الأحمر. |
| [setTintColor(int value)](#setTintColor-int-) | يعيّن لون الصبغة. |
| [setTintColorBlue_internalized(double value)](#setTintColorBlue-internalized-double-) | يحصل أو يعيّن القيمة المزدوجة للون الصبغ الأزرق. |
| [setTintColorGreen_internalized(double value)](#setTintColorGreen-internalized-double-) | يحصل أو يعيّن القيمة المزدوجة للون الصبغ الأخضر. |
| [setTintColorRed_internalized(double value)](#setTintColorRed-internalized-double-) | يحصل أو يعيّن القيمة المزدوجة للون الصبغ الأحمر. |
| [setUseTint(boolean value)](#setUseTint-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [tint color] مستخدمًا. |
| [setYellows(int value)](#setYellows-int-) | يحصل أو يعيّن قيمة الأصفر. |
| [toString()](#toString--) | يرجع سلسلة تمثل هذا الكائن. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlwhResource() {#BlwhResource--}
```
public BlwhResource()
```


ينشئ مثيلاً جديدًا للفئة [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource).

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


إصدار رأس PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


توقيع المورد الخاص بـ PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


إصدار رأس PSD

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


توقيع المورد المشترك.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


مفتاح معلومات أداة النوع.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


رخصة المشروع.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


يتحقق من ويضبط ما إذا كان المورد خاصًا بـ PSB. بعض الموارد غير معروفة حاليًا، لكن لدينا قائمة كاملة بالموارد الخاصة بـ PSB التي تغير سلوكها عند الحفظ. لذلك نحتاج إلى التحقق من ذلك في UnknownResource على الأقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | int | المفتاح. |

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
### getBlackAndWhitePresetFileName() {#getBlackAndWhitePresetFileName--}
```
public final String getBlackAndWhitePresetFileName()
```


يحصل أو يضبط اسم ملف الإعداد المسبق للونين الأسود والأبيض.

القيمة: اسم ملف الإعداد المسبق بالأبيض والأسود.

**Returns:**
java.lang.String
### getBlues() {#getBlues--}
```
public final int getBlues()
```


يحصل أو يضبط قيمة اللون الأزرق.

القيمة: قيمة اللون الأزرق.

**Returns:**
int
### getBwPresetKind() {#getBwPresetKind--}
```
public final int getBwPresetKind()
```


يحصل أو يضبط قيمة نوع الإعداد المسبق للونين الأسود والأبيض.

القيمة: قيمة نوع الإعداد المسبق بالأبيض والأسود.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCyans() {#getCyans--}
```
public final int getCyans()
```


يحصل أو يضبط قيمة اللون السيان.

القيمة: قيمة اللون السماوي.

**Returns:**
int
### getData() {#getData--}
```
public final byte[] getData()
```


يحصل أو يضبط البيانات.

القيمة: البيانات.

**Returns:**
byte[]
### getGreens() {#getGreens--}
```
public final int getGreens()
```


يحصل أو يعيّن قيمة الأخضر.

القيمة: قيمة اللون الأخضر.

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


يحصل أو يضبط الرأس.

القيمة: الترويسة.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public final int getKey()
```


يحصل على مفتاح مورد الطبقة.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


يحصل على طول مورد الطبقة بالبايت.

**Returns:**
int
### getMagentas() {#getMagentas--}
```
public final int getMagentas()
```


يحصل أو يعيّن قيمة الماجنتا.

القيمة: قيمة اللون الماجنتا.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


يحصل على طول البادئة. القيمة الافتراضية هي 12 لموارد 8BIM و 16 لموارد 8B64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| psdVersion | int | إصدار PSD. |

**Returns:**
int - طول البادئة.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود.

**Returns:**
int
### getReds() {#getReds--}
```
public final int getReds()
```


يحصل أو يعيّن قيمة الأحمر.

القيمة: قيمة اللون الأحمر.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


يحصل على توقيع مورد الطبقة.

**Returns:**
int
### getTintColor() {#getTintColor--}
```
public int getTintColor()
```


يحصل على لون الصبغة ARGB.

**Returns:**
int - لون الصبغة ARGB.
### getTintColorBlue_internalized() {#getTintColorBlue-internalized--}
```
public final double getTintColorBlue_internalized()
```


يحصل أو يعيّن القيمة المزدوجة للون الصبغ الأزرق.

القيمة: القيمة المزدوجة للون الصبغ الأزرق.

**Returns:**
double
### getTintColorGreen_internalized() {#getTintColorGreen-internalized--}
```
public final double getTintColorGreen_internalized()
```


يحصل أو يعيّن القيمة المزدوجة للون الصبغ الأخضر.

القيمة: القيمة المزدوجة للون الصبغ الأخضر.

**Returns:**
double
### getTintColorRed_internalized() {#getTintColorRed-internalized--}
```
public final double getTintColorRed_internalized()
```


يحصل أو يعيّن القيمة المزدوجة للون الصبغ الأحمر.

القيمة: القيمة المزدوجة للون الصبغ الأحمر.

**Returns:**
double
### getUseTint() {#getUseTint--}
```
public final boolean getUseTint()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [tint color] مستخدمًا.

القيمة:  true  إذا تم استخدام [tint color]; وإلا،  false .

**Returns:**
boolean
### getYellows() {#getYellows--}
```
public final int getYellows()
```


يحصل أو يعيّن قيمة الأصفر.

القيمة: قيمة اللون الأصفر.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


يحدد ما إذا كان المورد خاصًا بـ PSB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | int | مفتاح المورد. |

**Returns:**
boolean -  true  إذا كان المورد خاصًا بـ PSD؛ وإلا،  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن خاصًا بـ PSB.

القيمة:  true  إذا كان هذا الكائن خاصًا بـ PSB؛ وإلا،  false .

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


يحفظ المورد إلى حاوية الدفق المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق التي سيتم الحفظ إليها. |
| psdVersion | int | إصدار PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


يحفظ رأس المورد المخصص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |
| التوقيع | int | التوقيع. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


يحفظ توقيع الرأس، المعرف والطول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |
| التوقيع | int | التوقيع. |
| isLengthLong | boolean | إذا تم ضبطه على  true  يكون الطول طويلًا. |

### setBlackAndWhitePresetFileName(String value) {#setBlackAndWhitePresetFileName-java.lang.String-}
```
public final void setBlackAndWhitePresetFileName(String value)
```


يحصل أو يضبط اسم ملف الإعداد المسبق للونين الأسود والأبيض.

القيمة: اسم ملف الإعداد المسبق بالأبيض والأسود.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setBlues(int value) {#setBlues-int-}
```
public final void setBlues(int value)
```


يحصل أو يضبط قيمة اللون الأزرق.

القيمة: قيمة اللون الأزرق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setBwPresetKind(int value) {#setBwPresetKind-int-}
```
public final void setBwPresetKind(int value)
```


يحصل أو يضبط قيمة نوع الإعداد المسبق للونين الأسود والأبيض.

القيمة: قيمة نوع الإعداد المسبق بالأبيض والأسود.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setCyans(int value) {#setCyans-int-}
```
public final void setCyans(int value)
```


يحصل أو يضبط قيمة اللون السيان.

القيمة: قيمة اللون السماوي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setGreens(int value) {#setGreens-int-}
```
public final void setGreens(int value)
```


يحصل أو يعيّن قيمة الأخضر.

القيمة: قيمة اللون الأخضر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

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

### setMagentas(int value) {#setMagentas-int-}
```
public final void setMagentas(int value)
```


يحصل أو يعيّن قيمة الماجنتا.

القيمة: قيمة اللون الماجنتا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


يعيّن قيمة الخاصية وفقًا للهيكل النوعي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | البنية. |

### setReds(int value) {#setReds-int-}
```
public final void setReds(int value)
```


يحصل أو يعيّن قيمة الأحمر.

القيمة: قيمة اللون الأحمر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setTintColor(int value) {#setTintColor-int-}
```
public void setTintColor(int value)
```


يعيّن لون الصبغة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة. |

### setTintColorBlue_internalized(double value) {#setTintColorBlue-internalized-double-}
```
public final void setTintColorBlue_internalized(double value)
```


يحصل أو يعيّن القيمة المزدوجة للون الصبغ الأزرق.

القيمة: القيمة المزدوجة للون الصبغ الأزرق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setTintColorGreen_internalized(double value) {#setTintColorGreen-internalized-double-}
```
public final void setTintColorGreen_internalized(double value)
```


يحصل أو يعيّن القيمة المزدوجة للون الصبغ الأخضر.

القيمة: القيمة المزدوجة للون الصبغ الأخضر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setTintColorRed_internalized(double value) {#setTintColorRed-internalized-double-}
```
public final void setTintColorRed_internalized(double value)
```


يحصل أو يعيّن القيمة المزدوجة للون الصبغ الأحمر.

القيمة: القيمة المزدوجة للون الصبغ الأحمر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setUseTint(boolean value) {#setUseTint-boolean-}
```
public final void setUseTint(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [tint color] مستخدمًا.

القيمة:  true  إذا تم استخدام [tint color]; وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setYellows(int value) {#setYellows-int-}
```
public final void setYellows(int value)
```


يحصل أو يعيّن قيمة الأصفر.

القيمة: قيمة اللون الأصفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### toString() {#toString--}
```
public String toString()
```


يرجع سلسلة تمثل هذا الكائن.

**Returns:**
java.lang.String - سلسلة تمثل هذه الحالة.
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

