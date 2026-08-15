---
title: "Класс IntRange"
type: docs
weight: 2340
url: /ru/python-net/aspose.psd/intrange/
---

**Summary:** Class for representing sequence of elements

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IntRange

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [IntRange(range)](#IntRange_range_1) | Инициализирует новый экземпляр класса [IntRange](/psd/python-net/aspose.psd/intrange/). |
| [IntRange(start, count)](#IntRange_start_count_2) | Инициализирует новый экземпляр класса [IntRange](/psd/python-net/aspose.psd/intrange/). |
| [IntRange(start, count, delta)](#IntRange_start_count_delta_3) | Инициализирует новый экземпляр класса [IntRange](/psd/python-net/aspose.psd/intrange/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| range | int | r/w | Получает или задаёт диапазон. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_array_one_item_from_index(index)](#get_array_one_item_from_index_index_1) | Возвращает массив из одного элемента по указанному индексу |
| [get_range(start, count, delta)](#get_range_start_count_delta_2) | Получает диапазон количества элементов int, начиная с start |


### Constructor: IntRange(range) {#IntRange_range_1}


```
 IntRange(range) 
```

Инициализирует новый экземпляр класса [IntRange](/psd/python-net/aspose.psd/intrange/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| range | int | Диапазон. |

### Constructor: IntRange(start, count) {#IntRange_start_count_2}


```
 IntRange(start, count) 
```

Инициализирует новый экземпляр класса [IntRange](/psd/python-net/aspose.psd/intrange/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| start | int | Начало. |
| количество | int | Количество. |

### Constructor: IntRange(start, count, delta) {#IntRange_start_count_delta_3}


```
 IntRange(start, count, delta) 
```

Инициализирует новый экземпляр класса [IntRange](/psd/python-net/aspose.psd/intrange/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| start | int | Начало. |
| количество | int | Количество. |
| delta | int | Дельта. |

### Method: get_array_one_item_from_index(index) {#get_array_one_item_from_index_index_1}


```
 get_array_one_item_from_index(index) 
```

Возвращает массив из одного элемента по указанному индексу

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | int | Индекс диапазона. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Массив int |


### Method: get_range(start, count, delta)  [static] {#get_range_start_count_delta_2}


```
 get_range(start, count, delta) 
```

Получает диапазон количества элементов int, начиная с start

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| start | int | Начало. |
| количество | int | Количество. |
| delta | int | Дельта. |

**Returns**

| Тип | Описание |
| :- | :- |
| iter[int] | Массив элементов |


