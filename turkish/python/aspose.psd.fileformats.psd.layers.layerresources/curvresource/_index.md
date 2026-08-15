---
title: "CurvResource Sınıfı"
type: docs
weight: 190
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Summary:** Class CurvResource. Resource of Curves Adjustment Layer<br/>            1 byte - 0 if use curves, 1 if used pixels on map<br/>            if 0 then:<br/>            2 bytes - short.  Default is 1<br/>            4 bytes - int. Used only last byte by bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            2 bytes - short points count<br/>            4 bytes * count of point - points of curve 2 short: first position, second height<br/>            4 bytes - word "Crv "<br/>            2 bytes - short default is 4 for Curves<br/>            4 bytes - int. Default is 1<br/>            4 bytes - point count<br/>            4 bytes * point count - points of curve 2 short: first position, second height<br/>            0-4 bytes - Leading to be fold for four<br/>            if 1 then:<br/>            2 bytes - short. Default is 1<br/>            4 bytes - int. Used only last byte. One channel is in one bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            256 * count of changed channels - ordered values of channel in range 0 - 255<br/>            4 bytes - word "Crv "<br/>            2 bytes - short. Default is 3 for pixels on map<br/>            4 bytes - int Channel count<br/>            (2 + 256) bytes - short 2 for channel index, 256 is ordered values of channel in range 0 - 255

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [CurvResource(bytes)](#CurvResource_bytes_1) | [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) sınıfının yeni bir örneğini başlatır. |
| [CurvResource(max_channel_count)](#CurvResource_max_channel_count_2) | [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| is_data_stored_discretely | bool | r/w | Bu örneğin verisinin ayrı ayrı depolanıp depolanmadığını gösteren bir değeri alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_active_manager()](#get_active_manager__1) | Etkin yöneticiyi alır. |
| [get_channel_data(channel_index)](#get_channel_data_channel_index_2) | Kanal verilerini alır. |
| [get_curve_manager()](#get_curve_manager__3) | Eğri yöneticisini alır. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_4) | Kaynağı belirtilen akış konteynerine kaydeder. |


### Constructor: CurvResource(bytes) {#CurvResource_bytes_1}


```
 CurvResource(bytes) 
```

[CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bayt | byte | Baytlar. |

### Constructor: CurvResource(max_channel_count) {#CurvResource_max_channel_count_2}


```
 CurvResource(max_channel_count) 
```

[CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| max_channel_count | int | Maksimum kanal sayısı. |

### Method: get_active_manager() {#get_active_manager__1}


```
 get_active_manager() 
```

Etkin yöneticiyi alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | Aktif yönetici |


### Method: get_channel_data(channel_index) {#get_channel_data_channel_index_2}


```
 get_channel_data(channel_index) 
```

Kanal verilerini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| channel_index | int | Kanalın indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| byte | Kanal verileri |


### Method: get_curve_manager() {#get_curve_manager__3}


```
 get_curve_manager() 
```

Eğri yöneticisini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) veya [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_4}


```
 save(stream_container, psd_version) 
```

Kaynağı belirtilen akış konteynerine kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kaydedilecek akış konteyneri. |
| psd_version | int | PSD sürümü. |

