---
title: "TiffStreamReader 类"
type: docs
weight: 10
url: /zh/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Summary:** The tiff stream for handling little endian tiff file format.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffStreamReader(data)](#TiffStreamReader_data_1) | 初始化 [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) 类的新实例。 |
| [TiffStreamReader(data, start_index)](#TiffStreamReader_data_start_index_2) | 初始化 [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) 类的新实例。 |
| [TiffStreamReader(data, start_index, data_length)](#TiffStreamReader_data_start_index_data_length_3) | 初始化 [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) 类的新实例。 |
| [TiffStreamReader(stream_container)](#TiffStreamReader_stream_container_4) | 初始化 [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| 长度 | long | r | 获取读取器长度。 |
| throw_exceptions | bool | 读/写 | 获取或设置一个值，指示在数据处理错误（读取或写入流）时是否抛出异常。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | 从流中读取字节值数组。 |
| [read_bytes(position, count)](#read_bytes_position_count_2) | 从流中读取无符号字节值数组。 |
| [read_double(position)](#read_double_position_3) | 从流中读取单个 double 值。 |
| [read_double_array(position, count)](#read_double_array_position_count_4) | 从流中读取 double 值数组。 |
| [read_float(position)](#read_float_position_5) | 从流中读取单个 float 值。 |
| [read_float_array(position, count)](#read_float_array_position_count_6) | 从流中读取 float 值数组。 |
| [read_rational(position)](#read_rational_position_7) | 从流中读取单个有理数值。 |
| [read_rational_array(position, count)](#read_rational_array_position_count_8) | 从流中读取有理值数组。 |
| [read_s_byte(position)](#read_s_byte_position_9) | 从流中读取有符号字节数据。 |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_10) | 从流中读取有符号字节值数组。 |
| [read_s_long(position)](#read_s_long_position_11) | 从流中读取有符号整数值。 |
| [read_s_long_array(position, count)](#read_s_long_array_position_count_12) | 从流中读取有符号整数值数组。 |
| [read_s_rational(position)](#read_s_rational_position_13) | 从流中读取单个有符号有理数值。 |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_14) | 从流中读取有符号有理数值数组。 |
| [read_s_short(position)](#read_s_short_position_15) | 从流中读取有符号短整数值。 |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_16) | 从流中读取有符号短整数值数组。 |
| [read_u_long(position)](#read_u_long_position_17) | 从流中读取无符号整数值。 |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_18) | 从流中读取无符号整数值数组。 |
| [read_u_short(position)](#read_u_short_position_19) | 从流中读取无符号短整数值。 |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_20) | 从流中读取无符号整数值数组。 |
| [to_stream_container(start_position)](#to_stream_container_start_position_21) | 将底层数据转换为流容器。 |


### Constructor: TiffStreamReader(data) {#TiffStreamReader_data_1}


```
 TiffStreamReader(data) 
```

初始化 [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | byte | 字节数组数据。 |

### Constructor: TiffStreamReader(data, start_index) {#TiffStreamReader_data_start_index_2}


```
 TiffStreamReader(data, start_index) 
```

初始化 [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | byte | 字节数组数据。 |
| start_index | int | 对 <paramref name="data" /> 的起始索引。 |

### Constructor: TiffStreamReader(data, start_index, data_length) {#TiffStreamReader_data_start_index_data_length_3}


```
 TiffStreamReader(data, start_index, data_length) 
```

初始化 [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | byte | 字节数组数据。 |
| start_index | int | 对 <paramref name="data" /> 的起始索引。 |
| data_length | int | 数据的长度。 |

### Constructor: TiffStreamReader(stream_container) {#TiffStreamReader_stream_container_4}


```
 TiffStreamReader(stream_container) 
```

初始化 [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 流容器。 |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

从流中读取字节值数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数组 | byte | 要填充的数组。 |
| array_index | int | 开始放置值的数组索引。 |
| position | long | 要读取的流位置。 |
| 计数 | long | 要读取的元素数量。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| long | 字节值数组。 |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

从流中读取无符号字节值数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| byte | 无符号字节值的数组。 |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

从流中读取单个 double 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| double | 单个双精度值。 |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

从流中读取 double 值数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| double | 双精度值的数组。 |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

从流中读取单个 float 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| float | 单个浮点值。 |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

从流中读取 float 值数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| float | 浮点值的数组。 |


### Method: read_rational(position) {#read_rational_position_7}


```
 read_rational(position) 
```

从流中读取单个有理数值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 有理数。 |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_8}


```
 read_rational_array(position, count) 
```

从流中读取有理值数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 有理值的数组。 |


### Method: read_s_byte(position) {#read_s_byte_position_9}


```
 read_s_byte(position) 
```

从流中读取有符号字节数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| sbyte | 有符号字节值。 |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_10}


```
 read_s_byte_array(position, count) 
```

从流中读取有符号字节值数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| sbyte | 有符号字节值的数组。 |


### Method: read_s_long(position) {#read_s_long_position_11}


```
 read_s_long(position) 
```

从流中读取有符号整数值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 有符号整数值。 |


### Method: read_s_long_array(position, count) {#read_s_long_array_position_count_12}


```
 read_s_long_array(position, count) 
```

从流中读取有符号整数值数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 有符号整数值的数组。 |


### Method: read_s_rational(position) {#read_s_rational_position_13}


```
 read_s_rational(position) 
```

从流中读取单个有符号有理数值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 有符号有理数。 |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_14}


```
 read_s_rational_array(position, count) 
```

从流中读取有符号有理数值数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 有符号有理值的数组。 |


### Method: read_s_short(position) {#read_s_short_position_15}


```
 read_s_short(position) 
```

从流中读取有符号短整数值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| short | 有符号短整数值。 |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_16}


```
 read_s_short_array(position, count) 
```

从流中读取有符号短整数值数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| short | 有符号短整数值的数组。 |


### Method: read_u_long(position) {#read_u_long_position_17}


```
 read_u_long(position) 
```

从流中读取无符号整数值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| uint | 无符号整数值。 |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_18}


```
 read_u_long_array(position, count) 
```

从流中读取无符号整数值数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| uint | 无符号整数值的数组。 |


### Method: read_u_short(position) {#read_u_short_position_19}


```
 read_u_short(position) 
```

从流中读取无符号短整数值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| ushort | 无符号短整数值。 |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_20}


```
 read_u_short_array(position, count) 
```

从流中读取无符号整数值数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| position | long | 要读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| ushort | 无符号整数值的数组。 |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_21}


```
 to_stream_container(start_position) 
```

将底层数据转换为流容器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| start_position | long | 开始转换的起始位置。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 带有转换数据的[StreamContainer](/psd/python-net/aspose.psd/streamcontainer/)。 |


