---
title: "Форма"
second_title: "Aspose.PSD for Java API Справочник"
description: "Форма."
type: docs
weight: 96
url: /ru/java/com.aspose.psd/shape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public abstract class Shape extends ObjectWithBounds
```

Форма. Непрерывный набор точек, соединённых по определённому правилу.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Shape()](#Shape--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Получает границы объекта. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Получает границы объекта. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Получает границы объекта. |
| [getCenter()](#getCenter--) | Получает центр формы. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | Получает сегменты формы. |
| [hasSegments()](#hasSegments--) | Получает значение, указывающее, имеет ли форма сегменты. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Применяет указанное преобразование к форме. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
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
### getBounds() {#getBounds--}
```
public abstract RectangleF getBounds()
```


Получает границы объекта.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public abstract RectangleF getBounds(Matrix matrix)
```


Получает границы объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Матрица, применяемая перед вычислением границ. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public abstract RectangleF getBounds(Matrix matrix, Pen pen)
```


Получает границы объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Матрица, применяемая перед вычислением границ. |
| pen | [Pen](../../com.aspose.psd/pen) | Ручка, используемая для объекта. Это может влиять на размер границ объекта. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public abstract PointF getCenter()
```


Получает центр формы.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The shape's center.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSegments() {#getSegments--}
```
public abstract ShapeSegment[] getSegments()
```


Получает сегменты формы.

**Returns:**
com.aspose.psd.ShapeSegment[] — сегменты формы.
### hasSegments() {#hasSegments--}
```
public abstract boolean hasSegments()
```


Получает значение, указывающее, имеет ли форма сегменты.

**Returns:**
boolean — True, если у формы есть сегменты; иначе false.
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




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public abstract void transform(Matrix transform)
```


Применяет указанное преобразование к форме.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | Преобразование, которое нужно применить. |

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

