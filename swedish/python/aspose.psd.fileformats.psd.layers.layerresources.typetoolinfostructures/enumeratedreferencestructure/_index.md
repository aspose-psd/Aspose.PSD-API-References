---
title: "EnumeratedReferenceStructure klass"
type: docs
weight: 70
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure/
---

**Summary:** Enumerated reference structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.EnumeratedReferenceStructure

**Inheritance:** EnumeratedDescriptorStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [EnumeratedReferenceStructure(key_name, class_id, type_id, enum_name)](#EnumeratedReferenceStructure_key_name_class_id_type_id_enum_name_1) | Initierar en ny instans av [EnumeratedReferenceStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| ENUMERATED_STRUCTURE_KEY [static] | int | r | Identifierar structure key. |
| STRUCTURE_KEY [static] | int | r | Den enumererade deskriptornyckeln. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Hämtar eller anger class ID. |
| class_name | string | r/w | Hämtar eller anger class name. |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Hämtar eller anger enum-namnet. |
| nyckel | int | r | Hämtar nyckeln. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Hämtar eller anger key name. |
| length | int | r | Hämtar [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) längd i byte. |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Hämtar eller anger typ-ID. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Hämtar header length. |
| [save(stream_container)](#save_stream_container_2) | Sparar data. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Sparar structure till den specificerade stream container. |


### Constructor: EnumeratedReferenceStructure(key_name, class_id, type_id, enum_name) {#EnumeratedReferenceStructure_key_name_class_id_type_id_enum_name_1}


```
 EnumeratedReferenceStructure(key_name, class_id, type_id, enum_name) 
```

Initierar en ny instans av [EnumeratedReferenceStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Nyckelnamnet. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Den class ID. |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Typ-ID. |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Enum-namnet. |

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

Sparar data.

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

