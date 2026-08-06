---
title: "DublinCorePackage"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل مخطط Dublic Core."
type: docs
weight: 10
url: /ar/java/com.aspose.psd.xmp.schemas.dublincore/dublincorepackage/
---

**Inheritance:**
java.lang.Object، [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class DublinCorePackage extends XmpPackage
```

يمثل مخطط Dublic Core.

لمزيد من المعلومات راجع: http://dublincore.org/documents/usageguide/elements.shtml.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DublinCorePackage()](#DublinCorePackage--) | يُنشئ مثيلًا جديدًا من الفئة  DublinCorePackage . |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | يضيف مساحة اسم النوع المعقد. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | يضيف خاصية سلسلة. |
| [assign_internalized(XmpPackage xmpPackege)](#assign-internalized-com.aspose.psd.xmp.XmpPackage-) | يعين حزمة XMP المحددة إلى الحالية. |
| [clear()](#clear--) | يمسح هذه النسخة. |
| [combinePackage_internalized(XmpPackage other)](#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-) | يجمع الحزمة. |
| [containsKey(String key)](#containsKey-java.lang.String-) | يحدد ما إذا كان المفتاح المحدد يحتوي على المفتاح. |
| [deepClone_internalized()](#deepClone-internalized--) | ينسخ هذه النسخة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | يحصل على المفاتيح في حزمة XMP. |
| [getNamespaceUri()](#getNamespaceUri--) | يحصل على URI مساحة الاسم. |
| [getPrefix()](#getPrefix--) | يحصل على البادئة. |
| [getXmlNamespace()](#getXmlNamespace--) | يحصل على مساحة اسم XML. |
| [getXmlValue()](#getXmlValue--) | يحوّل قيمة XMP إلى تمثيل XML. |
| [get_Item(String key)](#get-Item-java.lang.String-) | يحصل أو يعيّن الـObject بالمفتاح المحدد. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | يرجع عدّادًا يتنقل عبر المجموعة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | إزالة القيمة بالمفتاح المحدد. |
| [setAuthor(String author)](#setAuthor-java.lang.String-) | يضيف المؤلف. |
| [setAuthor(String[] author)](#setAuthor-java.lang.String---) | يضيف المؤلف. |
| [setDescription(LangAlt desc)](#setDescription-com.aspose.psd.xmp.LangAlt-) | يضيف الوصف. |
| [setDescription(String desc)](#setDescription-java.lang.String-) | يضيف الوصف. |
| [setPublisher(String publisher)](#setPublisher-java.lang.String-) | يضيف الناشر. |
| [setPublisher(String[] publisher)](#setPublisher-java.lang.String---) | يضيف الناشر. |
| [setSubject(String subject)](#setSubject-java.lang.String-) | يضيف الموضوع. |
| [setSubject(String[] subject)](#setSubject-java.lang.String---) | يضيف الموضوع. |
| [setTitle(LangAlt title)](#setTitle-com.aspose.psd.xmp.LangAlt-) | يضيف عنوان Dublin Core للغات المختلفة. |
| [setTitle(String title)](#setTitle-java.lang.String-) | يضيف عنوان Dublin Core. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | يضبط القيمة. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | يضبط قيمة XMP المنطقية. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | يضبط المعرف الفريد لـ XMP. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | يضبط قيمة نوع XMP. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | يضبط الـ  Object  بالمفتاح المحدد. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DublinCorePackage() {#DublinCorePackage--}
```
public DublinCorePackage()
```


يُنشئ مثيلًا جديدًا من الفئة  DublinCorePackage .

### addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri) {#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-}
```
public void addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)
```


يضيف مساحة اسم النوع المعقد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| typePrefix | java.lang.String | بادئة النوع. |
| typeNamespaceUri | java.lang.String | معرف URI مساحة الاسم للنوع. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


يضيف خاصية سلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| القيمة | java.lang.String | قيمة السلسلة. |

### assign_internalized(XmpPackage xmpPackege) {#assign-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void assign_internalized(XmpPackage xmpPackege)
```


يعين حزمة XMP المحددة إلى الحالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| xmpPackege | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | حزمة XMP. |

### clear() {#clear--}
```
public void clear()
```


يمسح هذه النسخة.

### combinePackage_internalized(XmpPackage other) {#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void combinePackage_internalized(XmpPackage other)
```


يجمع الحزمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | الحزمة الأخرى للجمع. |

### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


يحدد ما إذا كان المفتاح المحدد يحتوي على المفتاح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | المفتاح الذي سيتم فحصه. |

**Returns:**
boolean - يُرجع true إذا كان المفتاح المحدد يحتوي على المفتاح.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPackage deepClone_internalized()
```


