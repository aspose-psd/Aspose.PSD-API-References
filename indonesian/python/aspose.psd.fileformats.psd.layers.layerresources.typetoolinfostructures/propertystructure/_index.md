---
title: "PropertyStructure Kelas"
type: docs
weight: 130
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/propertystructure/
---

**Summary:** The property structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.PropertyStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [PropertyStructure(key_name, class_id, key_id)](#PropertyStructure_key_name_class_id_key_id_1) | Menginisialisasi sebuah instance baru dari kelas [PropertyStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/propertystructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Mengidentifikasi kunci struktur. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Mendapatkan atau mengatur ID kelas. |
| class_name | string | r/w | Mendapatkan atau mengatur nama kelas. |
| key | int | r | Mendapatkan kunci struktur. |
| key_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Mendapatkan atau mengatur ID kunci. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Mendapatkan atau mengatur nama kunci. |
| length | int | r | Mendapatkan panjang [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) dalam byte. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Mendapatkan panjang header. |
| [save(stream_container)](#save_stream_container_2) | Menyimpan struktur ke kontainer aliran yang ditentukan. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Menyimpan struktur ke kontainer aliran yang ditentukan. |


### Constructor: PropertyStructure(key_name, class_id, key_id) {#PropertyStructure_key_name_class_id_key_id_1}


```
 PropertyStructure(key_name, class_id, key_id) 
```

Menginisialisasi sebuah instance baru dari kelas [PropertyStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/propertystructure/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Nama kunci. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | ID kelas. |
| key_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | ID kunci. |

### Method: get_header_length() {#get_header_length__1}


```
 get_header_length() 
```

Mendapatkan panjang header.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Panjang header |


### Method: save(stream_container) {#save_stream_container_2}


```
 save(stream_container) 
```

Menyimpan struktur ke kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran. |

### Method: save_without_key_name(stream_container) {#save_without_key_name_stream_container_3}


```
 save_without_key_name(stream_container) 
```

Menyimpan struktur ke kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran. |

