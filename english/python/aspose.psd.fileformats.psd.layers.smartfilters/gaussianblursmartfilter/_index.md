---
title: GaussianBlurSmartFilter Class
type: docs
weight: 20
url: /python-net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/
---

**Summary:** The GaussianBlur smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.GaussianBlurSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.1.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GaussianBlurSmartFilter()](#GaussianBlurSmartFilter__1) | Initializes a new instance of the [GaussianBlurSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| FILTER_TYPE [static] | int | r | The identifier of current smart filter. |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Gets or sets the blending mode. |
| filter_id | int | r | Gets the smart filter type identifier. |
| is_enabled | bool | r/w | Gets or sets the is enabled status of the smart filter. |
| name | string | r | Gets the smart filter name. |
| opacity | double | r/w | Gets or sets the opacity value of smart filter. |
| radius | double | r/w | Gets or sets the radius of gaussian smart filter. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | The source descriptor structure with smart filter data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | Applies the current filter to input [RasterImage](/psd/python-net/aspose.psd/rasterimage/) image. |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | Applies the current filter to input [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) mask data. |
| [clone()](#clone__3) | Makes the memberwise clone of the current instance of the type. |


### Constructor: GaussianBlurSmartFilter() {#GaussianBlurSmartFilter__1}


```
 GaussianBlurSmartFilter() 
```

Initializes a new instance of the [GaussianBlurSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/) class.

### Method: apply(raster_image) {#apply_raster_image_1}


```
 apply(raster_image) 
```

Applies the current filter to input [RasterImage](/psd/python-net/aspose.psd/rasterimage/) image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | The raster image. |

### Method: apply_to_mask(layer_with_mask) {#apply_to_mask_layer_with_mask_2}


```
 apply_to_mask(layer_with_mask) 
```

Applies the current filter to input [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) mask data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| layer_with_mask | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | The layer with mask data. |

### Method: clone() {#clone__3}


```
 clone() 
```

Makes the memberwise clone of the current instance of the type.

**Returns**

| Type | Description |
| :- | :- |
| [SmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter) | Returns the memberwise clone of the current instance of the type. |


