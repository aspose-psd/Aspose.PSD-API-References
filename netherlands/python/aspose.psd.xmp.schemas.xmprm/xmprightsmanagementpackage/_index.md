---
title: "XmpRightsManagementPackage Klasse"
type: docs
weight: 10
url: /nl/python-net/aspose.psd.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Summary:** Represents XMP Rights Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmprm](/psd/python-net/aspose.psd.xmp.schemas.xmprm/)

**Full Name:** aspose.psd.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__1) | Initialiseert een nieuw exemplaar van de XmpRightsManagementPackage klasse |
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
| [set_certificate(certificate)](#set_certificate_certificate_5) | Stelt het certificaat in. |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_6) | Markeert als rechtenbeheerinhoud |
| [set_owners(owners)](#set_owners_owners_7) | Stelt eigenaren in. |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_8) | Stelt de gebruiksvoorwaarden in. |
| [set_value(key, value)](#set_value_key_value_9) | Stelt de waarde in. |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_10) | Stelt de webverklaring in. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_11) | Stelt de XMP-typewaarde in. |


### Constructor: XmpRightsManagementPackage() {#XmpRightsManagementPackage__1}


```
 XmpRightsManagementPackage() 
```

Initialiseert een nieuw exemplaar van de XmpRightsManagementPackage klasse

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


### Method: set_certificate(certificate) {#set_certificate_certificate_5}


```
 set_certificate(certificate) 
```

Stelt het certificaat in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| certificaat | string | Het certificaat. |

### Method: set_marked_as_right_management(value) {#set_marked_as_right_management_value_6}


```
 set_marked_as_right_management(value) 
```

Markeert als rechtenbeheerinhoud

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | bool | Als ingesteld op <c>true</c> betekent dit dat het een rechtenbeheerde bron is. |

### Method: set_owners(owners) {#set_owners_owners_7}


```
 set_owners(owners) 
```

Stelt eigenaren in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| eigenaren | string | De eigenaren. |

### Method: set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_8}


```
 set_usage_terms(usage_terms) 
```

Stelt de gebruiksvoorwaarden in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| usage_terms | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | De gebruiksvoorwaarden. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Stelt de waarde in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de toegevoegde waarde. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | De waarde om aan toe te voegen. |

### Method: set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_10}


```
 set_web_statement(web_statement_url) 
```

Stelt de webverklaring in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| web_statement_url | string | De webverklaring URL. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_11}


```
 set_xmp_type_value(key, value) 
```

Stelt de XMP-typewaarde in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | string | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de ingestelde waarde. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | De waarde om in te stellen. |

