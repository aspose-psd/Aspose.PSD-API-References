---
title: "XmpPacketWrapper"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يحتوي على حزمة xmp مسلسلة تشمل الرأس والذيل."
type: docs
weight: 20
url: /ar/java/com.aspose.psd.xmp/xmppacketwrapper/
---

**Inheritance:**
java.lang.Object
```
public class XmpPacketWrapper
```

يحتوي على حزمة xmp مسلسلة تشمل الرأس والذيل.

يمكن وضع غلاف يتكوّن من زوج من تعليمات معالجة XML (PIs) حول العنصر rdf:RDF.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-) | يُنشئ مثيلاً جديدًا من الفئة XmpPacketWrapper. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | يُنشئ مثيلاً جديدًا من الفئة XmpPacketWrapper. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.psd.xmp.XmpPackage-) | يضيف الحزمة. |
| [clearPackages()](#clearPackages--) | يزيل جميع XmpPackage داخل XMP. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | يحدد ما إذا كانت الحزمة موجودة في غلاف XMP. |
| [deepClone_internalized()](#deepClone-internalized--) | ينسخ هذه النسخة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeaderPi()](#getHeaderPi--) | يحصل على تعليمات معالجة الرأس. |
| [getMeta()](#getMeta--) | يحصل على بيانات التعريف XMP. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | يحصل على الحزمة حسب مساحة الاسم URI. |
| [getPackages()](#getPackages--) | يحصل على مصفوفة من XmpPackage داخل XMP. |
| [getPackagesCount()](#getPackagesCount--) | يحصل على عدد الحزم داخل بنية XMP. |
| [getRdfRoot_internalized()](#getRdfRoot-internalized--) | يحصل على عنصر RDF الجذر. |
| [getTrailerPi()](#getTrailerPi--) | يحصل على تعليمات معالجة التذييل. |
| [getXmlValue_internalized()](#getXmlValue-internalized--) | يحوّل قيمة XMP إلى تمثيل XML. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.psd.xmp.XmpPackage-) | يزيل حزمة XMP. |
| [setHeaderPi(XmpHeaderPi value)](#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-) | يضبط تعليمات معالجة الرأس. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.psd.xmp.XmpMeta-) | يضبط بيانات التعريف XMP. |
| [setRdfRoot_internalized(XmpRdfRoot value)](#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-) | يضبط عنصر RDF الجذر. |
| [setTrailerPi(XmpTrailerPi value)](#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-) | يضبط تعليمات معالجة التذييل. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


يُنشئ مثيلاً جديدًا من الفئة XmpPacketWrapper.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | رأس XMP لتعليمات المعالجة. |
| trailer | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | تذييل XMP لتعليمات المعالجة. |
| xmpMeta | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | بيانات XMP الوصفية. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


يُنشئ مثيلاً جديدًا من الفئة XmpPacketWrapper.

### addPackage(XmpPackage package_) {#addPackage-com.aspose.psd.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


يضيف الحزمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | الحزمة. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


يزيل جميع XmpPackage داخل XMP.

### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


يحدد ما إذا كانت الحزمة موجودة في غلاف XMP.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| namespaceUri | java.lang.String | مسار مخطط الحزمة uri. |

**Returns:**
boolean - يرجع true إذا كانت الحزمة ذات مساحة الاسم المحددة Uri موجودة في غلاف XMP.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPacketWrapper deepClone_internalized()
```


ينسخ هذه النسخة.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The cloned object
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
### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


يحصل على تعليمات معالجة الرأس.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


يحصل على بيانات XMP الوصفية. اختياري.

**Returns:**
[XmpMeta](../../com.aspose.psd.xmp/xmpmeta) - The XMP meta. Optional.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


يحصل على الحزمة حسب مساحة الاسم URI.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI مخطط الحزمة. |

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


يحصل على مصفوفة من XmpPackage داخل XMP.

**Returns:**
com.aspose.psd.xmp.XmpPackage[] - المصفوفة من XmpPackage داخل XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


يحصل على عدد الحزم داخل بنية XMP.

**Returns:**
int - عدد الحزم داخل بنية XMP.
### getRdfRoot_internalized() {#getRdfRoot-internalized--}
```
public XmpRdfRoot getRdfRoot_internalized()
```


يحصل على عنصر RDF الجذر.

**Returns:**
[XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) - The RDF root element.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


يحصل على تعليمات معالجة التذييل.

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - Trailer processing instruction.
### getXmlValue_internalized() {#getXmlValue-internalized--}
```
public String getXmlValue_internalized()
```


يحوّل قيمة XMP إلى تمثيل XML.

**Returns:**
java.lang.String - يرجع قيمة XMP المحوّلة إلى XML.
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




### removePackage(XmpPackage package_) {#removePackage-com.aspose.psd.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


يزيل حزمة XMP.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | الحزمة. |

### setHeaderPi(XmpHeaderPi value) {#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-}
```
public void setHeaderPi(XmpHeaderPi value)
```


يضبط تعليمات معالجة الرأس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | تعليمات المعالجة Header. |

### setMeta(XmpMeta value) {#setMeta-com.aspose.psd.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


يضبط بيانات XMP الوصفية. اختياري.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | بيانات XMP الوصفية. اختياري. |

### setRdfRoot_internalized(XmpRdfRoot value) {#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-}
```
public void setRdfRoot_internalized(XmpRdfRoot value)
```


يضبط عنصر RDF الجذر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) | عنصر الجذر RDF. |

### setTrailerPi(XmpTrailerPi value) {#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-}
```
public void setTrailerPi(XmpTrailerPi value)
```


يضبط تعليمات معالجة التذييل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | تعليمات المعالجة Trailer. |

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

