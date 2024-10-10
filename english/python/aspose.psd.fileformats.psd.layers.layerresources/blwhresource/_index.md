---
title: BlwhResource Class
type: docs
weight: 50
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Summary:** BlwhResource class is a resource of Black and White Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlwhResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.8.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BlwhResource()](#BlwhResource__1) | Initializes a new instance of the BlwhResource class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| black_and_white_preset_file_name | string | r/w | Gets or sets the black and white preset file name. |
| blues | int | r/w | Gets or sets the blues value. |
| bw_preset_kind | int | r/w | Gets or sets the black and white preset kind value. |
| cyans | int | r/w | Gets or sets the cyans value. |
| greens | int | r/w | Gets or sets the greens value. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| magentas | int | r/w | Gets or sets the magentas value. |
| psd_version | int | r | Gets the psd version. |
| reds | int | r/w | Gets or sets the reds value. |
| signature | int | r | Gets the signature. |
| tint_color | int | r/w | Gets or sets the Tint Color ARGB value. |
| use_tint | bool | r/w | Gets or sets a value indicating whether [tint color] is used. |
| yellows | int | r/w | Gets or sets the yellows value. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: BlwhResource() {#BlwhResource__1}


```
 BlwhResource() 
```

Initializes a new instance of the BlwhResource class

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

