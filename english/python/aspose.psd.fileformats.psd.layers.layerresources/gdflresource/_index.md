---
title: GdFlResource Class
type: docs
weight: 290
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Summary:** Class GdFlResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GdFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.1.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GdFlResource()](#GdFlResource__1) | Initializes a new instance of the GdFlResource class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| align_with_layer | bool | r/w | Gets or sets a value indicating whether [align with layer]. |
| angle | double | r/w | Gets or sets the angle. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Gets the color of the RGB. |
| color_model | string | r/w | Color Model - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Gets the color points. |
| dither | bool | r/w | Gets or sets a value indicating whether this [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) is dither. |
| gradient_interval | double | r/w | Gets or sets the gradient interval. |
| gradient_mode | string | r/w | Mode for this gradient.<br/>            Determines 'Gradient Type' = 'Solid/Noise' = "CstS"/"ClNs". |
| gradient_name | string | r/w | Gets or sets the name of the gradient. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/) | r/w | Gets or sets the type of the gradient. |
| horizontal_offset | double | r/w | Gets or sets the horizontal offset. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Maximum color of PixelDataFormat. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Minimum color of PixelDataFormat. |
| psd_version | int | r | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| reverse | bool | r/w | Gets or sets a value indicating whether this [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) is reverse. |
| rnd_number_seed | int | r/w | The random number seed used to generate colors for Noise gradient. |
| roughness | int | r/w | Roughness factor. |
| scale | int | r/w | Gets or sets the scale. |
| show_transparency | bool | r/w | Flag for showing transparency. |
| signature | int | r | Gets the layer resource signature. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Gets the transparency points. |
| use_vector_color | bool | r/w | Flag for using vector color. |
| vertical_offset | double | r/w | Gets or sets the vertical offset. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: GdFlResource() {#GdFlResource__1}


```
 GdFlResource() 
```

Initializes a new instance of the GdFlResource class

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

