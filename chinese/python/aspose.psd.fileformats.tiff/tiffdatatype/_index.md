---
title: "TiffDataType 类"
type: docs
weight: 10
url: /zh/python-net/aspose.psd.fileformats.tiff/tiffdatatype/
---

**Summary:** The tiff data type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffDataType

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| aligned_data_size | uint | r | 获取以字节为单位的额外数据大小（如果 12 字节不足以容纳标签数据时）。 |
| 计数 | uint | r | 获取元素的计数。 |
| data_size | uint | r | 获取以字节为单位的额外数据大小（如果 12 字节不足以容纳标签数据时）。 |
| id | ushort | r | 获取标签 ID 的整数表示。 |
| is_valid | bool | r | 获取一个值，指示标签数据是否有效。有效的标签包含可以保留的数据。无效的标签无法存储。 |
| tag_id | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | r | 获取标签 ID。 |
| tag_type | [TiffDataTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffdatatypes/) | r | 获取标签类型。 |
| value | object | 读/写 | 获取或设置此数据类型包含的值。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | 比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于前、后还是与另一个对象相同位置。 |
| [deep_clone()](#deep_clone__2) | 对该实例执行深度克隆。 |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_3) | 读取标签数据。 |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_4) | 写入额外的标签数据。 |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_5) | 写入标签数据。 |


### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于前、后还是与另一个对象相同位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| obj | object | 用于与此实例比较的对象。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 一个 32 位有符号整数，用于指示被比较对象的相对顺序。返回值具有以下含义：<br/>            值<br/>            含义<br/>            小于零<br/>            此实例小于 <paramref name="obj" />。<br/>            零<br/>            此实例等于 <paramref name="obj" />。<br/>            大于零<br/>            此实例大于 <paramref name="obj" />。 |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

对该实例执行深度克隆。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | 当前实例的深度克隆。 |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_3}


```
 read_tag(data_stream, position) 
```

读取标签数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) | 数据流。 |
| position | long | 标签位置。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | 读取的标签。 |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_4}


```
 write_additional_data(data_stream) 
```

写入额外的标签数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | 数据流。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| long | 实际写入的字节数。 |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_5}


```
 write_tag(data_stream, additional_data_offset) 
```

写入标签数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | 数据流。 |
| additional_data_offset | long | 写入附加数据的偏移量。 |

