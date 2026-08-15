---
title: "Класс Pen"
type: docs
weight: 3360
url: /ru/python-net/aspose.psd/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Pen

**Inheritance:** TransparencySupporter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Создаёт новый экземпляр класса [Pen](/psd/python-net/aspose.psd/pen/) с указанным [Pen.brush](/psd/python-net/aspose.psd/pen/). |
| [Pen(brush, width)](#Pen_brush_width_2) | Создаёт новый экземпляр класса [Pen](/psd/python-net/aspose.psd/pen/) с указанными [Pen.brush](/psd/python-net/aspose.psd/pen/) и [Pen.width](/psd/python-net/aspose.psd/pen/). |
| [Pen(color)](#Pen_color_3) | Создаёт новый экземпляр класса [Pen](/psd/python-net/aspose.psd/pen/) с указанным цветом. |
| [Pen(color, width)](#Pen_color_width_4) | Создаёт новый экземпляр класса [Pen](/psd/python-net/aspose.psd/pen/) с указанными свойствами [Pen.color](/psd/python-net/aspose.psd/pen/) и [Pen.width](/psd/python-net/aspose.psd/pen/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/psd/python-net/aspose.psd/penalignment) | r/w | Получает или задаёт выравнивание для этого [Pen](/psd/python-net/aspose.psd/pen/). |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | r/w | Получает или задает [Pen.brush](/psd/python-net/aspose.psd/pen/), определяющий атрибуты этого [Pen](/psd/python-net/aspose.psd/pen/). |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает или задает цвет этого [Pen](/psd/python-net/aspose.psd/pen/). |
| compound_array | float | r/w | Получает или задает массив значений, определяющих составную ручку. Составная ручка рисует составную линию, состоящую из параллельных линий и промежутков. |
| custom_end_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Получает или задает пользовательскую заглушку, используемую в конце линий, нарисованных этой [Pen](/psd/python-net/aspose.psd/pen/). |
| custom_start_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Получает или задает пользовательскую заглушку, используемую в начале линий, нарисованных этой [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | r/w | Получает или задает стиль заглушки, используемый в конце штрихов, составляющих пунктирные линии, нарисованные этой [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_offset | float | r/w | Получает или задает расстояние от начала линии до начала шаблона штрихов. |
| dash_pattern | float | r/w | Получает или задает массив пользовательских штрихов и пробелов. |
| dash_style | [DashStyle](/psd/python-net/aspose.psd/dashstyle) | r/w | Получает или задает стиль, используемый для пунктирных линий, нарисованных этой [Pen](/psd/python-net/aspose.psd/pen/). |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Получает или задает стиль заглушки, используемый в конце линий, нарисованных этой [Pen](/psd/python-net/aspose.psd/pen/). |
| line_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Получает или задает стиль соединения концов двух последовательных линий, нарисованных этой [Pen](/psd/python-net/aspose.psd/pen/). |
| miter_limit | float | r/w | Получает или задает предел толщины соединения на скошенном угле. |
| opacity | float | r/w | Получает или задает непрозрачность объекта. Значение должно быть от 0 до 1. Значение 0 означает, что объект полностью видим, значение 1 означает, что объект полностью непрозрачный. |
| pen_type | [PenType](/psd/python-net/aspose.psd/pentype) | r | Получает стиль линий, нарисованных этой [Pen](/psd/python-net/aspose.psd/pen/). |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Получает или задает стиль заглушки, используемый в начале линий, нарисованных этой [Pen](/psd/python-net/aspose.psd/pen/). |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Получает или задает копию геометрического преобразования для этой [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | r/w | Получает или задает ширину этой [Pen](/psd/python-net/aspose.psd/pen/), в единицах объекта Graphics, используемого для рисования. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [multiply_transform(matrix)](#multiply_transform_matrix_1) | Умножает матрицу преобразования для этой [Pen](/psd/python-net/aspose.psd/pen/) на указанную [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_2) | Умножает матрицу преобразования для этой [Pen](/psd/python-net/aspose.psd/pen/) на указанную [Matrix](/psd/python-net/aspose.psd/matrix/) в заданном порядке. |
| reset_transform() | Сбрасывает матрицу геометрического преобразования для этой [Pen](/psd/python-net/aspose.psd/pen/) к единичной. |
| [rotate_transform(angle)](#rotate_transform_angle_3) | Поворачивает локальное геометрическое преобразование на указанный угол. Этот метод добавляет вращение в начало преобразования. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_4) | Поворачивает локальное геометрическое преобразование на указанный угол в заданном порядке. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_5) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты. Этот метод добавляет матрицу масштабирования в начало преобразования. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_6) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты в указанном порядке. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_7) | Устанавливает значения, определяющие стиль окончания, используемый для завершения линий, нарисованных этим [Pen](/psd/python-net/aspose.psd/pen/). |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Перемещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Создаёт новый экземпляр класса [Pen](/psd/python-net/aspose.psd/pen/) с указанным [Pen.brush](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Pen.brush](/psd/python-net/aspose.psd/pen/) определяет свойства заливки этого [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Создаёт новый экземпляр класса [Pen](/psd/python-net/aspose.psd/pen/) с указанными [Pen.brush](/psd/python-net/aspose.psd/pen/) и [Pen.width](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Pen.brush](/psd/python-net/aspose.psd/pen/) определяет характеристики этого [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | Ширина нового [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Создаёт новый экземпляр класса [Pen](/psd/python-net/aspose.psd/pen/) с указанным цветом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Структура [Pen.color](/psd/python-net/aspose.psd/pen/), указывающая цвет этого [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Создаёт новый экземпляр класса [Pen](/psd/python-net/aspose.psd/pen/) с указанными свойствами [Pen.color](/psd/python-net/aspose.psd/pen/) и [Pen.width](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Структура [Pen.color](/psd/python-net/aspose.psd/pen/), указывающая цвет этого [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | Значение, указывающее ширину этого [Pen](/psd/python-net/aspose.psd/pen/). |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_1}


```
 multiply_transform(matrix) 
```

Умножает матрицу преобразования для этой [Pen](/psd/python-net/aspose.psd/pen/) на указанную [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Объект [Matrix](/psd/python-net/aspose.psd/matrix/), которым умножается матрица преобразования. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_2}


```
 multiply_transform(matrix, order) 
```

Умножает матрицу преобразования для этой [Pen](/psd/python-net/aspose.psd/pen/) на указанную [Matrix](/psd/python-net/aspose.psd/matrix/) в заданном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/), которым умножается матрица преобразования. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Порядок, в котором выполняется операция умножения. |

### Method: rotate_transform(angle) {#rotate_transform_angle_3}


```
 rotate_transform(angle) 
```

Поворачивает локальное геометрическое преобразование на указанный угол. Этот метод добавляет вращение в начало преобразования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_4}


```
 rotate_transform(angle, order) 
```

Поворачивает локальное геометрическое преобразование на указанный угол в заданном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), определяющий, добавлять ли матрицу вращения в конец или в начало. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_5}


```
 scale_transform(sx, sy) 
```

Масштабирует локальное геометрическое преобразование на указанные коэффициенты. Этот метод добавляет матрицу масштабирования в начало преобразования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Коэффициент, на который масштабируется преобразование по оси x. |
| sy | float | Коэффициент, на который масштабируется преобразование по оси y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_6}


```
 scale_transform(sx, sy, order) 
```

Масштабирует локальное геометрическое преобразование на указанные коэффициенты в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Коэффициент, на который масштабируется преобразование по оси x. |
| sy | float | Коэффициент, на который масштабируется преобразование по оси y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), определяющий, добавлять ли матрицу масштабирования в конец или в начало. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_7}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Устанавливает значения, определяющие стиль окончания, используемый для завершения линий, нарисованных этим [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | [LineCap](/psd/python-net/aspose.psd/linecap/) представляет стиль окончания, используемый в начале линий, нарисованных этим [Pen](/psd/python-net/aspose.psd/pen/). |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | [LineCap](/psd/python-net/aspose.psd/linecap/) представляет стиль окончания, используемый в конце линий, нарисованных этим [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | [LineCap](/psd/python-net/aspose.psd/linecap/) представляет стиль окончания, используемый в начале или в конце пунктирных линий, нарисованных этим [Pen](/psd/python-net/aspose.psd/pen/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Перемещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Порядок (добавление в начало или в конец), в котором применять трансляцию. |

