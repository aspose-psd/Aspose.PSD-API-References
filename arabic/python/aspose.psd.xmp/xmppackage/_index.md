---
title: "فئة XmpPackage"
type: docs
weight: 430
url: /ar/python-net/aspose.psd.xmp/xmppackage/
---

**Summary:** Defines the XmpPackage class that represents base abstraction for XMP package.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackage

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| namespace_uri | string | r | يحصل على URI للمساحة الاسمية. |
| بادئة | string | r | يحصل على البادئة. |
| xml_namespace | string | r | يحصل على مساحة الاسم XML. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | يضيف القيمة. |
| clear() | يمسح هذا الكائن. |
| [contains_key(key)](#contains_key_key_2) | يحدد ما إذا كان المفتاح المحدد يحتوي على المفتاح. |
| [get_xml_value()](#get_xml_value__3) | يحوّل قيمة XMP إلى تمثيل XML. |
| [remove(key)](#remove_key_4) | إزالة القيمة بالمفتاح المحدد. |
| [set_value(key, value)](#set_value_key_value_5) | يضبط القيمة. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_6) | يضبط قيمة نوع XMP. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

يضيف القيمة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي تم التعرف عليه بالقيمة المضافة. |
| قيمة | string | القيمة التي ستُضاف إليها. |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

يحدد ما إذا كان المفتاح المحدد يحتوي على المفتاح.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key | string | المفتاح الذي سيتم فحصه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | يرجع true إذا كان المفتاح المحدد يحتوي على المفتاح. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

يحوّل قيمة XMP إلى تمثيل XML.

**Returns**

| النوع | الوصف |
| :- | :- |
| string | يرجع قيمة XMP المحوّلة إلى تمثيل XML. |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

إزالة القيمة بالمفتاح المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي تم التعرف عليه بالقيمة المُزالة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | يرجع true إذا تمت إزالة القيمة بالمفتاح المحدد. |


### Method: set_value(key, value) {#set_value_key_value_5}


```
 set_value(key, value) 
```

يضبط القيمة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي تم التعرف عليه بالقيمة المضافة. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | القيمة التي ستُضاف إليها. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_6}


```
 set_xmp_type_value(key, value) 
```

يضبط قيمة نوع XMP.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه بالقيمة المحددة. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | القيمة التي سيتم تعيينها. |

