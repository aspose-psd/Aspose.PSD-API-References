---
title: "Класс Size"
type: docs
weight: 4080
url: /ru/python-net/aspose.psd/size/
---

**Summary:** Represents size.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Size

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Size()](#Size__1) | Инициализирует новый экземпляр класса Size |
| [Size(point)](#Size_point_2) | Инициализирует новый экземпляр структуры [Size](/psd/python-net/aspose.psd/size/) из указанного [Point](/psd/python-net/aspose.psd/point/). |
| [Size(width, height)](#Size_width_height_3) | Инициализирует новый экземпляр структуры [Size](/psd/python-net/aspose.psd/size/) из указанных размеров. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| empty [static] | [Size](/psd/python-net/aspose.psd/size) | r | Возвращает новый экземпляр структуры [Size](/psd/python-net/aspose.psd/size/), у которого значения [Size.width](/psd/python-net/aspose.psd/size/) и [Size.height](/psd/python-net/aspose.psd/size/) установлены в ноль. |
| height | int | r/w | Получает или задаёт вертикальную компоненту этого [Size](/psd/python-net/aspose.psd/size/). |
| is_empty | bool | r | Возвращает значение, указывающее, имеет ли этот [Size](/psd/python-net/aspose.psd/size/) ширину и высоту, равные 0. |
| width | int | r/w | Получает или задаёт горизонтальную компоненту этого [Size](/psd/python-net/aspose.psd/size/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Добавляет ширину и высоту одной структуры [Size](/psd/python-net/aspose.psd/size/) к ширине и высоте другой структуры [Size](/psd/python-net/aspose.psd/size/). |
| [ceiling(size)](#ceiling_size_2) | Преобразует указанную структуру [SizeF](/psd/python-net/aspose.psd/sizef/) в структуру [Size](/psd/python-net/aspose.psd/size/), округляя значения структуры [Size](/psd/python-net/aspose.psd/size/) до следующего большего целого. |
| [round(size)](#round_size_3) | Преобразует указанную структуру [SizeF](/psd/python-net/aspose.psd/sizef/) в структуру [Size](/psd/python-net/aspose.psd/size/) путем округления значений структуры [SizeF](/psd/python-net/aspose.psd/sizef/) до ближайших целых значений. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Вычитает ширину и высоту одной структуры [Size](/psd/python-net/aspose.psd/size/) из ширины и высоты другой структуры [Size](/psd/python-net/aspose.psd/size/). |
| [truncate(size)](#truncate_size_5) | Преобразует указанную структуру [SizeF](/psd/python-net/aspose.psd/sizef/) в структуру [Size](/psd/python-net/aspose.psd/size/) путем усечения значений структуры [SizeF](/psd/python-net/aspose.psd/sizef/) до следующего меньшего целого значения. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Инициализирует новый экземпляр класса Size

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

Инициализирует новый экземпляр структуры [Size](/psd/python-net/aspose.psd/size/) из указанного [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Точка, из которой инициализируется эта [Size](/psd/python-net/aspose.psd/size/). |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Инициализирует новый экземпляр структуры [Size](/psd/python-net/aspose.psd/size/) из указанных размеров.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Компонент ширины нового [Size](/psd/python-net/aspose.psd/size/). |
| height | int | Компонент высоты нового [Size](/psd/python-net/aspose.psd/size/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Добавляет ширину и высоту одной структуры [Size](/psd/python-net/aspose.psd/size/) к ширине и высоте другой структуры [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | Первый [Size](/psd/python-net/aspose.psd/size/) для добавления. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | Второй [Size](/psd/python-net/aspose.psd/size/) для добавления. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Структура [Size](/psd/python-net/aspose.psd/size/), являющаяся результатом операции сложения. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Преобразует указанную структуру [SizeF](/psd/python-net/aspose.psd/sizef/) в структуру [Size](/psd/python-net/aspose.psd/size/), округляя значения структуры [Size](/psd/python-net/aspose.psd/size/) до следующего большего целого.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Структура [SizeF](/psd/python-net/aspose.psd/sizef/) для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Структура [Size](/psd/python-net/aspose.psd/size/), в которую преобразует этот метод. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Преобразует указанную структуру [SizeF](/psd/python-net/aspose.psd/sizef/) в структуру [Size](/psd/python-net/aspose.psd/size/) путем округления значений структуры [SizeF](/psd/python-net/aspose.psd/sizef/) до ближайших целых значений.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Структура [SizeF](/psd/python-net/aspose.psd/sizef/) для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Структура [Size](/psd/python-net/aspose.psd/size/), в которую преобразует этот метод. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Вычитает ширину и высоту одной структуры [Size](/psd/python-net/aspose.psd/size/) из ширины и высоты другой структуры [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | Структура [Size](/psd/python-net/aspose.psd/size/) слева от оператора вычитания. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | Структура [Size](/psd/python-net/aspose.psd/size/) справа от оператора вычитания. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | [Size](/psd/python-net/aspose.psd/size/), являющийся результатом операции вычитания. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Преобразует указанную структуру [SizeF](/psd/python-net/aspose.psd/sizef/) в структуру [Size](/psd/python-net/aspose.psd/size/) путем усечения значений структуры [SizeF](/psd/python-net/aspose.psd/sizef/) до следующего меньшего целого значения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Структура [SizeF](/psd/python-net/aspose.psd/sizef/) для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Структура [Size](/psd/python-net/aspose.psd/size/), в которую преобразует этот метод. |


