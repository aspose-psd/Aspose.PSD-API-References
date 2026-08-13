---
title: "EnumeratedReferenceStructure 类"
type: docs
weight: 70
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure/
---

**Summary:** Enumerated reference structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.EnumeratedReferenceStructure

**Inheritance:** EnumeratedDescriptorStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EnumeratedReferenceStructure(key_name, class_id, type_id, enum_name)](#EnumeratedReferenceStructure_key_name_class_id_type_id_enum_name_1) | 初始化一个新的 [EnumeratedReferenceStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ENUMERATED_STRUCTURE_KEY [static] | int | r | 标识结构键。 |
| STRUCTURE_KEY [static] | int | r | 枚举描述符键。 |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | 获取或设置类 ID。 |
| class_name | 字符串 | 读/写 | 获取或设置类名。 |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | 获取或设置枚举名称。 |
| key | int | r | 获取键。 |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | 获取或设置键名。 |
| length | int | r | 获取 [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) 的字节长度。 |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | 获取或设置类型 ID。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | 获取头部长度。 |
| [save(stream_container)](#save_stream_container_2) | 保存数据。 |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | 将结构保存到指定的流容器。 |


### Constructor: EnumeratedReferenceStructure(key_name, class_id, type_id, enum_name) {#EnumeratedReferenceStructure_key_name_class_id_type_id_enum_name_1}


```
 EnumeratedReferenceStructure(key_name, class_id, type_id, enum_name) 
```

初始化一个新的 [EnumeratedReferenceStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure/) 类的实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | 键名。 |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | 类 ID。 |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | 类型 ID。 |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | 枚举名称。 |

### Method: get_header_length() {#get_header_length__1}


```
 get_header_length() 
```

获取头部长度。

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 头部长度 |


### Method: save(stream_container) {#save_stream_container_2}


```
 save(stream_container) 
```

保存数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 流容器。 |

### Method: save_without_key_name(stream_container) {#save_without_key_name_stream_container_3}


```
 save_without_key_name(stream_container) 
```

将结构保存到指定的流容器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 流容器。 |

