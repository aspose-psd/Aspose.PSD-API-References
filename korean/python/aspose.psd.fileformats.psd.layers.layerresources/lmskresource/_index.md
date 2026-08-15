---
title: "LmskResource 클래스"
type: docs
weight: 560
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---

**Summary:** The LMsk resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LmskResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [LmskResource()](#LmskResource__1) | 새로운 [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) 클래스의 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| color_component1 | ushort | r/w | 색 구성 요소 1을 가져옵니다. |
| color_component2 | ushort | r/w | 색 구성 요소 2를 가져옵니다. |
| color_component3 | ushort | r/w | 색 구성 요소 3을 가져옵니다. |
| color_component4 | ushort | r/w | 색 구성 요소 4를 가져옵니다. |
| color_space | [ColorSpace](/psd/python-net/aspose.psd.fileformats.psd.resources.enums/colorspace/) | r/w | 색 공간을 가져옵니다. |
| flag | byte | r | 플래그를 가져옵니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| opacity | short | r/w | 불투명도를 가져옵니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| signature | int | r | 서명을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: LmskResource() {#LmskResource__1}


```
 LmskResource() 
```

새로운 [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) 클래스의 인스턴스를 초기화합니다.

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

