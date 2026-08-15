---
title: "TiffStreamWriter 클래스"
type: docs
weight: 20
url: /ko/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Summary:** Tiff stream writer.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [TiffStreamWriter(writer)](#TiffStreamWriter_writer_1) | 새로운 [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| position | long | r/w | 스트림 위치를 가져오거나 설정합니다. |
| sync_root | object | r | 동기화된 리소스에 대한 접근을 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [write(data)](#write_data_1) | 지정된 데이터를 씁니다. |
| [write(data, offset, data_length)](#write_data_offset_data_length_2) | 지정된 데이터를 씁니다. |
| [write_double(data)](#write_double_data_3) | 스트림에 단일 double 값을 씁니다. |
| [write_double_array(data)](#write_double_array_data_4) | 스트림에 double 값 배열을 씁니다. |
| [write_float(data)](#write_float_data_5) | 스트림에 단일 float 값을 씁니다. |
| [write_float_array(data)](#write_float_array_data_6) | 스트림에 float 값 배열을 씁니다. |
| [write_rational(data)](#write_rational_data_7) | 스트림에 단일 rational 숫자 값을 씁니다. |
| [write_rational_array(data)](#write_rational_array_data_8) | 스트림에 unsigned rational 값 배열을 씁니다. |
| [write_s_byte(data)](#write_s_byte_data_9) | 스트림에 단일 signed byte 값을 씁니다. |
| [write_s_byte_array(data)](#write_s_byte_array_data_10) | 스트림에 signed byte 값 배열을 씁니다. |
| [write_s_long_array(data)](#write_s_long_array_data_11) | 스트림에 정수 값 배열을 씁니다. |
| [write_s_rational(data)](#write_s_rational_data_12) | 스트림에 단일 signed rational 숫자 값을 씁니다. |
| [write_s_rational_array(data)](#write_s_rational_array_data_13) | 스트림에 signed rational 값 배열을 씁니다. |
| [write_s_short(data)](#write_s_short_data_14) | 스트림에 단일 short 값을 씁니다. |
| [write_s_short_array(data)](#write_s_short_array_data_15) | 스트림에 short 값 배열을 씁니다. |
| [write_slong(data)](#write_slong_data_16) | 스트림에 단일 정수 값을 씁니다. |
| [write_u_byte(data)](#write_u_byte_data_17) | 스트림에 단일 바이트 값을 씁니다. |
| [write_u_long(data)](#write_u_long_data_18) | 스트림에 단일 부호 없는 정수 값을 씁니다. |
| [write_u_long_array(data)](#write_u_long_array_data_19) | 스트림에 부호 없는 정수 값 배열을 씁니다. |
| [write_u_short(data)](#write_u_short_data_20) | 스트림에 단일 부호 없는 short 값을 씁니다. |
| [write_u_short_array(data)](#write_u_short_array_data_21) | 스트림에 부호 없는 short 값 배열을 씁니다. |


### Constructor: TiffStreamWriter(writer) {#TiffStreamWriter_writer_1}


```
 TiffStreamWriter(writer) 
```

새로운 [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| writer | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 스트림 라이터. |

### Method: write(data) {#write_data_1}


```
 write(data) 
```

지정된 데이터를 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | byte | 쓰기 위한 데이터. |

### Method: write(data, offset, data_length) {#write_data_offset_data_length_2}


```
 write(data, offset, data_length) 
```

지정된 데이터를 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | byte | 쓰기 위한 데이터. |
| offset | int | 데이터 오프셋. |
| data_length | int | 작성할 데이터의 길이. |

### Method: write_double(data) {#write_double_data_3}


```
 write_double(data) 
```

스트림에 단일 double 값을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | double | 쓰기 위한 값. |

### Method: write_double_array(data) {#write_double_array_data_4}


```
 write_double_array(data) 
```

스트림에 double 값 배열을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | double | 쓰기 위한 배열. |

### Method: write_float(data) {#write_float_data_5}


```
 write_float(data) 
```

스트림에 단일 float 값을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | float | 쓰기 위한 값. |

### Method: write_float_array(data) {#write_float_array_data_6}


```
 write_float_array(data) 
```

스트림에 float 값 배열을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | float | 쓰기 위한 배열. |

### Method: write_rational(data) {#write_rational_data_7}


```
 write_rational(data) 
```

스트림에 단일 rational 숫자 값을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| data | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 쓰기 위한 값. |

### Method: write_rational_array(data) {#write_rational_array_data_8}


```
 write_rational_array(data) 
```

스트림에 unsigned rational 값 배열을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| data | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 쓰기 위한 배열. |

### Method: write_s_byte(data) {#write_s_byte_data_9}


```
 write_s_byte(data) 
```

스트림에 단일 signed byte 값을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | sbyte | 쓰기 위한 값. |

### Method: write_s_byte_array(data) {#write_s_byte_array_data_10}


```
 write_s_byte_array(data) 
```

스트림에 signed byte 값 배열을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | sbyte | 쓰기 위한 배열. |

### Method: write_s_long_array(data) {#write_s_long_array_data_11}


```
 write_s_long_array(data) 
```

스트림에 정수 값 배열을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | int | 쓰기 위한 배열. |

### Method: write_s_rational(data) {#write_s_rational_data_12}


```
 write_s_rational(data) 
```

스트림에 단일 signed rational 숫자 값을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| data | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 쓰기 위한 값. |

### Method: write_s_rational_array(data) {#write_s_rational_array_data_13}


```
 write_s_rational_array(data) 
```

스트림에 signed rational 값 배열을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| data | [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 쓰기 위한 배열. |

### Method: write_s_short(data) {#write_s_short_data_14}


```
 write_s_short(data) 
```

스트림에 단일 short 값을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | short | 쓰기 위한 값. |

### Method: write_s_short_array(data) {#write_s_short_array_data_15}


```
 write_s_short_array(data) 
```

스트림에 short 값 배열을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | short | 쓰기 위한 배열. |

### Method: write_slong(data) {#write_slong_data_16}


```
 write_slong(data) 
```

스트림에 단일 정수 값을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | int | 쓰기 위한 값. |

### Method: write_u_byte(data) {#write_u_byte_data_17}


```
 write_u_byte(data) 
```

스트림에 단일 바이트 값을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | byte | 쓰기 위한 값. |

### Method: write_u_long(data) {#write_u_long_data_18}


```
 write_u_long(data) 
```

스트림에 단일 부호 없는 정수 값을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | uint | 쓰기 위한 값. |

### Method: write_u_long_array(data) {#write_u_long_array_data_19}


```
 write_u_long_array(data) 
```

스트림에 부호 없는 정수 값 배열을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | uint | 쓰기 위한 배열. |

### Method: write_u_short(data) {#write_u_short_data_20}


```
 write_u_short(data) 
```

스트림에 단일 부호 없는 short 값을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | ushort | 쓰기 위한 값. |

### Method: write_u_short_array(data) {#write_u_short_array_data_21}


```
 write_u_short_array(data) 
```

스트림에 부호 없는 short 값 배열을 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | ushort | 쓰기 위한 배열. |

