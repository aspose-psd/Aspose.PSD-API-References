---
title: "XmpArray Klasse"
type: docs
weight: 290
url: /de/python-net/aspose.psd.xmp/xmparray/
---

**Summary:** Represents Xmp Array in [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/). TODO: Array may contain complex data.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpArray

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [XmpArray(type)](#XmpArray_type_1) | Initialisiert eine neue Instanz der [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) Klasse. |
| [XmpArray(type, items)](#XmpArray_type_items_2) | Initialisiert eine neue Instanz der [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| values | string | r | Gibt ein Array von Werten innerhalb von [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/). |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_item(item)](#add_item_item_1) | Fügt ein neues Element hinzu. |
| [get_xml_value()](#get_xml_value__2) | Konvertiert den XMP-Wert in die XML-Darstellung |


### Constructor: XmpArray(type) {#XmpArray_type_1}


```
 XmpArray(type) 
```

Initialisiert eine neue Instanz der [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [XmpArrayType](/psd/python-net/aspose.psd.xmp/xmparraytype) | Der Typ des Arrays. |

### Constructor: XmpArray(type, items) {#XmpArray_type_items_2}


```
 XmpArray(type, items) 
```

Initialisiert eine neue Instanz der [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [XmpArrayType](/psd/python-net/aspose.psd.xmp/xmparraytype) | Der Typ des Arrays. |
| Elemente | string | Die Elementeliste. |

### Method: add_item(item) {#add_item_item_1}


```
 add_item(item) 
```

Fügt ein neues Element hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Element | string | Das Element, das zur Liste der Elemente hinzugefügt werden soll. |

### Method: get_xml_value() {#get_xml_value__2}


```
 get_xml_value() 
```

Konvertiert den XMP-Wert in die XML-Darstellung

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt den XMP-Wert zurück, konvertiert in die XML-Darstellung |


