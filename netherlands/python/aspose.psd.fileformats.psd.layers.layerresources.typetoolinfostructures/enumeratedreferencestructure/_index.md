---
title: "EnumeratedReferenceStructure Klasse"
type: docs
weight: 70
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure/
---

**Summary:** Enumerated reference structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.EnumeratedReferenceStructure

**Inheritance:** EnumeratedDescriptorStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [EnumeratedReferenceStructure(key_name, class_id, type_id, enum_name)](#EnumeratedReferenceStructure_key_name_class_id_type_id_enum_name_1) | Initialiseert een nieuw exemplaar van de [EnumeratedReferenceStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| ENUMERATED_STRUCTURE_KEY [static] | int | r | Identificeert de structure key. |
| STRUCTURE_KEY [static] | int | r | De genummerde descriptor sleutel. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Haalt de class ID op of stelt deze in. |
| class_name | string | r/w | Haalt de class name op of stelt deze in. |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Haalt de enumnaam op of stelt deze in. |
| key | int | r | Haalt de sleutel op. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Haalt de key name op of stelt deze in. |
| length | int | r | Haalt de [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) lengte in bytes op. |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Haalt de type-ID op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Haalt de header length op. |
| [save(stream_container)](#save_stream_container_2) | Slaat de gegevens op. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Slaat de structuur op in de opgegeven streamcontainer. |


### Constructor: EnumeratedReferenceStructure(key_name, class_id, type_id, enum_name) {#EnumeratedReferenceStructure_key_name_class_id_type_id_enum_name_1}


```
 EnumeratedReferenceStructure(key_name, class_id, type_id, enum_name) 
```

Initialiseert een nieuw exemplaar van de [EnumeratedReferenceStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | De sleutelnaam. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | De klasse-ID. |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | De type-ID. |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | De enumnaam. |

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

Slaat de gegevens op.

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

