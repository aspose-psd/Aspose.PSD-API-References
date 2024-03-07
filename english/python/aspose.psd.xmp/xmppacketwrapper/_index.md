---
title: XmpPacketWrapper Class
type: docs
weight: 450
url: /python-net/aspose.psd.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPacketWrapper

**Aspose.PSD Version:** 24.1.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Initializes a new instance of the [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) class. |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Initializes a new instance of the [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | r | Gets the header processing instruction. |
| meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | r/w | Gets the XMP meta. Optional. |
| packages | [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | r | Gets array of [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) inside XMP. |
| packages_count | int | r | Gets amount of packages inside XMP structure. |
| trailer_pi | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | r | Gets the trailer processing instruction. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Adds the package. |
| clear_packages() | Removes all [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) inside XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Determines whethere package is exist in xmp wrapper. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Gets package by namespace URI. |
| [remove_package(package)](#remove_package_package_4) | Removes the XMP package. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Initializes a new instance of the [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) class.

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Initializes a new instance of the [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| header | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | The XMP header of processing instruction. |
| trailer | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | The XMP trailer of processing instruction. |
| xmp_meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | The XMP metadata. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Adds the package.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | The package. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Determines whethere package is exist in xmp wrapper.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| namespace_uri | string | Package schema uri. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Returns true if package with specified namespace Uri exist in XMP wrapper. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Gets package by namespace URI.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| namespace_uri | string | The package schema URI. |

**Returns**

| Type | Description |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Returns the XMP package for specified namespace URI. |


### Method: remove_package(package) {#remove_package_package_4}


```
 remove_package(package) 
```

Removes the XMP package.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | The package. |

