---
title: "XmpMediaManagementPackage Kelas"
type: docs
weight: 10
url: /id/python-net/aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmpmm](/psd/python-net/aspose.psd.xmp.schemas.xmpmm/)

**Full Name:** aspose.psd.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | Menginisialisasi sebuah instance baru dari kelas XmpMediaManagementPackage |
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
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_5) | Mengatur nilai derived from. |
| [set_document_id(guid)](#set_document_id_guid_6) | Mengatur pengidentifikasi dokumen. |
| [set_document_id(guid)](#set_document_id_guid_7) | Mengatur pengidentifikasi dokumen. |
| [set_instance_id(guid)](#set_instance_id_guid_8) | Mengatur id instance. |
| [set_instance_id(guid)](#set_instance_id_guid_9) | Mengatur id instance. |
| [set_original_document_id(guid)](#set_original_document_id_guid_10) | Mengatur id dokumen asli. |
| [set_original_document_id(guid)](#set_original_document_id_guid_11) | Mengatur id dokumen asli. |
| [set_value(key, value)](#set_value_key_value_12) | Mengatur nilai. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_13) | Mengatur nilai tipe XMP. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

Menginisialisasi sebuah instance baru dari kelas XmpMediaManagementPackage

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


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_5}


```
 set_derived_from(resource_ref) 
```

Mengatur nilai derived from.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| resource_ref | [ResourceRef](/psd/python-net/aspose.psd.xmp.types.complex.resourceref/resourceref/) | Referensi sumber daya. |

### Method: set_document_id(guid) {#set_document_id_guid_6}


```
 set_document_id(guid) 
```

Mengatur pengidentifikasi dokumen.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| guid | Guid | Pengidentifikasi unik. |

### Method: set_document_id(guid) {#set_document_id_guid_7}


```
 set_document_id(guid) 
```

Mengatur pengidentifikasi dokumen.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| guid | string | Pengidentifikasi unik. |

### Method: set_instance_id(guid) {#set_instance_id_guid_8}


```
 set_instance_id(guid) 
```

Mengatur id instance.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| guid | Guid | Pengidentifikasi unik. |

### Method: set_instance_id(guid) {#set_instance_id_guid_9}


```
 set_instance_id(guid) 
```

Mengatur id instance.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| guid | string | Pengidentifikasi unik. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_10}


```
 set_original_document_id(guid) 
```

Mengatur id dokumen asli.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| guid | Guid | Pengidentifikasi unik. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_11}


```
 set_original_document_id(guid) 
```

Mengatur id dokumen asli.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| guid | string | Pengidentifikasi unik. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Mengatur nilai.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key | string | Representasi string dari kunci yang diidentifikasi dengan nilai yang ditambahkan. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Nilai untuk ditambahkan ke. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_13}


```
 set_xmp_type_value(key, value) 
```

Mengatur nilai tipe XMP.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key | string | Representasi string dari kunci yang diidentifikasi dengan nilai yang ditetapkan. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Nilai untuk diatur ke. |

