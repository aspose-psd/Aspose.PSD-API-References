---
title: "LayerStateEffects Klasse"
type: docs
weight: 30
url: /nl/python-net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Summary:** The layer state effects.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.LayerStateEffects

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| effects | [ILayerEffect[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/) | r | Haalt de laageffecten op. |
| is_visible | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of dit exemplaar zichtbaar is. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_color_overlay()](#add_color_overlay__1) | Voegt het kleuroverlay-effect toe. |
| [add_drop_shadow()](#add_drop_shadow__2) | Voegt het dropschaduw-effect toe. |
| [add_gradient_overlay()](#add_gradient_overlay__3) | Voegt het verloopoverlay-effect toe. |
| [add_inner_shadow()](#add_inner_shadow__4) | Voegt het interne schaduw-effect toe. |
| [add_outer_glow()](#add_outer_glow__5) | Voegt het buitenstraal-effect toe. |
| [add_pattern_overlay()](#add_pattern_overlay__6) | Voegt het patroonoverlay-effect toe. |
| [add_stroke(fill_type)](#add_stroke_fill_type_7) | Voegt het stroke-effect toe. |
| clear_layer_style() | Verwijdert alle laagstijleffecten. |
| [remove_effect_at(index)](#remove_effect_at_index_8) | Verwijdert het laag-effect op de specifieke index. |


### Method: add_color_overlay() {#add_color_overlay__1}


```
 add_color_overlay() 
```

Voegt het kleuroverlay-effect toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) | De nieuwe instantie van de [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) klasse. |


### Method: add_drop_shadow() {#add_drop_shadow__2}


```
 add_drop_shadow() 
```

Voegt het dropschaduw-effect toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) | De nieuwe instantie van de [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) klasse. |


### Method: add_gradient_overlay() {#add_gradient_overlay__3}


```
 add_gradient_overlay() 
```

Voegt het verloopoverlay-effect toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) | De nieuwe instantie van de [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) klasse. |


### Method: add_inner_shadow() {#add_inner_shadow__4}


```
 add_inner_shadow() 
```

Voegt het interne schaduw-effect toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) | De nieuwe instantie van de [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) klasse. |


### Method: add_outer_glow() {#add_outer_glow__5}


```
 add_outer_glow() 
```

Voegt het buitenstraal-effect toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) | De nieuwe instantie van de [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) klasse. |


### Method: add_pattern_overlay() {#add_pattern_overlay__6}


```
 add_pattern_overlay() 
```

Voegt het patroonoverlay-effect toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) | De nieuwe instantie van de [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) klasse. |


### Method: add_stroke(fill_type) {#add_stroke_fill_type_7}


```
 add_stroke(fill_type) 
```

Voegt het stroke-effect toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype/) | Het type stroke fill. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) | De nieuwe instantie van de [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) klasse. |


### Method: remove_effect_at(index) {#remove_effect_at_index_8}


```
 remove_effect_at(index) 
```

Verwijdert het laag-effect op de specifieke index.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | De index van het laag-effect. |

