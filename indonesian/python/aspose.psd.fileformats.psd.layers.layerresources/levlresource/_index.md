---
title: "LevlResource Kelas"
type: docs
weight: 490
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---

**Summary:** Class LevlResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LevlResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [LevlResource()](#LevlResource__1) | Menginisialisasi instance baru dari kelas [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/). |
| [LevlResource(bytes)](#LevlResource_bytes_2) | Menginisialisasi instance baru dari kelas [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) .<br/>            Didukung dalam mode warna GrayScale, Duotone, RGB, CMYK, Lab<br/>            2 byte - Versi (=2)<br/>            29 * 10 byte - Set rekaman level dengan 5 integer pendek<br/>            4 byte - Header Lvls (Mulai pada indeks 292)<br/>            2 byte - Versi (=3)<br/>            2 byte - Jumlah total rekaman level<br/>            10 * (Total Count - 29)<br/>            Akhiran nol dari sumber daya Lvls harus dilipat untuk empat juga |
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
| version | short | r | Mendapatkan versi. Defaultnya adalah 2 |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_channel(channel_index)](#get_channel_channel_index_1) | Mendapatkan channel. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: LevlResource() {#LevlResource__1}


```
 LevlResource() 
```

Menginisialisasi instance baru dari kelas [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).

### Constructor: LevlResource(bytes) {#LevlResource_bytes_2}


```
 LevlResource(bytes) 
```

Menginisialisasi instance baru dari kelas [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) .<br/>            Didukung dalam mode warna GrayScale, Duotone, RGB, CMYK, Lab<br/>            2 byte - Versi (=2)<br/>            29 * 10 byte - Set rekaman level dengan 5 integer pendek<br/>            4 byte - Header Lvls (Mulai pada indeks 292)<br/>            2 byte - Versi (=3)<br/>            2 byte - Jumlah total rekaman level<br/>            10 * (Total Count - 29)<br/>            Akhiran nol dari sumber daya Lvls harus dilipat untuk empat juga

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| byte | byte | Byte-byte. |

### Method: get_channel(channel_index) {#get_channel_channel_index_1}


```
 get_channel(channel_index) 
```

Mendapatkan channel.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| channel_index | int | Indeks saluran. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel) | Data Level Saluran |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Menyimpan sumber daya ke kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran untuk disimpan. |
| psd_version | int | Versi PSD. |

