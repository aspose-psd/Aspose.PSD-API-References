---
title: "LnsrResource 클래스"
type: docs
weight: 600
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/
---

**Summary:** Class lnsrResource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LnsrResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [LnsrResource(bytes)](#LnsrResource_bytes_1) | 새 인스턴스를 초기화합니다 [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/) 클래스.<br/>            사용자 지정 또는 알 수 없는 값 |
| [LnsrResource(lnsr_resource_type)](#LnsrResource_lnsr_resource_type_2) | 새 인스턴스를 초기화합니다 [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| 데이터 | byte | r | 원시 데이터를 가져옵니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| signature | int | r | 서명을 가져옵니다. |
| value | [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype) | r | 해당 열거형이 설명된 경우 값을 LnsrResourceType으로 가져옵니다.<br/>            그렇지 않으면 Unknown을 반환합니다 |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 지정된 스트림 컨테이너를 저장합니다. |


### Constructor: LnsrResource(bytes) {#LnsrResource_bytes_1}


```
 LnsrResource(bytes) 
```

새 인스턴스를 초기화합니다 [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/) 클래스.<br/>            사용자 지정 또는 알 수 없는 값

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 바이트 | byte | 바이트입니다. |

### Constructor: LnsrResource(lnsr_resource_type) {#LnsrResource_lnsr_resource_type_2}


```
 LnsrResource(lnsr_resource_type) 
```

새 인스턴스를 초기화합니다 [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| lnsr_resource_type | [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype) | LNSR의 유형. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

지정된 스트림 컨테이너를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |
| psd_version | int | PSD 버전. |

