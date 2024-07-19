---
title: ObjectArrayStructure Class
type: docs
weight: 100
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---

**Summary:** Defines the ObjectArrayStructure class that usually holds [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) array.<br/>            It is used in the PSD file resources, such as PlLd Resource and SoLd Resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ObjectArrayStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.5.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ObjectArrayStructure(key, key_name, class_id, class_name, structures)](#ObjectArrayStructure_key_key_name_class_id_class_name_structures_1) | Initializes a new instance of the [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/) class. |
| [ObjectArrayStructure(key_name, class_id_name, structures)](#ObjectArrayStructure_key_name_class_id_name_structures_2) | Initializes a new instance of the [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Identifies the 'ObAr' structure key. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Gets or sets the object array class ID. |
| class_name | string | r/w | Gets or sets the object array class name. |
| key | int | r | Gets the object array structure key. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Gets or sets the key name. |
| length | int | r | Gets the [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) length in bytes. |
| structure_count | int | r | Gets the object array substructure count. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Gets or sets a copy of an array of structures. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Gets the header length. |
| [save(stream_container)](#save_stream_container_2) | Saves the structure to the specified stream container. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Saves the structure to the specified stream container. |


### Constructor: ObjectArrayStructure(key, key_name, class_id, class_name, structures) {#ObjectArrayStructure_key_key_name_class_id_class_name_structures_1}


```
 ObjectArrayStructure(key, key_name, class_id, class_name, structures) 
```

Initializes a new instance of the [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | int | The integer key. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | The key name. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | The class identifier. |
| class_name | string | Name of the class. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | The structures. |

### Constructor: ObjectArrayStructure(key_name, class_id_name, structures) {#ObjectArrayStructure_key_name_class_id_name_structures_2}


```
 ObjectArrayStructure(key_name, class_id_name, structures) 
```

Initializes a new instance of the [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key_name | string | Name of the key. |
| class_id_name | string | Name of the class identifier. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | The structures. |

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

