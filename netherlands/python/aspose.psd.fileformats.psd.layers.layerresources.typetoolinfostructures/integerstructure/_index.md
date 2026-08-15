---
title: "IntegerStructure Klasse"
type: docs
weight: 80
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/integerstructure/
---

**Summary:** The integer structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.IntegerStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [IntegerStructure(key_name)](#IntegerStructure_key_name_1) | Initialiseert een nieuw exemplaar van de [IntegerStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/integerstructure/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | De integer-structuursleutel. |
| key | int | r | Haalt de sleutel op. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Haalt de key name op of stelt deze in. |
| length | int | r | Haalt de [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) lengte in bytes op. |
| value | int | r/w | Haalt op of stelt een integerwaarde in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Haalt de header length op. |
| [save(stream_container)](#save_stream_container_2) | Slaat de structuur op in de opgegeven streamcontainer. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Slaat de structuur op in de opgegeven streamcontainer. |


### Constructor: IntegerStructure(key_name) {#IntegerStructure_key_name_1}


```
 IntegerStructure(key_name) 
```

Initialiseert een nieuw exemplaar van de [IntegerStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/integerstructure/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | De sleutelnaam. |

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

