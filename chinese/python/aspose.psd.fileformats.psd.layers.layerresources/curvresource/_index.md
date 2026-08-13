---
title: "CurvResource 类"
type: docs
weight: 190
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Summary:** Class CurvResource. Resource of Curves Adjustment Layer<br/>            1 byte - 0 if use curves, 1 if used pixels on map<br/>            if 0 then:<br/>            2 bytes - short.  Default is 1<br/>            4 bytes - int. Used only last byte by bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            2 bytes - short points count<br/>            4 bytes * count of point - points of curve 2 short: first position, second height<br/>            4 bytes - word "Crv "<br/>            2 bytes - short default is 4 for Curves<br/>            4 bytes - int. Default is 1<br/>            4 bytes - point count<br/>            4 bytes * point count - points of curve 2 short: first position, second height<br/>            0-4 bytes - Leading to be fold for four<br/>            if 1 then:<br/>            2 bytes - short. Default is 1<br/>            4 bytes - int. Used only last byte. One channel is in one bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            256 * count of changed channels - ordered values of channel in range 0 - 255<br/>            4 bytes - word "Crv "<br/>            2 bytes - short. Default is 3 for pixels on map<br/>            4 bytes - int Channel count<br/>            (2 + 256) bytes - short 2 for channel index, 256 is ordered values of channel in range 0 - 255

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CurvResource(bytes)](#CurvResource_bytes_1) | 初始化 [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) 类的新实例。 |
| [CurvResource(max_channel_count)](#CurvResource_max_channel_count_2) | 初始化 [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| is_data_stored_discretely | bool | 读/写 | 获取或设置一个值，指示此实例是否以离散方式存储数据。 |
| key | int | r | 获取图层资源键。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| signature | int | r | 获取签名。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_active_manager()](#get_active_manager__1) | 获取活动管理器。 |
| [get_channel_data(channel_index)](#get_channel_data_channel_index_2) | 获取通道数据。 |
| [get_curve_manager()](#get_curve_manager__3) | 获取曲线管理器。 |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_4) | 将资源保存到指定的流容器。 |


### Constructor: CurvResource(bytes) {#CurvResource_bytes_1}


```
 CurvResource(bytes) 
```

初始化 [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 字节 | byte | 这些字节。 |

### Constructor: CurvResource(max_channel_count) {#CurvResource_max_channel_count_2}


```
 CurvResource(max_channel_count) 
```

初始化 [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| max_channel_count | int | 最大通道数。 |

### Method: get_active_manager() {#get_active_manager__1}


```
 get_active_manager() 
```

获取活动管理器。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | 活动管理器 |


### Method: get_channel_data(channel_index) {#get_channel_data_channel_index_2}


```
 get_channel_data(channel_index) 
```

获取通道数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| channel_index | int | 通道的索引。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| byte | 通道数据 |


### Method: get_curve_manager() {#get_curve_manager__3}


```
 get_curve_manager() 
```

获取曲线管理器。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) 或 [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_4}


```
 save(stream_container, psd_version) 
```

将资源保存到指定的流容器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 要保存到的流容器。 |
| psd_version | int | PSD 版本。 |

