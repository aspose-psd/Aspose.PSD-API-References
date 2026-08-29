---
title: "Classe ColorPaletteHelper"
type: docs
weight: 810
url: /fr/python-net/aspose.psd/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPaletteHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Crée la palette de couleurs 4 bits. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Crée la palette de niveaux de gris 4 bits. |
| [create_8_bit()](#create_8_bit__3) | Crée la palette de couleurs 8 bits. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Crée la palette de niveaux de gris 8 bits. |
| [create_monochrome()](#create_monochrome__5) | Crée une palette de couleurs monochrome contenant uniquement 2 couleurs. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_6) | Obtient la palette de couleurs à partir d'une image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7) | Obtient la palette de couleurs à partir d'une image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_8) | Obtient la palette de couleurs à partir d'une image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs. |
| [get_downscale_palette(image)](#get_downscale_palette_image_9) | Obtenir une palette de 256 couleurs, composée des bits supérieurs des valeurs de couleur de l'image initiale. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_10) | Obtenir une palette uniforme de 256 couleurs. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_11) | Détermine si la palette spécifiée contient des couleurs transparentes. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Crée la palette de couleurs 4 bits.

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette de couleurs 4 bits. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Crée la palette de niveaux de gris 4 bits.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| min_is_white | bool | si défini sur <c>true</c> la palette commence avec la couleur blanche, sinon elle commence avec la couleur noire. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette de niveaux de gris 4 bits. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Crée la palette de couleurs 8 bits.

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette de couleur 8 bits. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Crée la palette de niveaux de gris 8 bits.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| min_is_white | bool | si défini sur <c>true</c> la palette commence avec la couleur blanche, sinon elle commence avec la couleur noire. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette de niveaux de gris 8 bits. |


### Method: create_monochrome()  [static] {#create_monochrome__5}


```
 create_monochrome() 
```

Crée une palette de couleurs monochrome contenant uniquement 2 couleurs.

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palette de couleur pour images monochromes. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_6}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Obtient la palette de couleurs à partir d'une image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | L'image raster. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Les limites de l'image de destination. |
| entries_count | int | Le nombre d'entrées souhaité. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette de couleur qui commence avec les couleurs les plus fréquentes de <paramref name=\"image\" /> et contient <paramref name=\"entriesCount\" /> entrées. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Obtient la palette de couleurs à partir d'une image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | L'image raster. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Les limites de l'image de destination. |
| entries_count | int | Le nombre d'entrées souhaité. |
| use_image_palette | bool | Si défini, il utilisera sa propre palette d'image si disponible. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette de couleur qui commence avec les couleurs les plus fréquentes de <paramref name=\"image\" /> et contient <paramref name=\"entriesCount\" /> entrées. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_8}


```
 get_close_image_palette(image, entries_count) 
```

Obtient la palette de couleurs à partir d'une image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | L'image raster. |
| entries_count | int | Le nombre d'entrées souhaité. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette de couleur qui commence avec les couleurs les plus fréquentes de <paramref name=\"image\" /> et contient <paramref name=\"entriesCount\" /> entrées. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_9}


```
 get_downscale_palette(image) 
```

Obtenir une palette de 256 couleurs, composée des bits supérieurs des valeurs de couleur de l'image initiale.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | L'image. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Le [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_10}


```
 get_uniform_color_palette(image) 
```

Obtenir une palette uniforme de 256 couleurs.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | L'image. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Le [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_11}


```
 has_transparent_colors(palette) 
```

Détermine si la palette spécifiée contient des couleurs transparentes.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si la palette spécifiée possède des couleurs transparentes ; sinon, <c>false</c>. |


