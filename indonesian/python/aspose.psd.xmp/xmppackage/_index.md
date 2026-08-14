---
title: "Kelas XmpPackage"
type: docs
weight: 430
url: /id/python-net/aspose.psd.xmp/xmppackage/
---

**Summary:** Defines the XmpPackage class that represents base abstraction for XMP package.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackage

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Mendapatkan URI namespace. |
| awalan | string | r | Mendapatkan awalan. |
| xml_namespace | string | r | Mendapatkan namespace XML. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Menambahkan nilai. |
| clear() | Menghapus instance ini. |
| [contains_key(key)](#contains_key_key_2) | Menentukan apakah kunci yang ditentukan berisi kunci. |
| [get_xml_value()](#get_xml_value__3) | Mengonversi nilai XMP ke representasi XML. |
| [remove(key)](#remove_key_4) | Menghapus nilai dengan kunci yang ditentukan. |
| [set_value(key, value)](#set_value_key_value_5) | Mengatur nilai. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_6) | Mengatur nilai tipe XMP. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Menambahkan nilai.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key | string | Representasi string dari kunci yang diidentifikasi dengan nilai yang ditambahkan. |
| value | string | Nilai untuk ditambahkan ke. |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

Menentukan apakah kunci yang ditentukan berisi kunci.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key | string | Kunci yang akan diperiksa. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Mengembalikan true jika kunci yang ditentukan berisi kunci. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Mengonversi nilai XMP ke representasi XML.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Mengembalikan nilai XMP yang dikonversi ke representasi XML. |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

Menghapus nilai dengan kunci yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key | string | Representasi string dari kunci yang diidentifikasi dengan nilai yang dihapus. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Mengembalikan true jika nilai dengan kunci yang ditentukan telah dihapus. |


### Method: set_value(key, value) {#set_value_key_value_5}


```
 set_value(key, value) 
```

Mengatur nilai.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key | string | Representasi string dari kunci yang diidentifikasi dengan nilai yang ditambahkan. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Nilai untuk ditambahkan ke. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_6}


```
 set_xmp_type_value(key, value) 
```

Mengatur nilai tipe XMP.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key | string | Representasi string dari kunci yang diidentifikasi dengan nilai yang ditetapkan. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Nilai untuk diatur ke. |

