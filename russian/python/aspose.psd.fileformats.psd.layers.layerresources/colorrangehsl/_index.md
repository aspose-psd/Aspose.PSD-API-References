---
title: "Класс ColorRangeHsl"
type: docs
weight: 180
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Summary:** [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) has 6 color ranges where you can change HSV parameters. <br/>            Every range has 4 key points to identify range borders. And it's ColorRangeHsl

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [ColorRangeHsl()](#ColorRangeHsl__1) | Инициализирует новый экземпляр класса [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/). |
| [ColorRangeHsl(data)](#ColorRangeHsl_data_2) | Инициализирует новый экземпляр класса [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| hue | short | r/w | Получает или задает hue. |
| left_border | short | r/w | Получает или задает левую границу. |
| lightness | short | r/w | Получает или задает lightness. |
| most_left_border | short | r/w | Получает или задает самую левую границу. |
| most_right_border | short | r/w | Получает или задает самую правую границу. |
| right_border | short | r/w | Получает или задает правую границу. |
| насыщенность | short | r/w | Получает или задает насыщенность. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_range_coefficient(hue)](#get_range_coefficient_hue_1) | Получает коэффициент диапазона. |
| [is_hue_in_big_range(hue)](#is_hue_in_big_range_hue_2) | Определяет, находится ли оттенок в большом диапазоне. |
| [is_hue_in_small_range(hue)](#is_hue_in_small_range_hue_3) | Определяет, находится ли оттенок в небольшом диапазоне. |
| [save(stream_container)](#save_stream_container_4) | Сохраняет данные в указанный контейнер потока. |


### Constructor: ColorRangeHsl() {#ColorRangeHsl__1}


```
 ColorRangeHsl() 
```

Инициализирует новый экземпляр класса [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/).

### Constructor: ColorRangeHsl(data) {#ColorRangeHsl_data_2}


```
 ColorRangeHsl(data) 
```

Инициализирует новый экземпляр класса [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Данные диапазона цвета. |

### Method: get_range_coefficient(hue) {#get_range_coefficient_hue_1}


```
 get_range_coefficient(hue) 
```

Получает коэффициент диапазона.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| hue | double | Значение оттенка. |

**Returns**

| Тип | Описание |
| :- | :- |
| double | Коэффициент диапазона насыщенности. |


### Method: is_hue_in_big_range(hue) {#is_hue_in_big_range_hue_2}


```
 is_hue_in_big_range(hue) 
```

Определяет, находится ли оттенок в большом диапазоне.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| hue | double | Значение оттенка. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если оттенок в большом диапазоне; иначе <c>false</c>. |


### Method: is_hue_in_small_range(hue) {#is_hue_in_small_range_hue_3}


```
 is_hue_in_small_range(hue) 
```

Определяет, находится ли оттенок в небольшом диапазоне.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| hue | double | Значение оттенка. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если оттенок в небольшом диапазоне; иначе, <c>false</c>. |


### Method: save(stream_container) {#save_stream_container_4}


```
 save(stream_container) 
```

Сохраняет данные в указанный контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока. |

