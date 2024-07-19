---
title: SmartObjectProvider Class
type: docs
weight: 1870
url: /python-net/aspose.psd.fileformats.psd/smartobjectprovider/
---

**Summary:** Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.SmartObjectProvider

**Aspose.PSD Version:** 24.5.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [convert_to_smart_object(layer_numbers)](#convert_to_smart_object_layer_numbers_1) | Converts layers to an embedded smart object. |
| [convert_to_smart_object(layers)](#convert_to_smart_object_layers_2) | Converts layers to an embedded smart object. |
| embed_all_linked() | Embeds all linked smart objects in the image. |
| [new_smart_object_via_copy(source_layer)](#new_smart_object_via_copy_source_layer_3) | Creates a new smart object layer by coping the source one. |
| update_all_modified_content() | Updates the content of all modified smart objects in the image. |


### Method: convert_to_smart_object(layer_numbers) {#convert_to_smart_object_layer_numbers_1}


```
 convert_to_smart_object(layer_numbers) 
```

Converts layers to an embedded smart object.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| layer_numbers | int | The layer numbers. |

**Returns**

| Type | Description |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | The created [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) instance. |


### Method: convert_to_smart_object(layers) {#convert_to_smart_object_layers_2}


```
 convert_to_smart_object(layers) 
```

Converts layers to an embedded smart object.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | The layers. |

**Returns**

| Type | Description |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | The created [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) instance. |


### Method: new_smart_object_via_copy(source_layer) {#new_smart_object_via_copy_source_layer_3}


```
 new_smart_object_via_copy(source_layer) 
```

Creates a new smart object layer by coping the source one.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_layer | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | The source layer. |

**Returns**

| Type | Description |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | The cloned [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) instance. |


