---
title: "PsdColorPalette Sınıfı"
type: docs
weight: 1750
url: /tr/python-net/aspose.psd.fileformats.psd/psdcolorpalette/
---

**Summary:** The PSD color palette.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdColorPalette

**Inheritance:** IPsdColorPalette, IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PsdColorPalette(color_palette)](#PsdColorPalette_color_palette_1) | Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır. |
| [PsdColorPalette(color_palette, transparent_index)](#PsdColorPalette_color_palette_transparent_index_2) | Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır. |
| [PsdColorPalette(color_palette_argb_32_entries, is_compact_palette)](#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3) | Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır. |
| [PsdColorPalette(color_palette_entries)](#PsdColorPalette_color_palette_entries_4) | Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır ve IsCompactPalette yanlıştır. |
| [PsdColorPalette(color_palette_entries, is_compact_palette)](#PsdColorPalette_color_palette_entries_is_compact_palette_5) | Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır. |
| [PsdColorPalette(color_palette_entries, transparent_index)](#PsdColorPalette_color_palette_entries_transparent_index_6) | Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır ve IsCompactPalette yanlıştır. |
| [PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette)](#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7) | Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır. |
| [PsdColorPalette(raw_entries_data)](#PsdColorPalette_raw_entries_data_8) | Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır ve IsCompactPalette yanlıştır. |
| [PsdColorPalette(raw_entries_data, is_compact_palette)](#PsdColorPalette_raw_entries_data_is_compact_palette_9) | Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır. |
| [PsdColorPalette(raw_entries_data, transparent_index)](#PsdColorPalette_raw_entries_data_transparent_index_10) | Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır ve IsCompactPalette yanlıştır. |
| [PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette)](#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11) | Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | 32 bit ARGB renklerinin bir dizisini alır. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | [Color](/psd/python-net/aspose.psd/color/) yapıların bir dizisini alır. |
| entries_count | int | r | Giriş sayısını alır. |
| şeffaf_renk_var | bool | r | Şeffaf rengin mevcut olup olmadığını gösteren bir değeri alır. |
| is_compact_palette | bool | r | Paletin sıkıştırılmış olup olmadığını gösteren bir değeri alır. |
| raw_entries | byte | r | Ham renk paleti giriş verilerini alır. |
| raw_entries_count | int | r | Ham renk paleti giriş sayısını alır. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Şeffaf rengi alır. |
| transparent_index | short | r | Şeffaf rengin indeksini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Paleti kopyalar. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Paleti kopyalar. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | İndeks ile 32-bit ARGB palet rengini alır. |
| [get_color(index)](#get_color_index_4) | İndeks ile palet rengini alır. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | En yakın rengin indeksini alır. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | En yakın rengin indeksini alır. |


### Constructor: PsdColorPalette(color_palette) {#PsdColorPalette_color_palette_1}


```
 PsdColorPalette(color_palette) 
```

Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Renk paleti. |

### Constructor: PsdColorPalette(color_palette, transparent_index) {#PsdColorPalette_color_palette_transparent_index_2}


```
 PsdColorPalette(color_palette, transparent_index) 
```

Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Renk paleti. |
| transparent_index | short | Şeffaf renk indeksi. |

### Constructor: PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) {#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3}


```
 PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) 
```

Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color_palette_argb_32_entries | int | Renk paleti 32-bit ARGB girişleri. |
| is_compact_palette | bool | Kompakt palet olup olmadığını gösterir. |

### Constructor: PsdColorPalette(color_palette_entries) {#PsdColorPalette_color_palette_entries_4}


```
 PsdColorPalette(color_palette_entries) 
```

Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır ve IsCompactPalette yanlıştır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Renk paleti girişleri. |

### Constructor: PsdColorPalette(color_palette_entries, is_compact_palette) {#PsdColorPalette_color_palette_entries_is_compact_palette_5}


```
 PsdColorPalette(color_palette_entries, is_compact_palette) 
```

Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Renk paleti girişleri. |
| is_compact_palette | bool | Kompakt palet olup olmadığını gösterir. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index) {#PsdColorPalette_color_palette_entries_transparent_index_6}


```
 PsdColorPalette(color_palette_entries, transparent_index) 
```

Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır ve IsCompactPalette yanlıştır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Renk paleti girişleri. |
| transparent_index | short | Şeffaf renk indeksi. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) {#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7}


```
 PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) 
```

Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Renk paleti girişleri. |
| transparent_index | short | Şeffaf renk indeksi. |
| use_compact_palette | bool | Kompakt palet olup olmadığını gösterir. |

### Constructor: PsdColorPalette(raw_entries_data) {#PsdColorPalette_raw_entries_data_8}


```
 PsdColorPalette(raw_entries_data) 
```

Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır ve IsCompactPalette yanlıştır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| raw_entries_data | byte | Ham giriş verileri. |

### Constructor: PsdColorPalette(raw_entries_data, is_compact_palette) {#PsdColorPalette_raw_entries_data_is_compact_palette_9}


```
 PsdColorPalette(raw_entries_data, is_compact_palette) 
```

Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| raw_entries_data | byte | Ham giriş verileri. |
| is_compact_palette | bool | Kompakt palet olup olmadığını gösterir. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index) {#PsdColorPalette_raw_entries_data_transparent_index_10}


```
 PsdColorPalette(raw_entries_data, transparent_index) 
```

Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır ve IsCompactPalette yanlıştır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| raw_entries_data | byte | Ham giriş verileri. |
| transparent_index | short | Şeffaf renk indeksi. Not: indeks ham giriş indeksi değildir, bunun yerine dönüştürülmüş renk dizisi içindir. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) {#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11}


```
 PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) 
```

Yeni bir [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| raw_entries_data | byte | Ham giriş verileri. |
| transparent_index | short | Şeffaf renk indeksi. Not: indeks ham giriş indeksi değildir, bunun yerine dönüştürülmüş renk dizisi içindir. |
| use_compact_palette | bool | Kompakt palet olup olmadığını gösterir. |

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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | Yeni oluşturulan ve kopyalanan palet veya null palet geçildiyse null. |


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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | Yeni oluşturulan ve kopyalanan palet veya null palet geçildiyse null. |


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


