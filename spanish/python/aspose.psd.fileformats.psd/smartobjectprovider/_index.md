---
title: "Clase SmartObjectProvider"
type: docs
weight: 1940
url: /es/python-net/aspose.psd.fileformats.psd/smartobjectprovider/
---

**Summary:** Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.SmartObjectProvider

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [convert_to_smart_object(layer_numbers)](#convert_to_smart_object_layer_numbers_1) | Convierte capas en un objeto inteligente incrustado. |
| [convert_to_smart_object(layers)](#convert_to_smart_object_layers_2) | Convierte capas en un objeto inteligente incrustado. |
| embed_all_linked() | Incrusta todos los objetos inteligentes vinculados en la imagen. |
| [new_smart_object_via_copy(source_layer)](#new_smart_object_via_copy_source_layer_3) | Crea una nueva capa de objeto inteligente copiando la original. |
| update_all_modified_content() | Actualiza el contenido de todos los objetos inteligentes modificados en la imagen. |


### Method: convert_to_smart_object(layer_numbers) {#convert_to_smart_object_layer_numbers_1}


```
 convert_to_smart_object(layer_numbers) 
```

Convierte capas en un objeto inteligente incrustado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer_numbers | int | Los números de capa. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | La instancia creada de [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |


### Method: convert_to_smart_object(layers) {#convert_to_smart_object_layers_2}


```
 convert_to_smart_object(layers) 
```

Convierte capas en un objeto inteligente incrustado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Las capas. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | La instancia creada de [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |


### Method: new_smart_object_via_copy(source_layer) {#new_smart_object_via_copy_source_layer_3}


```
 new_smart_object_via_copy(source_layer) 
```

Crea una nueva capa de objeto inteligente copiando la original.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_layer | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | La capa fuente. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | La instancia clonada de [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |


