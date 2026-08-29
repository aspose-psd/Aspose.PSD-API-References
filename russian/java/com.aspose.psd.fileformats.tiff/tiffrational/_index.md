---
title: "TiffRational"
second_title: "Aspose.PSD for Java API Справочник"
description: "Тип rational TIFF."
type: docs
weight: 12
url: /ru/java/com.aspose.psd.fileformats.tiff/tiffrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffRational
```

Тип rational TIFF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffRational()](#TiffRational--) | Инициализирует новый экземпляр класса  TiffRational  . |
| [TiffRational(long value)](#TiffRational-long-) | Инициализирует новый экземпляр класса  TiffRational  . |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | Инициализирует новый экземпляр класса  TiffRational  . |
## Поля

| Поле | Описание |
| --- | --- |
| [Epsilon](#Epsilon) | Эпсилон для вычисления дроби |
## Методы

| Метод | Описание |
| --- | --- |
| [approximateFraction(double value)](#approximateFraction-double-) | Аппроксимирует предоставленное значение до дроби. |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Аппроксимирует предоставленное значение до дроби. |
| [approximateFraction(float value)](#approximateFraction-float-) | Аппроксимирует предоставленное значение до дроби. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Аппроксимирует предоставленное значение до дроби. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный объект этому экземпляру. |
| [getClass()](#getClass--) |  |
| [getDenominator()](#getDenominator--) | Получает знаменатель. |
| [getNominator()](#getNominator--) | Получает числитель. |
| [getValue()](#getValue--) | Получает значение float. |
| [getValueD()](#getValueD--) | Получает двойное значение. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает  System.String  который представляет этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


Инициализирует новый экземпляр класса  TiffRational  .

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


Инициализирует новый экземпляр класса  TiffRational  .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | long | Значение числителя. |

Числитель будет использоваться как указанное значение, а знаменатель будет равен 1. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


Инициализирует новый экземпляр класса  TiffRational  .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| числитель | long | Числитель. |
| знаменатель | long | Знаменатель. |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


Эпсилон для вычисления дроби

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


Аппроксимирует предоставленное значение до дроби.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Значение. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


Аппроксимирует предоставленное значение до дроби.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Значение. |
| эпсилон | double | Допустимая ошибка. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


Аппроксимирует предоставленное значение до дроби.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Значение. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


Аппроксимирует предоставленное значение до дроби.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Значение. |
| эпсилон | double | Допустимая ошибка. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный объект этому экземпляру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения с этим экземпляром. |

**Returns:**
boolean — true, если указанный объект равен этому экземпляру; иначе — false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDenominator() {#getDenominator--}
```
public long getDenominator()
```


Получает знаменатель.

Значение: знаменатель.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


Получает числитель.

Значение: числитель.

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


Получает значение float.

Значение: Значение типа float.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Получает двойное значение.

Значение: значение типа double.

**Returns:**
double
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int - Хеш-код для этого экземпляра, подходящий для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Возвращает  System.String  который представляет этот экземпляр.

**Returns:**
java.lang.String -  System.String  представляющий этот экземпляр.
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

