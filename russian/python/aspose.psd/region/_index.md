---
title: "Класс Region"
type: docs
weight: 3870
url: /ru/python-net/aspose.psd/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Region

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Region()](#Region__1) | Инициализирует новый [Region](/psd/python-net/aspose.psd/region/). |
| [Region(path)](#Region_path_2) | Инициализирует новый [Region](/psd/python-net/aspose.psd/region/) с указанным [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [Region(rect)](#Region_rect_3) | Инициализирует новый [Region](/psd/python-net/aspose.psd/region/) из указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [Region(rect)](#Region_rect_4) | Инициализирует новый [Region](/psd/python-net/aspose.psd/region/) из указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [complement(path)](#complement_path_1) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), чтобы включить часть указанного [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), которая не пересекается с этим [Region](/psd/python-net/aspose.psd/region/). |
| [complement(rect)](#complement_rect_2) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), чтобы включить часть указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/), которая не пересекается с этим [Region](/psd/python-net/aspose.psd/region/). |
| [complement(rect)](#complement_rect_3) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), чтобы включить часть указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/), которая не пересекается с этим [Region](/psd/python-net/aspose.psd/region/). |
| [complement(region)](#complement_region_4) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), чтобы включить часть указанного [Region](/psd/python-net/aspose.psd/region/), которая не пересекается с этим [Region](/psd/python-net/aspose.psd/region/). |
| [deep_clone()](#deep_clone__5) | Создаёт точную глубокую копию этого [Region](/psd/python-net/aspose.psd/region/). |
| [exclude(path)](#exclude_path_6) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), чтобы включить только ту часть его внутренней области, которая не пересекается с указанным [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [exclude(rect)](#exclude_rect_7) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), чтобы включить только ту часть его внутренней области, которая не пересекается с указанной структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [exclude(rect)](#exclude_rect_8) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), чтобы включить только ту часть его внутренней области, которая не пересекается с указанной структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [exclude(region)](#exclude_region_9) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), чтобы включить только ту часть его внутренней области, которая не пересекается с указанным [Region](/psd/python-net/aspose.psd/region/). |
| [intersect(path)](#intersect_path_10) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), до пересечения с указанным [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [intersect(rect)](#intersect_rect_11) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), до пересечения с указанной структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [intersect(rect)](#intersect_rect_12) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), до пересечения с указанной структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [intersect(region)](#intersect_region_13) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), до пересечения с указанным [Region](/psd/python-net/aspose.psd/region/). |
| [is_empty(g)](#is_empty_g_14) | Проверяет, имеет ли этот [Region](/psd/python-net/aspose.psd/region/) пустую внутреннюю область на указанной поверхности рисования. |
| [is_infinite(g)](#is_infinite_g_15) | Проверяет, имеет ли этот [Region](/psd/python-net/aspose.psd/region/) бесконечную внутреннюю область на указанной поверхности рисования. |
| [is_visible(point)](#is_visible_point_16) | Проверяет, содержится ли указанная структура [PointF](/psd/python-net/aspose.psd/pointf/) внутри этого [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(point)](#is_visible_point_17) | Проверяет, содержится ли указанная структура [PointF](/psd/python-net/aspose.psd/pointf/) внутри этого [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(point, g)](#is_visible_point_g_18) | Проверяет, содержится ли указанная структура [PointF](/psd/python-net/aspose.psd/pointf/) внутри этого [Region](/psd/python-net/aspose.psd/region/) при отрисовке с использованием указанного [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(point, g)](#is_visible_point_g_19) | Проверяет, содержится ли указанная структура [PointF](/psd/python-net/aspose.psd/pointf/) внутри этого [Region](/psd/python-net/aspose.psd/region/) при отрисовке с использованием указанного [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(rect)](#is_visible_rect_20) | Проверяет, содержится ли какая-либо часть указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/) внутри этого [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(rect)](#is_visible_rect_21) | Проверяет, содержится ли какая-либо часть указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/) внутри этого [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(rect, g)](#is_visible_rect_g_22) | Проверяет, содержится ли какая-либо часть указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/) внутри этого [Region](/psd/python-net/aspose.psd/region/) при отрисовке с использованием указанного [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(rect, g)](#is_visible_rect_g_23) | Проверяет, содержится ли какая-либо часть указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/) внутри этого [Region](/psd/python-net/aspose.psd/region/) при отрисовке с использованием указанного [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y)](#is_visible_x_y_24) | Проверяет, содержится ли указанная точка внутри этого [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_25) | Проверяет, содержится ли указанная точка внутри этого [Region](/psd/python-net/aspose.psd/region/) при отрисовке с использованием указанного [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_26) | Проверяет, содержится ли указанная точка внутри этого [Region](/psd/python-net/aspose.psd/region/) при отрисовке с использованием указанного [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_27) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_28) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_29) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/psd/python-net/aspose.psd/region/) при отрисовке с использованием указанного [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_30) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/psd/python-net/aspose.psd/region/) при отрисовке с использованием указанного [Graphics](/psd/python-net/aspose.psd/graphics/). |
| make_empty() | Инициализирует этот [Region](/psd/python-net/aspose.psd/region/) пустым внутренним пространством. |
| make_infinite() | Инициализирует объект этого [Region](/psd/python-net/aspose.psd/region/) бесконечным внутренним пространством. |
| [transform(matrix)](#transform_matrix_31) | Преобразует этот [Region](/psd/python-net/aspose.psd/region/) с помощью указанной [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [translate(dx, dy)](#translate_dx_dy_32) | Смещает координаты этого [Region](/psd/python-net/aspose.psd/region/) на указанное значение. |
| [translate(dx, dy)](#translate_dx_dy_33) | Смещает координаты этого [Region](/psd/python-net/aspose.psd/region/) на указанное значение. |
| [union(path)](#union_path_34) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), объединяя его с указанным [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [union(rect)](#union_rect_35) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), объединяя его с указанной структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [union(rect)](#union_rect_36) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), объединяя его с указанной структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [union(region)](#union_region_37) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), объединяя его с указанным [Region](/psd/python-net/aspose.psd/region/). |
| [xor(path)](#xor_path_38) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), объединяя его за вычетом пересечения с указанным [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [xor(rect)](#xor_rect_39) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), объединяя его за вычетом пересечения с указанной структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [xor(rect)](#xor_rect_40) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), объединяя его за вычетом пересечения с указанной структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [xor(region)](#xor_region_41) | Обновляет этот [Region](/psd/python-net/aspose.psd/region/), объединяя его за вычетом пересечения с указанным [Region](/psd/python-net/aspose.psd/region/). |


### Constructor: Region() {#Region__1}


```
 Region() 
```

Инициализирует новый [Region](/psd/python-net/aspose.psd/region/).

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

Инициализирует новый [Region](/psd/python-net/aspose.psd/region/) с указанным [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Объект [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), определяющий новую [Region](/psd/python-net/aspose.psd/region/). |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

Инициализирует новый [Region](/psd/python-net/aspose.psd/region/) из указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), определяющая внутреннее пространство новой [Region](/psd/python-net/aspose.psd/region/). |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

Инициализирует новый [Region](/psd/python-net/aspose.psd/region/) из указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), определяющая внутреннее пространство новой [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), чтобы включить часть указанного [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), которая не пересекается с этим [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Элемент [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), дополняющий этот [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), чтобы включить часть указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/), которая не пересекается с этим [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), дополняющая этот [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), чтобы включить часть указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/), которая не пересекается с этим [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), дополняющая этот [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), чтобы включить часть указанного [Region](/psd/python-net/aspose.psd/region/), которая не пересекается с этим [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Объект [Region](/psd/python-net/aspose.psd/region/), дополняющий этот объект [Region](/psd/python-net/aspose.psd/region/). |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Создаёт точную глубокую копию этого [Region](/psd/python-net/aspose.psd/region/).

**Returns**

| Тип | Описание |
| :- | :- |
| [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/), создаваемый этим методом. |


### Method: exclude(path) {#exclude_path_6}


```
 exclude(path) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), чтобы включить только ту часть его внутренней области, которая не пересекается с указанным [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), исключаемый из этого [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_7}


```
 exclude(rect) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), чтобы включить только ту часть его внутренней области, которая не пересекается с указанной структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), исключаемая из этого [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_8}


```
 exclude(rect) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), чтобы включить только ту часть его внутренней области, которая не пересекается с указанной структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), исключаемая из этого [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(region) {#exclude_region_9}


```
 exclude(region) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), чтобы включить только ту часть его внутренней области, которая не пересекается с указанным [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/), исключаемый из этого [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(path) {#intersect_path_10}


```
 intersect(path) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), до пересечения с указанным [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), пересекающийся с этим [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), до пересечения с указанной структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), пересекающаяся с этим [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_12}


```
 intersect(rect) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), до пересечения с указанной структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), пересекающаяся с этим [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(region) {#intersect_region_13}


```
 intersect(region) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), до пересечения с указанным [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/), пересекающийся с этим [Region](/psd/python-net/aspose.psd/region/). |

### Method: is_empty(g) {#is_empty_g_14}


```
 is_empty(g) 
```

Проверяет, имеет ли этот [Region](/psd/python-net/aspose.psd/region/) пустую внутреннюю область на указанной поверхности рисования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | [Graphics](/psd/python-net/aspose.psd/graphics/), представляющий поверхность для рисования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true если внутренность этого [Region](/psd/python-net/aspose.psd/region/) пуста при применении преобразования, связанного с <paramref name="g" />; иначе false. |


### Method: is_infinite(g) {#is_infinite_g_15}


```
 is_infinite(g) 
```

Проверяет, имеет ли этот [Region](/psd/python-net/aspose.psd/region/) бесконечную внутреннюю область на указанной поверхности рисования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | [Graphics](/psd/python-net/aspose.psd/graphics/), представляющий поверхность для рисования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true если внутренность этого [Region](/psd/python-net/aspose.psd/region/) бесконечна при применении преобразования, связанного с <paramref name="g" />; иначе false. |


### Method: is_visible(point) {#is_visible_point_16}


```
 is_visible(point) 
```

Проверяет, содержится ли указанная структура [PointF](/psd/python-net/aspose.psd/pointf/) внутри этого [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Структура [PointF](/psd/python-net/aspose.psd/pointf/) для тестирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда <paramref name="point" /> содержится в этом [Region](/psd/python-net/aspose.psd/region/); иначе false. |


### Method: is_visible(point) {#is_visible_point_17}


```
 is_visible(point) 
```

Проверяет, содержится ли указанная структура [PointF](/psd/python-net/aspose.psd/pointf/) внутри этого [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Структура [PointF](/psd/python-net/aspose.psd/pointf/) для тестирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда <paramref name="point" /> содержится в этом [Region](/psd/python-net/aspose.psd/region/); иначе false. |


### Method: is_visible(point, g) {#is_visible_point_g_18}


```
 is_visible(point, g) 
```

Проверяет, содержится ли указанная структура [PointF](/psd/python-net/aspose.psd/pointf/) внутри этого [Region](/psd/python-net/aspose.psd/region/) при отрисовке с использованием указанного [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Структура [PointF](/psd/python-net/aspose.psd/pointf/) для тестирования. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Объект [Graphics](/psd/python-net/aspose.psd/graphics/), представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда <paramref name="point" /> содержится в этом [Region](/psd/python-net/aspose.psd/region/); иначе false. |


### Method: is_visible(point, g) {#is_visible_point_g_19}


```
 is_visible(point, g) 
```

Проверяет, содержится ли указанная структура [PointF](/psd/python-net/aspose.psd/pointf/) внутри этого [Region](/psd/python-net/aspose.psd/region/) при отрисовке с использованием указанного [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Структура [PointF](/psd/python-net/aspose.psd/pointf/) для тестирования. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Объект [Graphics](/psd/python-net/aspose.psd/graphics/), представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда <paramref name="point" /> содержится в этом [Region](/psd/python-net/aspose.psd/region/); иначе false. |


### Method: is_visible(rect) {#is_visible_rect_20}


```
 is_visible(rect) 
```

Проверяет, содержится ли какая-либо часть указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/) внутри этого [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/) для тестирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть <paramref name="rect" /> содержится в этом [Region](/psd/python-net/aspose.psd/region/); иначе false. |


### Method: is_visible(rect) {#is_visible_rect_21}


```
 is_visible(rect) 
```

Проверяет, содержится ли какая-либо часть указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/) внутри этого [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/) для тестирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть <paramref name="rect" /> содержится в этом [Region](/psd/python-net/aspose.psd/region/); иначе false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_22}


```
 is_visible(rect, g) 
```

Проверяет, содержится ли какая-либо часть указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/) внутри этого [Region](/psd/python-net/aspose.psd/region/) при отрисовке с использованием указанного [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/) для тестирования. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Объект [Graphics](/psd/python-net/aspose.psd/graphics/), представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда <paramref name="rect" /> содержится в этом [Region](/psd/python-net/aspose.psd/region/); иначе false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_23}


```
 is_visible(rect, g) 
```

Проверяет, содержится ли какая-либо часть указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/) внутри этого [Region](/psd/python-net/aspose.psd/region/) при отрисовке с использованием указанного [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/) для тестирования. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Объект [Graphics](/psd/python-net/aspose.psd/graphics/), представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда <paramref name="rect" /> содержится в этом [Region](/psd/python-net/aspose.psd/region/); иначе false. |


### Method: is_visible(x, y) {#is_visible_x_y_24}


```
 is_visible(x, y) 
```

Проверяет, содержится ли указанная точка внутри этого [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, когда указанная точка содержится в этом [Region](/psd/python-net/aspose.psd/region/); иначе false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_25}


```
 is_visible(x, y, g) 
```

Проверяет, содержится ли указанная точка внутри этого [Region](/psd/python-net/aspose.psd/region/) при отрисовке с использованием указанного [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Объект [Graphics](/psd/python-net/aspose.psd/graphics/), представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, когда указанная точка содержится в этом [Region](/psd/python-net/aspose.psd/region/); иначе false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_26}


```
 is_visible(x, y, g) 
```

Проверяет, содержится ли указанная точка внутри этого [Region](/psd/python-net/aspose.psd/region/) при отрисовке с использованием указанного [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Объект [Graphics](/psd/python-net/aspose.psd/graphics/), представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, когда указанная точка содержится в этом [Region](/psd/python-net/aspose.psd/region/); иначе false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_27}


```
 is_visible(x, y, width, height) 
```

Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x левого верхнего угла проверяемого прямоугольника. |
| y | float | Координата y левого верхнего угла проверяемого прямоугольника. |
| width | float | Ширина проверяемого прямоугольника. |
| height | float | Высота проверяемого прямоугольника. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть указанного прямоугольника содержится в этом объекте [Region](/psd/python-net/aspose.psd/region/); иначе false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_28}


```
 is_visible(x, y, width, height) 
```

Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x левого верхнего угла проверяемого прямоугольника. |
| y | int | Координата y левого верхнего угла проверяемого прямоугольника. |
| width | int | Ширина проверяемого прямоугольника. |
| height | int | Высота проверяемого прямоугольника. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть указанного прямоугольника содержится в этом объекте [Region](/psd/python-net/aspose.psd/region/); иначе false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_29}


```
 is_visible(x, y, width, height, g) 
```

Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/psd/python-net/aspose.psd/region/) при отрисовке с использованием указанного [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x левого верхнего угла проверяемого прямоугольника. |
| y | float | Координата y левого верхнего угла проверяемого прямоугольника. |
| width | float | Ширина проверяемого прямоугольника. |
| height | float | Высота проверяемого прямоугольника. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Объект [Graphics](/psd/python-net/aspose.psd/graphics/), представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть указанного прямоугольника содержится в этом [Region](/psd/python-net/aspose.psd/region/); иначе false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_30}


```
 is_visible(x, y, width, height, g) 
```

Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/psd/python-net/aspose.psd/region/) при отрисовке с использованием указанного [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x левого верхнего угла проверяемого прямоугольника. |
| y | int | Координата y левого верхнего угла проверяемого прямоугольника. |
| width | int | Ширина проверяемого прямоугольника. |
| height | int | Высота проверяемого прямоугольника. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Объект [Graphics](/psd/python-net/aspose.psd/graphics/), представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть указанного прямоугольника содержится в этом [Region](/psd/python-net/aspose.psd/region/); иначе false. |


### Method: transform(matrix) {#transform_matrix_31}


```
 transform(matrix) 
```

Преобразует этот [Region](/psd/python-net/aspose.psd/region/) с помощью указанной [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Матрица [Matrix](/psd/python-net/aspose.psd/matrix/), с помощью которой преобразовать этот [Region](/psd/python-net/aspose.psd/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_32}


```
 translate(dx, dy) 
```

Смещает координаты этого [Region](/psd/python-net/aspose.psd/region/) на указанное значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Величина горизонтального смещения этого [Region](/psd/python-net/aspose.psd/region/). |
| dy | float | Величина вертикального смещения этого [Region](/psd/python-net/aspose.psd/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_33}


```
 translate(dx, dy) 
```

Смещает координаты этого [Region](/psd/python-net/aspose.psd/region/) на указанное значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | int | Величина горизонтального смещения этого [Region](/psd/python-net/aspose.psd/region/). |
| dy | int | Величина вертикального смещения этого [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(path) {#union_path_34}


```
 union(path) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), объединяя его с указанным [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), объединяемый с этим [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(rect) {#union_rect_35}


```
 union(rect) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), объединяя его с указанной структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), объединяемая с этим [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(rect) {#union_rect_36}


```
 union(rect) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), объединяя его с указанной структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), объединяемая с этим [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(region) {#union_region_37}


```
 union(region) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), объединяя его с указанным [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/), объединяемый с этим [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(path) {#xor_path_38}


```
 xor(path) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), объединяя его за вычетом пересечения с указанным [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), выполняющий XOR с этим [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(rect) {#xor_rect_39}


```
 xor(rect) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), объединяя его за вычетом пересечения с указанной структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), выполняющая XOR с этим [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(rect) {#xor_rect_40}


```
 xor(rect) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), объединяя его за вычетом пересечения с указанной структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), выполняющая XOR с этим [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(region) {#xor_region_41}


```
 xor(region) 
```

Обновляет этот [Region](/psd/python-net/aspose.psd/region/), объединяя его за вычетом пересечения с указанным [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/), выполняющий XOR с этим [Region](/psd/python-net/aspose.psd/region/). |

