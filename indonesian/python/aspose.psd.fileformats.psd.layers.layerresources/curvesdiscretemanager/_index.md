---
title: "Kelas CurvesDiscreteManager"
type: docs
weight: 210
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates pixels' map

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesDiscreteManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Mendapatkan jumlah saluran maksimum. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_value_in_position(channel_index, position)](#get_value_in_position_channel_index_position_1) | Mendapatkan nilai pada posisi. |
| [set_to_default_value_in_position(channel_index, position)](#set_to_default_value_in_position_channel_index_position_2) | Mengatur ke nilai default pada posisi. |
| [set_value_in_position(channel_index, position, value)](#set_value_in_position_channel_index_position_value_3) | Mengatur nilai pada posisi. |
| [set_value_of_whole_channel(channel_index, channel_value)](#set_value_of_whole_channel_channel_index_channel_value_4) | Mengatur nilai seluruh saluran. |


### Method: get_value_in_position(channel_index, position) {#get_value_in_position_channel_index_position_1}


```
 get_value_in_position(channel_index, position) 
```

Mendapatkan nilai pada posisi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| channel_index | int | Indeks saluran. |
| posisi | byte | Posisi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| byte | Nilai kurva berdasarkan posisinya |


### Method: set_to_default_value_in_position(channel_index, position) {#set_to_default_value_in_position_channel_index_position_2}


```
 set_to_default_value_in_position(channel_index, position) 
```

Mengatur ke nilai default pada posisi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| channel_index | int | Indeks saluran. |
| posisi | byte | Posisi. |

### Method: set_value_in_position(channel_index, position, value) {#set_value_in_position_channel_index_position_value_3}


```
 set_value_in_position(channel_index, position, value) 
```

Mengatur nilai pada posisi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| channel_index | int | Indeks saluran. |
| posisi | byte | Posisi. |
| value | byte | Nilai value. |

### Method: set_value_of_whole_channel(channel_index, channel_value) {#set_value_of_whole_channel_channel_index_channel_value_4}


```
 set_value_of_whole_channel(channel_index, channel_value) 
```

Mengatur nilai seluruh saluran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| channel_index | int | Indeks saluran. |
| channel_value | byte | Nilai saluran. |

