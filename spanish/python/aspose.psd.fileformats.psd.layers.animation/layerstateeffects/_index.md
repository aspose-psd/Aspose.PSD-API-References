---
title: "Clase LayerStateEffects"
type: docs
weight: 30
url: /es/python-net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Summary:** The layer state effects.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.LayerStateEffects

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| effects | [ILayerEffect[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/) | r | Obtiene los efectos de capa. |
| is_visible | bool | r/w | Obtiene o establece un valor que indica si esta instancia es visible. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_color_overlay()](#add_color_overlay__1) | Añade el efecto de superposición de color. |
| [add_drop_shadow()](#add_drop_shadow__2) | Agrega el efecto de sombra paralela. |
| [add_gradient_overlay()](#add_gradient_overlay__3) | Añade el efecto de superposición de degradado. |
| [add_inner_shadow()](#add_inner_shadow__4) | Agrega el efecto de sombra interna. |
| [add_outer_glow()](#add_outer_glow__5) | Agrega el efecto de resplandor externo. |
| [add_pattern_overlay()](#add_pattern_overlay__6) | Añade el efecto de superposición de patrón. |
| [add_stroke(fill_type)](#add_stroke_fill_type_7) | Agrega el efecto de trazo. |
| clear_layer_style() | Borra todos los efectos de estilo de capa. |
| [remove_effect_at(index)](#remove_effect_at_index_8) | Elimina el efecto de capa en el índice específico. |


### Method: add_color_overlay() {#add_color_overlay__1}


```
 add_color_overlay() 
```

Añade el efecto de superposición de color.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) | La nueva instancia de la clase [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/). |


### Method: add_drop_shadow() {#add_drop_shadow__2}


```
 add_drop_shadow() 
```

Agrega el efecto de sombra paralela.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) | La nueva instancia de la clase [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/). |


### Method: add_gradient_overlay() {#add_gradient_overlay__3}


```
 add_gradient_overlay() 
```

Añade el efecto de superposición de degradado.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) | La nueva instancia de la clase [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/). |


### Method: add_inner_shadow() {#add_inner_shadow__4}


```
 add_inner_shadow() 
```

Agrega el efecto de sombra interna.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) | La nueva instancia de la clase [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/). |


### Method: add_outer_glow() {#add_outer_glow__5}


```
 add_outer_glow() 
```

Agrega el efecto de resplandor externo.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) | La nueva instancia de la clase [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/). |


### Method: add_pattern_overlay() {#add_pattern_overlay__6}


```
 add_pattern_overlay() 
```

Añade el efecto de superposición de patrón.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) | La nueva instancia de la clase [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/). |


### Method: add_stroke(fill_type) {#add_stroke_fill_type_7}


```
 add_stroke(fill_type) 
```

Agrega el efecto de trazo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype/) | El tipo de relleno de trazo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) | La nueva instancia de la clase [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/). |


### Method: remove_effect_at(index) {#remove_effect_at_index_8}


```
 remove_effect_at(index) 
```

Elimina el efecto de capa en el índice específico.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | int | El índice del efecto de capa. |

