---
title: "Класс Rectangle"
type: docs
weight: 3810
url: /ru/python-net/aspose.psd/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Rectangle

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Инициализирует новый экземпляр класса Rectangle |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Инициализирует новый экземпляр структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/) с указанным расположением и размером. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Инициализирует новый экземпляр структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/) с указанным расположением и размером. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| bottom | int | r/w | Получает или задаёт координату y, которая является суммой значений свойств [Rectangle.y](/psd/python-net/aspose.psd/rectangle/) и [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| empty [static] | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Получает новый экземпляр структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/), у которой значения [Rectangle.x](/psd/python-net/aspose.psd/rectangle/), [Rectangle.y](/psd/python-net/aspose.psd/rectangle/), [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) и [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) установлены в ноль. |
| height | int | r/w | Получает или задаёт высоту этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| is_empty | bool | r | Получает значение, указывающее, имеют ли все числовые свойства этой [Rectangle](/psd/python-net/aspose.psd/rectangle/) значение ноль. |
| left | int | r/w | Получает или задаёт координату x левой границы этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| location | [Point](/psd/python-net/aspose.psd/point) | r/w | Получает или задаёт координаты верхнего левого угла этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| right | int | r/w | Получает или задаёт координату x, которая является суммой значений свойств [Rectangle.x](/psd/python-net/aspose.psd/rectangle/) и [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| size | [Size](/psd/python-net/aspose.psd/size) | r/w | Получает или задаёт размер этой [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| top | int | r/w | Получает или задаёт координату y верхней границы этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| width | int | r/w | Получает или задаёт ширину этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| x | int | r/w | Получает или задаёт координату x верхнего левого угла этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| y | int | r/w | Получает или задаёт координату y верхнего левого угла этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Преобразует указанную структуру [RectangleF](/psd/python-net/aspose.psd/rectanglef/) в структуру [Rectangle](/psd/python-net/aspose.psd/rectangle/), округляя значения [RectangleF](/psd/python-net/aspose.psd/rectanglef/) до следующего большего целого числа. |
| [contains(point)](#contains_point_2) | Определяет, содержится ли указанная точка внутри этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [contains(rect)](#contains_rect_3) | Определяет, полностью ли прямоугольный регион, представленный <paramref name="rect" />, содержится внутри этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [contains(x, y)](#contains_x_y_4) | Определяет, содержится ли указанная точка внутри этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_5) | Создаёт структуру [Rectangle](/psd/python-net/aspose.psd/rectangle/) с указанными позициями краёв. |
| [from_points(point1, point2)](#from_points_point1_point2_6) | Создаёт новый [Rectangle](/psd/python-net/aspose.psd/rectangle/) из двух указанных точек. Две вертикали созданного [Rectangle](/psd/python-net/aspose.psd/rectangle/) будут равны переданным <paramref name="point1" /> и <paramref name="point2" />. Обычно это противоположные вершины. |
| [inflate(rect, x, y)](#inflate_rect_x_y_7) | Создаёт и возвращает увеличенную копию указанной структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). Копия увеличивается на указанную величину. Исходная структура [Rectangle](/psd/python-net/aspose.psd/rectangle/) остаётся неизменной. |
| [inflate(size)](#inflate_size_8) | Увеличивает размер этого [Rectangle](/psd/python-net/aspose.psd/rectangle/) на указанную величину. |
| [inflate(width, height)](#inflate_width_height_9) | Увеличивает размер этого [Rectangle](/psd/python-net/aspose.psd/rectangle/) на указанную величину. |
| [intersect(a, b)](#intersect_a_b_10) | Возвращает третью структуру [Rectangle](/psd/python-net/aspose.psd/rectangle/), представляющую пересечение двух других структур [Rectangle](/psd/python-net/aspose.psd/rectangle/). Если пересечения нет, возвращается пустой [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [intersect(rect)](#intersect_rect_11) | Заменяет этот [Rectangle](/psd/python-net/aspose.psd/rectangle/) пересечением его с указанным [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [intersects_with(rect)](#intersects_with_rect_12) | Определяет, пересекается ли этот прямоугольник с <paramref name=\"rect\" />. |
| normalize() | Нормализует прямоугольник, делая его ширину и высоту положительными, левый край меньше правого, а верхний меньше нижнего. |
| [offset(pos)](#offset_pos_13) | Изменяет расположение этого прямоугольника на указанную величину. |
| [offset(x, y)](#offset_x_y_14) | Изменяет расположение этого прямоугольника на указанную величину. |
| [round(value)](#round_value_15) | Преобразует указанный [RectangleF](/psd/python-net/aspose.psd/rectanglef/) в [Rectangle](/psd/python-net/aspose.psd/rectangle/), округляя значения [RectangleF](/psd/python-net/aspose.psd/rectanglef/) до ближайших целых чисел. |
| [truncate(value)](#truncate_value_16) | Преобразует указанный [RectangleF](/psd/python-net/aspose.psd/rectanglef/) в [Rectangle](/psd/python-net/aspose.psd/rectangle/), отбрасывая дробную часть значений [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [union(a, b)](#union_a_b_17) | Получает структуру [Rectangle](/psd/python-net/aspose.psd/rectangle/), содержащую объединение двух структур [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Инициализирует новый экземпляр класса Rectangle

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Инициализирует новый экземпляр структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/) с указанным расположением и размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | Точка [Point](/psd/python-net/aspose.psd/point/), представляющая верхний левый угол прямоугольной области. |
| size | [Size](/psd/python-net/aspose.psd/size) | Размер [Size](/psd/python-net/aspose.psd/size/), представляющий ширину и высоту прямоугольной области. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Инициализирует новый экземпляр структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/) с указанным расположением и размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x верхнего левого угла прямоугольника. |
| y | int | Координата y верхнего левого угла прямоугольника. |
| width | int | Ширина прямоугольника. |
| height | int | Высота прямоугольника. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Преобразует указанную структуру [RectangleF](/psd/python-net/aspose.psd/rectanglef/) в структуру [Rectangle](/psd/python-net/aspose.psd/rectangle/), округляя значения [RectangleF](/psd/python-net/aspose.psd/rectanglef/) до следующего большего целого числа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/) для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Возвращает [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Определяет, содержится ли указанная точка внутри этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Точка [Point](/psd/python-net/aspose.psd/point/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если точка, представленная параметром <paramref name=\"point\" />, содержится в этой структуре [Rectangle](/psd/python-net/aspose.psd/rectangle/); в противном случае — false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Определяет, полностью ли прямоугольный регион, представленный <paramref name="rect" />, содержится внутри этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник [Rectangle](/psd/python-net/aspose.psd/rectangle/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если прямоугольная область, представленная параметром <paramref name=\"rect\" />, полностью содержится в этой структуре [Rectangle](/psd/python-net/aspose.psd/rectangle/); в противном случае — false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Определяет, содержится ли указанная точка внутри этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если точка, определённая параметрами <paramref name=\"x\" /> и <paramref name=\"y\" />, содержится в этой структуре [Rectangle](/psd/python-net/aspose.psd/rectangle/); в противном случае — false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_5}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Создаёт структуру [Rectangle](/psd/python-net/aspose.psd/rectangle/) с указанными позициями краёв.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| left | int | Координата X верхнего левого угла этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| top | int | Координата Y верхнего левого угла этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| right | int | Координата X нижнего правого угла этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| bottom | int | Координата Y нижнего правого угла этой структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Новый [Rectangle](/psd/python-net/aspose.psd/rectangle/), создаваемый этим методом. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_6}


```
 from_points(point1, point2) 
```

Создаёт новый [Rectangle](/psd/python-net/aspose.psd/rectangle/) из двух указанных точек. Две вертикали созданного [Rectangle](/psd/python-net/aspose.psd/rectangle/) будут равны переданным <paramref name="point1" /> и <paramref name="point2" />. Обычно это противоположные вершины.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Первая [Point](/psd/python-net/aspose.psd/point/) для нового прямоугольника. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Вторая [Point](/psd/python-net/aspose.psd/point/) для нового прямоугольника. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Новосозданный [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_7}


```
 inflate(rect, x, y) 
```

Создаёт и возвращает увеличенную копию указанной структуры [Rectangle](/psd/python-net/aspose.psd/rectangle/). Копия увеличивается на указанную величину. Исходная структура [Rectangle](/psd/python-net/aspose.psd/rectangle/) остаётся неизменной.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/), с которым начинается. Этот прямоугольник не изменяется. |
| x | int | Величина горизонтального увеличения этого [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| y | int | Величина вертикального увеличения этого [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Увеличенный [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(size) {#inflate_size_8}


```
 inflate(size) 
```

Увеличивает размер этого [Rectangle](/psd/python-net/aspose.psd/rectangle/) на указанную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | Величина, на которую следует расширить этот прямоугольник. |

### Method: inflate(width, height) {#inflate_width_height_9}


```
 inflate(width, height) 
```

Увеличивает размер этого [Rectangle](/psd/python-net/aspose.psd/rectangle/) на указанную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Величина горизонтального увеличения этого [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| height | int | Величина вертикального увеличения этого [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

### Method: intersect(a, b)  [static] {#intersect_a_b_10}


```
 intersect(a, b) 
```

Возвращает третью структуру [Rectangle](/psd/python-net/aspose.psd/rectangle/), представляющую пересечение двух других структур [Rectangle](/psd/python-net/aspose.psd/rectangle/). Если пересечения нет, возвращается пустой [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Первый прямоугольник для пересечения. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Второй прямоугольник для пересечения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/), представляющий пересечение параметров <paramref name=\"a\" /> и <paramref name=\"b\" />. |


### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Заменяет этот [Rectangle](/psd/python-net/aspose.psd/rectangle/) пересечением его с указанным [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник [Rectangle](/psd/python-net/aspose.psd/rectangle/) для пересечения. |

### Method: intersects_with(rect) {#intersects_with_rect_12}


```
 intersects_with(rect) 
```

Определяет, пересекается ли этот прямоугольник с <paramref name=\"rect\" />.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если есть любое пересечение, иначе false. |


### Method: offset(pos) {#offset_pos_13}


```
 offset(pos) 
```

Изменяет расположение этого прямоугольника на указанную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pos | [Point](/psd/python-net/aspose.psd/point) | Величина смещения местоположения. |

### Method: offset(x, y) {#offset_x_y_14}


```
 offset(x, y) 
```

Изменяет расположение этого прямоугольника на указанную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Горизонтальное смещение. |
| y | int | Вертикальное смещение. |

### Method: round(value)  [static] {#round_value_15}


```
 round(value) 
```

Преобразует указанный [RectangleF](/psd/python-net/aspose.psd/rectanglef/) в [Rectangle](/psd/python-net/aspose.psd/rectangle/), округляя значения [RectangleF](/psd/python-net/aspose.psd/rectanglef/) до ближайших целых чисел.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Прямоугольник [RectangleF](/psd/python-net/aspose.psd/rectanglef/) для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Новый [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_16}


```
 truncate(value) 
```

Преобразует указанный [RectangleF](/psd/python-net/aspose.psd/rectanglef/) в [Rectangle](/psd/python-net/aspose.psd/rectangle/), отбрасывая дробную часть значений [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Прямоугольник [RectangleF](/psd/python-net/aspose.psd/rectanglef/) для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Новый [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_17}


```
 union(a, b) 
```

Получает структуру [Rectangle](/psd/python-net/aspose.psd/rectangle/), содержащую объединение двух структур [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Первый прямоугольник для объединения. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Второй прямоугольник для объединения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [Rectangle](/psd/python-net/aspose.psd/rectangle/), ограничивающая объединение двух структур [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


