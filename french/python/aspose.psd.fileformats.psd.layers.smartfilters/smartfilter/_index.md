---
title: "SmartFilter Classe"
type: docs
weight: 50
url: /fr/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/
---

**Summary:** The class to process a base logic of smart filters.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Obtient ou définit le mode de fusion. |
| filter_id | int | r | Obtient l'identifiant du type de filtre intelligent. |
| is_enabled | bool | r/w | Obtient ou définit l'état d'activation du filtre intelligent. |
| name | chaîne | r | Obtient le nom du filtre intelligent. |
| opacity | double | r/w | Obtient ou définit la valeur d'opacité du filtre intelligent. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | La structure de descripteur source contenant les données du filtre intelligent. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | Applique le filtre actuel à l'image d'entrée [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | Applique le filtre actuel aux données de masque d'entrée [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
| [clone()](#clone__3) | Crée le clone champ par champ de l'instance actuelle du type. |


### Method: apply(raster_image) {#apply_raster_image_1}


```
 apply(raster_image) 
```

Applique le filtre actuel à l'image d'entrée [RasterImage](/psd/python-net/aspose.psd/rasterimage/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | L'image raster. |

### Method: apply_to_mask(layer_with_mask) {#apply_to_mask_layer_with_mask_2}


```
 apply_to_mask(layer_with_mask) 
```

Applique le filtre actuel aux données de masque d'entrée [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer_with_mask | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Le calque contenant les données de masque. |

### Method: clone() {#clone__3}


```
 clone() 
```

Crée le clone champ par champ de l'instance actuelle du type.

**Returns**

| Type | Description |
| :- | :- |
| [SmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter) | Renvoie le clone champ par champ de l'instance actuelle du type. |


