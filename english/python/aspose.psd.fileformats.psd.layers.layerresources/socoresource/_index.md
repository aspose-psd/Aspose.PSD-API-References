---
title: SoCoResource Class
type: docs
weight: 870
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/
---

**Summary:** Class SoCoResource.<br/>            This resource contains information about Color Fill Layers

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SoCoResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.2.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SoCoResource()](#SoCoResource__1) | Initializes a new instance of the [SoCoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Gets the RGB color . |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| psd_version | int | r | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| signature | int | r | Gets the layer resource signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: SoCoResource() {#SoCoResource__1}


```
 SoCoResource() 
```

Initializes a new instance of the [SoCoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/) class.

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

