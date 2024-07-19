---
title: TypeToolInfoResource Class
type: docs
weight: 950
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Summary:** The type tool information. For PSD version lower than 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfoResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.5.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TypeToolInfoResource()](#TypeToolInfoResource__1) | Initializes a new instance of the TypeToolInfoResource class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| a_component | short | r/w | Gets or sets a component. |
| b_component | short | r/w | Gets or sets the b component. |
| character_count | int | r/w | Gets or sets the character count. |
| color_space_value | short | r/w | Gets or sets the color space value. |
| font_version | short | r/w | Gets or sets the font version. |
| fonts | [TypeToolFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) | r/w | Gets or sets the fonts. |
| fonts_count | short | r | Gets the fonts count. |
| g_component | short | r/w | Gets or sets the g component. |
| horizontal_placement | int | r/w | Gets or sets the horizontal placement. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| line_count | short | r | Gets the line count. |
| lines | [TypeToolLineInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) | r/w | Gets or sets the lines. |
| psd_version | int | r | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| r_component | short | r/w | Gets or sets the r component. |
| scale_factor | int | r/w | Gets or sets the scale factor. |
| selection_end | int | r/w | Gets or sets the selection end. |
| selection_start | int | r/w | Gets or sets the selection start. |
| signature | int | r | Gets the layer resource signature. |
| styles | [TypeToolStyleInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) | r/w | Gets or sets the font styles. |
| styles_count | short | r | Gets the styles count. |
| transform_matrix | double | r/w | Gets or sets the transform matrix. |
| type_value | short | r/w | Gets or sets the type value. |
| version | short | r/w | Gets or sets the version. |
| vertical_placement | int | r/w | Gets or sets the vertical placement. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the specified stream container. |


### Constructor: TypeToolInfoResource() {#TypeToolInfoResource__1}


```
 TypeToolInfoResource() 
```

Initializes a new instance of the TypeToolInfoResource class

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

