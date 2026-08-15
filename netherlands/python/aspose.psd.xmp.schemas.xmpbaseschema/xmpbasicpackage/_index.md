---
title: "XmpBasicPackage Klasse"
type: docs
weight: 10
url: /nl/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.psd.xmp.schemas.xmpbaseschema](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.psd.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Initialiseert een nieuw exemplaar van de [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) klasse. |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Initialiseert een nieuw exemplaar van de [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | Maximum ratingwaarde. |
| RATING_MIN [static] | int | r | Minimum ratingwaarde. |
| RATING_REJECTED [static] | int | r | Afgewezen ratingwaarde. |
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
| [set_created_date(created_date)](#set_created_date_created_date_5) | Voegt de aanmaakdatum van de resource toe. |
| [set_created_date(created_date)](#set_created_date_created_date_6) | Voegt de aanmaakdatum van de resource toe. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_7) | Stelt het makerhulpmiddel in. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_8) | Stelt de identifier in. |
| [set_label(label)](#set_label_label_9) | Stelt het label in. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_10) | Voegt de datum van laatste wijziging van metadata toe. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_11) | Voegt de datum van laatste wijziging van metadata toe. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_12) | Voegt de datum van laatste wijziging van de resource toe. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_13) | Voegt de datum van laatste wijziging van de resource toe. |
| [set_rating(choise)](#set_rating_choise_14) | Stelt beoordeling in. |
| [set_value(key, value)](#set_value_key_value_15) | Stelt de waarde in. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_16) | Stelt de XMP-typewaarde in. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Initialiseert een nieuw exemplaar van de [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) klasse.

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Initialiseert een nieuw exemplaar van de [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| voorvoegsel | string | Het voorvoegsel. |
| namespace_uri | string | De namespace-URI. |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_5}


```
 set_created_date(created_date) 
```

Voegt de aanmaakdatum van de resource toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| created_date | datetime | Aangemaakte datum. |

### Method: set_created_date(created_date) {#set_created_date_created_date_6}


```
 set_created_date(created_date) 
```

Voegt de aanmaakdatum van de resource toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| created_date | string | Aangemaakte datum. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_7}


```
 set_creator_tool(creator_tool) 
```

Stelt het makerhulpmiddel in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| creator_tool | string | Naam van tool. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_8}


```
 set_identifier(idenfifier) 
```

Stelt de identifier in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| idenfifier | string | De idenfifier. |

### Method: set_label(label) {#set_label_label_9}


```
 set_label(label) 
```

Stelt het label in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| label | string | Het label. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_10}


```
 set_metadata_date(metadata_date) 
```

Voegt de datum van laatste wijziging van metadata toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| metadata_date | datetime | Metadata datum. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_11}


```
 set_metadata_date(metadata_date) 
```

Voegt de datum van laatste wijziging van metadata toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| metadata_date | string | Metadata datum. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_12}


```
 set_modify_date(modified_date) 
```

Voegt de datum van laatste wijziging van de resource toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| modified_date | datetime | Laatst gewijzigde datum. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_13}


```
 set_modify_date(modified_date) 
```

Voegt de datum van laatste wijziging van de resource toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| modified_date | string | Laatst gewijzigde datum. |

### Method: set_rating(choise) {#set_rating_choise_14}


```
 set_rating(choise) 
```

Stelt beoordeling in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| choise | int | Van -1 tot 5 |

### Method: set_value(key, value) {#set_value_key_value_15}


```
 set_value(key, value) 
```

Stelt de waarde in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de toegevoegde waarde. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | De waarde om aan toe te voegen. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_16}


```
 set_xmp_type_value(key, value) 
```

Stelt de XMP-typewaarde in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de ingestelde waarde. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | De waarde om in te stellen. |

