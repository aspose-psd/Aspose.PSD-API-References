---
title: "Kelas Thumbnail4Resource"
type: docs
weight: 240
url: /id/python-net/aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Summary:** Represents the thumbnail resource for psd 4.0.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.Thumbnail4Resource

**Inheritance:** ThumbnailResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Thumbnail4Resource()](#Thumbnail4Resource__1) | Menginisialisasi sebuah instance baru dari kelas Thumbnail4Resource |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Signature sumber daya ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Signature sumber daya Photoshop standar. |
| bits_pixel | short | r/w | Mendapatkan atau mengatur bits pixel. |
| data_size | int | r | Mendapatkan ukuran data sumber daya dalam byte. |
| format | [ThumbnailFormat](/psd/python-net/aspose.psd.fileformats.psd.resources/thumbnailformat) | r/w | Mendapatkan atau mengatur format data thumbnail. |
| tinggi | int | r/w | Mendapatkan atau mengatur tinggi thumbnail dalam piksel. |
| id | short | r/w | Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya. |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) | r/w | Mendapatkan atau mengatur opsi JPEG. Cocok ketika sumber thumbnail disimpan hanya dalam format file JPEG. Opsi ini tidak berpengaruh ketika format RAW didefinisikan. |
| minimal_version | int | r | Mendapatkan versi psd minimal yang diperlukan. |
| name | string | r/w | Mendapatkan atau mengatur nama sumber daya. String Pascal, dipadding agar ukuran genap (nama null terdiri dari dua byte 0). |
| planes_count | short | r/w | Mendapatkan atau mengatur jumlah plane. |
| signature | int | r | Mendapatkan signature sumber daya. Harus selalu '8BIM'. |
| ukuran | int | r | Mendapatkan ukuran blok sumber daya dalam byte termasuk datanya. |
| size_after_compression | int | r | Mendapatkan atau mengatur ukuran setelah kompresi. Digunakan untuk pemeriksaan konsistensi. |
| thumbnail_argb_32_data | int | r/w | Mendapatkan atau mengatur data thumbnail ARGB 32-bit. |
| thumbnail_data | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur data thumbnail. |
| total_size | int | r | Mendapatkan ukuran total data. |
| width | int | r/w | Mendapatkan atau mengatur lebar thumbnail dalam piksel. |
| width_bytes | int | r | Mendapatkan lebar baris dalam byte. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream)](#save_stream_1) | Menyimpan data blok sumber daya. |
| validate_values() | Memvalidasi nilai sumber daya. |


### Constructor: Thumbnail4Resource() {#Thumbnail4Resource__1}


```
 Thumbnail4Resource() 
```

Menginisialisasi sebuah instance baru dari kelas Thumbnail4Resource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Menyimpan data blok sumber daya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |

