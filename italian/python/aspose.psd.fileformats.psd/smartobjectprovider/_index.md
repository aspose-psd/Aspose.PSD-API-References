---
title: "SmartObjectProvider Classe"
type: docs
weight: 1940
url: /it/python-net/aspose.psd.fileformats.psd/smartobjectprovider/
---

**Summary:** Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.SmartObjectProvider

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [convert_to_smart_object(layer_numbers)](#convert_to_smart_object_layer_numbers_1) | Converte i livelli in un smart object incorporato. |
| [convert_to_smart_object(layers)](#convert_to_smart_object_layers_2) | Converte i livelli in un smart object incorporato. |
| embed_all_linked() | Incorpora tutti gli smart object collegati nell'immagine. |
| [new_smart_object_via_copy(source_layer)](#new_smart_object_via_copy_source_layer_3) | Crea un nuovo livello smart object copiando quello di origine. |
| update_all_modified_content() | Aggiorna il contenuto di tutti gli smart object modificati nell'immagine. |


### Method: convert_to_smart_object(layer_numbers) {#convert_to_smart_object_layer_numbers_1}


```
 convert_to_smart_object(layer_numbers) 
```

Converte i livelli in un smart object incorporato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer_numbers | int | I numeri dei livelli. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | L'istanza creata di [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |


### Method: convert_to_smart_object(layers) {#convert_to_smart_object_layers_2}


```
 convert_to_smart_object(layers) 
```

Converte i livelli in un smart object incorporato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | I livelli. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | L'istanza creata di [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |


### Method: new_smart_object_via_copy(source_layer) {#new_smart_object_via_copy_source_layer_3}


```
 new_smart_object_via_copy(source_layer) 
```

Crea un nuovo livello smart object copiando quello di origine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_layer | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Il livello sorgente. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | L'istanza clonata [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |


