---
title: "فئة XmpRdfRoot"
type: docs
weight: 460
url: /ar/python-net/aspose.psd.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | يُنشئ مثيلًا جديدًا من الفئة XmpRdfRoot |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | يضيف السمة. |
| clear_attributes() | يزيل جميع السمات. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | يحصل على السمة. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | يحصل على URI مساحة الاسم وفقًا للبادئة المحددة. قد تبدأ البادئة بدون xmlns. |
| [get_xml_value()](#get_xml_value__4) | يحوّل قيمة xmp إلى تمثيل xml. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | يضيف URI مساحة الاسم وفقًا للبادئة. قد تبدأ البادئة بدون xmlns. |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

يُنشئ مثيلًا جديدًا من الفئة XmpRdfRoot

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


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

يحصل على URI مساحة الاسم وفقًا للبادئة المحددة. قد تبدأ البادئة بدون xmlns.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| بادئة | string | البادئة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| string | يعيد URI مخطط الحزمة. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

يحوّل قيمة xmp إلى تمثيل xml.

**Returns**

| النوع | الوصف |
| :- | :- |
| string | يعيد قيمة XMP محوّلة إلى سلسلة XML. |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

يضيف URI مساحة الاسم وفقًا للبادئة. قد تبدأ البادئة بدون xmlns.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| بادئة | string | البادئة. |
| namespace_uri | string | URI مخطط الحزمة. |

