---
title: "ILayerResourceLoader 类"
type: docs
weight: 720
url: /zh/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---

**Summary:** The layer resource loader.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.ILayerResourceLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container, psd_version)](#can_load_stream_container_psd_version_1) | 确定是否可以从指定的 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) 加载图层资源。 |
| [load(stream_container, psd_version)](#load_stream_container_psd_version_2) | 加载 [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/)。 |


### Method: can_load(stream_container, psd_version) {#can_load_stream_container_psd_version_1}


```
 can_load(stream_container, psd_version) 
```

确定是否可以从指定的 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) 加载图层资源。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 流容器。 |
| psd_version | int | PSD 版本。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 表示可以从指定的 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) 加载图层资源；否则为 <c>false</c>。 |


### Method: load(stream_container, psd_version) {#load_stream_container_psd_version_2}


```
 load(stream_container, psd_version) 
```

加载 [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 要加载的流容器。 |
| psd_version | int | PSD 版本。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | 已加载的资源。 |


