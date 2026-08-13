---
title: "ColorPaletteHelper 类"
type: docs
weight: 810
url: /zh/python-net/aspose.psd/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPaletteHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | 创建 4 位颜色调色板。 |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | 创建 4 位灰度调色板。 |
| [create_8_bit()](#create_8_bit__3) | 创建 8 位颜色调色板。 |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | 创建 8 位灰度调色板。 |
| [create_monochrome()](#create_monochrome__5) | 创建仅包含 2 种颜色的单色颜色调色板。 |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_6) | 如果光栅图像没有调色板，则从图像获取调色板（对图像进行调色）。如果已有调色板，则直接使用它，而不进行计算。 |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7) | 如果光栅图像没有调色板，则从图像获取调色板（对图像进行调色）。如果已有调色板，则直接使用它，而不进行计算。 |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_8) | 如果光栅图像没有调色板，则从图像获取调色板（对图像进行调色）。如果已有调色板，则直接使用它，而不进行计算。 |
| [get_downscale_palette(image)](#get_downscale_palette_image_9) | 获取 256 色调色板，由初始图像颜色值的高位组成。 |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_10) | 获取统一的 256 色调色板。 |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_11) | 确定指定的调色板是否具有透明颜色。 |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

创建 4 位颜色调色板。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 4 位颜色调色板。 |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

创建 4 位灰度调色板。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| min_is_white | bool | 如果设置为 <c>true</c>，调色板将以白色开始，否则以黑色开始。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 4 位灰度调色板。 |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

创建 8 位颜色调色板。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 8 位彩色调色板。 |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

创建 8 位灰度调色板。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| min_is_white | bool | 如果设置为 <c>true</c>，调色板将以白色开始，否则以黑色开始。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 8 位灰度调色板。 |


### Method: create_monochrome()  [static] {#create_monochrome__5}


```
 create_monochrome() 
```

创建仅包含 2 种颜色的单色颜色调色板。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 单色图像的颜色调色板。 |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_6}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

如果光栅图像没有调色板，则从图像获取调色板（对图像进行调色）。如果已有调色板，则直接使用它，而不进行计算。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 光栅图像。 |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 目标图像的边界。 |
| entries_count | int | 所需条目数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 该颜色调色板从 <paramref name="image" /> 中最常见的颜色开始，并包含 <paramref name="entriesCount" /> 条目。 |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

如果光栅图像没有调色板，则从图像获取调色板（对图像进行调色）。如果已有调色板，则直接使用它，而不进行计算。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 光栅图像。 |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 目标图像的边界。 |
| entries_count | int | 所需条目数。 |
| use_image_palette | bool | 如果设置，它将在可用时使用其自己的图像调色板 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 该颜色调色板从 <paramref name="image" /> 中最常见的颜色开始，并包含 <paramref name="entriesCount" /> 条目。 |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_8}


```
 get_close_image_palette(image, entries_count) 
```

如果光栅图像没有调色板，则从图像获取调色板（对图像进行调色）。如果已有调色板，则直接使用它，而不进行计算。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 光栅图像。 |
| entries_count | int | 所需条目数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 该颜色调色板从 <paramref name="image" /> 中最常见的颜色开始，并包含 <paramref name="entriesCount" /> 条目。 |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_9}


```
 get_downscale_palette(image) 
```

获取 256 色调色板，由初始图像颜色值的高位组成。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 图像。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | 该 [ColorPalette](/psd/python-net/aspose.psd/colorpalette/)。 |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_10}


```
 get_uniform_color_palette(image) 
```

获取统一的 256 色调色板。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 图像。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | 该 [ColorPalette](/psd/python-net/aspose.psd/colorpalette/)。 |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_11}


```
 has_transparent_colors(palette) 
```

确定指定的调色板是否具有透明颜色。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 调色板。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 表示指定的调色板具有透明颜色；否则为 <c>false</c>。 |


