---
title: "XmpMediaManagementPackage Klasse"
type: docs
weight: 10
url: /nl/python-net/aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmpmm](/psd/python-net/aspose.psd.xmp.schemas.xmpmm/)

**Full Name:** aspose.psd.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | Initialiseert een nieuw exemplaar van de XmpMediaManagementPackage klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Haalt de namespace-URI op. |
| voorvoegsel | string | r | Haalt het voorvoegsel op. |
| xml_namespace | string | r | Haalt de XML-namespace op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Voegt een stringeigenschap toe. |
| clear() | Maakt deze instantie leeg. |
| [contains_key(key)](#contains_key_key_2) | Bepaalt of de opgegeven sleutel de sleutel bevat. |
| [get_xml_value()](#get_xml_value__3) | Converteert XMP-waarde naar de XML-representatie. |
| [remove(key)](#remove_key_4) | Verwijder de waarde met de opgegeven sleutel. |
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_5) | Stelt de afgeleide van in. |
| [set_document_id(guid)](#set_document_id_guid_6) | Stelt de documentidentificatie in. |
| [set_document_id(guid)](#set_document_id_guid_7) | Stelt de documentidentificatie in. |
| [set_instance_id(guid)](#set_instance_id_guid_8) | Stelt instantie-id in. |
| [set_instance_id(guid)](#set_instance_id_guid_9) | Stelt instantie-id in. |
| [set_original_document_id(guid)](#set_original_document_id_guid_10) | Stelt de originele document-id in. |
| [set_original_document_id(guid)](#set_original_document_id_guid_11) | Stelt de originele document-id in. |
| [set_value(key, value)](#set_value_key_value_12) | Stelt de waarde in. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_13) | Stelt de XMP-typewaarde in. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

Initialiseert een nieuw exemplaar van de XmpMediaManagementPackage klasse

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Voegt een stringeigenschap toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de toegevoegde waarde. |
| value | string | De tekenreekswaarde. |

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


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_5}


```
 set_derived_from(resource_ref) 
```

Stelt de afgeleide van in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| resource_ref | [ResourceRef](/psd/python-net/aspose.psd.xmp.types.complex.resourceref/resourceref/) | De resource-referentie. |

### Method: set_document_id(guid) {#set_document_id_guid_6}


```
 set_document_id(guid) 
```

Stelt de documentidentificatie in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| guid | Guid | De unieke identifier. |

### Method: set_document_id(guid) {#set_document_id_guid_7}


```
 set_document_id(guid) 
```

Stelt de documentidentificatie in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| guid | string | De unieke identifier. |

### Method: set_instance_id(guid) {#set_instance_id_guid_8}


```
 set_instance_id(guid) 
```

Stelt instantie-id in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| guid | Guid | De unieke identifier. |

### Method: set_instance_id(guid) {#set_instance_id_guid_9}


```
 set_instance_id(guid) 
```

Stelt instantie-id in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| guid | string | De unieke identifier. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_10}


```
 set_original_document_id(guid) 
```

Stelt de originele document-id in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| guid | Guid | De unieke identifier. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_11}


```
 set_original_document_id(guid) 
```

Stelt de originele document-id in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| guid | string | De unieke identifier. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Stelt de waarde in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de toegevoegde waarde. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | De waarde om aan toe te voegen. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_13}


```
 set_xmp_type_value(key, value) 
```

Stelt de XMP-typewaarde in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de ingestelde waarde. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | De waarde om in te stellen. |

