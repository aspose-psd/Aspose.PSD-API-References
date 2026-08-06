---
title: "CurvResource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "الفئة CurvResource."
type: docs
weight: 23
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class CurvResource extends AdjustmentLayerResource
```

الفئة CurvResource. مورد طبقة تعديل المنحنيات 1 بايت - 0 إذا تم استخدام المنحنيات، 1 إذا تم استخدام بكسلات على الخريطة إذا 0 ثم: 2 بايت - عدد قصير. القيمة الافتراضية 1 4 بايت - عدد صحيح. يُستخدم البايت الأخير فقط بت. البت الأول للقناة الواحدة، البت الرابع للقنوات الأربعة على سبيل المثال 2 بايت - عدد نقاط قصيرة 4 بايت * عدد النقاط - نقاط المنحنى 2 عدد قصير: الموضع الأول، الارتفاع الثاني 4 بايت - كلمة "Crv " 2 بايت - عدد قصير القيمة الافتراضية 4 للمنحنيات 4 بايت - عدد صحيح. القيمة الافتراضية 1 4 بايت - عدد النقاط 4 بايت * عدد النقاط - نقاط المنحنى 2 عدد قصير: الموضع الأول، الارتفاع الثاني 0-4 بايت - يجب طيها لأربعة إذا 1 ثم: 2 بايت - عدد قصير. القيمة الافتراضية 1 4 بايت - عدد صحيح. يُستخدم البايت الأخير فقط. قناة واحدة في بت واحد. البت الأول للقناة الواحدة، البت الرابع للقنوات الأربعة على سبيل المثال 256 * عدد القنوات المتغيرة - قيم مرتبة للقناة في النطاق 0 - 255 4 بايت - كلمة "Crv " 2 بايت - عدد قصير. القيمة الافتراضية 3 للبكسلات على الخريطة 4 بايت - عدد صحيح عدد القنوات (2 + 256) بايت - عدد قصير 2 لفهرس القناة، 256 هي القيم المرتبة للقناة في النطاق 0 - 255
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CurvResource(int maxChannelCount)](#CurvResource-int-) | ينشئ مثيلاً جديداً للفئة [CurvResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvresource). |
| [CurvResource(byte[] bytes)](#CurvResource-byte---) | ينشئ مثيلاً جديداً للفئة [CurvResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvresource). |
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
| [getActiveManager()](#getActiveManager--) | يحصل على المدير النشط. |
| [getChannelData(int channelIndex)](#getChannelData-int-) | يحصل على بيانات القناة. |
| [getClass()](#getClass--) |  |
| [getCurveManager()](#getCurveManager--) | يحصل على مدير المنحنى. |
| [getData()](#getData--) | يحصل أو يضبط البيانات. |
| [getHeader_internalized()](#getHeader-internalized--) | يحصل أو يضبط الرأس. |
| [getKey()](#getKey--) | يحصل على مفتاح مورد الطبقة. |
| [getLength()](#getLength--) | يحصل على طول مورد الطبقة بالبايت. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | يحصل على طول البادئة. |
| [getPsdVersion()](#getPsdVersion--) | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. |
| [getSignature()](#getSignature--) | يحصل على توقيع مورد الطبقة. |
| [hashCode()](#hashCode--) |  |
| [isDataStoredDiscretely()](#isDataStoredDiscretely--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل يخزن البيانات بشكل منفصل. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | يحدد ما إذا كان المورد خاصًا بـ PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن خاصًا بـ PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | يحفظ المورد إلى حاوية الدفق المحددة. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | يحفظ رأس المورد المخصص. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | يحفظ توقيع الرأس، المعرف والطول. |
| [setDataStoredDiscretely(boolean value)](#setDataStoredDiscretely-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل يخزن البيانات بشكل منفصل. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | يحصل أو يضبط الرأس. |
| [toString()](#toString--) | يرجع سلسلة تمثل هذا الكائن. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvResource(int maxChannelCount) {#CurvResource-int-}
```
public CurvResource(int maxChannelCount)
```


ينشئ مثيلاً جديداً للفئة [CurvResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvresource).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| maxChannelCount | int | العدد الأقصى للقنوات. |

### CurvResource(byte[] bytes) {#CurvResource-byte---}
```
public CurvResource(byte[] bytes)
```


ينشئ مثيلاً جديداً للفئة [CurvResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvresource).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بايتات | byte[] | البايتات. |

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
### getActiveManager() {#getActiveManager--}
```
public final CurvesManager getActiveManager()
```


يحصل على المدير النشط.

**Returns:**
[CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) - Active manager
### getChannelData(int channelIndex) {#getChannelData-int-}
```
public final byte[] getChannelData(int channelIndex)
```


يحصل على بيانات القناة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| channelIndex | int | فهرس القناة. |

**Returns:**
byte[] - بيانات القناة
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurveManager() {#getCurveManager--}
```
public final CurvesManager getCurveManager()
```


يحصل على مدير المنحنى.

**Returns:**
[CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) - [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) or [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager)
### getData() {#getData--}
```
public final byte[] getData()
```


يحصل أو يضبط البيانات.

القيمة: البيانات.

**Returns:**
byte[]
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
### isDataStoredDiscretely() {#isDataStoredDiscretely--}
```
public final boolean isDataStoredDiscretely()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل يخزن البيانات بشكل منفصل.

القيمة:  true  إذا كان هذا المثيل يخزن البيانات بشكل منفصل؛ وإلا،  false .

**Returns:**
boolean
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

### setDataStoredDiscretely(boolean value) {#setDataStoredDiscretely-boolean-}
```
public final void setDataStoredDiscretely(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل يخزن البيانات بشكل منفصل.

القيمة:  true  إذا كان هذا المثيل يخزن البيانات بشكل منفصل؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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