ينسخ هذه النسخة.

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - The cloned object
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
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


يحصل على المفاتيح في حزمة XMP.

القيمة: المفاتيح في حزمة XMP.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


يحصل على URI مساحة الاسم.

القيمة: معرف مساحة الاسم URI.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


يحصل على البادئة.

القيمة: البادئة.

**Returns:**
java.lang.String
### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


يحصل على مساحة اسم XML.

القيمة: مساحة اسم XML.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


يحوّل قيمة XMP إلى تمثيل XML.

**Returns:**
java.lang.String - يُرجِع قيمة XMP محوَّلة إلى تمثيل XML.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


يحصل أو يعيّن الـObject بالمفتاح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | المفتاح الذي يحدد القيمة. |

**Returns:**
java.lang.Object - يُرجِع الـ Object بالمفتاح المحدد.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


يرجع عدّادًا يتنقل عبر المجموعة.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - أداة T:System.Collections.Generic.IEnumerator1 التي يمكن استخدامها للتنقل عبر المجموعة.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


إزالة القيمة بالمفتاح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | التمثيل النصي للمفتاح الذي يتم تحديده بالقيمة المحذوفة. |

**Returns:**
boolean - يُرجِع true إذا تم حذف القيمة بالمفتاح المحدد.
### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


يضيف المؤلف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المؤلف | java.lang.String | المؤلف. |

### setAuthor(String[] author) {#setAuthor-java.lang.String---}
```
public void setAuthor(String[] author)
```


يضيف المؤلف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المؤلف | java.lang.String[] | المؤلف. |

### setDescription(LangAlt desc) {#setDescription-com.aspose.psd.xmp.LangAlt-}
```
public void setDescription(LangAlt desc)
```


يضيف الوصف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| desc | [LangAlt](../../com.aspose.psd.xmp/langalt) | الوصف. |

### setDescription(String desc) {#setDescription-java.lang.String-}
```
public void setDescription(String desc)
```


يضيف الوصف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الوصف | java.lang.String | الوصف. |

### setPublisher(String publisher) {#setPublisher-java.lang.String-}
```
public void setPublisher(String publisher)
```


يضيف الناشر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الناشر | java.lang.String | الناشر. |

### setPublisher(String[] publisher) {#setPublisher-java.lang.String---}
```
public void setPublisher(String[] publisher)
```


يضيف الناشر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الناشر | java.lang.String[] | الناشر. |

### setSubject(String subject) {#setSubject-java.lang.String-}
```
public void setSubject(String subject)
```


يضيف الموضوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الموضوع | java.lang.String | الموضوع. |

### setSubject(String[] subject) {#setSubject-java.lang.String---}
```
public void setSubject(String[] subject)
```


يضيف الموضوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الموضوع | java.lang.String[] | الموضوع. |

### setTitle(LangAlt title) {#setTitle-com.aspose.psd.xmp.LangAlt-}
```
public void setTitle(LangAlt title)
```


يضيف عنوان Dublin Core للغات المختلفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| title | [LangAlt](../../com.aspose.psd.xmp/langalt) | مثال من LangAlt. |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


يضيف عنوان Dublin Core.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العنوان | java.lang.String | العنوان. |

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


يضبط القيمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| value | [IXmlValue](../../com.aspose.psd.xmp/ixmlvalue) | القيمة التي سيتم الإضافة إليها. |

### setXmpBoolean(String key, String boolValue) {#setXmpBoolean-java.lang.String-java.lang.String-}
```
public void setXmpBoolean(String key, String boolValue)
```


يضبط قيمة XMP المنطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه بالقيمة المحددة. |
| boolValue | java.lang.String | القيمة المنطقية. |

### setXmpGuid(String key, String guid) {#setXmpGuid-java.lang.String-java.lang.String-}
```
public void setXmpGuid(String key, String guid)
```


يضبط المعرف الفريد لـ XMP.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | تمثيل السلسلة للمفتاح الذي تم التعرف عليه بقيمة GUID المحددة. |
| guid | java.lang.String | المعرّف الفريد. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


يضبط قيمة نوع XMP.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه بالقيمة المحددة. |
| value | [XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase) | القيمة التي سيتم تعيينها. |

### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


يضبط الـ  Object  بالمفتاح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | المفتاح الذي يحدد القيمة. |
| القيمة | java.lang.Object | قيمة الـ Object. |

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

