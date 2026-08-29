---
title: "Classe SmartObjectProvider"
type: docs
weight: 1940
url: /fr/python-net/aspose.psd.fileformats.psd/smartobjectprovider/
---

**Summary:** Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.SmartObjectProvider

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [convert_to_smart_object(layer_numbers)](#convert_to_smart_object_layer_numbers_1) | Convertit les calques en un objet intelligent intégré. |
| [convert_to_smart_object(layers)](#convert_to_smart_object_layers_2) | Convertit les calques en un objet intelligent intégré. |
| embed_all_linked() | Intègre tous les objets intelligents liés dans l'image. |
| [new_smart_object_via_copy(source_layer)](#new_smart_object_via_copy_source_layer_3) | Crée un nouveau calque d'objet intelligent en copiant la source. |
| update_all_modified_content() | Met à jour le contenu de tous les objets intelligents modifiés dans l'image. |


### Method: convert_to_smart_object(layer_numbers) {#convert_to_smart_object_layer_numbers_1}


```
 convert_to_smart_object(layer_numbers) 
```

Convertit les calques en un objet intelligent intégré.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer_numbers | int | Les numéros de calque. |

**Returns**

| Type | Description |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | L'instance [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) créée. |


### Method: convert_to_smart_object(layers) {#convert_to_smart_object_layers_2}


```
 convert_to_smart_object(layers) 
```

Convertit les calques en un objet intelligent intégré.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Les calques. |

**Returns**

| Type | Description |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | L'instance [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) créée. |


### Method: new_smart_object_via_copy(source_layer) {#new_smart_object_via_copy_source_layer_3}


```
 new_smart_object_via_copy(source_layer) 
```

Crée un nouveau calque d'objet intelligent en copiant la source.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_layer | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | La couche source. |

**Returns**

| Type | Description |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | L'instance clonée de [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |


