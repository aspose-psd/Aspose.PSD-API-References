---
title: "Point"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет упорядоченную пару целочисленных координат x и y, определяющих точку в двумерной плоскости."
type: docs
weight: 82
url: /ru/java/com.aspose.psd/point/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Представляет упорядоченную пару целочисленных координат x и y, определяющих точку в двумерной плоскости.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Инициализирует новый экземпляр структуры Aspose.Imaging.Point с указанными координатами. |
| [Point(Size size)](#Point-com.aspose.psd.Size-) | Инициализирует новый экземпляр структуры Aspose.Imaging.Point из структуры Aspose.Imaging.Size. |
| [Point(int dw)](#Point-int-) | Инициализирует новый экземпляр структуры Aspose.Imaging.Point, используя координаты, указанные целочисленным значением. |
## Поля

| Поле | Описание |
| --- | --- |
| [PointFormat_internalized](#PointFormat-internalized) | Представляет формат точки. |
## Методы

| Метод | Описание |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Point that)](#CloneTo-com.aspose.psd.Point-) |  |
| [add(Point point, Size size)](#add-com.aspose.psd.Point-com.aspose.psd.Size-) | Добавляет указанный  Aspose.Imaging.Size  к указанному  Aspose.Imaging.Point . |
| [ceiling(PointF point)](#ceiling-com.aspose.psd.PointF-) | Преобразует указанный  Aspose.Imaging.PointF  в  Aspose.Imaging.Point , округляя значения  Aspose.Imaging.PointF  до следующего большего целого значения. |
| [equals(Object obj)](#equals-java.lang.Object-) | Указывает, содержит ли данный  Aspose.Imaging.Point  те же координаты, что и указанный  System.Object . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Получает новый экземпляр структуры  Aspose.Imaging.Point , у которой значения  Aspose.Imaging.Point.X  и  Aspose.Imaging.Point.Y  установлены в ноль. |
| [getX()](#getX--) | Получает или задает координату x этой  Aspose.Imaging.Point . |
| [getY()](#getY--) | Получает или задает координату y этой  Aspose.Imaging.Point . |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этой  Aspose.Imaging.Point . |
| [isEmpty()](#isEmpty--) | Получает значение, указывающее, пустой ли этот  Aspose.Imaging.Point . |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point point)](#offset-com.aspose.psd.Point-) | Смещает этот  Aspose.Imaging.Point  на указанный  Aspose.Imaging.Point . |
| [offset(int dx, int dy)](#offset-int-int-) | Смещает этот  Aspose.Imaging.Point  на указанную величину. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-) | Смещает  Aspose.Imaging.Point  на заданный  Aspose.Imaging.Size . |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-) | Сравнивает два объекта  Aspose.Imaging.Point . |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-) | Сравнивает два объекта  Aspose.Imaging.Point . |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-) | Смещает  Aspose.Imaging.Point  на отрицательное значение заданного  Aspose.Imaging.Size . |
| [round(PointF point)](#round-com.aspose.psd.PointF-) | Преобразует указанный  Aspose.Imaging.PointF  в объект  Aspose.Imaging.Point , округляя значения  Aspose.Imaging.Point  до ближайшего целого. |
| [setX(int value)](#setX-int-) | Получает или задает координату x этой  Aspose.Imaging.Point . |
| [setY(int value)](#setY-int-) | Получает или задает координату y этой  Aspose.Imaging.Point . |
| [subtract(Point point, Size size)](#subtract-com.aspose.psd.Point-com.aspose.psd.Size-) | Возвращает результат вычитания указанного  Aspose.Imaging.Size  из указанного  Aspose.Imaging.Point . |
| [toString()](#toString--) | Преобразует эту  Aspose.Imaging.Point  в человекочитаемую строку. |
| [to_PointF(Point point)](#to-PointF-com.aspose.psd.Point-) | Преобразует указанную структуру  Point  в структуру  PointF . |
| [to_Size(Point point)](#to-Size-com.aspose.psd.Point-) | Преобразует указанную структуру  Aspose.Imaging.Point  в структуру  Aspose.Imaging.Size . |
| [truncate(PointF point)](#truncate-com.aspose.psd.PointF-) | Преобразует указанный  Aspose.Imaging.PointF  в  Aspose.Imaging.Point , усекшая значения  Aspose.Imaging.Point . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Инициализирует новый экземпляр структуры Aspose.Imaging.Point с указанными координатами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Горизонтальное положение точки. |
| y | int | Вертикальное положение точки. |

### Point(Size size) {#Point-com.aspose.psd.Size-}
```
public Point(Size size)
```


Инициализирует новый экземпляр структуры Aspose.Imaging.Point из структуры Aspose.Imaging.Size.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Содержит новые координаты точки. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Инициализирует новый экземпляр структуры Aspose.Imaging.Point, используя координаты, указанные целочисленным значением.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dw | int | 32-битное целое число, указывающее координаты новой точки. |

### PointFormat_internalized {#PointFormat-internalized}
```
public static final String PointFormat_internalized
```


Представляет формат точки.

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.psd/point)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Point that) {#CloneTo-com.aspose.psd.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [Point](../../com.aspose.psd/point) |  |

### add(Point point, Size size) {#add-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point add(Point point, Size size)
```


Добавляет указанный  Aspose.Imaging.Size  к указанному  Aspose.Imaging.Point .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Точка  Aspose.Imaging.Point  для добавления. |
| size | [Size](../../com.aspose.psd/size) | Размер  Aspose.Imaging.Size  для добавления к точке . |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the addition operation.
### ceiling(PointF point) {#ceiling-com.aspose.psd.PointF-}
```
public static Point ceiling(PointF point)
```


Преобразует указанный  Aspose.Imaging.PointF  в  Aspose.Imaging.Point , округляя значения  Aspose.Imaging.PointF  до следующего большего целого значения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Aspose.Imaging.PointF для преобразования. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Указывает, содержит ли данный  Aspose.Imaging.Point  те же координаты, что и указанный  System.Object .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект  System.Object  для проверки. |

**Returns:**
boolean - Истина, если obj является Aspose.Imaging.Point и имеет те же координаты, что и этот Aspose.Imaging.Point.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Получает новый экземпляр структуры  Aspose.Imaging.Point , у которой значения  Aspose.Imaging.Point.X  и  Aspose.Imaging.Point.Y  установлены в ноль.

**Returns:**
[Point](../../com.aspose.psd/point)
### getX() {#getX--}
```
public int getX()
```


Получает или задает координату x этой  Aspose.Imaging.Point .

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


Получает или задает координату y этой  Aspose.Imaging.Point .

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этой  Aspose.Imaging.Point .

**Returns:**
int - Хеш-код для этого экземпляра, подходящий для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Получает значение, указывающее, пустой ли этот  Aspose.Imaging.Point .

**Returns:**
boolean - Истина, если оба Aspose.Imaging.Point.X и Aspose.Imaging.Point.Y равны 0; иначе — ложь.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.psd/point) |  |
| obj2 | [Point](../../com.aspose.psd/point) |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(Point point) {#offset-com.aspose.psd.Point-}
```
public void offset(Point point)
```


Смещает этот  Aspose.Imaging.Point  на указанный  Aspose.Imaging.Point .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Aspose.Imaging.Point, используемый для смещения этого Aspose.Imaging.Point. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Смещает этот  Aspose.Imaging.Point  на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | int | Величина смещения координаты x. |
| dy | int | Величина смещения координаты y. |

### op_Addition(Point point, Size size) {#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Смещает  Aspose.Imaging.Point  на заданный  Aspose.Imaging.Size .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Aspose.Imaging.Point для трансляции. |
| size | [Size](../../com.aspose.psd/size) | Aspose.Imaging.Size, определяющий пару чисел для добавления к координатам point. |

**Returns:**
[Point](../../com.aspose.psd/point) - The translated  Aspose.Imaging.Point .
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Сравнивает два объекта Aspose.Imaging.Point. Результат указывает, равны ли значения свойств Aspose.Imaging.Point.X и Aspose.Imaging.Point.Y у обоих объектов Aspose.Imaging.Point.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Первый Aspose.Imaging.Point для сравнения. |
| point2 | [Point](../../com.aspose.psd/point) | Второй Aspose.Imaging.Point для сравнения. |

**Returns:**
boolean - Истина, если значения Aspose.Imaging.Point.X и Aspose.Imaging.Point.Y у point1 и point2 равны; иначе — ложь.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Сравнивает два объекта Aspose.Imaging.Point. Результат указывает, не равны ли значения свойств Aspose.Imaging.Point.X или Aspose.Imaging.Point.Y у двух объектов Aspose.Imaging.Point.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Первый Aspose.Imaging.Point для сравнения. |
| point2 | [Point](../../com.aspose.psd/point) | Второй Aspose.Imaging.Point для сравнения. |

**Returns:**
boolean - Истина, если значения свойства Aspose.Imaging.Point.X или свойства Aspose.Imaging.Point.Y у point1 и point2 различаются; иначе — ложь.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Смещает  Aspose.Imaging.Point  на отрицательное значение заданного  Aspose.Imaging.Size .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Aspose.Imaging.Point для трансляции. |
| size | [Size](../../com.aspose.psd/size) | Aspose.Imaging.Size, определяющий пару чисел для вычитания из координат point. |

**Returns:**
[Point](../../com.aspose.psd/point) - A  Aspose.Imaging.Point  structure that is translated by the negative of a given  Aspose.Imaging.Size  structure.
### round(PointF point) {#round-com.aspose.psd.PointF-}
```
public static Point round(PointF point)
```


Преобразует указанный  Aspose.Imaging.PointF  в объект  Aspose.Imaging.Point , округляя значения  Aspose.Imaging.Point  до ближайшего целого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Aspose.Imaging.PointF для преобразования. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Получает или задает координату x этой  Aspose.Imaging.Point .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Получает или задает координату y этой  Aspose.Imaging.Point .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### subtract(Point point, Size size) {#subtract-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point subtract(Point point, Size size)
```


Возвращает результат вычитания указанного  Aspose.Imaging.Size  из указанного  Aspose.Imaging.Point .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Aspose.Imaging.Point, из которого будет вычитаться. |
| size | [Size](../../com.aspose.psd/size) | Aspose.Imaging.Size для вычитания из point. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Преобразует эту  Aspose.Imaging.Point  в человекочитаемую строку.

**Returns:**
java.lang.String -  System.String  представляющий этот экземпляр.
### to_PointF(Point point) {#to-PointF-com.aspose.psd.Point-}
```
public static PointF to_PointF(Point point)
```


Преобразует указанную структуру  Point  в структуру  PointF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Point для преобразования. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  PointF  that results from the conversion.
### to_Size(Point point) {#to-Size-com.aspose.psd.Point-}
```
public static Size to_Size(Point point)
```


Преобразует указанную структуру  Aspose.Imaging.Point  в структуру  Aspose.Imaging.Size .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Aspose.Imaging.Point для преобразования. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that results from the conversion.
### truncate(PointF point) {#truncate-com.aspose.psd.PointF-}
```
public static Point truncate(PointF point)
```


Преобразует указанный  Aspose.Imaging.PointF  в  Aspose.Imaging.Point , усекшая значения  Aspose.Imaging.Point .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Aspose.Imaging.PointF для преобразования. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
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

