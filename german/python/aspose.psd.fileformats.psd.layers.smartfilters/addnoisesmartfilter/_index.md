---
title: "AddNoiseSmartFilter Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/
---

**Summary:** The AddNoise smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.AddNoiseSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter__1) | Initialisiert eine neue Instanz der [AddNoiseSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| FILTER_TYPE [statisch] | int | r | Der Bezeichner des aktuellen Smartfilters. |
| amount_noise | double | r/w | Liest oder setzt den Rauschwert. |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Liest oder setzt den Mischmodus. |
| distribution | [NoiseDistribution](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/noisedistribution) | r/w | Liest oder setzt die Verteilung des Rauschfilters. |
| filter_id | int | r | Liest den Typbezeichner des Smartfilters. |
| is_enabled | bool | r/w | Liest oder setzt den Aktivierungsstatus des Smartfilters. |
| is_monochromatic | bool | r/w | Liest oder setzt den monochromen Wert. |
| name | string | r | Liest den Namen des Smartfilters. |
| Deckkraft | double | r/w | Liest oder setzt den Opazitätswert des Smartfilters. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | Die Quellbeschreibungsstruktur mit Smartfilter-Daten. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | Wendet den aktuellen Filter auf das Eingabe-[RasterImage](/psd/python-net/aspose.psd/rasterimage/) Bild an. |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | Wendet den aktuellen Filter auf die Eingabe-[Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) Maskendaten an. |
| [clone()](#clone__3) | Erstellt die memberweise Kopie der aktuellen Instanz des Typs. |


### Constructor: AddNoiseSmartFilter() {#AddNoiseSmartFilter__1}


```
 AddNoiseSmartFilter() 
```

Initialisiert eine neue Instanz der [AddNoiseSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/) Klasse.

### Method: apply(raster_image) {#apply_raster_image_1}


```
 apply(raster_image) 
```

Wendet den aktuellen Filter auf das Eingabe-[RasterImage](/psd/python-net/aspose.psd/rasterimage/) Bild an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Das Rasterbild. |

### Method: apply_to_mask(layer_with_mask) {#apply_to_mask_layer_with_mask_2}


```
 apply_to_mask(layer_with_mask) 
```

Wendet den aktuellen Filter auf die Eingabe-[Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) Maskendaten an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer_with_mask | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Die Ebene mit Maskendaten. |

### Method: clone() {#clone__3}


```
 clone() 
```

Erstellt die memberweise Kopie der aktuellen Instanz des Typs.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter) | Gibt die memberweise Kopie der aktuellen Instanz des Typs zurück. |


