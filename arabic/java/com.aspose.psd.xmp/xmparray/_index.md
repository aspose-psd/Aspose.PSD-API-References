---
title: "XmpArray"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل Xmp Array في XmpPackage."
type: docs
weight: 12
url: /ar/java/com.aspose.psd.xmp/xmparray/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public class XmpArray implements IXmlValue
```

يمثل Xmp Array في XmpPackage. ملاحظة: قد يحتوي Array على بيانات معقدة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpArray(int type, String[] items)](#XmpArray-int-java.lang.String---) | ينشئ مثيلاً جديداً من الفئة XmpArray. |
| [XmpArray(int type)](#XmpArray-int-) | ينشئ مثيلاً جديداً من الفئة XmpArray. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addElement_internalized(XmpPackage element)](#addElement-internalized-com.aspose.psd.xmp.XmpPackage-) | يضيف عنصرًا جديدًا. |
| [addItem(String item)](#addItem-java.lang.String-) | يضيف عنصرًا جديدًا. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getElements_internalized()](#getElements-internalized--) | يحصل على مصفوفة القيم داخل [XmpArray](../../com.aspose.psd.xmp/xmparray). |
| [getValues()](#getValues--) | يحصل على مصفوفة القيم داخل XmpArray. |
| [getXmlValue()](#getXmlValue--) | يحوّل قيمة XMP إلى تمثيل XML. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | يرجع  System.String  الذي يمثل هذه الحالة. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpArray(int type, String[] items) {#XmpArray-int-java.lang.String---}
```
public XmpArray(int type, String[] items)
```


ينشئ مثيلاً جديداً من الفئة XmpArray.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع | int | نوع المصفوفة. |
| العناصر | java.lang.String[] | قائمة العناصر. |

### XmpArray(int type) {#XmpArray-int-}
```
public XmpArray(int type)
```


ينشئ مثيلاً جديداً من الفئة XmpArray.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع | int | نوع المصفوفة. |

### addElement_internalized(XmpPackage element) {#addElement-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public final void addElement_internalized(XmpPackage element)
```


يضيف عنصرًا جديدًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| element | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | العنصر الذي سيُضاف إلى قائمة العناصر. |

### addItem(String item) {#addItem-java.lang.String-}
```
public void addItem(String item)
```


يضيف عنصرًا جديدًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| عنصر | java.lang.String | العنصر الذي سيُضاف إلى قائمة العناصر. |

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
### getElements_internalized() {#getElements-internalized--}
```
public final XmpPackage[] getElements_internalized()
```


يحصل على مصفوفة القيم داخل [XmpArray](../../com.aspose.psd.xmp/xmparray).

**Returns:**
com.aspose.psd.xmp.XmpPackage[]
### getValues() {#getValues--}
```
public String[] getValues()
```


يحصل على مصفوفة القيم داخل XmpArray.

**Returns:**
java.lang.String[]
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


يحوّل قيمة XMP إلى تمثيل XML.

**Returns:**
java.lang.String - يُرجِع قيمة XMP محوَّلة إلى تمثيل XML.
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

