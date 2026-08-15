---
title: "PropertyStructure 클래스"
type: docs
weight: 130
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/propertystructure/
---

**Summary:** The property structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.PropertyStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PropertyStructure(key_name, class_id, key_id)](#PropertyStructure_key_name_class_id_key_id_1) | 새 인스턴스를 초기화합니다: [PropertyStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/propertystructure/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | 구조 키를 식별합니다. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | 클래스 ID를 가져오거나 설정합니다. |
| class_name | 문자열 | r/w | 클래스 이름을 가져오거나 설정합니다. |
| 키 | int | r | 구조 키를 가져옵니다. |
| key_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | 키 ID를 가져오거나 설정합니다. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | 키 이름을 가져옵니다. |
| length | int | r | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)의 길이를 바이트 단위로 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | 헤더 길이를 가져옵니다. |
| [save(stream_container)](#save_stream_container_2) | 구조를 지정된 스트림 컨테이너에 저장합니다. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | 구조를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: PropertyStructure(key_name, class_id, key_id) {#PropertyStructure_key_name_class_id_key_id_1}


```
 PropertyStructure(key_name, class_id, key_id) 
```

새 인스턴스를 초기화합니다: [PropertyStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/propertystructure/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | 키의 이름. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | 클래스 ID. |
| key_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | 키 ID. |

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

