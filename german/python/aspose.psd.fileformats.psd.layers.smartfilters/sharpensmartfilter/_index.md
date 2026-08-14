---
title: "SharpenSmartFilter Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/
---

**Summary:** The Sharpen smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.SharpenSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [SharpenSmartFilter()](#SharpenSmartFilter__1) | Initialisiert eine neue Instanz der [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/) Klasse. |
| [SharpenSmartFilter(source_descriptor)](#SharpenSmartFilter_source_descriptor_2) | Initialisiert eine neue Instanz der [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| FILTER_TYPE [statisch] | int | r | Der Bezeichner des aktuellen Smartfilters. |
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


### Constructor: SharpenSmartFilter() {#SharpenSmartFilter__1}


```
 SharpenSmartFilter() 
```

Initialisiert eine neue Instanz der [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/) Klasse.

### Constructor: SharpenSmartFilter(source_descriptor) {#SharpenSmartFilter_source_descriptor_2}


```
 SharpenSmartFilter(source_descriptor) 
```

Initialisiert eine neue Instanz der [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | Die Beschreibungsstruktur mit Smartfilter-Informationen. |

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


