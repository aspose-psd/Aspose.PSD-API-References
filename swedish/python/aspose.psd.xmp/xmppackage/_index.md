---
title: "XmpPackage‑klass"
type: docs
weight: 430
url: /sv/python-net/aspose.psd.xmp/xmppackage/
---

**Summary:** Defines the XmpPackage class that represents base abstraction for XMP package.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackage

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Hämtar namnrymdens URI. |
| prefix | string | r | Hämtar prefixet. |
| xml_namespace | string | r | Hämtar XML‑namnrymden. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Lägger till värdet. |
| clear() | Rensar denna instans. |
| [contains_key(key)](#contains_key_key_2) | Bestämmer om den angivna nyckeln innehåller nyckeln. |
| [get_xml_value()](#get_xml_value__3) | Konverterar XMP‑värde till XML‑representationen. |
| [remove(key)](#remove_key_4) | Tar bort värdet med den angivna nyckeln. |
| [set_value(key, value)](#set_value_key_value_5) | Ställer in värdet. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_6) | Ställer in XMP‑typvärdet. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Lägger till värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Strängrepresentationen av nyckeln som identifieras med tillagt värde. |
| värde | string | Värdet att lägga till. |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

Bestämmer om den angivna nyckeln innehåller nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Nyckeln som ska kontrolleras. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Returnerar true om den angivna nyckeln innehåller nyckeln. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Konverterar XMP‑värde till XML‑representationen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar XMP-värdet konverterat till XML-representationen. |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

Tar bort värdet med den angivna nyckeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Strängrepresentationen av nyckeln som identifieras med borttaget värde. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Returnerar true om värdet med den angivna nyckeln togs bort. |


### Method: set_value(key, value) {#set_value_key_value_5}


```
 set_value(key, value) 
```

Ställer in värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Strängrepresentationen av nyckeln som identifieras med tillagt värde. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Värdet att lägga till. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_6}


```
 set_xmp_type_value(key, value) 
```

Ställer in XMP‑typvärdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Strängrepresentationen av nyckeln som identifieras med satt värde. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Värdet att sätta till. |

