---
title: "Класс SizeF"
type: docs
weight: 4090
url: /ru/python-net/aspose.psd/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SizeF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [SizeF()](#SizeF__1) | Инициализирует новый экземпляр класса SizeF |
| [SizeF(point)](#SizeF_point_2) | Инициализирует новый экземпляр структуры [SizeF](/psd/python-net/aspose.psd/sizef/) из указанного [PointF](/psd/python-net/aspose.psd/pointf/). |
| [SizeF(size)](#SizeF_size_3) | Инициализирует новый экземпляр структуры [SizeF](/psd/python-net/aspose.psd/sizef/) из указанного [SizeF](/psd/python-net/aspose.psd/sizef/). |
| [SizeF(width, height)](#SizeF_width_height_4) | Инициализирует новый экземпляр структуры [SizeF](/psd/python-net/aspose.psd/sizef/) из указанных размеров. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/psd/python-net/aspose.psd/sizef) | r | Получает новый экземпляр структуры [SizeF](/psd/python-net/aspose.psd/sizef/), у которой значения [SizeF.width](/psd/python-net/aspose.psd/sizef/) и [SizeF.height](/psd/python-net/aspose.psd/sizef/) установлены в ноль. |
| height | float | r/w | Получает или задает вертикальный компонент этого [SizeF](/psd/python-net/aspose.psd/sizef/). |
| is_empty | bool | r | Получает значение, указывающее, имеет ли этот [SizeF](/psd/python-net/aspose.psd/sizef/) нулевую ширину и высоту. |
| width | float | r/w | Получает или задает горизонтальный компонент этого [SizeF](/psd/python-net/aspose.psd/sizef/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Добавляет ширину и высоту одной структуры [SizeF](/psd/python-net/aspose.psd/sizef/) к ширине и высоте другой структуры [SizeF](/psd/python-net/aspose.psd/sizef/). |
| [subtract(size1, size2)](#subtract_size1_size2_2) | Вычитает ширину и высоту одной структуры [SizeF](/psd/python-net/aspose.psd/sizef/) из ширины и высоты другой структуры [SizeF](/psd/python-net/aspose.psd/sizef/). |
| [to_point_f()](#to_point_f__3) | Преобразует [SizeF](/psd/python-net/aspose.psd/sizef/) в [PointF](/psd/python-net/aspose.psd/pointf/). |
| [to_size()](#to_size__4) | Преобразует [SizeF](/psd/python-net/aspose.psd/sizef/) в структуру [Size](/psd/python-net/aspose.psd/size/) с усечёнными значениями размеров. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Инициализирует новый экземпляр класса SizeF

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Инициализирует новый экземпляр структуры [SizeF](/psd/python-net/aspose.psd/sizef/) из указанного [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) из которого инициализируется этот [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Инициализирует новый экземпляр структуры [SizeF](/psd/python-net/aspose.psd/sizef/) из указанного [SizeF](/psd/python-net/aspose.psd/sizef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | [SizeF](/psd/python-net/aspose.psd/sizef/) из которого создать новый [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Инициализирует новый экземпляр структуры [SizeF](/psd/python-net/aspose.psd/sizef/) из указанных размеров.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | float | Ширина нового [SizeF](/psd/python-net/aspose.psd/sizef/). |
| height | float | Высота нового [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Добавляет ширину и высоту одной структуры [SizeF](/psd/python-net/aspose.psd/sizef/) к ширине и высоте другой структуры [SizeF](/psd/python-net/aspose.psd/sizef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | Первый [SizeF](/psd/python-net/aspose.psd/sizef/) для добавления. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | Второй [SizeF](/psd/python-net/aspose.psd/sizef/) для добавления. |

**Returns**

| Тип | Описание |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Структура [SizeF](/psd/python-net/aspose.psd/sizef/), являющаяся результатом операции сложения. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_2}


```
 subtract(size1, size2) 
```

Вычитает ширину и высоту одной структуры [SizeF](/psd/python-net/aspose.psd/sizef/) из ширины и высоты другой структуры [SizeF](/psd/python-net/aspose.psd/sizef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | Структура [SizeF](/psd/python-net/aspose.psd/sizef/) слева от оператора вычитания. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | Структура [SizeF](/psd/python-net/aspose.psd/sizef/) справа от оператора вычитания. |

**Returns**

| Тип | Описание |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Структура [SizeF](/psd/python-net/aspose.psd/sizef/) является результатом операции вычитания. |


### Method: to_point_f() {#to_point_f__3}


```
 to_point_f() 
```

Преобразует [SizeF](/psd/python-net/aspose.psd/sizef/) в [PointF](/psd/python-net/aspose.psd/pointf/).

**Returns**

| Тип | Описание |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Возвращает структуру [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: to_size() {#to_size__4}


```
 to_size() 
```

Преобразует [SizeF](/psd/python-net/aspose.psd/sizef/) в структуру [Size](/psd/python-net/aspose.psd/size/) с усечёнными значениями размеров.

**Returns**

| Тип | Описание |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Возвращает структуру [Size](/psd/python-net/aspose.psd/size/). |


