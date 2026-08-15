---
title: "Класс LayerStateEffects"
type: docs
weight: 30
url: /ru/python-net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Summary:** The layer state effects.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.LayerStateEffects

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| effects | [ILayerEffect[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/) | r | Получает эффекты слоя. |
| видим | bool | r/w | Получает или задаёт значение, указывающее, видим ли данный экземпляр. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_color_overlay()](#add_color_overlay__1) | Добавляет эффект цветовой наложения. |
| [add_drop_shadow()](#add_drop_shadow__2) | Добавляет эффект отбрасываемой тени. |
| [add_gradient_overlay()](#add_gradient_overlay__3) | Добавляет эффект градиентного наложения. |
| [add_inner_shadow()](#add_inner_shadow__4) | Добавляет эффект внутренней тени. |
| [add_outer_glow()](#add_outer_glow__5) | Добавляет эффект внешнего свечения. |
| [add_pattern_overlay()](#add_pattern_overlay__6) | Добавляет эффект наложения шаблона. |
| [add_stroke(fill_type)](#add_stroke_fill_type_7) | Добавляет эффект обводки. |
| clear_layer_style() | Очищает все эффекты стилей слоя. |
| [remove_effect_at(index)](#remove_effect_at_index_8) | Удаляет эффект слоя по указанному индексу. |


### Method: add_color_overlay() {#add_color_overlay__1}


```
 add_color_overlay() 
```

Добавляет эффект цветовой наложения.

**Returns**

| Тип | Описание |
| :- | :- |
| [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) | Новый экземпляр класса [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/). |


### Method: add_drop_shadow() {#add_drop_shadow__2}


```
 add_drop_shadow() 
```

Добавляет эффект отбрасываемой тени.

**Returns**

| Тип | Описание |
| :- | :- |
| [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) | Новый экземпляр класса [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/). |


### Method: add_gradient_overlay() {#add_gradient_overlay__3}


```
 add_gradient_overlay() 
```

Добавляет эффект градиентного наложения.

**Returns**

| Тип | Описание |
| :- | :- |
| [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) | Новый экземпляр класса [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/). |


### Method: add_inner_shadow() {#add_inner_shadow__4}


```
 add_inner_shadow() 
```

Добавляет эффект внутренней тени.

**Returns**

| Тип | Описание |
| :- | :- |
| [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) | Новый экземпляр класса [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/). |


### Method: add_outer_glow() {#add_outer_glow__5}


```
 add_outer_glow() 
```

Добавляет эффект внешнего свечения.

**Returns**

| Тип | Описание |
| :- | :- |
| [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) | Новый экземпляр класса [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/). |


### Method: add_pattern_overlay() {#add_pattern_overlay__6}


```
 add_pattern_overlay() 
```

Добавляет эффект наложения шаблона.

**Returns**

| Тип | Описание |
| :- | :- |
| [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) | Новый экземпляр класса [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/). |


### Method: add_stroke(fill_type) {#add_stroke_fill_type_7}


```
 add_stroke(fill_type) 
```

Добавляет эффект обводки.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype/) | Тип stroke fill. |

**Returns**

| Тип | Описание |
| :- | :- |
| [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) | Новый экземпляр класса [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/). |


### Method: remove_effect_at(index) {#remove_effect_at_index_8}


```
 remove_effect_at(index) 
```

Удаляет эффект слоя по указанному индексу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | int | Индекс эффекта слоя. |

