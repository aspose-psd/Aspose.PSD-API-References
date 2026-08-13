---
title: "FilterEffectMaskData 类"
type: docs
weight: 310
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Summary:** The filter mask data class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FilterEffectMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask)](#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1) | 初始化 [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | 获取通道。 |
| guid | 字符串 | r | 获取 GUID。 |
| 长度 | int | r | 获取过滤掩码数据的字节长度。 |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | 获取 sheet mask 矩形。 |
| max_channels | int | r | 获取通道计数的最大值。 |
| pixels_depth | int | r | 获取像素深度。 |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | 获取通道矩形。 |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | 获取 sheet mask。 |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | 获取用户掩码。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save_data(stream_container)](#save_data_stream_container_1) | 将资源保存到指定的流容器。 |


### Constructor: FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) {#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1}


```
 FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) 
```

初始化 [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| guid | 字符串 | 资源 guid。 |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 通道矩形。 |
| pixels_depth | int | 像素深度。 |
| max_channels | int | 最大通道值。 |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | 通道。 |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | 用户蒙版。 |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 工作表蒙版矩形。 |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | 工作表蒙版。 |

### Method: save_data(stream_container) {#save_data_stream_container_1}


```
 save_data(stream_container) 
```

将资源保存到指定的流容器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 要保存到的流容器。 |

