---
title: "Κλάση SmartObjectProvider"
type: docs
weight: 1940
url: /el/python-net/aspose.psd.fileformats.psd/smartobjectprovider/
---

**Summary:** Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.SmartObjectProvider

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [convert_to_smart_object(layer_numbers)](#convert_to_smart_object_layer_numbers_1) | Μετατρέπει τα στρώματα σε ενσωματωμένο smart object. |
| [convert_to_smart_object(layers)](#convert_to_smart_object_layers_2) | Μετατρέπει τα στρώματα σε ενσωματωμένο smart object. |
| embed_all_linked() | Ενσωματώνει όλα τα συνδεδεμένα smart objects στην εικόνα. |
| [new_smart_object_via_copy(source_layer)](#new_smart_object_via_copy_source_layer_3) | Δημιουργεί ένα νέο στρώμα smart object αντιγράφοντας το πηγαίο. |
| update_all_modified_content() | Ενημερώνει το περιεχόμενο όλων των τροποποιημένων smart objects στην εικόνα. |


### Method: convert_to_smart_object(layer_numbers) {#convert_to_smart_object_layer_numbers_1}


```
 convert_to_smart_object(layer_numbers) 
```

Μετατρέπει τα στρώματα σε ενσωματωμένο smart object.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer_numbers | int | Οι αριθμοί των στρωμάτων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Η δημιουργημένη παρουσία του [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) αντικειμένου. |


### Method: convert_to_smart_object(layers) {#convert_to_smart_object_layers_2}


```
 convert_to_smart_object(layers) 
```

Μετατρέπει τα στρώματα σε ενσωματωμένο smart object.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Τα στρώματα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Η δημιουργημένη παρουσία του [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) αντικειμένου. |


### Method: new_smart_object_via_copy(source_layer) {#new_smart_object_via_copy_source_layer_3}


```
 new_smart_object_via_copy(source_layer) 
```

Δημιουργεί ένα νέο στρώμα smart object αντιγράφοντας το πηγαίο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_layer | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Το αρχικό στρώμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Η κλωνοποιημένη [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) αντίγραφο. |


