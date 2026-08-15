---
title: "XmpPacketWrapper klass"
type: docs
weight: 450
url: /sv/python-net/aspose.psd.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPacketWrapper

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Initierar en ny instans av [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) klassen. |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Initierar en ny instans av [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) klassen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | r | Hämtar header‑processinstruktionen. |
| meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | r/w | Hämtar XMP‑metadata. Valfritt. |
| packages | [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | r | Hämtar array av [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) i XMP. |
| packages_count | int | r | Hämtar antalet paket i XMP‑strukturen. |
| trailer_pi | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | r | Hämtar trailer‑processinstruktionen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Lägger till paketet. |
| clear_packages() | Tar bort alla [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) i XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Bestämmer om paketet finns i XMP‑omslaget. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Hämtar paketet efter namnrymds‑URI. |
| [remove_package(package)](#remove_package_package_4) | Tar bort XMP‑paketet. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Initierar en ny instans av [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) klassen.

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Initierar en ny instans av [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) klassen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| header | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | XMP‑huvudet för processinstruktionen. |
| trailer | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | XMP‑trailern för processinstruktionen. |
| xmp_meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | XMP‑metadata. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Lägger till paketet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Paketet. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Bestämmer om paketet finns i XMP‑omslaget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namespace_uri | string | Paketets schemauri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Returnerar true om paket med angiven namnrymds‑URI finns i XMP‑omslaget. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Hämtar paketet efter namnrymds‑URI.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namespace_uri | string | Paketets schemauri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Returnerar XMP‑paketet för angiven namnrymds‑URI. |


### Method: remove_package(package) {#remove_package_package_4}


```
 remove_package(package) 
```

Tar bort XMP‑paketet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Paketet. |

