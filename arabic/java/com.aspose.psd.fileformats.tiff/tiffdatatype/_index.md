---
title: "TiffDataType"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "نوع بيانات TIFF."
type: docs
weight: 10
url: /ar/java/com.aspose.psd.fileformats.tiff/tiffdatatype/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

نوع بيانات TIFF.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-) | يقارن المثيلة الحالية مع كائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كانت المثيلة الحالية تسبق أو تتبع أو تقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر. |
| [deepClone()](#deepClone--) | ينفّذ استنساخًا عميقًا لهذا الكائن. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getAlignedDataSize()](#getAlignedDataSize--) | يحصل على حجم البيانات الإضافية بالبايت (في حال أن 12 بايت غير كافية لاستيعاب بيانات العلامة). |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | يحصل على عدد العناصر. |
| [getDataSize()](#getDataSize--) | يحصل على حجم البيانات الإضافية بالبايت (في حال أن 12 بايت غير كافية لاستيعاب بيانات العلامة). |
| [getId()](#getId--) | يحصل على تمثيل معرف العلامة كعدد صحيح. |
| [getTagId()](#getTagId--) | يحصل على معرف العلامة. |
| [getTagType()](#getTagType--) | يحصل على نوع العلامة. |
| [getValue()](#getValue--) | يحصل على القيمة التي يحتويها هذا النوع من البيانات. |
| [hashCode()](#hashCode--) |  |
| [isPrivate_internalized()](#isPrivate-internalized--) | يحصل على قيمة تشير إلى ما إذا كانت العلامة خاصة. |
| [isValid()](#isValid--) | يحصل على قيمة تشير إلى ما إذا كانت بيانات العلامة صالحة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-) | يقرأ بيانات العلامة. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [toString()](#toString--) | يرجع  System.String  الذي يمثل هذه الحالة. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-) | يكتب البيانات الإضافية للعلامة. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | يكتب بيانات العلامة. |
### compareTo(TiffDataType obj) {#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


يقارن المثيلة الحالية مع كائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كانت المثيلة الحالية تسبق أو تتبع أو تقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | كائن للمقارنة مع هذا الكائن. |

**Returns:**
int - عدد صحيح موقع 32‑بت يشير إلى الترتيب النسبي للكائنات التي يتم مقارنتها. قيمة الإرجاع لها المعاني التالية: القيمة المعنى أقل من الصفر هذا الكائن أصغر من obj. الصفر هذا الكائن يساوي obj. أكبر من الصفر هذا الكائن أكبر من obj.
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


ينفّذ استنساخًا عميقًا لهذا الكائن.

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


يحصل على حجم البيانات الإضافية بالبايت (في حال أن 12 بايت غير كافية لاستيعاب بيانات العلامة).

**Returns:**
long - حجم البيانات الإضافية بالبايت.

هذا هو عدد بايتات البيانات محاذى إلى حد الكلمة.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public abstract long getCount()
```


يحصل على عدد العناصر.

**Returns:**
long - عدد العناصر.
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


يحصل على حجم البيانات الإضافية بالبايت (في حال أن 12 بايت غير كافية لاستيعاب بيانات العلامة).

**Returns:**
long - حجم البيانات الإضافية بالبايت.

هذا هو عدد البايتات الدقيق.
### getId() {#getId--}
```
public int getId()
```


يحصل على تمثيل معرف العلامة كعدد صحيح.

**Returns:**
int - تمثيل معرف العلامة كعدد صحيح
### getTagId() {#getTagId--}
```
public int getTagId()
```


يحصل على معرف العلامة.

**Returns:**
int - معرف العلامة.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


يحصل على نوع العلامة.

**Returns:**
int - نوع العلامة.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


يحصل على القيمة التي يحتويها هذا النوع من البيانات.

**Returns:**
java.lang.Object - القيمة.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isPrivate_internalized() {#isPrivate-internalized--}
```
public boolean isPrivate_internalized()
```


يحصل على قيمة تشير إلى ما إذا كانت العلامة خاصة. العلامات الخاصة بتنسيق tiff هي العلامات التي يكون معرفها أعلى من 32768.

**Returns:**
boolean -  true  إذا كانت بيانات العلامة صالحة؛ وإلا،  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


يحصل على قيمة تشير إلى ما إذا كانت بيانات العلامة صالحة. العلامة الصالحة تحتوي على بيانات قد يتم حفظها. العلامة غير الصالحة لا يمكن تخزينها.

**Returns:**
boolean -  true  إذا كانت بيانات العلامة صالحة؛ وإلا،  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


يقرأ بيانات العلامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader) | دفق البيانات. |
| position | long | موضع العلامة. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - The read tag.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


يضبط القيمة التي يحتويها هذا النوع من البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.Object | القيمة. |

### toString() {#toString--}
```
public String toString()
```


يرجع  System.String  الذي يمثل هذه الحالة.

**Returns:**
java.lang.String - سلسلة System.String تمثل هذه الحالة.
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

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


يكتب البيانات الإضافية للعلامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | دفق البيانات. |

**Returns:**
long - عدد البايتات الفعلية المكتوبة.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


يكتب بيانات العلامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | دفق البيانات. |
| additionalDataOffset | long | الإزاحة لكتابة البيانات الإضافية إليها. |

