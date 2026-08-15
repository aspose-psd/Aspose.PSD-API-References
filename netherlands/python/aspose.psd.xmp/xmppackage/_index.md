---
title: "XmpPackage Klasse"
type: docs
weight: 430
url: /nl/python-net/aspose.psd.xmp/xmppackage/
---

**Summary:** Defines the XmpPackage class that represents base abstraction for XMP package.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackage

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Haalt de namespace-URI op. |
| voorvoegsel | string | r | Haalt het voorvoegsel op. |
| xml_namespace | string | r | Haalt de XML-namespace op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Voegt de waarde toe. |
| clear() | Maakt deze instantie leeg. |
| [contains_key(key)](#contains_key_key_2) | Bepaalt of de opgegeven sleutel de sleutel bevat. |
| [get_xml_value()](#get_xml_value__3) | Converteert XMP-waarde naar de XML-representatie. |
| [remove(key)](#remove_key_4) | Verwijder de waarde met de opgegeven sleutel. |
| [set_value(key, value)](#set_value_key_value_5) | Stelt de waarde in. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_6) | Stelt de XMP-typewaarde in. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Voegt de waarde toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de toegevoegde waarde. |
| value | string | De waarde om aan toe te voegen. |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

Bepaalt of de opgegeven sleutel de sleutel bevat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De te controleren sleutel. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Retourneert true als de opgegeven sleutel de sleutel bevat. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Converteert XMP-waarde naar de XML-representatie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Retourneert de XMP-waarde geconverteerd naar de XML-representatie. |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

Verwijder de waarde met de opgegeven sleutel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de verwijderde waarde. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Retourneert true als de waarde met de opgegeven sleutel is verwijderd. |


### Method: set_value(key, value) {#set_value_key_value_5}


```
 set_value(key, value) 
```

Stelt de waarde in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de toegevoegde waarde. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | De waarde om aan toe te voegen. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_6}


```
 set_xmp_type_value(key, value) 
```

Stelt de XMP-typewaarde in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de ingestelde waarde. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | De waarde om in te stellen. |

