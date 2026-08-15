---
title: "Txt2Resource 클래스"
type: docs
weight: 970
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Summary:** Txt2 resource class

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Txt2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [Txt2Resource()](#Txt2Resource__1) | Txt2Resource 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| 데이터 | byte | r/w | 데이터를 가져오거나 설정합니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| signature | int | r | 서명을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_text_record(text, bounds)](#add_text_record_text_bounds_1) | 텍스트 레코드를 Resource에 추가하고 텍스트 레코드의 ID를 반환합니다. |
| [get_text_data()](#get_text_data__2) | 리소스 데이터에서 텍스트 레코드를 가져옵니다. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_3) | 지정된 스트림 컨테이너를 저장합니다. |


### Constructor: Txt2Resource() {#Txt2Resource__1}


```
 Txt2Resource() 
```

Txt2Resource 클래스의 새 인스턴스를 초기화합니다.

### Method: add_text_record(text, bounds) {#add_text_record_text_bounds_1}


```
 add_text_record(text, bounds) 
```

텍스트 레코드를 Resource에 추가하고 텍스트 레코드의 ID를 반환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| text | 문자열 | 레코드 텍스트. |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 경계. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 리소스에 대한 텍스트 레코드의 ID를 반환합니다. |


### Method: get_text_data() {#get_text_data__2}


```
 get_text_data() 
```

리소스 데이터에서 텍스트 레코드를 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | 텍스트 레코드 배열 |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_3}


```
 save(stream_container, psd_version) 
```

지정된 스트림 컨테이너를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |
| psd_version | int | PSD 버전. |

