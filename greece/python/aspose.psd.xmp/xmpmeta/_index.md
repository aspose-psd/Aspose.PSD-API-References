---
title: "XmpMeta Κλάση"
type: docs
weight: 410
url: /el/python-net/aspose.psd.xmp/xmpmeta/
---

**Summary:** Represents xmpmeta. Optional.<br/>            The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpMeta

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [XmpMeta()](#XmpMeta__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/). |
| [XmpMeta(toolkit_version)](#XmpMeta_toolkit_version_2) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| adobe_xmp_toolkit | string | r/w | Λαμβάνει ή ορίζει την έκδοση του Adobe Xmp toolkit. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Προσθέτει το χαρακτηριστικό. |
| clear_attributes() | Αφαιρεί όλα τα χαρακτηριστικά. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Λαμβάνει το χαρακτηριστικό. |
| [get_xml_value()](#get_xml_value__3) | Μετατρέπει την τιμή XMP στην αναπαράσταση XML. |


### Constructor: XmpMeta() {#XmpMeta__1}


```
 XmpMeta() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/).

### Constructor: XmpMeta(toolkit_version) {#XmpMeta_toolkit_version_2}


```
 XmpMeta(toolkit_version) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| toolkit_version | string | Έκδοση του Adobe XMP toolkit. |

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


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Μετατρέπει την τιμή XMP στην αναπαράσταση XML.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Επιστρέφει την τιμή XMP μετατρεπόμενη στην αναπαράσταση XML. |


