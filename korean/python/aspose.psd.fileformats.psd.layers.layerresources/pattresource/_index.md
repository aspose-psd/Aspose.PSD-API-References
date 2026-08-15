---
title: "PattResource 클래스"
type: docs
weight: 770
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Summary:** Class PattResource. Resource with pattern data

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PattResource()](#PattResource__1) | [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) 클래스의 새 인스턴스를 초기화합니다. |
| [PattResource(key, patterns)](#PattResource_key_patterns_2) | [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 8비트용 'Patt' 유형 도구 정보 키. |
| TYPE_TOOL_KEY2 [static] | int | r | 16비트용 'Pat2' 유형 도구 정보 키. |
| TYPE_TOOL_KEY3 [static] | int | r | 32비트용 'Pat3' 유형 도구 정보 키. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | r/w | 패턴 데이터를 가져오거나 설정합니다; |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| signature | int | r | 서명을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 리소스 블록 데이터를 저장합니다. |


### Constructor: PattResource() {#PattResource__1}


```
 PattResource() 
```

[PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) 클래스의 새 인스턴스를 초기화합니다.

### Constructor: PattResource(key, patterns) {#PattResource_key_patterns_2}


```
 PattResource(key, patterns) 
```

[PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 키 | int | 리소스 유형 키. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | 패턴 데이터. |

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

