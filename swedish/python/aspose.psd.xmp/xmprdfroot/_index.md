---
title: "XmpRdfRoot-klass"
type: docs
weight: 460
url: /sv/python-net/aspose.psd.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | Initierar en ny instans av klassen XmpRdfRoot |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Lägger till attributet. |
| clear_attributes() | Tar bort alla attribut. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Hämtar attributet. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | Hämtar namnrymdens URI med ett specifikt prefix. Prefixet kan börja utan xmlns. |
| [get_xml_value()](#get_xml_value__4) | Konverterar xmp‑värde till xml‑representationen. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | Lägger till namnrymdens uri med prefix. Prefixet kan börja utan xmlns. |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

Initierar en ny instans av klassen XmpRdfRoot

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Lägger till attributet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribut | string | Attributet. |
| värde | string | Värdet. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Hämtar attributet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribut | string | Attributet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar attributet för angivet attributnamn. |


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

Hämtar namnrymdens URI med ett specifikt prefix. Prefixet kan börja utan xmlns.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| prefix | string | Prefixet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar ett paket-schema-URI. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Konverterar xmp‑värde till xml‑representationen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar XMP-värde konverterat till XML-sträng. |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

Lägger till namnrymdens uri med prefix. Prefixet kan börja utan xmlns.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| prefix | string | Prefixet. |
| namespace_uri | string | Paketets schemauri. |

