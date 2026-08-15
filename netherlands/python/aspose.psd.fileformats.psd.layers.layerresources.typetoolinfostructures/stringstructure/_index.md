---
title: "StringStructure Klasse"
type: docs
weight: 160
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/
---

**Summary:** The string structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.StringStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [StringStructure(key_name)](#StringStructure_key_name_1) | Initialiseert een nieuw exemplaar van de [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) klasse. |
| [StringStructure(key_name, value)](#StringStructure_key_name_value_2) | Initialiseert een nieuw exemplaar van de [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) klasse met waarde. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Identificeert de structure key. |
| key | int | r | Haalt de sleutel op. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Haalt de key name op of stelt deze in. |
| length | int | r | Haalt de [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) lengte in bytes op. |
| value | string | r/w | Haalt op of stelt de waarde in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Haalt de header length op. |
| [save(stream_container)](#save_stream_container_2) | Slaat de structuur op in de opgegeven streamcontainer. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Slaat de structuur op in de opgegeven streamcontainer. |


### Constructor: StringStructure(key_name) {#StringStructure_key_name_1}


```
 StringStructure(key_name) 
```

Initialiseert een nieuw exemplaar van de [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | De sleutelnaam. |

### Constructor: StringStructure(key_name, value) {#StringStructure_key_name_value_2}


```
 StringStructure(key_name, value) 
```

Initialiseert een nieuw exemplaar van de [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) klasse met waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | De sleutelnaam. |
| value | string | De value. |

### Method: get_header_length() {#get_header_length__1}


```
 get_header_length() 
```

Haalt de header length op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De headerlengte |


### Method: save(stream_container) {#save_stream_container_2}


```
 save(stream_container) 
```

Slaat de structuur op in de opgegeven streamcontainer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer. |

### Method: save_without_key_name(stream_container) {#save_without_key_name_stream_container_3}


```
 save_without_key_name(stream_container) 
```

Slaat de structuur op in de opgegeven streamcontainer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer. |

