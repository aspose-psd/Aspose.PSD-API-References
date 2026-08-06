---
title: "LmskResource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "مورد LMsk."
type: docs
weight: 50
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class LmskResource extends LayerResource
```

مورد LMsk.

--------------------

هذا المورد يحتوي على معرف مساحة اللون، الذي يشير إلى نوع مساحة لون محدد، و4 مكونات لونية. اعتمادًا على المعرف، تكون مكونات اللون ذات معاني مختلفة. إذا كان نوع مساحة اللون لا يتطلب أربعة قيم، فإن المكونات الإضافية غير معرفة وتكتب دائمًا كأصفار. مكونات اللون حسب أنواع مساحات اللون: RGB - المكونات الثلاثة الأولى هي الأحمر، الأخضر، والأزرق. HSB - المكونات الثلاثة الأولى هي الصبغة، التشبع، والسطوع. CMYK - المكونات الأربعة هي السيان، الماجنتا، الأصفر، والأسود. Lab - المكونات الثلاثة الأولى هي الإضاءة، a chrominance، و b chrominance. Grayscale - المكون الأول هو قيمة الرمادي، من 0...10000.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [LmskResource()](#LmskResource--) | ينشئ مثيلًا جديدًا من الفئة [LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource) class. |
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
| [create_internalized(byte[] data)](#create-internalized-byte---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorComponent1()](#getColorComponent1--) | يحصل على المكوّن اللوني 1. |
| [getColorComponent2()](#getColorComponent2--) | يحصل على المكوّن اللوني 2. |
| [getColorComponent3()](#getColorComponent3--) | يحصل على المكوّن اللوني 3. |
| [getColorComponent4()](#getColorComponent4--) | يحصل على المكوّن اللوني 4. |
| [getColorSpace()](#getColorSpace--) | يحصل على مساحة اللون. |
| [getFlag()](#getFlag--) | يحصل على العلامة. |
| [getHeader_internalized()](#getHeader-internalized--) | يحصل أو يضبط الرأس. |
| [getKey()](#getKey--) | يحصل على مفتاح مورد الطبقة. |
| [getLength()](#getLength--) | يحصل على طول مورد الطبقة بالبايت. |
| [getOpacity()](#getOpacity--) | يحصل على الشفافية. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | يحصل على طول البادئة. |
| [getPsdVersion()](#getPsdVersion--) | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. |
| [getSignature()](#getSignature--) | يحصل على توقيع مورد الطبقة. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | يحدد ما إذا كان المورد خاصًا بـ PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن خاصًا بـ PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | يحفظ المورد إلى حاوية الدفق المحددة. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | يحفظ رأس المورد المخصص. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | يحفظ توقيع الرأس، المعرف والطول. |
| [setColorComponent1(int value)](#setColorComponent1-int-) | يحصل على المكوّن اللوني 1. |
| [setColorComponent2(int value)](#setColorComponent2-int-) | يحصل على المكوّن اللوني 2. |
| [setColorComponent3(int value)](#setColorComponent3-int-) | يحصل على المكوّن اللوني 3. |
| [setColorComponent4(int value)](#setColorComponent4-int-) | يحصل على المكوّن اللوني 4. |
| [setColorSpace(int value)](#setColorSpace-int-) | يحصل على مساحة اللون. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | يحصل أو يضبط الرأس. |
| [setOpacity(short value)](#setOpacity-short-) | يحصل على الشفافية. |
| [toString()](#toString--) | يرجع سلسلة تمثل هذا الكائن. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LmskResource() {#LmskResource--}
```
public LmskResource()
```


ينشئ مثيلًا جديدًا من الفئة [LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource) class.

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

### create_internalized(byte[] data) {#create-internalized-byte---}
```
public static LmskResource create_internalized(byte[] data)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | byte[] |  |

**Returns:**
[LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource)
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
### getColorComponent1() {#getColorComponent1--}
```
public final int getColorComponent1()
```


يحصل على المكوّن اللوني 1.

القيمة: المكوّن اللوني 1.

**Returns:**
int
### getColorComponent2() {#getColorComponent2--}
```
public final int getColorComponent2()
```


يحصل على المكوّن اللوني 2.

القيمة: المكوّن اللوني 2.

**Returns:**
int
### getColorComponent3() {#getColorComponent3--}
```
public final int getColorComponent3()
```


يحصل على المكوّن اللوني 3.

القيمة: المكوّن اللوني 3.

**Returns:**
int
### getColorComponent4() {#getColorComponent4--}
```
public final int getColorComponent4()
```


يحصل على المكوّن اللوني 4.

القيمة: المكوّن اللوني 4.

**Returns:**
int
### getColorSpace() {#getColorSpace--}
```
public final int getColorSpace()
```


يحصل على مساحة اللون.

القيمة: مساحة اللون.

**Returns:**
int
### getFlag() {#getFlag--}
```
public final byte getFlag()
```


يحصل على العلامة.

القيمة: العلامة.

**Returns:**
byte
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
### getOpacity() {#getOpacity--}
```
public final short getOpacity()
```


يحصل على الشفافية.

القيمة: الشفافية.

**Returns:**
short
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

### setColorComponent1(int value) {#setColorComponent1-int-}
```
public final void setColorComponent1(int value)
```


يحصل على المكوّن اللوني 1.

القيمة: المكوّن اللوني 1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setColorComponent2(int value) {#setColorComponent2-int-}
```
public final void setColorComponent2(int value)
```


يحصل على المكوّن اللوني 2.

القيمة: المكوّن اللوني 2.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setColorComponent3(int value) {#setColorComponent3-int-}
```
public final void setColorComponent3(int value)
```


يحصل على المكوّن اللوني 3.

القيمة: المكوّن اللوني 3.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setColorComponent4(int value) {#setColorComponent4-int-}
```
public final void setColorComponent4(int value)
```


يحصل على المكوّن اللوني 4.

القيمة: المكوّن اللوني 4.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public final void setColorSpace(int value)
```


يحصل على مساحة اللون.

القيمة: مساحة اللون.

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

### setOpacity(short value) {#setOpacity-short-}
```
public final void setOpacity(short value)
```


يحصل على الشفافية.

القيمة: الشفافية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

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

