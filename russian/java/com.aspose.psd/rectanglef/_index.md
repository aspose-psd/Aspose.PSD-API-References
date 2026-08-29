---
title: "RectangleF"
second_title: "Aspose.PSD for Java API Справочник"
description: "Сохраняет набор из четырёх чисел с плавающей запятой, представляющих положение и размер прямоугольника."
type: docs
weight: 89
url: /ru/java/com.aspose.psd/rectanglef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Сохраняет набор из четырёх чисел с плавающей запятой, представляющих положение и размер прямоугольника.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Инициализирует новый экземпляр структуры  com.aspose.psd.RectangleF  с указанным расположением и размером. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Инициализирует новый экземпляр структуры  com.aspose.psd.RectangleF  с указанным расположением и размером. |
## Методы

| Метод | Описание |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.psd.RectangleF-) |  |
| [contains(PointF point)](#contains-com.aspose.psd.PointF-) | Определяет, содержит ли указанная точка эту структуру  com.aspose.psd.RectangleF . |
| [contains(RectangleF rect)](#contains-com.aspose.psd.RectangleF-) | Определяет, полностью ли прямоугольный регион, представленный  rect , содержится в этой структуре  com.aspose.psd.RectangleF . |
| [contains(float x, float y)](#contains-float-float-) | Определяет, содержит ли указанная точка эту структуру  com.aspose.psd.RectangleF . |
| [create_internalized(float x, float y, SizeF size)](#create-internalized-float-float-com.aspose.psd.SizeF-) |  |
| [divideToTransformMatrix_internalized(double[] transformMatrix)](#divideToTransformMatrix-internalized-double---) | Делит текущие значения прямоугольника для преобразования вертикальных и горизонтальных масштабов матрицы и возвращает новый экземпляр [RectangleF](../../com.aspose.psd/rectanglef) с полученными значениями. |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверяет, является ли  obj  объектом  com.aspose.psd.RectangleF  с тем же расположением и размером, что и этот  com.aspose.psd.RectangleF . |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Создаёт структуру  com.aspose.psd.RectangleF  с верхним левым и нижним правым углом в указанных позициях. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Создаёт новый  Rectangle  из двух указанных точек. |
| [getBottom()](#getBottom--) | Получает или задаёт координату y, которая является суммой  com.aspose.psd.RectangleF.Y  и  com.aspose.psd.RectangleF.Height  этой структуры  com.aspose.psd.RectangleF . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Получает новый экземпляр структуры  com.aspose.psd.RectangleF , у которой значения  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  и  com.aspose.psd.RectangleF.Height  установлены в ноль. |
| [getHeight()](#getHeight--) | Получает или задаёт высоту этой структуры  com.aspose.psd.RectangleF . |
| [getLeft()](#getLeft--) | Получает или задаёт координату x левой границы этой структуры  com.aspose.psd.RectangleF . |
| [getLocation()](#getLocation--) | Получает или задаёт координаты верхнего левого угла этой структуры  com.aspose.psd.RectangleF . |
| [getRight()](#getRight--) | Получает или задаёт координату x, которая является суммой  com.aspose.psd.RectangleF.X  и  com.aspose.psd.RectangleF.Width  этой структуры  com.aspose.psd.RectangleF . |
| [getSize()](#getSize--) | Получает или задает размер этого com.aspose.psd.RectangleF. |
| [getTop()](#getTop--) | Получает или задает координату y верхнего края этой структуры com.aspose.psd.RectangleF. |
| [getWidth()](#getWidth--) | Получает или задает ширину этой структуры com.aspose.psd.RectangleF. |
| [getX()](#getX--) | Получает или задает координату x верхнего левого угла этой структуры com.aspose.psd.RectangleF. |
| [getY()](#getY--) | Получает или задает координату y верхнего левого угла этой структуры com.aspose.psd.RectangleF. |
| [hashCode()](#hashCode--) | Получает хеш-код этой структуры com.aspose.psd.RectangleF. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.psd.RectangleF-float-float-) | Создает и возвращает расширенную копию указанной структуры com.aspose.psd.RectangleF. |
| [inflate(SizeF size)](#inflate-com.aspose.psd.SizeF-) | Расширяет этот com.aspose.psd.RectangleF на указанную величину. |
| [inflate(float x, float y)](#inflate-float-float-) | Расширяет эту структуру com.aspose.psd.RectangleF на указанную величину. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Заменяет эту структуру com.aspose.psd.RectangleF пересечением её с указанной структурой com.aspose.psd.RectangleF. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Возвращает структуру com.aspose.psd.RectangleF, представляющую пересечение двух прямоугольников. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.psd.RectangleF-) | Определяет, пересекается ли этот прямоугольник с rect. |
| [isEmpty()](#isEmpty--) | Получает значение, указывающее, имеет ли свойство com.aspose.psd.RectangleF.Width или com.aspose.psd.RectangleF.Height этой структуры com.aspose.psd.RectangleF значение ноль. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) |  |
| [multiplyToTransformMatrix_internalized(double[] transformMatrix)](#multiplyToTransformMatrix-internalized-double---) | Умножает текущие значения прямоугольника для преобразования вертикальных и горизонтальных масштабов матрицы и возвращает новый экземпляр [RectangleF](../../com.aspose.psd/rectanglef) с полученными значениями. |
| [normalize()](#normalize--) | Нормализует прямоугольник, делая его ширину и высоту положительными, левую сторону меньше правой и верхнюю меньше нижней. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(PointF pos)](#offset-com.aspose.psd.PointF-) | Корректирует положение этого прямоугольника на указанную величину. |
| [offset(float x, float y)](#offset-float-float-) | Корректирует положение этого прямоугольника на указанную величину. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.psd.RectangleF-float-) | Реализует оператор /. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Проверяет, имеют ли две структуры com.aspose.psd.RectangleF одинаковое положение и размер. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Проверяет, различаются ли две структуры com.aspose.psd.RectangleF по положению или размеру. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.psd.RectangleF-float-) | Реализует оператор \*. |
| [setBottom(float value)](#setBottom-float-) | Получает или задаёт координату y, которая является суммой  com.aspose.psd.RectangleF.Y  и  com.aspose.psd.RectangleF.Height  этой структуры  com.aspose.psd.RectangleF . |
| [setHeight(float value)](#setHeight-float-) | Получает или задаёт высоту этой структуры  com.aspose.psd.RectangleF . |
| [setLeft(float value)](#setLeft-float-) | Получает или задаёт координату x левой границы этой структуры  com.aspose.psd.RectangleF . |
| [setLocation(PointF value)](#setLocation-com.aspose.psd.PointF-) | Получает или задаёт координаты верхнего левого угла этой структуры  com.aspose.psd.RectangleF . |
| [setRight(float value)](#setRight-float-) | Получает или задаёт координату x, которая является суммой  com.aspose.psd.RectangleF.X  и  com.aspose.psd.RectangleF.Width  этой структуры  com.aspose.psd.RectangleF . |
| [setSize(SizeF value)](#setSize-com.aspose.psd.SizeF-) | Получает или задает размер этого com.aspose.psd.RectangleF. |
| [setTop(float value)](#setTop-float-) | Получает или задает координату y верхнего края этой структуры com.aspose.psd.RectangleF. |
| [setWidth(float value)](#setWidth-float-) | Получает или задает ширину этой структуры com.aspose.psd.RectangleF. |
| [setX(float value)](#setX-float-) | Получает или задает координату x верхнего левого угла этой структуры com.aspose.psd.RectangleF. |
| [setY(float value)](#setY-float-) | Получает или задает координату y верхнего левого угла этой структуры com.aspose.psd.RectangleF. |
| [toRectangle_internalized()](#toRectangle-internalized--) | Преобразует [RectangleF](../../com.aspose.psd/rectanglef) в структуру [Rectangle](../../com.aspose.psd/rectangle) с усечёнными значениями прямоугольника. |
| [toString()](#toString--) | Преобразует атрибуты этого com.aspose.psd.RectangleF в читаемую человеком строку. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.psd.Rectangle-) | Преобразует указанную структуру com.aspose.psd.Rectangle в структуру com.aspose.psd.RectangleF. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Создаёт наименьший возможный третий прямоугольник, который может содержать оба прямоугольника, образующих объединение. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Инициализирует новый экземпляр структуры  com.aspose.psd.RectangleF  с указанным расположением и размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x верхнего левого угла прямоугольника. |
| y | float | Y‑координата верхнего левого угла прямоугольника. |
| ширина | float | Ширина прямоугольника. |
| высота | float | Высота прямоугольника. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Инициализирует новый экземпляр структуры  com.aspose.psd.RectangleF  с указанным расположением и размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| location | [PointF](../../com.aspose.psd/pointf) | Объект  com.aspose.psd.PointF  , представляющий верхний левый угол прямоугольной области. |
| size | [SizeF](../../com.aspose.psd/sizef) | Объект  com.aspose.psd.SizeF  , представляющий ширину и высоту прямоугольной области. |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(RectangleF that) {#CloneTo-com.aspose.psd.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### contains(PointF point) {#contains-com.aspose.psd.PointF-}
```
public boolean contains(PointF point)
```


Определяет, содержит ли указанная точка эту структуру  com.aspose.psd.RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Объект  com.aspose.psd.PointF  для проверки. |

**Returns:**
boolean — Этот метод возвращает true, если точка, представленная параметром  point , находится внутри этой структуры  com.aspose.psd.RectangleF ; в противном случае false.
### contains(RectangleF rect) {#contains-com.aspose.psd.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Определяет, полностью ли прямоугольный регион, представленный  rect , содержится в этой структуре  com.aspose.psd.RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Объект  com.aspose.psd.RectangleF  для проверки. |

**Returns:**
boolean — Этот метод возвращает true, если прямоугольная область, представленная параметром  rect , полностью содержится в прямоугольной области, представленной этой структурой  com.aspose.psd.RectangleF ; в противном случае false.
### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Определяет, содержит ли указанная точка эту структуру  com.aspose.psd.RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | X‑координата точки для проверки. |
| y | float | Y‑координата точки для проверки. |

**Returns:**
boolean — Этот метод возвращает true, если точка, определённая параметрами  x  и  y , находится внутри этой структуры  com.aspose.psd.RectangleF ; в противном случае false.
### create_internalized(float x, float y, SizeF size) {#create-internalized-float-float-com.aspose.psd.SizeF-}
```
public static RectangleF create_internalized(float x, float y, SizeF size)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float |  |
| y | float |  |
| size | [SizeF](../../com.aspose.psd/sizef) |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### divideToTransformMatrix_internalized(double[] transformMatrix) {#divideToTransformMatrix-internalized-double---}
```
public final RectangleF divideToTransformMatrix_internalized(double[] transformMatrix)
```


Делит текущие значения прямоугольника для преобразования вертикальных и горизонтальных масштабов матрицы и возвращает новый экземпляр [RectangleF](../../com.aspose.psd/rectanglef) с полученными значениями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| transformMatrix | double[] | Матрица преобразования слоя. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with divided values.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверяет, является ли  obj  объектом  com.aspose.psd.RectangleF  с тем же расположением и размером, что и этот  com.aspose.psd.RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект  System.Object  для проверки. |

**Returns:**
boolean — Этот метод возвращает true, если  obj  является  com.aspose.psd.RectangleF  и его свойства X, Y, Width и Height равны соответствующим свойствам этой  com.aspose.psd.RectangleF ; в противном случае false.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Создаёт структуру  com.aspose.psd.RectangleF  с верхним левым и нижним правым углом в указанных позициях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | float | X‑координата верхнего левого угла прямоугольной области. |
| top | float | Y‑координата верхнего левого угла прямоугольной области. |
| right | float | X‑координата нижнего правого угла прямоугольной области. |
| bottom | float | Y‑координата нижнего правого угла прямоугольной области. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The new  com.aspose.psd.RectangleF  that this method creates.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Создаёт новый  Rectangle  из двух указанных точек. Две вершины созданного  Rectangle  будут равны переданным  point1  и  point2 . Обычно это противоположные вершины.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Первый пункт для нового прямоугольника. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Второй пункт для нового прямоугольника. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public float getBottom()
```


Получает или задаёт координату y, которая является суммой  com.aspose.psd.RectangleF.Y  и  com.aspose.psd.RectangleF.Height  этой структуры  com.aspose.psd.RectangleF .

**Returns:**
float — Координата y, являющаяся суммой com.aspose.psd.RectangleF.Y и com.aspose.psd.RectangleF.Height этой структуры com.aspose.psd.RectangleF.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


Получает новый экземпляр структуры  com.aspose.psd.RectangleF , у которой значения  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  и  com.aspose.psd.RectangleF.Height  установлены в ноль.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


Получает или задаёт высоту этой структуры  com.aspose.psd.RectangleF .

**Returns:**
float — Высота этой структуры com.aspose.psd.RectangleF.
### getLeft() {#getLeft--}
```
public float getLeft()
```


Получает или задаёт координату x левой границы этой структуры  com.aspose.psd.RectangleF .

**Returns:**
float — Координата x левой границы этой структуры com.aspose.psd.RectangleF.
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Получает или задаёт координаты верхнего левого угла этой структуры  com.aspose.psd.RectangleF .

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  com.aspose.psd.PointF  that represents the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getRight() {#getRight--}
```
public float getRight()
```


Получает или задаёт координату x, которая является суммой  com.aspose.psd.RectangleF.X  и  com.aspose.psd.RectangleF.Width  этой структуры  com.aspose.psd.RectangleF .

**Returns:**
float — Координата x, являющаяся суммой com.aspose.psd.RectangleF.X и com.aspose.psd.RectangleF.Width этой структуры com.aspose.psd.RectangleF.
### getSize() {#getSize--}
```
public SizeF getSize()
```


Получает или задает размер этого com.aspose.psd.RectangleF.

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  com.aspose.psd.SizeF  that represents the width and height of this  com.aspose.psd.RectangleF  structure.
### getTop() {#getTop--}
```
public float getTop()
```


Получает или задает координату y верхнего края этой структуры com.aspose.psd.RectangleF.

**Returns:**
float — Координата y верхней границы этой структуры com.aspose.psd.RectangleF.
### getWidth() {#getWidth--}
```
public float getWidth()
```


Получает или задает ширину этой структуры com.aspose.psd.RectangleF.

**Returns:**
float — Ширина этой структуры com.aspose.psd.RectangleF.
### getX() {#getX--}
```
public float getX()
```


Получает или задает координату x верхнего левого угла этой структуры com.aspose.psd.RectangleF.

**Returns:**
float — Координата x верхнего левого угла этой структуры com.aspose.psd.RectangleF.
### getY() {#getY--}
```
public float getY()
```


Получает или задает координату y верхнего левого угла этой структуры com.aspose.psd.RectangleF.

**Returns:**
float — Координата y верхнего левого угла этой структуры com.aspose.psd.RectangleF.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш-код этой структуры com.aspose.psd.RectangleF.

**Returns:**
int — Хеш-код для этого com.aspose.psd.RectangleF.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.psd.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Создаёт и возвращает увеличенную копию указанной структуры com.aspose.psd.RectangleF. Копия увеличивается на указанную величину. Исходный прямоугольник остаётся неизменным.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура com.aspose.psd.RectangleF, которую нужно скопировать. Этот прямоугольник не изменяется. |
| x | float | Величина, на которую следует увеличить копию прямоугольника по горизонтали. |
| y | float | Величина, на которую следует увеличить копию прямоугольника по вертикали. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The inflated  com.aspose.psd.RectangleF .
### inflate(SizeF size) {#inflate-com.aspose.psd.SizeF-}
```
public void inflate(SizeF size)
```


Расширяет этот com.aspose.psd.RectangleF на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Величина, на которую следует увеличить этот прямоугольник. |

### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Расширяет эту структуру com.aspose.psd.RectangleF на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Величина, на которую следует увеличить эту структуру com.aspose.psd.RectangleF по горизонтали. |
| y | float | Величина, на которую следует увеличить эту структуру com.aspose.psd.RectangleF по вертикали. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Заменяет эту структуру com.aspose.psd.RectangleF пересечением её с указанной структурой com.aspose.psd.RectangleF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Прямоугольник для пересечения. |

### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Возвращает структуру com.aspose.psd.RectangleF, представляющую пересечение двух прямоугольников. Если пересечения нет, возвращается пустой com.aspose.psd.RectangleF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Первый прямоугольник для пересечения. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Второй прямоугольник для пересечения. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure the size of which represents the overlapped area of the two specified rectangles.
### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.psd.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Определяет, пересекается ли этот прямоугольник с rect.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Прямоугольник для проверки. |

**Returns:**
boolean — Этот метод возвращает true, если существует какое-либо пересечение.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Получает значение, указывающее, имеет ли свойство com.aspose.psd.RectangleF.Width или com.aspose.psd.RectangleF.Height этой структуры com.aspose.psd.RectangleF значение ноль.

**Returns:**
boolean — Это свойство возвращает true, если свойство com.aspose.psd.RectangleF.Width или com.aspose.psd.RectangleF.Height этой структуры com.aspose.psd.RectangleF имеет значение ноль; в противном случае — false.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.psd/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.psd/rectanglef) |  |

**Returns:**
boolean
### multiplyToTransformMatrix_internalized(double[] transformMatrix) {#multiplyToTransformMatrix-internalized-double---}
```
public final RectangleF multiplyToTransformMatrix_internalized(double[] transformMatrix)
```


Умножает текущие значения прямоугольника для преобразования вертикальных и горизонтальных масштабов матрицы и возвращает новый экземпляр [RectangleF](../../com.aspose.psd/rectanglef) с полученными значениями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| transformMatrix | double[] | Матрица преобразования слоя. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with multiplied values.
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




### offset(PointF pos) {#offset-com.aspose.psd.PointF-}
```
public void offset(PointF pos)
```


Корректирует положение этого прямоугольника на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.psd/pointf) | Величина смещения местоположения. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Корректирует положение этого прямоугольника на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Величина смещения местоположения по горизонтали. |
| y | float | Величина смещения местоположения по вертикали. |

### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Реализует оператор /.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Прямоугольник. |
| разделитель | float | Разделитель. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Проверяет, имеют ли две структуры com.aspose.psd.RectangleF одинаковое положение и размер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | Структура  com.aspose.psd.RectangleF  слева от оператора равенства. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | Структура  com.aspose.psd.RectangleF  справа от оператора равенства. |

**Returns:**
boolean - Этот оператор возвращает true, если две указанные структуры  com.aspose.psd.RectangleF  имеют одинаковые свойства  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width , и  com.aspose.psd.RectangleF.Height .
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Проверяет, различаются ли две структуры com.aspose.psd.RectangleF по положению или размеру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | Структура  com.aspose.psd.RectangleF  слева от оператора неравенства. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | Структура  com.aspose.psd.RectangleF  справа от оператора неравенства. |

**Returns:**
boolean - Этот оператор возвращает true, если любое из свойств  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  или  com.aspose.psd.RectangleF.Height  двух структур  com.aspose.psd.RectangleF  не равно; в противном случае false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Реализует оператор \*.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Прямоугольник. |
| множитель | float | Множитель. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Получает или задаёт координату y, которая является суммой  com.aspose.psd.RectangleF.Y  и  com.aspose.psd.RectangleF.Height  этой структуры  com.aspose.psd.RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Получает или задаёт высоту этой структуры  com.aspose.psd.RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Получает или задаёт координату x левой границы этой структуры  com.aspose.psd.RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setLocation(PointF value) {#setLocation-com.aspose.psd.PointF-}
```
public void setLocation(PointF value)
```


Получает или задаёт координаты верхнего левого угла этой структуры  com.aspose.psd.RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Получает или задаёт координату x, которая является суммой  com.aspose.psd.RectangleF.X  и  com.aspose.psd.RectangleF.Width  этой структуры  com.aspose.psd.RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setSize(SizeF value) {#setSize-com.aspose.psd.SizeF-}
```
public void setSize(SizeF value)
```


Получает или задает размер этого com.aspose.psd.RectangleF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) |  |

### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Получает или задает координату y верхнего края этой структуры com.aspose.psd.RectangleF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Получает или задает ширину этой структуры com.aspose.psd.RectangleF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Получает или задает координату x верхнего левого угла этой структуры com.aspose.psd.RectangleF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Получает или задает координату y верхнего левого угла этой структуры com.aspose.psd.RectangleF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### toRectangle_internalized() {#toRectangle-internalized--}
```
public final Rectangle toRectangle_internalized()
```


Преобразует [RectangleF](../../com.aspose.psd/rectanglef) в структуру [Rectangle](../../com.aspose.psd/rectangle) с усечёнными значениями прямоугольника.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a [Rectangle](../../com.aspose.psd/rectangle) structure.
### toString() {#toString--}
```
public String toString()
```


Преобразует атрибуты этого com.aspose.psd.RectangleF в читаемую человеком строку.

**Returns:**
java.lang.String - Строка, содержащая позицию, ширину и высоту этой структуры  com.aspose.psd.RectangleF .
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.psd.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Преобразует указанную структуру com.aspose.psd.Rectangle в структуру com.aspose.psd.RectangleF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура  com.aspose.psd.Rectangle  для преобразования. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The  com.aspose.psd.RectangleF  structure that is converted from the specified  com.aspose.psd.Rectangle  structure.
### union(RectangleF a, RectangleF b) {#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Создаёт наименьший возможный третий прямоугольник, который может содержать оба прямоугольника, образующих объединение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Первый прямоугольник для объединения. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Второй прямоугольник для объединения. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure that contains both of the two rectangles that form the union.
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

