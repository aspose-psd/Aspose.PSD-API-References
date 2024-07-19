---
title: Lfx2Resource Class
type: docs
weight: 460
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/lfx2resource/
---

**Summary:** Lfx2 resource (effects resource)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Lfx2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.5.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Lfx2Resource()](#Lfx2Resource__1) | Initializes a new instance of the Lfx2Resource class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| descriptor_version | int | r | Gets the descriptor version. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| psd_version | int | r | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| signature | int | r | Gets the layer resource signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: Lfx2Resource() {#Lfx2Resource__1}


```
 Lfx2Resource() 
```

Initializes a new instance of the Lfx2Resource class

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

