---
title: "SharpenSmartFilter‑klasse"
type: docs
weight: 40
url: /nl/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/
---

**Summary:** The Sharpen smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.SharpenSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [SharpenSmartFilter()](#SharpenSmartFilter__1) | Initialiseert een nieuw exemplaar van de [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/) klasse. |
| [SharpenSmartFilter(source_descriptor)](#SharpenSmartFilter_source_descriptor_2) | Initialiseert een nieuw exemplaar van de [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| FILTER_TYPE [static] | int | r | De identifier van de huidige slimme filter. |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Haalt of stelt de mengmodus in. |
| filter_id | int | r | Haalt de identifier van het slimme filtertype op. |
| is_enabled | bool | r/w | Haalt of stelt de ingeschakeld-status van de slimme filter in. |
| name | string | r | Haalt de naam van de slimme filter op. |
| opacity | double | r/w | Haalt of stelt de doorzichtigheidswaarde van de slimme filter in. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | De bronbeschrijvingsstructuur met slimme filtergegevens. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | Past het huidige filter toe op de invoer [RasterImage](/psd/python-net/aspose.psd/rasterimage/) afbeelding. |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | Past het huidige filter toe op de invoer [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) maskergegevens. |
| [clone()](#clone__3) | Maakt de lid-voor-lid kloon van de huidige instantie van het type. |


### Constructor: SharpenSmartFilter() {#SharpenSmartFilter__1}


```
 SharpenSmartFilter() 
```

Initialiseert een nieuw exemplaar van de [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/) klasse.

### Constructor: SharpenSmartFilter(source_descriptor) {#SharpenSmartFilter_source_descriptor_2}


```
 SharpenSmartFilter(source_descriptor) 
```

Initialiseert een nieuw exemplaar van de [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | De beschrijvingsstructuur met slimme filterinformatie. |

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


