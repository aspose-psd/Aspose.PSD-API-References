---
title: XmpMediaManagementPackage Class
type: docs
weight: 10
url: /python-net/aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmpmm](/psd/python-net/aspose.psd.xmp.schemas.xmpmm/)

**Full Name:** aspose.psd.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.8.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | Initializes a new instance of the XmpMediaManagementPackage class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
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
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_5) | Sets the derived from. |
| [set_document_id(guid)](#set_document_id_guid_6) | Sets the document identifier. |
| [set_document_id(guid)](#set_document_id_guid_7) | Sets the document identifier. |
| [set_instance_id(guid)](#set_instance_id_guid_8) | Sets instance id. |
| [set_instance_id(guid)](#set_instance_id_guid_9) | Sets instance id. |
| [set_original_document_id(guid)](#set_original_document_id_guid_10) | Sets the original document id. |
| [set_original_document_id(guid)](#set_original_document_id_guid_11) | Sets the original document id. |
| [set_value(key, value)](#set_value_key_value_12) | Sets the value. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_13) | Sets the XMP type value. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

Initializes a new instance of the XmpMediaManagementPackage class

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


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_5}


```
 set_derived_from(resource_ref) 
```

Sets the derived from.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| resource_ref | [ResourceRef](/psd/python-net/aspose.psd.xmp.types.complex.resourceref/resourceref/) | The resource reference. |

### Method: set_document_id(guid) {#set_document_id_guid_6}


```
 set_document_id(guid) 
```

Sets the document identifier.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| guid | Guid | The unique identifier. |

### Method: set_document_id(guid) {#set_document_id_guid_7}


```
 set_document_id(guid) 
```

Sets the document identifier.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| guid | string | The unique identifier. |

### Method: set_instance_id(guid) {#set_instance_id_guid_8}


```
 set_instance_id(guid) 
```

Sets instance id.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| guid | Guid | The unique identifier. |

### Method: set_instance_id(guid) {#set_instance_id_guid_9}


```
 set_instance_id(guid) 
```

Sets instance id.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| guid | string | The unique identifier. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_10}


```
 set_original_document_id(guid) 
```

Sets the original document id.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| guid | Guid | The unique identifier. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_11}


```
 set_original_document_id(guid) 
```

Sets the original document id.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| guid | string | The unique identifier. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | The value to add to. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_13}


```
 set_xmp_type_value(key, value) 
```

Sets the XMP type value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | The value to set to. |

