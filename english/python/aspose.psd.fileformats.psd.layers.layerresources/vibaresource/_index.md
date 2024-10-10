---
title: VibAResource Class
type: docs
weight: 1040
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/
---

**Summary:** VibA Resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VibAResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.8.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VibAResource()](#VibAResource__1) | Initializes a new instance of the [VibAResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| psd_version | int | r | Gets the psd version. |
| saturation | int | r/w | Gets or sets saturation value |
| signature | int | r | Gets the signature. |
| vibrance | int | r/w | Gets or sets vibrance value |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: VibAResource() {#VibAResource__1}


```
 VibAResource() 
```

Initializes a new instance of the [VibAResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/) class.

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

