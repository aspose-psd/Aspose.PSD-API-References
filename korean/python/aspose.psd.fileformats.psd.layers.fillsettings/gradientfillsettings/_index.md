---
title: "GradientFillSettings 클래스"
type: docs
weight: 50
url: /ko/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Summary:** Gradient fill effect settings.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [GradientFillSettings()](#GradientFillSettings__1) | 새 인스턴스를 초기화합니다 [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | 값을 가져오거나 설정합니다. [align with layer] 여부를 나타냅니다. |
| 각도 | double | r/w | 각도를 가져오거나 설정합니다. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | 색상을 가져오거나 설정합니다. |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | 색상 포인트를 가져오거나 설정합니다. |
| dither | bool | r/w | 값을 가져오거나 설정합니다. 이 [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/)가 디더인지 여부를 나타냅니다. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | 채우기 유형입니다. |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r | 이 그라디언트의 모드를 가져옵니다.<br/>            'Gradient Type' = 'Solid/Noise' (0/1)를 결정합니다. |
| gradient_name | 문자열 | r/w | 그라디언트 이름을 가져오거나 설정합니다. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | 그라디언트 유형을 가져오거나 설정합니다. |
| horizontal_offset | double | r/w | 수평 오프셋을 백분율로 가져오거나 설정합니다. |
| 보간 | short | r/w | 보간. 'Gradient Type' = 'Solid'일 때 부드러움을 결정합니다. 값 범위: 0-4096. |
| reverse | bool | r/w | 값을 가져오거나 설정합니다. 이 [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/)가 역방향인지 여부를 나타냅니다. |
| scale | int | r/w | scale을 가져오거나 설정합니다. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | 투명도 포인트를 가져오거나 설정합니다. |
| vertical_offset | double | r/w | 수직 오프셋을 백분율로 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_color_point()](#add_color_point__1) | 색상 포인트를 추가합니다. |
| [add_transparency_point()](#add_transparency_point__2) | 색상 포인트를 추가합니다. |
| [generate_lfx_2_resource_nodes()](#generate_lfx_2_resource_nodes__3) | LFX2 리소스 노드를 생성합니다. |
| [remove_color_point(point)](#remove_color_point_point_4) | 색상 포인트를 제거합니다. |
| [remove_transparency_point(point)](#remove_transparency_point_point_5) | 투명도 포인트를 제거합니다. |


### Constructor: GradientFillSettings() {#GradientFillSettings__1}


```
 GradientFillSettings() 
```

새 인스턴스를 초기화합니다 [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) 클래스.

### Method: add_color_point() {#add_color_point__1}


```
 add_color_point() 
```

색상 포인트를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [GradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) | 생성된 색상 포인트 |


### Method: add_transparency_point() {#add_transparency_point__2}


```
 add_transparency_point() 
```

색상 포인트를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [GradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) | 생성된 투명도 포인트 |


### Method: generate_lfx_2_resource_nodes()  [static] {#generate_lfx_2_resource_nodes__3}


```
 generate_lfx_2_resource_nodes() 
```

LFX2 리소스 노드를 생성합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| System.Collections.Generic.List<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | 생성된 [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) 목록 |


### Method: remove_color_point(point) {#remove_color_point_point_4}


```
 remove_color_point(point) 
```

색상 포인트를 제거합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | 포인트. |

### Method: remove_transparency_point(point) {#remove_transparency_point_point_5}


```
 remove_transparency_point(point) 
```

투명도 포인트를 제거합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [IGradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | 포인트. |

