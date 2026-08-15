---
title: "PatternFillSettings 클래스"
type: docs
weight: 130
url: /ko/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Summary:** Pattern fill effect settings

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings

**Inheritance:** IFillSettings, IPatternFillSettings, BaseFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PatternFillSettings()](#PatternFillSettings__1) | 새로운 PatternFillSettings 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | 값을 가져오거나 설정하여 [link with layer]인지 여부를 나타냅니다. |
| 각도 | double | r/w | 각도를 가져오거나 설정합니다. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | 색상을 가져오거나 설정합니다. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | 채우기 유형 |
| horizontal_offset | int | r/w | 수평 오프셋을 가져오거나 설정합니다. |
| linked | bool | r/w | 값을 가져오거나 설정하여 이 [PatternFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/)이 연결되어 있는지 여부를 나타냅니다. |
| pattern_data | int | r/w | 패턴 데이터를 가져오거나 설정합니다. |
| pattern_height | int | r/w | 패턴의 높이를 가져오거나 설정합니다. |
| pattern_id | 문자열 | r/w | 패턴 식별자를 가져오거나 설정합니다. |
| pattern_name | 문자열 | r/w | 패턴의 이름을 가져오거나 설정합니다. |
| pattern_width | int | r/w | 패턴의 너비를 가져오거나 설정합니다. |
| point_type | 문자열 | r/w | 포인트의 유형을 가져오거나 설정합니다. |
| scale | double | r/w | scale을 가져오거나 설정합니다. |
| vertical_offset | int | r/w | 수직 오프셋을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)](#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1) | LFX2 리소스 노드를 생성합니다. |


### Constructor: PatternFillSettings() {#PatternFillSettings__1}


```
 PatternFillSettings() 
```

새로운 PatternFillSettings 클래스 인스턴스를 초기화합니다.

### Method: generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)  [static] {#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1}


```
 generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset) 
```

LFX2 리소스 노드를 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point_type | 문자열 | 포인트의 유형. |
| color | [Color](/psd/python-net/aspose.psd/color) | 색상. |
| pattern_name | 문자열 | 패턴 이름. |
| 식별자 | 문자열 | 식별자. |
| scale | double | 스케일. |
| 연결됨 | bool | 설정이 <c>true</c>인 경우 [linked]. |
| offset | [PointF](/psd/python-net/aspose.psd/pointf) | 오프셋. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | 다음의 목록: [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


