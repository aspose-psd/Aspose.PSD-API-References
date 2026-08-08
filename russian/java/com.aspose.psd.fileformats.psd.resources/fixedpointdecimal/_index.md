---
title: "FixedPointDecimal"
second_title: "Aspose.PSD for Java API Справочник"
description: "Фиксированная точка с 16-битным целым и 16-битной дробной частью."
type: docs
weight: 17
url: /ru/java/com.aspose.psd.fileformats.psd.resources/fixedpointdecimal/
---

**Inheritance:**
java.lang.Object
```
public class FixedPointDecimal
```

Фиксированная точка с десятичным представлением, 16-битное целое и 16-битная дробная часть.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FixedPointDecimal(int integer, int fraction)](#FixedPointDecimal-int-int-) | Инициализирует новый экземпляр класса [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal). |
| [FixedPointDecimal(long value)](#FixedPointDecimal-long-) | Инициализирует новый экземпляр класса [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal). |
| [FixedPointDecimal(double value)](#FixedPointDecimal-double-) | Инициализирует новый экземпляр класса [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal). |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFraction()](#getFraction--) | Получает или задает дробную часть. |
| [getInteger()](#getInteger--) | Получает или задает целую часть. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFraction(int value)](#setFraction-int-) | Получает или задает дробную часть. |
| [setInteger(int value)](#setInteger-int-) | Получает или задает целую часть. |
| [toDouble()](#toDouble--) | Преобразует текущий фиксированный десятичный тип в double. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FixedPointDecimal(int integer, int fraction) {#FixedPointDecimal-int-int-}
```
public FixedPointDecimal(int integer, int fraction)
```


Инициализирует новый экземпляр класса [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| целое | int | Целое. |
| дробная часть | int | Дробная часть. |

### FixedPointDecimal(long value) {#FixedPointDecimal-long-}
```
public FixedPointDecimal(long value)
```


Инициализирует новый экземпляр класса [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal). Разделяет старшие и младшие слова 32-битного целого на фиксированное число.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long | Значение. |

### FixedPointDecimal(double value) {#FixedPointDecimal-double-}
```
public FixedPointDecimal(double value)
```


Инициализирует новый экземпляр класса [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Значение. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFraction() {#getFraction--}
```
public final int getFraction()
```


Получает или задает дробную часть.

Значение: Дробная часть.

**Returns:**
int
### getInteger() {#getInteger--}
```
public final int getInteger()
```


Получает или задает целую часть.

Значение: Целое.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFraction(int value) {#setFraction-int-}
```
public final void setFraction(int value)
```


Получает или задает дробную часть.

Значение: Дробная часть.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setInteger(int value) {#setInteger-int-}
```
public final void setInteger(int value)
```


Получает или задает целую часть.

Значение: Целое.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```


Преобразует текущий фиксированный десятичный тип в double.

**Returns:**
double — Преобразованное значение.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

