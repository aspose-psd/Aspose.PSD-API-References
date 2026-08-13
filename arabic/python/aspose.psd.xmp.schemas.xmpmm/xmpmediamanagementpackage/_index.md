---
title: "XmpMediaManagementPackage فئة"
type: docs
weight: 10
url: /ar/python-net/aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmpmm](/psd/python-net/aspose.psd.xmp.schemas.xmpmm/)

**Full Name:** aspose.psd.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | يُنشئ مثيلًا جديدًا من فئة XmpMediaManagementPackage |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
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
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_5) | يضبط المستمد من. |
| [set_document_id(guid)](#set_document_id_guid_6) | يضبط معرف المستند. |
| [set_document_id(guid)](#set_document_id_guid_7) | يضبط معرف المستند. |
| [set_instance_id(guid)](#set_instance_id_guid_8) | يضبط معرف المثيل. |
| [set_instance_id(guid)](#set_instance_id_guid_9) | يضبط معرف المثيل. |
| [set_original_document_id(guid)](#set_original_document_id_guid_10) | يضبط معرف المستند الأصلي. |
| [set_original_document_id(guid)](#set_original_document_id_guid_11) | يضبط معرف المستند الأصلي. |
| [set_value(key, value)](#set_value_key_value_12) | يضبط القيمة. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_13) | يضبط قيمة نوع XMP. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

يُنشئ مثيلًا جديدًا من فئة XmpMediaManagementPackage

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


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_5}


```
 set_derived_from(resource_ref) 
```

يضبط المستمد من.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| resource_ref | [ResourceRef](/psd/python-net/aspose.psd.xmp.types.complex.resourceref/resourceref/) | مرجع المورد. |

### Method: set_document_id(guid) {#set_document_id_guid_6}


```
 set_document_id(guid) 
```

يضبط معرف المستند.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| guid | Guid | المعرف الفريد. |

### Method: set_document_id(guid) {#set_document_id_guid_7}


```
 set_document_id(guid) 
```

يضبط معرف المستند.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| guid | string | المعرف الفريد. |

### Method: set_instance_id(guid) {#set_instance_id_guid_8}


```
 set_instance_id(guid) 
```

يضبط معرف المثيل.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| guid | Guid | المعرف الفريد. |

### Method: set_instance_id(guid) {#set_instance_id_guid_9}


```
 set_instance_id(guid) 
```

يضبط معرف المثيل.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| guid | string | المعرف الفريد. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_10}


```
 set_original_document_id(guid) 
```

يضبط معرف المستند الأصلي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| guid | Guid | المعرف الفريد. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_11}


```
 set_original_document_id(guid) 
```

يضبط معرف المستند الأصلي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| guid | string | المعرف الفريد. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

يضبط القيمة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي تم التعرف عليه بالقيمة المضافة. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | القيمة التي ستُضاف إليها. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_13}


```
 set_xmp_type_value(key, value) 
```

يضبط قيمة نوع XMP.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه بالقيمة المحددة. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | القيمة التي سيتم تعيينها. |

