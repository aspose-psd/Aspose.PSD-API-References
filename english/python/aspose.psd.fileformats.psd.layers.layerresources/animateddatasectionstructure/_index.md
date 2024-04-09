---
title: AnimatedDataSectionStructure Class
type: docs
weight: 30
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/
---

**Summary:** The section with animated data.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.AnimatedDataSectionStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.2.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Identifies the structure key of AnDs. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r | Gets or sets the animated data section structures. |
| key | int | r | Gets the structure key. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Gets or sets the key name. |
| length | int | r | Gets the [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) length in bytes. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Gets the header length. |
| [save(stream_container)](#save_stream_container_2) | Saves the data. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Saves the structure to the specified stream container. |


### Method: get_header_length() {#get_header_length__1}


```
 get_header_length() 
```

Gets the header length.

**Returns**

| Type | Description |
| :- | :- |
| int | The header length |


### Method: save(stream_container) {#save_stream_container_2}


```
 save(stream_container) 
```

Saves the data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container. |

### Method: save_without_key_name(stream_container) {#save_without_key_name_stream_container_3}


```
 save_without_key_name(stream_container) 
```

Saves the structure to the specified stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container. |

