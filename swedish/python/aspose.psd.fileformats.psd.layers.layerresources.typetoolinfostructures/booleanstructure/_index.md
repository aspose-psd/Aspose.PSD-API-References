---
title: "BooleanStructure klass"
type: docs
weight: 20
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/booleanstructure/
---

**Summary:** The boolean structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.BooleanStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [BooleanStructure(key_name)](#BooleanStructure_key_name_1) | Initierar en ny instans av klassen [BooleanStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/booleanstructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Identifierar structure key. |
| nyckel | int | r | Hämtar structure key. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Hämtar eller anger key name. |
| length | int | r | Hämtar [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) längd i byte. |
| värde | bool | r/w | Hämtar eller anger ett booleskt värde. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Hämtar header length. |
| [save(stream_container)](#save_stream_container_2) | Sparar structure till den specificerade stream container. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Sparar structure till den specificerade stream container. |


### Constructor: BooleanStructure(key_name) {#BooleanStructure_key_name_1}


```
 BooleanStructure(key_name) 
```

Initierar en ny instans av klassen [BooleanStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/booleanstructure/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Nyckelnamnet. |

### Method: get_header_length() {#get_header_length__1}


```
 get_header_length() 
```

Hämtar header length.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Den header length |


### Method: save(stream_container) {#save_stream_container_2}


```
 save(stream_container) 
```

Sparar structure till den specificerade stream container.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren. |

### Method: save_without_key_name(stream_container) {#save_without_key_name_stream_container_3}


```
 save_without_key_name(stream_container) 
```

Sparar structure till den specificerade stream container.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren. |

