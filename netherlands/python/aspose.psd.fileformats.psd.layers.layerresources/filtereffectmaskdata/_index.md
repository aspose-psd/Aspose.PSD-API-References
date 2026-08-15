---
title: "FilterEffectMaskData Klasse"
type: docs
weight: 310
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Summary:** The filter mask data class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FilterEffectMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask)](#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1) | Initialiseert een nieuw exemplaar van de [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Haalt de kanalen op. |
| guid | string | r | Haalt de GUID op. |
| lengte | int | r | Haalt de filtermaskergegevenslengte op in bytes. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Haalt de bladmaskerrechthoek op. |
| max_channels | int | r | Haalt het maximum van het aantal kanalen op. |
| pixels_depth | int | r | Haalt de pixeldiepte op. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Haalt de kanaalrechthoek op. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Haalt de bladmasker op. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Haalt de gebruikersmasker op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save_data(stream_container)](#save_data_stream_container_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) {#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1}


```
 FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) 
```

Initialiseert een nieuw exemplaar van de [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| guid | string | De resource guid. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De kanaalrechthoek. |
| pixels_depth | int | De pixeldiepte. |
| max_channels | int | De maximale kanaalwaarde. |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | De kanalen. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | De gebruikersmasker. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De bladmasker rechthoek. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | De bladmasker. |

### Method: save_data(stream_container) {#save_data_stream_container_1}


```
 save_data(stream_container) 
```

Slaat de bron op in de opgegeven streamcontainer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer om in op te slaan. |

