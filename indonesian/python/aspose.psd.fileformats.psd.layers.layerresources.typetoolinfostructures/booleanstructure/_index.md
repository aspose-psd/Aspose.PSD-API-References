---
title: "Kelas BooleanStructure"
type: docs
weight: 20
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/booleanstructure/
---

**Summary:** The boolean structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.BooleanStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [BooleanStructure(key_name)](#BooleanStructure_key_name_1) | Menginisialisasi instance baru dari kelas [BooleanStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/booleanstructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Mengidentifikasi kunci struktur. |
| key | int | r | Mendapatkan kunci struktur. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Mendapatkan atau mengatur nama kunci. |
| length | int | r | Mendapatkan panjang [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) dalam byte. |
| value | bool | r/w | Mendapatkan atau mengatur nilai boolean. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Mendapatkan panjang header. |
| [save(stream_container)](#save_stream_container_2) | Menyimpan struktur ke kontainer aliran yang ditentukan. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Menyimpan struktur ke kontainer aliran yang ditentukan. |


### Constructor: BooleanStructure(key_name) {#BooleanStructure_key_name_1}


```
 BooleanStructure(key_name) 
```

Menginisialisasi instance baru dari kelas [BooleanStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/booleanstructure/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Nama kunci. |

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

