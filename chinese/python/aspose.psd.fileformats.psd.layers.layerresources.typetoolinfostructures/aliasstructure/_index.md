---
title: "AliasStructure 类"
type: docs
weight: 10
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/aliasstructure/
---

**Summary:** The alias structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.AliasStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AliasStructure(key_name)](#AliasStructure_key_name_1) | 初始化 [AliasStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/aliasstructure/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | 标识结构键。 |
| data_length | int | r | 获取以字节为单位的精确数据长度。 |
| full_path | 字符串 | 读/写 | 获取或设置完整路径。 |
| key | int | r | 获取结构键。 |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | 获取或设置键名。 |
| length | int | r | 获取 [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) 的字节长度。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | 获取头部长度。 |
| [save(stream_container)](#save_stream_container_2) | 将结构保存到指定的流容器。 |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | 将结构保存到指定的流容器。 |


### Constructor: AliasStructure(key_name) {#AliasStructure_key_name_1}


```
 AliasStructure(key_name) 
```

初始化 [AliasStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/aliasstructure/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | 键名。 |

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

将结构保存到指定的流容器。

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

