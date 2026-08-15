---
title: "ColorPaletteHelper-klass"
type: docs
weight: 810
url: /sv/python-net/aspose.psd/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPaletteHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Skapar 4-bitars färgpalett. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Skapar 4-bitars gråskalepalett. |
| [create_8_bit()](#create_8_bit__3) | Skapar 8-bitars färgpalett. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Skapar 8-bitars gråskalepalett. |
| [create_monochrome()](#create_monochrome__5) | Skapar en monokrom färgpalett som endast innehåller 2 färger. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_6) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns används den istället för att utföra beräkningar. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns används den istället för att utföra beräkningar. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_8) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns används den istället för att utföra beräkningar. |
| [get_downscale_palette(image)](#get_downscale_palette_image_9) | Hämta en 256‑färgs palett, sammansatt av de övre bitarna i de ursprungliga bildens färgvärden. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_10) | Hämta en enhetlig 256‑färgs palett. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_11) | Bestämmer om den angivna paletten har transparenta färger. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Skapar 4-bitars färgpalett.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Den 4‑bitars färgpaletten. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Skapar 4-bitars gråskalepalett.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| min_is_white | bool | Om den är satt till <c>true</c> startar paletten med vit färg, annars startar den med svart färg. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Den 4‑bitars gråskala‑paletten. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Skapar 8-bitars färgpalett.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Den 8‑bitars färgpaletten. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Skapar 8-bitars gråskalepalett.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| min_is_white | bool | Om den är satt till <c>true</c> startar paletten med vit färg, annars startar den med svart färg. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Den 8‑bitars gråskala‑paletten. |


### Method: create_monochrome()  [static] {#create_monochrome__5}


```
 create_monochrome() 
```

Skapar en monokrom färgpalett som endast innehåller 2 färger.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Färgpalett för monokroma bilder. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_6}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns används den istället för att utföra beräkningar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Rasterbilden. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Destinationens bildgränser. |
| entries_count | int | Det önskade antalet poster. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Färgpaletten som börjar med de mest frekventa färgerna från <paramref name="image" /> och innehåller <paramref name="entriesCount" /> poster. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns används den istället för att utföra beräkningar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Rasterbilden. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Destinationens bildgränser. |
| entries_count | int | Det önskade antalet poster. |
| use_image_palette | bool | Om den är satt kommer den att använda sin egen bildpalett om den finns tillgänglig. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Färgpaletten som börjar med de mest frekventa färgerna från <paramref name="image" /> och innehåller <paramref name="entriesCount" /> poster. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_8}


```
 get_close_image_palette(image, entries_count) 
```

Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns används den istället för att utföra beräkningar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Rasterbilden. |
| entries_count | int | Det önskade antalet poster. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Färgpaletten som börjar med de mest frekventa färgerna från <paramref name="image" /> och innehåller <paramref name="entriesCount" /> poster. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_9}


```
 get_downscale_palette(image) 
```

Hämta en 256‑färgs palett, sammansatt av de övre bitarna i de ursprungliga bildens färgvärden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Bilden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Den [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_10}


```
 get_uniform_color_palette(image) 
```

Hämta en enhetlig 256‑färgs palett.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Bilden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Den [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_11}


```
 has_transparent_colors(palette) 
```

Bestämmer om den angivna paletten har transparenta färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Paletten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om den angivna paletten har transparenta färger; annars <c>false</c>. |


