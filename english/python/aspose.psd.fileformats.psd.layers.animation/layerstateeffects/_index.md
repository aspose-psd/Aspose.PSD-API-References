---
title: LayerStateEffects Class
type: docs
weight: 30
url: /python-net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Summary:** The layer state effects.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.LayerStateEffects

**Aspose.PSD Version:** 24.6.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| effects | [ILayerEffect[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/) | r | Gets the layer effects. |
| is_visible | bool | r/w | Gets or sets a value indicating whether this instance is visible. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_color_overlay()](#add_color_overlay__1) | Adds the color overlay effect. |
| [add_drop_shadow()](#add_drop_shadow__2) | Adds the drop shadow effect. |
| [add_gradient_overlay()](#add_gradient_overlay__3) | Adds the gradient overlay effect. |
| [add_inner_shadow()](#add_inner_shadow__4) | Adds the inner shadow effect. |
| [add_outer_glow()](#add_outer_glow__5) | Adds the outer glow effect. |
| [add_pattern_overlay()](#add_pattern_overlay__6) | Adds the pattern overlay effect. |
| [add_stroke(fill_type)](#add_stroke_fill_type_7) | Adds the stroke effect. |
| clear_layer_style() | Clears all layer style effects. |
| [remove_effect_at(index)](#remove_effect_at_index_8) | Removes the the layer effect at the specific index. |


### Method: add_color_overlay() {#add_color_overlay__1}


```
 add_color_overlay() 
```

Adds the color overlay effect.

**Returns**

| Type | Description |
| :- | :- |
| [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) | The new instance of the [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) class. |


### Method: add_drop_shadow() {#add_drop_shadow__2}


```
 add_drop_shadow() 
```

Adds the drop shadow effect.

**Returns**

| Type | Description |
| :- | :- |
| [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) | The new instance of the [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) class. |


### Method: add_gradient_overlay() {#add_gradient_overlay__3}


```
 add_gradient_overlay() 
```

Adds the gradient overlay effect.

**Returns**

| Type | Description |
| :- | :- |
| [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) | The new instance of the [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) class. |


### Method: add_inner_shadow() {#add_inner_shadow__4}


```
 add_inner_shadow() 
```

Adds the inner shadow effect.

**Returns**

| Type | Description |
| :- | :- |
| [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) | The new instance of the [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) class. |


### Method: add_outer_glow() {#add_outer_glow__5}


```
 add_outer_glow() 
```

Adds the outer glow effect.

**Returns**

| Type | Description |
| :- | :- |
| [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) | The new instance of the [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) class. |


### Method: add_pattern_overlay() {#add_pattern_overlay__6}


```
 add_pattern_overlay() 
```

Adds the pattern overlay effect.

**Returns**

| Type | Description |
| :- | :- |
| [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) | The new instance of the [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) class. |


### Method: add_stroke(fill_type) {#add_stroke_fill_type_7}


```
 add_stroke(fill_type) 
```

Adds the stroke effect.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype/) | The type stroke fill. |

**Returns**

| Type | Description |
| :- | :- |
| [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) | The new instance of the [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) class. |


### Method: remove_effect_at(index) {#remove_effect_at_index_8}


```
 remove_effect_at(index) 
```

Removes the the layer effect at the specific index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The index of layer effect. |

