---
title: "XmpHeaderPi"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل تعليمات معالجة رأس XMP."
type: docs
weight: 16
url: /ar/java/com.aspose.psd.xmp/xmpheaderpi/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

يمثل تعليمات معالجة رأس XMP.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | يُنشئ مثيلاً جديدًا من الفئة XmpHeaderPi. |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | يُنشئ مثيلاً جديدًا من الفئة XmpHeaderPi. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | ينسخ هذه النسخة. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد  System.Object , يساوي هذه الحالة. |
| [getClass()](#getClass--) |  |
| [getGuid()](#getGuid--) | يمثّل معرف الرأس Guid. |
| [getXmlValue()](#getXmlValue--) | يحوّل قيمة XMP إلى تمثيل XML. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة لهذا الكائن. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.psd.xmp.XmpHeaderPi-) | يشير إلى ما إذا كان الكائن الحالي مساويًا لكائن آخر من نفس النوع. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGuid(String value)](#setGuid-java.lang.String-) | يمثّل معرف الرأس Guid. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


يُنشئ مثيلاً جديدًا من الفئة XmpHeaderPi.

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


يُنشئ مثيلاً جديدًا من الفئة XmpHeaderPi.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| guid | java.lang.String | المعرّف الفريد. |

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpHeaderPi deepClone_internalized()
```


ينسخ هذه النسخة.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الكائن المحدد  System.Object , يساوي هذه الحالة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن System.Object للمقارنة مع هذا الكائن. |

**Returns:**
منطقية - true إذا كان الكائن System.Object المحدد مساويًا لهذا الكائن؛ وإلا false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGuid() {#getGuid--}
```
public String getGuid()
```


يمثّل معرف الرأس Guid.

نص رأس الـ PI يحتوي على GUID، مما يجعل ظهوره عن طريق الخطأ في تدفق البيانات غير محتمل.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


يحوّل قيمة XMP إلى تمثيل XML.

**Returns:**
java.lang.String - يُرجِع قيمة XMP محوَّلة إلى تمثيل XML.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة لهذا الكائن.

**Returns:**
int - رمز تجزئة لهذا الكائن، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.psd.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


يشير إلى ما إذا كان الكائن الحالي مساويًا لكائن آخر من نفس النوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | كائن للمقارنة مع هذا الكائن. |

**Returns:**
منطقية - true إذا كان الكائن الحالي مساويًا للمعامل other؛ وإلا false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


يمثّل معرف الرأس Guid.

نص رأس الـ PI يحتوي على GUID، مما يجعل ظهوره عن طريق الخطأ في تدفق البيانات غير محتمل.

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

