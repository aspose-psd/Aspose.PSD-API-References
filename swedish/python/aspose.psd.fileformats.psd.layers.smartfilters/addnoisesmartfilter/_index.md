---
title: "AddNoiseSmartFilter-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/
---

**Summary:** The AddNoise smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.AddNoiseSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter__1) | Initierar en ny instans av klassen [AddNoiseSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| FILTER_TYPE [statisk] | int | r | Identifieraren för aktuellt smartfilter. |
| amount_noise | double | r/w | Hämtar eller anger brusvärdets mängd. |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Hämtar eller anger blandningsläget. |
| distribution | [NoiseDistribution](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/noisedistribution) | r/w | Hämtar eller anger fördelningen av brusfilter. |
| filter_id | int | r | Hämtar identifieraren för smartfiltertypen. |
| is_enabled | bool | r/w | Hämtar eller anger om smartfiltret är aktiverat. |
| is_monochromatic | bool | r/w | Hämtar eller anger värdet för monochromatic. |
| name | string | r | Hämtar smartfilternamnet. |
| opacity | double | r/w | Hämtar eller anger opacitetsvärdet för smartfilter. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | Källbeskrivarstrukturen med smartfilterdata. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | Tillämpar det aktuella filtret på inmatningsbilden [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | Tillämpar det aktuella filtret på inmatningsmaskdata för [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
| [clone()](#clone__3) | Skapar en medlemsvis klon av den aktuella instansen av typen. |


### Constructor: AddNoiseSmartFilter() {#AddNoiseSmartFilter__1}


```
 AddNoiseSmartFilter() 
```

Initierar en ny instans av klassen [AddNoiseSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/).

### Method: apply(raster_image) {#apply_raster_image_1}


```
 apply(raster_image) 
```

Tillämpar det aktuella filtret på inmatningsbilden [RasterImage](/psd/python-net/aspose.psd/rasterimage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Rasterbilden. |

### Method: apply_to_mask(layer_with_mask) {#apply_to_mask_layer_with_mask_2}


```
 apply_to_mask(layer_with_mask) 
```

Tillämpar det aktuella filtret på inmatningsmaskdata för [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer_with_mask | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Lagret med maskdata. |

### Method: clone() {#clone__3}


```
 clone() 
```

Skapar en medlemsvis klon av den aktuella instansen av typen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter) | Returnerar en medlemsvis klon av den aktuella instansen av typen. |


