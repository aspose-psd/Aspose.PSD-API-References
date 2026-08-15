---
title: "SmartFilter Klasse"
type: docs
weight: 50
url: /nl/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/
---

**Summary:** The class to process a base logic of smart filters.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
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


