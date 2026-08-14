---
title: "Kelas PdfPackage"
type: docs
weight: 10
url: /id/python-net/aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.psd.xmp.schemas.pdf](/psd/python-net/aspose.psd.xmp.schemas.pdf/)

**Full Name:** aspose.psd.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Menginisialisasi sebuah instance baru dari kelas PdfPackage |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Mendapatkan URI namespace. |
| awalan | string | r | Mendapatkan awalan. |
| xml_namespace | string | r | Mendapatkan namespace XML. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Menambahkan properti string. |
| clear() | Menghapus instance ini. |
| [contains_key(key)](#contains_key_key_2) | Menentukan apakah kunci yang ditentukan berisi kunci. |
| [get_xml_value()](#get_xml_value__3) | Mengonversi nilai XMP ke representasi XML. |
| [remove(key)](#remove_key_4) | Menghapus nilai dengan kunci yang ditentukan. |
| [set_keywords(keywords)](#set_keywords_keywords_5) | Mengatur kata kunci. |
| [set_pdf_version(version)](#set_pdf_version_version_6) | Mengatur versi PDF. |
| [set_producer(producer)](#set_producer_producer_7) | Mengatur nama alat yang membuat PDF. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_8) | Mengatur trapped. |
| [set_value(key, value)](#set_value_key_value_9) | Mengatur nilai. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | Mengatur nilai tipe XMP. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Menginisialisasi sebuah instance baru dari kelas PdfPackage

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Menambahkan properti string.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key | string | Representasi string dari kunci yang diidentifikasi dengan nilai yang ditambahkan. |
| value | string | Nilai string. |

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


### Method: set_keywords(keywords) {#set_keywords_keywords_5}


```
 set_keywords(keywords) 
```

Mengatur kata kunci.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| kata kunci | string | Kata kunci. |

### Method: set_pdf_version(version) {#set_pdf_version_version_6}


```
 set_pdf_version(version) 
```

Mengatur versi PDF.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| version | string | Versi PDF, misalnya: 1.0, 1.3, dll. |

### Method: set_producer(producer) {#set_producer_producer_7}


```
 set_producer(producer) 
```

Mengatur nama alat yang membuat PDF.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| producer | string | Nama producer. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_8}


```
 set_trapped(is_trapped) 
```

Mengatur trapped.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| is_trapped | bool | jika disetel ke <c>true</c> dokumen telah ter-trapped. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Mengatur nilai.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key | string | Representasi string dari kunci yang diidentifikasi dengan nilai yang ditambahkan. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Nilai untuk ditambahkan ke. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

Mengatur nilai tipe XMP.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key | string | Representasi string dari kunci yang diidentifikasi dengan nilai yang ditetapkan. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Nilai untuk diatur ke. |

