---
title: "Txt2Resource 类"
type: docs
weight: 970
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Summary:** Txt2 resource class

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Txt2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Txt2Resource()](#Txt2Resource__1) | 初始化 Txt2Resource 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| 数据 | byte | 读/写 | 获取或设置数据。 |
| key | int | r | 获取图层资源键。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| signature | int | r | 获取签名。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_text_record(text, bounds)](#add_text_record_text_bounds_1) | 将文本记录添加到 Resource 并返回文本记录的 id。 |
| [get_text_data()](#get_text_data__2) | 从资源数据中获取文本记录。 |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_3) | 保存指定的流容器。 |


### Constructor: Txt2Resource() {#Txt2Resource__1}


```
 Txt2Resource() 
```

初始化 Txt2Resource 类的新实例

### Method: add_text_record(text, bounds) {#add_text_record_text_bounds_1}


```
 add_text_record(text, bounds) 
```

将文本记录添加到 Resource 并返回文本记录的 id。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | 字符串 | 记录文本。 |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 边界。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 返回资源的文本记录 Id |


### Method: get_text_data() {#get_text_data__2}


```
 get_text_data() 
```

从资源数据中获取文本记录。

**Returns**

| 类型 | 描述 |
| :- | :- |
| 字符串 | 文本记录数组 |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_3}


```
 save(stream_container, psd_version) 
```

保存指定的流容器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 流容器。 |
| psd_version | int | PSD 版本。 |

