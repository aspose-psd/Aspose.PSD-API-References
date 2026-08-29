---
title: "AutoMaskingArgs"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет аргументы, указанные для автоматических методов маскирования"
type: docs
weight: 11
url: /ru/java/com.aspose.psd.masking.options/automaskingargs/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.masking.options.IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Представляет аргументы, указанные для автоматических методов маскирования
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Получает максимальное количество итераций. |
| [getNumberOfObjects()](#getNumberOfObjects--) | Получает количество объектов, на которое разбивается исходное изображение (необязательно), значение по умолчанию — 2 (объект и фон). |
| [getObjectsPoints()](#getObjectsPoints--) | Получает точки, принадлежащие разделённым объектам (необязательно) NumberOfObjects координат, принадлежащих NumberOfObjects объектам исходного изображения. |
| [getObjectsRectangles()](#getObjectsRectangles--) | Получает прямоугольники объектов, принадлежащие разделённым объектам (необязательно). |
| [getOrphanedPoints()](#getOrphanedPoints--) | Получает точки, которые больше не принадлежат ни одному объекту (необязательно). |
| [getPrecision()](#getPrecision--) | Получает точность метода сегментации (необязательно). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Устанавливает максимальное количество итераций. |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | Устанавливает количество объектов, на которое разбивается исходное изображение (необязательно), значение по умолчанию — 2 (объект и фон). |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.psd.Point-----) | Устанавливает точки, принадлежащие разделённым объектам (необязательно) NumberOfObjects координат, принадлежащих NumberOfObjects объектам исходного изображения. |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.psd.Rectangle---) | Устанавливает прямоугольники объектов, принадлежащие разделённым объектам (необязательно). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.psd.Point---) | Устанавливает точки, которые больше не принадлежат ни одному объекту (необязательно). |
| [setPrecision(double value)](#setPrecision-double-) | Устанавливает точность метода сегментации (необязательно). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


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
### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


Получает максимальное количество итераций.

Значение: Максимальное максимальное количество итераций.

**Returns:**
int — максимальное количество итераций.
### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


Получает количество объектов, на которое разбивается исходное изображение (необязательно), значение по умолчанию — 2 (объект и фон).

Значение: Количество объектов.

**Returns:**
int — количество объектов, на которое разбивается исходное изображение (необязательно), значение по умолчанию — 2 (объект и фон).
### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Получает точки, принадлежащие разделённым объектам (необязательно) NumberOfObjects координат, принадлежащих NumberOfObjects объектам исходного изображения. Этот параметр используется для повышения точности метода сегментации.

Значение: Точки объектов.

**Returns:**
com.aspose.psd.Point[][] - точки, которые принадлежат отдельным объектам (необязательно) NumberOfObjects координат, которые принадлежат NumberOfObjects объектам исходного изображения.
### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Получает прямоугольники объектов, которые принадлежат отдельным объектам (необязательно). Этот параметр используется для повышения точности метода сегментации.

Значение: Прямоугольники объектов.

**Returns:**
com.aspose.psd.Rectangle[] - прямоугольники объектов, которые принадлежат отдельным объектам (необязательно).
### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Получает точки, которые больше не принадлежат ни одному объекту (необязательно). Этот параметр используется только в случае повторной сегментации.

Значение: Оставшиеся без привязки точки.

**Returns:**
com.aspose.psd.Point[] - точки, которые больше не принадлежат ни одному объекту (необязательно).
### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Получает точность метода сегментации (необязательно).

Значение: Точность метода сегментации (необязательно).

**Returns:**
double - точность метода сегментации (необязательно).
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




### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


Устанавливает максимальное количество итераций.

Значение: Максимальное максимальное количество итераций.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | максимальное количество итераций. |

### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


Устанавливает количество объектов, на которое разбивается исходное изображение (необязательно), значение по умолчанию — 2 (объект и фон).

Значение: Количество объектов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | количество объектов, на которые следует разделить исходное изображение (необязательно), значение по умолчанию — 2 (объект и фон). |

### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.psd.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Устанавливает точки, которые принадлежат отдельным объектам (необязательно) NumberOfObjects координат, которые принадлежат NumberOfObjects объектам исходного изображения. Этот параметр используется для повышения точности метода сегментации.

Значение: Точки объектов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | точки, которые принадлежат отдельным объектам (необязательно) NumberOfObjects координат, которые принадлежат NumberOfObjects объектам исходного изображения. |

### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.psd.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Устанавливает прямоугольники объектов, которые принадлежат отдельным объектам (необязательно). Этот параметр используется для повышения точности метода сегментации.

Значение: Прямоугольники объектов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | прямоугольники объектов, которые принадлежат отдельным объектам (необязательно). |

### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.psd.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Устанавливает точки, которые больше не принадлежат ни одному объекту (необязательно). Этот параметр используется только в случае повторной сегментации.

Значение: Оставшиеся без привязки точки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | точки, которые больше не принадлежат ни одному объекту (необязательно). |

### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Устанавливает точность метода сегментации (необязательно).

Значение: Точность метода сегментации (необязательно).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | точность метода сегментации (необязательно). |

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

