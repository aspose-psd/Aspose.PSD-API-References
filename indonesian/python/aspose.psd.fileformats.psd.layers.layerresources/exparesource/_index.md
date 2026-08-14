---
title: "Kelas ExpaResource"
type: docs
weight: 280
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/
---

**Summary:** Class ExpaResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ExpaResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [ExpaResource()](#ExpaResource__1) | Menginisialisasi instance baru dari kelas [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/). |
| [ExpaResource(bytes)](#ExpaResource_bytes_2) | Menginisialisasi instance baru dari kelas [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/). |
| [ExpaResource(exposure, offset, gamma)](#ExpaResource_exposure_offset_gamma_3) | Menginisialisasi instance baru dari kelas [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| eksposur | float | r/w | Mendapatkan atau mengatur eksposur. |
| koreksi_gamma | float | r/w | Mendapatkan atau mengatur gamma. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| offset | float | r/w | Mendapatkan atau mengatur offset. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
| version | short | r | Mendapatkan versi. Default adalah 1 |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: ExpaResource() {#ExpaResource__1}


```
 ExpaResource() 
```

Menginisialisasi instance baru dari kelas [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/).

### Constructor: ExpaResource(bytes) {#ExpaResource_bytes_2}


```
 ExpaResource(bytes) 
```

Menginisialisasi instance baru dari kelas [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| byte | byte | Byte-byte. |

### Constructor: ExpaResource(exposure, offset, gamma) {#ExpaResource_exposure_offset_gamma_3}


```
 ExpaResource(exposure, offset, gamma) 
```

Menginisialisasi instance baru dari kelas [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| eksposur | float | Eksposur. |
| offset | float | Offset. |
| gamma | float | Gamma. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Menyimpan sumber daya ke kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran untuk disimpan. |
| psd_version | int | Versi PSD. |

