---
title: "PattResource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "الفئة PattResource."
type: docs
weight: 66
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class PattResource extends LayerResource
```

الفئة PattResource. مورد يحتوي على بيانات النمط
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PattResource()](#PattResource--) | يُنشئ مثيلًا جديدًا من الفئة [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource). |
| [PattResource(int key, PattResourceData[] patterns)](#PattResource-int-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---) | يُنشئ مثيلًا جديدًا من الفئة [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | إصدار رأس PSB |
| [PsbResourceSignature](#PsbResourceSignature) | توقيع المورد الخاص بـ PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | إصدار رأس PSD |
| [ResourceSignature](#ResourceSignature) | توقيع المورد المشترك. |
| [TypeToolKey](#TypeToolKey) | مفتاح معلومات أداة النوع 'Patt' للبتات 8. |
| [TypeToolKey2](#TypeToolKey2) | مفتاح معلومات أداة النوع 'Pat2' للبتات 16. |
| [TypeToolKey3](#TypeToolKey3) | مفتاح معلومات أداة النوع 'Pat3' للبتات 32. |
| [ventureLicense_internalized](#ventureLicense-internalized) | رخصة المشروع. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addNewPattResourceData_internalized(PattResource resource)](#addNewPattResourceData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | يُحدّث مورد Patt بالبيانات الافتراضية. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | يتحقق من ويضبط ما إذا كان المورد خاصًا بـ PSB. |
| [createDefaultNotEmptyResource_internalized(int bitDepth)](#createDefaultNotEmptyResource-internalized-int-) | ينشئ المورد الافتراضي غير الفارغ. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | يحصل أو يضبط الرأس. |
| [getKey()](#getKey--) | يحصل على مفتاح مورد الطبقة. |
| [getLength()](#getLength--) | يحصل على طول مورد الطبقة بالبايت. |
| [getPatterns()](#getPatterns--) | يحصل أو يعيّن بيانات الأنماط؛ |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | يحصل على طول البادئة. |
| [getPsdVersion()](#getPsdVersion--) | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. |
| [getSignature()](#getSignature--) | يحصل على توقيع مورد الطبقة. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | يحدد ما إذا كان المورد خاصًا بـ PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن خاصًا بـ PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | يحفظ بيانات كتلة المورد. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | يحفظ رأس المورد المخصص. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | يحفظ توقيع الرأس، المعرف والطول. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | يحصل أو يضبط الرأس. |
| [setPatterns(PattResourceData[] value)](#setPatterns-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---) | يحصل أو يعيّن بيانات الأنماط؛ |
| [toString()](#toString--) | يرجع سلسلة تمثل هذا الكائن. |
| [updateOrAddPattern_internalized(IPatternFillSettings patternSettings)](#updateOrAddPattern-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings-) | يبحث عن عنصر بيانات النمط ويُحدّثه بالجديد، وإلا يضيف جديدًا إلى نهاية المصفوفة. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResource() {#PattResource--}
```
public PattResource()
```


يُنشئ مثيلًا جديدًا من الفئة [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource).

### PattResource(int key, PattResourceData[] patterns) {#PattResource-int-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---}
```
public PattResource(int key, PattResourceData[] patterns)
```


يُنشئ مثيلًا جديدًا من الفئة [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | int | مفتاح نوع المورد. |
| patterns | [PattResourceData\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | بيانات الأنماط. |

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


مفتاح معلومات أداة النوع 'Patt' للبتات 8.

### TypeToolKey2 {#TypeToolKey2}
```
public static final int TypeToolKey2
```


مفتاح معلومات أداة النوع 'Pat2' للبتات 16.

### TypeToolKey3 {#TypeToolKey3}
```
public static final int TypeToolKey3
```


مفتاح معلومات أداة النوع 'Pat3' للبتات 32.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


رخصة المشروع.

### addNewPattResourceData_internalized(PattResource resource) {#addNewPattResourceData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public static void addNewPattResourceData_internalized(PattResource resource)
```


يُحدّث مورد Patt بالبيانات الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) | المورد. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


يتحقق من ويضبط ما إذا كان المورد خاصًا بـ PSB. بعض الموارد غير معروفة حاليًا، لكن لدينا قائمة كاملة بالموارد الخاصة بـ PSB التي تغير سلوكها عند الحفظ. لذلك نحتاج إلى التحقق من ذلك في UnknownResource على الأقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | int | المفتاح. |

### createDefaultNotEmptyResource_internalized(int bitDepth) {#createDefaultNotEmptyResource-internalized-int-}
```
public static PattResource createDefaultNotEmptyResource_internalized(int bitDepth)
```


ينشئ المورد الافتراضي غير الفارغ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitDepth | int |  |

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - Created [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getPatterns() {#getPatterns--}
```
public final PattResourceData[] getPatterns()
```


يحصل أو يعيّن بيانات الأنماط؛

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData[]
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
### getSignature() {#getSignature--}
```
public int getSignature()
```


يحصل على توقيع مورد الطبقة.

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


يحفظ بيانات كتلة المورد.

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

### setPatterns(PattResourceData[] value) {#setPatterns-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---}
```
public final void setPatterns(PattResourceData[] value)
```


يحصل أو يعيّن بيانات الأنماط؛

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PattResourceData\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) |  |

### toString() {#toString--}
```
public String toString()
```


يرجع سلسلة تمثل هذا الكائن.

**Returns:**
java.lang.String - سلسلة تمثل هذه الحالة.
### updateOrAddPattern_internalized(IPatternFillSettings patternSettings) {#updateOrAddPattern-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings-}
```
public final void updateOrAddPattern_internalized(IPatternFillSettings patternSettings)
```


يبحث عن عنصر بيانات النمط ويُحدّثه بالجديد، وإلا يضيف جديدًا إلى نهاية المصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| patternSettings | [IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings) | كائن إعدادات الأنماط لتحديث عنصر النمط. |

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

