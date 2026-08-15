---
title: "IPsdColorPalette Класс"
type: docs
weight: 1990
url: /ru/python-net/aspose.psd/ipsdcolorpalette/
---

**Summary:** The pasd color palette

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPsdColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Получает массив 32-битных структур ARGB. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Получает массив структур [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Получает количество записей. |
| имеет_прозрачный_цвет | bool | r | Получает значение, указывающее, существует ли прозрачный цвет. |
| is_compact_palette | bool | r | Получает значение, указывающее, используется ли компактная палитра. |
| raw_entries | байт | r | Получает необработанные данные записей цветовой палитры. |
| raw_entries_count | int | r | Получает количество необработанных записей цветовой палитры. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Получает прозрачный цвет. |
| transparent_index | short | r | Получает индекс прозрачного цвета. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | Получает 32-битный цвет палитры ARGB по индексу. |
| [get_color(index)](#get_color_index_2) | Получает цвет палитры по индексу. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | Получает индекс ближайшего 32‑битного цвета ARGB. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | Получает индекс ближайшего 32‑битного цвета ARGB. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


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


### Method: get_color(index) {#get_color_index_2}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

Получает индекс ближайшего 32‑битного цвета ARGB.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_32_color | int | 32‑битный цвет ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Индекс ближайшего цвета. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

Получает индекс ближайшего 32‑битного цвета ARGB.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Индекс ближайшего цвета. |


