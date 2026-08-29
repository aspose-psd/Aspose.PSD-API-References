---
title: "ObjectArrayStructure klass"
type: docs
weight: 100
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---

**Summary:** Defines the ObjectArrayStructure class that usually holds [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) array.<br/>            It is used in the PSD file resources, such as PlLd Resource and SoLd Resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ObjectArrayStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [ObjectArrayStructure(key, key_name, class_id, class_name, structures)](#ObjectArrayStructure_key_key_name_class_id_class_name_structures_1) | Initierar en ny instans av klassen [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/). |
| [ObjectArrayStructure(key_name, class_id_name, structures)](#ObjectArrayStructure_key_name_class_id_name_structures_2) | Initierar en ny instans av klassen [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Identifierar nyckeln 'ObAr' för strukturen. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Hämtar eller anger objektarrayens klass-ID. |
| class_name | string | r/w | Hämtar eller anger namn på objektarrayens klass. |
| nyckel | int | r | Hämtar nyckeln för objektarrayens struktur. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Hämtar eller anger key name. |
| length | int | r | Hämtar [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) längd i byte. |
| structure_count | int | r | Hämtar antalet delstrukturer i objektarrayen. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Hämtar eller anger en kopia av en matris av strukturer. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Hämtar header length. |
| [save(stream_container)](#save_stream_container_2) | Sparar structure till den specificerade stream container. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Sparar structure till den specificerade stream container. |


### Constructor: ObjectArrayStructure(key, key_name, class_id, class_name, structures) {#ObjectArrayStructure_key_key_name_class_id_class_name_structures_1}


```
 ObjectArrayStructure(key, key_name, class_id, class_name, structures) 
```

Initierar en ny instans av klassen [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | int | Den heltalsnyckeln. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Nyckelnamnet. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Klassidentifieraren. |
| class_name | string | Namnet på klassen. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Strukturerna. |

### Constructor: ObjectArrayStructure(key_name, class_id_name, structures) {#ObjectArrayStructure_key_name_class_id_name_structures_2}


```
 ObjectArrayStructure(key_name, class_id_name, structures) 
```

Initierar en ny instans av klassen [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key_name | string | Namn på key. |
| class_id_name | string | Namnet på klassidentifieraren. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Strukturerna. |

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

