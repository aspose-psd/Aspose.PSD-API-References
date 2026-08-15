---
title: "LayerStateEffects-klass"
type: docs
weight: 30
url: /sv/python-net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Summary:** The layer state effects.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.LayerStateEffects

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| effects | [ILayerEffect[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/) | r | Hämtar lagereffekterna. |
| is_visible | bool | r/w | Hämtar eller anger ett värde som indikerar om detta objekt är synligt. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_color_overlay()](#add_color_overlay__1) | Lägger till färgöverläggseffekten. |
| [add_drop_shadow()](#add_drop_shadow__2) | Lägger till fallskuggeffekten. |
| [add_gradient_overlay()](#add_gradient_overlay__3) | Lägger till gradientöverläggseffekten. |
| [add_inner_shadow()](#add_inner_shadow__4) | Lägger till inre skuggeffekten. |
| [add_outer_glow()](#add_outer_glow__5) | Lägger till yttre glödeffekten. |
| [add_pattern_overlay()](#add_pattern_overlay__6) | Lägger till mönsteröverläggseffekten. |
| [add_stroke(fill_type)](#add_stroke_fill_type_7) | Lägger till streckeffekten. |
| clear_layer_style() | Rensar alla lagerstils-effekter. |
| [remove_effect_at(index)](#remove_effect_at_index_8) | Tar bort lagereffekten på det specifika indexet. |


### Method: add_color_overlay() {#add_color_overlay__1}


```
 add_color_overlay() 
```

Lägger till färgöverläggseffekten.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) | Den nya instansen av klassen [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/). |


### Method: add_drop_shadow() {#add_drop_shadow__2}


```
 add_drop_shadow() 
```

Lägger till fallskuggeffekten.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) | Den nya instansen av klassen [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/). |


### Method: add_gradient_overlay() {#add_gradient_overlay__3}


```
 add_gradient_overlay() 
```

Lägger till gradientöverläggseffekten.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) | Den nya instansen av klassen [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/). |


### Method: add_inner_shadow() {#add_inner_shadow__4}


```
 add_inner_shadow() 
```

Lägger till inre skuggeffekten.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) | Den nya instansen av klassen [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/). |


### Method: add_outer_glow() {#add_outer_glow__5}


```
 add_outer_glow() 
```

Lägger till yttre glödeffekten.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) | Den nya instansen av klassen [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/). |


### Method: add_pattern_overlay() {#add_pattern_overlay__6}


```
 add_pattern_overlay() 
```

Lägger till mönsteröverläggseffekten.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) | Den nya instansen av klassen [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/). |


### Method: add_stroke(fill_type) {#add_stroke_fill_type_7}


```
 add_stroke(fill_type) 
```

Lägger till streckeffekten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype/) | Strokifyllningstypen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) | Den nya instansen av klassen [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/). |


### Method: remove_effect_at(index) {#remove_effect_at_index_8}


```
 remove_effect_at(index) 
```

Tar bort lagereffekten på det specifika indexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Index för lagereffekt. |

