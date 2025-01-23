---
title: VstkResource Class
type: docs
weight: 40
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Summary:** Resource class VstkResource. Contains information about Vector Stroke Data.<br/>            Resource should be initialized either by AssignItems method from ResourceLoader,<br/>            either by assigning values to properties of the class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VstkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VstkResource()](#VstkResource__1) | Initializes a new instance of the VstkResource class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| fill_enabled | bool | r/w | Gets or sets a value indicating whether Stroke fill enabled. |
| fill_settings | [IFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) | r/w | Gets or sets Fill settings of the Stroke. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| psd_version | int | r | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| signature | int | r | Gets the signature. |
| stroke_enabled | bool | r/w | Gets or sets a value indicating whether stroke effect enabled. |
| stroke_style_blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Gets or sets Stroke Blend mode. |
| stroke_style_content | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r/w | Gets or sets Stroke entity. Property determines fill settings of the stroke. |
| stroke_style_line_alignment | [StrokePosition](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/) | r/w | Gets or sets Stroke style line alignment. |
| stroke_style_line_cap_type | [LineCapType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype) | r/w | Gets or sets the type of the stroke style line cap. |
| stroke_style_line_cap_width | double | r/w | Gets or sets Stroke line cap width. |
| stroke_style_line_dash_offset | int | r/w | Gets or sets the stroke style line dash offset. |
| stroke_style_line_dash_set | double | r/w | Gets or sets array of line dashes. |
| stroke_style_line_join_type | [LineJoinType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype) | r/w | Gets or sets Stroke style line join type. |
| stroke_style_line_width | double | r/w | Gets or sets Stroke line width. |
| stroke_style_miter_limit | double | r/w | Gets or sets the stroke style miter limit. |
| stroke_style_opacity | int | r/w | Gets or sets Stroke style opacity (0-100%). |
| stroke_style_resolution | double | r/w | Gets or sets Stroke style resolution. |
| stroke_style_scale_lock | bool | r/w | Gets or sets Stroke style scale lock. |
| stroke_style_stroke_adjust | bool | r/w | Gets or sets Stroke adjust. |
| stroke_style_version | int | r/w | Gets or sets the stroke style version. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: VstkResource() {#VstkResource__1}


```
 VstkResource() 
```

Initializes a new instance of the VstkResource class

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

