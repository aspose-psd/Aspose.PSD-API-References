---
title: "StringStructure क्लास"
type: docs
weight: 160
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/
---

**Summary:** The string structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.StringStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [StringStructure(key_name)](#StringStructure_key_name_1) | नया उदाहरण प्रारंभ करता है [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) क्लास का। |
| [StringStructure(key_name, value)](#StringStructure_key_name_value_2) | नया उदाहरण प्रारंभ करता है [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) क्लास का मान के साथ। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [स्थिर] | int | r | संरचना कुंजी की पहचान करता है। |
| key | int | r | कुंजी प्राप्त करता है। |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | key name को प्राप्त करता है या सेट करता है। |
| length | int | r | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) की लंबाई बाइट्स में प्राप्त करता है। |
| value | string | r/w | मान को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | हेडर की लंबाई प्राप्त करता है। |
| [save(stream_container)](#save_stream_container_2) | निर्दिष्ट स्ट्रीम कंटेनर में संरचना को सहेजता है। |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | निर्दिष्ट स्ट्रीम कंटेनर में संरचना को सहेजता है। |


### Constructor: StringStructure(key_name) {#StringStructure_key_name_1}


```
 StringStructure(key_name) 
```

नया उदाहरण प्रारंभ करता है [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | कुंजी का नाम। |

### Constructor: StringStructure(key_name, value) {#StringStructure_key_name_value_2}


```
 StringStructure(key_name, value) 
```

नया उदाहरण प्रारंभ करता है [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) क्लास का मान के साथ।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | कुंजी का नाम। |
| value | string | मान। |

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

