---
title: "Kelas UnknownResource"
type: docs
weight: 280
url: /id/python-net/aspose.psd.fileformats.psd.resources/unknownresource/
---

**Summary:** The unknown resource. When a resource block is not recognized then this resource block is created.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.UnknownResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Signature sumber daya ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Signature sumber daya Photoshop standar. |
| data | byte | r | Mendapatkan data sumber daya. |
| data_size | int | r | Mendapatkan ukuran data sumber daya dalam byte. |
| id | short | r/w | Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya. |
| minimal_version | int | r | Mendapatkan versi psd minimal yang diperlukan. |
| name | string | r/w | Mendapatkan atau mengatur nama sumber daya. String Pascal, dipadding agar ukuran genap (nama null terdiri dari dua byte 0). |
| signature | int | r | Mendapatkan signature sumber daya. Harus selalu '8BIM'. |
| ukuran | int | r | Mendapatkan ukuran blok sumber daya dalam byte termasuk datanya. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream)](#save_stream_1) | Menyimpan blok sumber daya ke aliran yang ditentukan. |
| validate_values() | Memvalidasi nilai sumber daya. |


### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Menyimpan blok sumber daya ke aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Aliran untuk menyimpan blok sumber daya. |

