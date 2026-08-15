---
title: "SmartObjectProvider klass"
type: docs
weight: 1940
url: /sv/python-net/aspose.psd.fileformats.psd/smartobjectprovider/
---

**Summary:** Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.SmartObjectProvider

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [convert_to_smart_object(layer_numbers)](#convert_to_smart_object_layer_numbers_1) | Konverterar lager till ett inbäddat smart objekt. |
| [convert_to_smart_object(layers)](#convert_to_smart_object_layers_2) | Konverterar lager till ett inbäddat smart objekt. |
| embed_all_linked() | Bäddar in alla länkade smarta objekt i bilden. |
| [new_smart_object_via_copy(source_layer)](#new_smart_object_via_copy_source_layer_3) | Skapar ett nytt smart objekt‑lager genom att kopiera källlagret. |
| update_all_modified_content() | Uppdaterar innehållet i alla modifierade smarta objekt i bilden. |


### Method: convert_to_smart_object(layer_numbers) {#convert_to_smart_object_layer_numbers_1}


```
 convert_to_smart_object(layer_numbers) 
```

Konverterar lager till ett inbäddat smart objekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer_numbers | int | Lagernumren. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Den skapade [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)‑instansen. |


### Method: convert_to_smart_object(layers) {#convert_to_smart_object_layers_2}


```
 convert_to_smart_object(layers) 
```

Konverterar lager till ett inbäddat smart objekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Lagerna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Den skapade [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)‑instansen. |


### Method: new_smart_object_via_copy(source_layer) {#new_smart_object_via_copy_source_layer_3}


```
 new_smart_object_via_copy(source_layer) 
```

Skapar ett nytt smart objekt‑lager genom att kopiera källlagret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_layer | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Källagret. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Den klonade [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) instansen. |


