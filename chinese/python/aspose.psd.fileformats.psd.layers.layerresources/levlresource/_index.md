---
title: "LevlResource 类"
type: docs
weight: 490
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---

**Summary:** Class LevlResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LevlResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LevlResource()](#LevlResource__1) | 初始化 [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) 类的新实例。 |
| [LevlResource(bytes)](#LevlResource_bytes_2) | 初始化 [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) 类的新实例。<br/>            支持 GrayScale、Duotone、RGB、CMYK、Lab 颜色模式<br/>            2 字节 - 版本 (=2)<br/>            29 * 10 字节 - 含 5 个短整数的级别记录集合<br/>            4 字节 - Lvls 头部（起始于索引 292）<br/>            2 字节 - 版本 (=3)<br/>            2 字节 - 总级别记录计数<br/>            10 * (总计数 - 29)<br/>            Lvls 资源的零结尾应为四的倍数 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| key | int | r | 获取图层资源键。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| signature | int | r | 获取签名。 |
| version | short | r | 获取版本。默认值为 2。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_channel(channel_index)](#get_channel_channel_index_1) | 获取通道。 |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | 将资源保存到指定的流容器。 |


### Constructor: LevlResource() {#LevlResource__1}


```
 LevlResource() 
```

初始化 [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) 类的新实例。

### Constructor: LevlResource(bytes) {#LevlResource_bytes_2}


```
 LevlResource(bytes) 
```

初始化 [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) 类的新实例。<br/>            支持 GrayScale、Duotone、RGB、CMYK、Lab 颜色模式<br/>            2 字节 - 版本 (=2)<br/>            29 * 10 字节 - 含 5 个短整数的级别记录集合<br/>            4 字节 - Lvls 头部（起始于索引 292）<br/>            2 字节 - 版本 (=3)<br/>            2 字节 - 总级别记录计数<br/>            10 * (总计数 - 29)<br/>            Lvls 资源的零结尾应为四的倍数

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 字节 | byte | 这些字节。 |

### Method: get_channel(channel_index) {#get_channel_channel_index_1}


```
 get_channel(channel_index) 
```

获取通道。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| channel_index | int | 通道的索引。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel) | 通道的级别数据 |


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

