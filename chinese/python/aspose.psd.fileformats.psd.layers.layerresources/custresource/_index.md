---
title: "CustResource 类"
type: docs
weight: 230
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/
---

**Summary:** Class CustResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CustResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CustResource()](#CustResource__1) | 初始化一个新的 [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) 类实例。 |
| [CustResource(data)](#CustResource_data_2) | 初始化一个新的 [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| key | int | r | 获取图层资源键。 |
| layer_created_date_time | datetime | 读/写 | 获取或设置图层创建日期。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| signature | int | r | 获取签名。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 将资源保存到指定的流容器。 |


### Constructor: CustResource() {#CustResource__1}


```
 CustResource() 
```

初始化一个新的 [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) 类实例。

### Constructor: CustResource(data) {#CustResource_data_2}


```
 CustResource(data) 
```

初始化一个新的 [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) 类实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | byte | 资源的数据。 |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

将资源保存到指定的流容器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 要保存到的流容器。 |
| psd_version | int | PSD 版本。 |

