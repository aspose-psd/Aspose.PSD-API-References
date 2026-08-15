---
title: "Класс ColorPaletteHelper"
type: docs
weight: 810
url: /ru/python-net/aspose.psd/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPaletteHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Создаёт 4‑битовую цветовую палитру. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Создаёт 4‑битовую палитру градаций серого. |
| [create_8_bit()](#create_8_bit__3) | Создаёт 8‑битовую цветовую палитру. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Создаёт 8‑битовую палитру градаций серого. |
| [create_monochrome()](#create_monochrome__5) | Создаёт монохромную цветовую палитру, содержащую только 2 цвета. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_6) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_8) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений. |
| [get_downscale_palette(image)](#get_downscale_palette_image_9) | Получить 256‑цветную палитру, составленную из старших битов начальных цветовых значений изображения. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_10) | Получить однородную 256‑цветную палитру. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_11) | Определяет, содержит ли указанная палитра прозрачные цвета. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Создаёт 4‑битовую цветовую палитру.

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 4‑битовая цветовая палитра. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Создаёт 4‑битовую палитру градаций серого.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| min_is_white | bool | если установлено значение <c>true</c>, палитра начинается с белого цвета, иначе начинается с черного цвета. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Эта 4‑битовая градационная палитра. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Создаёт 8‑битовую цветовую палитру.

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Эта 8‑битовая цветовая палитра. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Создаёт 8‑битовую палитру градаций серого.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| min_is_white | bool | если установлено значение <c>true</c>, палитра начинается с белого цвета, иначе начинается с черного цвета. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Эта 8‑битовая градационная палитра. |


### Method: create_monochrome()  [static] {#create_monochrome__5}


```
 create_monochrome() 
```

Создаёт монохромную цветовую палитру, содержащую только 2 цвета.

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Цветовая палитра для монохромных изображений. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_6}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Растровое изображение. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Границы целевого изображения. |
| entries_count | int | Желаемое количество записей. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Цветовая палитра, которая начинается с наиболее часто встречающихся цветов из <paramref name="image" /> и содержит <paramref name="entriesCount" /> записей. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Растровое изображение. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Границы целевого изображения. |
| entries_count | int | Желаемое количество записей. |
| use_image_palette | bool | Если установлено, будет использовать собственную палитру изображения, если она доступна |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Цветовая палитра, которая начинается с наиболее часто встречающихся цветов из <paramref name="image" /> и содержит <paramref name="entriesCount" /> записей. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_8}


```
 get_close_image_palette(image, entries_count) 
```

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Растровое изображение. |
| entries_count | int | Желаемое количество записей. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Цветовая палитра, которая начинается с наиболее часто встречающихся цветов из <paramref name="image" /> и содержит <paramref name="entriesCount" /> записей. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_9}


```
 get_downscale_palette(image) 
```

Получить 256‑цветную палитру, составленную из старших битов начальных цветовых значений изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Изображение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Эта [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_10}


```
 get_uniform_color_palette(image) 
```

Получить однородную 256‑цветную палитру.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Изображение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Эта [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_11}


```
 has_transparent_colors(palette) 
```

Определяет, содержит ли указанная палитра прозрачные цвета.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Эта палитра. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если указанная палитра имеет прозрачные цвета; иначе <c>false</c>. |


