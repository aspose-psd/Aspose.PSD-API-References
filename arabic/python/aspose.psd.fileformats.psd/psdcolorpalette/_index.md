---
title: "فئة PsdColorPalette"
type: docs
weight: 1750
url: /ar/python-net/aspose.psd.fileformats.psd/psdcolorpalette/
---

**Summary:** The PSD color palette.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdColorPalette

**Inheritance:** IPsdColorPalette, IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PsdColorPalette(color_palette)](#PsdColorPalette_color_palette_1) | إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette, transparent_index)](#PsdColorPalette_color_palette_transparent_index_2) | إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_argb_32_entries, is_compact_palette)](#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3) | إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_entries)](#PsdColorPalette_color_palette_entries_4) | إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) و IsCompactPalette هو false. |
| [PsdColorPalette(color_palette_entries, is_compact_palette)](#PsdColorPalette_color_palette_entries_is_compact_palette_5) | إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_entries, transparent_index)](#PsdColorPalette_color_palette_entries_transparent_index_6) | إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) و IsCompactPalette هو false. |
| [PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette)](#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7) | إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(raw_entries_data)](#PsdColorPalette_raw_entries_data_8) | إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) و IsCompactPalette هو false. |
| [PsdColorPalette(raw_entries_data, is_compact_palette)](#PsdColorPalette_raw_entries_data_is_compact_palette_9) | إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(raw_entries_data, transparent_index)](#PsdColorPalette_raw_entries_data_transparent_index_10) | إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) و IsCompactPalette هو false. |
| [PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette)](#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11) | إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | يحصل على مصفوفة من ألوان ARGB 32-بت. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | يحصل على مصفوفة من هياكل [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | يحصل على عدد الإدخالات. |
| has_transparent_color | bool | r | يحصل على قيمة تشير إلى ما إذا كان اللون الشفاف موجودًا. |
| is_compact_palette | bool | r | يحصل على قيمة تشير إلى ما إذا كانت اللوحة مضغوطة. |
| raw_entries | byte | r | يحصل على بيانات الإدخالات الخام للوحة الألوان. |
| raw_entries_count | int | r | يحصل على عدد الإدخالات الخام للوحة الألوان. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | يحصل على اللون الشفاف. |
| transparent_index | short | r | يحصل على فهرس اللون الشفاف. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | ينسخ لوحة الألوان. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | ينسخ لوحة الألوان. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | يحصل على لون لوحة ARGB 32‑بت حسب الفهرس. |
| [get_color(index)](#get_color_index_4) | يحصل على لون لوحة الألوان حسب الفهرس. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | يحصل على فهرس أقرب لون. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | يحصل على فهرس أقرب لون. |


### Constructor: PsdColorPalette(color_palette) {#PsdColorPalette_color_palette_1}


```
 PsdColorPalette(color_palette) 
```

إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة الألوان. |

### Constructor: PsdColorPalette(color_palette, transparent_index) {#PsdColorPalette_color_palette_transparent_index_2}


```
 PsdColorPalette(color_palette, transparent_index) 
```

إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة الألوان. |
| transparent_index | short | فهرس اللون الشفاف. |

### Constructor: PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) {#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3}


```
 PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) 
```

إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| color_palette_argb_32_entries | int | مدخلات لوحة الألوان 32-بت ARGB. |
| is_compact_palette | bool | تشير إلى ما إذا كانت لوحة الألوان مضغوطة. |

### Constructor: PsdColorPalette(color_palette_entries) {#PsdColorPalette_color_palette_entries_4}


```
 PsdColorPalette(color_palette_entries) 
```

إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) و IsCompactPalette هو false.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | مدخلات لوحة الألوان. |

### Constructor: PsdColorPalette(color_palette_entries, is_compact_palette) {#PsdColorPalette_color_palette_entries_is_compact_palette_5}


```
 PsdColorPalette(color_palette_entries, is_compact_palette) 
```

إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | مدخلات لوحة الألوان. |
| is_compact_palette | bool | تشير إلى ما إذا كانت لوحة الألوان مضغوطة. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index) {#PsdColorPalette_color_palette_entries_transparent_index_6}


```
 PsdColorPalette(color_palette_entries, transparent_index) 
```

إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) و IsCompactPalette هو false.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | مدخلات لوحة الألوان. |
| transparent_index | short | فهرس اللون الشفاف. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) {#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7}


```
 PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) 
```

إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | مدخلات لوحة الألوان. |
| transparent_index | short | فهرس اللون الشفاف. |
| use_compact_palette | bool | تشير إلى ما إذا كانت لوحة الألوان مضغوطة. |

### Constructor: PsdColorPalette(raw_entries_data) {#PsdColorPalette_raw_entries_data_8}


```
 PsdColorPalette(raw_entries_data) 
```

إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) و IsCompactPalette هو false.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| raw_entries_data | byte | بيانات المدخلات الخام. |

### Constructor: PsdColorPalette(raw_entries_data, is_compact_palette) {#PsdColorPalette_raw_entries_data_is_compact_palette_9}


```
 PsdColorPalette(raw_entries_data, is_compact_palette) 
```

إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| raw_entries_data | byte | بيانات المدخلات الخام. |
| is_compact_palette | bool | تشير إلى ما إذا كانت لوحة الألوان مضغوطة. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index) {#PsdColorPalette_raw_entries_data_transparent_index_10}


```
 PsdColorPalette(raw_entries_data, transparent_index) 
```

إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) و IsCompactPalette هو false.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| raw_entries_data | byte | بيانات المدخلات الخام. |
| transparent_index | short | فهرس اللون الشفاف. لاحظ أن الفهرس ليس فهرس المدخلات الخام بل هو للفهرس المحول لمصفوفة الألوان. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) {#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11}


```
 PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) 
```

إنشاء مثيل جديد للفئة [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| raw_entries_data | byte | بيانات المدخلات الخام. |
| transparent_index | short | فهرس اللون الشفاف. لاحظ أن الفهرس ليس فهرس المدخلات الخام بل هو للفهرس المحول لمصفوفة الألوان. |
| use_compact_palette | bool | تشير إلى ما إذا كانت لوحة الألوان مضغوطة. |

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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | لوحة الألوان التي تم إنشاؤها ونسخها حديثًا أو null إذا تم تمرير لوحة ألوان null. |


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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | لوحة الألوان التي تم إنشاؤها ونسخها حديثًا أو null إذا تم تمرير لوحة ألوان null. |


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


