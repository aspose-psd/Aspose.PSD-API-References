---
title: "Kelas UnknownStructure"
type: docs
weight: 190
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unknownstructure/
---

**Summary:** The unknown structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.UnknownStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [UnknownStructure(key_name, key)](#UnknownStructure_key_name_key_1) | Menginisialisasi sebuah instance baru dari kelas [UnknownStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unknownstructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| data | byte | r/w | Mendapatkan atau mengatur data. |
| key | int | r | Mendapatkan kunci struktur. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Mendapatkan atau mengatur nama kunci. |
| length | int | r | Mendapatkan panjang [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) dalam byte. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Mendapatkan panjang header. |
| [save(stream_container)](#save_stream_container_2) | Menyimpan struktur ke kontainer aliran yang ditentukan. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Menyimpan struktur ke kontainer aliran yang ditentukan. |


### Constructor: UnknownStructure(key_name, key) {#UnknownStructure_key_name_key_1}


```
 UnknownStructure(key_name, key) 
```

Menginisialisasi sebuah instance baru dari kelas [UnknownStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unknownstructure/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Nama kunci. |
| key | int | Kunci struktur. |

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

