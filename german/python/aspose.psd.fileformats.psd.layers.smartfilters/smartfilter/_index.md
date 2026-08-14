---
title: "SmartFilter Klasse"
type: docs
weight: 50
url: /de/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/
---

**Summary:** The class to process a base logic of smart filters.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Liest oder setzt den Mischmodus. |
| filter_id | int | r | Liest den Typbezeichner des Smartfilters. |
| is_enabled | bool | r/w | Liest oder setzt den Aktivierungsstatus des Smartfilters. |
| name | string | r | Liest den Namen des Smartfilters. |
| Deckkraft | double | r/w | Liest oder setzt den Opazitätswert des Smartfilters. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | Die Quellbeschreibungsstruktur mit Smartfilter-Daten. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | Wendet den aktuellen Filter auf das Eingabe-[RasterImage](/psd/python-net/aspose.psd/rasterimage/) Bild an. |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | Wendet den aktuellen Filter auf die Eingabe-[Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) Maskendaten an. |
| [clone()](#clone__3) | Erstellt die memberweise Kopie der aktuellen Instanz des Typs. |


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


