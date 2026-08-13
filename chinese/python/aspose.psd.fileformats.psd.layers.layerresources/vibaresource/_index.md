---
title: "VibAResource 类"
type: docs
weight: 1090
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/
---

**Summary:** VibA Resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VibAResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VibAResource()](#VibAResource__1) | 初始化一个新的 [VibAResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| key | int | r | 获取图层资源键。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| 饱和度 | int | 读/写 | 获取或设置饱和度值 |
| signature | int | r | 获取签名。 |
| 活力 | int | 读/写 | 获取或设置活力值 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 将资源保存到指定的流容器。 |


### Constructor: VibAResource() {#VibAResource__1}


```
 VibAResource() 
```

初始化一个新的 [VibAResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/) 类实例。

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

