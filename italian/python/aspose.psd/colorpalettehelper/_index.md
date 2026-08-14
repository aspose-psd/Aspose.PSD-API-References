---
title: "Classe ColorPaletteHelper"
type: docs
weight: 810
url: /it/python-net/aspose.psd/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPaletteHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Crea la tavolozza dei colori a 4 bit. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Crea la tavolozza in scala di grigi a 4 bit. |
| [create_8_bit()](#create_8_bit__3) | Crea la tavolozza dei colori a 8 bit. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Crea la tavolozza in scala di grigi a 8 bit. |
| [create_monochrome()](#create_monochrome__5) | Crea una tavolozza di colori monocromatica contenente solo 2 colori. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_6) | Ottiene la tavolozza dei colori da un'immagine raster (palletizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà usata invece di eseguire i calcoli. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7) | Ottiene la tavolozza dei colori da un'immagine raster (palletizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà usata invece di eseguire i calcoli. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_8) | Ottiene la tavolozza dei colori da un'immagine raster (palletizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà usata invece di eseguire i calcoli. |
| [get_downscale_palette(image)](#get_downscale_palette_image_9) | Ottieni una tavolozza di 256 colori, composta dai bit più alti dei valori di colore dell'immagine iniziale. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_10) | Ottieni una tavolozza uniforme di 256 colori. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_11) | Determina se la tavolozza specificata contiene colori trasparenti. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Crea la tavolozza dei colori a 4 bit.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La tavolozza dei colori a 4 bit. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Crea la tavolozza in scala di grigi a 4 bit.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| min_is_white | bool | se impostato su <c>true</c> la palette inizia con il colore bianco, altrimenti inizia con il colore nero. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette in scala di grigi a 4 bit. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Crea la tavolozza dei colori a 8 bit.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette a colori a 8 bit. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Crea la tavolozza in scala di grigi a 8 bit.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| min_is_white | bool | se impostato su <c>true</c> la palette inizia con il colore bianco, altrimenti inizia con il colore nero. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette in scala di grigi a 8 bit. |


### Method: create_monochrome()  [static] {#create_monochrome__5}


```
 create_monochrome() 
```

Crea una tavolozza di colori monocromatica contenente solo 2 colori.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palette di colori per immagini monocromatiche. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_6}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Ottiene la tavolozza dei colori da un'immagine raster (palletizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà usata invece di eseguire i calcoli.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | L'immagine raster. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | I limiti dell'immagine di destinazione. |
| entries_count | int | Il conteggio delle voci desiderate. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette di colori che inizia con i colori più frequenti dall<paramref name="image" /> e contiene <paramref name="entriesCount" /> voci. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Ottiene la tavolozza dei colori da un'immagine raster (palletizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà usata invece di eseguire i calcoli.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | L'immagine raster. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | I limiti dell'immagine di destinazione. |
| entries_count | int | Il conteggio delle voci desiderate. |
| use_image_palette | bool | Se impostato, utilizzerà la propria palette immagine se disponibile. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette di colori che inizia con i colori più frequenti dall<paramref name="image" /> e contiene <paramref name="entriesCount" /> voci. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_8}


```
 get_close_image_palette(image, entries_count) 
```

Ottiene la tavolozza dei colori da un'immagine raster (palletizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà usata invece di eseguire i calcoli.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | L'immagine raster. |
| entries_count | int | Il conteggio delle voci desiderate. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette di colori che inizia con i colori più frequenti dall<paramref name="image" /> e contiene <paramref name="entriesCount" /> voci. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_9}


```
 get_downscale_palette(image) 
```

Ottieni una tavolozza di 256 colori, composta dai bit più alti dei valori di colore dell'immagine iniziale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | L'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | La [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_10}


```
 get_uniform_color_palette(image) 
```

Ottieni una tavolozza uniforme di 256 colori.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | L'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | La [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_11}


```
 has_transparent_colors(palette) 
```

Determina se la tavolozza specificata contiene colori trasparenti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se la palette specificata ha colori trasparenti; altrimenti, <c>false</c>. |


