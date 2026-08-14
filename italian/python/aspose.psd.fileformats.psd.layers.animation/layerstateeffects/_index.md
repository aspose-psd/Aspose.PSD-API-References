---
title: "Classe LayerStateEffects"
type: docs
weight: 30
url: /it/python-net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Summary:** The layer state effects.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.LayerStateEffects

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| effects | [ILayerEffect[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/) | r | Ottiene gli effetti del livello. |
| è_visibile | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è visibile. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_color_overlay()](#add_color_overlay__1) | Aggiunge l'effetto di sovrapposizione colore. |
| [add_drop_shadow()](#add_drop_shadow__2) | Aggiunge l'effetto ombra proiettata. |
| [add_gradient_overlay()](#add_gradient_overlay__3) | Aggiunge l'effetto di sovrapposizione gradiente. |
| [add_inner_shadow()](#add_inner_shadow__4) | Aggiunge l'effetto ombra interna. |
| [add_outer_glow()](#add_outer_glow__5) | Aggiunge l'effetto bagliore esterno. |
| [add_pattern_overlay()](#add_pattern_overlay__6) | Aggiunge l'effetto di sovrapposizione pattern. |
| [add_stroke(fill_type)](#add_stroke_fill_type_7) | Aggiunge l'effetto contorno. |
| clear_layer_style() | Cancella tutti gli effetti di stile del livello. |
| [remove_effect_at(index)](#remove_effect_at_index_8) | Rimuove l'effetto di livello all'indice specifico. |


### Method: add_color_overlay() {#add_color_overlay__1}


```
 add_color_overlay() 
```

Aggiunge l'effetto di sovrapposizione colore.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) | La nuova istanza della classe [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) |


### Method: add_drop_shadow() {#add_drop_shadow__2}


```
 add_drop_shadow() 
```

Aggiunge l'effetto ombra proiettata.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) | La nuova istanza della classe [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) |


### Method: add_gradient_overlay() {#add_gradient_overlay__3}


```
 add_gradient_overlay() 
```

Aggiunge l'effetto di sovrapposizione gradiente.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) | La nuova istanza della classe [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) |


### Method: add_inner_shadow() {#add_inner_shadow__4}


```
 add_inner_shadow() 
```

Aggiunge l'effetto ombra interna.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) | La nuova istanza della classe [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) |


### Method: add_outer_glow() {#add_outer_glow__5}


```
 add_outer_glow() 
```

Aggiunge l'effetto bagliore esterno.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) | La nuova istanza della classe [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) |


### Method: add_pattern_overlay() {#add_pattern_overlay__6}


```
 add_pattern_overlay() 
```

Aggiunge l'effetto di sovrapposizione pattern.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) | La nuova istanza della classe [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) |


### Method: add_stroke(fill_type) {#add_stroke_fill_type_7}


```
 add_stroke(fill_type) 
```

Aggiunge l'effetto contorno.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype/) | Il tipo di riempimento stroke. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) | La nuova istanza della classe [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) |


### Method: remove_effect_at(index) {#remove_effect_at_index_8}


```
 remove_effect_at(index) 
```

Rimuove l'effetto di livello all'indice specifico.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | L'indice dell'effetto di livello. |

