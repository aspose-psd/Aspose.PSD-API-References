---
title: "Kelas LayerStateEffects"
type: docs
weight: 30
url: /id/python-net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---

**Summary:** The layer state effects.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.LayerStateEffects

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| effects | [ILayerEffect[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/) | r | Mendapatkan efek lapisan. |
| terlihat | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_color_overlay()](#add_color_overlay__1) | Menambahkan efek overlay warna. |
| [add_drop_shadow()](#add_drop_shadow__2) | Menambahkan efek bayangan jatuh. |
| [add_gradient_overlay()](#add_gradient_overlay__3) | Menambahkan efek overlay gradien. |
| [add_inner_shadow()](#add_inner_shadow__4) | Menambahkan efek bayangan dalam. |
| [add_outer_glow()](#add_outer_glow__5) | Menambahkan efek cahaya luar. |
| [add_pattern_overlay()](#add_pattern_overlay__6) | Menambahkan efek overlay pola. |
| [add_stroke(fill_type)](#add_stroke_fill_type_7) | Menambahkan efek goresan. |
| clear_layer_style() | Menghapus semua efek gaya lapisan. |
| [remove_effect_at(index)](#remove_effect_at_index_8) | Menghapus efek lapisan pada indeks tertentu. |


### Method: add_color_overlay() {#add_color_overlay__1}


```
 add_color_overlay() 
```

Menambahkan efek overlay warna.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) | Instansi baru dari kelas [ColorOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) |


### Method: add_drop_shadow() {#add_drop_shadow__2}


```
 add_drop_shadow() 
```

Menambahkan efek bayangan jatuh.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) | Instansi baru dari kelas [DropShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) |


### Method: add_gradient_overlay() {#add_gradient_overlay__3}


```
 add_gradient_overlay() 
```

Menambahkan efek overlay gradien.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) | Instansi baru dari kelas [GradientOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) |


### Method: add_inner_shadow() {#add_inner_shadow__4}


```
 add_inner_shadow() 
```

Menambahkan efek bayangan dalam.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) | Instansi baru dari kelas [InnerShadowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) |


### Method: add_outer_glow() {#add_outer_glow__5}


```
 add_outer_glow() 
```

Menambahkan efek cahaya luar.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) | Instansi baru dari kelas [OuterGlowEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) |


### Method: add_pattern_overlay() {#add_pattern_overlay__6}


```
 add_pattern_overlay() 
```

Menambahkan efek overlay pola.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) | Instansi baru dari kelas [PatternOverlayEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) |


### Method: add_stroke(fill_type) {#add_stroke_fill_type_7}


```
 add_stroke(fill_type) 
```

Menambahkan efek goresan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype/) | Tipe stroke fill. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) | Instansi baru dari kelas [StrokeEffect](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) |


### Method: remove_effect_at(index) {#remove_effect_at_index_8}


```
 remove_effect_at(index) 
```

Menghapus efek lapisan pada indeks tertentu.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Indeks efek lapisan. |

