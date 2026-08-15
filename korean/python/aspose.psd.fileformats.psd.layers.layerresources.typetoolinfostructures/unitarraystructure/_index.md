---
title: "UnitArrayStructure 클래스"
type: docs
weight: 170
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/
---

**Summary:** Defines the UnitArrayStructure class that holds float values array and their measure unit.<br/>            It is used in the PSD file resources, usually by [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/).

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.UnitArrayStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [UnitArrayStructure(key_name, unit_type, values)](#UnitArrayStructure_key_name_unit_type_values_1) | 새로운 [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | 'UnFl' [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) 키를 정의합니다. |
| 키 | int | r | 이 단위 배열 구조 키를 가져옵니다. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | 키 이름을 가져옵니다. |
| length | int | r | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)의 길이를 바이트 단위로 가져옵니다. |
| unit_type | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes) | r/w | [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) 값의 측정 단위 유형을 가져오거나 설정합니다. |
| value_count | int | r | 값 개수를 가져옵니다. |
| values | double | r/w | 단위 배열 구조 값들을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | 헤더 길이를 가져옵니다. |
| [save(stream_container)](#save_stream_container_2) | 구조를 지정된 스트림 컨테이너에 저장합니다. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | 구조를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: UnitArrayStructure(key_name, unit_type, values) {#UnitArrayStructure_key_name_unit_type_values_1}


```
 UnitArrayStructure(key_name, unit_type, values) 
```

새로운 [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | 키의 이름. |
| unit_type | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes) | 단위의 유형입니다. |
| values | double | 값들입니다. |

### Method: get_header_length() {#get_header_length__1}


```
 get_header_length() 
```

헤더 길이를 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 헤더 길이 |


### Method: save(stream_container) {#save_stream_container_2}


```
 save(stream_container) 
```

구조를 지정된 스트림 컨테이너에 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |

### Method: save_without_key_name(stream_container) {#save_without_key_name_stream_container_3}


```
 save_without_key_name(stream_container) 
```

구조를 지정된 스트림 컨테이너에 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |

