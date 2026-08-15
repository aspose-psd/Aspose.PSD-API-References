---
title: "Класс PsdColorPalette"
type: docs
weight: 1750
url: /ru/python-net/aspose.psd.fileformats.psd/psdcolorpalette/
---

**Summary:** The PSD color palette.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdColorPalette

**Inheritance:** IPsdColorPalette, IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PsdColorPalette(color_palette)](#PsdColorPalette_color_palette_1) | Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette, transparent_index)](#PsdColorPalette_color_palette_transparent_index_2) | Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_argb_32_entries, is_compact_palette)](#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3) | Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_entries)](#PsdColorPalette_color_palette_entries_4) | Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) и IsCompactPalette равно false. |
| [PsdColorPalette(color_palette_entries, is_compact_palette)](#PsdColorPalette_color_palette_entries_is_compact_palette_5) | Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_entries, transparent_index)](#PsdColorPalette_color_palette_entries_transparent_index_6) | Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) и IsCompactPalette равно false. |
| [PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette)](#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7) | Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(raw_entries_data)](#PsdColorPalette_raw_entries_data_8) | Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) и IsCompactPalette равно false. |
| [PsdColorPalette(raw_entries_data, is_compact_palette)](#PsdColorPalette_raw_entries_data_is_compact_palette_9) | Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(raw_entries_data, transparent_index)](#PsdColorPalette_raw_entries_data_transparent_index_10) | Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) и IsCompactPalette равно false. |
| [PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette)](#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11) | Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Возвращает массив 32‑битных цветов ARGB. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Получает массив структур [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Получает количество записей. |
| имеет_прозрачный_цвет | bool | r | Получает значение, указывающее, существует ли прозрачный цвет. |
| is_compact_palette | bool | r | Возвращает значение, указывающее, является ли палитра компактной. |
| raw_entries | байт | r | Получает необработанные данные записей цветовой палитры. |
| raw_entries_count | int | r | Получает количество необработанных записей цветовой палитры. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Получает прозрачный цвет. |
| transparent_index | short | r | Получает индекс прозрачного цвета. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Копирует палитру. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Копирует палитру. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Получает 32-битный цвет палитры ARGB по индексу. |
| [get_color(index)](#get_color_index_4) | Получает цвет палитры по индексу. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Получает индекс ближайшего цвета. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Получает индекс ближайшего цвета. |


### Constructor: PsdColorPalette(color_palette) {#PsdColorPalette_color_palette_1}


```
 PsdColorPalette(color_palette) 
```

Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Цветовая палитра. |

### Constructor: PsdColorPalette(color_palette, transparent_index) {#PsdColorPalette_color_palette_transparent_index_2}


```
 PsdColorPalette(color_palette, transparent_index) 
```

Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Цветовая палитра. |
| transparent_index | short | Индекс прозрачного цвета. |

### Constructor: PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) {#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3}


```
 PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) 
```

Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color_palette_argb_32_entries | int | Записи 32-битовой ARGB палитры цветов. |
| is_compact_palette | bool | Указывает, является ли палитра компактной. |

### Constructor: PsdColorPalette(color_palette_entries) {#PsdColorPalette_color_palette_entries_4}


```
 PsdColorPalette(color_palette_entries) 
```

Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) и IsCompactPalette равно false.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Записи палитры цветов. |

### Constructor: PsdColorPalette(color_palette_entries, is_compact_palette) {#PsdColorPalette_color_palette_entries_is_compact_palette_5}


```
 PsdColorPalette(color_palette_entries, is_compact_palette) 
```

Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Записи палитры цветов. |
| is_compact_palette | bool | Указывает, является ли палитра компактной. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index) {#PsdColorPalette_color_palette_entries_transparent_index_6}


```
 PsdColorPalette(color_palette_entries, transparent_index) 
```

Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) и IsCompactPalette равно false.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Записи палитры цветов. |
| transparent_index | short | Индекс прозрачного цвета. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) {#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7}


```
 PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) 
```

Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Записи палитры цветов. |
| transparent_index | short | Индекс прозрачного цвета. |
| use_compact_palette | bool | Указывает, является ли палитра компактной. |

### Constructor: PsdColorPalette(raw_entries_data) {#PsdColorPalette_raw_entries_data_8}


```
 PsdColorPalette(raw_entries_data) 
```

Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) и IsCompactPalette равно false.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| raw_entries_data | байт | Сырые данные записей. |

### Constructor: PsdColorPalette(raw_entries_data, is_compact_palette) {#PsdColorPalette_raw_entries_data_is_compact_palette_9}


```
 PsdColorPalette(raw_entries_data, is_compact_palette) 
```

Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| raw_entries_data | байт | Сырые данные записей. |
| is_compact_palette | bool | Указывает, является ли палитра компактной. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index) {#PsdColorPalette_raw_entries_data_transparent_index_10}


```
 PsdColorPalette(raw_entries_data, transparent_index) 
```

Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) и IsCompactPalette равно false.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| raw_entries_data | байт | Сырые данные записей. |
| transparent_index | short | Индекс прозрачного цвета. Обратите внимание, что индекс не является индексом сырых записей, а относится к преобразованному массиву цветов. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) {#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11}


```
 PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) 
```

Инициализирует новый экземпляр класса [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| raw_entries_data | байт | Сырые данные записей. |
| transparent_index | short | Индекс прозрачного цвета. Обратите внимание, что индекс не является индексом сырых записей, а относится к преобразованному массиву цветов. |
| use_compact_palette | bool | Указывает, является ли палитра компактной. |

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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | Новосозданная и скопированная палитра или null, если передана null‑палитра. |


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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | Новосозданная и скопированная палитра или null, если передана null‑палитра. |


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


