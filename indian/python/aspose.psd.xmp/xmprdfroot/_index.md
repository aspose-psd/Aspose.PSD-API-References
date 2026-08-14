---
title: "XmpRdfRoot क्लास"
type: docs
weight: 460
url: /hi/python-net/aspose.psd.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | XmpRdfRoot क्लास का नया उदाहरण प्रारंभ करता है |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | गुण जोड़ता है। |
| clear_attributes() | सभी विशेषताओं को हटाता है। |
| [get_attribute(attribute)](#get_attribute_attribute_2) | विशेषता प्राप्त करता है। |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | विशिष्ट उपसर्ग द्वारा नेमस्पेस URI प्राप्त करता है। उपसर्ग बिना xmlns के शुरू हो सकता है। |
| [get_xml_value()](#get_xml_value__4) | xmp मान को xml प्रतिनिधित्व में परिवर्तित करता है। |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | उपसर्ग द्वारा नेमस्पेस URI जोड़ता है। उपसर्ग बिना xmlns के शुरू हो सकता है। |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

XmpRdfRoot क्लास का नया उदाहरण प्रारंभ करता है

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

गुण जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| विशेषता | string | यह विशेषता। |
| value | string | मान। |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

विशेषता प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| विशेषता | string | यह विशेषता। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | निर्दिष्ट विशेषता नाम के लिए विशेषता लौटाता है। |


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

विशिष्ट उपसर्ग द्वारा नेमस्पेस URI प्राप्त करता है। उपसर्ग बिना xmlns के शुरू हो सकता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| उपसर्ग | string | उपसर्ग। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | पैकेज स्कीमा URI लौटाता है। |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

xmp मान को xml प्रतिनिधित्व में परिवर्तित करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | XMP मान को XML स्ट्रिंग में परिवर्तित करके लौटाता है। |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

उपसर्ग द्वारा नेमस्पेस URI जोड़ता है। उपसर्ग बिना xmlns के शुरू हो सकता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| उपसर्ग | string | उपसर्ग। |
| namespace_uri | string | पैकेज स्कीमा URI। |

