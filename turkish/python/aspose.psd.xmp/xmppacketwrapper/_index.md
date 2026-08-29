---
title: "XmpPacketWrapper Sınıfı"
type: docs
weight: 450
url: /tr/python-net/aspose.psd.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPacketWrapper

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Yeni bir [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) sınıfı örneği başlatır. |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Yeni bir [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | r | Header işleme talimatını alır. |
| meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | r/w | XMP meta verisini alır. İsteğe bağlı. |
| packages | [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | r | XMP içinde bulunan [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) dizisini alır. |
| packages_count | int | r | XMP yapısı içindeki paket sayısını alır. |
| trailer_pi | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | r | Trailer işleme talimatını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Paketi ekler. |
| clear_packages() | XMP içindeki tüm [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) öğelerini kaldırır. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Paketin xmp sarmalayıcısında mevcut olup olmadığını belirler. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Paketi namespace URI'sine göre alır. |
| [remove_package(package)](#remove_package_package_4) | XMP paketini kaldırır. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Yeni bir [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) sınıfı örneği başlatır.

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Yeni bir [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| header | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | İşleme talimatının XMP başlığı. |
| trailer | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | İşleme talimatının XMP trailer'ı. |
| xmp_meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | XMP meta verileri. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Paketi ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Paket. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Paketin xmp sarmalayıcısında mevcut olup olmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| namespace_uri | string | Paket şema uri'si. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen namespace Uri'ye sahip paket XMP sarmalayıcısında mevcutsa true döndürür. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Paketi namespace URI'sine göre alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| namespace_uri | string | Paket şema URI'si. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Belirtilen ad alanı URI'si için XMP paketini döndürür. |


### Method: remove_package(package) {#remove_package_package_4}


```
 remove_package(package) 
```

XMP paketini kaldırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Paket. |

