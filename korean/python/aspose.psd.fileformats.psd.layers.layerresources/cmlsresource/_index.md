---
title: "CmlsResource 클래스"
type: docs
weight: 170
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/cmlsresource/
---

**Summary:** Class CmlsResource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CmlsResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [CmlsResource(data)](#CmlsResource_data_1) | 새로운 [CmlsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cmlsresource/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| signature | int | r | 서명을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: CmlsResource(data) {#CmlsResource_data_1}


```
 CmlsResource(data) 
```

새로운 [CmlsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cmlsresource/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | byte | 리소스의 데이터. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

리소스를 지정된 스트림 컨테이너에 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 저장할 스트림 컨테이너. |
| psd_version | int | PSD 버전. |

