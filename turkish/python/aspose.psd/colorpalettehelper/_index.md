---
title: "ColorPaletteHelper Sınıfı"
type: docs
weight: 810
url: /tr/python-net/aspose.psd/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPaletteHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | 4 bit renk paletini oluşturur. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | 4 bit gri tonlamalı paleti oluşturur. |
| [create_8_bit()](#create_8_bit__3) | 8 bit renk paletini oluşturur. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | 8 bit gri tonlamalı paleti oluşturur. |
| [create_monochrome()](#create_monochrome__5) | Sadece 2 renk içeren monokrom bir renk paleti oluşturur. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_6) | Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletleştirir) renk paletini alır. Palet mevcutsa, hesaplamalar yerine bu palet kullanılır. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7) | Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletleştirir) renk paletini alır. Palet mevcutsa, hesaplamalar yerine bu palet kullanılır. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_8) | Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletleştirir) renk paletini alır. Palet mevcutsa, hesaplamalar yerine bu palet kullanılır. |
| [get_downscale_palette(image)](#get_downscale_palette_image_9) | İlk görüntü renk değerlerinin üst bitlerinden oluşan 256 renk paletini al. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_10) | Tekdüzen 256 renk paletini al. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_11) | Belirtilen paletin şeffaf renkleri olup olmadığını belirler. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

4 bit renk paletini oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 4 bit renk paleti. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

4 bit gri tonlamalı paleti oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| min_is_white | bool | eğer <c>true</c> olarak ayarlanırsa palet beyaz renk ile başlar, aksi takdirde siyah renk ile başlar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 4 bitlik gri tonlamalı palet. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

8 bit renk paletini oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 8 bitlik renk paleti. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

8 bit gri tonlamalı paleti oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| min_is_white | bool | eğer <c>true</c> olarak ayarlanırsa palet beyaz renk ile başlar, aksi takdirde siyah renk ile başlar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 8 bitlik gri tonlamalı palet. |


### Method: create_monochrome()  [static] {#create_monochrome__5}


```
 create_monochrome() 
```

Sadece 2 renk içeren monokrom bir renk paleti oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Monokrom görüntüler için renk paleti. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_6}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletleştirir) renk paletini alır. Palet mevcutsa, hesaplamalar yerine bu palet kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Raster görüntü. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Hedef görüntünün sınırları. |
| entries_count | int | İstenen giriş sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | En sık kullanılan renklerle <paramref name=\"image\" /> kaynağından başlayan ve <paramref name=\"entriesCount\" /> giriş içeren renk paleti. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletleştirir) renk paletini alır. Palet mevcutsa, hesaplamalar yerine bu palet kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Raster görüntü. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Hedef görüntünün sınırları. |
| entries_count | int | İstenen giriş sayısı. |
| use_image_palette | bool | Ayarlanırsa, mevcutsa kendi görüntü paletini kullanacaktır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | En sık kullanılan renklerle <paramref name=\"image\" /> kaynağından başlayan ve <paramref name=\"entriesCount\" /> giriş içeren renk paleti. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_8}


```
 get_close_image_palette(image, entries_count) 
```

Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletleştirir) renk paletini alır. Palet mevcutsa, hesaplamalar yerine bu palet kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Raster görüntü. |
| entries_count | int | İstenen giriş sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | En sık kullanılan renklerle <paramref name=\"image\" /> kaynağından başlayan ve <paramref name=\"entriesCount\" /> giriş içeren renk paleti. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_9}


```
 get_downscale_palette(image) 
```

İlk görüntü renk değerlerinin üst bitlerinden oluşan 256 renk paletini al.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Görsel. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Bu [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_10}


```
 get_uniform_color_palette(image) 
```

Tekdüzen 256 renk paletini al.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Görsel. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Bu [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_11}


```
 has_transparent_colors(palette) 
```

Belirtilen paletin şeffaf renkleri olup olmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen paletin şeffaf renkleri varsa <c>true</c>; aksi takdirde <c>false</c>. |


