---
title: "LayerStateEffects Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Summary:** The layer state effects.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.LayerStateEffects

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| effects | [ILayerEffect[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/) | r | Liest die Ebeneneffekte. |
| is_visible | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_color_overlay()](#add_color_overlay__1) | Fügt den Farbüberlagerungseffekt hinzu. |
| [add_drop_shadow()](#add_drop_shadow__2) | Fügt den Drop‑Shadow‑Effekt hinzu. |
| [add_gradient_overlay()](#add_gradient_overlay__3) | Fügt den Farbverlauf-Overlay-Effekt hinzu. |
| [add_inner_shadow()](#add_inner_shadow__4) | Fügt den inneren Schatteneffekt hinzu. |
| [add_outer_glow()](#add_outer_glow__5) | Fügt den äußeren Leuchteffekt hinzu. |
| [add_pattern_overlay()](#add_pattern_overlay__6) | Fügt den Muster-Overlay-Effekt hinzu. |
| [add_stroke(fill_type)](#add_stroke_fill_type_7) | Fügt den Strich-Effekt hinzu. |
| clear_layer_style() | Löscht alle Ebenenstil-Effekte. |
| [remove_effect_at(index)](#remove_effect_at_index_8) | Entfernt den Ebeneneffekt am spezifischen Index. |


### Method: add_color_overlay() {#add_color_overlay__1}


```
 add_color_overlay() 
```

Fügt den Farbüberlagerungseffekt hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) | Die neue Instanz der Klasse [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/). |


### Method: add_drop_shadow() {#add_drop_shadow__2}


```
 add_drop_shadow() 
```

Fügt den Drop‑Shadow‑Effekt hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) | Die neue Instanz der Klasse [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/). |


### Method: add_gradient_overlay() {#add_gradient_overlay__3}


```
 add_gradient_overlay() 
```

Fügt den Farbverlauf-Overlay-Effekt hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) | Die neue Instanz der Klasse [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/). |


### Method: add_inner_shadow() {#add_inner_shadow__4}


```
 add_inner_shadow() 
```

Fügt den inneren Schatteneffekt hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) | Die neue Instanz der Klasse [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/). |


### Method: add_outer_glow() {#add_outer_glow__5}


```
 add_outer_glow() 
```

Fügt den äußeren Leuchteffekt hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) | Die neue Instanz der Klasse [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/). |


### Method: add_pattern_overlay() {#add_pattern_overlay__6}


```
 add_pattern_overlay() 
```

Fügt den Muster-Overlay-Effekt hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) | Die neue Instanz der Klasse [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/). |


### Method: add_stroke(fill_type) {#add_stroke_fill_type_7}


```
 add_stroke(fill_type) 
```

Fügt den Strich-Effekt hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype/) | Der Typ Strichfüllung. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) | Die neue Instanz der Klasse [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/). |


### Method: remove_effect_at(index) {#remove_effect_at_index_8}


```
 remove_effect_at(index) 
```

Entfernt den Ebeneneffekt am spezifischen Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Der Index des Ebeneneffekts. |

