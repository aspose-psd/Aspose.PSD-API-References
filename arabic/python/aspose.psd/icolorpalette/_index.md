---
title: "الفئة IColorPalette"
type: docs
weight: 1710
url: /ar/python-net/aspose.psd/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | يحصل على مصفوفة من هياكل ARGB 32‑بت. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | يحصل على مصفوفة من هياكل [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | يحصل على عدد الإدخالات. |
| is_compact_palette | bool | r | يحصل على قيمة تشير إلى ما إذا تم استخدام لوحة ألوان مدمجة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | يحصل على لون لوحة ARGB 32‑بت حسب الفهرس. |
| [get_color(index)](#get_color_index_2) | يحصل على لون لوحة الألوان حسب الفهرس. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | يحصل على فهرس أقرب لون 32-bit ARGB. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | يحصل على فهرس أقرب لون 32-bit ARGB. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


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


### Method: get_color(index) {#get_color_index_2}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

يحصل على فهرس أقرب لون 32-bit ARGB.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| argb_32_color | int | لون 32-bit ARGB. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | فهرس أقرب لون. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

يحصل على فهرس أقرب لون 32-bit ARGB.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | فهرس أقرب لون. |


