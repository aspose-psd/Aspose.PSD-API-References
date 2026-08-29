---
title: "Classe LayerStateEffects"
type: docs
weight: 30
url: /fr/python-net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Summary:** The layer state effects.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.LayerStateEffects

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| effects | [ILayerEffect[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/) | r | Obtient les effets de couche. |
| est_visible | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est visible. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_color_overlay()](#add_color_overlay__1) | Ajoute l'effet de superposition de couleur. |
| [add_drop_shadow()](#add_drop_shadow__2) | Ajoute l'effet d'ombre portée. |
| [add_gradient_overlay()](#add_gradient_overlay__3) | Ajoute l'effet de superposition de dégradé. |
| [add_inner_shadow()](#add_inner_shadow__4) | Ajoute l'effet d'ombre interne. |
| [add_outer_glow()](#add_outer_glow__5) | Ajoute l'effet de lueur externe. |
| [add_pattern_overlay()](#add_pattern_overlay__6) | Ajoute l'effet de superposition de motif. |
| [add_stroke(fill_type)](#add_stroke_fill_type_7) | Ajoute l'effet de contour. |
| clear_layer_style() | Efface tous les effets de style de couche. |
| [remove_effect_at(index)](#remove_effect_at_index_8) | Supprime l'effet de calque à l'index spécifique. |


### Method: add_color_overlay() {#add_color_overlay__1}


```
 add_color_overlay() 
```

Ajoute l'effet de superposition de couleur.

**Returns**

| Type | Description |
| :- | :- |
| [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) | Nouvelle instance de la classe [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/). |


### Method: add_drop_shadow() {#add_drop_shadow__2}


```
 add_drop_shadow() 
```

Ajoute l'effet d'ombre portée.

**Returns**

| Type | Description |
| :- | :- |
| [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) | Nouvelle instance de la classe [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/). |


### Method: add_gradient_overlay() {#add_gradient_overlay__3}


```
 add_gradient_overlay() 
```

Ajoute l'effet de superposition de dégradé.

**Returns**

| Type | Description |
| :- | :- |
| [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) | Nouvelle instance de la classe [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/). |


### Method: add_inner_shadow() {#add_inner_shadow__4}


```
 add_inner_shadow() 
```

Ajoute l'effet d'ombre interne.

**Returns**

| Type | Description |
| :- | :- |
| [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) | Nouvelle instance de la classe [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/). |


### Method: add_outer_glow() {#add_outer_glow__5}


```
 add_outer_glow() 
```

Ajoute l'effet de lueur externe.

**Returns**

| Type | Description |
| :- | :- |
| [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) | Nouvelle instance de la classe [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/). |


### Method: add_pattern_overlay() {#add_pattern_overlay__6}


```
 add_pattern_overlay() 
```

Ajoute l'effet de superposition de motif.

**Returns**

| Type | Description |
| :- | :- |
| [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) | Nouvelle instance de la classe [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/). |


### Method: add_stroke(fill_type) {#add_stroke_fill_type_7}


```
 add_stroke(fill_type) 
```

Ajoute l'effet de contour.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype/) | Le type remplissage du trait. |

**Returns**

| Type | Description |
| :- | :- |
| [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) | Nouvelle instance de la classe [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/). |


### Method: remove_effect_at(index) {#remove_effect_at_index_8}


```
 remove_effect_at(index) 
```

Supprime l'effet de calque à l'index spécifique.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index de l'effet de calque. |

