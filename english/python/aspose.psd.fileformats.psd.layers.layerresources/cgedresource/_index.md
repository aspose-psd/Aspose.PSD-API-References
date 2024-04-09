---
title: CgEdResource Class
type: docs
weight: 90
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Summary:** Class CgEdResource. Content Generator Extra Data (Photoshop CS5)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CgEdResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.2.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CgEdResource()](#CgEdResource__1) | Initializes a new instance of the CgEdResource class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| auto | bool | r/w | Gets or sets a value indicating whether this [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) is automatic. |
| brightness | int | r/w | Gets or sets the brightness. |
| contrast | int | r/w | Gets or sets the contrast. |
| key | int | r | Gets the layer resource key. |
| lab_color | bool | r/w | Gets or sets a value indicating whether [lab color] is used. |
| length | int | r | Gets the layer resource length in bytes. |
| mean_value_for_brightness_and_contrast | int | r/w | Gets or sets the mean value for brightness and contrast. |
| psd_version | int | r | Gets the psd version. |
| signature | int | r | Gets the signature. |
| use_legacy | bool | r/w | Gets or sets a value indicating whether [use legacy]. |
| version | int | r/w | Gets or sets the version. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: CgEdResource() {#CgEdResource__1}


```
 CgEdResource() 
```

Initializes a new instance of the CgEdResource class

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

