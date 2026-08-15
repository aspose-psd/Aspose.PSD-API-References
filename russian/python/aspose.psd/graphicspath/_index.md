---
title: "GraphicsPath Класс"
type: docs
weight: 1570
url: /ru/python-net/aspose.psd/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Инициализирует новый экземпляр класса [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Инициализирует новый экземпляр класса [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Инициализирует новый экземпляр класса [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Инициализирует новый экземпляр класса [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Получает или задает границы объекта. |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | r | Получает фигуры пути. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | r/w | Получает или задает перечисление [FillMode](/psd/python-net/aspose.psd/fillmode/), которое определяет, как заполняются внутренние области фигур в этом [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Добавляет новую фигуру. |
| [add_figures(figures)](#add_figures_figures_2) | Добавляет новые фигуры. |
| [add_path(adding_path)](#add_path_adding_path_3) | Добавляет указанный [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) к этому пути. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Добавляет указанный [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) к этому пути. |
| [deep_clone()](#deep_clone__5) | Выполняет глубокое клонирование этого графического пути. |
| flatten() | Преобразует каждую кривую в этом пути в последовательность соединённых отрезков. |
| [flatten(matrix)](#flatten_matrix_6) | Применяет указанное преобразование, а затем преобразует каждую кривую в этом [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) в последовательность соединённых отрезков. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Преобразует каждую кривую в этом [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) в последовательность соединённых отрезков. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Получает границы объекта. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Получает границы объекта. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/) и использовании указанного [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/) и использовании указанного [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/) и использовании указанного [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/) и использовании указанного [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(point)](#is_visible_point_18) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(point)](#is_visible_point_19) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_20) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_21) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_22) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_23) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_24) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) в видимом области отсечения указанного [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_25) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) в видимом области отсечения указанного [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [remove_figure(figure)](#remove_figure_figure_26) | Удаляет фигуру. |
| [remove_figures(figures)](#remove_figures_figures_27) | Удаляет фигуры. |
| reset() | Очищает графический путь и устанавливает [FillMode](/psd/python-net/aspose.psd/fillmode/) в значение [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| reverse() | Изменяет порядок фигур, форм и точек в каждой форме этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) на обратный. |
| [transform(transform)](#transform_transform_28) | Применяет указанное преобразование к фигуре. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_29) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_30) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_31) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_32) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen)](#widen_pen_33) | Добавляет дополнительный контур к пути. |
| [widen(pen, matrix)](#widen_pen_matrix_34) | Добавляет дополнительный контур к [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_35) | Заменяет этот [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) кривыми, которые охватывают область, заполняемую при отрисовке этого пути указанным пером. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Инициализирует новый экземпляр класса [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Инициализирует новый экземпляр класса [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Фигуры для инициализации. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Инициализирует новый экземпляр класса [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Фигуры для инициализации. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Режим заполнения. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Инициализирует новый экземпляр класса [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Режим заполнения. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Добавляет новую фигуру.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | Фигура для добавления. |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Добавляет новые фигуры.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Фигуры для добавления. |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Добавляет указанный [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) к этому пути.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Элемент [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) для добавления. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Добавляет указанный [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) к этому пути.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Элемент [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) для добавления. |
| соединить | bool | Булево значение, указывающее, является ли первая фигура в добавленном пути частью последней фигуры в этом пути. Значение true указывает, что первая фигура в добавленном пути является частью последней фигуры в этом пути. Значение false указывает, что первая фигура в добавленном пути отдельна от последней фигуры в этом пути. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Выполняет глубокое клонирование этого графического пути.

**Returns**

| Тип | Описание |
| :- | :- |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Глубокая копия графического пути. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Применяет указанное преобразование, а затем преобразует каждую кривую в этом [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) в последовательность соединённых отрезков.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Матрица [Matrix](/psd/python-net/aspose.psd/matrix/) для преобразования этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) перед уплощением. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Преобразует каждую кривую в этом [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) в последовательность соединённых отрезков.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Матрица [Matrix](/psd/python-net/aspose.psd/matrix/) для преобразования этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) перед уплощением. |
| уплощённость | float | Указывает максимальную допустимую ошибку между кривой и её уплощённым приближением. Значение 0.25 является значением по умолчанию. Уменьшение значения уплощённости увеличит количество отрезков линии в приближении. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


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


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Точка [PointF](/psd/python-net/aspose.psd/pointf/) указывает расположение для проверки. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Карандаш [Pen](/psd/python-net/aspose.psd/pen/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/); в противном случае false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Точка [PointF](/psd/python-net/aspose.psd/pointf/) указывает расположение для проверки. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Карандаш [Pen](/psd/python-net/aspose.psd/pen/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/); в противном случае false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/) и использовании указанного [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Точка [PointF](/psd/python-net/aspose.psd/pointf/) указывает расположение для проверки. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Карандаш [Pen](/psd/python-net/aspose.psd/pen/) для проверки. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Графика [Graphics](/psd/python-net/aspose.psd/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/); в противном случае false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/) и использовании указанного [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Точка [PointF](/psd/python-net/aspose.psd/pointf/) указывает расположение для проверки. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Карандаш [Pen](/psd/python-net/aspose.psd/pen/) для проверки. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Графика [Graphics](/psd/python-net/aspose.psd/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/); в противном случае false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Карандаш [Pen](/psd/python-net/aspose.psd/pen/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/); в противном случае false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Карандаш [Pen](/psd/python-net/aspose.psd/pen/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/); в противном случае false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/) и использовании указанного [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Карандаш [Pen](/psd/python-net/aspose.psd/pen/) для проверки. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Графика [Graphics](/psd/python-net/aspose.psd/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/); в противном случае false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/) и использовании указанного [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Карандаш [Pen](/psd/python-net/aspose.psd/pen/) для проверки. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Графика [Graphics](/psd/python-net/aspose.psd/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри (под) контура этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) при отрисовке указанным [Pen](/psd/python-net/aspose.psd/pen/); в противном случае false. |


### Method: is_visible(point) {#is_visible_point_18}


```
 is_visible(point) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Точка [PointF](/psd/python-net/aspose.psd/pointf/) представляет проверяемую точку. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); в противном случае false. |


### Method: is_visible(point) {#is_visible_point_19}


```
 is_visible(point) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Точка [PointF](/psd/python-net/aspose.psd/pointf/) представляет проверяемую точку. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); в противном случае false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_20}


```
 is_visible(pt, graphics) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Точка [PointF](/psd/python-net/aspose.psd/pointf/) представляет проверяемую точку. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Графика [Graphics](/psd/python-net/aspose.psd/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри этого; в противном случае false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_21}


```
 is_visible(pt, graphics) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Точка [PointF](/psd/python-net/aspose.psd/pointf/) представляет проверяемую точку. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Графика [Graphics](/psd/python-net/aspose.psd/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри этого; в противном случае false. |


### Method: is_visible(x, y) {#is_visible_x_y_22}


```
 is_visible(x, y) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); в противном случае false. |


### Method: is_visible(x, y) {#is_visible_x_y_23}


```
 is_visible(x, y) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); в противном случае false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_24}


```
 is_visible(x, y, graphics) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) в видимом области отсечения указанного [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Графика [Graphics](/psd/python-net/aspose.psd/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); в противном случае false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_25}


```
 is_visible(x, y, graphics) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) в видимом области отсечения указанного [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Графика [Graphics](/psd/python-net/aspose.psd/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри этого [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); в противном случае false. |


### Method: remove_figure(figure) {#remove_figure_figure_26}


```
 remove_figure(figure) 
```

Удаляет фигуру.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | Фигура для удаления. |

### Method: remove_figures(figures) {#remove_figures_figures_27}


```
 remove_figures(figures) 
```

Удаляет фигуры.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Фигуры для удаления. |

### Method: transform(transform) {#transform_transform_28}


```
 transform(transform) 
```

Применяет указанное преобразование к фигуре.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Преобразование для применения. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_29}


```
 warp(dest_points, src_rect) 
```

Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/) определяющих параллелограмм, в который преобразуется прямоугольник, определённый <paramref name="srcRect" />. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Прямоугольник [RectangleF](/psd/python-net/aspose.psd/rectanglef/) представляет прямоугольник, преобразуемый в параллелограмм, определённый <paramref name="destPoints" />. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_30}


```
 warp(dest_points, src_rect, matrix) 
```

Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/) определяющих параллелограмм, в который преобразуется прямоугольник, определённый <paramref name="srcRect" />. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Прямоугольник [RectangleF](/psd/python-net/aspose.psd/rectanglef/) представляет прямоугольник, преобразуемый в параллелограмм, определённый <paramref name="destPoints" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Матрица [Matrix](/psd/python-net/aspose.psd/matrix/) указывает геометрическое преобразование, применяемое к пути. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_31}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/) определяющих параллелограмм, в который преобразуется прямоугольник, определённый <paramref name="srcRect" />. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Прямоугольник [RectangleF](/psd/python-net/aspose.psd/rectanglef/) представляет прямоугольник, преобразуемый в параллелограмм, определённый <paramref name="destPoints" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Матрица [Matrix](/psd/python-net/aspose.psd/matrix/) указывает геометрическое преобразование, применяемое к пути. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Перечисление [WarpMode](/psd/python-net/aspose.psd/warpmode/) указывает, использует ли данная операция искажения перспективный или билинейный режим. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_32}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/) определяющих параллелограмм, в который преобразуется прямоугольник, определённый <paramref name="srcRect" />. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Прямоугольник [RectangleF](/psd/python-net/aspose.psd/rectanglef/) представляет прямоугольник, преобразуемый в параллелограмм, определённый <paramref name="destPoints" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Матрица [Matrix](/psd/python-net/aspose.psd/matrix/) указывает геометрическое преобразование, применяемое к пути. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Перечисление [WarpMode](/psd/python-net/aspose.psd/warpmode/) указывает, использует ли данная операция искажения перспективный или билинейный режим. |
| flatness | float | Значение от 0 до 1, указывающее, насколько плоским является полученный путь. Для получения дополнительной информации см. методы [GraphicsPath.flatten()](/psd/python-net/aspose.psd/graphicspath/) . |

### Method: widen(pen) {#widen_pen_33}


```
 widen(pen) 
```

Добавляет дополнительный контур к пути.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Карандаш [Pen](/psd/python-net/aspose.psd/pen/) указывает ширину между оригинальным контуром пути и новым контуром, создаваемым этим методом. |

### Method: widen(pen, matrix) {#widen_pen_matrix_34}


```
 widen(pen, matrix) 
```

Добавляет дополнительный контур к [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Карандаш [Pen](/psd/python-net/aspose.psd/pen/) указывает ширину между оригинальным контуром пути и новым контуром, создаваемым этим методом. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Матрица [Matrix](/psd/python-net/aspose.psd/matrix/) указывает преобразование, применяемое к пути перед расширением. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_35}


```
 widen(pen, matrix, flatness) 
```

Заменяет этот [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) кривыми, которые охватывают область, заполняемую при отрисовке этого пути указанным пером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Карандаш [Pen](/psd/python-net/aspose.psd/pen/) указывает ширину между оригинальным контуром пути и новым контуром, создаваемым этим методом. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Матрица [Matrix](/psd/python-net/aspose.psd/matrix/) указывает преобразование, применяемое к пути перед расширением. |
| уплощённость | float | Значение, определяющее гладкость кривых. |

