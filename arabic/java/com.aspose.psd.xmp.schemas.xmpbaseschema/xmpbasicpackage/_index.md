---
title: "XmpBasicPackage"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل مساحة الاسم الأساسية XMP."
type: docs
weight: 10
url: /ar/java/com.aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Inheritance:**
java.lang.Object، [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

يمثل مساحة الاسم الأساسية XMP.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | يُنشئ مثيلاً جديدًا لفئة  XmpBasicPackage  . |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | يُنشئ مثيلاً جديدًا لفئة  XmpBasicPackage  . |
## الحقول

| حقل | الوصف |
| --- | --- |
| [RatingMax](#RatingMax) | القيمة القصوى للتقييم. |
| [RatingMin](#RatingMin) | القيمة الدنيا للتقييم. |
| [RatingRejected](#RatingRejected) | القيمة المرفوضة للتقييم. |
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
| [get_Item(String key)](#get-Item-java.lang.String-) | يحصل أو يضبط الـ Object بالمفتاح المحدد. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | يرجع عدّادًا يتنقل عبر المجموعة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | إزالة القيمة بالمفتاح المحدد. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | يضيف تاريخ إنشاء المورد. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) | يضيف تاريخ إنشاء المورد. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | يضبط أداة الإنشاء. |
| [setIdentifier(String[] idenfifier)](#setIdentifier-java.lang.String---) | يضبط المعرف. |
| [setLabel(String label)](#setLabel-java.lang.String-) | يضبط التسمية. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | يضيف تاريخ آخر تعديل للبيانات الوصفية. |
| [setMetadataDate_internalized(System.DateTime metadataDate)](#setMetadataDate-internalized-com.aspose.ms.System.DateTime-) | يضيف تاريخ آخر تعديل للبيانات الوصفية. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | يضيف تاريخ آخر تعديل للمورد. |
| [setModifyDate_internalized(System.DateTime modifiedDate)](#setModifyDate-internalized-com.aspose.ms.System.DateTime-) | يضيف تاريخ آخر تعديل للمورد. |
| [setRating(int choise)](#setRating-int-) | يضبط التقييم. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | يضبط القيمة. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | يضبط قيمة XMP المنطقية. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | يضبط المعرف الفريد لـ XMP. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | يضبط قيمة نوع XMP. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | يحصل أو يضبط الـ Object بالمفتاح المحدد. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


يُنشئ مثيلاً جديدًا لفئة  XmpBasicPackage  .

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


يُنشئ مثيلاً جديدًا لفئة  XmpBasicPackage  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| prefix | java.lang.String | البادئة. |
| namespaceUri | java.lang.String | معرف مساحة الاسم. |

### RatingMax {#RatingMax}
```
public static final int RatingMax
```


القيمة القصوى للتقييم.

### RatingMin {#RatingMin}
```
public static final int RatingMin
```


القيمة الدنيا للتقييم.

### RatingRejected {#RatingRejected}
```
public static final int RatingRejected
```


القيمة المرفوضة للتقييم.

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


يحصل أو يضبط الـ Object بالمفتاح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | المفتاح الذي يحدد القيمة. القيمة: الـ Object. |

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
### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


يضيف تاريخ إنشاء المورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| createdDate | java.lang.String | تاريخ الإنشاء. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```


يضيف تاريخ إنشاء المورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime | تاريخ الإنشاء. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


يضبط أداة الإنشاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| creatorTool | java.lang.String | اسم الأداة. |

### setIdentifier(String[] idenfifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] idenfifier)
```


يضبط المعرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| idenfifier | java.lang.String[] | المعرف idenfifier. |

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


يضبط التسمية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| label | java.lang.String | التسمية. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


يضيف تاريخ آخر تعديل للبيانات الوصفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| metadataDate | java.lang.String | تاريخ البيانات الوصفية. |

### setMetadataDate_internalized(System.DateTime metadataDate) {#setMetadataDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setMetadataDate_internalized(System.DateTime metadataDate)
```


يضيف تاريخ آخر تعديل للبيانات الوصفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| metadataDate | com.aspose.ms.System.DateTime | تاريخ البيانات الوصفية. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


يضيف تاريخ آخر تعديل للمورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| modifiedDate | java.lang.String | تاريخ آخر تعديل. |

### setModifyDate_internalized(System.DateTime modifiedDate) {#setModifyDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setModifyDate_internalized(System.DateTime modifiedDate)
```


يضيف تاريخ آخر تعديل للمورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| modifiedDate | com.aspose.ms.System.DateTime | تاريخ آخر تعديل. |

### setRating(int choise) {#setRating-int-}
```
public void setRating(int choise)
```


يضبط التقييم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| اختيار | int | من -1 حتى 5 |

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


يحصل أو يضبط الـ Object بالمفتاح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | المفتاح الذي يحدد القيمة. القيمة: الـ Object. |
| القيمة | java.lang.Object |  |

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

