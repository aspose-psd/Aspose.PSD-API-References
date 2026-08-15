---
title: "DescriptorStructure Klasse"
type: docs
weight: 40
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/
---

**Summary:** The descriptor structure

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [DescriptorStructure(key_name, class_id, class_name, structures)](#DescriptorStructure_key_name_class_id_class_name_structures_1) | Initialiseert een nieuw exemplaar van de [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Identificeert de structure key. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Haalt de class ID op of stelt deze in. |
| class_name | string | r/w | Haalt de class name op of stelt deze in. |
| key | int | r | Haalt de structure key op. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Haalt de key name op of stelt deze in. |
| length | int | r | Haalt de [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) lengte in bytes op. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Haalt een kopie van een array van structuren op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Haalt de header length op. |
| [save(stream_container)](#save_stream_container_2) | Slaat de gegevens op. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Slaat de structuur op in de opgegeven streamcontainer. |


### Constructor: DescriptorStructure(key_name, class_id, class_name, structures) {#DescriptorStructure_key_name_class_id_class_name_structures_1}


```
 DescriptorStructure(key_name, class_id, class_name, structures) 
```

Initialiseert een nieuw exemplaar van de [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | De sleutelnaam. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | De klasse‑identificatie. |
| class_name | string | Naam van de klasse. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | De structuren. |

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

