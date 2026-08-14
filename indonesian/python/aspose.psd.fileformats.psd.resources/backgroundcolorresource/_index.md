---
title: "Kelas BackgroundColorResource"
type: docs
weight: 20
url: /id/python-net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/
---

**Summary:** The resource with border information of image print settings.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.BackgroundColorResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [BackgroundColorResource()](#BackgroundColorResource__1) | Menginisialisasi sebuah instance baru dari kelas BackgroundColorResource |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Signature sumber daya ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Signature sumber daya Photoshop standar. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur warna latar belakang. |
| data_size | int | r | Mendapatkan ukuran data sumber daya dalam byte. |
| id | short | r/w | Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya. |
| minimal_version | int | r | Mendapatkan versi PSD minimal yang diperlukan. |
| name | string | r/w | Mendapatkan atau mengatur nama sumber daya. String Pascal, dipadding agar ukuran genap (nama null terdiri dari dua byte 0). |
| signature | int | r | Mendapatkan signature sumber daya. Harus selalu '8BIM'. |
| ukuran | int | r | Mendapatkan ukuran blok sumber daya dalam byte termasuk datanya. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream)](#save_stream_1) | Menyimpan blok sumber daya ke aliran yang ditentukan. |
| validate_values() | Memvalidasi nilai sumber daya. |


### Constructor: BackgroundColorResource() {#BackgroundColorResource__1}


```
 BackgroundColorResource() 
```

Menginisialisasi sebuah instance baru dari kelas BackgroundColorResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Menyimpan blok sumber daya ke aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Aliran untuk menyimpan blok sumber daya. |

