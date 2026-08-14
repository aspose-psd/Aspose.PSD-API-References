---
title: "XmpPacketWrapper Klasse"
type: docs
weight: 450
url: /de/python-net/aspose.psd.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPacketWrapper

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Initialisiert eine neue Instanz der [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) Klasse. |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Initialisiert eine neue Instanz der [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | r | Liefert die Header-Verarbeitungsanweisung. |
| meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | r/w | Liefert die XMP-Metadaten. Optional. |
| packages | [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | r | Liefert ein Array von [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) innerhalb von XMP. |
| packages_count | int | r | Liefert die Anzahl der Pakete innerhalb der XMP-Struktur. |
| trailer_pi | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | r | Liefert die Trailer-Verarbeitungsanweisung. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Fügt das Paket hinzu. |
| clear_packages() | Entfernt alle [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) innerhalb von XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Bestimmt, ob ein Paket im XMP-Wrapper existiert. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Liefert das Paket nach Namespace-URI. |
| [remove_package(package)](#remove_package_package_4) | Entfernt das XMP-Paket. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Initialisiert eine neue Instanz der [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) Klasse.

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Initialisiert eine neue Instanz der [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| header | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | Der XMP-Header der Verarbeitungsanweisung. |
| trailer | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | Der XMP-Trailer der Verarbeitungsanweisung. |
| xmp_meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | Die XMP-Metadaten. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Fügt das Paket hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Das Paket. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Bestimmt, ob ein Paket im XMP-Wrapper existiert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| namespace_uri | string | Paket-Schema-URI. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Gibt true zurück, wenn ein Paket mit dem angegebenen Namespace-URI im XMP-Wrapper existiert. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Liefert das Paket nach Namespace-URI.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| namespace_uri | string | Der Paket-Schema-URI. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Gibt das XMP-Paket für den angegebenen Namespace-URI zurück. |


### Method: remove_package(package) {#remove_package_package_4}


```
 remove_package(package) 
```

Entfernt das XMP-Paket.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Das Paket. |

