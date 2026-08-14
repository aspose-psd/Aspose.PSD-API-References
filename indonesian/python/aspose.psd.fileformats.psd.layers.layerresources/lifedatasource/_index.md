---
title: "Kelas LiFeDataSource"
type: docs
weight: 520
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/
---

**Summary:** Defines the LnkeDataSource class that contains information about external linked file.<br/>            This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LiFeDataSource

**Inheritance:** LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [LiFeDataSource()](#LiFeDataSource__1) | Menginisialisasi sebuah instance baru dari kelas [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . |
| [LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator)](#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2) | Menginisialisasi sebuah instance baru dari kelas [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| adobe_stock_id | string | r/w | Mendapatkan atau mengatur pustaka grafis AdobeStockId, untuk Adobe® Photoshop® CC Libraries. |
| adobe_stock_license_state | string | r | Mendapatkan status lisensi Adobe Stock jika tersedia, untuk Adobe® Photoshop® CC libraries. |
| asset_locked_state | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah aset PSD terkunci.<br/>            Status kunci aset, untuk aset Adobe® Photoshop® СС Libraries. |
| asset_mod_time | double | r/w | Mendapatkan atau mengatur waktu modifikasi aset, untuk aset Adobe® Photoshop® СС Libraries. |
| child_doc_id | string | r/w | Mendapatkan atau mengatur pengidentifikasi dokumen anak dalam sumber data liFE atau liFD dari sumber daya Lnk2 / LnkE Adobe® Photoshop®. |
| comp_id | int | r/w | Mendapatkan atau mengatur ID komposisi yang saat ini dipilih untuk dokumen anak, yang akan menjadi -1 jika tidak ada yang dipilih.<br/>            Komposisi adalah susunan tata letak halaman yang dapat dibuat desainer. Dengan menggunakan layer comps, Anda dapat membuat, mengelola, dan melihat beberapa versi<br/>            dari tata letak dalam satu file Adobe® Photoshop®. Sebuah layer comp adalah snapshot dari keadaan panel Layers. Layer comps menyimpan tiga jenis opsi layer tetapi<br/>            properti ini mendapatkan pengidentifikasi pemilihan Layer Comp untuk Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps dalam Smart Objects</see> |
| date | datetime | r/w | Mendapatkan atau mengatur tanggal dan waktu penulisan terakhir dari file eksternal dalam sumber data LiFE dari sumber daya PSD LnkE. |
| element_name | string | r/w | Mendapatkan atau mengatur nama elemen perpustakaan grafis, untuk Adobe® Photoshop® CC Libraries. |
| element_ref | string | r/w | Mendapatkan atau mengatur referensi elemen perpustakaan grafis, untuk Adobe® Photoshop® CC Libraries. |
| file_creator | string | r/w | Mendapatkan atau mengatur pembuat file dalam sumber daya format PSD LnkE / Lnk2. |
| file_name | string | r/w | Mendapatkan atau mengatur nama file eksternal atau tersemat dalam sumber daya tautan PSD . |
| file_size | long | r/w | Mendapatkan atau mengatur ukuran file eksternal dalam sumber data LiFE dari sumber daya PSD LnkE. |
| file_type | string | r/w | Mendapatkan atau mengatur tipe file tersemat atau eksternal yang dimiliki atau ditautkan oleh sumber daya Adobe® Photoshop® Lnk2 / LnkE. |
| full_path | string | r/w | Mendapatkan atau mengatur jalur lengkap file eksternal dalam sumber data LiFE dari sumber daya PSD LnkE. |
| has_file_open_descriptor | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah sumber data tautan ini memiliki deskriptor file terbuka: CompId dan OriginalCompId. |
| is_library_link | bool | r | Mendapatkan nilai yang menunjukkan apakah sumber data tautan PSD ini terhubung ke item Adobe® Photoshop® СС Library. |
| panjang | long | r | Mendapatkan panjang sumber data tautan dalam byte. |
| original_comp_id | int | r | Mendapatkan ID asli dari Comp yang saat ini dipilih untuk dokumen anak, yang akan menjadi -1 jika tidak ada yang dipilih.<br/>            Properti ini mendapatkan pengidentifikasi pemilihan Comp lapisan asli untuk Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| original_file_name | string | r | Mendapatkan nama file asli dari sumber data dalam sumber daya tautan global Adobe® Photoshop®. |
| relative_path | string | r/w | Mendapatkan atau mengatur jalur relatif file eksternal dalam sumber data LiFE dari sumber daya PSD LnkE. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Mendapatkan jenis sumber data tautan global Adobe® Photoshop® yang dapat berupa salah satu berikut atau tidak ada:<br/>            File tautan tersemat liFD yang sesuai dengan PSD Lnk2Resource<br/>            File tautan eksternal liFE yang sesuai dengan PSD LnkeResource<br/>            Alias file tautan liFA |
| unique_id | Guid | r | Mendapatkan pengidentifikasi unik global dari sumber data dalam sumber daya tautan PSD. |
| version | int | r | Mendapatkan versi sumber data dalam sumber daya PSD LnkE / Lnk2. |


### Constructor: LiFeDataSource() {#LiFeDataSource__1}


```
 LiFeDataSource() 
```

Menginisialisasi sebuah instance baru dari kelas [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) .

### Constructor: LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) {#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2}


```
 LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) 
```

Menginisialisasi sebuah instance baru dari kelas [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| version | int | Versi. |
| unique_id | Guid | Pengidentifikasi unik. |
| original_file_name | string | Nama file asli. |
| file_type | string | Tipe file. |
| file_creator | string | Pembuat file. |

