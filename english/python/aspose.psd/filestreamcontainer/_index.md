---
title: FileStreamContainer Class
type: docs
weight: 1220
url: /python-net/aspose.psd/filestreamcontainer/
---

**Summary:** Helper for file stream processing.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FileStreamContainer

**Inheritance:** StreamContainer

**Aspose.PSD Version:** 24.5.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | Specifies read and write bytes count when reading sequentially. |
| can_read | bool | r | Gets a value indicating whether stream supports reading. |
| can_seek | bool | r | Gets a value indicating whether stream supports seeking. |
| can_write | bool | r | Gets a value indicating whether stream supports writing. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| file_path | string | r | Gets the file path. |
| is_created | bool | r | Gets a value indicating whether stream was created explicitly. |
| is_stream_disposed_on_close | bool | r | Gets a value indicating whether this stream is disposed on close. |
| is_temporal | bool | r/w | Gets or sets a value indicating whether stream is temporal. |
| length | long | r/w | Gets or sets the stream length in bytes. This value is less than the  by the starting stream position passed in the StreamContainer constructor. |
| position | long | r/w | Gets or sets the current position within the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| stream | _io.BufferedRandom | r | Gets the data stream. |
| sync_root | object | r | Gets an object that can be used to synchronize access to the synchronized resource. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_file_stream(file_location, is_temporal)](#create_file_stream_file_location_is_temporal_1) | Creates a new file stream. |
| flush() | Clears all buffers for this stream and causes any buffered data to be written to the underlying device. |
| [open_file_stream(file_location)](#open_file_stream_file_location_2) | Opens an existing file stream. If file stream does not exist the appropriate exception is thrown. |
| [read(buffer, offset, count)](#read_buffer_offset_count_3) | Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| [read(bytes)](#read_bytes_4) | Reads bytes to fill the specified bytes buffer. |
| [read_byte()](#read_byte__5) | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| [save(destination_stream)](#save_destination_stream_6) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) and stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) value. |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_7) | Saves (copies) all the stream's data to the specified stream. Uses stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) value. |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_8) | Saves (copies) the stream's data to the specified stream. |
| [save(file_path)](#save_file_path_9) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) and stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) value. |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_10) | Saves (copies) the stream's data to the specified stream. Uses stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) value. |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_11) | Saves (copies) the stream's data to the specified stream. |
| [seek(offset, origin)](#seek_offset_origin_12) | Sets the position within the current stream. |
| seek_begin() | Sets the stream position to the beginning of the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| [to_bytes()](#to_bytes__13) | Converts the stream data to the int array. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_14) | Converts the stream data to the int array. |
| [write(buffer, offset, count)](#write_buffer_offset_count_15) | Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| [write(bytes)](#write_bytes_16) | Writes all of the specified bytes to the stream. |
| [write_byte(value)](#write_byte_value_17) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| [write_to(stream_container)](#write_to_stream_container_18) | Copies the contained data to another [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_19) | Copies the contained data to another [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |


### Method: create_file_stream(file_location, is_temporal)  [static] {#create_file_stream_file_location_is_temporal_1}


```
 create_file_stream(file_location, is_temporal) 
```

Creates a new file stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_location | string | The file location. |
| is_temporal | bool | If set to <c>true</c> the file stream container is temporal. |

**Returns**

| Type | Description |
| :- | :- |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer) | The file stream container. |


### Method: open_file_stream(file_location)  [static] {#open_file_stream_file_location_2}


```
 open_file_stream(file_location) 
```

Opens an existing file stream. If file stream does not exist the appropriate exception is thrown.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_location | string | The file location. |

**Returns**

| Type | Description |
| :- | :- |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer) | The file stream container. |


### Method: read(buffer, offset, count) {#read_buffer_offset_count_3}


```
 read(buffer, offset, count) 
```

Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| buffer | byte | An array of bytes. When this method returns, the buffer contains the specified byte array with the values between <paramref name="offset" /> and (<paramref name="offset" /> + <paramref name="count" /> - 1) replaced by the bytes read from the current source. |
| offset | int | The zero-based byte offset in <paramref name="buffer" /> at which to begin storing the data read from the current stream. |
| count | int | The maximum number of bytes to be read from the current stream. |

**Returns**

| Type | Description |
| :- | :- |
| int | The total number of bytes read into the buffer. This can be less than the number of bytes requested if that many bytes are not currently available, or zero (0) if the end of the stream has been reached. |


### Method: read(bytes) {#read_bytes_4}


```
 read(bytes) 
```

Reads bytes to fill the specified bytes buffer.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bytes | byte | The bytes to fill. |

**Returns**

| Type | Description |
| :- | :- |
| int | The number of bytes read. This value can be less than the number of bytes in the buffer if there is not enough bytes in the stream. |


### Method: read_byte() {#read_byte__5}


```
 read_byte() 
```

Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream.

**Returns**

| Type | Description |
| :- | :- |
| int | The unsigned byte cast to an Int32, or -1 if at the end of the stream. |


### Method: save(destination_stream) {#save_destination_stream_6}


```
 save(destination_stream) 
```

Saves (copies) the stream's data to the specified stream. Uses default buffer size [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) and stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | The stream to save the data to. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_7}


```
 save(destination_stream, buffer_size) 
```

Saves (copies) all the stream's data to the specified stream. Uses stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | The stream to save the data to. |
| buffer_size | int | The buffer. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_8}


```
 save(destination_stream, buffer_size, length) 
```

Saves (copies) the stream's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | The stream to save the data to. |
| buffer_size | int | The buffer size. By default [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) value is used. |
| length | long | The stream data length to copy. By default the length is set to [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) value. |

### Method: save(file_path) {#save_file_path_9}


```
 save(file_path) 
```

Saves (copies) the stream's data to the specified stream. Uses default buffer size [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) and stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the stream data to. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_10}


```
 save(file_path, buffer_size) 
```

Saves (copies) the stream's data to the specified stream. Uses stream [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the stream data to. |
| buffer_size | int | The buffer size. By default [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) value is used. |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_11}


```
 save(file_path, buffer_size, length) 
```

Saves (copies) the stream's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the stream data to. |
| buffer_size | int | The buffer size. By default [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) value is used. |
| length | long | The stream data length to copy. By default the length is set to [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) value. |

### Method: seek(offset, origin) {#seek_offset_origin_12}


```
 seek(offset, origin) 
```

Sets the position within the current stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| offset | long | A byte offset relative to the <paramref name="origin" /> parameter. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| origin | [SeekOrigin](/psd/python-net/aspose.psd/seekorigin) | A value of type SeekOrigin indicating the reference point used to obtain the new position. |

**Returns**

| Type | Description |
| :- | :- |
| long | The new position within the current stream. |


### Method: to_bytes() {#to_bytes__13}


```
 to_bytes() 
```

Converts the stream data to the int array.

**Returns**

| Type | Description |
| :- | :- |
| byte | The stream data converted to the int array. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_14}


```
 to_bytes(position, bytes_count) 
```

Converts the stream data to the int array.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to start reading bytes from. |
| bytes_count | long | The bytes count to read. |

**Returns**

| Type | Description |
| :- | :- |
| byte | The stream data converted to the int array. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_15}


```
 write(buffer, offset, count) 
```

Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| buffer | byte | An array of bytes. This method copies <paramref name="count" /> bytes from <paramref name="buffer" /> to the current stream. |
| offset | int | The zero-based byte offset in <paramref name="buffer" /> at which to begin copying bytes to the current stream. |
| count | int | The number of bytes to be written to the current stream. |

### Method: write(bytes) {#write_bytes_16}


```
 write(bytes) 
```

Writes all of the specified bytes to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bytes | byte | The bytes to write. |

### Method: write_byte(value) {#write_byte_value_17}


```
 write_byte(value) 
```

Writes a byte to the current position in the stream and advances the position within the stream by one byte.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | byte | The byte to write to the stream. |

### Method: write_to(stream_container) {#write_to_stream_container_18}


```
 write_to(stream_container) 
```

Copies the contained data to another [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to copy to. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_19}


```
 write_to(stream_container, length) 
```

Copies the contained data to another [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to copy to. |
| length | long | The bytes count to write. |

