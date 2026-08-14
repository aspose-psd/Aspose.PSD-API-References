---
title: "SmartObjectProvider क्लास"
type: docs
weight: 1940
url: /hi/python-net/aspose.psd.fileformats.psd/smartobjectprovider/
---

**Summary:** Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.SmartObjectProvider

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [convert_to_smart_object(layer_numbers)](#convert_to_smart_object_layer_numbers_1) | लेयर्स को एम्बेडेड स्मार्ट ऑब्जेक्ट में परिवर्तित करता है। |
| [convert_to_smart_object(layers)](#convert_to_smart_object_layers_2) | लेयर्स को एम्बेडेड स्मार्ट ऑब्जेक्ट में परिवर्तित करता है। |
| embed_all_linked() | छवि में सभी लिंक्ड स्मार्ट ऑब्जेक्ट्स को एम्बेड करता है। |
| [new_smart_object_via_copy(source_layer)](#new_smart_object_via_copy_source_layer_3) | स्रोत लेयर की कॉपी करके नया स्मार्ट ऑब्जेक्ट लेयर बनाता है। |
| update_all_modified_content() | छवि में सभी संशोधित स्मार्ट ऑब्जेक्ट्स की सामग्री को अपडेट करता है। |


### Method: convert_to_smart_object(layer_numbers) {#convert_to_smart_object_layer_numbers_1}


```
 convert_to_smart_object(layer_numbers) 
```

लेयर्स को एम्बेडेड स्मार्ट ऑब्जेक्ट में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer_numbers | int | लेयर संख्याएँ। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | बनाया गया [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) इंस्टेंस। |


### Method: convert_to_smart_object(layers) {#convert_to_smart_object_layers_2}


```
 convert_to_smart_object(layers) 
```

लेयर्स को एम्बेडेड स्मार्ट ऑब्जेक्ट में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | लेयर्स। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | बनाया गया [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) इंस्टेंस। |


### Method: new_smart_object_via_copy(source_layer) {#new_smart_object_via_copy_source_layer_3}


```
 new_smart_object_via_copy(source_layer) 
```

स्रोत लेयर की कॉपी करके नया स्मार्ट ऑब्जेक्ट लेयर बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_layer | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | स्रोत लेयर। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | क्लोन किया गया [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) इंस्टेंस। |


