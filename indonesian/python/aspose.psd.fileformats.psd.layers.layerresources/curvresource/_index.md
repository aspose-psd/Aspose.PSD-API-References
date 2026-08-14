---
title: "CurvResource Kelas"
type: docs
weight: 190
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Summary:** Class CurvResource. Resource of Curves Adjustment Layer<br/>            1 byte - 0 if use curves, 1 if used pixels on map<br/>            if 0 then:<br/>            2 bytes - short.  Default is 1<br/>            4 bytes - int. Used only last byte by bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            2 bytes - short points count<br/>            4 bytes * count of point - points of curve 2 short: first position, second height<br/>            4 bytes - word "Crv "<br/>            2 bytes - short default is 4 for Curves<br/>            4 bytes - int. Default is 1<br/>            4 bytes - point count<br/>            4 bytes * point count - points of curve 2 short: first position, second height<br/>            0-4 bytes - Leading to be fold for four<br/>            if 1 then:<br/>            2 bytes - short. Default is 1<br/>            4 bytes - int. Used only last byte. One channel is in one bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            256 * count of changed channels - ordered values of channel in range 0 - 255<br/>            4 bytes - word "Crv "<br/>            2 bytes - short. Default is 3 for pixels on map<br/>            4 bytes - int Channel count<br/>            (2 + 256) bytes - short 2 for channel index, 256 is ordered values of channel in range 0 - 255

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [CurvResource(bytes)](#CurvResource_bytes_1) | Menginisialisasi instance baru dari kelas [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/). |
| [CurvResource(max_channel_count)](#CurvResource_max_channel_count_2) | Menginisialisasi instance baru dari kelas [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| is_data_stored_discretely | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini menyimpan data secara terpisah. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_active_manager()](#get_active_manager__1) | Mendapatkan manajer aktif. |
| [get_channel_data(channel_index)](#get_channel_data_channel_index_2) | Mendapatkan data saluran. |
| [get_curve_manager()](#get_curve_manager__3) | Mendapatkan manajer kurva. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_4) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: CurvResource(bytes) {#CurvResource_bytes_1}


```
 CurvResource(bytes) 
```

Menginisialisasi instance baru dari kelas [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| byte | byte | Byte-byte. |

### Constructor: CurvResource(max_channel_count) {#CurvResource_max_channel_count_2}


```
 CurvResource(max_channel_count) 
```

Menginisialisasi instance baru dari kelas [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| max_channel_count | int | Jumlah saluran maksimum. |

### Method: get_active_manager() {#get_active_manager__1}


```
 get_active_manager() 
```

Mendapatkan manajer aktif.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | Manajer aktif |


### Method: get_channel_data(channel_index) {#get_channel_data_channel_index_2}


```
 get_channel_data(channel_index) 
```

Mendapatkan data saluran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| channel_index | int | Indeks saluran. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| byte | Data saluran |


### Method: get_curve_manager() {#get_curve_manager__3}


```
 get_curve_manager() 
```

Mendapatkan manajer kurva.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) atau [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_4}


```
 save(stream_container, psd_version) 
```

Menyimpan sumber daya ke kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran untuk disimpan. |
| psd_version | int | Versi PSD. |

