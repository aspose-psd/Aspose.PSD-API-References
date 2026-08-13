---
title: "الفئة ColorPaletteHelper"
type: docs
weight: 810
url: /ar/python-net/aspose.psd/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPaletteHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | ينشئ لوحة ألوان 4 بت. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | ينشئ لوحة تدرج رمادي 4 بت. |
| [create_8_bit()](#create_8_bit__3) | ينشئ لوحة ألوان 8 بت. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | ينشئ لوحة تدرج رمادي 8 بت. |
| [create_monochrome()](#create_monochrome__5) | ينشئ لوحة ألوان أحادية اللون تحتوي على لونين فقط. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_6) | يحصل على لوحة الألوان من صورة نقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت لوحة الألوان موجودة سيتم استخدامها بدلاً من إجراء الحسابات. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7) | يحصل على لوحة الألوان من صورة نقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت لوحة الألوان موجودة سيتم استخدامها بدلاً من إجراء الحسابات. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_8) | يحصل على لوحة الألوان من صورة نقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت لوحة الألوان موجودة سيتم استخدامها بدلاً من إجراء الحسابات. |
| [get_downscale_palette(image)](#get_downscale_palette_image_9) | احصل على لوحة ألوان 256، مكوّنة من البتات العليا لقيم ألوان الصورة الأولية. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_10) | احصل على لوحة ألوان 256 موحدة. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_11) | يحدد ما إذا كانت لوحة الألوان المحددة تحتوي على ألوان شفافة. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

ينشئ لوحة ألوان 4 بت.

**Returns**

| النوع | الوصف |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة ألوان 4 بت. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

ينشئ لوحة تدرج رمادي 4 بت.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| min_is_white | bool | إذا تم الضبط على <c>true</c> تبدأ اللوحة بالأبيض، وإلا تبدأ بالأسود. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة التدرج الرمادي 4 بت. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

ينشئ لوحة ألوان 8 بت.

**Returns**

| النوع | الوصف |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة الألوان 8 بت. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

ينشئ لوحة تدرج رمادي 8 بت.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| min_is_white | bool | إذا تم الضبط على <c>true</c> تبدأ اللوحة بالأبيض، وإلا تبدأ بالأسود. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة التدرج الرمادي 8 بت. |


### Method: create_monochrome()  [static] {#create_monochrome__5}


```
 create_monochrome() 
```

ينشئ لوحة ألوان أحادية اللون تحتوي على لونين فقط.

**Returns**

| النوع | الوصف |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة ألوان للصور أحادية اللون. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_6}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

يحصل على لوحة الألوان من صورة نقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت لوحة الألوان موجودة سيتم استخدامها بدلاً من إجراء الحسابات.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | صورة الراستر. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | حدود الصورة الوجهة. |
| entries_count | int | عدد الإدخالات المطلوب. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من <paramref name="image" /> وتحتوي على <paramref name="entriesCount" /> إدخالات. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

يحصل على لوحة الألوان من صورة نقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت لوحة الألوان موجودة سيتم استخدامها بدلاً من إجراء الحسابات.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | صورة الراستر. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | حدود الصورة الوجهة. |
| entries_count | int | عدد الإدخالات المطلوب. |
| use_image_palette | bool | إذا تم الضبط، سيستخدم لوحة ألوانه الخاصة إذا كانت متاحة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من <paramref name="image" /> وتحتوي على <paramref name="entriesCount" /> إدخالات. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_8}


```
 get_close_image_palette(image, entries_count) 
```

يحصل على لوحة الألوان من صورة نقطية (يقوم بتصنيف الصورة) في حال عدم وجود لوحة ألوان للصورة. إذا كانت لوحة الألوان موجودة سيتم استخدامها بدلاً من إجراء الحسابات.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | صورة الراستر. |
| entries_count | int | عدد الإدخالات المطلوب. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من <paramref name="image" /> وتحتوي على <paramref name="entriesCount" /> إدخالات. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_9}


```
 get_downscale_palette(image) 
```

احصل على لوحة ألوان 256، مكوّنة من البتات العليا لقيم ألوان الصورة الأولية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | الصورة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | الـ [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_10}


```
 get_uniform_color_palette(image) 
```

احصل على لوحة ألوان 256 موحدة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | الصورة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | الـ [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_11}


```
 has_transparent_colors(palette) 
```

يحدد ما إذا كانت لوحة الألوان المحددة تحتوي على ألوان شفافة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | اللوحة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كانت اللوحة المحددة تحتوي على ألوان شفافة؛ وإلا <c>false</c>. |


