---
title: "ArcShape"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет форму дуги."
type: docs
weight: 10
url: /ru/java/com.aspose.psd.shapes/arcshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape), [com.aspose.psd.shapes.EllipseShape](../../com.aspose.psd.shapes/ellipseshape), [com.aspose.psd.shapes.PieShape](../../com.aspose.psd.shapes/pieshape)

**All Implemented Interfaces:**
[com.aspose.psd.IOrderedShape](../../com.aspose.psd/iorderedshape)
```
public final class ArcShape extends PieShape implements IOrderedShape
```

Представляет форму дуги.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ArcShape()](#ArcShape--) | Создаёт новый экземпляр класса  ArcShape . |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)](#ArcShape-com.aspose.psd.RectangleF-float-float-) | Создаёт новый экземпляр класса  ArcShape . |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)](#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-) | Создаёт новый экземпляр класса  ArcShape . |
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
| [getLeftBottom()](#getLeftBottom--) | Получает левую нижнюю точку прямоугольника. |
| [getLeftTop()](#getLeftTop--) | Получает левую верхнюю точку прямоугольника. |
| [getRectangleHeight()](#getRectangleHeight--) | Получает высоту прямоугольника. |
| [getRectangleWidth()](#getRectangleWidth--) | Получает ширину прямоугольника. |
| [getRightBottom()](#getRightBottom--) | Получает правую нижнюю точку прямоугольника. |
| [getRightTop()](#getRightTop--) | Получает правую верхнюю точку прямоугольника. |
| [getSegments()](#getSegments--) | Получает сегменты формы. |
| [getStartAngle()](#getStartAngle--) | Получает или задает начальный угол. |
| [getStartPoint()](#getStartPoint--) | Возвращает начальную точку формы. |
| [getSweepAngle()](#getSweepAngle--) | Получает или задает угол разворота. |
| [hasSegments()](#hasSegments--) | Получает значение, указывающее, имеет ли форма сегменты. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Получает или задаёт значение, указывающее, закрыта ли упорядоченная фигура. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Меняет порядок точек для этой формы. |
| [setClosed(boolean value)](#setClosed-boolean-) | Получает или задаёт значение, указывающее, закрыта ли упорядоченная фигура. |
| [setStartAngle(float value)](#setStartAngle-float-) | Получает или задает начальный угол. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Получает или задает угол разворота. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Применяет указанное преобразование к форме. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArcShape() {#ArcShape--}
```
public ArcShape()
```


Создаёт новый экземпляр класса  ArcShape .

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle) {#ArcShape-com.aspose.psd.RectangleF-float-float-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Создаёт новый экземпляр класса  ArcShape .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Прямоугольник. |
| startAngle | float | Начальный угол. |
| sweepAngle | float | Угол разворота. |

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed) {#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)
```


Создаёт новый экземпляр класса  ArcShape .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Прямоугольник. |
| startAngle | float | Начальный угол. |
| sweepAngle | float | Угол разворота. |
| isClosed | boolean | Если установить значение  true , дуга будет закрытой. Закрытая дуга фактически вырождается в эллипс. |

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
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Получает левую нижнюю точку прямоугольника.

Значение: левая нижняя точка прямоугольника.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Получает левую верхнюю точку прямоугольника.

Значение: левая верхняя точка прямоугольника.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Получает высоту прямоугольника.

Значение: высота прямоугольника.

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Получает ширину прямоугольника.

Значение: ширина прямоугольника.

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Получает правую нижнюю точку прямоугольника.

Значение: Правый нижний угол прямоугольника.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Получает правую верхнюю точку прямоугольника.

Значение: Правый верхний угол прямоугольника.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Получает сегменты формы.

Значение: Сегменты фигуры.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Получает или задает начальный угол.

Значение: Начальный угол.

**Returns:**
float
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Возвращает начальную точку формы.

Значение: Начальная точка фигуры.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Получает или задает угол разворота.

Значение: Угол разворота.

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


Получает или задаёт значение, указывающее, закрыта ли упорядоченная фигура. При обработке закрытой упорядоченной фигуры начальная и конечная точки не имеют значения.

Значение:  True  если эта упорядоченная фигура закрыта; иначе,  false .

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


Получает или задаёт значение, указывающее, закрыта ли упорядоченная фигура. При обработке закрытой упорядоченной фигуры начальная и конечная точки не имеют значения.

Значение:  True  если эта упорядоченная фигура закрыта; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Получает или задает начальный угол.

Значение: Начальный угол.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Получает или задает угол разворота.

Значение: Угол разворота.

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

