---
title: "UnknownStructure Klasse"
type: docs
weight: 190
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unknownstructure/
---

**Summary:** The unknown structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.UnknownStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [UnknownStructure(key_name, key)](#UnknownStructure_key_name_key_1) | Initialiseert een nieuw exemplaar van de [UnknownStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unknownstructure/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| data | byte | r/w | Haalt de gegevens op of stelt ze in. |
| key | int | r | Haalt de structure key op. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Haalt de key name op of stelt deze in. |
| length | int | r | Haalt de [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) lengte in bytes op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Haalt de header length op. |
| [save(stream_container)](#save_stream_container_2) | Slaat de structuur op in de opgegeven streamcontainer. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Slaat de structuur op in de opgegeven streamcontainer. |


### Constructor: UnknownStructure(key_name, key) {#UnknownStructure_key_name_key_1}


```
 UnknownStructure(key_name, key) 
```

Initialiseert een nieuw exemplaar van de [UnknownStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unknownstructure/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | De sleutelnaam. |
| key | int | De structuur‑sleutel. |

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

