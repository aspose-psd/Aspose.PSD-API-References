---
title: "ObjectArrayStructure क्लास"
type: docs
weight: 100
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---

**Summary:** Defines the ObjectArrayStructure class that usually holds [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) array.<br/>            It is used in the PSD file resources, such as PlLd Resource and SoLd Resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ObjectArrayStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [ObjectArrayStructure(key, key_name, class_id, class_name, structures)](#ObjectArrayStructure_key_key_name_class_id_class_name_structures_1) | नया उदाहरण इनिशियलाइज़ करता है [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/) क्लास का। |
| [ObjectArrayStructure(key_name, class_id_name, structures)](#ObjectArrayStructure_key_name_class_id_name_structures_2) | नया उदाहरण इनिशियलाइज़ करता है [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [स्थिर] | int | r | 'ObAr' संरचना कुंजी की पहचान करता है। |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | ऑब्जेक्ट एरे क्लास ID को प्राप्त करता है या सेट करता है। |
| class_name | string | r/w | ऑब्जेक्ट एरे क्लास नाम को प्राप्त करता है या सेट करता है। |
| key | int | r | ऑब्जेक्ट एरे संरचना कुंजी को प्राप्त करता है। |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | key name को प्राप्त करता है या सेट करता है। |
| length | int | r | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) की लंबाई बाइट्स में प्राप्त करता है। |
| structure_count | int | r | ऑब्जेक्ट एरे सबस्ट्रक्चर गिनती को प्राप्त करता है। |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | संरचनाओं के एरे की एक प्रति प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | हेडर की लंबाई प्राप्त करता है। |
| [save(stream_container)](#save_stream_container_2) | निर्दिष्ट स्ट्रीम कंटेनर में संरचना को सहेजता है। |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | निर्दिष्ट स्ट्रीम कंटेनर में संरचना को सहेजता है। |


### Constructor: ObjectArrayStructure(key, key_name, class_id, class_name, structures) {#ObjectArrayStructure_key_key_name_class_id_class_name_structures_1}


```
 ObjectArrayStructure(key, key_name, class_id, class_name, structures) 
```

नया उदाहरण इनिशियलाइज़ करता है [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key | int | इंटीजर कुंजी। |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | कुंजी का नाम। |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | क्लास पहचानकर्ता। |
| class_name | string | क्लास का नाम। |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | संरचनाएँ। |

### Constructor: ObjectArrayStructure(key_name, class_id_name, structures) {#ObjectArrayStructure_key_name_class_id_name_structures_2}


```
 ObjectArrayStructure(key_name, class_id_name, structures) 
```

नया उदाहरण इनिशियलाइज़ करता है [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key_name | string | कुंजी का नाम। |
| class_id_name | string | क्लास पहचानकर्ता का नाम। |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | संरचनाएँ। |

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

