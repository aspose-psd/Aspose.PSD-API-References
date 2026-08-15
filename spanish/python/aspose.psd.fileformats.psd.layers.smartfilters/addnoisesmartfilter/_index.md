---
title: "Clase AddNoiseSmartFilter"
type: docs
weight: 10
url: /es/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/
---

**Summary:** The AddNoise smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.AddNoiseSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter__1) | Inicializa una nueva instancia de la clase [AddNoiseSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| FILTER_TYPE [static] | int | r | El identificador del filtro inteligente actual. |
| amount_noise | double | r/w | Obtiene o establece la cantidad del valor de ruido. |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Obtiene o establece el modo de fusión. |
| distribution | [NoiseDistribution](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/noisedistribution) | r/w | Obtiene o establece la distribución del filtro de ruido. |
| filter_id | int | r | Obtiene el identificador del tipo de filtro inteligente. |
| is_enabled | bool | r/w | Obtiene o establece el estado habilitado del filtro inteligente. |
| is_monochromatic | bool | r/w | Obtiene o establece el valor de monocromático. |
| name | string | r | Obtiene el nombre del filtro inteligente. |
| opacity | double | r/w | Obtiene o establece el valor de opacidad del filtro inteligente. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | La estructura del descriptor de origen con datos del filtro inteligente. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | Aplica el filtro actual a la imagen de entrada [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | Aplica el filtro actual a los datos de máscara de entrada [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
| [clone()](#clone__3) | Crea la clonación por miembros de la instancia actual del tipo. |


### Constructor: AddNoiseSmartFilter() {#AddNoiseSmartFilter__1}


```
 AddNoiseSmartFilter() 
```

Inicializa una nueva instancia de la clase [AddNoiseSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/).

### Method: apply(raster_image) {#apply_raster_image_1}


```
 apply(raster_image) 
```

Aplica el filtro actual a la imagen de entrada [RasterImage](/psd/python-net/aspose.psd/rasterimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | La imagen raster. |

### Method: apply_to_mask(layer_with_mask) {#apply_to_mask_layer_with_mask_2}


```
 apply_to_mask(layer_with_mask) 
```

Aplica el filtro actual a los datos de máscara de entrada [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer_with_mask | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | La capa con datos de máscara. |

### Method: clone() {#clone__3}


```
 clone() 
```

Crea la clonación por miembros de la instancia actual del tipo.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter) | Devuelve la clonación por miembros de la instancia actual del tipo. |


