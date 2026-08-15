---
title: "Lnk2Resource 클래스"
type: docs
weight: 570
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/
---

**Summary:** Defines the class which contains information about embedded files in the PSD format image.<br/>            The link resource may contain several [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instances which can be accessed by the indexer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Lnk2Resource

**Inheritance:** LinkResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [Lnk2Resource()](#Lnk2Resource__1) | 새 인스턴스를 초기화합니다 [Lnk2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| data_source_count | int | r | 인덱서를 통해 접근할 수 있는 링크 데이터 소스의 개수를 가져옵니다. |
| is_empty | bool | r | 이 링크 리소스 인스턴스가 비어 있는지 여부를 나타내는 값을 가져옵니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | PSD 전역 링크 리소스 길이를 바이트 단위로 가져옵니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| signature | int | r | 서명을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 리소스 블록 데이터를 저장합니다. |


### Constructor: Lnk2Resource() {#Lnk2Resource__1}


```
 Lnk2Resource() 
```

새 인스턴스를 초기화합니다 [Lnk2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/) 클래스.

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

리소스 블록 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 저장할 스트림 컨테이너. |
| psd_version | int | PSD 버전. |

