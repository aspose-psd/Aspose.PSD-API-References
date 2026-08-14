---
title: "Kelas LyidResource"
type: docs
weight: 660
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/
---

**Summary:** Class LyidResource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LyidResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [LyidResource(bytes)](#LyidResource_bytes_1) | Menginisialisasi instance baru dari kelas [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/).<br/>            Dengan nilai khusus atau tidak diketahui |
| [LyidResource(id)](#LyidResource_id_2) | Menginisialisasi instance baru dari kelas [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
| value | int | r | Mendapatkan nilai. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan ke kontainer aliran yang ditentukan. |


### Constructor: LyidResource(bytes) {#LyidResource_bytes_1}


```
 LyidResource(bytes) 
```

Menginisialisasi instance baru dari kelas [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/).<br/>            Dengan nilai khusus atau tidak diketahui

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| byte | byte | Byte-byte. |

### Constructor: LyidResource(id) {#LyidResource_id_2}


```
 LyidResource(id) 
```

Menginisialisasi instance baru dari kelas [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| id | int | Pengidentifikasi lapisan. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Menyimpan ke kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran. |
| psd_version | int | Versi PSD. |

