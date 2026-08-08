---
title: "Rectangle"
second_title: "Aspose.PSD for Java API Справочник"
description: "Сохраняет набор из четырёх целых чисел, представляющих положение и размер прямоугольника."
type: docs
weight: 88
url: /ru/java/com.aspose.psd/rectangle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Сохраняет набор из четырёх целых чисел, представляющих положение и размер прямоугольника.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Инициализирует новый экземпляр структуры com.aspose.psd.Rectangle с указанным расположением и размером. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-) | Инициализирует новый экземпляр структуры com.aspose.psd.Rectangle с указанным расположением и размером. |
## Методы

| Метод | Описание |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.psd.Rectangle-) |  |
| [ceiling(RectangleF value)](#ceiling-com.aspose.psd.RectangleF-) | Преобразует указанную структуру  com.aspose.psd.RectangleF  в структуру  com.aspose.psd.Rectangle  путем округления значений  com.aspose.psd.RectangleF  до следующего большего целого числа. |
| [contains(Point point)](#contains-com.aspose.psd.Point-) | Определяет, содержится ли указанная точка внутри этой структуры  com.aspose.psd.Rectangle . |
| [contains(Rectangle rect)](#contains-com.aspose.psd.Rectangle-) | Определяет, полностью ли прямоугольный регион, представленный переменной  rect , содержится внутри этой структуры  com.aspose.psd.Rectangle . |
| [contains(int x, int y)](#contains-int-int-) | Определяет, содержится ли указанная точка внутри этой структуры  com.aspose.psd.Rectangle . |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверяет, является ли  obj  структурой  com.aspose.psd.Rectangle  с тем же расположением и размером, что и эта структура  com.aspose.psd.Rectangle . |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Создаёт структуру  com.aspose.psd.Rectangle  с указанными позициями краёв. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-) | Создаёт новый  Rectangle  из двух указанных точек. |
| [getBottom()](#getBottom--) | Получает или задаёт координату y, которая является суммой значений свойств  com.aspose.psd.Rectangle.Y  и  com.aspose.psd.Rectangle.Height  этой структуры  com.aspose.psd.Rectangle . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Получает новый экземпляр структуры  com.aspose.psd.Rectangle , у которой значения  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  и  com.aspose.psd.Rectangle.Height  установлены в ноль. |
| [getHeight()](#getHeight--) | Получает или задаёт высоту этой структуры  com.aspose.psd.Rectangle . |
| [getLeft()](#getLeft--) | Получает или задаёт координату x левого края этой структуры  com.aspose.psd.Rectangle . |
| [getLocation()](#getLocation--) | Получает или задаёт координаты верхнего левого угла этой структуры  com.aspose.psd.Rectangle . |
| [getRight()](#getRight--) | Получает или задаёт координату x, которая является суммой значений свойств  com.aspose.psd.Rectangle.X  и  com.aspose.psd.Rectangle.Width  этой структуры  com.aspose.psd.Rectangle . |
| [getSize()](#getSize--) | Получает или задаёт размер этой структуры  com.aspose.psd.Rectangle . |
| [getTop()](#getTop--) | Получает или задаёт координату y верхнего края этой структуры  com.aspose.psd.Rectangle . |
| [getWidth()](#getWidth--) | Получает ширину этой структуры  com.aspose.psd.Rectangle . |
| [getX()](#getX--) | Получает или задаёт координату x верхнего левого угла этой структуры  com.aspose.psd.Rectangle . |
| [getY()](#getY--) | Получает или задаёт координату y верхнего левого угла этой структуры  com.aspose.psd.Rectangle . |
| [hashCode()](#hashCode--) | Возвращает хеш-код этой структуры  com.aspose.psd.Rectangle . |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.psd.Rectangle-int-int-) | Создаёт и возвращает расширенную копию указанной структуры  com.aspose.psd.Rectangle . |
| [inflate(Size size)](#inflate-com.aspose.psd.Size-) | Расширяет эту структуру  com.aspose.psd.Rectangle  на указанную величину. |
| [inflate(int width, int height)](#inflate-int-int-) | Расширяет эту структуру  com.aspose.psd.Rectangle  на указанную величину. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Заменяет эту структуру  com.aspose.psd.Rectangle  пересечением её с указанной структурой  com.aspose.psd.Rectangle . |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Возвращает третью структуру  com.aspose.psd.Rectangle , представляющую пересечение двух других структур  com.aspose.psd.Rectangle . |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.psd.Rectangle-) | Определяет, пересекается ли этот прямоугольник с rect. |
| [isEmpty()](#isEmpty--) | Получает значение, указывающее, имеют ли все числовые свойства этой структуры  com.aspose.psd.Rectangle  значение ноль. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) |  |
| [isVisible_internalized()](#isVisible-internalized--) | Получает значение, указывающее, виден ли этот  Rectangle  хотя бы частично |
| [normalize()](#normalize--) | Нормализует прямоугольник, делая его ширину и высоту положительными, левую сторону меньше правой и верхнюю меньше нижней. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point pos)](#offset-com.aspose.psd.Point-) | Корректирует положение этого прямоугольника на указанную величину. |
| [offset(int x, int y)](#offset-int-int-) | Корректирует положение этого прямоугольника на указанную величину. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Проверяет, имеют ли две структуры  com.aspose.psd.Rectangle  одинаковое расположение и размер. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Проверяет, отличаются ли две структуры  com.aspose.psd.Rectangle  расположением или размером. |
| [round(RectangleF value)](#round-com.aspose.psd.RectangleF-) | Преобразует указанный com.aspose.psd.RectangleF в com.aspose.psd.Rectangle, округляя значения com.aspose.psd.RectangleF до ближайших целых чисел. |
| [setBottom(int value)](#setBottom-int-) | Получает или задаёт координату y, которая является суммой значений свойств  com.aspose.psd.Rectangle.Y  и  com.aspose.psd.Rectangle.Height  этой структуры  com.aspose.psd.Rectangle . |
| [setHeight(int value)](#setHeight-int-) | Получает или задаёт высоту этой структуры  com.aspose.psd.Rectangle . |
| [setLeft(int value)](#setLeft-int-) | Получает или задаёт координату x левого края этой структуры  com.aspose.psd.Rectangle . |
| [setLocation(Point value)](#setLocation-com.aspose.psd.Point-) | Получает или задаёт координаты верхнего левого угла этой структуры  com.aspose.psd.Rectangle . |
| [setRight(int value)](#setRight-int-) | Получает или задаёт координату x, которая является суммой значений свойств  com.aspose.psd.Rectangle.X  и  com.aspose.psd.Rectangle.Width  этой структуры  com.aspose.psd.Rectangle . |
| [setSize(Size value)](#setSize-com.aspose.psd.Size-) | Получает или задаёт размер этой структуры  com.aspose.psd.Rectangle . |
| [setTop(int value)](#setTop-int-) | Получает или задаёт координату y верхнего края этой структуры  com.aspose.psd.Rectangle . |
| [setWidth(int value)](#setWidth-int-) | Устанавливает ширину этой структуры com.aspose.psd.Rectangle. |
| [setX(int value)](#setX-int-) | Получает или задаёт координату x верхнего левого угла этой структуры  com.aspose.psd.Rectangle . |
| [setY(int value)](#setY-int-) | Получает или задаёт координату y верхнего левого угла этой структуры  com.aspose.psd.Rectangle . |
| [toString()](#toString--) | Преобразует атрибуты этой структуры com.aspose.psd.Rectangle в читаемую строку. |
| [truncate(RectangleF value)](#truncate-com.aspose.psd.RectangleF-) | Преобразует указанный com.aspose.psd.RectangleF в com.aspose.psd.Rectangle, отбрасывая дробную часть значений com.aspose.psd.RectangleF. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Возвращает структуру com.aspose.psd.Rectangle, содержащую объединение двух структур com.aspose.psd.Rectangle. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Инициализирует новый экземпляр структуры com.aspose.psd.Rectangle с указанным расположением и размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x верхнего левого угла прямоугольника. |
| y | int | Y‑координата верхнего левого угла прямоугольника. |
| ширина | int | Ширина прямоугольника. |
| высота | int | Высота прямоугольника. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public Rectangle(Point location, Size size)
```


Инициализирует новый экземпляр структуры com.aspose.psd.Rectangle с указанным расположением и размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | Точка com.aspose.psd.Point, представляющая левый верхний угол прямоугольной области. |
| size | [Size](../../com.aspose.psd/size) | Размер com.aspose.psd.Size, представляющий ширину и высоту прямоугольной области. |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Rectangle that) {#CloneTo-com.aspose.psd.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.psd/rectangle) |  |

### ceiling(RectangleF value) {#ceiling-com.aspose.psd.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Преобразует указанную структуру  com.aspose.psd.RectangleF  в структуру  com.aspose.psd.Rectangle  путем округления значений  com.aspose.psd.RectangleF  до следующего большего целого числа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Структура com.aspose.psd.RectangleF, которую нужно преобразовать. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a  com.aspose.psd.Rectangle .
### contains(Point point) {#contains-com.aspose.psd.Point-}
```
public boolean contains(Point point)
```


Определяет, содержится ли указанная точка внутри этой структуры  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Точка com.aspose.psd.Point для проверки. |

**Returns:**
boolean — Этот метод возвращает true, если точка, представленная переменной point, содержится в этой структуре com.aspose.psd.Rectangle; в противном случае — false.
### contains(Rectangle rect) {#contains-com.aspose.psd.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Определяет, полностью ли прямоугольный регион, представленный переменной  rect , содержится внутри этой структуры  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура com.aspose.psd.Rectangle для проверки. |

**Returns:**
boolean — Этот метод возвращает true, если прямоугольная область, представленная переменной rect, полностью содержится в этой структуре com.aspose.psd.Rectangle; в противном случае — false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Определяет, содержится ли указанная точка внутри этой структуры  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | X‑координата точки для проверки. |
| y | int | Y‑координата точки для проверки. |

**Returns:**
boolean — Этот метод возвращает true, если точка, определённая переменными x и y, содержится в этой структуре com.aspose.psd.Rectangle; в противном случае — false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверяет, является ли  obj  структурой  com.aspose.psd.Rectangle  с тем же расположением и размером, что и эта структура  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект  System.Object  для проверки. |

**Returns:**
boolean — Этот метод возвращает true, если obj является структурой com.aspose.psd.Rectangle и её свойства com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width и com.aspose.psd.Rectangle.Height равны соответствующим свойствам этой структуры com.aspose.psd.Rectangle; в противном случае — false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Создаёт структуру  com.aspose.psd.Rectangle  с указанными позициями краёв.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | int | Координата x левого верхнего угла этой структуры com.aspose.psd.Rectangle. |
| top | int | Координата y левого верхнего угла этой структуры com.aspose.psd.Rectangle. |
| right | int | Координата x правого нижнего угла этой структуры com.aspose.psd.Rectangle. |
| bottom | int | Координата y правого нижнего угла этой структуры com.aspose.psd.Rectangle. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The new  com.aspose.psd.Rectangle  that this method creates.
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Создаёт новый Rectangle из двух указанных точек. Две вершины созданного Rectangle будут соответствовать переданным point1 и point2. Обычно это противоположные вершины.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Первый пункт для нового прямоугольника. |
| point2 | [Point](../../com.aspose.psd/point) | Второй пункт для нового прямоугольника. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public int getBottom()
```


Получает или задаёт координату y, которая является суммой значений свойств  com.aspose.psd.Rectangle.Y  и  com.aspose.psd.Rectangle.Height  этой структуры  com.aspose.psd.Rectangle .

**Returns:**
int — Координата y, являющаяся суммой com.aspose.psd.Rectangle.Y и com.aspose.psd.Rectangle.Height этой структуры com.aspose.psd.Rectangle.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Получает новый экземпляр структуры  com.aspose.psd.Rectangle , у которой значения  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  и  com.aspose.psd.Rectangle.Height  установлены в ноль.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает или задаёт высоту этой структуры  com.aspose.psd.Rectangle .

**Returns:**
int — Высота этой структуры com.aspose.psd.Rectangle.
### getLeft() {#getLeft--}
```
public int getLeft()
```


Получает или задаёт координату x левого края этой структуры  com.aspose.psd.Rectangle .

**Returns:**
int — Координата x левого края этой структуры com.aspose.psd.Rectangle.
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Получает или задаёт координаты верхнего левого угла этой структуры  com.aspose.psd.Rectangle .

**Returns:**
[Point](../../com.aspose.psd/point) - A  com.aspose.psd.Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getRight() {#getRight--}
```
public int getRight()
```


Получает или задаёт координату x, которая является суммой значений свойств  com.aspose.psd.Rectangle.X  и  com.aspose.psd.Rectangle.Width  этой структуры  com.aspose.psd.Rectangle .

**Returns:**
int — Координата x, являющаяся суммой com.aspose.psd.Rectangle.X и com.aspose.psd.Rectangle.Width этой структуры com.aspose.psd.Rectangle.
### getSize() {#getSize--}
```
public Size getSize()
```


Получает или задаёт размер этой структуры  com.aspose.psd.Rectangle .

**Returns:**
[Size](../../com.aspose.psd/size) - A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure.
### getTop() {#getTop--}
```
public int getTop()
```


Получает или задаёт координату y верхнего края этой структуры  com.aspose.psd.Rectangle .

**Returns:**
int — Координата y верхнего края этой структуры com.aspose.psd.Rectangle.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину этой структуры  com.aspose.psd.Rectangle .

**Returns:**
int — Ширина этой структуры com.aspose.psd.Rectangle.
### getX() {#getX--}
```
public int getX()
```


Получает или задаёт координату x верхнего левого угла этой структуры  com.aspose.psd.Rectangle .

**Returns:**
int - Координата x верхнего левого угла этой структуры  com.aspose.psd.Rectangle .
### getY() {#getY--}
```
public int getY()
```


Получает или задаёт координату y верхнего левого угла этой структуры  com.aspose.psd.Rectangle .

**Returns:**
int - Координата y верхнего левого угла этой структуры  com.aspose.psd.Rectangle .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код этой структуры  com.aspose.psd.Rectangle .

**Returns:**
int - Целое число, представляющее хеш-код для этого прямоугольника.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Создаёт и возвращает расширенную копию указанной структуры  com.aspose.psd.Rectangle . Копия расширяется на указанную величину. Исходная структура  com.aspose.psd.Rectangle  остаётся неизменной.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура  com.aspose.psd.Rectangle , с которой начинать. Этот прямоугольник не изменяется. |
| x | int | Величина, на которую расширяется этот  com.aspose.psd.Rectangle  по горизонтали. |
| y | int | Величина, на которую расширяется этот  com.aspose.psd.Rectangle  по вертикали. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The inflated  com.aspose.psd.Rectangle .
### inflate(Size size) {#inflate-com.aspose.psd.Size-}
```
public void inflate(Size size)
```


Расширяет эту структуру  com.aspose.psd.Rectangle  на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Величина, на которую следует увеличить этот прямоугольник. |

### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Расширяет эту структуру  com.aspose.psd.Rectangle  на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ширина | int | Величина, на которую расширяется этот  com.aspose.psd.Rectangle  по горизонтали. |
| высота | int | Величина, на которую расширяется этот  com.aspose.psd.Rectangle  по вертикали. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Заменяет эту структуру  com.aspose.psd.Rectangle  пересечением её с указанной структурой  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура  com.aspose.psd.Rectangle , с которой выполнять пересечение. |

### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Возвращает третий объект структуры  com.aspose.psd.Rectangle , представляющий пересечение двух других структур  com.aspose.psd.Rectangle . Если пересечения нет, возвращается пустой  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Первый прямоугольник для пересечения. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Второй прямоугольник для пересечения. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  that represents the intersection of  a  and  b .
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.psd.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Определяет, пересекается ли этот прямоугольник с rect.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник для проверки. |

**Returns:**
boolean - Этот метод возвращает true, если существует какое‑либо пересечение, иначе false.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Получает значение, указывающее, имеют ли все числовые свойства этой структуры  com.aspose.psd.Rectangle  значение ноль.

**Returns:**
boolean - Это свойство возвращает true, если свойства  com.aspose.psd.Rectangle.Width ,  com.aspose.psd.Rectangle.Height ,  com.aspose.psd.Rectangle.X  и  com.aspose.psd.Rectangle.Y  данного  com.aspose.psd.Rectangle  имеют значение ноль; иначе false.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.psd/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
boolean
### isVisible_internalized() {#isVisible-internalized--}
```
public boolean isVisible_internalized()
```


Получает значение, указывающее, виден ли этот  Rectangle  хотя бы частично

**Returns:**
boolean -  true  если этот  Rectangle  хотя бы частично видим; иначе  false .
### normalize() {#normalize--}
```
public void normalize()
```


Нормализует прямоугольник, делая его ширину и высоту положительными, левую сторону меньше правой и верхнюю меньше нижней.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(Point pos) {#offset-com.aspose.psd.Point-}
```
public void offset(Point pos)
```


Корректирует положение этого прямоугольника на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pos | [Point](../../com.aspose.psd/point) | Величина смещения местоположения. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Корректирует положение этого прямоугольника на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Горизонтальное смещение. |
| y | int | Вертикальное смещение. |

### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Проверяет, имеют ли две структуры  com.aspose.psd.Rectangle  одинаковое расположение и размер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | Структура  com.aspose.psd.Rectangle , находящаяся слева от оператора равенства. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | Структура  com.aspose.psd.Rectangle , находящаяся справа от оператора равенства. |

**Returns:**
boolean - Этот оператор возвращает true, если две структуры  com.aspose.psd.Rectangle  имеют одинаковые свойства  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  и  com.aspose.psd.Rectangle.Height .
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Проверяет, отличаются ли две структуры  com.aspose.psd.Rectangle  расположением или размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | Структура  com.aspose.psd.Rectangle , находящаяся слева от оператора неравенства. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | Структура  com.aspose.psd.Rectangle , находящаяся справа от оператора неравенства. |

**Returns:**
boolean - Этот оператор возвращает true, если любые из свойств  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  или  com.aspose.psd.Rectangle.Height  двух структур  com.aspose.psd.Rectangle  не равны; иначе false.
### round(RectangleF value) {#round-com.aspose.psd.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Преобразует указанный com.aspose.psd.RectangleF в com.aspose.psd.Rectangle, округляя значения com.aspose.psd.RectangleF до ближайших целых чисел.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Объект  com.aspose.psd.RectangleF  для преобразования. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Получает или задаёт координату y, которая является суммой значений свойств  com.aspose.psd.Rectangle.Y  и  com.aspose.psd.Rectangle.Height  этой структуры  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Координата y, являющаяся суммой  com.aspose.psd.Rectangle.Y  и  com.aspose.psd.Rectangle.Height  данного  com.aspose.psd.Rectangle . |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Получает или задаёт высоту этой структуры  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Высота этой структуры  com.aspose.psd.Rectangle . |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Получает или задаёт координату x левого края этой структуры  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Координата x левого края этой структуры  com.aspose.psd.Rectangle . |

### setLocation(Point value) {#setLocation-com.aspose.psd.Point-}
```
public void setLocation(Point value)
```


Получает или задаёт координаты верхнего левого угла этой структуры  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) | Точка, представляющая верхний левый угол этой структуры com.aspose.psd.Rectangle. |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Получает или задаёт координату x, которая является суммой значений свойств  com.aspose.psd.Rectangle.X  и  com.aspose.psd.Rectangle.Width  этой структуры  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Координата x, являющаяся суммой com.aspose.psd.Rectangle.X и com.aspose.psd.Rectangle.Width этой структуры com.aspose.psd.Rectangle. |

### setSize(Size value) {#setSize-com.aspose.psd.Size-}
```
public void setSize(Size value)
```


Получает или задаёт размер этой структуры  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) | Объект com.aspose.psd.Size, представляющий ширину и высоту этой структуры com.aspose.psd.Rectangle. |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Получает или задаёт координату y верхнего края этой структуры  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Координата y верхнего края этой структуры com.aspose.psd.Rectangle. |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Устанавливает ширину этой структуры com.aspose.psd.Rectangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Ширина этой структуры com.aspose.psd.Rectangle. |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Получает или задаёт координату x верхнего левого угла этой структуры  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Координата x левого верхнего угла этой структуры com.aspose.psd.Rectangle. |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Получает или задаёт координату y верхнего левого угла этой структуры  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Координата y левого верхнего угла этой структуры com.aspose.psd.Rectangle. |

### toString() {#toString--}
```
public String toString()
```


Преобразует атрибуты этой структуры com.aspose.psd.Rectangle в читаемую строку.

**Returns:**
java.lang.String — строка, содержащая позицию, ширину и высоту этой структуры com.aspose.psd.Rectangle.
### truncate(RectangleF value) {#truncate-com.aspose.psd.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Преобразует указанный com.aspose.psd.RectangleF в com.aspose.psd.Rectangle, отбрасывая дробную часть значений com.aspose.psd.RectangleF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Объект  com.aspose.psd.RectangleF  для преобразования. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### union(Rectangle a, Rectangle b) {#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Возвращает структуру com.aspose.psd.Rectangle, содержащую объединение двух структур com.aspose.psd.Rectangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Первый прямоугольник для объединения. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Второй прямоугольник для объединения. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  structure that bounds the union of the two  com.aspose.psd.Rectangle  structures.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

