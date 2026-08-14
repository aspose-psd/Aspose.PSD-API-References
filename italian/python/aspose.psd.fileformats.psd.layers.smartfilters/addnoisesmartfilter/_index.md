---
title: "Classe AddNoiseSmartFilter"
type: docs
weight: 10
url: /it/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/
---

**Summary:** The AddNoise smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.AddNoiseSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter__1) | Inizializza una nuova istanza della classe [AddNoiseSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| FILTER_TYPE [static] | int | r | L'identificatore del filtro intelligente corrente. |
| amount_noise | double | r/w | Ottiene o imposta la quantità del valore del rumore. |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Ottiene o imposta la modalità di fusione. |
| distribution | [NoiseDistribution](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/noisedistribution) | r/w | Ottiene o imposta la distribuzione del filtro di rumore. |
| filter_id | int | r | Ottiene l'identificatore del tipo di filtro intelligente. |
| is_enabled | bool | r/w | Ottiene o imposta lo stato abilitato del filtro intelligente. |
| is_monochromatic | bool | r/w | Ottiene o imposta il valore di monocromatico. |
| name | string | r | Ottiene il nome del filtro intelligente. |
| opacity | double | r/w | Ottiene o imposta il valore di opacità del filtro intelligente. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | La struttura del descrittore di origine con i dati del filtro intelligente. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | Applica il filtro corrente all'immagine [RasterImage](/psd/python-net/aspose.psd/rasterimage/) di input. |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | Applica il filtro corrente ai dati della maschera [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) di input. |
| [clone()](#clone__3) | Crea la clonazione membro per membro dell'istanza corrente del tipo. |


### Constructor: AddNoiseSmartFilter() {#AddNoiseSmartFilter__1}


```
 AddNoiseSmartFilter() 
```

Inizializza una nuova istanza della classe [AddNoiseSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/).

### Method: apply(raster_image) {#apply_raster_image_1}


```
 apply(raster_image) 
```

Applica il filtro corrente all'immagine [RasterImage](/psd/python-net/aspose.psd/rasterimage/) di input.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | L'immagine raster. |

### Method: apply_to_mask(layer_with_mask) {#apply_to_mask_layer_with_mask_2}


```
 apply_to_mask(layer_with_mask) 
```

Applica il filtro corrente ai dati della maschera [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) di input.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer_with_mask | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Il livello con i dati della maschera. |

### Method: clone() {#clone__3}


```
 clone() 
```

Crea la clonazione membro per membro dell'istanza corrente del tipo.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter) | Restituisce la clonazione membro per membro dell'istanza corrente del tipo. |


