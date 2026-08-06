---
title: "PhflResourceVersion3"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "الفئة PhflResource."
type: docs
weight: 70
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.PhflResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresource)
```
public class PhflResourceVersion3 extends PhflResource
```

الفئة PhflResource. مورد طبقة تعديل التعرض 2 الإصدار ( = 3 ) أو ( = 2 ) 12 4 بايت لكل لون XYZ (فقط في الإصدار 3) 10 2 بايت مساحة اللون تليها 4 \* 2 بايت مكوّن اللون (فقط في الإصدار 2) 4 الكثافة 1 الحفاظ على الإضاءة
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PhflResourceVersion3()](#PhflResourceVersion3--) | ينشئ مثيلًا جديدًا من الفئة [PhflResourceVersion3](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3). |
| [PhflResourceVersion3(byte[] data)](#PhflResourceVersion3-byte---) | ينشئ مثيلًا جديدًا من الفئة [PhflResourceVersion3](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3). |
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
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | يحصل على مساحة اللون. |
| [getColorX()](#getColorX--) | يحصل أو يضبط اللون X. |
| [getColorY()](#getColorY--) | يحصل أو يضبط اللون Y. |
| [getColorZ()](#getColorZ--) | يحصل أو يضبط اللون Z. |
| [getData()](#getData--) | يحصل أو يضبط البيانات. |
| [getDensity()](#getDensity--) | يحصل أو يعيّن الكثافة. |
| [getHeader_internalized()](#getHeader-internalized--) | يحصل أو يضبط الرأس. |
| [getKey()](#getKey--) | يحصل على مفتاح مورد الطبقة. |
| [getLength()](#getLength--) | يحصل على طول مورد الطبقة بالبايت. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | يحصل على طول البادئة. |
| [getPreserveLuminosity()](#getPreserveLuminosity--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [preserve luminosity]. |
| [getPsdVersion()](#getPsdVersion--) | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. |
| [getRgbColor()](#getRgbColor--) | يحصل على اللون. |
| [getSignature()](#getSignature--) | يحصل على توقيع مورد الطبقة. |
| [getVersion()](#getVersion--) | يحصل على الإصدار. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | يحدد ما إذا كان المورد خاصًا بـ PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن خاصًا بـ PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | يحفظ المورد إلى حاوية الدفق المحددة. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | يحفظ رأس المورد المخصص. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | يحفظ توقيع الرأس، المعرف والطول. |
| [setColorSpace(short value)](#setColorSpace-short-) | يحصل على مساحة اللون. |
| [setColorX(float value)](#setColorX-float-) | يحصل أو يضبط اللون X. |
| [setColorY(float value)](#setColorY-float-) | يحصل أو يضبط اللون Y. |
| [setColorZ(float value)](#setColorZ-float-) | يحصل أو يضبط اللون Z. |
| [setDensity(int value)](#setDensity-int-) | يحصل أو يعيّن الكثافة. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | يحصل أو يضبط الرأس. |
| [setPreserveLuminosity(boolean value)](#setPreserveLuminosity-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [preserve luminosity]. |
| [setRgbColor(Color color)](#setRgbColor-com.aspose.psd.Color-) | يعيّن لون RGB. |
| [setVersion(short value)](#setVersion-short-) | يحصل على الإصدار. |
| [toString()](#toString--) | يرجع سلسلة تمثل هذا الكائن. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhflResourceVersion3() {#PhflResourceVersion3--}
```
public PhflResourceVersion3()
```


ينشئ مثيلًا جديدًا من الفئة [PhflResourceVersion3](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3).

### PhflResourceVersion3(byte[] data) {#PhflResourceVersion3-byte---}
```
public PhflResourceVersion3(byte[] data)
```


ينشئ مثيلًا جديدًا من الفئة [PhflResourceVersion3](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | byte[] | بيانات المورد. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorSpace() {#getColorSpace--}
```
public final short getColorSpace()
```


يحصل على مساحة اللون.

القيمة: مساحة اللون.

**Returns:**
short
### getColorX() {#getColorX--}
```
public final float getColorX()
```


يحصل أو يضبط اللون X.

القيمة: اللون X.

**Returns:**
float
### getColorY() {#getColorY--}
```
public final float getColorY()
```


يحصل أو يضبط اللون Y.

القيمة: اللون Y.

**Returns:**
float
### getColorZ() {#getColorZ--}
```
public final float getColorZ()
```


يحصل أو يضبط اللون Z.

القيمة: اللون Z.

**Returns:**
float
### getData() {#getData--}
```
public final byte[] getData()
```


يحصل أو يضبط البيانات.

القيمة: البيانات.

**Returns:**
byte[]
### getDensity() {#getDensity--}
```
public final int getDensity()
```


يحصل أو يعيّن الكثافة.

القيمة: الكثافة.

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
### getPreserveLuminosity() {#getPreserveLuminosity--}
```
public final boolean getPreserveLuminosity()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [preserve luminosity].

القيمة:  true  إذا كان [preserve luminosity]; وإلا،  false .

**Returns:**
boolean
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود.

**Returns:**
int
### getRgbColor() {#getRgbColor--}
```
public Color getRgbColor()
```


يحصل على اللون.

**Returns:**
[Color](../../com.aspose.psd/color) - The RGB color
### getSignature() {#getSignature--}
```
public int getSignature()
```


يحصل على توقيع مورد الطبقة.

**Returns:**
int
### getVersion() {#getVersion--}
```
public short getVersion()
```


يحصل على الإصدار. الافتراضي هو 2 أو 3

**Returns:**
short
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

### setColorSpace(short value) {#setColorSpace-short-}
```
public void setColorSpace(short value)
```


يحصل على مساحة اللون.

القيمة: مساحة اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setColorX(float value) {#setColorX-float-}
```
public final void setColorX(float value)
```


يحصل أو يضبط اللون X.

القيمة: اللون X.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setColorY(float value) {#setColorY-float-}
```
public final void setColorY(float value)
```


يحصل أو يضبط اللون Y.

القيمة: اللون Y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setColorZ(float value) {#setColorZ-float-}
```
public final void setColorZ(float value)
```


يحصل أو يضبط اللون Z.

القيمة: اللون Z.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setDensity(int value) {#setDensity-int-}
```
public final void setDensity(int value)
```


يحصل أو يعيّن الكثافة.

القيمة: الكثافة.

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

### setPreserveLuminosity(boolean value) {#setPreserveLuminosity-boolean-}
```
public final void setPreserveLuminosity(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [preserve luminosity].

القيمة:  true  إذا كان [preserve luminosity]; وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setRgbColor(Color color) {#setRgbColor-com.aspose.psd.Color-}
```
public void setRgbColor(Color color)
```


يعيّن لون RGB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | اللون. |

### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


يحصل على الإصدار. الافتراضي هو 2 أو 3

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

