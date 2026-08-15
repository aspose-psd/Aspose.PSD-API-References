---
title: "XmpMediaManagementPackage klass"
type: docs
weight: 10
url: /sv/python-net/aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmpmm](/psd/python-net/aspose.psd.xmp.schemas.xmpmm/)

**Full Name:** aspose.psd.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | Initierar en ny instans av XmpMediaManagementPackage klass |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Hämtar namnrymdens URI. |
| prefix | string | r | Hämtar prefixet. |
| xml_namespace | string | r | Hämtar XML‑namnrymden. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Lägger till en strängegenskap. |
| clear() | Rensar denna instans. |
| [contains_key(key)](#contains_key_key_2) | Bestämmer om den angivna nyckeln innehåller nyckeln. |
| [get_xml_value()](#get_xml_value__3) | Konverterar XMP‑värde till XML‑representationen. |
| [remove(key)](#remove_key_4) | Tar bort värdet med den angivna nyckeln. |
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_5) | Ställer in den härledda från. |
| [set_document_id(guid)](#set_document_id_guid_6) | Ställer in dokumentidentifieraren. |
| [set_document_id(guid)](#set_document_id_guid_7) | Ställer in dokumentidentifieraren. |
| [set_instance_id(guid)](#set_instance_id_guid_8) | Ställer in instans-ID. |
| [set_instance_id(guid)](#set_instance_id_guid_9) | Ställer in instans-ID. |
| [set_original_document_id(guid)](#set_original_document_id_guid_10) | Ställer in det ursprungliga dokument-ID:t. |
| [set_original_document_id(guid)](#set_original_document_id_guid_11) | Ställer in det ursprungliga dokument-ID:t. |
| [set_value(key, value)](#set_value_key_value_12) | Ställer in värdet. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_13) | Ställer in XMP‑typvärdet. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

Initierar en ny instans av XmpMediaManagementPackage klass

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Lägger till en strängegenskap.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Strängrepresentationen av nyckeln som identifieras med tillagt värde. |
| värde | string | Strängvärdet. |

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


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_5}


```
 set_derived_from(resource_ref) 
```

Ställer in den härledda från.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| resource_ref | [ResourceRef](/psd/python-net/aspose.psd.xmp.types.complex.resourceref/resourceref/) | Resursreferensen. |

### Method: set_document_id(guid) {#set_document_id_guid_6}


```
 set_document_id(guid) 
```

Ställer in dokumentidentifieraren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| guid | Guid | Den unika identifieraren. |

### Method: set_document_id(guid) {#set_document_id_guid_7}


```
 set_document_id(guid) 
```

Ställer in dokumentidentifieraren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| guid | string | Den unika identifieraren. |

### Method: set_instance_id(guid) {#set_instance_id_guid_8}


```
 set_instance_id(guid) 
```

Ställer in instans-ID.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| guid | Guid | Den unika identifieraren. |

### Method: set_instance_id(guid) {#set_instance_id_guid_9}


```
 set_instance_id(guid) 
```

Ställer in instans-ID.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| guid | string | Den unika identifieraren. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_10}


```
 set_original_document_id(guid) 
```

Ställer in det ursprungliga dokument-ID:t.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| guid | Guid | Den unika identifieraren. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_11}


```
 set_original_document_id(guid) 
```

Ställer in det ursprungliga dokument-ID:t.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| guid | string | Den unika identifieraren. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Ställer in värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Strängrepresentationen av nyckeln som identifieras med tillagt värde. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Värdet att lägga till. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_13}


```
 set_xmp_type_value(key, value) 
```

Ställer in XMP‑typvärdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Strängrepresentationen av nyckeln som identifieras med satt värde. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Värdet att sätta till. |

