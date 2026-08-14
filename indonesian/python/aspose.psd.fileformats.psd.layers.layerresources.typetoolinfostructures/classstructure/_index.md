---
title: "Kelas ClassStructure"
type: docs
weight: 30
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/
---

**Summary:** The class structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ClassStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [ClassStructure(key_name, class_id, structure_key)](#ClassStructure_key_name_class_id_structure_key_1) | Menginisialisasi instance baru dari kelas [ClassStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| STRUCTURE_KEY_CLSS [static] | int | r | Mengidentifikasi kunci struktur. |
| STRUCTURE_KEY_GLBC [static] | int | r | Mengidentifikasi kunci struktur. |
| STRUCTURE_KEY_TYPE [static] | int | r | Mengidentifikasi kunci struktur. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Mendapatkan atau mengatur ID kelas. |
| class_name | string | r/w | Mendapatkan atau mengatur nama kelas. |
| key | int | r | Mendapatkan kunci struktur. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Mendapatkan atau mengatur nama kunci. |
| length | int | r | Mendapatkan panjang [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) dalam byte. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Mendapatkan panjang header. |
| [save(stream_container)](#save_stream_container_2) | Menyimpan struktur ke kontainer aliran yang ditentukan. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Menyimpan struktur ke kontainer aliran yang ditentukan. |


### Constructor: ClassStructure(key_name, class_id, structure_key) {#ClassStructure_key_name_class_id_structure_key_1}


```
 ClassStructure(key_name, class_id, structure_key) 
```

Menginisialisasi instance baru dari kelas [ClassStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Nama kunci. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | ID kelas. |
| structure_key | int | Kunci struktur. |

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

