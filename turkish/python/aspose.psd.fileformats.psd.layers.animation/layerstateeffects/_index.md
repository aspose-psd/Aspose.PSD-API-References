---
title: "LayerStateEffects Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Summary:** The layer state effects.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.LayerStateEffects

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| effects | [ILayerEffect[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/) | r | Katman etkilerini alır. |
| görünür | bool | r/w | Bu örneğin görünür olup olmadığını gösteren bir değeri alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_color_overlay()](#add_color_overlay__1) | Renk bindirme etkisini ekler. |
| [add_drop_shadow()](#add_drop_shadow__2) | Gölge düşürme efektini ekler. |
| [add_gradient_overlay()](#add_gradient_overlay__3) | Gradyan bindirme etkisini ekler. |
| [add_inner_shadow()](#add_inner_shadow__4) | İç gölge efektini ekler. |
| [add_outer_glow()](#add_outer_glow__5) | Dış parıltı efektini ekler. |
| [add_pattern_overlay()](#add_pattern_overlay__6) | Desen bindirme etkisini ekler. |
| [add_stroke(fill_type)](#add_stroke_fill_type_7) | Çizgi efektini ekler. |
| clear_layer_style() | Tüm katman stil etkilerini temizler. |
| [remove_effect_at(index)](#remove_effect_at_index_8) | Belirli bir indeksteki katman etkisini kaldırır. |


### Method: add_color_overlay() {#add_color_overlay__1}


```
 add_color_overlay() 
```

Renk bindirme etkisini ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) | Yeni [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) sınıfının örneği. |


### Method: add_drop_shadow() {#add_drop_shadow__2}


```
 add_drop_shadow() 
```

Gölge düşürme efektini ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) | Yeni [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) sınıfının örneği. |


### Method: add_gradient_overlay() {#add_gradient_overlay__3}


```
 add_gradient_overlay() 
```

Gradyan bindirme etkisini ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) | Yeni [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) sınıfının örneği. |


### Method: add_inner_shadow() {#add_inner_shadow__4}


```
 add_inner_shadow() 
```

İç gölge efektini ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) | Yeni [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) sınıfının örneği. |


### Method: add_outer_glow() {#add_outer_glow__5}


```
 add_outer_glow() 
```

Dış parıltı efektini ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) | Yeni [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) sınıfının örneği. |


### Method: add_pattern_overlay() {#add_pattern_overlay__6}


```
 add_pattern_overlay() 
```

Desen bindirme etkisini ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) | Yeni [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) sınıfının örneği. |


### Method: add_stroke(fill_type) {#add_stroke_fill_type_7}


```
 add_stroke(fill_type) 
```

Çizgi efektini ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype/) | stroke fill türü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) | Yeni [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) sınıfının örneği. |


### Method: remove_effect_at(index) {#remove_effect_at_index_8}


```
 remove_effect_at(index) 
```

Belirli bir indeksteki katman etkisini kaldırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| indeks | int | Katman etkisinin indeksi. |

