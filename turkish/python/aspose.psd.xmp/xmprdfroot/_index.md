---
title: "XmpRdfRoot Sınıfı"
type: docs
weight: 460
url: /tr/python-net/aspose.psd.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | XmpRdfRoot sınıfının yeni bir örneğini başlatır |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Özniteliği ekler. |
| clear_attributes() | Tüm öznitelikleri kaldırır. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Özniteliği alır. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | Belirli bir önek ile ad alanı URI'sini alır. Önek xmlns olmadan başlayabilir. |
| [get_xml_value()](#get_xml_value__4) | xmp değerini xml temsiline dönüştürür. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | Önek ile ad alanı URI'si ekler. Önek xmlns olmadan başlayabilir. |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

XmpRdfRoot sınıfının yeni bir örneğini başlatır

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Özniteliği ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| öznitelik | string | Öznitelik. |
| değer | string | Değer. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Özniteliği alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| öznitelik | string | Öznitelik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Belirtilen öznitelik adı için özniteliği döndürür. |


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

Belirli bir önek ile ad alanı URI'sini alır. Önek xmlns olmadan başlayabilir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| önek | string | Önek. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Bir paket şema URI'si döndürür. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

xmp değerini xml temsiline dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | XMP değerini XML dizesine dönüştürülmüş olarak döndürür. |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

Önek ile ad alanı URI'si ekler. Önek xmlns olmadan başlayabilir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| önek | string | Önek. |
| namespace_uri | string | Paket şema uri'si. |

