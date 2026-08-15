---
title: "Класс RectangleF"
type: docs
weight: 3830
url: /ru/python-net/aspose.psd/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RectangleF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | Инициализирует новый экземпляр класса RectangleF |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Инициализирует новый экземпляр структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/) с указанным расположением и размером. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Инициализирует новый экземпляр структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/) с указанным расположением и размером. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| bottom | float | r/w | Получает или задает координату y, которая является суммой [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/) и [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) этой структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| empty [static] | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Возвращает новый экземпляр структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/), у которой свойства [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) и [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) установлены в ноль. |
| height | float | r/w | Получает или задает высоту этой структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| is_empty | bool | r | Возвращает значение, указывающее, имеет ли свойство [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) или [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) этой структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/) значение ноль. |
| left | float | r/w | Получает или задает координату x левой грани этой структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Получает или задает координаты верхнего левого угла этой структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| right | float | r/w | Получает или задает координату x, которая является суммой [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/) и [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) этой структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Получает или задает размер этой структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| top | float | r/w | Получает или задает координату y верхней грани этой структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| width | float | r/w | Получает или задает ширину этой структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| x | float | r/w | Получает или задает координату x верхнего левого угла этой структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| y | float | r/w | Получает или задает координату y верхнего левого угла этой структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [contains(point)](#contains_point_1) | Определяет, содержится ли указанная точка в этой структуре [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [contains(rect)](#contains_rect_2) | Определяет, полностью ли прямоугольный регион, представленный <paramref name=\"rect\" /> содержится внутри этой структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [contains(x, y)](#contains_x_y_3) | Определяет, содержится ли указанная точка в этой структуре [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_4) | Создаёт структуру [RectangleF](/psd/python-net/aspose.psd/rectanglef/) с верхним левым и нижним правым углом в указанных позициях. |
| [from_points(point1, point2)](#from_points_point1_point2_5) | Создаёт новый [Rectangle](/psd/python-net/aspose.psd/rectangle/) из двух указанных точек. Две вершины созданного [Rectangle](/psd/python-net/aspose.psd/rectangle/) будут равны переданным <paramref name=\"point1\" /> и <paramref name=\"point2\" />. Обычно это противоположные вершины. |
| [inflate(rect, x, y)](#inflate_rect_x_y_6) | Создаёт и возвращает увеличенную копию указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/). Копия увеличивается на заданную величину. Исходный прямоугольник остаётся неизменным. |
| [inflate(size)](#inflate_size_7) | Увеличивает этот [RectangleF](/psd/python-net/aspose.psd/rectanglef/) на указанную величину. |
| [inflate(x, y)](#inflate_x_y_8) | Увеличивает эту структуру [RectangleF](/psd/python-net/aspose.psd/rectanglef/) на указанную величину. |
| [intersect(a, b)](#intersect_a_b_9) | Возвращает структуру [RectangleF](/psd/python-net/aspose.psd/rectanglef/), представляющую пересечение двух прямоугольников. Если пересечения нет, возвращается пустой [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [intersect(rect)](#intersect_rect_10) | Заменяет эту структуру [RectangleF](/psd/python-net/aspose.psd/rectanglef/) пересечением её самой и указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [intersects_with(rect)](#intersects_with_rect_11) | Определяет, пересекается ли этот прямоугольник с <paramref name=\"rect\" />. |
| normalize() | Нормализует прямоугольник, делая его ширину и высоту положительными, левый край меньше правого, а верхний меньше нижнего. |
| [offset(pos)](#offset_pos_12) | Изменяет расположение этого прямоугольника на указанную величину. |
| [offset(x, y)](#offset_x_y_13) | Изменяет расположение этого прямоугольника на указанную величину. |
| [union(a, b)](#union_a_b_14) | Создаёт наименьший возможный третий прямоугольник, который может содержать оба из двух прямоугольников, образующих объединение. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

Инициализирует новый экземпляр класса RectangleF

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Инициализирует новый экземпляр структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/) с указанным расположением и размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | Объект [PointF](/psd/python-net/aspose.psd/pointf/) представляет верхний левый угол прямоугольного региона. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Объект [SizeF](/psd/python-net/aspose.psd/sizef/) представляет ширину и высоту прямоугольного региона. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Инициализирует новый экземпляр структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/) с указанным расположением и размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x верхнего левого угла прямоугольника. |
| y | float | Координата y верхнего левого угла прямоугольника. |
| width | float | Ширина прямоугольника. |
| height | float | Высота прямоугольника. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Определяет, содержится ли указанная точка в этой структуре [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если точка, представленная параметром <paramref name=\"point\" />, содержится внутри этой структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/); в противном случае — false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Определяет, полностью ли прямоугольный регион, представленный <paramref name=\"rect\" /> содержится внутри этой структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если прямоугольный регион, представленный <paramref name=\"rect\" />, полностью содержится в прямоугольном регионе, представленном этим [RectangleF](/psd/python-net/aspose.psd/rectanglef/); в противном случае — false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Определяет, содержится ли указанная точка в этой структуре [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если точка, определённая параметрами <paramref name="x" /> и <paramref name="y" />, содержится внутри этой структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/); в противном случае — false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_4}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Создаёт структуру [RectangleF](/psd/python-net/aspose.psd/rectanglef/) с верхним левым и нижним правым углом в указанных позициях.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| слева | float | Координата x верхнего левого угла прямоугольной области. |
| верх | float | Координата y верхнего левого угла прямоугольной области. |
| справа | float | Координата x нижнего правого угла прямоугольной области. |
| bottom | float | Координата y нижнего правого угла прямоугольной области. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Новый [RectangleF](/psd/python-net/aspose.psd/rectanglef/), который создаёт этот метод. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_5}


```
 from_points(point1, point2) 
```

Создаёт новый [Rectangle](/psd/python-net/aspose.psd/rectangle/) из двух указанных точек. Две вершины созданного [Rectangle](/psd/python-net/aspose.psd/rectangle/) будут равны переданным <paramref name=\"point1\" /> и <paramref name=\"point2\" />. Обычно это противоположные вершины.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Первая [Point](/psd/python-net/aspose.psd/point/) для нового прямоугольника. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Вторая [Point](/psd/python-net/aspose.psd/point/) для нового прямоугольника. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Новосозданный [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_6}


```
 inflate(rect, x, y) 
```

Создаёт и возвращает увеличенную копию указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/). Копия увеличивается на заданную величину. Исходный прямоугольник остаётся неизменным.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) для копирования. Этот прямоугольник не изменяется. |
| x | float | Величина, на которую следует расширить копию прямоугольника по горизонтали. |
| y | float | Величина, на которую следует расширить копию прямоугольника по вертикали. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Расширенный [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |


### Method: inflate(size) {#inflate_size_7}


```
 inflate(size) 
```

Увеличивает этот [RectangleF](/psd/python-net/aspose.psd/rectanglef/) на указанную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Величина, на которую следует расширить этот прямоугольник. |

### Method: inflate(x, y) {#inflate_x_y_8}


```
 inflate(x, y) 
```

Увеличивает эту структуру [RectangleF](/psd/python-net/aspose.psd/rectanglef/) на указанную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Величина, на которую следует расширить эту структуру [RectangleF](/psd/python-net/aspose.psd/rectanglef/) по горизонтали. |
| y | float | Величина, на которую следует расширить эту структуру [RectangleF](/psd/python-net/aspose.psd/rectanglef/) по вертикали. |

### Method: intersect(a, b)  [static] {#intersect_a_b_9}


```
 intersect(a, b) 
```

Возвращает структуру [RectangleF](/psd/python-net/aspose.psd/rectanglef/), представляющую пересечение двух прямоугольников. Если пересечения нет, возвращается пустой [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Первый прямоугольник для пересечения. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Второй прямоугольник для пересечения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Третья структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), размер которой представляет собой область перекрытия двух указанных прямоугольников. |


### Method: intersect(rect) {#intersect_rect_10}


```
 intersect(rect) 
```

Заменяет эту структуру [RectangleF](/psd/python-net/aspose.psd/rectanglef/) пересечением её самой и указанной структуры [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Прямоугольник для пересечения. |

### Method: intersects_with(rect) {#intersects_with_rect_11}


```
 intersects_with(rect) 
```

Определяет, пересекается ли этот прямоугольник с <paramref name=\"rect\" />.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Прямоугольник для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если существует какое-либо пересечение. |


### Method: offset(pos) {#offset_pos_12}


```
 offset(pos) 
```

Изменяет расположение этого прямоугольника на указанную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pos | [PointF](/psd/python-net/aspose.psd/pointf) | Величина смещения местоположения. |

### Method: offset(x, y) {#offset_x_y_13}


```
 offset(x, y) 
```

Изменяет расположение этого прямоугольника на указанную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Величина смещения местоположения по горизонтали. |
| y | float | Величина смещения местоположения по вертикали. |

### Method: union(a, b)  [static] {#union_a_b_14}


```
 union(a, b) 
```

Создаёт наименьший возможный третий прямоугольник, который может содержать оба из двух прямоугольников, образующих объединение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Первый прямоугольник для объединения. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Второй прямоугольник для объединения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Третья структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/) , содержащая оба прямоугольника, образующие объединение. |


