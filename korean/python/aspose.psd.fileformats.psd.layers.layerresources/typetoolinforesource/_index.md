---
title: "TypeToolInfoResource 클래스"
type: docs
weight: 1000
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Summary:** The type tool information. For PSD version lower than 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfoResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [TypeToolInfoResource()](#TypeToolInfoResource__1) | 새로운 TypeToolInfoResource 클래스의 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| a_component | short | r/w | 구성 요소를 가져오거나 설정합니다. |
| b_component | short | r/w | b 구성 요소를 가져오거나 설정합니다. |
| character_count | int | r/w | 문자 수를 가져오거나 설정합니다. |
| color_space_value | short | r/w | 색 공간 값을 가져오거나 설정합니다. |
| font_version | short | r/w | 글꼴 버전을 가져오거나 설정합니다. |
| fonts | [TypeToolFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) | r/w | 글꼴을 가져오거나 설정합니다. |
| fonts_count | short | r | 글꼴 수를 가져옵니다. |
| g_component | short | r/w | g 구성 요소를 가져오거나 설정합니다. |
| horizontal_placement | int | r/w | 수평 배치를 가져오거나 설정합니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| line_count | short | r | 라인 수를 가져옵니다. |
| lines | [TypeToolLineInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) | r/w | 라인을 가져오거나 설정합니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| r_component | short | r/w | r 구성 요소를 가져오거나 설정합니다. |
| scale_factor | int | r/w | 스케일 팩터를 가져오거나 설정합니다. |
| selection_end | int | r/w | 선택 끝을 가져오거나 설정합니다. |
| selection_start | int | r/w | 선택 시작을 가져오거나 설정합니다. |
| signature | int | r | 서명을 가져옵니다. |
| styles | [TypeToolStyleInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) | r/w | 글꼴 스타일을 가져오거나 설정합니다. |
| styles_count | short | r | 스타일 수를 가져옵니다. |
| transform_matrix | double | r/w | 변환 행렬을 가져오거나 설정합니다. |
| type_value | short | r/w | 유형 값을 가져오거나 설정합니다. |
| version | short | r/w | 버전을 가져오거나 설정합니다. |
| vertical_placement | int | r/w | 수직 배치를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 지정된 스트림 컨테이너를 저장합니다. |


### Constructor: TypeToolInfoResource() {#TypeToolInfoResource__1}


```
 TypeToolInfoResource() 
```

새로운 TypeToolInfoResource 클래스의 인스턴스를 초기화합니다.

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

