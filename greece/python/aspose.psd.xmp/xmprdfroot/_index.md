---
title: "XmpRdfRoot Κλάση"
type: docs
weight: 460
url: /el/python-net/aspose.psd.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης XmpRdfRoot |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Προσθέτει το χαρακτηριστικό. |
| clear_attributes() | Αφαιρεί όλα τα χαρακτηριστικά. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Λαμβάνει το χαρακτηριστικό. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | Λαμβάνει το URI του χώρου ονομάτων με συγκεκριμένο πρόθεμα. Το πρόθεμα μπορεί να ξεκινά χωρίς xmlns. |
| [get_xml_value()](#get_xml_value__4) | Μετατρέπει την τιμή xmp στην αναπαράσταση xml. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | Προσθέτει το URI του χώρου ονομάτων με πρόθεμα. Το πρόθεμα μπορεί να ξεκινά χωρίς xmlns. |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης XmpRdfRoot

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Προσθέτει το χαρακτηριστικό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| χαρακτηριστικό | string | Το χαρακτηριστικό. |
| value | string | Η value. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Λαμβάνει το χαρακτηριστικό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| χαρακτηριστικό | string | Το χαρακτηριστικό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Επιστρέφει το χαρακτηριστικό για το συγκεκριμένο όνομα χαρακτηριστικού. |


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

Λαμβάνει το URI του χώρου ονομάτων με συγκεκριμένο πρόθεμα. Το πρόθεμα μπορεί να ξεκινά χωρίς xmlns.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| πρόθεμα | string | Το πρόθεμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Επιστρέφει ένα URI σχήματος πακέτου. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Μετατρέπει την τιμή xmp στην αναπαράσταση xml.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Επιστρέφει την τιμή XMP μετατρεπόμενη σε συμβολοσειρά XML. |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

Προσθέτει το URI του χώρου ονομάτων με πρόθεμα. Το πρόθεμα μπορεί να ξεκινά χωρίς xmlns.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| πρόθεμα | string | Το πρόθεμα. |
| namespace_uri | string | URI σχήματος πακέτου. |

