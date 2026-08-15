---
title: "ClassStructure Class"
type: docs
weight: 30
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/
---

**Summary:** The class structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ClassStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [ClassStructure(key_name, class_id, structure_key)](#ClassStructure_key_name_class_id_structure_key_1) | Initierar en ny instans av [ClassStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/) klassen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| STRUCTURE_KEY_CLSS [static] | int | r | Identifierar structure key. |
| STRUCTURE_KEY_GLBC [static] | int | r | Identifierar structure key. |
| STRUCTURE_KEY_TYPE [static] | int | r | Identifierar structure key. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Hämtar eller anger class ID. |
| class_name | string | r/w | Hämtar eller anger class name. |
| nyckel | int | r | Hämtar structure key. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Hämtar eller anger key name. |
| length | int | r | Hämtar [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) längd i byte. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Hämtar header length. |
| [save(stream_container)](#save_stream_container_2) | Sparar structure till den specificerade stream container. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Sparar structure till den specificerade stream container. |


### Constructor: ClassStructure(key_name, class_id, structure_key) {#ClassStructure_key_name_class_id_structure_key_1}


```
 ClassStructure(key_name, class_id, structure_key) 
```

Initierar en ny instans av [ClassStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/) klassen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Namn på key. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Den class ID. |
| structure_key | int | Den structure key. |

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

