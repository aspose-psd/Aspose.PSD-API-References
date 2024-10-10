---
title: BlncResource Class
type: docs
weight: 40
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Summary:** BlncResource class is a resource of Color Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlncResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.8.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BlncResource()](#BlncResource__1) | Initializes a new instance of the [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| highlights_cyan_red_balance | short | r/w | Gets or sets the Highlights Cyan Red Balance. |
| highlights_magenta_green_balance | short | r/w | Gets or sets the Highlights Magenta Green Balance. |
| highlights_yellow_blue_balance | short | r/w | Gets or sets the Highlights Yellow Blue Balance. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| midtones_cyan_red_balance | short | r/w | Gets or sets the Midtones Cyan Red Balance. |
| midtones_magenta_green_balance | short | r/w | Gets or sets the Midtones Magenta Green Balance. |
| midtones_yellow_blue_balance | short | r/w | Gets or sets the Midtones Yellow Blue Balance. |
| preserve_luminosity | bool | r/w | Gets or sets a value indicating whether this [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) preserves luminosity. |
| psd_version | int | r | Gets the PSD version. |
| shadows_cyan_red_balance | short | r/w | Gets or sets the Shadows Cyan Red Balance. |
| shadows_magenta_green_balance | short | r/w | Gets or sets the Shadows Magenta Green Balance. |
| shadows_yellow_blue_balance | short | r/w | Gets or sets the Shadows Yellow Blue Balance. |
| signature | int | r | Gets the signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: BlncResource() {#BlncResource__1}


```
 BlncResource() 
```

Initializes a new instance of the [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) class.

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

