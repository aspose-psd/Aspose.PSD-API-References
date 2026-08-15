---
title: "GaussianBlurSmartFilter Klasse"
type: docs
weight: 20
url: /nl/python-net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/
---

**Summary:** The GaussianBlur smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.GaussianBlurSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [GaussianBlurSmartFilter()](#GaussianBlurSmartFilter__1) | Initialiseert een nieuwe instantie van de [GaussianBlurSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| FILTER_TYPE [static] | int | r | De identifier van de huidige slimme filter. |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Haalt of stelt de mengmodus in. |
| filter_id | int | r | Haalt de identifier van het slimme filtertype op. |
| is_enabled | bool | r/w | Haalt of stelt de ingeschakeld-status van de slimme filter in. |
| name | string | r | Haalt de naam van de slimme filter op. |
| opacity | double | r/w | Haalt of stelt de doorzichtigheidswaarde van de slimme filter in. |
| straal | double | r/w | Haalt of stelt de radius van de Gaussian slimme filter in. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | De bronbeschrijvingsstructuur met slimme filtergegevens. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | Past het huidige filter toe op de invoer [RasterImage](/psd/python-net/aspose.psd/rasterimage/) afbeelding. |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | Past het huidige filter toe op de invoer [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) maskergegevens. |
| [clone()](#clone__3) | Maakt de lid-voor-lid kloon van de huidige instantie van het type. |


### Constructor: GaussianBlurSmartFilter() {#GaussianBlurSmartFilter__1}


```
 GaussianBlurSmartFilter() 
```

Initialiseert een nieuwe instantie van de [GaussianBlurSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/) klasse.

### Method: apply(raster_image) {#apply_raster_image_1}


```
 apply(raster_image) 
```

Past het huidige filter toe op de invoer [RasterImage](/psd/python-net/aspose.psd/rasterimage/) afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | De rasterafbeelding. |

### Method: apply_to_mask(layer_with_mask) {#apply_to_mask_layer_with_mask_2}


```
 apply_to_mask(layer_with_mask) 
```

Past het huidige filter toe op de invoer [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) maskergegevens.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer_with_mask | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | De laag met maskergegevens. |

### Method: clone() {#clone__3}


```
 clone() 
```

Maakt de lid-voor-lid kloon van de huidige instantie van het type.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [SmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter) | Retourneert de lid-voor-lid kloon van de huidige instantie van het type. |


