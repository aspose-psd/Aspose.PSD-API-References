---
title: "Класс ColorPalette"
type: docs
weight: 800
url: /ru/python-net/aspose.psd/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Инициализирует новый экземпляр класса [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) и устанавливает IsCompactPalette в false. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Инициализирует новый экземпляр класса [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Инициализирует новый экземпляр класса [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) и устанавливает IsCompactPalette в false. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Инициализирует новый экземпляр класса [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Получает массив 32-битных структур ARGB. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Получает массив структур [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Получает количество записей. |
| is_compact_palette | bool | r | Получает или задает значение, указывающее, используется ли компактная палитра. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Копирует палитру. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Копирует палитру. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Получает 32-битный цвет палитры ARGB по индексу. |
| [get_color(index)](#get_color_index_4) | Получает цвет палитры по индексу. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Получает индекс ближайшего цвета. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Получает индекс ближайшего цвета. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Инициализирует новый экземпляр класса [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) и устанавливает IsCompactPalette в false.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_32_entries | int | Записи 32‑битовой цветовой палитры ARGB. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Инициализирует новый экземпляр класса [ColorPalette](/psd/python-net/aspose.psd/colorpalette/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_32_entries | int | Записи 32‑битовой цветовой палитры ARGB. |
| is_compact_palette | bool | Указывает, является ли палитра компактной. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Инициализирует новый экземпляр класса [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) и устанавливает IsCompactPalette в false.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Инициализирует новый экземпляр класса [ColorPalette](/psd/python-net/aspose.psd/colorpalette/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |
| is_compact_palette | bool | Указывает, является ли палитра компактной. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Копирует палитру.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Цветовая палитра. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Новосозданная и скопированная палитра или null, если передана null‑палитра. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Копирует палитру.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Цветовая палитра. |
| use_compact_palette | bool | Указывает, является ли палитра компактной. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Новосозданная и скопированная палитра или null, если передана null‑палитра. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_3}


```
 get_argb_32_color(index) 
```

Получает 32-битный цвет палитры ARGB по индексу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | int | 32‑битный индекс цвета палитры ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Элемент палитры цветов, указанный с помощью <paramref name="index" />. |


### Method: get_color(index) {#get_color_index_4}


```
 get_color(index) 
```

Получает цвет палитры по индексу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | int | Индекс цвета палитры. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Элемент палитры цветов, указанный с помощью <paramref name="index" />. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_5}


```
 get_nearest_color_index(argb_32_color) 
```

Получает индекс ближайшего цвета.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_32_color | int | 32‑битный цвет ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Индекс ближайшего цвета. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_6}


```
 get_nearest_color_index(color) 
```

Получает индекс ближайшего цвета.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Индекс ближайшего цвета. |


