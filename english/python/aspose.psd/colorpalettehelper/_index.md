---
title: ColorPaletteHelper Class
type: docs
weight: 760
url: /python-net/aspose.psd/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPaletteHelper

**Aspose.PSD Version:** 24.2.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Creates the 4 bit color palette. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Creates the 4 bit grayscale palette. |
| [create_8_bit()](#create_8_bit__3) | Creates the 8 bit color palette. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Creates the 8 bit grayscale palette. |
| [create_monochrome()](#create_monochrome__5) | Creates a monochrome color palette containing 2 colors only. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_6) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_8) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [get_downscale_palette(image)](#get_downscale_palette_image_9) | Get 256 color palette, composed from upper bits of initial image color values. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_10) | Get uniform 256 color palette. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_11) | Determines whether the specified palette has transparent colors. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Creates the 4 bit color palette.

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | The 4 bit color palette. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Creates the 4 bit grayscale palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| min_is_white | bool | if set to <c>true</c> the palette starts with white color, otherwise it starts with black color. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | The 4 bit grayscale palette. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Creates the 8 bit color palette.

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | The 8 bit color palette. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Creates the 8 bit grayscale palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| min_is_white | bool | if set to <c>true</c> the palette starts with white color, otherwise it starts with black color. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | The 8 bit grayscale palette. |


### Method: create_monochrome()  [static] {#create_monochrome__5}


```
 create_monochrome() 
```

Creates a monochrome color palette containing 2 colors only.

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Color palette for monochrome images. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_6}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | The raster image. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The destination image bounds. |
| entries_count | int | The desired entries count. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | The color palette which starts with the most frequent colors from the <paramref name="image" /> and contains <paramref name="entriesCount" /> entries. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | The raster image. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The destination image bounds. |
| entries_count | int | The desired entries count. |
| use_image_palette | bool | If set, it will use its own image palette if available |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | The color palette which starts with the most frequent colors from the <paramref name="image" /> and contains <paramref name="entriesCount" /> entries. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_8}


```
 get_close_image_palette(image, entries_count) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | The raster image. |
| entries_count | int | The desired entries count. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | The color palette which starts with the most frequent colors from the <paramref name="image" /> and contains <paramref name="entriesCount" /> entries. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_9}


```
 get_downscale_palette(image) 
```

Get 256 color palette, composed from upper bits of initial image color values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | The image. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | The [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_10}


```
 get_uniform_color_palette(image) 
```

Get uniform 256 color palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | The image. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | The [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_11}


```
 has_transparent_colors(palette) 
```

Determines whether the specified palette has transparent colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | The palette. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if the specified palette has transparent colors; otherwise, <c>false</c>. |


