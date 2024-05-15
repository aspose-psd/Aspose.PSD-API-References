---
title: XmpRightsManagementPackage Class
type: docs
weight: 10
url: /python-net/aspose.psd.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Summary:** Represents XMP Rights Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmprm](/psd/python-net/aspose.psd.xmp.schemas.xmprm/)

**Full Name:** aspose.psd.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.4.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__1) | Initializes a new instance of the XmpRightsManagementPackage class |
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
| [set_certificate(certificate)](#set_certificate_certificate_5) | Sets the certificate. |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_6) | Marks as right management content |
| [set_owners(owners)](#set_owners_owners_7) | Sets owners. |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_8) | Sets the usage terms. |
| [set_value(key, value)](#set_value_key_value_9) | Sets the value. |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_10) | Sets the web statement. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_11) | Sets the XMP type value. |


### Constructor: XmpRightsManagementPackage() {#XmpRightsManagementPackage__1}


```
 XmpRightsManagementPackage() 
```

Initializes a new instance of the XmpRightsManagementPackage class

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


### Method: set_certificate(certificate) {#set_certificate_certificate_5}


```
 set_certificate(certificate) 
```

Sets the certificate.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| certificate | string | The certificate. |

### Method: set_marked_as_right_management(value) {#set_marked_as_right_management_value_6}


```
 set_marked_as_right_management(value) 
```

Marks as right management content

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | bool | if set to <c>true</c> that this is a rights-managed resource. |

### Method: set_owners(owners) {#set_owners_owners_7}


```
 set_owners(owners) 
```

Sets owners.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| owners | string | The owners. |

### Method: set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_8}


```
 set_usage_terms(usage_terms) 
```

Sets the usage terms.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| usage_terms | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | The usage terms. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | The value to add to. |

### Method: set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_10}


```
 set_web_statement(web_statement_url) 
```

Sets the web statement.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| web_statement_url | string | The web statement URL. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_11}


```
 set_xmp_type_value(key, value) 
```

Sets the XMP type value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | The value to set to. |

