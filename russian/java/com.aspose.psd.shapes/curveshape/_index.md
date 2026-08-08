---
title: "CurveShape"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет форму изогнутого сплайна."
type: docs
weight: 12
url: /ru/java/com.aspose.psd.shapes/curveshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.PolygonShape](../../com.aspose.psd.shapes/polygonshape)
```
public final class CurveShape extends PolygonShape
```

Представляет форму изогнутого сплайна.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CurveShape()](#CurveShape--) | Инициализирует новый экземпляр класса  CurveShape  . |
| [CurveShape(PointF[] points)](#CurveShape-com.aspose.psd.PointF---) | Инициализирует новый экземпляр класса  CurveShape  . |
| [CurveShape(PointF[] points, boolean isClosed)](#CurveShape-com.aspose.psd.PointF---boolean-) | Инициализирует новый экземпляр класса  CurveShape  . |
| [CurveShape(PointF[] points, float tension)](#CurveShape-com.aspose.psd.PointF---float-) | Инициализирует новый экземпляр класса  CurveShape  . |
| [CurveShape(PointF[] points, float tension, boolean isClosed)](#CurveShape-com.aspose.psd.PointF---float-boolean-) | Инициализирует новый экземпляр класса  CurveShape  . |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Получает границы объекта. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Получает границы объекта. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Получает границы объекта. |
| [getCenter()](#getCenter--) | Получает центр формы. |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Возвращает конечную точку формы. |
| [getPoints()](#getPoints--) | Получает или задает точки кривой. |
| [getSegments()](#getSegments--) | Получает сегменты формы. |
| [getStartPoint()](#getStartPoint--) | Возвращает начальную точку формы. |
| [getTension()](#getTension--) | Получает или задает натяжение кривой. |
| [hasSegments()](#hasSegments--) | Получает значение, указывающее, имеет ли форма сегменты. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Получает или задает значение, указывающее, замкнута ли фигура. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Меняет порядок точек для этой формы. |
| [setClosed(boolean value)](#setClosed-boolean-) | Получает или задает значение, указывающее, замкнута ли фигура. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.psd.PointF---) | Получает или задает точки кривой. |
| [setTension(float value)](#setTension-float-) | Получает или задает натяжение кривой. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Применяет указанное преобразование к форме. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurveShape() {#CurveShape--}
```
public CurveShape()
```


Инициализирует новый экземпляр класса  CurveShape  .

### CurveShape(PointF[] points) {#CurveShape-com.aspose.psd.PointF---}
```
public CurveShape(PointF[] points)
```


Инициализирует новый экземпляр класса  CurveShape  . По умолчанию используется натяжение 0.5.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив точек. |

### CurveShape(PointF[] points, boolean isClosed) {#CurveShape-com.aspose.psd.PointF---boolean-}
```
public CurveShape(PointF[] points, boolean isClosed)
```


Инициализирует новый экземпляр класса  CurveShape  . По умолчанию используется натяжение 0.5.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив точек. |
| isClosed | boolean |  |

### CurveShape(PointF[] points, float tension) {#CurveShape-com.aspose.psd.PointF---float-}
```
public CurveShape(PointF[] points, float tension)
```


Инициализирует новый экземпляр класса  CurveShape  .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив точек. |
| натяжение | float | Натяжение кривой. |

### CurveShape(PointF[] points, float tension, boolean isClosed) {#CurveShape-com.aspose.psd.PointF---float-boolean-}
```
public CurveShape(PointF[] points, float tension, boolean isClosed)
```


Инициализирует новый экземпляр класса  CurveShape  .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив точек. |
| натяжение | float | Натяжение кривой. |
| isClosed | boolean | если установить значение  true , кривая будет замкнута. |

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
public RectangleF getBounds()
```


Получает границы объекта.

Значение: границы объекта.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
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
public RectangleF getBounds(Matrix matrix, Pen pen)
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
public PointF getCenter()
```


Получает центр формы.

Значение: центр формы.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Возвращает конечную точку формы.

Значение: Конечная точка фигуры.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Получает или задает точки кривой.

Значение: Точки кривой.

**Returns:**
com.aspose.psd.PointF[]
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Получает сегменты формы.

Значение: Сегменты фигуры.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Возвращает начальную точку формы.

Значение: Начальная точка фигуры.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getTension() {#getTension--}
```
public float getTension()
```


Получает или задает натяжение кривой.

Значение: Натяжение кривой.

**Returns:**
float
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Получает значение, указывающее, имеет ли форма сегменты.

Значение:  True  если у фигуры есть сегменты; иначе,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Получает или задает значение, указывающее, замкнута ли фигура.

Значение:  true  если фигура замкнута; иначе,  false .

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




### reverse() {#reverse--}
```
public void reverse()
```


Меняет порядок точек для этой формы.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Получает или задает значение, указывающее, замкнута ли фигура.

Значение:  true  если фигура замкнута; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setPoints(PointF[] value) {#setPoints-com.aspose.psd.PointF---}
```
public void setPoints(PointF[] value)
```


Получает или задает точки кривой.

Значение: Точки кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Получает или задает натяжение кривой.

Значение: Натяжение кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
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

