---
title: "LevlResource Sınıfı"
type: docs
weight: 490
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---

**Summary:** Class LevlResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LevlResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [LevlResource()](#LevlResource__1) | [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) sınıfının yeni bir örneğini başlatır. |
| [LevlResource(bytes)](#LevlResource_bytes_2) | [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) sınıfının yeni bir örneğini başlatır.<br/>            GrayScale, Duotone, RGB, CMYK, Lab renk modlarında desteklenir<br/>            2 bayt - Versiyon (=2)<br/>            29 * 10 bayt - 5 kısa tam sayı içeren seviye kayıtları seti<br/>            4 bayt - Lvls başlığı (292 indeksinde başlar)<br/>            2 bayt - Versiyon (=3)<br/>            2 bayt - Toplam seviye kaydı sayısı<br/>            10 * (Toplam Sayı - 29)<br/>            Lvls kaynağının sıfır sonu da dört için katlanmalıdır |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
| version | short | r | Sürümü alır. Varsayılan 2'dir. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_channel(channel_index)](#get_channel_channel_index_1) | Kanalı alır. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Kaynağı belirtilen akış konteynerine kaydeder. |


### Constructor: LevlResource() {#LevlResource__1}


```
 LevlResource() 
```

[LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) sınıfının yeni bir örneğini başlatır.

### Constructor: LevlResource(bytes) {#LevlResource_bytes_2}


```
 LevlResource(bytes) 
```

[LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) sınıfının yeni bir örneğini başlatır.<br/>            GrayScale, Duotone, RGB, CMYK, Lab renk modlarında desteklenir<br/>            2 bayt - Versiyon (=2)<br/>            29 * 10 bayt - 5 kısa tam sayı içeren seviye kayıtları seti<br/>            4 bayt - Lvls başlığı (292 indeksinde başlar)<br/>            2 bayt - Versiyon (=3)<br/>            2 bayt - Toplam seviye kaydı sayısı<br/>            10 * (Toplam Sayı - 29)<br/>            Lvls kaynağının sıfır sonu da dört için katlanmalıdır

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bayt | byte | Baytlar. |

### Method: get_channel(channel_index) {#get_channel_channel_index_1}


```
 get_channel(channel_index) 
```

Kanalı alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| channel_index | int | Kanalın indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel) | Kanalın Seviye Verileri |


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

