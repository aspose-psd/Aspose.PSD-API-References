---
title: FilterEffectMaskData Class
type: docs
weight: 270
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Summary:** The filter mask data class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FilterEffectMaskData

**Aspose.PSD Version:** 24.2.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask)](#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1) | Initializes a new instance of the [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Gets the channels. |
| guid | string | r | Gets the GUID. |
| length | int | r | Gets the filter mask data length in bytes. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Gets the sheet mask rectangle. |
| max_channels | int | r | Gets the max of channels count. |
| pixels_depth | int | r | Gets the pixels depth. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Gets the channels rectangle. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Gets the sheet mask. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Gets the user mask. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save_data(stream_container)](#save_data_stream_container_1) | Saves the resource to the specified stream container. |


### Constructor: FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) {#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1}


```
 FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) 
```

Initializes a new instance of the [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| guid | string | The resource guid. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The channels rectangle. |
| pixels_depth | int | The pixels depth. |
| max_channels | int | The max channels value. |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | The channels. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | The user mask. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The sheet mask rectangle. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | The sheet mask. |

### Method: save_data(stream_container) {#save_data_stream_container_1}


```
 save_data(stream_container) 
```

Saves the resource to the specified stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to save to. |

