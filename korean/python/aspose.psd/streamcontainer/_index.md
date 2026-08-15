---
title: "StreamContainer 클래스"
type: docs
weight: 4230
url: /ko/python-net/aspose.psd/streamcontainer/
---

**Summary:** Represents stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StreamContainer

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [StreamContainer(stream)](#StreamContainer_stream_1) | 새 인스턴스를 초기화합니다 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) 클래스. |
| [StreamContainer(stream, dispose_stream)](#StreamContainer_stream_dispose_stream_2) | 새 인스턴스를 초기화합니다 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [정적] | int | r | 연속적으로 읽을 때 읽기 및 쓰기 바이트 수를 지정합니다. |
| can_read | bool | r | 스트림이 읽기를 지원하는지 여부를 나타내는 값을 가져옵니다. |
| can_seek | bool | r | 스트림이 탐색을 지원하는지 여부를 나타내는 값을 가져옵니다. |
| can_write | bool | r | 스트림이 쓰기를 지원하는지 여부를 나타내는 값을 가져옵니다. |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| is_stream_disposed_on_close | bool | r | 이 스트림이 닫힐 때 해제되는지 여부를 나타내는 값을 가져옵니다. |
| 길이 | long | r/w | 스트림 길이를 바이트 단위로 가져오거나 설정합니다. 이 값은 StreamContainer 생성자에 전달된 시작 스트림 위치에 의해 감소된 값보다 작습니다. |
| position | long | r/w | 스트림 내 현재 위치를 가져오거나 설정합니다. 이 값은 StreamContainer 생성자에 전달된 시작 스트림 위치로부터의 오프셋을 나타냅니다. |
| 스트림 | _io.BufferedRandom | r | 데이터 스트림을 가져옵니다. |
| sync_root | object | r | 동기화된 리소스에 대한 접근을 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| flush() | 이 스트림의 모든 버퍼를 비우고 버퍼링된 데이터를 기본 장치에 기록하도록 합니다. |
| [read(buffer, offset, count)](#read_buffer_offset_count_1) | 현재 스트림에서 바이트 시퀀스를 읽고 읽은 바이트 수만큼 스트림 내 위치를 이동합니다. |
| [read(bytes)](#read_bytes_2) | 지정된 바이트 버퍼를 채우기 위해 바이트를 읽습니다. |
| [read_byte()](#read_byte__3) | 스트림에서 바이트를 읽고 스트림 내 위치를 한 바이트만큼 이동합니다. 스트림 끝에 도달하면 -1을 반환합니다. |
| [save(destination_stream)](#save_destination_stream_4) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. 기본 버퍼 크기 [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/)와 스트림 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 값을 사용합니다. |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_5) | 스트림의 모든 데이터를 지정된 스트림에 저장(복사)합니다. 스트림 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 값을 사용합니다. |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_6) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. |
| [save(file_path)](#save_file_path_7) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. 기본 버퍼 크기 [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/)와 스트림 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 값을 사용합니다. |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_8) | 지정된 스트림에 스트림의 데이터를 저장(복사)합니다. 스트림 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 값을 사용합니다. |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_9) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. |
| [seek(offset, origin)](#seek_offset_origin_10) | 현재 스트림 내의 위치를 설정합니다. |
| seek_begin() | 스트림 위치를 스트림의 시작으로 설정합니다. 이 값은 StreamContainer 생성자에 전달된 시작 스트림 위치로부터의 오프셋을 나타냅니다. |
| [to_bytes()](#to_bytes__11) | 스트림 데이터를 int 배열로 변환합니다. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_12) | 스트림 데이터를 int 배열로 변환합니다. |
| [write(buffer, offset, count)](#write_buffer_offset_count_13) | 바이트 시퀀스를 현재 스트림에 쓰고, 쓰여진 바이트 수만큼 스트림 내 현재 위치를 앞으로 이동합니다. |
| [write(bytes)](#write_bytes_14) | 지정된 모든 바이트를 스트림에 씁니다. |
| [write_byte(value)](#write_byte_value_15) | 스트림의 현재 위치에 바이트를 쓰고, 스트림 내 위치를 한 바이트 앞으로 이동합니다. |
| [write_to(stream_container)](#write_to_stream_container_16) | 포함된 데이터를 다른 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/)에 복사합니다. |
| [write_to(stream_container, length)](#write_to_stream_container_length_17) | 포함된 데이터를 다른 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/)에 복사합니다. |


### Constructor: StreamContainer(stream) {#StreamContainer_stream_1}


```
 StreamContainer(stream) 
```

새 인스턴스를 초기화합니다 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 스트림. |

### Constructor: StreamContainer(stream, dispose_stream) {#StreamContainer_stream_dispose_stream_2}


```
 StreamContainer(stream, dispose_stream) 
```

새 인스턴스를 초기화합니다 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 데이터 스트림입니다. |
| dispose_stream | bool | <c>true</c> 로 설정하면 컨테이너가 해제될 때 스트림이 해제됩니다. |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_1}


```
 read(buffer, offset, count) 
```

현재 스트림에서 바이트 시퀀스를 읽고 읽은 바이트 수만큼 스트림 내 위치를 이동합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 버퍼 | byte | 바이트 배열입니다. 이 메서드가 반환될 때, 버퍼는 지정된 바이트 배열을 포함하며, <paramref name=\"offset\" />와 (<paramref name=\"offset\" /> + <paramref name=\"count\" /> - 1) 사이의 값은 현재 소스에서 읽은 바이트로 교체됩니다. |
| offset | int | 현재 스트림에서 읽은 데이터를 저장하기 시작할 <paramref name=\"buffer\" /> 내의 0 기반 바이트 오프셋입니다. |
| count | int | 현재 스트림에서 읽을 최대 바이트 수입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 버퍼에 읽힌 총 바이트 수입니다. 요청한 바이트 수보다 적을 수 있으며, 이는 현재 사용 가능한 바이트가 충분하지 않을 경우이거나, 스트림 끝에 도달하면 0(0)이 됩니다. |


### Method: read(bytes) {#read_bytes_2}


```
 read(bytes) 
```

지정된 바이트 버퍼를 채우기 위해 바이트를 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 바이트 | byte | 채울 바이트. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 읽힌 바이트 수입니다. 스트림에 충분한 바이트가 없을 경우 이 값은 버퍼의 바이트 수보다 작을 수 있습니다. |


### Method: read_byte() {#read_byte__3}


```
 read_byte() 
```

스트림에서 바이트를 읽고 스트림 내 위치를 한 바이트만큼 이동합니다. 스트림 끝에 도달하면 -1을 반환합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | Int32로 변환된 부호 없는 바이트이며, 스트림 끝에 도달하면 -1입니다. |


### Method: save(destination_stream) {#save_destination_stream_4}


```
 save(destination_stream) 
```

스트림의 데이터를 지정된 스트림에 저장(복사)합니다. 기본 버퍼 크기 [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/)와 스트림 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 값을 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | 데이터를 저장할 스트림입니다. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_5}


```
 save(destination_stream, buffer_size) 
```

스트림의 모든 데이터를 지정된 스트림에 저장(복사)합니다. 스트림 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 값을 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | 데이터를 저장할 스트림입니다. |
| buffer_size | int | 버퍼. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_6}


```
 save(destination_stream, buffer_size, length) 
```

스트림의 데이터를 지정된 스트림에 저장(복사)합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | 데이터를 저장할 스트림입니다. |
| buffer_size | int | 버퍼 크기입니다. 기본적으로 [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) 값이 사용됩니다. |
| length | long | 복사할 스트림 데이터 길이입니다. 기본적으로 길이는 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 값으로 설정됩니다. |

### Method: save(file_path) {#save_file_path_7}


```
 save(file_path) 
```

스트림의 데이터를 지정된 스트림에 저장(복사)합니다. 기본 버퍼 크기 [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/)와 스트림 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 값을 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 스트림 데이터를 저장할 파일 경로입니다. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_8}


```
 save(file_path, buffer_size) 
```

지정된 스트림에 스트림의 데이터를 저장(복사)합니다. 스트림 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 값을 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 스트림 데이터를 저장할 파일 경로입니다. |
| buffer_size | int | 버퍼 크기입니다. 기본적으로 [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) 값이 사용됩니다. |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_9}


```
 save(file_path, buffer_size, length) 
```

스트림의 데이터를 지정된 스트림에 저장(복사)합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 스트림 데이터를 저장할 파일 경로입니다. |
| buffer_size | int | 버퍼 크기입니다. 기본적으로 [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) 값이 사용됩니다. |
| length | long | 복사할 스트림 데이터 길이입니다. 기본적으로 길이는 [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 값으로 설정됩니다. |

### Method: seek(offset, origin) {#seek_offset_origin_10}


```
 seek(offset, origin) 
```

현재 스트림 내의 위치를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| offset | long | 바이트 오프셋은 <paramref name=\"origin\" /> 매개변수에 상대적입니다. 이 값은 StreamContainer 생성자에 전달된 시작 스트림 위치로부터의 오프셋을 나타냅니다. |
| origin | [SeekOrigin](/psd/python-net/aspose.psd/seekorigin) | 새 위치를 얻기 위해 사용되는 기준점을 나타내는 SeekOrigin 유형의 값입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| long | 현재 스트림 내의 새로운 위치입니다. |


### Method: to_bytes() {#to_bytes__11}


```
 to_bytes() 
```

스트림 데이터를 int 배열로 변환합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| byte | int 배열로 변환된 스트림 데이터입니다. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_12}


```
 to_bytes(position, bytes_count) 
```

스트림 데이터를 int 배열로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 바이트를 읽기 시작할 위치입니다. |
| bytes_count | long | 읽을 바이트 수입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| byte | int 배열로 변환된 스트림 데이터입니다. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_13}


```
 write(buffer, offset, count) 
```

바이트 시퀀스를 현재 스트림에 쓰고, 쓰여진 바이트 수만큼 스트림 내 현재 위치를 앞으로 이동합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 버퍼 | byte | 바이트 배열입니다. 이 메서드는 <paramref name=\"count\" /> 바이트를 <paramref name=\"buffer\" />에서 현재 스트림으로 복사합니다. |
| offset | int | <paramref name=\"buffer\" />에서 현재 스트림으로 바이트 복사를 시작할 제로 기반 바이트 오프셋입니다. |
| count | int | 현재 스트림에 기록될 바이트 수입니다. |

### Method: write(bytes) {#write_bytes_14}


```
 write(bytes) 
```

지정된 모든 바이트를 스트림에 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 바이트 | byte | 작성할 바이트입니다. |

### Method: write_byte(value) {#write_byte_value_15}


```
 write_byte(value) 
```

스트림의 현재 위치에 바이트를 쓰고, 스트림 내 위치를 한 바이트 앞으로 이동합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 값 | byte | 스트림에 기록할 바이트입니다. |

### Method: write_to(stream_container) {#write_to_stream_container_16}


```
 write_to(stream_container) 
```

포함된 데이터를 다른 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/)에 복사합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 복사할 스트림 컨테이너입니다. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_17}


```
 write_to(stream_container, length) 
```

포함된 데이터를 다른 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/)에 복사합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 복사할 스트림 컨테이너입니다. |
| 길이 | long | 작성할 바이트 수입니다. |

