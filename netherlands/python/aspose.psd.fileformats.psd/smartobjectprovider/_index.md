---
title: "SmartObjectProvider‑klasse"
type: docs
weight: 1940
url: /nl/python-net/aspose.psd.fileformats.psd/smartobjectprovider/
---

**Summary:** Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.SmartObjectProvider

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [convert_to_smart_object(layer_numbers)](#convert_to_smart_object_layer_numbers_1) | Converteert lagen naar een ingebed smart object. |
| [convert_to_smart_object(layers)](#convert_to_smart_object_layers_2) | Converteert lagen naar een ingebed smart object. |
| embed_all_linked() | Voegt alle gekoppelde smart objects in de afbeelding in. |
| [new_smart_object_via_copy(source_layer)](#new_smart_object_via_copy_source_layer_3) | Maakt een nieuwe smart object-laag door de bronlaag te kopiëren. |
| update_all_modified_content() | Werkt de inhoud van alle gewijzigde smart objects in de afbeelding bij. |


### Method: convert_to_smart_object(layer_numbers) {#convert_to_smart_object_layer_numbers_1}


```
 convert_to_smart_object(layer_numbers) 
```

Converteert lagen naar een ingebed smart object.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer_numbers | int | De laagnummers. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | De gemaakte [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) instantie. |


### Method: convert_to_smart_object(layers) {#convert_to_smart_object_layers_2}


```
 convert_to_smart_object(layers) 
```

Converteert lagen naar een ingebed smart object.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | De lagen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | De gemaakte [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) instantie. |


### Method: new_smart_object_via_copy(source_layer) {#new_smart_object_via_copy_source_layer_3}


```
 new_smart_object_via_copy(source_layer) 
```

Maakt een nieuwe smart object-laag door de bronlaag te kopiëren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_layer | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | De bronlaag. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | De gekloonde [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) instantie. |


