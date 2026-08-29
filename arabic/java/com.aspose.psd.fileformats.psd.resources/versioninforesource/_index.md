---
title: "VersionInfoResource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "مورد معلومات الإصدار"
type: docs
weight: 41
url: /ar/java/com.aspose.psd.fileformats.psd.resources/versioninforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class VersionInfoResource extends ResourceBlock
```

مورد معلومات الإصدار
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [VersionInfoResource()](#VersionInfoResource--) | تهيئة نسخة جديدة من الفئة [VersionInfoResource](../../com.aspose.psd.fileformats.psd.resources/versioninforesource) . |
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
| [getFileVersion()](#getFileVersion--) | الحصول أو تعيين إصدار الملف. |
| [getID()](#getID--) | يحصل أو يعيّن المعرف الفريد للمورد. |
| [getMinimalVersion()](#getMinimalVersion--) | يحصل على الحد الأدنى المطلوب لإصدار PSD. |
| [getName()](#getName--) | يحصل على أو يعيّن اسم المورد. |
| [getReaderName()](#getReaderName--) | الحصول أو تعيين اسم القارئ. |
| [getSignature()](#getSignature--) | يحصل على توقيع المورد. |
| [getSize()](#getSize--) | يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها. |
| [getVersion()](#getVersion--) | يحصل على أو يعيّن الإصدار. |
| [getWriterName()](#getWriterName--) | الحصول أو تعيين اسم الكاتب. |
| [hasRealMergedData()](#hasRealMergedData--) | الحصول أو تعيين قيمة تشير إلى ما إذا كانت هذه النسخة تحتوي على بيانات مدمجة حقيقية. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | يحفظ كتلة المورد إلى الدفق المحدد. |
| [setFileVersion(long value)](#setFileVersion-long-) | الحصول أو تعيين إصدار الملف. |
| [setID(short value)](#setID-short-) | يحصل أو يعيّن المعرف الفريد للمورد. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | يحصل على أو يعيّن معلومات الطبقة والقناع. |
| [setName(String value)](#setName-java.lang.String-) | يحصل على أو يعيّن اسم المورد. |
| [setReaderName(String value)](#setReaderName-java.lang.String-) | الحصول أو تعيين اسم القارئ. |
| [setRealMergedData(boolean value)](#setRealMergedData-boolean-) | الحصول أو تعيين قيمة تشير إلى ما إذا كانت هذه النسخة تحتوي على بيانات مدمجة حقيقية. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | يحصل على أو يعيّن حالة كتلة المورد. |
| [setVersion(long value)](#setVersion-long-) | يحصل على أو يعيّن الإصدار. |
| [setWriterName(String value)](#setWriterName-java.lang.String-) | الحصول أو تعيين اسم الكاتب. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | يُحقق من صحة قيم المورد. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VersionInfoResource() {#VersionInfoResource--}
```
public VersionInfoResource()
```


تهيئة نسخة جديدة من الفئة [VersionInfoResource](../../com.aspose.psd.fileformats.psd.resources/versioninforesource) .

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
### getFileVersion() {#getFileVersion--}
```
public final long getFileVersion()
```


الحصول أو تعيين إصدار الملف.

القيمة: إصدار الملف.

**Returns:**
long
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
### getReaderName() {#getReaderName--}
```
public final String getReaderName()
```


الحصول أو تعيين اسم القارئ.

القيمة: اسم القارئ.

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
### getVersion() {#getVersion--}
```
public final long getVersion()
```


يحصل على أو يعيّن الإصدار.

القيمة: الإصدار.

**Returns:**
long
### getWriterName() {#getWriterName--}
```
public final String getWriterName()
```


الحصول أو تعيين اسم الكاتب.

القيمة: اسم الكاتب.

**Returns:**
java.lang.String
### hasRealMergedData() {#hasRealMergedData--}
```
public final boolean hasRealMergedData()
```


الحصول أو تعيين قيمة تشير إلى ما إذا كانت هذه النسخة تحتوي على بيانات مدمجة حقيقية.

القيمة:  true  إذا كانت هذه النسخة تحتوي على بيانات مدمجة حقيقية؛ وإلا،  false .

**Returns:**
boolean
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

### setFileVersion(long value) {#setFileVersion-long-}
```
public final void setFileVersion(long value)
```


الحصول أو تعيين إصدار الملف.

القيمة: إصدار الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

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

### setReaderName(String value) {#setReaderName-java.lang.String-}
```
public final void setReaderName(String value)
```


الحصول أو تعيين اسم القارئ.

القيمة: اسم القارئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setRealMergedData(boolean value) {#setRealMergedData-boolean-}
```
public final void setRealMergedData(boolean value)
```


الحصول أو تعيين قيمة تشير إلى ما إذا كانت هذه النسخة تحتوي على بيانات مدمجة حقيقية.

القيمة:  true  إذا كانت هذه النسخة تحتوي على بيانات مدمجة حقيقية؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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

### setVersion(long value) {#setVersion-long-}
```
public final void setVersion(long value)
```


يحصل على أو يعيّن الإصدار.

القيمة: الإصدار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setWriterName(String value) {#setWriterName-java.lang.String-}
```
public final void setWriterName(String value)
```


الحصول أو تعيين اسم الكاتب.

القيمة: اسم الكاتب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

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

