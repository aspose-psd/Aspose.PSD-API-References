---
title: "XmpMeta"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل xmpmeta."
type: docs
weight: 17
url: /ar/java/com.aspose.psd.xmp/xmpmeta/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

يمثل xmpmeta. اختياري. الغرض من هذا العنصر هو تحديد بيانات XMP الوصفية داخل نص XML عام قد يحتوي على استخدامات غير XMP لـ RDF.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | يقوم بتهيئة نسخة جديدة من الفئة  XmpMeta . |
| [XmpMeta()](#XmpMeta--) | يقوم بتهيئة نسخة جديدة من الفئة  XmpMeta . |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | يضيف السمة. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | يعين العنصر XMP المحدد إلى العنصر الحالي. |
| [clearAttributes()](#clearAttributes--) | يزيل جميع السمات. |
| [deepClone_internalized()](#deepClone-internalized--) | ينسخ هذه النسخة. |
| [equals(Object other)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد  System.Object , يساوي هذه الحالة. |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | يحصل أو يضبط إصدار مجموعة أدوات Adobe Xmp. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | يحصل على السمة. |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | يحوّل قيمة XMP إلى تمثيل XML. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة لهذا الكائن. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | يشير إلى ما إذا كان الكائن الحالي مساويًا لكائن آخر من نفس النوع. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.psd.xmp.XmpMeta-) | يشير إلى ما إذا كان الكائن الحالي مساويًا لكائن آخر من نفس النوع. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | يحصل أو يضبط إصدار مجموعة أدوات Adobe Xmp. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


يقوم بتهيئة نسخة جديدة من الفئة  XmpMeta .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| toolkitVersion | java.lang.String | إصدار مجموعة أدوات Adobe XMP. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


يقوم بتهيئة نسخة جديدة من الفئة  XmpMeta .

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


يضيف السمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| attribute | java.lang.String | السمة. |
| القيمة | java.lang.String | القيمة. |

### assign_internalized(XmpElementBase xmpElement) {#assign-internalized-com.aspose.psd.xmp.XmpElementBase-}
```
public void assign_internalized(XmpElementBase xmpElement)
```


يعين العنصر XMP المحدد إلى العنصر الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| xmpElement | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | العنصر XMP. |

### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


يزيل جميع السمات.

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpElementBase deepClone_internalized()
```


ينسخ هذه النسخة.

**Returns:**
[XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) - The cloned object
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


يحدد ما إذا كان الكائن المحدد  System.Object , يساوي هذه الحالة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | java.lang.Object | الكائن System.Object للمقارنة مع هذا الكائن. |

**Returns:**
منطقية - true إذا كان الكائن System.Object المحدد مساويًا لهذا الكائن؛ وإلا false.
### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


يحصل أو يضبط إصدار مجموعة أدوات Adobe Xmp.

**Returns:**
java.lang.String
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


يحصل على السمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| attribute | java.lang.String | السمة. |

**Returns:**
java.lang.String - يرجع السمة للاسم المحدد للصفة.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### isEquals(XmpElementBase other) {#isEquals-com.aspose.psd.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


يشير إلى ما إذا كان الكائن الحالي مساويًا لكائن آخر من نفس النوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | كائن للمقارنة مع هذا الكائن. |

**Returns:**
منطقية - true إذا كان الكائن الحالي مساويًا للمعامل other؛ وإلا false.
### isEquals(XmpMeta other) {#isEquals-com.aspose.psd.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


يشير إلى ما إذا كان الكائن الحالي مساويًا لكائن آخر من نفس النوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | كائن للمقارنة مع هذا الكائن. |

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




### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


يحصل أو يضبط إصدار مجموعة أدوات Adobe Xmp.

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

