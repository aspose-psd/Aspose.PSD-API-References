---
title: "LayerStateEffects クラス"
type: docs
weight: 30
url: /ja/python-net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Summary:** The layer state effects.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.LayerStateEffects

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| effects | [ILayerEffect[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/) | r | レイヤー効果を取得します。 |
| is_visible | bool | r/w | このインスタンスが表示されているかどうかを示す値を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_color_overlay()](#add_color_overlay__1) | カラーオーバーレイ効果を追加します。 |
| [add_drop_shadow()](#add_drop_shadow__2) | ドロップシャドウ効果を追加します。 |
| [add_gradient_overlay()](#add_gradient_overlay__3) | グラデーションオーバーレイ効果を追加します。 |
| [add_inner_shadow()](#add_inner_shadow__4) | インナーシャドウ効果を追加します。 |
| [add_outer_glow()](#add_outer_glow__5) | アウトアーグロー効果を追加します。 |
| [add_pattern_overlay()](#add_pattern_overlay__6) | パターンオーバーレイ効果を追加します。 |
| [add_stroke(fill_type)](#add_stroke_fill_type_7) | ストローク効果を追加します。 |
| clear_layer_style() | すべてのレイヤースタイル効果をクリアします。 |
| [remove_effect_at(index)](#remove_effect_at_index_8) | 指定されたインデックスのレイヤー効果を削除します。 |


### Method: add_color_overlay() {#add_color_overlay__1}


```
 add_color_overlay() 
```

カラーオーバーレイ効果を追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) | 新しい [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) クラスのインスタンスです。 |


### Method: add_drop_shadow() {#add_drop_shadow__2}


```
 add_drop_shadow() 
```

ドロップシャドウ効果を追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) | 新しい [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) クラスのインスタンスです。 |


### Method: add_gradient_overlay() {#add_gradient_overlay__3}


```
 add_gradient_overlay() 
```

グラデーションオーバーレイ効果を追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) | 新しい [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) クラスのインスタンスです。 |


### Method: add_inner_shadow() {#add_inner_shadow__4}


```
 add_inner_shadow() 
```

インナーシャドウ効果を追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) | 新しい [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) クラスのインスタンスです。 |


### Method: add_outer_glow() {#add_outer_glow__5}


```
 add_outer_glow() 
```

アウトアーグロー効果を追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) | 新しい [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats/psd.layers.layereffects/outergloweffect/) クラスのインスタンスです。 |


### Method: add_pattern_overlay() {#add_pattern_overlay__6}


```
 add_pattern_overlay() 
```

パターンオーバーレイ効果を追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) | 新しい [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats/psd.layers.layereffects/patternoverlayeffect/) クラスのインスタンスです。 |


### Method: add_stroke(fill_type) {#add_stroke_fill_type_7}


```
 add_stroke(fill_type) 
```

ストローク効果を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype/) | タイプ ストローク フィルです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) | 新しい [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) クラスのインスタンスです。 |


### Method: remove_effect_at(index) {#remove_effect_at_index_8}


```
 remove_effect_at(index) 
```

指定されたインデックスのレイヤー効果を削除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| index | int | レイヤーエフェクトのインデックスです。 |

