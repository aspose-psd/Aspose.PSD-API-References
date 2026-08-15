---
title: "FilterEffectMaskData Sınıfı"
type: docs
weight: 310
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Summary:** The filter mask data class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FilterEffectMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask)](#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1) | Yeni bir [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) sınıf örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Kanalları alır. |
| guid | string | r | GUID'i alır. |
| uzunluk | int | r | Filtre maske veri uzunluğunu bayt cinsinden alır. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Sayfa maske dikdörtgenini alır. |
| max_channels | int | r | Kanal sayısının maksimumunu alır. |
| pixels_depth | int | r | Piksel derinliğini alır. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Kanal dikdörtgenini alır. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Sayfa maskesini alır. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Kullanıcı maskesini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save_data(stream_container)](#save_data_stream_container_1) | Kaynağı belirtilen akış konteynerine kaydeder. |


### Constructor: FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) {#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1}


```
 FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) 
```

Yeni bir [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) sınıf örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| guid | string | Kaynak guid'i. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Kanal dikdörtgeni. |
| pixels_depth | int | Piksel derinliği. |
| max_channels | int | Maksimum kanal değeri. |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Kanallar. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Kullanıcı maskesi. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Sayfa maskesi dikdörtgeni. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Sayfa maskesi. |

### Method: save_data(stream_container) {#save_data_stream_container_1}


```
 save_data(stream_container) 
```

Kaynağı belirtilen akış konteynerine kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kaydedilecek akış konteyneri. |

