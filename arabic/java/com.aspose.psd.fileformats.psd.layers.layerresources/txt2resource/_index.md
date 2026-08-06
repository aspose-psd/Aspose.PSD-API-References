---
title: "Txt2Resource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "فئة مورد Txt2"
type: docs
weight: 76
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class Txt2Resource extends LayerResource
```

فئة مورد Txt2
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Txt2Resource()](#Txt2Resource--) | يُنشئ مثيلًا جديدًا من الفئة [Txt2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource). |
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
| [addTextRecord(String text, RectangleF bounds)](#addTextRecord-java.lang.String-com.aspose.psd.RectangleF-) | يضيف سجل النص إلى Resource ويعيد معرف سجل النص. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | يتحقق من ويضبط ما إذا كان المورد خاصًا بـ PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | يحصل أو يضبط البيانات. |
| [getHeader_internalized()](#getHeader-internalized--) | يحصل أو يضبط الرأس. |
| [getKey()](#getKey--) | يحصل على مفتاح مورد الطبقة. |
| [getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree)](#getKeys-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--) | يحصل على ما إذا كان resource مضغوطًا. |
| [getLength()](#getLength--) | يحصل على طول مورد الطبقة بالبايت. |
| [getParsedTxt2Model_internalized()](#getParsedTxt2Model-internalized--) | يحلل بيانات txt2 إلى كائن من فئة Txt2DataRoot. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | يحصل على طول البادئة. |
| [getPsdVersion()](#getPsdVersion--) | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. |
| [getSignature()](#getSignature--) | يحصل على توقيع مورد الطبقة. |
| [getTextData()](#getTextData--) | يحصل على سجل النص من بيانات resource. |
| [getText_internalized()](#getText-internalized--) | يحصل أو يضبط الاسم. |
| [getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree)](#getTxt2FromParsedTree-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--) | يحصل على TXT2 من الشجرة المُحللة. |
| [getTxt2ParsedTree_internalized()](#getTxt2ParsedTree-internalized--) | يحصل على شجرة TXT2 المُحللة. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | يحدد ما إذا كان المورد خاصًا بـ PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن خاصًا بـ PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTextRecord_internalized(int textIndex)](#removeTextRecord-internalized-int-) | إزالة سجل النص من Resource. |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | يحفظ حاوية الدفق المحددة. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | يحفظ رأس المورد المخصص. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | يحفظ توقيع الرأس، المعرف والطول. |
| [setData(byte[] value)](#setData-byte---) | يحصل أو يضبط البيانات. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | يحصل أو يضبط الرأس. |
| [setText_internalized(String value)](#setText-internalized-java.lang.String-) | يحصل أو يضبط الاسم. |
| [toString()](#toString--) | يرجع سلسلة تمثل هذا الكائن. |
| [updateTextData_internalized(int textIndex, String newText, double fontSize, Color color)](#updateTextData-internalized-int-java.lang.String-double-com.aspose.psd.Color-) | يحدّث سجل النص بواسطة فهرس النص مع بيانات نص افتراضية جديدة ونص جديد، وحجم الخط واللون. |
| [updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot)](#updateTxt2DataFromModel-internalized-com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot-) | يحدّث بيانات txt2 من نموذج Txt2DataRoot. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Txt2Resource() {#Txt2Resource--}
```
public Txt2Resource()
```


يُنشئ مثيلًا جديدًا من الفئة [Txt2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource).

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

### addTextRecord(String text, RectangleF bounds) {#addTextRecord-java.lang.String-com.aspose.psd.RectangleF-}
```
public final int addTextRecord(String text, RectangleF bounds)
```


يضيف سجل النص إلى Resource ويعيد معرف سجل النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | نص السجل. |
| bounds | [RectangleF](../../com.aspose.psd/rectanglef) | الحدود. |

**Returns:**
int - يُعيد Id لسجل النص للـ resource
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
### getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree) {#getKeys-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--}
```
public static ITextEngineKeys getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree)
```


يحصل على ما إذا كان resource مضغوطًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| شجرة | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> | الشجرة. |

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.ITextEngineKeys - يُعيد كائنًا بالمفاتيح.
### getLength() {#getLength--}
```
public int getLength()
```


يحصل على طول مورد الطبقة بالبايت.

**Returns:**
int
### getParsedTxt2Model_internalized() {#getParsedTxt2Model-internalized--}
```
public final Txt2DataRoot getParsedTxt2Model_internalized()
```


يحلل بيانات txt2 إلى كائن من فئة Txt2DataRoot.

**Returns:**
com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot - بيانات txt2 ككائن من فئة Txt2DataRoot.
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
### getTextData() {#getTextData--}
```
public final String[] getTextData()
```


يحصل على سجل النص من بيانات resource.

**Returns:**
java.lang.String[] - مصفوفة من سجلات النص
### getText_internalized() {#getText-internalized--}
```
public final String getText_internalized()
```


يحصل أو يضبط الاسم.

القيمة: الاسم.

**Returns:**
java.lang.String
### getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree) {#getTxt2FromParsedTree-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--}
```
public final String getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree)
```


يحصل على TXT2 من الشجرة المُحللة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| شجرة | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> | شجرة البيانات. |

**Returns:**
java.lang.String - بيانات Txt2.
### getTxt2ParsedTree_internalized() {#getTxt2ParsedTree-internalized--}
```
public final System.Collections.Generic.Dictionary<String,Object> getTxt2ParsedTree_internalized()
```


يحصل على شجرة TXT2 المُحللة.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> - الشجرة المُحللة
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




### removeTextRecord_internalized(int textIndex) {#removeTextRecord-internalized-int-}
```
public final void removeTextRecord_internalized(int textIndex)
```


إزالة سجل النص من Resource.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| textIndex | int | المؤشر لسجل النص لإزالته. |

### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


يحفظ حاوية الدفق المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |
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

### setData(byte[] value) {#setData-byte---}
```
public final void setData(byte[] value)
```


يحصل أو يضبط البيانات.

القيمة: البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

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

### setText_internalized(String value) {#setText-internalized-java.lang.String-}
```
public final void setText_internalized(String value)
```


يحصل أو يضبط الاسم.

القيمة: الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


يرجع سلسلة تمثل هذا الكائن.

**Returns:**
java.lang.String - سلسلة تمثل هذه الحالة.
### updateTextData_internalized(int textIndex, String newText, double fontSize, Color color) {#updateTextData-internalized-int-java.lang.String-double-com.aspose.psd.Color-}
```
public final void updateTextData_internalized(int textIndex, String newText, double fontSize, Color color)
```


يحدّث سجل النص بواسطة فهرس النص مع بيانات نص افتراضية جديدة ونص جديد، وحجم الخط واللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| textIndex | int | المؤشر لسجل النص في بيانات مورد txt2. |
| newText | java.lang.String | النص الجديد. |
| fontSize | double | حجم الخط الجديد. |
| color | [Color](../../com.aspose.psd/color) | لون النص الجديد. |

### updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot) {#updateTxt2DataFromModel-internalized-com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot-}
```
public final void updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot)
```


يحدّث بيانات txt2 من نموذج Txt2DataRoot.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| txt2DataRoot | com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot | نموذج بيانات txt2. |

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

