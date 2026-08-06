---
title: "XmpRdfRoot"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل عنصر rdfRDF."
type: docs
weight: 21
url: /ar/java/com.aspose.psd.xmp/xmprdfroot/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

يمثل عنصر rdf:RDF. يجب تسلسل حزمة XMP واحدة باستخدام عنصر XML rdf:RDF واحد. يجب أن يتكون محتوى عنصر rdf:RDF من صفر أو أكثر من عناصر rdf:Description.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | يُنشئ مثيلاً جديدًا لفئة  XmpRdfRoot  . |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | يضيف السمة. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | يعين العنصر XMP المحدد إلى العنصر الحالي. |
| [clearAttributes()](#clearAttributes--) | يزيل جميع السمات. |
| [deepClone_internalized()](#deepClone-internalized--) | ينسخ هذه النسخة. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد Object يساوي هذه الحالة. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | يحصل على السمة. |
| [getClass()](#getClass--) |  |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | يحصل على URI للمساحة الاسمية وفقًا للبادئة المحددة. |
| [getXmlValue()](#getXmlValue--) | يحوّل قيمة xmp إلى تمثيل xml. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة لهذا الكائن. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | يشير إلى ما إذا كان الكائن الحالي مساويًا لكائن آخر من نفس النوع. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | يضيف URI للمساحة الاسمية وفقًا للبادئة. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


يُنشئ مثيلاً جديدًا لفئة  XmpRdfRoot  .

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
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الكائن المحدد Object يساوي هذه الحالة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة مع هذه المثيلة. |

**Returns:**
boolean - true إذا كان الكائن المحدد مساويًا لهذه المثيلة؛ وإلا false.
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
### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


يحصل على URI للمساحة الاسمية وفقًا للبادئة المحددة. قد تبدأ البادئة بدون xmlns.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| prefix | java.lang.String | البادئة. |

**Returns:**
java.lang.String - يُرجع URI لمخطط الحزمة.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


يحوّل قيمة xmp إلى تمثيل xml.

**Returns:**
java.lang.String - يُرجع قيمة XMP محوّلة إلى سلسلة XML.
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


يضيف URI للمساحة الاسمية وفقًا للبادئة. قد تبدأ البادئة بدون xmlns.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| prefix | java.lang.String | البادئة. |
| namespaceUri | java.lang.String | مسار مخطط الحزمة uri. |

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

