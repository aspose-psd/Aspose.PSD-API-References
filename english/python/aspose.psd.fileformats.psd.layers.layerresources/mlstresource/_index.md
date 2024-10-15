---
title: MlstResource Class
type: docs
weight: 690
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/
---

**Summary:** The mlst resource.<br/>            This class, among other things, contains information about the position of the layer on the timeline.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MlstResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MlstResource()](#MlstResource__1) | Initializes a new instance of the MlstResource class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| descriptor_version | int | r | Gets or sets the descriptor version. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r | Gets or sets the structures. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| psd_version | int | r | Gets the psd version. |
| signature | int | r | Gets the signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the specified stream container. |


### Constructor: MlstResource() {#MlstResource__1}


```
 MlstResource() 
```

Initializes a new instance of the MlstResource class

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Saves the specified stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container. |
| psd_version | int | The PSD version. |

