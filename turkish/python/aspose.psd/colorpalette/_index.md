---
title: "ColorPalette Sınıfı"
type: docs
weight: 800
url: /tr/python-net/aspose.psd/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) |  [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) sınıfının yeni bir örneğini başlatır ve IsCompactPalette false'dur. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) |  [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) sınıfının yeni bir örneğini başlatır. |
| [ColorPalette(entries)](#ColorPalette_entries_3) |  [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) sınıfının yeni bir örneğini başlatır ve IsCompactPalette false'dur. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) |  [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | 32-bit ARGB yapıların bir dizisini alır. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | [Color](/psd/python-net/aspose.psd/color/) yapıların bir dizisini alır. |
| entries_count | int | r | Giriş sayısını alır. |
| is_compact_palette | bool | r | Kompakt paletin kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Paleti kopyalar. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Paleti kopyalar. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | İndeks ile 32-bit ARGB palet rengini alır. |
| [get_color(index)](#get_color_index_4) | İndeks ile palet rengini alır. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | En yakın rengin indeksini alır. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | En yakın rengin indeksini alır. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

 [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) sınıfının yeni bir örneğini başlatır ve IsCompactPalette false'dur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| argb_32_entries | int | 32 bit ARGB renk paleti girişleri. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

 [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| argb_32_entries | int | 32 bit ARGB renk paleti girişleri. |
| is_compact_palette | bool | Kompakt palet olup olmadığını gösterir. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

 [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) sınıfının yeni bir örneğini başlatır ve IsCompactPalette false'dur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

 [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |
| is_compact_palette | bool | Kompakt palet olup olmadığını gösterir. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Paleti kopyalar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Renk paleti. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Yeni oluşturulan ve kopyalanan palet veya null palet geçildiyse null. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Paleti kopyalar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Renk paleti. |
| use_compact_palette | bool | Kompakt palet olup olmadığını gösterir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Yeni oluşturulan ve kopyalanan palet veya null palet geçildiyse null. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_3}


```
 get_argb_32_color(index) 
```

İndeks ile 32-bit ARGB palet rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| indeks | int | 32-bit ARGB palet renk indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | <paramref name="index" /> tarafından belirtilen renk paleti girdisi. |


### Method: get_color(index) {#get_color_index_4}


```
 get_color(index) 
```

İndeks ile palet rengini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| indeks | int | Palet renk indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | <paramref name="index" /> tarafından belirtilen renk paleti girdisi. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_5}


```
 get_nearest_color_index(argb_32_color) 
```

En yakın rengin indeksini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| argb_32_color | int | 32-bit ARGB rengi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | En yakın rengin indeksi. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_6}


```
 get_nearest_color_index(color) 
```

En yakın rengin indeksini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | En yakın rengin indeksi. |


