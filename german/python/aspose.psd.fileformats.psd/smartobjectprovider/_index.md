---
title: "SmartObjectProvider Klasse"
type: docs
weight: 1940
url: /de/python-net/aspose.psd.fileformats.psd/smartobjectprovider/
---

**Summary:** Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.SmartObjectProvider

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [convert_to_smart_object(layer_numbers)](#convert_to_smart_object_layer_numbers_1) | Konvertiert Ebenen in ein eingebettetes Smart-Objekt. |
| [convert_to_smart_object(layers)](#convert_to_smart_object_layers_2) | Konvertiert Ebenen in ein eingebettetes Smart-Objekt. |
| embed_all_linked() | Bettet alle verknüpften Smart Objects in das Bild ein. |
| [new_smart_object_via_copy(source_layer)](#new_smart_object_via_copy_source_layer_3) | Erstellt eine neue Smart Object‑Ebene, indem die Quell‑Ebene kopiert wird. |
| update_all_modified_content() | Aktualisiert den Inhalt aller modifizierten Smart Objects im Bild. |


### Method: convert_to_smart_object(layer_numbers) {#convert_to_smart_object_layer_numbers_1}


```
 convert_to_smart_object(layer_numbers) 
```

Konvertiert Ebenen in ein eingebettetes Smart-Objekt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer_numbers | int | Die Ebenennummern. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Die erstellte [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) Instanz. |


### Method: convert_to_smart_object(layers) {#convert_to_smart_object_layers_2}


```
 convert_to_smart_object(layers) 
```

Konvertiert Ebenen in ein eingebettetes Smart-Objekt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Die Ebenen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Die erstellte [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) Instanz. |


### Method: new_smart_object_via_copy(source_layer) {#new_smart_object_via_copy_source_layer_3}


```
 new_smart_object_via_copy(source_layer) 
```

Erstellt eine neue Smart Object‑Ebene, indem die Quell‑Ebene kopiert wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_layer | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Die Quell‑Ebene. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Die geklonte [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) Instanz. |


