---
title: "EllipseShape"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет форму эллипса."
type: docs
weight: 13
url: /ru/java/com.aspose.psd.shapes/ellipseshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape)
```
public class EllipseShape extends RectangleShape
```

Представляет форму эллипса.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EllipseShape()](#EllipseShape--) | Инициализирует новый экземпляр класса EllipseShape. |
| [EllipseShape(RectangleF rectangle)](#EllipseShape-com.aspose.psd.RectangleF-) | Инициализирует новый экземпляр класса EllipseShape. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Получает границы объекта. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Получает границы объекта. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Получает границы объекта. |
| [getCenter()](#getCenter--) | Получает центр формы. |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Получает левую нижнюю точку прямоугольника. |
| [getLeftTop()](#getLeftTop--) | Получает левую верхнюю точку прямоугольника. |
| [getRectangleHeight()](#getRectangleHeight--) | Получает высоту прямоугольника. |
| [getRectangleWidth()](#getRectangleWidth--) | Получает ширину прямоугольника. |
| [getRightBottom()](#getRightBottom--) | Получает правую нижнюю точку прямоугольника. |
| [getRightTop()](#getRightTop--) | Получает правую верхнюю точку прямоугольника. |
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
### EllipseShape() {#EllipseShape--}
```
public EllipseShape()
```


Инициализирует новый экземпляр класса EllipseShape.

### EllipseShape(RectangleF rectangle) {#EllipseShape-com.aspose.psd.RectangleF-}
```
public EllipseShape(RectangleF rectangle)
```


Инициализирует новый экземпляр класса EllipseShape.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Прямоугольник. |

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

