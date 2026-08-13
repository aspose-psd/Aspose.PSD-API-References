---
title: "فئة ColorPalette"
type: docs
weight: 800
url: /ar/python-net/aspose.psd/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | ينشئ مثلاً جديدًا من فئة [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) وتكون IsCompactPalette غير صحيحة. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | ينشئ مثلاً جديدًا من فئة [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |
| [ColorPalette(entries)](#ColorPalette_entries_3) | ينشئ مثلاً جديدًا من فئة [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) وتكون IsCompactPalette غير صحيحة. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | ينشئ مثلاً جديدًا من فئة [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | يحصل على مصفوفة من هياكل ARGB 32‑بت. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | يحصل على مصفوفة من هياكل [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | يحصل على عدد الإدخالات. |
| is_compact_palette | bool | r | يحصل أو يضبط قيمة تشير إلى ما إذا كانت لوحة الألوان المدمجة مستخدمة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | ينسخ لوحة الألوان. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | ينسخ لوحة الألوان. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | يحصل على لون لوحة ARGB 32‑بت حسب الفهرس. |
| [get_color(index)](#get_color_index_4) | يحصل على لون لوحة الألوان حسب الفهرس. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | يحصل على فهرس أقرب لون. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | يحصل على فهرس أقرب لون. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

ينشئ مثلاً جديدًا من فئة [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) وتكون IsCompactPalette غير صحيحة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| argb_32_entries | int | إدخالات لوحة ألوان ARGB ذات 32 بت. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

ينشئ مثلاً جديدًا من فئة [ColorPalette](/psd/python-net/aspose.psd/colorpalette/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| argb_32_entries | int | إدخالات لوحة ألوان ARGB ذات 32 بت. |
| is_compact_palette | bool | تشير إلى ما إذا كانت لوحة الألوان مضغوطة. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

ينشئ مثلاً جديدًا من فئة [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) وتكون IsCompactPalette غير صحيحة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

ينشئ مثلاً جديدًا من فئة [ColorPalette](/psd/python-net/aspose.psd/colorpalette/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |
| is_compact_palette | bool | تشير إلى ما إذا كانت لوحة الألوان مضغوطة. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

ينسخ لوحة الألوان.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة الألوان. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | لوحة الألوان التي تم إنشاؤها ونسخها حديثًا أو null إذا تم تمرير لوحة ألوان null. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

ينسخ لوحة الألوان.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة الألوان. |
| use_compact_palette | bool | تشير إلى ما إذا كانت لوحة الألوان مضغوطة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | لوحة الألوان التي تم إنشاؤها ونسخها حديثًا أو null إذا تم تمرير لوحة ألوان null. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_3}


```
 get_argb_32_color(index) 
```

يحصل على لون لوحة ARGB 32‑بت حسب الفهرس.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| index | int | فهرس لون لوحة 32-bit ARGB. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | إدخال لوحة الألوان المحدد بواسطة <paramref name="index" />. |


### Method: get_color(index) {#get_color_index_4}


```
 get_color(index) 
```

يحصل على لون لوحة الألوان حسب الفهرس.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| index | int | فهرس لون اللوحة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | إدخال لوحة الألوان المحدد بواسطة <paramref name="index" />. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_5}


```
 get_nearest_color_index(argb_32_color) 
```

يحصل على فهرس أقرب لون.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| argb_32_color | int | لون 32-bit ARGB. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | فهرس أقرب لون. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_6}


```
 get_nearest_color_index(color) 
```

يحصل على فهرس أقرب لون.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | فهرس أقرب لون. |


