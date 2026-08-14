---
title: "UnitArrayStructure क्लास"
type: docs
weight: 170
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/
---

**Summary:** Defines the UnitArrayStructure class that holds float values array and their measure unit.<br/>            It is used in the PSD file resources, usually by [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/).

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.UnitArrayStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [UnitArrayStructure(key_name, unit_type, values)](#UnitArrayStructure_key_name_unit_type_values_1) | नया उदाहरण प्रारंभ करता है [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | परिभाषित करता है 'UnFl' [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) कुंजी को। |
| key | int | r | इस यूनिट एरे संरचना कुंजी को प्राप्त करता है। |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | key name को प्राप्त करता है या सेट करता है। |
| length | int | r | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) की लंबाई बाइट्स में प्राप्त करता है। |
| unit_type | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes) | r/w | माप इकाई प्रकार को प्राप्त करता है या सेट करता है [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) मानों का। |
| value_count | int | r | मान गिनती को प्राप्त करता है। |
| मान | डबल | r/w | इकाई एरे संरचना मान प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | हेडर की लंबाई प्राप्त करता है। |
| [save(stream_container)](#save_stream_container_2) | निर्दिष्ट स्ट्रीम कंटेनर में संरचना को सहेजता है। |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | निर्दिष्ट स्ट्रीम कंटेनर में संरचना को सहेजता है। |


### Constructor: UnitArrayStructure(key_name, unit_type, values) {#UnitArrayStructure_key_name_unit_type_values_1}


```
 UnitArrayStructure(key_name, unit_type, values) 
```

नया उदाहरण प्रारंभ करता है [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | कुंजी का नाम। |
| unit_type | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes) | इकाई का प्रकार। |
| मान | डबल | मान। |

### Method: get_header_length() {#get_header_length__1}


```
 get_header_length() 
```

हेडर की लंबाई प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | हेडर की लंबाई |


### Method: save(stream_container) {#save_stream_container_2}


```
 save(stream_container) 
```

निर्दिष्ट स्ट्रीम कंटेनर में संरचना को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |

### Method: save_without_key_name(stream_container) {#save_without_key_name_stream_container_3}


```
 save_without_key_name(stream_container) 
```

निर्दिष्ट स्ट्रीम कंटेनर में संरचना को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |

