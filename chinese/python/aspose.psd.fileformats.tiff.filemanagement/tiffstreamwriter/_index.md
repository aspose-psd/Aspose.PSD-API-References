---
title: "TiffStreamWriter 类"
type: docs
weight: 20
url: /zh/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Summary:** Tiff stream writer.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffStreamWriter(writer)](#TiffStreamWriter_writer_1) | 初始化一个新的 [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| position | long | 读/写 | 获取或设置流位置。 |
| sync_root | object | r | 获取一个可用于同步对同步资源访问的对象。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [write(data)](#write_data_1) | 写入指定的数据。 |
| [write(data, offset, data_length)](#write_data_offset_data_length_2) | 写入指定的数据。 |
| [write_double(data)](#write_double_data_3) | 向流写入单个 double 值。 |
| [write_double_array(data)](#write_double_array_data_4) | 向流写入 double 值数组。 |
| [write_float(data)](#write_float_data_5) | 向流写入单个 float 值。 |
| [write_float_array(data)](#write_float_array_data_6) | 向流写入 float 值数组。 |
| [write_rational(data)](#write_rational_data_7) | 向流写入单个有理数值。 |
| [write_rational_array(data)](#write_rational_array_data_8) | 向流写入无符号有理数数组。 |
| [write_s_byte(data)](#write_s_byte_data_9) | 向流写入单个有符号字节值。 |
| [write_s_byte_array(data)](#write_s_byte_array_data_10) | 向流写入有符号字节数组。 |
| [write_s_long_array(data)](#write_s_long_array_data_11) | 向流写入整数数组。 |
| [write_s_rational(data)](#write_s_rational_data_12) | 向流写入单个有符号有理数值。 |
| [write_s_rational_array(data)](#write_s_rational_array_data_13) | 向流写入有符号有理数数组。 |
| [write_s_short(data)](#write_s_short_data_14) | 向流写入单个 short 值。 |
| [write_s_short_array(data)](#write_s_short_array_data_15) | 向流写入 short 值数组。 |
| [write_slong(data)](#write_slong_data_16) | 将单个整数值写入流。 |
| [write_u_byte(data)](#write_u_byte_data_17) | 将单个字节值写入流。 |
| [write_u_long(data)](#write_u_long_data_18) | 将单个无符号整数值写入流。 |
| [write_u_long_array(data)](#write_u_long_array_data_19) | 将无符号整数数组写入流。 |
| [write_u_short(data)](#write_u_short_data_20) | 将单个无符号短整数值写入流。 |
| [write_u_short_array(data)](#write_u_short_array_data_21) | 将无符号短整数数组写入流。 |


### Constructor: TiffStreamWriter(writer) {#TiffStreamWriter_writer_1}


```
 TiffStreamWriter(writer) 
```

初始化一个新的 [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) 类实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| writer | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 流写入器。 |

### Method: write(data) {#write_data_1}


```
 write(data) 
```

写入指定的数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | byte | 要写入的数据。 |

### Method: write(data, offset, data_length) {#write_data_offset_data_length_2}


```
 write(data, offset, data_length) 
```

写入指定的数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | byte | 要写入的数据。 |
| offset | int | 数据偏移量。 |
| data_length | int | 要写入的数据长度。 |

### Method: write_double(data) {#write_double_data_3}


```
 write_double(data) 
```

向流写入单个 double 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | double | 要写入的值。 |

### Method: write_double_array(data) {#write_double_array_data_4}


```
 write_double_array(data) 
```

向流写入 double 值数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | double | 要写入的数组。 |

### Method: write_float(data) {#write_float_data_5}


```
 write_float(data) 
```

向流写入单个 float 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | float | 要写入的值。 |

### Method: write_float_array(data) {#write_float_array_data_6}


```
 write_float_array(data) 
```

向流写入 float 值数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | float | 要写入的数组。 |

### Method: write_rational(data) {#write_rational_data_7}


```
 write_rational(data) 
```

向流写入单个有理数值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| data | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 要写入的值。 |

### Method: write_rational_array(data) {#write_rational_array_data_8}


```
 write_rational_array(data) 
```

向流写入无符号有理数数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| data | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 要写入的数组。 |

### Method: write_s_byte(data) {#write_s_byte_data_9}


```
 write_s_byte(data) 
```

向流写入单个有符号字节值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | sbyte | 要写入的值。 |

### Method: write_s_byte_array(data) {#write_s_byte_array_data_10}


```
 write_s_byte_array(data) 
```

向流写入有符号字节数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | sbyte | 要写入的数组。 |

### Method: write_s_long_array(data) {#write_s_long_array_data_11}


```
 write_s_long_array(data) 
```

向流写入整数数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | int | 要写入的数组。 |

### Method: write_s_rational(data) {#write_s_rational_data_12}


```
 write_s_rational(data) 
```

向流写入单个有符号有理数值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| data | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 要写入的值。 |

### Method: write_s_rational_array(data) {#write_s_rational_array_data_13}


```
 write_s_rational_array(data) 
```

向流写入有符号有理数数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| data | [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 要写入的数组。 |

### Method: write_s_short(data) {#write_s_short_data_14}


```
 write_s_short(data) 
```

向流写入单个 short 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | short | 要写入的值。 |

### Method: write_s_short_array(data) {#write_s_short_array_data_15}


```
 write_s_short_array(data) 
```

向流写入 short 值数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | short | 要写入的数组。 |

### Method: write_slong(data) {#write_slong_data_16}


```
 write_slong(data) 
```

将单个整数值写入流。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | int | 要写入的值。 |

### Method: write_u_byte(data) {#write_u_byte_data_17}


```
 write_u_byte(data) 
```

将单个字节值写入流。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | byte | 要写入的值。 |

### Method: write_u_long(data) {#write_u_long_data_18}


```
 write_u_long(data) 
```

将单个无符号整数值写入流。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | uint | 要写入的值。 |

### Method: write_u_long_array(data) {#write_u_long_array_data_19}


```
 write_u_long_array(data) 
```

将无符号整数数组写入流。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | uint | 要写入的数组。 |

### Method: write_u_short(data) {#write_u_short_data_20}


```
 write_u_short(data) 
```

将单个无符号短整数值写入流。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | ushort | 要写入的值。 |

### Method: write_u_short_array(data) {#write_u_short_array_data_21}


```
 write_u_short_array(data) 
```

将无符号短整数数组写入流。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | ushort | 要写入的数组。 |

