---
title: "XmpDate"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل التاريخ في حزمة XMP."
type: docs
weight: 11
url: /ar/java/com.aspose.psd.xmp.types.basic/xmpdate/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

يمثل التاريخ في حزمة XMP.

يتم تمثيل قيمة التاريخ والوقت باستخدام مجموعة فرعية من الصيغ كما هو معرف في صيغ التاريخ والوقت: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | يُنشئ مثيلاً جديدًا للفئة  XmpDate  . |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | يُنشئ مثيلاً جديدًا للفئة  XmpDate  . |
## الحقول

| حقل | الوصف |
| --- | --- |
| [Iso8601Format](#Iso8601Format) | سلسلة تنسيق ISO 8601 (دورة كاملة). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [create_internalized(System.DateTime dateTime)](#create-internalized-com.aspose.ms.System.DateTime-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | يحصل على سلسلة التنسيق للقيمة الحالية. |
| [getValue()](#getValue--) | يحصل أو يعيّن قيمة التاريخ. |
| [getValue_internalized()](#getValue-internalized--) |  |
| [getXmpRepresentation()](#getXmpRepresentation--) | يعيد القيمة المحتواة كسلسلة في تنسيق XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(Date value)](#setValue-java.util.Date-) | يحصل أو يعيّن قيمة التاريخ. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


يُنشئ مثيلاً جديدًا للفئة  XmpDate  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dateTime | java.util.Date | قيمة تاريخ ووقت يتم تمثيلها باستخدام مجموعة فرعية من تنسيق ISO RFC 8601. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


يُنشئ مثيلاً جديدًا للفئة  XmpDate  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dateString | java.lang.String | التمثيل النصي للتاريخ. |

### Iso8601Format {#Iso8601Format}
```
public static final String Iso8601Format
```


سلسلة تنسيق ISO 8601 (دورة كاملة).

انظر المزيد: https://en.wikipedia.org/wiki/ISO\_8601.

### create_internalized(System.DateTime dateTime) {#create-internalized-com.aspose.ms.System.DateTime-}
```
public static XmpDate create_internalized(System.DateTime dateTime)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dateTime | com.aspose.ms.System.DateTime |  |

**Returns:**
[XmpDate](../../com.aspose.psd.xmp.types.basic/xmpdate)
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
### getFormat() {#getFormat--}
```
public String getFormat()
```


يحصل على سلسلة التنسيق للقيمة الحالية.

القيمة: سلسلة التنسيق للقيمة الحالية.

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public Date getValue()
```


يحصل أو يعيّن قيمة التاريخ.

القيمة: قيمة التاريخ.

**Returns:**
java.util.Date
### getValue_internalized() {#getValue-internalized--}
```
public System.DateTime getValue_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


يعيد القيمة المحتواة كسلسلة في تنسيق XMP.

**Returns:**
java.lang.String - يعيد القيمة المحتواة كسلسلة في تنسيق XMP.
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




### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


يحصل أو يعيّن قيمة التاريخ.

القيمة: قيمة التاريخ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.Date |  |

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

