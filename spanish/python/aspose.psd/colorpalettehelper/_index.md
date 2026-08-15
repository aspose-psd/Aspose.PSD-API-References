---
title: "ColorPaletteHelper Class"
type: docs
weight: 810
url: /es/python-net/aspose.psd/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPaletteHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Crea la paleta de colores de 4 bits. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Crea la paleta de escala de grises de 4 bits. |
| [create_8_bit()](#create_8_bit__3) | Crea la paleta de colores de 8 bits. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Crea la paleta de escala de grises de 8 bits. |
| [create_monochrome()](#create_monochrome__5) | Crea una paleta de colores monocromática que contiene solo 2 colores. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_6) | Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7) | Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_8) | Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos. |
| [get_downscale_palette(image)](#get_downscale_palette_image_9) | Obtiene una paleta de 256 colores, compuesta a partir de los bits superiores de los valores de color de la imagen inicial. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_10) | Obtiene una paleta uniforme de 256 colores. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_11) | Determina si la paleta especificada tiene colores transparentes. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Crea la paleta de colores de 4 bits.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La paleta de colores de 4 bits. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Crea la paleta de escala de grises de 4 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| min_is_white | bool | si se establece en <c>true</c> la paleta comienza con color blanco, de lo contrario comienza con color negro. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La paleta de escala de grises de 4 bits. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Crea la paleta de colores de 8 bits.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La paleta de colores de 8 bits. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Crea la paleta de escala de grises de 8 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| min_is_white | bool | si se establece en <c>true</c> la paleta comienza con color blanco, de lo contrario comienza con color negro. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La paleta de escala de grises de 8 bits. |


### Method: create_monochrome()  [static] {#create_monochrome__5}


```
 create_monochrome() 
```

Crea una paleta de colores monocromática que contiene solo 2 colores.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Paleta de colores para imágenes monocromáticas. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_6}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | La imagen raster. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Los límites de la imagen de destino. |
| entries_count | int | El recuento deseado de entradas. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La paleta de colores que comienza con los colores más frecuentes de <paramref name="image" /> y contiene <paramref name="entriesCount" /> entradas. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | La imagen raster. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Los límites de la imagen de destino. |
| entries_count | int | El recuento deseado de entradas. |
| use_image_palette | bool | Si está configurado, usará su propia paleta de imágenes si está disponible. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La paleta de colores que comienza con los colores más frecuentes de <paramref name="image" /> y contiene <paramref name="entriesCount" /> entradas. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_8}


```
 get_close_image_palette(image, entries_count) 
```

Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | La imagen raster. |
| entries_count | int | El recuento deseado de entradas. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La paleta de colores que comienza con los colores más frecuentes de <paramref name="image" /> y contiene <paramref name="entriesCount" /> entradas. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_9}


```
 get_downscale_palette(image) 
```

Obtiene una paleta de 256 colores, compuesta a partir de los bits superiores de los valores de color de la imagen inicial.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | La imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | El [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_10}


```
 get_uniform_color_palette(image) 
```

Obtiene una paleta uniforme de 256 colores.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | La imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | El [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_11}


```
 has_transparent_colors(palette) 
```

Determina si la paleta especificada tiene colores transparentes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La paleta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la paleta especificada tiene colores transparentes; de lo contrario, <c>false</c>. |


