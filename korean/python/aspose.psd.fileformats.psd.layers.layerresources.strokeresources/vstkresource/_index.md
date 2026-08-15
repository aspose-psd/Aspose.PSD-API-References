---
title: "VstkResource 클래스"
type: docs
weight: 40
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Summary:** Resource class VstkResource. Contains information about Vector Stroke Data.<br/>            Resource should be initialized either by AssignItems method from ResourceLoader,<br/>            either by assigning values to properties of the class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VstkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [VstkResource()](#VstkResource__1) | VstkResource 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| fill_enabled | bool | r/w | Stroke fill이 활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| fill_settings | [IFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) | r/w | 스트로크의 채우기 설정을 가져오거나 설정합니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| signature | int | r | 서명을 가져옵니다. |
| stroke_enabled | bool | r/w | stroke effect가 활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| stroke_style_blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Stroke Blend 모드를 가져오거나 설정합니다. |
| stroke_style_content | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r/w | Stroke 엔터티를 가져오거나 설정합니다. 이 속성은 스트로크의 채우기 설정을 결정합니다. |
| stroke_style_line_alignment | [StrokePosition](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/) | r/w | 스트로크 스타일 라인 정렬을 가져오거나 설정합니다. |
| stroke_style_line_cap_type | [LineCapType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype) | r/w | 스트로크 스타일 라인 캡의 유형을 가져오거나 설정합니다. |
| stroke_style_line_cap_width | double | r/w | Stroke 라인 캡 너비를 가져오거나 설정합니다. |
| stroke_style_line_dash_offset | int | r/w | 스트로크 스타일 라인 대시 오프셋을 가져오거나 설정합니다. |
| stroke_style_line_dash_set | double | r/w | 라인 대시 배열을 가져오거나 설정합니다. |
| stroke_style_line_join_type | [LineJoinType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype) | r/w | Stroke 스타일 라인 조인 유형을 가져오거나 설정합니다. |
| stroke_style_line_width | double | r/w | Stroke 라인 너비를 가져오거나 설정합니다. |
| stroke_style_miter_limit | double | r/w | 스트로크 스타일 마이터 제한을 가져오거나 설정합니다. |
| stroke_style_opacity | int | r/w | Stroke 스타일 불투명도(0-100%)를 가져오거나 설정합니다. |
| stroke_style_resolution | double | r/w | Stroke style resolution을 가져오거나 설정합니다. |
| stroke_style_scale_lock | bool | r/w | Stroke style scale lock을 가져오거나 설정합니다. |
| stroke_style_stroke_adjust | bool | r/w | Stroke adjust를 가져오거나 설정합니다. |
| stroke_style_version | int | r/w | stroke style version을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: VstkResource() {#VstkResource__1}


```
 VstkResource() 
```

VstkResource 클래스의 새 인스턴스를 초기화합니다.

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

