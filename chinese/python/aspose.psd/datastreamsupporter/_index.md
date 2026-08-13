---
title: "DataStreamSupporter 类"
type: docs
weight: 1030
url: /zh/python-net/aspose.psd/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.DataStreamSupporter

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | 获取对象的数据流。 |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| is_cached | bool | r | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| cache_data() | 缓存数据，并确保不会从底层 [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) 进行额外的数据加载。 |
| save() | 将对象的数据保存到当前的 [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/)。 |
| [save(file_path)](#save_file_path_1) | 将对象的数据保存到指定的文件位置。 |
| [save(file_path, over_write)](#save_file_path_over_write_2) | 将对象的数据保存到指定的文件位置。 |
| [save(stream)](#save_stream_3) | 将对象的数据保存到指定的流中。 |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

将对象的数据保存到指定的文件位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 用于保存对象数据的文件路径。 |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

将对象的数据保存到指定的文件位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 用于保存对象数据的文件路径。 |
| over_write | bool | 如果设置为 <c>true</c>，则覆盖文件内容；否则将追加。 |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

将对象的数据保存到指定的流中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存对象数据的流。 |

