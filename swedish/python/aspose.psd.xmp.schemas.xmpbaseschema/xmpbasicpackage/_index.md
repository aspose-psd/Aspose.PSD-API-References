---
title: "XmpBasicPackage-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.psd.xmp.schemas.xmpbaseschema](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.psd.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Initierar en ny instans av klassen [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/). |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Initierar en ny instans av klassen [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | Maxvärde för betyg. |
| RATING_MIN [static] | int | r | Rating min värde. |
| RATING_REJECTED [static] | int | r | Rating avvisat värde. |
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
| [set_created_date(created_date)](#set_created_date_created_date_5) | Lägger till resursens skapade datum. |
| [set_created_date(created_date)](#set_created_date_created_date_6) | Lägger till resursens skapade datum. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_7) | Ställer in skapandeverktyget. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_8) | Ställer in identifieraren. |
| [set_label(label)](#set_label_label_9) | Ställer in etiketten. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_10) | Lägger till metadata senast ändrad datum. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_11) | Lägger till metadata senast ändrad datum. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_12) | Lägger till resursens senast ändrade datum. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_13) | Lägger till resursens senast ändrade datum. |
| [set_rating(choise)](#set_rating_choise_14) | Ställer in betyg. |
| [set_value(key, value)](#set_value_key_value_15) | Ställer in värdet. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_16) | Ställer in XMP‑typvärdet. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Initierar en ny instans av klassen [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/).

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Initierar en ny instans av klassen [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| prefix | string | Prefixet. |
| namespace_uri | string | Namnrymdens URI. |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_5}


```
 set_created_date(created_date) 
```

Lägger till resursens skapade datum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| created_date | datetime | Skapat datum. |

### Method: set_created_date(created_date) {#set_created_date_created_date_6}


```
 set_created_date(created_date) 
```

Lägger till resursens skapade datum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| created_date | string | Skapat datum. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_7}


```
 set_creator_tool(creator_tool) 
```

Ställer in skapandeverktyget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| creator_tool | string | Namn på verktyg. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_8}


```
 set_identifier(idenfifier) 
```

Ställer in identifieraren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| idenfifier | string | Den identifieraren. |

### Method: set_label(label) {#set_label_label_9}


```
 set_label(label) 
```

Ställer in etiketten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| label | string | Etiketten. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_10}


```
 set_metadata_date(metadata_date) 
```

Lägger till metadata senast ändrad datum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| metadata_date | datetime | Metadata datum. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_11}


```
 set_metadata_date(metadata_date) 
```

Lägger till metadata senast ändrad datum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| metadata_date | string | Metadata datum. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_12}


```
 set_modify_date(modified_date) 
```

Lägger till resursens senast ändrade datum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| modified_date | datetime | Senast ändrad datum. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_13}


```
 set_modify_date(modified_date) 
```

Lägger till resursens senast ändrade datum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| modified_date | string | Senast ändrad datum. |

### Method: set_rating(choise) {#set_rating_choise_14}


```
 set_rating(choise) 
```

Ställer in betyg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| choise | int | Från -1 till 5 |

### Method: set_value(key, value) {#set_value_key_value_15}


```
 set_value(key, value) 
```

Ställer in värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Strängrepresentationen av nyckeln som identifieras med tillagt värde. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Värdet att lägga till. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_16}


```
 set_xmp_type_value(key, value) 
```

Ställer in XMP‑typvärdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | string | Strängrepresentationen av nyckeln som identifieras med satt värde. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Värdet att sätta till. |

