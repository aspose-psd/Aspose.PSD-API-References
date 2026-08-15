---
title: "Класс PathGradientBrush"
type: docs
weight: 50
url: /ru/python-net/aspose.psd.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | Инициализирует новый экземпляр класса [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) с указанным путем. |
| [PathGradientBrush(points)](#PathGradientBrush_points_2) | Инициализирует новый экземпляр класса [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) с указанными точками. |
| [PathGradientBrush(points)](#PathGradientBrush_points_3) | Инициализирует новый экземпляр класса [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) с указанными точками. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_4) | Инициализирует новый экземпляр класса [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) с указанными точками и режимом обтекания. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_5) | Инициализирует новый экземпляр класса [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) с указанными точками и режимом обтекания. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Получает или задает [Blend](/psd/python-net/aspose.psd/blend/), который определяет позиции и коэффициенты, задающие пользовательское затухание градиента. |
| center_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает или задает цвет в центре градиента пути. |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Получает или задает центральную точку градиента пути. |
| освобождено | bool | r | Получает значение, указывающее, освобожден ли данный экземпляр. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Получает или задает точку фокуса для затухания градиента. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | Получает графический путь, на котором построена эта кисть. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Получает или задаёт [ColorBlend](/psd/python-net/aspose.psd/colorblend/), определяющий многокрасочный линейный градиент. |
| is_transform_changed | bool | r | Получает значение, указывающее, были ли преобразования изменены каким-либо образом. Например, установка матрицы преобразования или<br/>            вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| opacity | float | r/w | Получает или задаёт непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | Получает точки пути, на котором построена эта кисть. |
| surround_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Получает или задает массив цветов, соответствующих точкам пути, который заполняет этот [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/). |
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
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Создает градиент с центральным цветом и линейным переходом к одному окружающему цвету. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Создает градиент с центральным цветом и линейным переходом к каждому окружающему цвету. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Создает кисть градиента, изменяющую цвет, начиная от центра пути к его границе. Переход от одного цвета к другому основан на колоколообразной кривой. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Создает кисть градиента, изменяющую цвет, начиная от центра пути к его границе. Переход от одного цвета к другому основан на колоколообразной кривой. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Смещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

Инициализирует новый экземпляр класса [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) с указанным путем.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Графический путь [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) определяет область, заполняемую этой [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/). |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_2}


```
 PathGradientBrush(points) 
```

Инициализирует новый экземпляр класса [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) с указанными точками.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих точки, образующие вершины пути. |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_3}


```
 PathGradientBrush(points) 
```

Инициализирует новый экземпляр класса [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) с указанными точками.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих точки, образующие вершины пути. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_4}


```
 PathGradientBrush(points, wrap_mode) 
```

Инициализирует новый экземпляр класса [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) с указанными точками и режимом обтекания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих точки, образующие вершины пути. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Тип [WrapMode](/psd/python-net/aspose.psd/wrapmode/), определяющий, как заливки, нарисованные этой [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/), мозаично повторяются. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_5}


```
 PathGradientBrush(points, wrap_mode) 
```

Инициализирует новый экземпляр класса [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) с указанными точками и режимом обтекания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих точки, образующие вершины пути. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Тип [WrapMode](/psd/python-net/aspose.psd/wrapmode/), определяющий, как заливки, нарисованные этой [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/), мозаично повторяются. |

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

Создает градиент с центральным цветом и линейным переходом к одному окружающему цвету.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| фокус | float | Значение от 0 до 1, указывающее, где вдоль любого радиала от центра пути к его границе центральный цвет будет иметь наивысшую интенсивность. Значение 1 (по умолчанию) размещает наивысшую интенсивность в центре пути. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Создает градиент с центральным цветом и линейным переходом к каждому окружающему цвету.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| фокус | float | Значение от 0 до 1, указывающее, где вдоль любого радиала от центра пути к его границе центральный цвет будет иметь наивысшую интенсивность. Значение 1 (по умолчанию) размещает наивысшую интенсивность в центре пути. |
| scale | float | Значение от 0 до 1, указывающее максимальную интенсивность центрального цвета, смешиваемого с цветом границы. Значение 1 приводит к максимальной возможной интенсивности центрального цвета и является значением по умолчанию. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Создает кисть градиента, изменяющую цвет, начиная от центра пути к его границе. Переход от одного цвета к другому основан на колоколообразной кривой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| фокус | float | Значение от 0 до 1, указывающее, где вдоль любого радиала от центра пути к его границе центральный цвет будет иметь наивысшую интенсивность. Значение 1 (по умолчанию) размещает наивысшую интенсивность в центре пути. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Создает кисть градиента, изменяющую цвет, начиная от центра пути к его границе. Переход от одного цвета к другому основан на колоколообразной кривой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| фокус | float | Значение от 0 до 1, указывающее, где вдоль любого радиала от центра пути к его границе центральный цвет будет иметь наивысшую интенсивность. Значение 1 (по умолчанию) размещает наивысшую интенсивность в центре пути. |
| scale | float | Значение от 0 до 1, указывающее максимальную интенсивность центрального цвета, смешиваемого с цветом границы. Значение 1 приводит к максимальной возможной интенсивности центрального цвета и является значением по умолчанию. |

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

