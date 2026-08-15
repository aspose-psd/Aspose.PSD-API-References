---
title: "Класс Figure"
type: docs
weight: 1220
url: /ru/python-net/aspose.psd/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Figure

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Figure()](#Figure__1) | Инициализирует новый экземпляр класса Figure. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Получает или задает границы объекта. |
| is_closed | bool | r/w | Получает или задает значение, указывающее, закрыта ли эта фигура. Закрытая фигура будет иметь значение только в случае, когда<br/>            первая и последняя формы фигуры являются непрерывными формами. В таком случае первая точка первой формы будет<br/>            соединена прямой линией с последней точкой последней формы. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Получает все сегменты фигуры. |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | r | Получает формы фигуры. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Добавляет форму к фигуре. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Добавляет диапазон форм к фигуре. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Получает границы объекта. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Получает границы объекта. |
| [remove_shape(shape)](#remove_shape_shape_5) | Удаляет форму из фигуры. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Удаляет диапазон форм из фигуры. |
| reverse() | Обращает порядок форм этой фигуры и порядок точек форм. |
| [transform(transform)](#transform_transform_7) | Применяет указанное преобразование к фигуре. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Инициализирует новый экземпляр класса Figure.

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Добавляет форму к фигуре.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | Форма для добавления. |

### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Добавляет диапазон форм к фигуре.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | Формы для добавления. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


```
 get_bounds(matrix) 
```

Получает границы объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Матрица, применяемая перед вычислением границ, будет рассчитана. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Оценочные границы объекта. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


```
 get_bounds(matrix, pen) 
```

Получает границы объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Матрица, применяемая перед вычислением границ, будет рассчитана. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Перо, используемое для объекта. Это может влиять на размер границ объекта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Оценочные границы объекта. |


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Удаляет форму из фигуры.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | Форма для удаления. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Удаляет диапазон форм из фигуры.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | Диапазон форм для удаления. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

Применяет указанное преобразование к фигуре.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Преобразование для применения. |

