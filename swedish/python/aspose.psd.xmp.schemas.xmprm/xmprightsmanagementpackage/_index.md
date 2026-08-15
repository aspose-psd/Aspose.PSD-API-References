---
title: "XmpRightsManagementPackage‑klass"
type: docs
weight: 10
url: /sv/python-net/aspose.psd.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Summary:** Represents XMP Rights Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmprm](/psd/python-net/aspose.psd.xmp.schemas.xmprm/)

**Full Name:** aspose.psd.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__1) | Initierar en ny instans av klassen XmpRightsManagementPackage |
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
| [set_certificate(certificate)](#set_certificate_certificate_5) | Ställer in certifikatet. |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_6) | Markerar som rättighetsstyrt innehåll |
| [set_owners(owners)](#set_owners_owners_7) | Ställer in ägare. |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_8) | Ställer in användningsvillkoren. |
| [set_value(key, value)](#set_value_key_value_9) | Ställer in värdet. |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_10) | Ställer in webb‑uttalandet. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_11) | Ställer in XMP‑typvärdet. |


### Constructor: XmpRightsManagementPackage() {#XmpRightsManagementPackage__1}


```
 XmpRightsManagementPackage() 
```

Initierar en ny instans av klassen XmpRightsManagementPackage

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


### Method: set_certificate(certificate) {#set_certificate_certificate_5}


```
 set_certificate(certificate) 
```

Ställer in certifikatet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| certifikat | string | Certifikatet. |

### Method: set_marked_as_right_management(value) {#set_marked_as_right_management_value_6}


```
 set_marked_as_right_management(value) 
```

Markerar som rättighetsstyrt innehåll

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | bool | om inställt på <c>true</c> betyder det att detta är en rättighetsstyrd resurs. |

### Method: set_owners(owners) {#set_owners_owners_7}


```
 set_owners(owners) 
```

Ställer in ägare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ägare | string | Ägarna. |

### Method: set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_8}


```
 set_usage_terms(usage_terms) 
```

Ställer in användningsvillkoren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| usage_terms | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | Användarvillkoren. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Ställer in värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Strängrepresentationen av nyckeln som identifieras med tillagt värde. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Värdet att lägga till. |

### Method: set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_10}


```
 set_web_statement(web_statement_url) 
```

Ställer in webb‑uttalandet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| web_statement_url | string | Webbuttalande-URL:en. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_11}


```
 set_xmp_type_value(key, value) 
```

Ställer in XMP‑typvärdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Strängrepresentationen av nyckeln som identifieras med satt värde. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Värdet att sätta till. |

