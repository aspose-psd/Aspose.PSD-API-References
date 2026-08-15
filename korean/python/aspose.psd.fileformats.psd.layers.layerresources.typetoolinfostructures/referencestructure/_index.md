---
title: "ReferenceStructure 클래스"
type: docs
weight: 150
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/referencestructure/
---

**Summary:** The reference structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ReferenceStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [ReferenceStructure(key_name)](#ReferenceStructure_key_name_1) | 새 인스턴스를 초기화합니다 [ReferenceStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/referencestructure/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | 구조 키를 식별합니다. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | 구조체 배열의 복사본을 가져오거나 설정합니다. |
| 키 | int | r | 구조 키를 가져옵니다. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | 키 이름을 가져옵니다. |
| length | int | r | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)의 길이를 바이트 단위로 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | 헤더 길이를 가져옵니다. |
| [save(stream_container)](#save_stream_container_2) | 구조를 지정된 스트림 컨테이너에 저장합니다. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | 구조를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: ReferenceStructure(key_name) {#ReferenceStructure_key_name_1}


```
 ReferenceStructure(key_name) 
```

새 인스턴스를 초기화합니다 [ReferenceStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/referencestructure/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | 키 이름. |

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

