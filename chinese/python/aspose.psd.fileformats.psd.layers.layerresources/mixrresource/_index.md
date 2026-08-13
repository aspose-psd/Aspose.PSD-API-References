---
title: "MixrResource 类"
type: docs
weight: 680
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Summary:** Class MixrResource. Resource of Channel Mixer Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MixrResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MixrResource()](#MixrResource__1) | 初始化 [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) 类的新实例。<br/>            PSD 格式规范包含以下描述：<br/>            2 版本 (= 1)<br/>            2 单色<br/>            20 RGB 或 CMYK 颜色加上混合器设置的常量。4 * 2 字节的颜色加 2 字节的常量。 |
| [MixrResource(data)](#MixrResource_data_2) | 初始化 [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) 类的新实例。<br/>            PSD 格式规范包含以下描述：<br/>            2 版本 (= 1)<br/>            2 单色<br/>            20 RGB 或 CMYK 颜色加上混合器设置的常量。4 * 2 字节的颜色加 2 字节的常量。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| key | int | r | 获取图层资源键。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| monochrome | bool | r/w | 获取或设置一个值，指示此 [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) 是否为单色。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| signature | int | r | 获取签名。 |
| version | short | 读/写 | 获取或设置版本。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_channel_info(channel_index)](#get_channel_info_channel_index_1) | 获取通道信息原始数据 |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | 将资源保存到指定的流容器。 |
| [set_channel_info(channel_index, value)](#set_channel_info_channel_index_value_3) | 设置通道信息。 |


### Constructor: MixrResource() {#MixrResource__1}


```
 MixrResource() 
```

初始化 [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) 类的新实例。<br/>            PSD 格式规范包含以下描述：<br/>            2 版本 (= 1)<br/>            2 单色<br/>            20 RGB 或 CMYK 颜色加上混合器设置的常量。4 * 2 字节的颜色加 2 字节的常量。

### Constructor: MixrResource(data) {#MixrResource_data_2}


```
 MixrResource(data) 
```

初始化 [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) 类的新实例。<br/>            PSD 格式规范包含以下描述：<br/>            2 版本 (= 1)<br/>            2 单色<br/>            20 RGB 或 CMYK 颜色加上混合器设置的常量。4 * 2 字节的颜色加 2 字节的常量。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | byte | 资源的数据。 |

### Method: get_channel_info(channel_index) {#get_channel_info_channel_index_1}


```
 get_channel_info(channel_index) 
```

获取通道信息原始数据

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| channel_index | int | 通道的索引。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| byte | 通道信息的原始字节数组。 |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

将资源保存到指定的流容器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 要保存到的流容器。 |
| psd_version | int | PSD 版本。 |

### Method: set_channel_info(channel_index, value) {#set_channel_info_channel_index_value_3}


```
 set_channel_info(channel_index, value) 
```

设置通道信息。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| channel_index | int | 通道的索引。 |
| value | byte | 值。 |

