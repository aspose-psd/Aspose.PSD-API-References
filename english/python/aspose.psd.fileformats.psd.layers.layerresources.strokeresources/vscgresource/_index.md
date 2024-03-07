---
title: VscgResource Class
type: docs
weight: 30
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/
---

**Summary:** Vector Stroke Content Data resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VscgResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.1.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VscgResource()](#VscgResource__1) | Initializes a new instance of the VscgResource class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r | Gets or sets the structure items. |
| key | int | r | Gets the layer resource key. |
| key_for_data | int | r | Integer key that defines what kind of fill settings is tored in the resource:<br/>            * Color - 0x536f436f - SoCoResource.TypeToolKey<br/>            * Gradient - 0x4764466c - GdFlResource.TypeToolKey<br/>            * Pattern - 0x5074466c - PtFlResource.TypeToolKey |
| length | int | r | Gets the layer resource length in bytes. |
| psd_version | int | r | Gets the psd version. |
| signature | int | r | Gets the signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: VscgResource() {#VscgResource__1}


```
 VscgResource() 
```

Initializes a new instance of the VscgResource class

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

