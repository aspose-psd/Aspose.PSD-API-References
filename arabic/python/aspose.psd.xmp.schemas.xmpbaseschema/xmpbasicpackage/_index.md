---
title: "فئة XmpBasicPackage"
type: docs
weight: 10
url: /ar/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.psd.xmp.schemas.xmpbaseschema](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.psd.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | يُنشئ مثلاً جديداً من الفئة [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/). |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | يُنشئ مثلاً جديداً من الفئة [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | قيمة الحد الأقصى للتقييم. |
| RATING_MIN [static] | int | r | قيمة الحد الأدنى للتقييم. |
| RATING_REJECTED [static] | int | r | قيمة التقييم المرفوض. |
| namespace_uri | string | r | يحصل على URI للمساحة الاسمية. |
| بادئة | string | r | يحصل على البادئة. |
| xml_namespace | string | r | يحصل على مساحة الاسم XML. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | يضيف خاصية نصية. |
| clear() | يمسح هذا الكائن. |
| [contains_key(key)](#contains_key_key_2) | يحدد ما إذا كان المفتاح المحدد يحتوي على المفتاح. |
| [get_xml_value()](#get_xml_value__3) | يحوّل قيمة XMP إلى تمثيل XML. |
| [remove(key)](#remove_key_4) | إزالة القيمة بالمفتاح المحدد. |
| [set_created_date(created_date)](#set_created_date_created_date_5) | يضيف تاريخ إنشاء المورد. |
| [set_created_date(created_date)](#set_created_date_created_date_6) | يضيف تاريخ إنشاء المورد. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_7) | يضبط أداة الإنشاء. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_8) | يضبط المعرف. |
| [set_label(label)](#set_label_label_9) | يضبط التسمية. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_10) | يضيف تاريخ آخر تعديل للبيانات الوصفية. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_11) | يضيف تاريخ آخر تعديل للبيانات الوصفية. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_12) | يضيف تاريخ آخر تعديل للمورد. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_13) | يضيف تاريخ آخر تعديل للمورد. |
| [set_rating(choise)](#set_rating_choise_14) | يضبط التقييم. |
| [set_value(key, value)](#set_value_key_value_15) | يضبط القيمة. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_16) | يضبط قيمة نوع XMP. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

يُنشئ مثلاً جديداً من الفئة [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/).

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

يُنشئ مثلاً جديداً من الفئة [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| بادئة | string | البادئة. |
| namespace_uri | string | معرف URI للمساحة الاسمية. |

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

يضيف خاصية نصية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي تم التعرف عليه بالقيمة المضافة. |
| قيمة | string | قيمة السلسلة. |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_5}


```
 set_created_date(created_date) 
```

يضيف تاريخ إنشاء المورد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| created_date | datetime | تاريخ الإنشاء. |

### Method: set_created_date(created_date) {#set_created_date_created_date_6}


```
 set_created_date(created_date) 
```

يضيف تاريخ إنشاء المورد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| created_date | string | تاريخ الإنشاء. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_7}


```
 set_creator_tool(creator_tool) 
```

يضبط أداة الإنشاء.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| creator_tool | string | اسم الأداة. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_8}


```
 set_identifier(idenfifier) 
```

يضبط المعرف.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| معرف | string | المعرف. |

### Method: set_label(label) {#set_label_label_9}


```
 set_label(label) 
```

يضبط التسمية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تسمية | string | التسمية. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_10}


```
 set_metadata_date(metadata_date) 
```

يضيف تاريخ آخر تعديل للبيانات الوصفية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| metadata_date | datetime | تاريخ البيانات الوصفية. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_11}


```
 set_metadata_date(metadata_date) 
```

يضيف تاريخ آخر تعديل للبيانات الوصفية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| metadata_date | string | تاريخ البيانات الوصفية. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_12}


```
 set_modify_date(modified_date) 
```

يضيف تاريخ آخر تعديل للمورد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| modified_date | datetime | تاريخ آخر تعديل. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_13}


```
 set_modify_date(modified_date) 
```

يضيف تاريخ آخر تعديل للمورد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| modified_date | string | تاريخ آخر تعديل. |

### Method: set_rating(choise) {#set_rating_choise_14}


```
 set_rating(choise) 
```

يضبط التقييم.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| اختيار | int | من -1 إلى 5 |

### Method: set_value(key, value) {#set_value_key_value_15}


```
 set_value(key, value) 
```

يضبط القيمة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي تم التعرف عليه بالقيمة المضافة. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | القيمة التي ستُضاف إليها. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_16}


```
 set_xmp_type_value(key, value) 
```

يضبط قيمة نوع XMP.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه بالقيمة المحددة. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | القيمة التي سيتم تعيينها. |

