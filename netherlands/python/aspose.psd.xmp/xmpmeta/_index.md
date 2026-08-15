---
title: "XmpMeta Klasse"
type: docs
weight: 410
url: /nl/python-net/aspose.psd.xmp/xmpmeta/
---

**Summary:** Represents xmpmeta. Optional.<br/>            The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpMeta

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [XmpMeta()](#XmpMeta__1) | Initialiseert een nieuw exemplaar van de [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) klasse. |
| [XmpMeta(toolkit_version)](#XmpMeta_toolkit_version_2) | Initialiseert een nieuw exemplaar van de [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| adobe_xmp_toolkit | string | r/w | Haalt op of stelt de Adobe Xmp toolkit-versie in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Voegt het attribuut toe. |
| clear_attributes() | Verwijdert alle attributen. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Haalt het attribuut op. |
| [get_xml_value()](#get_xml_value__3) | Converteert XMP-waarde naar de XML-representatie. |


### Constructor: XmpMeta() {#XmpMeta__1}


```
 XmpMeta() 
```

Initialiseert een nieuw exemplaar van de [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) klasse.

### Constructor: XmpMeta(toolkit_version) {#XmpMeta_toolkit_version_2}


```
 XmpMeta(toolkit_version) 
```

Initialiseert een nieuw exemplaar van de [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| toolkit_version | string | Adobe XMP toolkit versie. |

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


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Converteert XMP-waarde naar de XML-representatie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Retourneert de XMP-waarde geconverteerd naar de XML-representatie. |


