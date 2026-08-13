---
title: "PattResource 类"
type: docs
weight: 770
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Summary:** Class PattResource. Resource with pattern data

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PattResource()](#PattResource__1) | 初始化 [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) 类的新实例。 |
| [PattResource(key, patterns)](#PattResource_key_patterns_2) | 初始化 [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 8 位的 'Patt' 类型工具信息键。 |
| TYPE_TOOL_KEY2 [static] | int | r | 16 位的 'Pat2' 类型工具信息键。 |
| TYPE_TOOL_KEY3 [static] | int | r | 32 位的 'Pat3' 类型工具信息键。 |
| key | int | r | 获取图层资源键。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | r/w | 获取或设置模式数据； |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| signature | int | r | 获取签名。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 保存资源块数据。 |


### Constructor: PattResource() {#PattResource__1}


```
 PattResource() 
```

初始化 [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) 类的新实例。

### Constructor: PattResource(key, patterns) {#PattResource_key_patterns_2}


```
 PattResource(key, patterns) 
```

初始化 [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | int | 资源类型键。 |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | 模式数据。 |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

保存资源块数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 要保存到的流容器。 |
| psd_version | int | PSD 版本。 |

