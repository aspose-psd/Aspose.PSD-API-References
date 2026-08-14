---
title: "Kelas PrintFlagsResource"
type: docs
weight: 200
url: /id/python-net/aspose.psd.fileformats.psd.resources/printflagsresource/
---

**Summary:** Print flags resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.PrintFlagsResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [PrintFlagsResource()](#PrintFlagsResource__1) | Menginisialisasi sebuah instance baru dari kelas PrintFlagsResource |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Signature sumber daya ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Signature sumber daya Photoshop standar. |
| bleed_scale | short | r/w | Mendapatkan atau mengatur skala bleed. |
| bleed_width | int | r/w | Mendapatkan atau mengatur lebar bleed. |
| center_crop_mark | byte | r/w | Mendapatkan atau mengatur tanda pemotongan tengah. |
| data_size | int | r | Mendapatkan ukuran data sumber daya dalam byte. |
| id | short | r/w | Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya. |
| minimal_version | int | r | Mendapatkan versi PSD minimal yang diperlukan. |
| name | string | r/w | Mendapatkan atau mengatur nama sumber daya. String Pascal, dipadding agar ukuran genap (nama null terdiri dari dua byte 0). |
| signature | int | r | Mendapatkan signature sumber daya. Harus selalu '8BIM'. |
| ukuran | int | r | Mendapatkan ukuran blok sumber daya dalam byte termasuk datanya. |
| version | short | r/w | Mendapatkan atau mengatur versi. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream)](#save_stream_1) | Menyimpan blok sumber daya ke aliran yang ditentukan. |
| validate_values() | Memvalidasi nilai sumber daya. |


### Constructor: PrintFlagsResource() {#PrintFlagsResource__1}


```
 PrintFlagsResource() 
```

Menginisialisasi sebuah instance baru dari kelas PrintFlagsResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Menyimpan blok sumber daya ke aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Aliran untuk menyimpan blok sumber daya. |

