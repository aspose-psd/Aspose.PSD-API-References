---
title: "WorkingPathResource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "مورد مسار العمل."
type: docs
weight: 43
url: /ar/java/com.aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class WorkingPathResource extends ResourceBlock implements IVectorPathData
```

مورد مسار العمل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WorkingPathResource(byte[] dataBytes)](#WorkingPathResource-byte---) | ينشئ مثيلًا جديدًا من الفئة [WorkingPathResource](../../com.aspose.psd.fileformats.psd.resources/workingpathresource). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | توقيع المورد لـ ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | توقيع مورد Photoshop العادي. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | يحصل على حجم بيانات المورد بالبايت. |
| [getID()](#getID--) | يحصل أو يعيّن المعرف الفريد للمورد. |
| [getMinimalVersion()](#getMinimalVersion--) | يحصل على الحد الأدنى المطلوب لإصدار PSD. |
| [getName()](#getName--) | يحصل على أو يعيّن اسم المورد. |
| [getPaths()](#getPaths--) | يحصل أو يضبط سجلات المسار. |
| [getSignature()](#getSignature--) | يحصل على توقيع المورد. |
| [getSize()](#getSize--) | يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها. |
| [getVersion()](#getVersion--) | يحصل على أو يعيّن الإصدار. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل معطَّلًا. |
| [isInverted()](#isInverted--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل مقلوبًا. |
| [isNotLinked()](#isNotLinked--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل غير مرتبط. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | يحفظ كتلة المورد إلى الدفق المحدد. |
| [setDisabled(boolean value)](#setDisabled-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل معطَّلًا. |
| [setID(short value)](#setID-short-) | يحصل أو يعيّن المعرف الفريد للمورد. |
| [setInverted(boolean value)](#setInverted-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل مقلوبًا. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | يحصل على أو يعيّن معلومات الطبقة والقناع. |
| [setName(String value)](#setName-java.lang.String-) | يحصل على أو يعيّن اسم المورد. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل غير مرتبط. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | يحصل أو يضبط سجلات المسار. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | يحصل على أو يعيّن حالة كتلة المورد. |
| [setVersion(int value)](#setVersion-int-) | يحصل على أو يعيّن الإصدار. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | يُحقق من صحة قيم المورد. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WorkingPathResource(byte[] dataBytes) {#WorkingPathResource-byte---}
```
public WorkingPathResource(byte[] dataBytes)
```


ينشئ مثيلًا جديدًا من الفئة [WorkingPathResource](../../com.aspose.psd.fileformats.psd.resources/workingpathresource).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dataBytes | byte[] | بيانات مسار المتجه. |

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


توقيع المورد لـ ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


توقيع مورد Photoshop العادي.

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
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


يحصل على حجم بيانات المورد بالبايت.

القيمة: حجم بيانات المورد.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


يحصل أو يعيّن المعرف الفريد للمورد.

القيمة: المعرف الفريد للمورد.

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


يحصل على الحد الأدنى المطلوب لإصدار PSD.

القيمة: الحد الأدنى لإصدار PSD.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


يحصل على أو يعيّن اسم المورد. سلسلة باسكال، مملوءة لجعل الحجم زوجيًا (اسم فارغ يتكون من بايتين قيمتهما 0).

القيمة: اسم المورد.

**Returns:**
java.lang.String
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


يحصل أو يضبط سجلات المسار.

القيمة: المسارات.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
### getSignature() {#getSignature--}
```
public final int getSignature()
```


يحصل على توقيع المورد. يجب أن يكون دائمًا '8BIM'.

القيمة: توقيع المورد.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها.

القيمة: حجم كتلة المورد.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final int getVersion()
```


يحصل على أو يعيّن الإصدار.

القيمة: الإصدار.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل معطَّلًا.

القيمة:  true  إذا كان هذا المثيل معطَّلًا؛ وإلا،  false .

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل مقلوبًا.

القيمة:  true  إذا كان هذا المثيل مقلوبًا؛ وإلا،  false .

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل غير مرتبط.

القيمة: true إذا لم يكن هذا الكائن مرتبطًا؛ وإلا false.

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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


يحفظ كتلة المورد إلى الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | الدفق لحفظ كتلة المورد إليه. |

### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل معطَّلًا.

القيمة:  true  إذا كان هذا المثيل معطَّلًا؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


يحصل أو يعيّن المعرف الفريد للمورد.

القيمة: المعرف الفريد للمورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل مقلوبًا.

القيمة:  true  إذا كان هذا المثيل مقلوبًا؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


يحصل على أو يعيّن معلومات الطبقة والقناع.

القيمة: معلومات الطبقة والقناع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


يحصل على أو يعيّن اسم المورد. سلسلة باسكال، مملوءة لجعل الحجم زوجيًا (اسم فارغ يتكون من بايتين قيمتهما 0).

القيمة: اسم المورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل غير مرتبط.

القيمة: true إذا لم يكن هذا الكائن مرتبطًا؛ وإلا false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


يحصل أو يضبط سجلات المسار.

القيمة: المسارات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التوقيع | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


يحصل على أو يعيّن حالة كتلة المورد.

القيمة: حالة كتلة المورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


يحصل على أو يعيّن الإصدار.

القيمة: الإصدار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


يُحقق من صحة قيم المورد.

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

