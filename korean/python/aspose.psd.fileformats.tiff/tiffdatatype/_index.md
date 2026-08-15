---
title: "TiffDataType 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.psd.fileformats.tiff/tiffdatatype/
---

**Summary:** The tiff data type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffDataType

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| aligned_data_size | uint | r | 태그 데이터를 저장하기에 12바이트가 충분하지 않은 경우를 대비해 추가 데이터 크기(바이트)를 가져옵니다. |
| count | uint | r | 요소 개수를 가져옵니다. |
| data_size | uint | r | 태그 데이터를 저장하기에 12바이트가 충분하지 않은 경우를 대비해 추가 데이터 크기(바이트)를 가져옵니다. |
| id | ushort | r | 태그 ID의 정수 표현을 가져옵니다. |
| is_valid | bool | r | 태그 데이터가 유효한지 여부를 나타내는 값을 가져옵니다. 유효한 태그는 보존될 수 있는 데이터를 포함합니다. 유효하지 않은 태그는 저장될 수 없습니다. |
| tag_id | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | r | 태그 ID를 가져옵니다. |
| tag_type | [TiffDataTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffdatatypes/) | r | 태그 유형을 가져옵니다. |
| 값 | object | r/w | 이 데이터 유형이 포함하는 값을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | 현재 인스턴스를 동일한 유형의 다른 객체와 비교하고, 현재 인스턴스가 정렬 순서에서 앞선, 뒤에 있거나 같은 위치에 있는지를 나타내는 정수를 반환합니다. |
| [deep_clone()](#deep_clone__2) | 이 인스턴스의 깊은 복제본을 수행합니다. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_3) | 태그 데이터를 읽습니다. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_4) | 추가 태그 데이터를 씁니다. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_5) | 태그 데이터를 씁니다. |


### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

현재 인스턴스를 동일한 유형의 다른 객체와 비교하고, 현재 인스턴스가 정렬 순서에서 앞선, 뒤에 있거나 같은 위치에 있는지를 나타내는 정수를 반환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| obj | object | 이 인스턴스와 비교할 객체입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 비교되는 객체들의 상대 순서를 나타내는 32비트 부호 있는 정수입니다. 반환값은 다음과 같은 의미를 가집니다:<br/>            값<br/>            의미<br/>            0보다 작음<br/>            이 인스턴스는 <paramref name="obj" />보다 작습니다.<br/>            0<br/>            이 인스턴스는 <paramref name="obj" />와 같습니다.<br/>            0보다 큼<br/>            이 인스턴스는 <paramref name="obj" />보다 큽니다. |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

이 인스턴스의 깊은 복제본을 수행합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | 현재 인스턴스의 깊은 복제본입니다. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_3}


```
 read_tag(data_stream, position) 
```

태그 데이터를 읽습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) | 데이터 스트림입니다. |
| position | long | 태그 위치입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | 읽은 태그입니다. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_4}


```
 write_additional_data(data_stream) 
```

추가 태그 데이터를 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | 데이터 스트림입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| long | 실제로 기록된 바이트 수입니다. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_5}


```
 write_tag(data_stream, additional_data_offset) 
```

태그 데이터를 씁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | 데이터 스트림입니다. |
| additional_data_offset | long | 추가 데이터를 기록할 오프셋입니다. |

