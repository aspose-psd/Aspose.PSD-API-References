---
title: "Kelas XmpRightsManagementPackage"
type: docs
weight: 10
url: /id/python-net/aspose.psd.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Summary:** Represents XMP Rights Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmprm](/psd/python-net/aspose.psd.xmp.schemas.xmprm/)

**Full Name:** aspose.psd.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__1) | Menginisialisasi sebuah instance baru dari kelas XmpRightsManagementPackage |
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
| [set_certificate(certificate)](#set_certificate_certificate_5) | Mengatur sertifikat. |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_6) | Menandai sebagai konten manajemen hak |
| [set_owners(owners)](#set_owners_owners_7) | Mengatur pemilik. |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_8) | Mengatur ketentuan penggunaan. |
| [set_value(key, value)](#set_value_key_value_9) | Mengatur nilai. |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_10) | Mengatur pernyataan web. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_11) | Mengatur nilai tipe XMP. |


### Constructor: XmpRightsManagementPackage() {#XmpRightsManagementPackage__1}


```
 XmpRightsManagementPackage() 
```

Menginisialisasi sebuah instance baru dari kelas XmpRightsManagementPackage

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


### Method: set_certificate(certificate) {#set_certificate_certificate_5}


```
 set_certificate(certificate) 
```

Mengatur sertifikat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sertifikat | string | Sertifikat. |

### Method: set_marked_as_right_management(value) {#set_marked_as_right_management_value_6}


```
 set_marked_as_right_management(value) 
```

Menandai sebagai konten manajemen hak

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | bool | jika diatur ke <c>true</c> bahwa ini adalah sumber daya yang dikelola hak. |

### Method: set_owners(owners) {#set_owners_owners_7}


```
 set_owners(owners) 
```

Mengatur pemilik.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pemilik | string | Pemilik. |

### Method: set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_8}


```
 set_usage_terms(usage_terms) 
```

Mengatur ketentuan penggunaan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| usage_terms | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | Ketentuan penggunaan. |

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

### Method: set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_10}


```
 set_web_statement(web_statement_url) 
```

Mengatur pernyataan web.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| web_statement_url | string | URL pernyataan web. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_11}


```
 set_xmp_type_value(key, value) 
```

Mengatur nilai tipe XMP.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key | string | Representasi string dari kunci yang diidentifikasi dengan nilai yang ditetapkan. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Nilai untuk diatur ke. |

