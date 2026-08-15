---
title: "PtFlResource 클래스"
type: docs
weight: 860
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---

**Summary:** Class PtFlResource. Contains Pattern Fill Layer Data.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PtFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PtFlResource()](#PtFlResource__1) | 새 인스턴스를 초기화합니다 [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) 클래스. |
| [PtFlResource(pattern_name, pattern_id)](#PtFlResource_pattern_name_pattern_id_2) | 새 인스턴스를 초기화합니다 [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| align_with_layer | bool | r/w | 값을 가져오거나 설정합니다. [align with layer] 여부를 나타냅니다. |
| 각도 | double | r/w | 각도를 가져오거나 설정합니다. |
| is_linked_with_layer | bool | r/w | 이 인스턴스가 레이어와 연결되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| offset | [Point](/psd/python-net/aspose.psd/point) | r/w | 오프셋을 가져오거나 설정합니다. |
| pattern_id | 문자열 | r/w | 패턴 식별자를 가져오거나 설정합니다. |
| pattern_name | 문자열 | r/w | 패턴의 이름을 가져오거나 설정합니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| scale | double | r/w | scale을 가져오거나 설정합니다. |
| signature | int | r | 서명을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: PtFlResource() {#PtFlResource__1}


```
 PtFlResource() 
```

새 인스턴스를 초기화합니다 [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) 클래스.

### Constructor: PtFlResource(pattern_name, pattern_id) {#PtFlResource_pattern_name_pattern_id_2}


```
 PtFlResource(pattern_name, pattern_id) 
```

새 인스턴스를 초기화합니다 [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pattern_name | 문자열 | 패턴 이름. |
| pattern_id | 문자열 | 패턴 식별자. |

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

