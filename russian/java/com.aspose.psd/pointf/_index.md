---
title: "PointF"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет упорядоченную пару чисел с плавающей запятой x и y, определяющих точку в двумерной плоскости."
type: docs
weight: 83
url: /ru/java/com.aspose.psd/pointf/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

Представляет упорядоченную пару чисел с плавающей запятой x и y, определяющих точку в двумерной плоскости.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | Инициализирует новый экземпляр структуры  com.aspose.psd.PointF  с указанными координатами. |
## Методы

| Метод | Описание |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(PointF that)](#CloneTo-com.aspose.psd.PointF-) |  |
| [add(PointF point, Size size)](#add-com.aspose.psd.PointF-com.aspose.psd.Size-) | Перемещает заданный  com.aspose.psd.PointF  на указанное значение  com.aspose.psd.Size . |
| [add(PointF point, SizeF size)](#add-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Перемещает заданный  com.aspose.psd.PointF  на указанное значение  com.aspose.psd.SizeF . |
| [equals(Object obj)](#equals-java.lang.Object-) | Указывает, содержит ли этот  com.aspose.psd.PointF  те же координаты, что и указанный  System.Object . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Получает новый экземпляр структуры  com.aspose.psd.PointF , у которой значения  com.aspose.psd.PointF.X  и  com.aspose.psd.PointF.Y  установлены в ноль. |
| [getX()](#getX--) | Получает или задает координату x этого  com.aspose.psd.PointF . |
| [getY()](#getY--) | Получает или задает координату y этого  com.aspose.psd.PointF . |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этой структуры  com.aspose.psd.PointF . |
| [isEmpty()](#isEmpty--) | Получает значение, указывающее, пустой ли этот  com.aspose.psd.PointF . |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.psd.PointF-com.aspose.psd.PointF-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.psd.PointF-com.aspose.psd.Size-) | Перемещает  com.aspose.psd.PointF  на заданный  com.aspose.psd.Size . |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Перемещает  com.aspose.psd.PointF  на указанное значение  com.aspose.psd.SizeF . |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Сравнивает две структуры  com.aspose.psd.PointF . |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Определяет, не равны ли координаты указанных точек. |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.Size-) | Перемещает  com.aspose.psd.PointF  на отрицательное значение заданного  com.aspose.psd.Size . |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Перемещает объект com.aspose.psd.PointF на отрицательное значение указанного com.aspose.psd.SizeF. |
| [setX(float value)](#setX-float-) | Получает или задает координату x этого  com.aspose.psd.PointF . |
| [setY(float value)](#setY-float-) | Получает или задает координату y этого  com.aspose.psd.PointF . |
| [subtract(PointF point, Size size)](#subtract-com.aspose.psd.PointF-com.aspose.psd.Size-) | Перемещает объект com.aspose.psd.PointF на отрицательное значение указанного размера. |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Перемещает объект com.aspose.psd.PointF на отрицательное значение указанного размера. |
| [toString()](#toString--) | Преобразует этот com.aspose.psd.PointF в читаемую строку. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


Инициализирует новый экземпляр структуры  com.aspose.psd.PointF  с указанными координатами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Горизонтальное положение точки. |
| y | float | Вертикальное положение точки. |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.psd/pointf)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(PointF that) {#CloneTo-com.aspose.psd.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [PointF](../../com.aspose.psd/pointf) |  |

### add(PointF point, Size size) {#add-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF add(PointF point, Size size)
```


Перемещает заданный  com.aspose.psd.PointF  на указанное значение  com.aspose.psd.Size .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Объект com.aspose.psd.PointF для перемещения. |
| size | [Size](../../com.aspose.psd/size) | Объект com.aspose.psd.Size, определяющий числа, добавляемые к координатам точки. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### add(PointF point, SizeF size) {#add-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


Перемещает заданный  com.aspose.psd.PointF  на указанное значение  com.aspose.psd.SizeF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Объект com.aspose.psd.PointF для перемещения. |
| size | [SizeF](../../com.aspose.psd/sizef) | Объект com.aspose.psd.SizeF, определяющий числа, добавляемые к координатам точки. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Указывает, содержит ли этот  com.aspose.psd.PointF  те же координаты, что и указанный  System.Object .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект  System.Object  для проверки. |

**Returns:**
boolean - Этот метод возвращает true, если obj является com.aspose.psd.PointF и имеет те же координаты, что и этот com.aspose.psd.Point.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


Получает новый экземпляр структуры  com.aspose.psd.PointF , у которой значения  com.aspose.psd.PointF.X  и  com.aspose.psd.PointF.Y  установлены в ноль.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getX() {#getX--}
```
public float getX()
```


Получает или задает координату x этого  com.aspose.psd.PointF .

**Returns:**
float
### getY() {#getY--}
```
public float getY()
```


Получает или задает координату y этого  com.aspose.psd.PointF .

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этой структуры  com.aspose.psd.PointF .

**Returns:**
int - Целочисленное значение, определяющее хеш для этой структуры com.aspose.psd.PointF.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Получает значение, указывающее, пустой ли этот  com.aspose.psd.PointF .

**Returns:**
boolean - True, если оба com.aspose.psd.PointF.X и com.aspose.psd.PointF.Y равны 0; иначе false.
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.psd/pointf) |  |
| obj2 | [PointF](../../com.aspose.psd/pointf) |  |

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




### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


Перемещает  com.aspose.psd.PointF  на заданный  com.aspose.psd.Size .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Объект com.aspose.psd.PointF для перемещения. |
| size | [Size](../../com.aspose.psd/size) | Объект com.aspose.psd.Size, определяющий пару чисел для добавления к координатам точки. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - Returns the translated  com.aspose.psd.PointF .
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


Перемещает  com.aspose.psd.PointF  на указанное значение  com.aspose.psd.SizeF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Объект com.aspose.psd.PointF для перемещения. |
| size | [SizeF](../../com.aspose.psd/sizef) | Объект com.aspose.psd.SizeF, определяющий числа для добавления к x- и y-координатам точки. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


Сравнивает две структуры com.aspose.psd.PointF. Результат указывает, равны ли значения свойств com.aspose.psd.PointF.X и com.aspose.psd.PointF.Y у обеих структур com.aspose.psd.PointF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Первый com.aspose.psd.PointF для сравнения. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Второй com.aspose.psd.PointF для сравнения. |

**Returns:**
boolean - True, если значения com.aspose.psd.PointF.X и com.aspose.psd.PointF.Y первых и вторых структур com.aspose.psd.PointF равны; иначе false.
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


Определяет, не равны ли координаты указанных точек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Первый com.aspose.psd.PointF для сравнения. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Второй com.aspose.psd.PointF для сравнения. |

**Returns:**
boolean - True, указывая, что значения com.aspose.psd.PointF.X и com.aspose.psd.PointF.Y точек point1 и point2 не равны; иначе false.
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


Перемещает  com.aspose.psd.PointF  на отрицательное значение заданного  com.aspose.psd.Size .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Объект com.aspose.psd.PointF для перемещения. |
| size | [Size](../../com.aspose.psd/size) | Объект com.aspose.psd.Size, определяющий числа, вычитаемые из x- и y-координат точки. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


Перемещает объект com.aspose.psd.PointF на отрицательное значение указанного com.aspose.psd.SizeF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Объект com.aspose.psd.PointF для перемещения. |
| size | [SizeF](../../com.aspose.psd/sizef) | Объект com.aspose.psd.SizeF, определяющий числа, вычитаемые из координат точки. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Получает или задает координату x этого  com.aspose.psd.PointF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Получает или задает координату y этого  com.aspose.psd.PointF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### subtract(PointF point, Size size) {#subtract-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF subtract(PointF point, Size size)
```


Перемещает объект com.aspose.psd.PointF на отрицательное значение указанного размера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Объект com.aspose.psd.PointF для перемещения. |
| size | [Size](../../com.aspose.psd/size) | Объект com.aspose.psd.Size, определяющий числа, вычитаемые из координат точки. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### subtract(PointF point, SizeF size) {#subtract-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


Перемещает объект com.aspose.psd.PointF на отрицательное значение указанного размера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Объект com.aspose.psd.PointF для перемещения. |
| size | [SizeF](../../com.aspose.psd/sizef) | Объект com.aspose.psd.SizeF, определяющий числа, вычитаемые из координат точки. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### toString() {#toString--}
```
public String toString()
```


Преобразует этот com.aspose.psd.PointF в читаемую строку.

**Returns:**
java.lang.String - Строка, представляющая этот com.aspose.psd.PointF.
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

