---
title: "ClassStructure क्लास"
type: docs
weight: 30
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/
---

**Summary:** The class structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ClassStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [ClassStructure(key_name, class_id, structure_key)](#ClassStructure_key_name_class_id_structure_key_1) | नया उदाहरण प्रारंभ करता है [ClassStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| STRUCTURE_KEY_CLSS [static] | int | r | संरचना कुंजी की पहचान करता है। |
| STRUCTURE_KEY_GLBC [static] | int | r | संरचना कुंजी की पहचान करता है। |
| STRUCTURE_KEY_TYPE [static] | int | r | संरचना कुंजी की पहचान करता है। |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | class ID को प्राप्त करता है या सेट करता है। |
| class_name | string | r/w | class name को प्राप्त करता है या सेट करता है। |
| key | int | r | संरचना कुंजी को प्राप्त करता है। |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | key name को प्राप्त करता है या सेट करता है। |
| length | int | r | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) की लंबाई बाइट्स में प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | हेडर की लंबाई प्राप्त करता है। |
| [save(stream_container)](#save_stream_container_2) | निर्दिष्ट स्ट्रीम कंटेनर में संरचना को सहेजता है। |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | निर्दिष्ट स्ट्रीम कंटेनर में संरचना को सहेजता है। |


### Constructor: ClassStructure(key_name, class_id, structure_key) {#ClassStructure_key_name_class_id_structure_key_1}


```
 ClassStructure(key_name, class_id, structure_key) 
```

नया उदाहरण प्रारंभ करता है [ClassStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | कुंजी का नाम। |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | क्लास आईडी। |
| structure_key | int | संरचना कुंजी। |

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

