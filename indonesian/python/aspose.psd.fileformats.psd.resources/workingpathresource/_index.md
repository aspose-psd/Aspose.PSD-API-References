---
title: "Kelas WorkingPathResource"
type: docs
weight: 320
url: /id/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Summary:** Working path resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.WorkingPathResource

**Inheritance:** IVectorPathData, ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [WorkingPathResource(data_bytes)](#WorkingPathResource_data_bytes_1) | Menginisialisasi instance baru dari kelas [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Signature sumber daya ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Signature sumber daya Photoshop standar. |
| data_size | int | r | Mendapatkan ukuran data sumber daya dalam byte. |
| id | short | r/w | Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya. |
| is_disabled | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dinonaktifkan. |
| is_inverted | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terbalik. |
| is_not_linked | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini tidak terhubung. |
| minimal_version | int | r | Mendapatkan versi PSD minimal yang diperlukan. |
| name | string | r/w | Mendapatkan atau mengatur nama sumber daya. String Pascal, dipadding agar ukuran genap (nama null terdiri dari dua byte 0). |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Mendapatkan atau mengatur catatan jalur. |
| signature | int | r | Mendapatkan signature sumber daya. Harus selalu '8BIM'. |
| ukuran | int | r | Mendapatkan ukuran blok sumber daya dalam byte termasuk datanya. |
| version | int | r/w | Mendapatkan atau mengatur versi. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream)](#save_stream_1) | Menyimpan blok sumber daya ke aliran yang ditentukan. |
| validate_values() | Memvalidasi nilai sumber daya. |


### Constructor: WorkingPathResource(data_bytes) {#WorkingPathResource_data_bytes_1}


```
 WorkingPathResource(data_bytes) 
```

Menginisialisasi instance baru dari kelas [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data_bytes | byte | Data dari jalur vektor. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Menyimpan blok sumber daya ke aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Aliran untuk menyimpan blok sumber daya. |

