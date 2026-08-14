---
title: "ListStructure क्लास"
type: docs
weight: 90
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure/
---

**Summary:** The list structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [ListStructure(key_name)](#ListStructure_key_name_1) | एक नया उदाहरण प्रारंभ करता है [ListStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure/) क्लास। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [स्थिर] | int | r | संरचना कुंजी की पहचान करता है। |
| items_count | int | r | items की गिनती प्राप्त करता है। |
| key | int | r | संरचना कुंजी को प्राप्त करता है। |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | key name को प्राप्त करता है या सेट करता है। |
| length | int | r | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) की लंबाई बाइट्स में प्राप्त करता है। |
| types | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | संरचनाओं के एरे की एक प्रति प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | हेडर की लंबाई प्राप्त करता है। |
| [save(stream_container)](#save_stream_container_2) | निर्दिष्ट स्ट्रीम कंटेनर में संरचना को सहेजता है। |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | निर्दिष्ट स्ट्रीम कंटेनर में संरचना को सहेजता है। |


### Constructor: ListStructure(key_name) {#ListStructure_key_name_1}


```
 ListStructure(key_name) 
```

एक नया उदाहरण प्रारंभ करता है [ListStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure/) क्लास।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | कुंजी का नाम। |

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

