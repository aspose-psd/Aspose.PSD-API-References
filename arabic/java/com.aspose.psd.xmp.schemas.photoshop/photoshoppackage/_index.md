---
title: "PhotoshopPackage"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل مساحة الاسم Adobe Photoshop."
type: docs
weight: 12
url: /ar/java/com.aspose.psd.xmp.schemas.photoshop/photoshoppackage/
---

**Inheritance:**
java.lang.Object، [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class PhotoshopPackage extends XmpPackage
```

يمثل مساحة الاسم Adobe Photoshop.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PhotoshopPackage()](#PhotoshopPackage--) | يقوم بتهيئة نسخة جديدة من الفئة PhotoshopPackage. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [UrgencyMax](#UrgencyMax) | القيمة القصوى للـUrgency. |
| [UrgencyMin](#UrgencyMin) | القيمة الدنيا للـUrgency. |
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
| [setAuthorsPosition(String authorsPosition)](#setAuthorsPosition-java.lang.String-) | يضبط موضع المؤلفين. |
| [setCaptionWriter(String captionWriter)](#setCaptionWriter-java.lang.String-) | يضبط كاتب التسمية. |
| [setCategory(String category)](#setCategory-java.lang.String-) | يضبط الفئة. |
| [setCity(String city)](#setCity-java.lang.String-) | يضبط المدينة. |
| [setColorMode(byte colorMode)](#setColorMode-byte-) | يضبط وضع اللون. |
| [setCountry(String country)](#setCountry-java.lang.String-) | يضبط الدولة. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | يضبط تاريخ الإنشاء. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setCredit(String credit)](#setCredit-java.lang.String-) | يضبط الائتمان. |
| [setDocumentAncestors(String[] ancestors)](#setDocumentAncestors-java.lang.String---) | يضبط أسلاف المستند. |
| [setHeadline(String headline)](#setHeadline-java.lang.String-) | يضبط العنوان الرئيسي. |
| [setHistory(String history)](#setHistory-java.lang.String-) | يضبط التاريخ. |
| [setIccProfile(String iccProfile)](#setIccProfile-java.lang.String-) | يضبط ملف تعريف icc. |
| [setInstructions(String instructions)](#setInstructions-java.lang.String-) | يضبط التعليمات. |
| [setSource(String source)](#setSource-java.lang.String-) | يضبط المصدر. |
| [setState(String state)](#setState-java.lang.String-) | يضبط الحالة. |
| [setSupplementalCategories(String[] supplementalCategories)](#setSupplementalCategories-java.lang.String---) | يضبط الفئات التكميلية. |
| [setTransmissionReference(String transmissionReference)](#setTransmissionReference-java.lang.String-) | يضبط مرجع الإرسال. |
| [setUrgency(int urgency)](#setUrgency-int-) | يضبط الإلحاح. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | يضبط القيمة. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | يضبط قيمة XMP المنطقية. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | يضبط المعرف الفريد لـ XMP. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | يضبط قيمة نوع XMP. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | يضبط الـ  Object  بالمفتاح المحدد. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhotoshopPackage() {#PhotoshopPackage--}
```
public PhotoshopPackage()
```


يقوم بتهيئة نسخة جديدة من الفئة PhotoshopPackage.

### UrgencyMax {#UrgencyMax}
```
public static final int UrgencyMax
```


القيمة القصوى للـUrgency.

### UrgencyMin {#UrgencyMin}
```
public static final int UrgencyMin
```


القيمة الدنيا للـUrgency.

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
### setAuthorsPosition(String authorsPosition) {#setAuthorsPosition-java.lang.String-}
```
public void setAuthorsPosition(String authorsPosition)
```


يضبط موضع المؤلفين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| authorsPosition | java.lang.String | موضع المؤلفين. |

### setCaptionWriter(String captionWriter) {#setCaptionWriter-java.lang.String-}
```
public void setCaptionWriter(String captionWriter)
```


يضبط كاتب التسمية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| captionWriter | java.lang.String | كاتب التسمية التوضيحية. |

### setCategory(String category) {#setCategory-java.lang.String-}
```
public void setCategory(String category)
```


يضبط الفئة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| category | java.lang.String | الفئة. |

### setCity(String city) {#setCity-java.lang.String-}
```
public void setCity(String city)
```


يضبط المدينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| city | java.lang.String | اسم المدينة. |

### setColorMode(byte colorMode) {#setColorMode-byte-}
```
public void setColorMode(byte colorMode)
```


يضبط وضع اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorMode | byte | وضع اللون. |

### setCountry(String country) {#setCountry-java.lang.String-}
```
public void setCountry(String country)
```


يضبط الدولة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| country | java.lang.String | البلد. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


يضبط تاريخ الإنشاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| createdDate | java.util.Date | تاريخ الإنشاء. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime |  |

### setCredit(String credit) {#setCredit-java.lang.String-}
```
public void setCredit(String credit)
```


يضبط الائتمان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رصيد | java.lang.String | الرصيد. |

### setDocumentAncestors(String[] ancestors) {#setDocumentAncestors-java.lang.String---}
```
public void setDocumentAncestors(String[] ancestors)
```


يضبط أسلاف المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الأسلاف | java.lang.String[] | الأسلاف. |

### setHeadline(String headline) {#setHeadline-java.lang.String-}
```
public void setHeadline(String headline)
```


يضبط العنوان الرئيسي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العنوان الرئيسي | java.lang.String | العنوان الرئيسي. |

### setHistory(String history) {#setHistory-java.lang.String-}
```
public void setHistory(String history)
```


يضبط التاريخ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التاريخ | java.lang.String | التاريخ. |

### setIccProfile(String iccProfile) {#setIccProfile-java.lang.String-}
```
public void setIccProfile(String iccProfile)
```


يضبط ملف تعريف icc.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| iccProfile | java.lang.String | ملف icc. |

### setInstructions(String instructions) {#setInstructions-java.lang.String-}
```
public void setInstructions(String instructions)
```


يضبط التعليمات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التعليمات | java.lang.String | التعليمات. |

### setSource(String source) {#setSource-java.lang.String-}
```
public void setSource(String source)
```


يضبط المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المصدر | java.lang.String | المصدر. |

### setState(String state) {#setState-java.lang.String-}
```
public void setState(String state)
```


يضبط الحالة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الحالة | java.lang.String | الحالة. |

### setSupplementalCategories(String[] supplementalCategories) {#setSupplementalCategories-java.lang.String---}
```
public void setSupplementalCategories(String[] supplementalCategories)
```


يضبط الفئات التكميلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| supplementalCategories | java.lang.String[] | الفئات التكميلية. |

### setTransmissionReference(String transmissionReference) {#setTransmissionReference-java.lang.String-}
```
public void setTransmissionReference(String transmissionReference)
```


يضبط مرجع الإرسال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| transmissionReference | java.lang.String | مرجع الإرسال. |

### setUrgency(int urgency) {#setUrgency-int-}
```
public void setUrgency(int urgency)
```


يضبط الإلحاح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الأولوية | int | الأولوية. |

يجب أن تكون الأولوية في النطاق من 1 إلى 8. |

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

