---
title: "FilterEffectMaskData klass"
type: docs
weight: 310
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Summary:** The filter mask data class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FilterEffectMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask)](#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1) | Initierar en ny instans av [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Hämtar kanalerna. |
| guid | string | r | Hämtar GUID:en. |
| längd | int | r | Hämtar filtermaskdatas längd i byte. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Hämtar bladmaskens rektangel. |
| max_channels | int | r | Hämtar maxantalet kanaler. |
| pixels_depth | int | r | Hämtar pixeldjupet. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Hämtar kanalernas rektangel. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Hämtar bladmasken. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Hämtar användarmasken. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save_data(stream_container)](#save_data_stream_container_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) {#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1}


```
 FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) 
```

Initierar en ny instans av [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| guid | string | Resursens GUID. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Kanalernas rektangel. |
| pixels_depth | int | Pixeldjupet. |
| max_channels | int | Det maximala kanalvärdet. |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Kanalerna. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Användarmasken. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Bladmaskens rektangel. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Bladmasken. |

### Method: save_data(stream_container) {#save_data_stream_container_1}


```
 save_data(stream_container) 
```

Sparar resursen till den angivna strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren att spara till. |

