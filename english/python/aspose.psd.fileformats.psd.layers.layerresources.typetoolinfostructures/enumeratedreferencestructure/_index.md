---
title: EnumeratedReferenceStructure Class
type: docs
weight: 70
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure/
---

**Summary:** Enumerated reference structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.EnumeratedReferenceStructure

**Inheritance:** EnumeratedDescriptorStructure

**Aspose.PSD Version:** 24.1.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EnumeratedReferenceStructure(key_name, class_id, type_id, enum_name)](#EnumeratedReferenceStructure_key_name_class_id_type_id_enum_name_1) | Initializes a new instance of the [EnumeratedReferenceStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ENUMERATED_STRUCTURE_KEY [static] | int | r | Identifies the structure key. |
| STRUCTURE_KEY [static] | int | r | The enumerated descriptor key. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Gets or sets the class ID. |
| class_name | string | r/w | Gets or sets the class name. |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Gets or sets the enum name. |
| key | int | r | Gets the key. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Gets or sets the key name. |
| length | int | r | Gets the [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) length in bytes. |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Gets or sets the type ID. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Gets the header length. |
| [save(stream_container)](#save_stream_container_2) | Saves the data. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Saves the structure to the specified stream container. |


### Constructor: EnumeratedReferenceStructure(key_name, class_id, type_id, enum_name) {#EnumeratedReferenceStructure_key_name_class_id_type_id_enum_name_1}


```
 EnumeratedReferenceStructure(key_name, class_id, type_id, enum_name) 
```

Initializes a new instance of the [EnumeratedReferenceStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | The key name. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | The class ID. |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | The type ID. |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | The enum name. |

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

