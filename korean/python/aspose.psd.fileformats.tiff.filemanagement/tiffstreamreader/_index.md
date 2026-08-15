---
title: "TiffStreamReader 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Summary:** The tiff stream for handling little endian tiff file format.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [TiffStreamReader(data)](#TiffStreamReader_data_1) | 새로운 [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) 클래스 인스턴스를 초기화합니다. |
| [TiffStreamReader(data, start_index)](#TiffStreamReader_data_start_index_2) | 새로운 [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) 클래스 인스턴스를 초기화합니다. |
| [TiffStreamReader(data, start_index, data_length)](#TiffStreamReader_data_start_index_data_length_3) | 새로운 [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) 클래스 인스턴스를 초기화합니다. |
| [TiffStreamReader(stream_container)](#TiffStreamReader_stream_container_4) | 새로운 [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| 길이 | long | r | 리더 길이를 가져옵니다. |
| throw_exceptions | bool | r/w | 예외가 잘못된 데이터 처리(스트림 읽기 또는 쓰기) 중에 발생하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | 스트림에서 바이트 값 배열을 읽습니다. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | 스트림에서 부호 없는 바이트 값 배열을 읽습니다. |
| [read_double(position)](#read_double_position_3) | 스트림에서 단일 double 값을 읽습니다. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | 스트림에서 double 값 배열을 읽습니다. |
| [read_float(position)](#read_float_position_5) | 스트림에서 단일 float 값을 읽습니다. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | 스트림에서 float 값 배열을 읽습니다. |
| [read_rational(position)](#read_rational_position_7) | 스트림에서 단일 유리수 값을 읽습니다. |
| [read_rational_array(position, count)](#read_rational_array_position_count_8) | 스트림에서 유리값 배열을 읽습니다. |
| [read_s_byte(position)](#read_s_byte_position_9) | 스트림에서 부호 있는 바이트 데이터를 읽습니다. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_10) | 스트림에서 부호 있는 바이트 값 배열을 읽습니다. |
| [read_s_long(position)](#read_s_long_position_11) | 스트림에서 부호 있는 정수 값을 읽습니다. |
| [read_s_long_array(position, count)](#read_s_long_array_position_count_12) | 스트림에서 부호 있는 정수 값 배열을 읽습니다. |
| [read_s_rational(position)](#read_s_rational_position_13) | 스트림에서 단일 부호 있는 유리수 값을 읽습니다. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_14) | 스트림에서 부호 있는 유리값 배열을 읽습니다. |
| [read_s_short(position)](#read_s_short_position_15) | 스트림에서 부호 있는 짧은 정수 값을 읽습니다. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_16) | 스트림에서 부호 있는 짧은 정수 값 배열을 읽습니다. |
| [read_u_long(position)](#read_u_long_position_17) | 스트림에서 부호 없는 정수 값을 읽습니다. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_18) | 스트림에서 부호 없는 정수 값 배열을 읽습니다. |
| [read_u_short(position)](#read_u_short_position_19) | 스트림에서 부호 없는 짧은 정수 값을 읽습니다. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_20) | 스트림에서 부호 없는 정수 값 배열을 읽습니다. |
| [to_stream_container(start_position)](#to_stream_container_start_position_21) | 기본 데이터를 스트림 컨테이너로 변환합니다. |


### Constructor: TiffStreamReader(data) {#TiffStreamReader_data_1}


```
 TiffStreamReader(data) 
```

새로운 [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | byte | 바이트 배열 데이터입니다. |

### Constructor: TiffStreamReader(data, start_index) {#TiffStreamReader_data_start_index_2}


```
 TiffStreamReader(data, start_index) 
```

새로운 [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | byte | 바이트 배열 데이터입니다. |
| start_index | int | <paramref name="data" />에 대한 시작 인덱스입니다. |

### Constructor: TiffStreamReader(data, start_index, data_length) {#TiffStreamReader_data_start_index_data_length_3}


```
 TiffStreamReader(data, start_index, data_length) 
```

새로운 [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | byte | 바이트 배열 데이터입니다. |
| start_index | int | <paramref name="data" />에 대한 시작 인덱스입니다. |
| data_length | int | 데이터의 길이입니다. |

### Constructor: TiffStreamReader(stream_container) {#TiffStreamReader_stream_container_4}


```
 TiffStreamReader(stream_container) 
```

새로운 [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

스트림에서 바이트 값 배열을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 배열 | byte | 채울 배열입니다. |
| array_index | int | 값을 넣기 시작할 배열 인덱스입니다. |
| position | long | 읽을 스트림 위치입니다. |
| count | long | 읽을 요소 개수입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| long | 바이트 값 배열입니다. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

스트림에서 부호 없는 바이트 값 배열을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |
| count | long | 요소 개수입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| byte | 부호 없는 바이트 값 배열. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

스트림에서 단일 double 값을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| double | 단일 double 값. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

스트림에서 double 값 배열을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |
| count | long | 요소 개수입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| double | double 값 배열. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

스트림에서 단일 float 값을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| float | 단일 float 값. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

스트림에서 float 값 배열을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |
| count | long | 요소 개수입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| float | float 값 배열. |


### Method: read_rational(position) {#read_rational_position_7}


```
 read_rational(position) 
```

스트림에서 단일 유리수 값을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 유리수. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_8}


```
 read_rational_array(position, count) 
```

스트림에서 유리값 배열을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |
| count | long | 요소 개수입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 유리수 값 배열. |


### Method: read_s_byte(position) {#read_s_byte_position_9}


```
 read_s_byte(position) 
```

스트림에서 부호 있는 바이트 데이터를 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| sbyte | 부호 있는 바이트 값. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_10}


```
 read_s_byte_array(position, count) 
```

스트림에서 부호 있는 바이트 값 배열을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |
| count | long | 요소 개수입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| sbyte | 부호 있는 바이트 값 배열. |


### Method: read_s_long(position) {#read_s_long_position_11}


```
 read_s_long(position) 
```

스트림에서 부호 있는 정수 값을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 부호 있는 정수 값. |


### Method: read_s_long_array(position, count) {#read_s_long_array_position_count_12}


```
 read_s_long_array(position, count) 
```

스트림에서 부호 있는 정수 값 배열을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |
| count | long | 요소 개수입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 부호 있는 정수 값 배열. |


### Method: read_s_rational(position) {#read_s_rational_position_13}


```
 read_s_rational(position) 
```

스트림에서 단일 부호 있는 유리수 값을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 부호 있는 유리수. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_14}


```
 read_s_rational_array(position, count) 
```

스트림에서 부호 있는 유리값 배열을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |
| count | long | 요소 개수입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 부호 있는 유리수 값 배열. |


### Method: read_s_short(position) {#read_s_short_position_15}


```
 read_s_short(position) 
```

스트림에서 부호 있는 짧은 정수 값을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| short | 부호 있는 short 값. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_16}


```
 read_s_short_array(position, count) 
```

스트림에서 부호 있는 짧은 정수 값 배열을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |
| count | long | 요소 개수입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| short | 부호 있는 short 값 배열. |


### Method: read_u_long(position) {#read_u_long_position_17}


```
 read_u_long(position) 
```

스트림에서 부호 없는 정수 값을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| uint | 부호 없는 정수 값. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_18}


```
 read_u_long_array(position, count) 
```

스트림에서 부호 없는 정수 값 배열을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |
| count | long | 요소 개수입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| uint | 부호 없는 정수 값 배열. |


### Method: read_u_short(position) {#read_u_short_position_19}


```
 read_u_short(position) 
```

스트림에서 부호 없는 짧은 정수 값을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| ushort | 부호 없는 short 값. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_20}


```
 read_u_short_array(position, count) 
```

스트림에서 부호 없는 정수 값 배열을 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| position | long | 읽을 위치입니다. |
| count | long | 요소 개수입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| ushort | 부호 없는 정수 값 배열. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_21}


```
 to_stream_container(start_position) 
```

기본 데이터를 스트림 컨테이너로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| start_position | long | 변환을 시작하는 시작 위치. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 변환된 데이터가 포함된 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |


