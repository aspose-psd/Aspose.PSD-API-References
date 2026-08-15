---
title: "MixrResource Sınıfı"
type: docs
weight: 680
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Summary:** Class MixrResource. Resource of Channel Mixer Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MixrResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [MixrResource()](#MixrResource__1) | Yeni bir [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) sınıfının yeni bir örneğini başlatır.<br/>            PSD formatı spesifikasyonu aşağıdaki açıklamayı içerir:<br/>            2 Versiyon ( = 1)<br/>            2 Monokrom<br/>            20 RGB veya CMYK renk artı karıştırıcı ayarları için sabit. 4 * 2 bayt renk ve 2 bayt sabit. |
| [MixrResource(data)](#MixrResource_data_2) | Yeni bir [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) sınıfının yeni bir örneğini başlatır.<br/>            PSD formatı spesifikasyonu aşağıdaki açıklamayı içerir:<br/>            2 Versiyon ( = 1)<br/>            2 Monokrom<br/>            20 RGB veya CMYK renk artı karıştırıcı ayarları için sabit. 4 * 2 bayt renk ve 2 bayt sabit. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| monochrome | bool | r/w | Bu [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) monokrom mu olduğunu belirten bir değeri alır veya ayarlar. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
| version | short | r/w | Sürümü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_channel_info(channel_index)](#get_channel_info_channel_index_1) | Kanal bilgisi ham verisini alır. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Kaynağı belirtilen akış konteynerine kaydeder. |
| [set_channel_info(channel_index, value)](#set_channel_info_channel_index_value_3) | Kanal bilgisini ayarlar. |


### Constructor: MixrResource() {#MixrResource__1}


```
 MixrResource() 
```

Yeni bir [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) sınıfının yeni bir örneğini başlatır.<br/>            PSD formatı spesifikasyonu aşağıdaki açıklamayı içerir:<br/>            2 Versiyon ( = 1)<br/>            2 Monokrom<br/>            20 RGB veya CMYK renk artı karıştırıcı ayarları için sabit. 4 * 2 bayt renk ve 2 bayt sabit.

### Constructor: MixrResource(data) {#MixrResource_data_2}


```
 MixrResource(data) 
```

Yeni bir [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) sınıfının yeni bir örneğini başlatır.<br/>            PSD formatı spesifikasyonu aşağıdaki açıklamayı içerir:<br/>            2 Versiyon ( = 1)<br/>            2 Monokrom<br/>            20 RGB veya CMYK renk artı karıştırıcı ayarları için sabit. 4 * 2 bayt renk ve 2 bayt sabit.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | byte | Kaynağın verisi. |

### Method: get_channel_info(channel_index) {#get_channel_info_channel_index_1}


```
 get_channel_info(channel_index) 
```

Kanal bilgisi ham verisini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| channel_index | int | Kanalın indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| byte | Kanal bilgisinin ham bayt dizisi. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Kaynağı belirtilen akış konteynerine kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kaydedilecek akış konteyneri. |
| psd_version | int | PSD sürümü. |

### Method: set_channel_info(channel_index, value) {#set_channel_info_channel_index_value_3}


```
 set_channel_info(channel_index, value) 
```

Kanal bilgisini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| channel_index | int | Kanalın indeksi. |
| değer | byte | Değer. |

