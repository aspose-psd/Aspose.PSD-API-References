---
title: XmpBasicPackage Class
type: docs
weight: 10
url: /python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.psd.xmp.schemas.xmpbaseschema](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.psd.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.5.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Initializes a new instance of the [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) class. |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Initializes a new instance of the [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | Rating max value. |
| RATING_MIN [static] | int | r | Rating min value. |
| RATING_REJECTED [static] | int | r | Rating rejected value. |
| namespace_uri | string | r | Gets the namespace URI. |
| prefix | string | r | Gets the prefix. |
| xml_namespace | string | r | Gets the XML namespace. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Adds string property. |
| clear() | Clears this instance. |
| [contains_key(key)](#contains_key_key_2) | Determines whether the specified key contains key. |
| [get_xml_value()](#get_xml_value__3) | Converts XMP value to the XML representation. |
| [remove(key)](#remove_key_4) | Remove the value with the specified key. |
| [set_created_date(created_date)](#set_created_date_created_date_5) | Adds resource created date. |
| [set_created_date(created_date)](#set_created_date_created_date_6) | Adds resource created date. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_7) | Sets the creator tool. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_8) | Sets the identifier. |
| [set_label(label)](#set_label_label_9) | Sets the label. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_10) | Adds metadata last changed date. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_11) | Adds metadata last changed date. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_12) | Adds resource last modified date. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_13) | Adds resource last modified date. |
| [set_rating(choise)](#set_rating_choise_14) | Sets rating. |
| [set_value(key, value)](#set_value_key_value_15) | Sets the value. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_16) | Sets the XMP type value. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Initializes a new instance of the [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) class.

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Initializes a new instance of the [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| prefix | string | The prefix. |
| namespace_uri | string | The namespace URI. |

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Adds string property.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | string | The string value. |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

Determines whether the specified key contains key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key to be checked. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Returns true if the specified key contains key. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Converts XMP value to the XML representation.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the XMP value converted to the XML representation. |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

Remove the value with the specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with removed value. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Returns true if the value with the specified key was removed. |


### Method: set_created_date(created_date) {#set_created_date_created_date_5}


```
 set_created_date(created_date) 
```

Adds resource created date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| created_date | datetime | Created date. |

### Method: set_created_date(created_date) {#set_created_date_created_date_6}


```
 set_created_date(created_date) 
```

Adds resource created date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| created_date | string | Created date. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_7}


```
 set_creator_tool(creator_tool) 
```

Sets the creator tool.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| creator_tool | string | Name of tool. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_8}


```
 set_identifier(idenfifier) 
```

Sets the identifier.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| idenfifier | string | The idenfifier. |

### Method: set_label(label) {#set_label_label_9}


```
 set_label(label) 
```

Sets the label.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| label | string | The label. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_10}


```
 set_metadata_date(metadata_date) 
```

Adds metadata last changed date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| metadata_date | datetime | Metadata date. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_11}


```
 set_metadata_date(metadata_date) 
```

Adds metadata last changed date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| metadata_date | string | Metadata date. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_12}


```
 set_modify_date(modified_date) 
```

Adds resource last modified date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| modified_date | datetime | Last modified date. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_13}


```
 set_modify_date(modified_date) 
```

Adds resource last modified date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| modified_date | string | Last modified date. |

### Method: set_rating(choise) {#set_rating_choise_14}


```
 set_rating(choise) 
```

Sets rating.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| choise | int | From -1 till 5 |

### Method: set_value(key, value) {#set_value_key_value_15}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | The value to add to. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_16}


```
 set_xmp_type_value(key, value) 
```

Sets the XMP type value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | The value to set to. |

