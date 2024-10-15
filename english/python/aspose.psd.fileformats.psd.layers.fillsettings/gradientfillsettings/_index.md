---
title: GradientFillSettings Class
type: docs
weight: 50
url: /python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Summary:** Gradient fill effect settings.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GradientFillSettings()](#GradientFillSettings__1) | Initializes a new instance of the [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Gets or sets a value indicating whether [align with layer]. |
| angle | double | r/w | Gets or sets the angle. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Gets or sets the color. |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Gets or sets the color points. |
| dither | bool | r/w | Gets or sets a value indicating whether this [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) is dither. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | The fill type. |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | Mode for this gradient.<br/>            Determines 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | Gets or sets the name of the gradient. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | Gets or sets the type of the gradient. |
| horizontal_offset | double | r/w | Gets or sets the horizontal offset in percentage. |
| interpolation | short | r/w | Interpolation. Determines Smoothness, when 'Gradient Type' = 'Solid'. Value range: 0-4096. |
| reverse | bool | r/w | Gets or sets a value indicating whether this [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) is reverse. |
| scale | int | r/w | Gets or sets the scale. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | Gets or sets the transparency points. |
| vertical_offset | double | r/w | Gets or sets the vertical offset in percentage. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_color_point()](#add_color_point__1) | Adds the color point. |
| [add_transparency_point()](#add_transparency_point__2) | Adds the color point. |
| [generate_lfx_2_resource_nodes()](#generate_lfx_2_resource_nodes__3) | Generates the LFX2 resource nodes. |
| [remove_color_point(point)](#remove_color_point_point_4) | Removes the color point. |
| [remove_transparency_point(point)](#remove_transparency_point_point_5) | Removes the transparency point. |


### Constructor: GradientFillSettings() {#GradientFillSettings__1}


```
 GradientFillSettings() 
```

Initializes a new instance of the [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) class.

### Method: add_color_point() {#add_color_point__1}


```
 add_color_point() 
```

Adds the color point.

**Returns**

| Type | Description |
| :- | :- |
| [GradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) | Created color point |


### Method: add_transparency_point() {#add_transparency_point__2}


```
 add_transparency_point() 
```

Adds the color point.

**Returns**

| Type | Description |
| :- | :- |
| [GradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) | Created transparency point |


### Method: generate_lfx_2_resource_nodes()  [static] {#generate_lfx_2_resource_nodes__3}


```
 generate_lfx_2_resource_nodes() 
```

Generates the LFX2 resource nodes.

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.List<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Generated List of [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


### Method: remove_color_point(point) {#remove_color_point_point_4}


```
 remove_color_point(point) 
```

Removes the color point.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | The point. |

### Method: remove_transparency_point(point) {#remove_transparency_point_point_5}


```
 remove_transparency_point(point) 
```

Removes the transparency point.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [IGradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | The point. |

