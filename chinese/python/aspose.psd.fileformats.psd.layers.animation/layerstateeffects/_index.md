---
title: "LayerStateEffects 类"
type: docs
weight: 30
url: /zh/python-net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Summary:** The layer state effects.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.LayerStateEffects

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| effects | [ILayerEffect[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/) | r | 获取图层效果。 |
| is_visible | bool | 读/写 | 获取或设置指示此实例是否可见的值。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_color_overlay()](#add_color_overlay__1) | 添加颜色叠加效果。 |
| [add_drop_shadow()](#add_drop_shadow__2) | 添加投影阴影效果。 |
| [add_gradient_overlay()](#add_gradient_overlay__3) | 添加渐变叠加效果。 |
| [add_inner_shadow()](#add_inner_shadow__4) | 添加内部阴影效果。 |
| [add_outer_glow()](#add_outer_glow__5) | 添加外发光效果。 |
| [add_pattern_overlay()](#add_pattern_overlay__6) | 添加图案叠加效果。 |
| [add_stroke(fill_type)](#add_stroke_fill_type_7) | 添加描边效果。 |
| clear_layer_style() | 清除所有图层样式效果。 |
| [remove_effect_at(index)](#remove_effect_at_index_8) | 移除特定索引处的图层效果。 |


### Method: add_color_overlay() {#add_color_overlay__1}


```
 add_color_overlay() 
```

添加颜色叠加效果。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) | 新的 [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) 类实例。 |


### Method: add_drop_shadow() {#add_drop_shadow__2}


```
 add_drop_shadow() 
```

添加投影阴影效果。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) | 新的 [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) 类实例。 |


### Method: add_gradient_overlay() {#add_gradient_overlay__3}


```
 add_gradient_overlay() 
```

添加渐变叠加效果。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) | 新的 [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) 类实例。 |


### Method: add_inner_shadow() {#add_inner_shadow__4}


```
 add_inner_shadow() 
```

添加内部阴影效果。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) | 新的 [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) 类实例。 |


### Method: add_outer_glow() {#add_outer_glow__5}


```
 add_outer_glow() 
```

添加外发光效果。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) | 新的 [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats/psd.layers.layereffects/outergloweffect/) 类实例。 |


### Method: add_pattern_overlay() {#add_pattern_overlay__6}


```
 add_pattern_overlay() 
```

添加图案叠加效果。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) | 新的 [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats/psd.layers.layereffects/patternoverlayeffect/) 类实例。 |


### Method: add_stroke(fill_type) {#add_stroke_fill_type_7}


```
 add_stroke(fill_type) 
```

添加描边效果。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype/) | 类型 stroke fill。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) | 新的 [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) 类的实例。 |


### Method: remove_effect_at(index) {#remove_effect_at_index_8}


```
 remove_effect_at(index) 
```

移除特定索引处的图层效果。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | int | 图层效果的索引。 |

