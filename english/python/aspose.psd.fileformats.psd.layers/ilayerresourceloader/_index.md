---
title: ILayerResourceLoader Class
type: docs
weight: 670
url: /python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---

**Summary:** The layer resource loader.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.ILayerResourceLoader

**Aspose.PSD Version:** 24.8.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container, psd_version)](#can_load_stream_container_psd_version_1) | Determines whether layer resource can be loaded from the specified [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [load(stream_container, psd_version)](#load_stream_container_psd_version_2) | Loads the [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/). |


### Method: can_load(stream_container, psd_version) {#can_load_stream_container_psd_version_1}


```
 can_load(stream_container, psd_version) 
```

Determines whether layer resource can be loaded from the specified [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container. |
| psd_version | int | The PSD version. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if layer resource can be loaded from the specified [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/); otherwise, <c>false</c>. |


### Method: load(stream_container, psd_version) {#load_stream_container_psd_version_2}


```
 load(stream_container, psd_version) 
```

Loads the [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to load from. |
| psd_version | int | The PSD version. |

**Returns**

| Type | Description |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | The loaded resource. |


