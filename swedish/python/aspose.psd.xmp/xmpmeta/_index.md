---
title: "XmpMeta-klass"
type: docs
weight: 410
url: /sv/python-net/aspose.psd.xmp/xmpmeta/
---

**Summary:** Represents xmpmeta. Optional.<br/>            The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpMeta

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [XmpMeta()](#XmpMeta__1) | Initierar en ny instans av klassen [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/). |
| [XmpMeta(toolkit_version)](#XmpMeta_toolkit_version_2) | Initierar en ny instans av klassen [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| adobe_xmp_toolkit | string | r/w | Hämtar eller anger Adobe Xmp-verktygsversion. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Lägger till attributet. |
| clear_attributes() | Tar bort alla attribut. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Hämtar attributet. |
| [get_xml_value()](#get_xml_value__3) | Konverterar XMP‑värde till XML‑representationen. |


### Constructor: XmpMeta() {#XmpMeta__1}


```
 XmpMeta() 
```

Initierar en ny instans av klassen [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/).

### Constructor: XmpMeta(toolkit_version) {#XmpMeta_toolkit_version_2}


```
 XmpMeta(toolkit_version) 
```

Initierar en ny instans av klassen [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| toolkit_version | string | Adobe XMP-verktygsversion. |

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


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Konverterar XMP‑värde till XML‑representationen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar XMP-värdet konverterat till XML-representationen. |


