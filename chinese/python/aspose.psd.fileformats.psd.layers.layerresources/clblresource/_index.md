---
title: "ClblResource 类"
type: docs
weight: 160
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/
---

**Summary:** Class ClblResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ClblResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ClblResource()](#ClblResource__1) | 初始化一个新的 [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) 类实例。 |
| [ClblResource(blend_clipped_elements)](#ClblResource_blend_clipped_elements_2) | 初始化一个新的 [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) 类实例。 |
| [ClblResource(data)](#ClblResource_data_3) | 初始化一个新的 [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) 类实例。<br/>            使用自定义或未知值 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| blend_clipped_elements | bool | 读/写 | 获取或设置一个值，指示是否 [混合剪裁元素]。 |
| key | int | r | 获取图层资源键。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| signature | int | r | 获取签名。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 保存指定的流容器。 |


### Constructor: ClblResource() {#ClblResource__1}


```
 ClblResource() 
```

初始化一个新的 [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) 类实例。

### Constructor: ClblResource(blend_clipped_elements) {#ClblResource_blend_clipped_elements_2}


```
 ClblResource(blend_clipped_elements) 
```

初始化一个新的 [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) 类实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| blend_clipped_elements | bool | 如果设置为 <c>true</c> [混合剪裁元素]。 |

### Constructor: ClblResource(data) {#ClblResource_data_3}


```
 ClblResource(data) 
```

初始化一个新的 [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) 类实例。<br/>            使用自定义或未知值

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | byte | 资源数据。 |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

保存指定的流容器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 流容器。 |
| psd_version | int | PSD 版本。 |

