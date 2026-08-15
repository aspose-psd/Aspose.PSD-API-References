---
title: "ColorPaletteHelper-klasse"
type: docs
weight: 810
url: /nl/python-net/aspose.psd/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPaletteHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Maakt het 4-bits kleurenpalet. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Maakt het 4-bits grijswaardenpalet. |
| [create_8_bit()](#create_8_bit__3) | Maakt het 8-bits kleurenpalet. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Maakt het 8-bits grijswaardenpalet. |
| [create_monochrome()](#create_monochrome__5) | Maakt een monochroom kleurenpalet dat slechts 2 kleuren bevat. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_6) | Haalt het kleurenpalet op uit een rasterafbeelding (paletiseert afbeelding) als de afbeelding er geen heeft. Als er al een palet bestaat, wordt dat in plaats van berekeningen gebruikt. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7) | Haalt het kleurenpalet op uit een rasterafbeelding (paletiseert afbeelding) als de afbeelding er geen heeft. Als er al een palet bestaat, wordt dat in plaats van berekeningen gebruikt. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_8) | Haalt het kleurenpalet op uit een rasterafbeelding (paletiseert afbeelding) als de afbeelding er geen heeft. Als er al een palet bestaat, wordt dat in plaats van berekeningen gebruikt. |
| [get_downscale_palette(image)](#get_downscale_palette_image_9) | Haal 256-kleurenpalet op, samengesteld uit de hogere bits van de oorspronkelijke afbeeldingskleurwaarden. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_10) | Haal uniform 256-kleurenpalet op. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_11) | Bepaalt of het opgegeven palet transparante kleuren heeft. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Maakt het 4-bits kleurenpalet.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het 4-bits kleurenpalet. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Maakt het 4-bits grijswaardenpalet.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| min_is_white | bool | als ingesteld op <c>true</c> start het palet met witte kleur, anders start het met zwarte kleur. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het 4‑bit grijstintenpalet. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Maakt het 8-bits kleurenpalet.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het 8‑bit kleurenpalet. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Maakt het 8-bits grijswaardenpalet.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| min_is_white | bool | als ingesteld op <c>true</c> start het palet met witte kleur, anders start het met zwarte kleur. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het 8‑bit grijstintenpalet. |


### Method: create_monochrome()  [static] {#create_monochrome__5}


```
 create_monochrome() 
```

Maakt een monochroom kleurenpalet dat slechts 2 kleuren bevat.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Kleurenpalet voor monochrome afbeeldingen. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_6}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Haalt het kleurenpalet op uit een rasterafbeelding (paletiseert afbeelding) als de afbeelding er geen heeft. Als er al een palet bestaat, wordt dat in plaats van berekeningen gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | De rasterafbeelding. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De grenzen van de doelafbeelding. |
| entries_count | int | Het gewenste aantal items. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het kleurenpalet dat begint met de meest voorkomende kleuren van de <paramref name="image" /> en <paramref name="entriesCount" /> items bevat. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Haalt het kleurenpalet op uit een rasterafbeelding (paletiseert afbeelding) als de afbeelding er geen heeft. Als er al een palet bestaat, wordt dat in plaats van berekeningen gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | De rasterafbeelding. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De grenzen van de doelafbeelding. |
| entries_count | int | Het gewenste aantal items. |
| use_image_palette | bool | Indien ingesteld, zal het zijn eigen afbeeldingspalet gebruiken indien beschikbaar. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het kleurenpalet dat begint met de meest voorkomende kleuren van de <paramref name="image" /> en <paramref name="entriesCount" /> items bevat. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_8}


```
 get_close_image_palette(image, entries_count) 
```

Haalt het kleurenpalet op uit een rasterafbeelding (paletiseert afbeelding) als de afbeelding er geen heeft. Als er al een palet bestaat, wordt dat in plaats van berekeningen gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | De rasterafbeelding. |
| entries_count | int | Het gewenste aantal items. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het kleurenpalet dat begint met de meest voorkomende kleuren van de <paramref name="image" /> en <paramref name="entriesCount" /> items bevat. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_9}


```
 get_downscale_palette(image) 
```

Haal 256-kleurenpalet op, samengesteld uit de hogere bits van de oorspronkelijke afbeeldingskleurwaarden.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | De afbeelding. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | De [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_10}


```
 get_uniform_color_palette(image) 
```

Haal uniform 256-kleurenpalet op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | De afbeelding. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | De [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_11}


```
 has_transparent_colors(palette) 
```

Bepaalt of het opgegeven palet transparante kleuren heeft.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het palet. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als het opgegeven palet transparante kleuren heeft; anders <c>false</c>. |


