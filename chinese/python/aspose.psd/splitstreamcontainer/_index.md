---
title: "SplitStreamContainer 类"
type: docs
weight: 4220
url: /zh/python-net/aspose.psd/splitstreamcontainer/
---

**Summary:** Represents split stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SplitStreamContainer

**Inheritance:** StreamContainer

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SplitStreamContainer(stream)](#SplitStreamContainer_stream_1) | 初始化 [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) 类的新实例。 |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_2) | 初始化 [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) 类的新实例。 |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_3) | 初始化 [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | 指定顺序读取时的读写字节计数。 |
| can_read | bool | r | 获取一个值，指示流是否支持读取。 |
| can_seek | bool | r | 获取一个值，指示流是否支持定位。 |
| can_write | bool | r | 获取一个值，指示流是否支持写入。 |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| is_stream_disposed_on_close | bool | r | 获取一个值，指示此流在关闭时是否被释放。 |
| 长度 | long | 读/写 | 获取或设置流的字节长度。该值小于在 StreamContainer 构造函数中传入的起始流位置所产生的值。 |
| position | long | 读/写 | 获取或设置流中的当前位置。该值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| 流 | _io.BufferedRandom | r | 获取数据流。 |
| sync_root | object | r | 获取一个可用于同步对同步资源访问的对象。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| flush() | 清除此流的所有缓冲区，并将任何缓冲的数据写入底层设备。 |
| [insert(position, stream, dispose_stream)](#insert_position_stream_dispose_stream_1) | 将流容器插入指定位置。 |
| [read(buffer, offset, count)](#read_buffer_offset_count_2) | 从当前流读取一系列字节，并将流中的位置前移读取的字节数。 |
| [read(bytes)](#read_bytes_3) | 读取字节以填充指定的字节缓冲区。 |
| [read_byte()](#read_byte__4) | 从流中读取一个字节，并将流中的位置前移一个字节；如果已到达流末尾，则返回 -1。 |
| [save(destination_stream)](#save_destination_stream_5) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) 和流的 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 值。 |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_6) | 将流的全部数据保存（复制）到指定的流。使用流的 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 值。 |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_7) | 将流的数据保存（复制）到指定的流。 |
| [save(file_path)](#save_file_path_8) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) 和流的 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 值。 |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_9) | 将流的数据保存（复制）到指定的流。使用流的 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 值。 |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_10) | 将流的数据保存（复制）到指定的流。 |
| [seek(offset, origin)](#seek_offset_origin_11) | 设置当前流中的位置。 |
| seek_begin() | 将流位置设置为流的开头。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| [to_bytes()](#to_bytes__12) | 将流数据转换为 int 数组。 |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_13) | 将流数据转换为 int 数组。 |
| [write(buffer, offset, count)](#write_buffer_offset_count_14) | 将一系列字节写入当前流，并根据写入的字节数前移该流中的当前位置。 |
| [write(bytes)](#write_bytes_15) | 将所有指定的字节写入流。 |
| [write_byte(value)](#write_byte_value_16) | 在流的当前位置写入一个字节，并将流中的位置前移一个字节。 |
| [write_to(stream_container)](#write_to_stream_container_17) | 将包含的数据复制到另一个 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/)。 |
| [write_to(stream_container, length)](#write_to_stream_container_length_18) | 将包含的数据复制到另一个 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/)。 |


### Constructor: SplitStreamContainer(stream) {#SplitStreamContainer_stream_1}


```
 SplitStreamContainer(stream) 
```

初始化 [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 流。 |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_2}


```
 SplitStreamContainer(stream, dispose_stream) 
```

初始化 [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 数据流。 |
| dispose_stream | bool | 如果设置为 <c>true</c>，则在容器被释放时流也会被释放。 |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_3}


```
 SplitStreamContainer(stream, dispose_stream) 
```

初始化 [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 数据流。 |
| dispose_stream | bool | 如果设置为 <c>true</c>，则在容器被释放时流也会被释放。 |

### Method: insert(position, stream, dispose_stream) {#insert_position_stream_dispose_stream_1}


```
 insert(position, stream, dispose_stream) 
```

将流容器插入指定位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | int | 要插入的位置。 |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 要插入的流容器。 |
| dispose_stream | bool | 如果设置为 <c>true</c>，则释放流。 |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_2}


```
 read(buffer, offset, count) 
```

从当前流读取一系列字节，并将流中的位置前移读取的字节数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 缓冲区 | byte | 字节数组。当此方法返回时，缓冲区包含指定的字节数组，其中位于 <paramref name=\"offset\" /> 与 (<paramref name=\"offset\" /> + <paramref name=\"count\" /> - 1) 之间的值已被从当前源读取的字节替换。 |
| offset | int | <paramref name=\"buffer\" /> 中的零基字节偏移量，指示从当前流读取的数据开始存储的位置。 |
| 计数 | int | 从当前流读取的最大字节数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 读取到缓冲区的字节总数。如果当前可用字节不足，请求的字节数可能会更少，或者在已到达流末尾时为零 (0)。 |


### Method: read(bytes) {#read_bytes_3}


```
 read(bytes) 
```

读取字节以填充指定的字节缓冲区。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 字节 | byte | 要填充的字节。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 读取的字节数。如果流中的字节不足，此值可能小于缓冲区中的字节数。 |


### Method: read_byte() {#read_byte__4}


```
 read_byte() 
```

从流中读取一个字节，并将流中的位置前移一个字节；如果已到达流末尾，则返回 -1。

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 转换为 Int32 的无符号字节，或在流末尾时为 -1。 |


### Method: save(destination_stream) {#save_destination_stream_5}


```
 save(destination_stream) 
```

将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) 和流的 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | 用于保存数据的流。 |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_6}


```
 save(destination_stream, buffer_size) 
```

将流的全部数据保存（复制）到指定的流。使用流的 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | 用于保存数据的流。 |
| buffer_size | int | 缓冲区。 |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_7}


```
 save(destination_stream, buffer_size, length) 
```

将流的数据保存（复制）到指定的流。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | 用于保存数据的流。 |
| buffer_size | int | 缓冲区大小。默认使用 ReadWriteBytesCount 的值。 |
| length | long | 要复制的流数据长度。默认情况下，长度设置为 [SplitStreamContainer.length](/psd/python-net/aspose.psd/splitstreamcontainer/) 的值。 |

### Method: save(file_path) {#save_file_path_8}


```
 save(file_path) 
```

将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) 和流的 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 保存流数据的文件路径。 |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_9}


```
 save(file_path, buffer_size) 
```

将流的数据保存（复制）到指定的流。使用流的 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 保存流数据的文件路径。 |
| buffer_size | int | 缓冲区大小。默认使用 [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) 的值。 |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_10}


```
 save(file_path, buffer_size, length) 
```

将流的数据保存（复制）到指定的流。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 保存流数据的文件路径。 |
| buffer_size | int | 缓冲区大小。默认使用 [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) 的值。 |
| length | long | 要复制的流数据长度。默认情况下，长度设置为 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 的值。 |

### Method: seek(offset, origin) {#seek_offset_origin_11}


```
 seek(offset, origin) 
```

设置当前流中的位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| offset | long | 相对于 <paramref name=\"origin\" /> 参数的字节偏移量。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| origin | [SeekOrigin](/psd/python-net/aspose.psd/seekorigin) | SeekOrigin 类型的值，指示用于获取新位置的参考点。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| long | 当前流中的新位置。 |


### Method: to_bytes() {#to_bytes__12}


```
 to_bytes() 
```

将流数据转换为 int 数组。

**Returns**

| 类型 | 描述 |
| :- | :- |
| byte | 转换为 int 数组的流数据。 |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_13}


```
 to_bytes(position, bytes_count) 
```

将流数据转换为 int 数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 开始读取字节的位置。 |
| bytes_count | long | 要读取的字节数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| byte | 转换为 int 数组的流数据。 |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_14}


```
 write(buffer, offset, count) 
```

将一系列字节写入当前流，并根据写入的字节数前移该流中的当前位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 缓冲区 | byte | 字节数组。此方法将 <paramref name=\"count\" /> 字节从 <paramref name=\"buffer\" /> 复制到当前流。 |
| offset | int | 在 <paramref name=\"buffer\" /> 中的基于零的字节偏移量，指示从何处开始将字节复制到当前流。 |
| 计数 | int | 写入当前流的字节数。 |

### Method: write(bytes) {#write_bytes_15}


```
 write(bytes) 
```

将所有指定的字节写入流。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 字节 | byte | 要写入的字节。 |

### Method: write_byte(value) {#write_byte_value_16}


```
 write_byte(value) 
```

在流的当前位置写入一个字节，并将流中的位置前移一个字节。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | byte | 要写入流的字节。 |

### Method: write_to(stream_container) {#write_to_stream_container_17}


```
 write_to(stream_container) 
```

将包含的数据复制到另一个 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 要复制到的流容器。 |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_18}


```
 write_to(stream_container, length) 
```

将包含的数据复制到另一个 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 要复制到的流容器。 |
| 长度 | long | 要写入的字节数。 |

