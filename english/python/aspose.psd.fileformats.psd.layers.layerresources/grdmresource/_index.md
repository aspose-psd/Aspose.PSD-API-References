---
title: GrdmResource Class
type: docs
weight: 300
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Summary:** Class GrdmResource. Contains information about Gradient-Map layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GrdmResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.1.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GrdmResource()](#GrdmResource__1) | Initializes a new instance of the GrdmResource class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| color_model | short | r/w | Color Model.<br/>            When 'Gradient type' = 'Noise', we can assign 'Color Model' to RGB/SHB/LAB (3/4/6). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Gets or sets the color points. |
| dither | bool | r/w | Is gradient dithered. |
| expansion_count | short | r/w | Expansion count ( = 2 for Photoshop 6.0). |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | Mode for this gradient<br/>            Determines 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | Name of the gradient: Unicode string, padded. |
| interpolation | short | r/w | Interpolation. Determines Smoothness, when 'Gradient Type' = 'Solid' (GradientMode = 0). |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r | Maximum color of PixelDataFormat.Rgba64Bpp format.<br/>            Color has ARGB channels, Each channel is 16bit. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r | Minimum color of PixelDataFormat.Rgba64Bpp format.<br/>            Color has ARGB channels, Each channel is 16bit. |
| psd_version | int | r | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| reverse | bool | r/w | Is gradient reversed. |
| rnd_number_seed | int | r/w | The random number seed used to generate colors for Noise gradient. |
| roughness | int | r/w | Roughness factor<br/>            When 'Gradient type' = 'Noise', we can assign 'Roughness' (0 - 2048). |
| show_transparency | short | r/w | Flag for showing transparency<br/>            When 'Gradient type' = 'Noise', we can assign 'Add transparency' to true. |
| signature | int | r | Gets the signature. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Gets or sets the transparency points. |
| use_vector_color | short | r/w | Flag for using vector color. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves resource data to the specified stream container. |
| [set_psd_version(value)](#set_psd_version_value_2) | Sets the minimal psd version required for layer resource. 0 indicates no restrictions. |


### Constructor: GrdmResource() {#GrdmResource__1}


```
 GrdmResource() 
```

Initializes a new instance of the GrdmResource class

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Saves resource data to the specified stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container. |
| psd_version | int | The PSD version. |

### Method: set_psd_version(value) {#set_psd_version_value_2}


```
 set_psd_version(value) 
```

Sets the minimal psd version required for layer resource. 0 indicates no restrictions.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | ushort | Psdversion value |

