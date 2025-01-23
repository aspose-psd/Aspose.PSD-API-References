---
title: AiLayerSection Class
type: docs
weight: 50
url: /python-net/aspose.psd.fileformats.ai/ailayersection/
---

**Summary:** The Ai format Layer Section

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiLayerSection

**Inheritance:** AiDataSection

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blue | int | r/w | Gets or sets the blue color component. |
| color_index | int | r/w | Gets or sets the index of the color.<br/>            This argument can take on values between –1 and 26. Each integer<br/>            represents a color that can be assigned to the layer for user<br/>            identification purposes. |
| color_number | int | r/w | Gets or sets the color number. -1 is the custom color value from Red, Green, Blue properties.<br/>            Specifies the layer’s color setting. |
| dim_value | int | r/w | Gets or sets the dim value as percentage.<br/>            Reduces the intensity of linked images and bitmap images contained in the layer to the specified percentage. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| green | int | r/w | Gets or sets the green color component. |
| has_multi_layer_masks | bool | r/w | Gets or sets a value indicating whether this instance has multilayer masks. |
| is_images_dimmed | bool | r/w | Gets or sets a value indicating whether this layer is dimmed.<br/>            Reduces the intensity of linked images and bitmap images contained in the layer. |
| is_locked | bool | r/w | Gets or sets a value indicating whether this layer is locked.<br/>            Prevents changes to the item. |
| is_preview | bool | r/w | Gets or sets a value indicating whether this layer is preview.<br/>            Displays the artwork contained in the layer in color instead of as outlines. |
| is_printed | bool | r/w | Gets or sets a value indicating whether this layer is printed.<br/>            Makes the artwork contained in the layer printable if true. |
| is_shown | bool | r/w | Gets or sets a value indicating whether this layer is shown.<br/>            Displays all artwork contained in the layer on the artboard if true. |
| is_template | bool | r/w | Gets or sets a value indicating whether this layer is a template layer. |
| name | string | r/w | Gets or sets the layer name.<br/>            Specifies the name of the item as it appears in the Layers panel. |
| raster_images | [AiRasterImageSection[]](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | r | Gets the raster images. |
| red | int | r/w | Gets or sets the red color component. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_raster_image(raster_image)](#add_raster_image_raster_image_1) | Adds the raster image. |
| [get_data()](#get_data__2) | Gets the string data. |


### Method: add_raster_image(raster_image) {#add_raster_image_raster_image_1}


```
 add_raster_image(raster_image) 
```

Adds the raster image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| raster_image | [AiRasterImageSection](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | The raster image. |

### Method: get_data() {#get_data__2}


```
 get_data() 
```

Gets the string data.

**Returns**

| Type | Description |
| :- | :- |
| string | The string data of section |


