---
title: "Kelas LiFdDataSource"
type: docs
weight: 510
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---

**Summary:** Defines the liFD data source class in PSD File that contains information about an embedded file.<br/>            This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LiFdDataSource

**Inheritance:** LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [LiFdDataSource()](#LiFdDataSource__1) | Menginisialisasi sebuah instance baru dari kelas [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/). |
| [LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator)](#LiFdDataSource_version_unique_id_original_file_name_file_type_file_creator_2) | Menginisialisasi sebuah instance baru dari kelas [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| asset_locked_state | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah aset PSD terkunci.<br/>            Status kunci aset, untuk aset Adobe® Photoshop® СС Libraries. |
| asset_mod_time | double | r/w | Mendapatkan atau mengatur waktu modifikasi aset, untuk aset Adobe® Photoshop® СС Libraries. |
| child_doc_id | string | r/w | Mendapatkan atau mengatur pengidentifikasi dokumen anak dalam sumber data liFE atau liFD dari sumber daya Lnk2 / LnkE Adobe® Photoshop®. |
| comp_id | int | r/w | Mendapatkan atau mengatur ID komposisi yang saat ini dipilih untuk dokumen anak, yang akan menjadi -1 jika tidak ada yang dipilih.<br/>            Komposisi adalah susunan tata letak halaman yang dapat dibuat desainer. Dengan menggunakan layer comps, Anda dapat membuat, mengelola, dan melihat beberapa versi<br/>            dari tata letak dalam satu file Adobe® Photoshop®. Sebuah layer comp adalah snapshot dari keadaan panel Layers. Layer comps menyimpan tiga jenis opsi layer tetapi<br/>            properti ini mendapatkan pengidentifikasi pemilihan Layer Comp untuk Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps dalam Smart Objects</see> |
| data | byte | r/w | Mendapatkan atau mengatur data objek pintar yang tertanam dalam file PSD. |
| file_creator | string | r/w | Mendapatkan atau mengatur pembuat file dalam sumber daya format PSD LnkE / Lnk2. |
| file_type | string | r/w | Mendapatkan atau mengatur tipe file tersemat atau eksternal yang dimiliki atau ditautkan oleh sumber daya Adobe® Photoshop® Lnk2 / LnkE. |
| has_file_open_descriptor | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah sumber data tautan ini memiliki deskriptor file terbuka: CompId dan OriginalCompId. |
| is_library_link | bool | r | Mendapatkan nilai yang menunjukkan apakah sumber data tautan PSD ini terhubung ke item Adobe® Photoshop® СС Library. |
| panjang | long | r | Mendapatkan panjang sumber data tautan dalam byte. |
| original_comp_id | int | r | Mendapatkan ID asli dari Comp yang saat ini dipilih untuk dokumen anak, yang akan menjadi -1 jika tidak ada yang dipilih.<br/>            Properti ini mendapatkan pengidentifikasi pemilihan Comp lapisan asli untuk Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| original_file_name | string | r | Mendapatkan nama file asli dari sumber data dalam sumber daya tautan global Adobe® Photoshop®. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Mendapatkan jenis sumber data tautan global Adobe® Photoshop® yang dapat berupa salah satu berikut atau tidak ada:<br/>            File tautan tersemat liFD yang sesuai dengan PSD Lnk2Resource<br/>            File tautan eksternal liFE yang sesuai dengan PSD LnkeResource<br/>            Alias file tautan liFA |
| unique_id | Guid | r | Mendapatkan pengidentifikasi unik global dari sumber data dalam sumber daya tautan PSD. |
| version | int | r | Mendapatkan versi sumber data dalam sumber daya PSD LnkE / Lnk2. |


### Constructor: LiFdDataSource() {#LiFdDataSource__1}


```
 LiFdDataSource() 
```

Menginisialisasi sebuah instance baru dari kelas [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/).

### Constructor: LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator) {#LiFdDataSource_version_unique_id_original_file_name_file_type_file_creator_2}


```
 LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator) 
```

Menginisialisasi sebuah instance baru dari kelas [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| version | int | Versi. |
| unique_id | Guid | Pengidentifikasi unik. |
| original_file_name | string | Nama file asli. |
| file_type | string | Tipe file. |
| file_creator | string | Pembuat file. |

