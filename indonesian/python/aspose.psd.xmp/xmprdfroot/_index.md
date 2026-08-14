---
title: "XmpRdfRoot Kelas"
type: docs
weight: 460
url: /id/python-net/aspose.psd.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | Menginisialisasi instance baru dari kelas XmpRdfRoot |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Menambahkan atribut. |
| clear_attributes() | Menghapus semua atribut. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Mendapatkan atribut. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | Mendapatkan URI namespace berdasarkan prefiks tertentu. Prefiks dapat dimulai tanpa xmlns. |
| [get_xml_value()](#get_xml_value__4) | Mengonversi nilai xmp ke representasi xml. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | Menambahkan URI namespace berdasarkan prefiks. Prefiks dapat dimulai tanpa xmlns. |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

Menginisialisasi instance baru dari kelas XmpRdfRoot

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Menambahkan atribut.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| atribut | string | Atribut. |
| value | string | Nilai value. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Mendapatkan atribut.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| atribut | string | Atribut. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Mengembalikan atribut untuk nama atribut yang ditentukan. |


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

Mendapatkan URI namespace berdasarkan prefiks tertentu. Prefiks dapat dimulai tanpa xmlns.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| awalan | string | Awalan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Mengembalikan URI skema paket. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Mengonversi nilai xmp ke representasi xml.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Mengembalikan nilai XMP yang dikonversi menjadi string XML. |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

Menambahkan URI namespace berdasarkan prefiks. Prefiks dapat dimulai tanpa xmlns.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| awalan | string | Awalan. |
| namespace_uri | string | URI skema paket. |

