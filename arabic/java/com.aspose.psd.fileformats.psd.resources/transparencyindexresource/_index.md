---
title: "TransparencyIndexResource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "كتلة مورد فهرس الشفافية."
type: docs
weight: 37
url: /ar/java/com.aspose.psd.fileformats.psd.resources/transparencyindexresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class TransparencyIndexResource extends ResourceBlock
```

كتلة مورد فهرس الشفافية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TransparencyIndexResource()](#TransparencyIndexResource--) | ينشئ مثيلًا جديدًا من الفئة [TransparencyIndexResource](../../com.aspose.psd.fileformats.psd.resources/transparencyindexresource). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [RequiredVersion_internalized](#RequiredVersion-internalized) | إصدار PSD المطلوب. |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | توقيع المورد لـ ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | توقيع مورد Photoshop العادي. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | يحصل على حجم بيانات المورد بالبايت. |
| [getID()](#getID--) | يحصل أو يعيّن المعرف الفريد للمورد. |
| [getMinimalVersion()](#getMinimalVersion--) | يحصل على الحد الأدنى لإصدار PSD المطلوب. |
| [getName()](#getName--) | يحصل على أو يعيّن اسم المورد. |
| [getSignature()](#getSignature--) | يحصل على توقيع المورد. |
| [getSize()](#getSize--) | يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها. |
| [getTransparencyIndex()](#getTransparencyIndex--) | يحصل أو يضبط فهرس لون الشفافية. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | يحفظ كتلة المورد إلى الدفق المحدد. |
| [setID(short value)](#setID-short-) | يحصل أو يعيّن المعرف الفريد للمورد. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | يحصل على أو يعيّن معلومات الطبقة والقناع. |
| [setName(String value)](#setName-java.lang.String-) | يحصل على أو يعيّن اسم المورد. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | يحصل على أو يعيّن حالة كتلة المورد. |
| [setTransparencyIndex(short value)](#setTransparencyIndex-short-) | يحصل أو يضبط فهرس لون الشفافية. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | يُحقق من صحة قيم المورد. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransparencyIndexResource() {#TransparencyIndexResource--}
```
public TransparencyIndexResource()
```


ينشئ مثيلًا جديدًا من الفئة [TransparencyIndexResource](../../com.aspose.psd.fileformats.psd.resources/transparencyindexresource).

### RequiredVersion_internalized {#RequiredVersion-internalized}
```
public static final int RequiredVersion_internalized
```


إصدار PSD المطلوب.

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


يحصل على الحد الأدنى لإصدار PSD المطلوب.

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
### getTransparencyIndex() {#getTransparencyIndex--}
```
public final short getTransparencyIndex()
```


يحصل أو يضبط فهرس لون الشفافية.

القيمة: فهرس لون الشفافية.

**Returns:**
short
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


يحفظ كتلة المورد إلى الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | الدفق لحفظ كتلة المورد إليه. |

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

### setTransparencyIndex(short value) {#setTransparencyIndex-short-}
```
public final void setTransparencyIndex(short value)
```


يحصل أو يضبط فهرس لون الشفافية.

القيمة: فهرس لون الشفافية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

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

