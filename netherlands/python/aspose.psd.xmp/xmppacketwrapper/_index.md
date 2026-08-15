---
title: "XmpPacketWrapper Klasse"
type: docs
weight: 450
url: /nl/python-net/aspose.psd.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPacketWrapper

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Initialiseert een nieuw exemplaar van de [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) klasse. |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Initialiseert een nieuw exemplaar van de [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | r | Haalt de header verwerkingsinstructie op. |
| meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | r/w | Haalt de XMP-meta op. Optioneel. |
| packages | [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | r | Haalt een array van [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) binnen XMP op. |
| packages_count | int | r | Haalt het aantal pakketten binnen de XMP-structuur op. |
| trailer_pi | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | r | Haalt de trailer verwerkingsinstructie op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Voegt het pakket toe. |
| clear_packages() | Verwijdert alle [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) binnen XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Bepaalt of een pakket bestaat in de xmp wrapper. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Haalt pakket op op basis van namespace-URI. |
| [remove_package(package)](#remove_package_package_4) | Verwijdert het XMP-pakket. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Initialiseert een nieuw exemplaar van de [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) klasse.

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Initialiseert een nieuw exemplaar van de [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| header | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | De XMP-header van de verwerkingsinstructie. |
| trailer | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | De XMP-trailer van de verwerkingsinstructie. |
| xmp_meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | De XMP-metadata. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Voegt het pakket toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Het pakket. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Bepaalt of een pakket bestaat in de xmp wrapper.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| namespace_uri | string | Pakket schema-URI. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Geeft true terug als een pakket met de opgegeven namespace-URI bestaat in de XMP-wrapper. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Haalt pakket op op basis van namespace-URI.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| namespace_uri | string | De pakketschema-URI. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Retourneert het XMP-pakket voor de opgegeven namespace-URI. |


### Method: remove_package(package) {#remove_package_package_4}


```
 remove_package(package) 
```

Verwijdert het XMP-pakket.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Het pakket. |

