---
title: "Класс LinearGradientBrush"
type: docs
weight: 20
url: /ru/python-net/aspose.psd.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | Инициализирует новый экземпляр класса [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) с параметрами по умолчанию.<br/>            Начальный цвет — черный, конечный цвет — белый, угол — 45 градусов, а прямоугольник расположен в (0,0) размером (1,1). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | Инициализирует новый экземпляр класса [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) с указанными точками и цветами. |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | Инициализирует новый экземпляр класса [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) с указанными точками и цветами. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | Инициализирует новый экземпляр класса [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) на основе прямоугольника, начального и конечного цветов и угла ориентации. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | Инициализирует новый экземпляр класса [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) на основе прямоугольника, начального и конечного цветов и угла ориентации. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | Инициализирует новый экземпляр класса [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) на основе прямоугольника, начального и конечного цветов и угла ориентации. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | Инициализирует новый экземпляр класса [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) на основе прямоугольника, начального и конечного цветов и угла ориентации. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| угол | float | r/w | Получает или задаёт угол градиента. |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Получает или задает [Blend](/psd/python-net/aspose.psd/blend/), который определяет позиции и коэффициенты, задающие пользовательское затухание градиента. |
| освобождено | bool | r | Получает значение, указывающее, освобожден ли данный экземпляр. |
| end_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает или задает конечный цвет градиента. |
| gamma_correction | bool | r/w | Получает или задаёт значение, указывающее, включена ли гамма‑коррекция для этого [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Получает или задаёт [ColorBlend](/psd/python-net/aspose.psd/colorblend/), определяющий многокрасочный линейный градиент. |
| is_angle_scalable | bool | r/w | Получает или задаёт значение, указывающее, изменяется ли [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) во время преобразований с этим [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | Получает значение, указывающее, были ли преобразования изменены каким-либо образом. Например, установка матрицы преобразования или<br/>            вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| linear_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Получает или задает начальный и конечный цвета градиента. |
| opacity | float | r/w | Получает или задаёт непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | Получает или задаёт прямоугольную область, определяющую начальную и конечную точки градиента. |
| start_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает или задает начальный цвет градиента. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Получает или задаёт копию [Matrix](/psd/python-net/aspose.psd/matrix/), определяющую локальное геометрическое преобразование для этого [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Получает или задаёт перечисление [WrapMode](/psd/python-net/aspose.psd/wrapmode/), указывающее режим обтекания для этого [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Создаёт новую глубокую копию текущего [Brush](/psd/python-net/aspose.psd/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Умножает [Matrix](/psd/python-net/aspose.psd/matrix/), представляющую локальное геометрическое преобразование этого [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/), на указанную [Matrix](/psd/python-net/aspose.psd/matrix/), предварительно добавляя указанную [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Умножает [Matrix](/psd/python-net/aspose.psd/matrix/), представляющую локальное геометрическое преобразование этого [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/), на указанную [Matrix](/psd/python-net/aspose.psd/matrix/) в указанном порядке. |
| reset_transform() | Сбрасывает свойство [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) к единичному. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет вращение в начало преобразования. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Масштабирует локальное геометрическое преобразование на указанные значения. Этот метод добавляет матрицу масштабирования в начало преобразования. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Масштабирует локальное геометрическое преобразование на указанные значения в указанном порядке. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Создает линейный градиент с центральным цветом и линейным затуханием к одному цвету с обеих сторон. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Создает линейный градиент с центральным цветом и линейным затуханием к одному цвету с обеих сторон. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Создает затухание градиента, основанное на колоколообразной кривой. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Создает затухание градиента, основанное на колоколообразной кривой. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Смещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) с параметрами по умолчанию.<br/>            Начальный цвет — черный, конечный цвет — белый, угол — 45 градусов, а прямоугольник расположен в (0,0) размером (1,1).

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) с указанными точками и цветами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Структура [Point](/psd/python-net/aspose.psd/point/), представляющая начальную точку линейного градиента. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Структура [Point](/psd/python-net/aspose.psd/point/), представляющая конечную точку линейного градиента. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Структура [Color](/psd/python-net/aspose.psd/color/), представляющая начальный цвет линейного градиента. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Структура [Color](/psd/python-net/aspose.psd/color/), представляющая конечный цвет линейного градиента. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) с указанными точками и цветами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Структура [Point](/psd/python-net/aspose.psd/point/), представляющая начальную точку линейного градиента. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Структура [Point](/psd/python-net/aspose.psd/point/), представляющая конечную точку линейного градиента. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Структура [Color](/psd/python-net/aspose.psd/color/), представляющая начальный цвет линейного градиента. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Структура [Color](/psd/python-net/aspose.psd/color/), представляющая конечный цвет линейного градиента. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) на основе прямоугольника, начального и конечного цветов и угла ориентации.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), определяющая границы линейного градиента. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Структура [Color](/psd/python-net/aspose.psd/color/), представляющая начальный цвет градиента. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Структура [Color](/psd/python-net/aspose.psd/color/) представляет конечный цвет градиента. |
| угол | float | Угол, измеряемый в градусах по часовой стрелке от оси x, линии ориентации градиента. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) на основе прямоугольника, начального и конечного цветов и угла ориентации.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), определяющая границы линейного градиента. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Структура [Color](/psd/python-net/aspose.psd/color/), представляющая начальный цвет градиента. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Структура [Color](/psd/python-net/aspose.psd/color/) представляет конечный цвет градиента. |
| угол | float | Угол, измеряемый в градусах по часовой стрелке от оси x, линии ориентации градиента. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) на основе прямоугольника, начального и конечного цветов и угла ориентации.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), определяющая границы линейного градиента. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Структура [Color](/psd/python-net/aspose.psd/color/), представляющая начальный цвет градиента. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Структура [Color](/psd/python-net/aspose.psd/color/) представляет конечный цвет градиента. |
| угол | float | Угол, измеряемый в градусах по часовой стрелке от оси x, линии ориентации градиента. |
| is_angle_scalable | bool | если установлено в <c>true</c>, угол изменяется во время преобразований с помощью этого [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/). |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) на основе прямоугольника, начального и конечного цветов и угла ориентации.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), определяющая границы линейного градиента. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Структура [Color](/psd/python-net/aspose.psd/color/), представляющая начальный цвет градиента. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Структура [Color](/psd/python-net/aspose.psd/color/) представляет конечный цвет градиента. |
| угол | float | Угол, измеряемый в градусах по часовой стрелке от оси x, линии ориентации градиента. |
| is_angle_scalable | bool | если установлено в <c>true</c>, угол изменяется во время преобразований с помощью этого [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Создаёт новую глубокую копию текущего [Brush](/psd/python-net/aspose.psd/brush/).

**Returns**

| Тип | Описание |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | Новый [Brush](/psd/python-net/aspose.psd/brush/), являющийся глубоким клоном данного экземпляра [Brush](/psd/python-net/aspose.psd/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Умножает [Matrix](/psd/python-net/aspose.psd/matrix/), представляющую локальное геометрическое преобразование этого [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/), на указанную [Matrix](/psd/python-net/aspose.psd/matrix/), предварительно добавляя указанную [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/), используемая для умножения геометрического преобразования. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Умножает [Matrix](/psd/python-net/aspose.psd/matrix/), представляющую локальное геометрическое преобразование этого [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/), на указанную [Matrix](/psd/python-net/aspose.psd/matrix/) в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/), используемая для умножения геометрического преобразования. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), определяющий порядок умножения двух матриц. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет вращение в начало преобразования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), определяющий, добавлять ли матрицу вращения в конец или в начало. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Масштабирует локальное геометрическое преобразование на указанные значения. Этот метод добавляет матрицу масштабирования в начало преобразования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Величина масштабирования преобразования по оси x. |
| sy | float | Величина масштабирования преобразования по оси y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Масштабирует локальное геометрическое преобразование на указанные значения в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Величина масштабирования преобразования по оси x. |
| sy | float | Величина масштабирования преобразования по оси y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), определяющий, добавлять ли матрицу масштабирования в конец или в начало. |

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_8}


```
 set_blend_triangular_shape(focus) 
```

Создает линейный градиент с центральным цветом и линейным затуханием к одному цвету с обеих сторон.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| фокус | float | Значение от 0 до 1, указывающее центр градиента (точка, где градиент состоит только из конечного цвета). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Создает линейный градиент с центральным цветом и линейным затуханием к одному цвету с обеих сторон.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| фокус | float | Значение от 0 до 1, указывающее центр градиента (точка, где градиент состоит только из конечного цвета). |
| scale | float | Значение от 0 до 1, указывающее, как быстро цвета переходят от начального цвета к <paramref name=\"focus\" /> (конечному цвету). |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Создает затухание градиента, основанное на колоколообразной кривой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| фокус | float | Значение от 0 до 1, указывающее центр градиента (точка, где начальный и конечный цвета смешаны поровну). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Создает затухание градиента, основанное на колоколообразной кривой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| фокус | float | Значение от 0 до 1, указывающее центр градиента (точка, где градиент состоит только из конечного цвета). |
| scale | float | Значение от 0 до 1, указывающее, как быстро цвета переходят от <paramref name=\"focus\" />. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Смещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Порядок (добавление в начало или в конец), в котором применять трансляцию. |

