---
title: BritResource Class
type: docs
weight: 80
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Summary:** Class BritResource. Resource of Brightness/Contrast Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BritResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.4.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BritResource()](#BritResource__1) | Initializes a new instance of the [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) class. |
| [BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color)](#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2) | Initializes a new instance of the [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) class. |
| [BritResource(bytes)](#BritResource_bytes_3) | Initializes a new instance of the [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) class.<br/>            PSD format specification contains following description:<br/>            2 Brightness<br/>            2 Contrast<br/>            2 Mean value for brightness and contrast<br/>            1 Lab color only<br/>            It is not used in modern PSD(CS5 and up) where CgEd is. CgEd stores info properties |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| brightness | short | r/w | Gets or sets the brightness. |
| contrast | short | r/w | Gets or sets the contrast. |
| key | int | r | Gets the layer resource key. |
| lab_color | bool | r/w | Gets or sets a value indicating whether [lab color]. |
| length | int | r | Gets the layer resource length in bytes. |
| mean_value_for_brightness_and_contrast | short | r/w | Gets or sets the mean value for brightness and contrast. |
| psd_version | int | r | Gets the psd version. |
| signature | int | r | Gets the signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: BritResource() {#BritResource__1}


```
 BritResource() 
```

Initializes a new instance of the [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) class.

### Constructor: BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) {#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2}


```
 BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) 
```

Initializes a new instance of the [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness | short | The brightness. |
| contrast | short | The contrast. |
| mean_value_for_brightness_and_contrast | short | The mean value for brightness and contrast. |
| lab_color | bool | if set to <c>true</c> [lab color]. |

### Constructor: BritResource(bytes) {#BritResource_bytes_3}


```
 BritResource(bytes) 
```

Initializes a new instance of the [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) class.<br/>            PSD format specification contains following description:<br/>            2 Brightness<br/>            2 Contrast<br/>            2 Mean value for brightness and contrast<br/>            1 Lab color only<br/>            It is not used in modern PSD(CS5 and up) where CgEd is. CgEd stores info properties

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bytes | byte | The bytes. |

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

