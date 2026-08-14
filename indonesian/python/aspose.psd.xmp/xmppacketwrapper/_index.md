---
title: "Kelas XmpPacketWrapper"
type: docs
weight: 450
url: /id/python-net/aspose.psd.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPacketWrapper

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Menginisialisasi instance baru dari kelas [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Menginisialisasi instance baru dari kelas [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | r | Mendapatkan instruksi pemrosesan header. |
| meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | r/w | Mendapatkan meta XMP. Opsional. |
| packages | [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | r | Mendapatkan array [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) di dalam XMP. |
| packages_count | int | r | Mendapatkan jumlah paket di dalam struktur XMP |
| trailer_pi | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | r | Mendapatkan instruksi pemrosesan trailer. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Menambahkan paket. |
| clear_packages() | Menghapus semua [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) di dalam XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Menentukan apakah paket ada di pembungkus xmp. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Mendapatkan paket berdasarkan namespace URI. |
| [remove_package(package)](#remove_package_package_4) | Menghapus paket XMP. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Menginisialisasi instance baru dari kelas [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/)

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Menginisialisasi instance baru dari kelas [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/)

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| header | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | Header XMP dari instruksi pemrosesan. |
| trailer | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | Trailer XMP dari instruksi pemrosesan. |
| xmp_meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | Metadata XMP. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Menambahkan paket.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Paket. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Menentukan apakah paket ada di pembungkus xmp.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| namespace_uri | string | URI skema paket. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Mengembalikan true jika paket dengan URI namespace yang ditentukan ada di pembungkus XMP. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Mendapatkan paket berdasarkan namespace URI.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| namespace_uri | string | URI skema paket. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Mengembalikan paket XMP untuk URI namespace yang ditentukan. |


### Method: remove_package(package) {#remove_package_package_4}


```
 remove_package(package) 
```

Menghapus paket XMP.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Paket. |

