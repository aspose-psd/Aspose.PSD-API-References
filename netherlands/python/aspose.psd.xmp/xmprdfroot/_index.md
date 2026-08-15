---
title: "XmpRdfRoot klasse"
type: docs
weight: 460
url: /nl/python-net/aspose.psd.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | Initialiseert een nieuw exemplaar van de XmpRdfRoot-klasse |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Voegt het attribuut toe. |
| clear_attributes() | Verwijdert alle attributen. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Haalt het attribuut op. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | Haalt de namespace-URI op op basis van een specifieke prefix. Prefix kan beginnen zonder xmlns. |
| [get_xml_value()](#get_xml_value__4) | Converteert xmp-waarde naar de xml-weergave. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | Voegt een namespace-URI toe op basis van een prefix. Prefix kan beginnen zonder xmlns. |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

Initialiseert een nieuw exemplaar van de XmpRdfRoot-klasse

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Voegt het attribuut toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribuut | string | Het attribuut. |
| value | string | De value. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Haalt het attribuut op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribuut | string | Het attribuut. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Retourneert het attribuut voor opgegeven attribuutnaam. |


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

Haalt de namespace-URI op op basis van een specifieke prefix. Prefix kan beginnen zonder xmlns.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| voorvoegsel | string | Het voorvoegsel. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Retourneert een pakket‑schema‑URI. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Converteert xmp-waarde naar de xml-weergave.

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Retourneert XMP-waarde geconverteerd naar een XML‑string. |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

Voegt een namespace-URI toe op basis van een prefix. Prefix kan beginnen zonder xmlns.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| voorvoegsel | string | Het voorvoegsel. |
| namespace_uri | string | Pakket schema-URI. |

