---
title: PdfPackage Class
type: docs
weight: 10
url: /python-net/aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.psd.xmp.schemas.pdf](/psd/python-net/aspose.psd.xmp.schemas.pdf/)

**Full Name:** aspose.psd.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.6.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Initializes a new instance of the PdfPackage class |
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
| [set_keywords(keywords)](#set_keywords_keywords_5) | Sets the keywords. |
| [set_pdf_version(version)](#set_pdf_version_version_6) | Sets the PDF version. |
| [set_producer(producer)](#set_producer_producer_7) | Sets the name of the tool that created Pdf. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_8) | Sets the trapped. |
| [set_value(key, value)](#set_value_key_value_9) | Sets the value. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | Sets the XMP type value. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Initializes a new instance of the PdfPackage class

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


### Method: set_keywords(keywords) {#set_keywords_keywords_5}


```
 set_keywords(keywords) 
```

Sets the keywords.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| keywords | string | The keywords. |

### Method: set_pdf_version(version) {#set_pdf_version_version_6}


```
 set_pdf_version(version) 
```

Sets the PDF version.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| version | string | Pdf version, for example: 1.0, 1.3 etc. |

### Method: set_producer(producer) {#set_producer_producer_7}


```
 set_producer(producer) 
```

Sets the name of the tool that created Pdf.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| producer | string | The producer name. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_8}


```
 set_trapped(is_trapped) 
```

Sets the trapped.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| is_trapped | bool | if set to <c>true</c> the document has been trapped. |

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

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

Sets the XMP type value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | The value to set to. |

