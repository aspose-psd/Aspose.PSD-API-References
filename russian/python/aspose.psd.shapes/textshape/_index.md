---
title: "Класс TextShape"
type: docs
weight: 90
url: /ru/python-net/aspose.psd.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.TextShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [TextShape()](#TextShape__1) | Инициализирует новый экземпляр класса [TextShape](/psd/python-net/aspose.psd.shapes/textshape/). |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | Инициализирует новый экземпляр класса [TextShape](/psd/python-net/aspose.psd.shapes/textshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Получает границы объекта. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Получает центр фигуры. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | r/w | Получает или задает шрифт, используемый для отрисовки текста. |
| has_segments | bool | r | Получает значение, указывающее, имеет ли фигура сегменты. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Получает левую нижнюю точку прямоугольника. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Получает левую верхнюю точку прямоугольника. |
| rectangle_height | double | r | Получает высоту прямоугольника. |
| rectangle_width | double | r | Получает ширину прямоугольника. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Получает правую нижнюю точку прямоугольника. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Получает правую верхнюю точку прямоугольника. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Получает сегменты фигуры. |
| text | string | r/w | Получает или задает отрисованный текст. |
| text_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r/w | Получает или задает формат текста. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Получает границы объекта. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Получает границы объекта. |
| [transform(transform)](#transform_transform_3) | Применяет указанное преобразование к фигуре. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

Инициализирует новый экземпляр класса [TextShape](/psd/python-net/aspose.psd.shapes/textshape/).

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

Инициализирует новый экземпляр класса [TextShape](/psd/python-net/aspose.psd.shapes/textshape/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string | Текст для отрисовки. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Прямоугольник текста. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Шрифт для использования. |
| string_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | Формат строки. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


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


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Применяет указанное преобразование к фигуре.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Преобразование для применения. |

