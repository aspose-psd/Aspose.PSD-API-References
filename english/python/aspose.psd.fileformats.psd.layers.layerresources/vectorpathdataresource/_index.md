---
title: VectorPathDataResource Class
type: docs
weight: 1030
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/
---

**Summary:** Class VectorPathDataResource.<br/>            This resource contains information about vector layer mask

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VectorPathDataResource

**Inheritance:** IVectorPathData, LayerResource

**Aspose.PSD Version:** 23.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| is_disabled | bool | r/w | Gets or sets a value indicating whether this instance is disabled. |
| is_inverted | bool | r/w | Gets or sets a value indicating whether this instance is inverted. |
| is_not_linked | bool | r/w | Gets or sets a value indicating whether this instance is not linked. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Gets or sets the path records. |
| psd_version | int | r | Gets the psd version. |
| signature | int | r | Gets the signature. |
| version | int | r/w | Gets or sets the version. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Saves the resource to the specified stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to save to. |
| psd_version | int | The PSD version. |

