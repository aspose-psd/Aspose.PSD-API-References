---
title: PatternFillSettings Class
type: docs
weight: 130
url: /python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Summary:** Pattern fill effect settings

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings

**Inheritance:** IFillSettings, IPatternFillSettings, BaseFillSettings

**Aspose.PSD Version:** 24.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PatternFillSettings()](#PatternFillSettings__1) | Initializes a new instance of the PatternFillSettings class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Gets or sets a value indicating whether [link with layer]. |
| angle | double | r/w | Gets or sets the angle. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Gets or sets the color. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | The fill type |
| horizontal_offset | int | r/w | Gets or sets the horizontal offset. |
| linked | bool | r/w | Gets or sets a value indicating whether this [PatternFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/) is linked. |
| pattern_data | int | r/w | Gets or sets the pattern data. |
| pattern_height | int | r/w | Gets or sets the height of the pattern. |
| pattern_id | string | r/w | Gets or sets the pattern identifier. |
| pattern_name | string | r/w | Gets or sets the name of the pattern. |
| pattern_width | int | r/w | Gets or sets the width of the pattern. |
| point_type | string | r/w | Gets or sets the type of the point. |
| scale | double | r/w | Gets or sets the scale. |
| vertical_offset | int | r/w | Gets or sets the vertical offset. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)](#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1) | Generates the LFX2 resource nodes. |


### Constructor: PatternFillSettings() {#PatternFillSettings__1}


```
 PatternFillSettings() 
```

Initializes a new instance of the PatternFillSettings class

### Method: generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)  [static] {#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1}


```
 generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset) 
```

Generates the LFX2 resource nodes.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point_type | string | Type of the point. |
| color | [Color](/psd/python-net/aspose.psd/color) | The color. |
| pattern_name | string | Name of the pattern. |
| identifier | string | The identifier. |
| scale | double | The scale. |
| linked | bool | if set to <c>true</c> [linked]. |
| offset | [PointF](/psd/python-net/aspose.psd/pointf) | The offset. |

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | List of [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


