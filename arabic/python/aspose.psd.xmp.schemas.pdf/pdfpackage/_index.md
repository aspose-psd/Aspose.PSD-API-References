---
title: "فئة PdfPackage"
type: docs
weight: 10
url: /ar/python-net/aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.psd.xmp.schemas.pdf](/psd/python-net/aspose.psd.xmp.schemas.pdf/)

**Full Name:** aspose.psd.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | يُنشئ مثيلًا جديدًا من فئة PdfPackage |
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
| [set_keywords(keywords)](#set_keywords_keywords_5) | يضبط الكلمات المفتاحية. |
| [set_pdf_version(version)](#set_pdf_version_version_6) | يضبط إصدار PDF. |
| [set_producer(producer)](#set_producer_producer_7) | يضبط اسم الأداة التي أنشأت ملف PDF. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_8) | يضبط قيمة trapped. |
| [set_value(key, value)](#set_value_key_value_9) | يضبط القيمة. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | يضبط قيمة نوع XMP. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

يُنشئ مثيلًا جديدًا من فئة PdfPackage

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


### Method: set_keywords(keywords) {#set_keywords_keywords_5}


```
 set_keywords(keywords) 
```

يضبط الكلمات المفتاحية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| الكلمات المفتاحية | string | الكلمات المفتاحية. |

### Method: set_pdf_version(version) {#set_pdf_version_version_6}


```
 set_pdf_version(version) 
```

يضبط إصدار PDF.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| version | string | إصدار PDF، على سبيل المثال: 1.0، 1.3 إلخ. |

### Method: set_producer(producer) {#set_producer_producer_7}


```
 set_producer(producer) 
```

يضبط اسم الأداة التي أنشأت ملف PDF.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| المنتج | string | اسم المنتج. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_8}


```
 set_trapped(is_trapped) 
```

يضبط قيمة trapped.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| is_trapped | bool | إذا تم ضبطه على <c>true</c> فإن المستند تم حجزه. |

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

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

يضبط قيمة نوع XMP.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key | string | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه بالقيمة المحددة. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | القيمة التي سيتم تعيينها. |

