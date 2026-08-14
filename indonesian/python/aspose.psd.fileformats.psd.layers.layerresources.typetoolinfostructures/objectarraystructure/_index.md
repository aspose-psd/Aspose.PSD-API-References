---
title: "Kelas ObjectArrayStructure"
type: docs
weight: 100
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---

**Summary:** Defines the ObjectArrayStructure class that usually holds [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) array.<br/>            It is used in the PSD file resources, such as PlLd Resource and SoLd Resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ObjectArrayStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [ObjectArrayStructure(key, key_name, class_id, class_name, structures)](#ObjectArrayStructure_key_key_name_class_id_class_name_structures_1) | Menginisialisasi instance baru dari kelas [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/). |
| [ObjectArrayStructure(key_name, class_id_name, structures)](#ObjectArrayStructure_key_name_class_id_name_structures_2) | Menginisialisasi instance baru dari kelas [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Mengidentifikasi kunci struktur 'ObAr'. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Mendapatkan atau mengatur ID kelas array objek. |
| class_name | string | r/w | Mendapatkan atau mengatur nama kelas array objek. |
| key | int | r | Mendapatkan kunci struktur array objek. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Mendapatkan atau mengatur nama kunci. |
| length | int | r | Mendapatkan panjang [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) dalam byte. |
| structure_count | int | r | Mendapatkan jumlah substruktur array objek. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Mendapatkan atau mengatur salinan array struktur. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Mendapatkan panjang header. |
| [save(stream_container)](#save_stream_container_2) | Menyimpan struktur ke kontainer aliran yang ditentukan. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Menyimpan struktur ke kontainer aliran yang ditentukan. |


### Constructor: ObjectArrayStructure(key, key_name, class_id, class_name, structures) {#ObjectArrayStructure_key_key_name_class_id_class_name_structures_1}


```
 ObjectArrayStructure(key, key_name, class_id, class_name, structures) 
```

Menginisialisasi instance baru dari kelas [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key | int | Kunci integer. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Nama kunci. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Pengidentifikasi kelas. |
| class_name | string | Nama kelas. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Struktur‑struktur. |

### Constructor: ObjectArrayStructure(key_name, class_id_name, structures) {#ObjectArrayStructure_key_name_class_id_name_structures_2}


```
 ObjectArrayStructure(key_name, class_id_name, structures) 
```

Menginisialisasi instance baru dari kelas [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key_name | string | Nama kunci. |
| class_id_name | string | Nama pengidentifikasi kelas. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Struktur‑struktur. |

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

