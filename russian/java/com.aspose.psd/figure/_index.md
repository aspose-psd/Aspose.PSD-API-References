---
title: "Фигура"
second_title: "Aspose.PSD for Java API Справочник"
description: "Фигура."
type: docs
weight: 42
url: /ru/java/com.aspose.psd/figure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

Фигура. Контейнер для фигур.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Figure()](#Figure--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [addShape(Shape shape)](#addShape-com.aspose.psd.Shape-) | Добавляет форму к фигуре. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.psd.Shape---) | Добавляет диапазон форм к фигуре. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Получает или задает границы объекта. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Получает границы объекта. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Получает границы объекта. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | Получает все сегменты фигуры. |
| [getShapes()](#getShapes--) | Получает формы фигуры. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Получает значение, указывающее, замкнута ли эта фигура. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeShape(Shape shape)](#removeShape-com.aspose.psd.Shape-) | Удаляет форму из фигуры. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.psd.Shape---) | Удаляет диапазон форм из фигуры. |
| [reverse()](#reverse--) | Меняет порядок форм этой фигуры и порядок точек форм в обратном порядке. |
| [setClosed(boolean value)](#setClosed-boolean-) | Задает значение, указывающее, замкнута ли эта фигура. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Применяет указанное преобразование к форме. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Figure() {#Figure--}
```
public Figure()
```


### addShape(Shape shape) {#addShape-com.aspose.psd.Shape-}
```
public void addShape(Shape shape)
```


Добавляет форму к фигуре.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | Форма для добавления. |

### addShapes(Shape[] shapes) {#addShapes-com.aspose.psd.Shape---}
```
public void addShapes(Shape[] shapes)
```


Добавляет диапазон форм к фигуре.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | Формы для добавления. |

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


Получает или задает границы объекта.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Получает все сегменты фигуры.

**Returns:**
com.aspose.psd.ShapeSegment[] - Сегменты фигуры.
### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Получает формы фигуры.

**Returns:**
com.aspose.psd.Shape[] - Формы фигуры.
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


Получает значение, указывающее, замкнута ли эта фигура. Замкнутая фигура будет иметь значение только в случае, когда первая и последняя формы фигуры являются непрерывными. В таком случае первая точка первой формы будет соединена прямой линией с последней точкой последней формы.

**Returns:**
boolean -  True  если эта фигура замкнута; иначе,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeShape(Shape shape) {#removeShape-com.aspose.psd.Shape-}
```
public void removeShape(Shape shape)
```


Удаляет форму из фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | Форма для удаления. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.psd.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Удаляет диапазон форм из фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | Диапазон форм для удаления. |

### reverse() {#reverse--}
```
public void reverse()
```


Меняет порядок форм этой фигуры и порядок точек форм в обратном порядке.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Задает значение, указывающее, замкнута ли эта фигура. Замкнутая фигура будет иметь значение только в случае, когда первая и последняя формы фигуры являются непрерывными. В таком случае первая точка первой формы будет соединена прямой линией с последней точкой последней формы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | True  если эта фигура замкнута; иначе,  false . |

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

