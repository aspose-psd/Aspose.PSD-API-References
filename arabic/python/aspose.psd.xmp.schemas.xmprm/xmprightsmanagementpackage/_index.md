---
title: "الفئة XmpRightsManagementPackage"
type: docs
weight: 10
url: /ar/python-net/aspose.psd.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Summary:** Represents XMP Rights Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmprm](/psd/python-net/aspose.psd.xmp.schemas.xmprm/)

**Full Name:** aspose.psd.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__1) | يُنشئ نسخة جديدة من الفئة XmpRightsManagementPackage. |
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
| [set_certificate(certificate)](#set_certificate_certificate_5) | يضبط الشهادة. |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_6) | يُعلّم كمحتوى إدارة حقوق. |
| [set_owners(owners)](#set_owners_owners_7) | يضبط المالكين. |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_8) | يضبط شروط الاستخدام. |
| [set_value(key, value)](#set_value_key_value_9) | يضبط القيمة. |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_10) | يضبط بيان الويب. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_11) | يضبط قيمة نوع XMP. |


### Constructor: XmpRightsManagementPackage() {#XmpRightsManagementPackage__1}


```
 XmpRightsManagementPackage() 
```

يُنشئ نسخة جديدة من الفئة XmpRightsManagementPackage.

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


### Method: set_certificate(certificate) {#set_certificate_certificate_5}


```
 set_certificate(certificate) 
```

يضبط الشهادة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| شهادة | string | الشهادة. |

### Method: set_marked_as_right_management(value) {#set_marked_as_right_management_value_6}


```
 set_marked_as_right_management(value) 
```

يُعلّم كمحتوى إدارة حقوق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| قيمة | bool | إذا تم تعيينه إلى <c>true</c> فهذا مورد مُدار الحقوق. |

### Method: set_owners(owners) {#set_owners_owners_7}


```
 set_owners(owners) 
```

يضبط المالكين.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| المالكين | string | المالكون. |

### Method: set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_8}


```
 set_usage_terms(usage_terms) 
```

يضبط شروط الاستخدام.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| usage_terms | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | شروط الاستخدام. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

يضبط القيمة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي تم التعرف عليه بالقيمة المضافة. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | القيمة التي ستُضاف إليها. |

### Method: set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_10}


```
 set_web_statement(web_statement_url) 
```

يضبط بيان الويب.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| web_statement_url | string | عنوان URL للبيان الويب. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_11}


```
 set_xmp_type_value(key, value) 
```

يضبط قيمة نوع XMP.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه بالقيمة المحددة. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | القيمة التي سيتم تعيينها. |

