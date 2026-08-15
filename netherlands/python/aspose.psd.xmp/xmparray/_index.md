---
title: "XmpArray klasse"
type: docs
weight: 290
url: /nl/python-net/aspose.psd.xmp/xmparray/
---

**Summary:** Represents Xmp Array in [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/). TODO: Array may contain complex data.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpArray

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [XmpArray(type)](#XmpArray_type_1) | Initialiseert een nieuw exemplaar van de [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) klasse. |
| [XmpArray(type, items)](#XmpArray_type_items_2) | Initialiseert een nieuw exemplaar van de [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| values | string | r | Haalt array van waarden op binnen [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/). |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_item(item)](#add_item_item_1) | Voegt nieuw item toe. |
| [get_xml_value()](#get_xml_value__2) | Converteert XMP-waarde naar de XML-representatie. |


### Constructor: XmpArray(type) {#XmpArray_type_1}


```
 XmpArray(type) 
```

Initialiseert een nieuw exemplaar van de [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [XmpArrayType](/psd/python-net/aspose.psd.xmp/xmparraytype) | Het type van de array. |

### Constructor: XmpArray(type, items) {#XmpArray_type_items_2}


```
 XmpArray(type, items) 
```

Initialiseert een nieuw exemplaar van de [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [XmpArrayType](/psd/python-net/aspose.psd.xmp/xmparraytype) | Het type van de array. |
| items | string | De itemslijst. |

### Method: add_item(item) {#add_item_item_1}


```
 add_item(item) 
```

Voegt nieuw item toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| item | string | Het item dat moet worden toegevoegd aan de lijst met items. |

### Method: get_xml_value() {#get_xml_value__2}


```
 get_xml_value() 
```

Converteert XMP-waarde naar de XML-representatie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Retourneert de XMP-waarde geconverteerd naar de XML-representatie. |


