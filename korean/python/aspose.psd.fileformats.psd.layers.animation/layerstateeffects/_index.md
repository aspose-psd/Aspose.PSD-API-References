---
title: "LayerStateEffects 클래스"
type: docs
weight: 30
url: /ko/python-net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Summary:** The layer state effects.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.LayerStateEffects

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| effects | [ILayerEffect[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/) | r | 레이어 효과를 가져옵니다. |
| is_visible | bool | r/w | 이 인스턴스가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_color_overlay()](#add_color_overlay__1) | 색상 오버레이 효과를 추가합니다. |
| [add_drop_shadow()](#add_drop_shadow__2) | 드롭 섀도우 효과를 추가합니다. |
| [add_gradient_overlay()](#add_gradient_overlay__3) | 그라디언트 오버레이 효과를 추가합니다. |
| [add_inner_shadow()](#add_inner_shadow__4) | 내부 섀도우 효과를 추가합니다. |
| [add_outer_glow()](#add_outer_glow__5) | 외부 글로우 효과를 추가합니다. |
| [add_pattern_overlay()](#add_pattern_overlay__6) | 패턴 오버레이 효과를 추가합니다. |
| [add_stroke(fill_type)](#add_stroke_fill_type_7) | 스트로크 효과를 추가합니다. |
| clear_layer_style() | 모든 레이어 스타일 효과를 지웁니다. |
| [remove_effect_at(index)](#remove_effect_at_index_8) | 특정 인덱스의 레이어 효과를 제거합니다. |


### Method: add_color_overlay() {#add_color_overlay__1}


```
 add_color_overlay() 
```

색상 오버레이 효과를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) | 새로운 [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) 클래스 인스턴스입니다. |


### Method: add_drop_shadow() {#add_drop_shadow__2}


```
 add_drop_shadow() 
```

드롭 섀도우 효과를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) | 새로운 [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) 클래스 인스턴스입니다. |


### Method: add_gradient_overlay() {#add_gradient_overlay__3}


```
 add_gradient_overlay() 
```

그라디언트 오버레이 효과를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) | 새로운 [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) 클래스 인스턴스입니다. |


### Method: add_inner_shadow() {#add_inner_shadow__4}


```
 add_inner_shadow() 
```

내부 섀도우 효과를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) | 새로운 [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) 클래스 인스턴스입니다. |


### Method: add_outer_glow() {#add_outer_glow__5}


```
 add_outer_glow() 
```

외부 글로우 효과를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) | 새로운 [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) 클래스 인스턴스입니다. |


### Method: add_pattern_overlay() {#add_pattern_overlay__6}


```
 add_pattern_overlay() 
```

패턴 오버레이 효과를 추가합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) | 새로운 [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) 클래스 인스턴스입니다. |


### Method: add_stroke(fill_type) {#add_stroke_fill_type_7}


```
 add_stroke(fill_type) 
```

스트로크 효과를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype/) | stroke fill 유형. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) | 새로운 [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) 클래스 인스턴스. |


### Method: remove_effect_at(index) {#remove_effect_at_index_8}


```
 remove_effect_at(index) 
```

특정 인덱스의 레이어 효과를 제거합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | int | 레이어 효과의 인덱스. |

