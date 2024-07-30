---
title: TiffStreamWriter Class
type: docs
weight: 20
url: /python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Summary:** Tiff stream writer.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter

**Aspose.PSD Version:** 24.6.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffStreamWriter(writer)](#TiffStreamWriter_writer_1) | Initializes a new instance of the [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| position | long | r/w | Gets or sets the stream position. |
| sync_root | object | r | Gets an object that can be used to synchronize access to the synchronized resource. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [write(data)](#write_data_1) | Writes the specified data. |
| [write(data, offset, data_length)](#write_data_offset_data_length_2) | Writes the specified data. |
| [write_double(data)](#write_double_data_3) | Writes a single double value to the stream. |
| [write_double_array(data)](#write_double_array_data_4) | Writes an array of double values to the stream. |
| [write_float(data)](#write_float_data_5) | Writes a single float value to the stream. |
| [write_float_array(data)](#write_float_array_data_6) | Writes an array of float values to the stream. |
| [write_rational(data)](#write_rational_data_7) | Writes a single rational number value to the stream. |
| [write_rational_array(data)](#write_rational_array_data_8) | Writes an array of unsigned rational values to the stream. |
| [write_s_byte(data)](#write_s_byte_data_9) | Writes a single signed byte value to the stream. |
| [write_s_byte_array(data)](#write_s_byte_array_data_10) | Writes an array of signed byte values to the stream. |
| [write_s_long_array(data)](#write_s_long_array_data_11) | Writes an array of integer values to the stream. |
| [write_s_rational(data)](#write_s_rational_data_12) | Writes a single signed rational number value to the stream. |
| [write_s_rational_array(data)](#write_s_rational_array_data_13) | Writes an array of signed rational values to the stream. |
| [write_s_short(data)](#write_s_short_data_14) | Writes a single short value to the stream. |
| [write_s_short_array(data)](#write_s_short_array_data_15) | Writes an array of short values to the stream. |
| [write_slong(data)](#write_slong_data_16) | Writes a single integer value to the stream. |
| [write_u_byte(data)](#write_u_byte_data_17) | Writes a single byte value to the stream. |
| [write_u_long(data)](#write_u_long_data_18) | Writes a single unsigned integer value to the stream. |
| [write_u_long_array(data)](#write_u_long_array_data_19) | Writes an array of unsigned integer values to the stream. |
| [write_u_short(data)](#write_u_short_data_20) | Writes a single unsigned short value to the stream. |
| [write_u_short_array(data)](#write_u_short_array_data_21) | Writes an array of unsigned short values to the stream. |


### Constructor: TiffStreamWriter(writer) {#TiffStreamWriter_writer_1}


```
 TiffStreamWriter(writer) 
```

Initializes a new instance of the [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| writer | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream writer. |

### Method: write(data) {#write_data_1}


```
 write(data) 
```

Writes the specified data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The data to write. |

### Method: write(data, offset, data_length) {#write_data_offset_data_length_2}


```
 write(data, offset, data_length) 
```

Writes the specified data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The data to write. |
| offset | int | The data offset. |
| data_length | int | Length of the data to writer. |

### Method: write_double(data) {#write_double_data_3}


```
 write_double(data) 
```

Writes a single double value to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | double | The value to write. |

### Method: write_double_array(data) {#write_double_array_data_4}


```
 write_double_array(data) 
```

Writes an array of double values to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | double | The array to write. |

### Method: write_float(data) {#write_float_data_5}


```
 write_float(data) 
```

Writes a single float value to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | float | The value to write. |

### Method: write_float_array(data) {#write_float_array_data_6}


```
 write_float_array(data) 
```

Writes an array of float values to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | float | The array to write. |

### Method: write_rational(data) {#write_rational_data_7}


```
 write_rational(data) 
```

Writes a single rational number value to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | The value to write. |

### Method: write_rational_array(data) {#write_rational_array_data_8}


```
 write_rational_array(data) 
```

Writes an array of unsigned rational values to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | The array to write. |

### Method: write_s_byte(data) {#write_s_byte_data_9}


```
 write_s_byte(data) 
```

Writes a single signed byte value to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | sbyte | The value to write. |

### Method: write_s_byte_array(data) {#write_s_byte_array_data_10}


```
 write_s_byte_array(data) 
```

Writes an array of signed byte values to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | sbyte | The array to write. |

### Method: write_s_long_array(data) {#write_s_long_array_data_11}


```
 write_s_long_array(data) 
```

Writes an array of integer values to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | int | The array to write. |

### Method: write_s_rational(data) {#write_s_rational_data_12}


```
 write_s_rational(data) 
```

Writes a single signed rational number value to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | The value to write. |

### Method: write_s_rational_array(data) {#write_s_rational_array_data_13}


```
 write_s_rational_array(data) 
```

Writes an array of signed rational values to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | The array to write. |

### Method: write_s_short(data) {#write_s_short_data_14}


```
 write_s_short(data) 
```

Writes a single short value to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | short | The value to write. |

### Method: write_s_short_array(data) {#write_s_short_array_data_15}


```
 write_s_short_array(data) 
```

Writes an array of short values to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | short | The array to write. |

### Method: write_slong(data) {#write_slong_data_16}


```
 write_slong(data) 
```

Writes a single integer value to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | int | The value to write. |

### Method: write_u_byte(data) {#write_u_byte_data_17}


```
 write_u_byte(data) 
```

Writes a single byte value to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The value to write. |

### Method: write_u_long(data) {#write_u_long_data_18}


```
 write_u_long(data) 
```

Writes a single unsigned integer value to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | uint | The value to write. |

### Method: write_u_long_array(data) {#write_u_long_array_data_19}


```
 write_u_long_array(data) 
```

Writes an array of unsigned integer values to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | uint | The array to write. |

### Method: write_u_short(data) {#write_u_short_data_20}


```
 write_u_short(data) 
```

Writes a single unsigned short value to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | ushort | The value to write. |

### Method: write_u_short_array(data) {#write_u_short_array_data_21}


```
 write_u_short_array(data) 
```

Writes an array of unsigned short values to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | ushort | The array to write. |

