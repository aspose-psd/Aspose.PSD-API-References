---
title: "CurvesDiscreteManager Sınıfı"
type: docs
weight: 210
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates pixels' map

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesDiscreteManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Maksimum kanal sayısını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_value_in_position(channel_index, position)](#get_value_in_position_channel_index_position_1) | Pozisyondaki değeri alır. |
| [set_to_default_value_in_position(channel_index, position)](#set_to_default_value_in_position_channel_index_position_2) | Pozisyondaki değeri varsayılan değere ayarlar. |
| [set_value_in_position(channel_index, position, value)](#set_value_in_position_channel_index_position_value_3) | Pozisyondaki değeri ayarlar. |
| [set_value_of_whole_channel(channel_index, channel_value)](#set_value_of_whole_channel_channel_index_channel_value_4) | Tüm kanalın değerini ayarlar. |


### Method: get_value_in_position(channel_index, position) {#get_value_in_position_channel_index_position_1}


```
 get_value_in_position(channel_index, position) 
```

Pozisyondaki değeri alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| channel_index | int | Kanalın indeksi. |
| konum | byte | Pozisyon. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| byte | Eğrinin konumuna göre değeri |


### Method: set_to_default_value_in_position(channel_index, position) {#set_to_default_value_in_position_channel_index_position_2}


```
 set_to_default_value_in_position(channel_index, position) 
```

Pozisyondaki değeri varsayılan değere ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| channel_index | int | Kanalın indeksi. |
| konum | byte | Pozisyon. |

### Method: set_value_in_position(channel_index, position, value) {#set_value_in_position_channel_index_position_value_3}


```
 set_value_in_position(channel_index, position, value) 
```

Pozisyondaki değeri ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| channel_index | int | Kanalın indeksi. |
| konum | byte | Pozisyon. |
| değer | byte | Değer. |

### Method: set_value_of_whole_channel(channel_index, channel_value) {#set_value_of_whole_channel_channel_index_channel_value_4}


```
 set_value_of_whole_channel(channel_index, channel_value) 
```

Tüm kanalın değerini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| channel_index | int | Kanalın indeksi. |
| channel_value | byte | Kanal değeri. |

