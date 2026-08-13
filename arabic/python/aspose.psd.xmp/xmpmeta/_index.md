---
title: "فئة XmpMeta"
type: docs
weight: 410
url: /ar/python-net/aspose.psd.xmp/xmpmeta/
---

**Summary:** Represents xmpmeta. Optional.<br/>            The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpMeta

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [XmpMeta()](#XmpMeta__1) | ينشئ مثيلاً جديداً من الفئة [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/). |
| [XmpMeta(toolkit_version)](#XmpMeta_toolkit_version_2) | ينشئ مثيلاً جديداً من الفئة [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| adobe_xmp_toolkit | string | r/w | يحصل أو يضبط نسخة Adobe Xmp toolkit. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | يضيف السمة. |
| clear_attributes() | يزيل جميع السمات. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | يحصل على السمة. |
| [get_xml_value()](#get_xml_value__3) | يحوّل قيمة XMP إلى تمثيل XML. |


### Constructor: XmpMeta() {#XmpMeta__1}


```
 XmpMeta() 
```

ينشئ مثيلاً جديداً من الفئة [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/).

### Constructor: XmpMeta(toolkit_version) {#XmpMeta_toolkit_version_2}


```
 XmpMeta(toolkit_version) 
```

ينشئ مثيلاً جديداً من الفئة [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| toolkit_version | string | إصدار مجموعة أدوات Adobe XMP. |

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

يضيف السمة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| سمة | string | السمة. |
| قيمة | string | القيمة. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

يحصل على السمة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| سمة | string | السمة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| string | يعيد السمة لاسم السمة المحدد. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

يحوّل قيمة XMP إلى تمثيل XML.

**Returns**

| النوع | الوصف |
| :- | :- |
| string | يرجع قيمة XMP المحوّلة إلى تمثيل XML. |


