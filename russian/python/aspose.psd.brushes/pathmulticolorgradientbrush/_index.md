---
title: "Класс PathMulticolorGradientBrush"
type: docs
weight: 70
url: /ru/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathMulticolorGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PathMulticolorGradientBrush(path)](#PathMulticolorGradientBrush_path_1) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) с указанным путем. |
| [PathMulticolorGradientBrush(points)](#PathMulticolorGradientBrush_points_2) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) с указанными точками. |
| [PathMulticolorGradientBrush(points)](#PathMulticolorGradientBrush_points_3) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) с указанными точками. |
| [PathMulticolorGradientBrush(points, wrap_mode)](#PathMulticolorGradientBrush_points_wrap_mode_4) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) с указанными точками и режимом обтекания. |
| [PathMulticolorGradientBrush(points, wrap_mode)](#PathMulticolorGradientBrush_points_wrap_mode_5) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) с указанными точками и режимом обтекания. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Получает или задает центральную точку градиента пути. |
| освобождено | bool | r | Получает значение, указывающее, освобожден ли данный экземпляр. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Получает или задает точку фокуса для затухания градиента. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | Получает графический путь, на котором построена эта кисть. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Получает или задаёт [ColorBlend](/psd/python-net/aspose.psd/colorblend/), определяющий многокрасочный линейный градиент. |
| is_transform_changed | bool | r | Получает значение, указывающее, были ли преобразования изменены каким-либо образом. Например, установка матрицы преобразования или<br/>            вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| opacity | float | r/w | Получает или задаёт непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | Получает точки пути, на котором построена эта кисть. |
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
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Смещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |


### Constructor: PathMulticolorGradientBrush(path) {#PathMulticolorGradientBrush_path_1}


```
 PathMulticolorGradientBrush(path) 
```

Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) с указанным путем.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Объект [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), определяющий область, заполняемую этим [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/). |

### Constructor: PathMulticolorGradientBrush(points) {#PathMulticolorGradientBrush_points_2}


```
 PathMulticolorGradientBrush(points) 
```

Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) с указанными точками.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих точки, образующие вершины пути. |

### Constructor: PathMulticolorGradientBrush(points) {#PathMulticolorGradientBrush_points_3}


```
 PathMulticolorGradientBrush(points) 
```

Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) с указанными точками.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих точки, образующие вершины пути. |

### Constructor: PathMulticolorGradientBrush(points, wrap_mode) {#PathMulticolorGradientBrush_points_wrap_mode_4}


```
 PathMulticolorGradientBrush(points, wrap_mode) 
```

Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) с указанными точками и режимом обтекания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих точки, образующие вершины пути. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Объект [WrapMode](/psd/python-net/aspose.psd/wrapmode/), определяющий способ чередования заливок, выполненных с помощью этого [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/). |

### Constructor: PathMulticolorGradientBrush(points, wrap_mode) {#PathMulticolorGradientBrush_points_wrap_mode_5}


```
 PathMulticolorGradientBrush(points, wrap_mode) 
```

Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) с указанными точками и режимом обтекания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих точки, образующие вершины пути. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Объект [WrapMode](/psd/python-net/aspose.psd/wrapmode/), определяющий способ чередования заливок, выполненных с помощью этого [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/). |

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

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Смещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


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

