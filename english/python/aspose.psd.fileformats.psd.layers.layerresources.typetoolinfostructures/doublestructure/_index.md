---
title: DoubleStructure Class
type: docs
weight: 50
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/doublestructure/
---

**Summary:** The double structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DoubleStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [DoubleStructure(key_name)](#DoubleStructure_key_name_1) | Initializes a new instance of the [DoubleStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/doublestructure/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Identifies the structure key. |
| key | int | r | Gets the structure key. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Gets or sets the key name. |
| length | int | r | Gets the [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) length in bytes. |
| value | double | r/w | Gets or sets the double value. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Gets the header length. |
| [save(stream_container)](#save_stream_container_2) | Saves the structure to the specified stream container. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Saves the structure to the specified stream container. |


### Constructor: DoubleStructure(key_name) {#DoubleStructure_key_name_1}


```
 DoubleStructure(key_name) 
```

Initializes a new instance of the [DoubleStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/doublestructure/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | The key name. |

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

Saves the structure to the specified stream container.

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

