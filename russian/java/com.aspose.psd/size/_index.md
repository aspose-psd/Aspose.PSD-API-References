---
title: "Size"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет размер."
type: docs
weight: 98
url: /ru/java/com.aspose.psd/size/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

Представляет размер.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.psd.Point-) | Инициализирует новый экземпляр структуры Aspose.Imaging.Size из указанного Aspose.Imaging.Point. |
| [Size(int width, int height)](#Size-int-int-) | Инициализирует новый экземпляр структуры Aspose.Imaging.Size из указанных размеров. |
## Методы

| Метод | Описание |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Size that)](#CloneTo-com.aspose.psd.Size-) |  |
| [add(Size size1, Size size2)](#add-com.aspose.psd.Size-com.aspose.psd.Size-) | Добавляет ширину и высоту одной структуры Aspose.Imaging.Size к ширине и высоте другой структуры Aspose.Imaging.Size. |
| [ceiling(SizeF size)](#ceiling-com.aspose.psd.SizeF-) | Преобразует указанную структуру Aspose.Imaging.SizeF в структуру Aspose.Imaging.Size, округляя значения структуры Aspose.Imaging.Size до ближайшего большего целого. |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверяет, является ли указанный объект Aspose.Imaging.Size с теми же размерами, что и этот Aspose.Imaging.Size. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Получает новый экземпляр структуры  Aspose.Imaging.Size , у которой значения  Aspose.Imaging.Size.Width  и  Aspose.Imaging.Size.Height  установлены в ноль. |
| [getHeight()](#getHeight--) | Получает или задает вертикальную компоненту этой структуры  Aspose.Imaging.Size . |
| [getWidth()](#getWidth--) | Получает или задает горизонтальную компоненту этой структуры  Aspose.Imaging.Size . |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этой структуры  Aspose.Imaging.Size . |
| [isEmpty()](#isEmpty--) | Получает значение, указывающее, имеет ли эта структура  Aspose.Imaging.Size  ширину и высоту, равные 0. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-) | Добавляет ширину и высоту одной структуры Aspose.Imaging.Size к ширине и высоте другой структуры Aspose.Imaging.Size. |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-) | Проверяет, равны ли две структуры  Aspose.Imaging.Size . |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-) | Проверяет, различаются ли две структуры  Aspose.Imaging.Size . |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-) | Вычитает ширину и высоту одной структуры  Aspose.Imaging.Size  из ширины и высоты другой структуры  Aspose.Imaging.Size . |
| [round(SizeF size)](#round-com.aspose.psd.SizeF-) | Преобразует указанную структуру  Aspose.Imaging.SizeF  в структуру  Aspose.Imaging.Size , округляя значения структуры  Aspose.Imaging.SizeF  до ближайших целых чисел. |
| [setHeight(int value)](#setHeight-int-) | Получает или задает вертикальную компоненту этой структуры  Aspose.Imaging.Size . |
| [setWidth(int value)](#setWidth-int-) | Получает или задает горизонтальную компоненту этой структуры  Aspose.Imaging.Size . |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.psd.Size-com.aspose.psd.Size-) | Вычитает ширину и высоту одной структуры  Aspose.Imaging.Size  из ширины и высоты другой структуры  Aspose.Imaging.Size . |
| [toString()](#toString--) | Создает человекочитаемую строку, представляющую эту структуру  Aspose.Imaging.Size . |
| [to_Point(Size size)](#to-Point-com.aspose.psd.Size-) | Преобразует указанную структуру  Aspose.Imaging.Size  в объект  Aspose.Imaging.Point . |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.psd.Size-) | Преобразует указанную структуру  Aspose.Imaging.Size  в структуру  Aspose.Imaging.SizeF . |
| [truncate(SizeF size)](#truncate-com.aspose.psd.SizeF-) | Преобразует указанную структуру  Aspose.Imaging.SizeF  в структуру  Aspose.Imaging.Size , отбрасывая значения структуры  Aspose.Imaging.SizeF  до следующего меньшего целого. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.psd.Point-}
```
public Size(Point point)
```


Инициализирует новый экземпляр структуры Aspose.Imaging.Size из указанного Aspose.Imaging.Point.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Точка  Aspose.Imaging.Point , из которой инициализируется эта структура  Aspose.Imaging.Size . |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Инициализирует новый экземпляр структуры Aspose.Imaging.Size из указанных размеров.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ширина | int | Компонента ширины новой структуры  Aspose.Imaging.Size . |
| высота | int | Компонента высоты новой структуры  Aspose.Imaging.Size . |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.psd/size)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Size that) {#CloneTo-com.aspose.psd.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [Size](../../com.aspose.psd/size) |  |

### add(Size size1, Size size2) {#add-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size add(Size size1, Size size2)
```


Добавляет ширину и высоту одной структуры Aspose.Imaging.Size к ширине и высоте другой структуры Aspose.Imaging.Size.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Первая структура  Aspose.Imaging.Size  для сложения. |
| size2 | [Size](../../com.aspose.psd/size) | Вторая структура  Aspose.Imaging.Size  для сложения. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.psd.SizeF-}
```
public static Size ceiling(SizeF size)
```


Преобразует указанную структуру Aspose.Imaging.SizeF в структуру Aspose.Imaging.Size, округляя значения структуры Aspose.Imaging.Size до ближайшего большего целого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Структура  Aspose.Imaging.SizeF  для преобразования. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверяет, является ли указанный объект Aspose.Imaging.Size с теми же размерами, что и этот Aspose.Imaging.Size.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект  System.Object  для проверки. |

**Returns:**
boolean - Истина, если  obj  является объектом  Aspose.Imaging.Size  и имеет такую же ширину и высоту, как эта  Aspose.Imaging.Size ; в противном случае — ложь.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


Получает новый экземпляр структуры  Aspose.Imaging.Size , у которой значения  Aspose.Imaging.Size.Width  и  Aspose.Imaging.Size.Height  установлены в ноль.

**Returns:**
[Size](../../com.aspose.psd/size)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает или задает вертикальную компоненту этой структуры  Aspose.Imaging.Size .

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает или задает горизонтальную компоненту этой структуры  Aspose.Imaging.Size .

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этой структуры  Aspose.Imaging.Size .

**Returns:**
int - Целочисленное значение, задающее хеш для этой структуры  Aspose.Imaging.Size .
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Получает значение, указывающее, имеет ли эта структура  Aspose.Imaging.Size  ширину и высоту, равные 0.

**Returns:**
boolean
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.psd/size) |  |
| obj2 | [Size](../../com.aspose.psd/size) |  |

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




### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


Добавляет ширину и высоту одной структуры Aspose.Imaging.Size к ширине и высоте другой структуры Aspose.Imaging.Size.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Первая структура  Aspose.Imaging.Size  для сложения. |
| size2 | [Size](../../com.aspose.psd/size) | Вторая структура  Aspose.Imaging.Size  для сложения. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


Проверяет, равны ли две структуры  Aspose.Imaging.Size .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Структура  Aspose.Imaging.Size  слева от оператора равенства. |
| size2 | [Size](../../com.aspose.psd/size) | Структура  Aspose.Imaging.Size  справа от оператора равенства. |

**Returns:**
boolean - Истина, если  size1  и  size2  имеют одинаковую ширину и высоту; в противном случае — ложь.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


Проверяет, различаются ли две структуры  Aspose.Imaging.Size .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Структура  Aspose.Imaging.Size  слева от оператора неравенства. |
| size2 | [Size](../../com.aspose.psd/size) | Структура  Aspose.Imaging.Size  находится справа от оператора неравенства. |

**Returns:**
boolean - true, если  size1  и  size2  различаются по ширине или высоте; false, если  size1  и  size2  равны.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


Вычитает ширину и высоту одной структуры  Aspose.Imaging.Size  из ширины и высоты другой структуры  Aspose.Imaging.Size .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Структура  Aspose.Imaging.Size  находится слева от оператора вычитания. |
| size2 | [Size](../../com.aspose.psd/size) | Структура  Aspose.Imaging.Size  находится справа от оператора вычитания. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the subtraction operation.
### round(SizeF size) {#round-com.aspose.psd.SizeF-}
```
public static Size round(SizeF size)
```


Преобразует указанную структуру  Aspose.Imaging.SizeF  в структуру  Aspose.Imaging.Size , округляя значения структуры  Aspose.Imaging.SizeF  до ближайших целых чисел.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Структура  Aspose.Imaging.SizeF  для преобразования. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Получает или задает вертикальную компоненту этой структуры  Aspose.Imaging.Size .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Получает или задает горизонтальную компоненту этой структуры  Aspose.Imaging.Size .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### subtract(Size size1, Size size2) {#subtract-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size subtract(Size size1, Size size2)
```


Вычитает ширину и высоту одной структуры  Aspose.Imaging.Size  из ширины и высоты другой структуры  Aspose.Imaging.Size .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Структура  Aspose.Imaging.Size  находится слева от оператора вычитания. |
| size2 | [Size](../../com.aspose.psd/size) | Структура  Aspose.Imaging.Size  находится справа от оператора вычитания. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that is a result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Создает человекочитаемую строку, представляющую эту структуру  Aspose.Imaging.Size .

**Returns:**
java.lang.String - Строка, представляющая этот  Aspose.Imaging.Size .
### to_Point(Size size) {#to-Point-com.aspose.psd.Size-}
```
public static Point to_Point(Size size)
```


Преобразует указанную структуру  Aspose.Imaging.Size  в объект  Aspose.Imaging.Point .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Структура  Aspose.Imaging.Size  для преобразования. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  structure to which this operator converts.
### to_SizeF(Size size) {#to-SizeF-com.aspose.psd.Size-}
```
public static SizeF to_SizeF(Size size)
```


Преобразует указанную структуру  Aspose.Imaging.Size  в структуру  Aspose.Imaging.SizeF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Структура  Aspose.Imaging.Size  для преобразования. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The  Aspose.Imaging.SizeF  structure to which this operator converts.
### truncate(SizeF size) {#truncate-com.aspose.psd.SizeF-}
```
public static Size truncate(SizeF size)
```


Преобразует указанную структуру  Aspose.Imaging.SizeF  в структуру  Aspose.Imaging.Size , отбрасывая значения структуры  Aspose.Imaging.SizeF  до следующего меньшего целого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Структура  Aspose.Imaging.SizeF  для преобразования. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
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

