---
title: "Kelas MixrResource"
type: docs
weight: 680
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Summary:** Class MixrResource. Resource of Channel Mixer Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MixrResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [MixrResource()](#MixrResource__1) | Menginisialisasi sebuah instance baru dari kelas [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/).<br/>            Spesifikasi format PSD berisi deskripsi berikut:<br/>            2 Versi ( = 1)<br/>            2 Monokrom<br/>            20 warna RGB atau CMYK plus konstanta untuk pengaturan mixer. 4 * 2 byte warna dengan 2 byte konstanta. |
| [MixrResource(data)](#MixrResource_data_2) | Menginisialisasi sebuah instance baru dari kelas [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/).<br/>            Spesifikasi format PSD berisi deskripsi berikut:<br/>            2 Versi ( = 1)<br/>            2 Monokrom<br/>            20 warna RGB atau CMYK plus konstanta untuk pengaturan mixer. 4 * 2 byte warna dengan 2 byte konstanta. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| monochrome | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) ini monokrom. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
| version | short | r/w | Mendapatkan atau mengatur versi. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_channel_info(channel_index)](#get_channel_info_channel_index_1) | Mendapatkan data mentah informasi saluran |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| [set_channel_info(channel_index, value)](#set_channel_info_channel_index_value_3) | Mengatur informasi saluran. |


### Constructor: MixrResource() {#MixrResource__1}


```
 MixrResource() 
```

Menginisialisasi sebuah instance baru dari kelas [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/).<br/>            Spesifikasi format PSD berisi deskripsi berikut:<br/>            2 Versi ( = 1)<br/>            2 Monokrom<br/>            20 warna RGB atau CMYK plus konstanta untuk pengaturan mixer. 4 * 2 byte warna dengan 2 byte konstanta.

### Constructor: MixrResource(data) {#MixrResource_data_2}


```
 MixrResource(data) 
```

Menginisialisasi sebuah instance baru dari kelas [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/).<br/>            Spesifikasi format PSD berisi deskripsi berikut:<br/>            2 Versi ( = 1)<br/>            2 Monokrom<br/>            20 warna RGB atau CMYK plus konstanta untuk pengaturan mixer. 4 * 2 byte warna dengan 2 byte konstanta.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | byte | Data sumber daya. |

### Method: get_channel_info(channel_index) {#get_channel_info_channel_index_1}


```
 get_channel_info(channel_index) 
```

Mendapatkan data mentah informasi saluran

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| channel_index | int | Indeks saluran. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| byte | Array byte mentah dari informasi saluran. |


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

### Method: set_channel_info(channel_index, value) {#set_channel_info_channel_index_value_3}


```
 set_channel_info(channel_index, value) 
```

Mengatur informasi saluran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| channel_index | int | Indeks saluran. |
| value | byte | Nilai value. |

