---
title: "RectangleExtensions"
second_title: "Aspose.PSD for Java API Справочник"
description: "Содержит методы расширения для Rectangle."
type: docs
weight: 23
url: /ru/java/com.aspose.psd.extensions/rectangleextensions/
---

**Inheritance:**
java.lang.Object
```
public final class RectangleExtensions
```

Содержит методы расширения для  Rectangle .
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toGdiRectangle(Rectangle rectangle)](#toGdiRectangle-com.aspose.psd.Rectangle-) | Преобразует  Rectangle  в  System.Drawing.Rectangle . |
| [toGdiRectangle(RectangleF rectangle)](#toGdiRectangle-com.aspose.psd.RectangleF-) | Преобразует  RectangleF  в  System.Drawing.Rectangle . |
| [toString()](#toString--) |  |
| [unionWith(RectangleF rectangle, RectangleF otherRectangle)](#unionWith-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Объединяет два прямоугольника. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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




### toGdiRectangle(Rectangle rectangle) {#toGdiRectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle toGdiRectangle(Rectangle rectangle)
```


Преобразует  Rectangle  в  System.Drawing.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник для преобразования. |

**Returns:**
[Rectangle](../../java.awt/rectangle) - The converted  System.Drawing.Rectangle .
### toGdiRectangle(RectangleF rectangle) {#toGdiRectangle-com.aspose.psd.RectangleF-}
```
public static Rectangle2D.Float toGdiRectangle(RectangleF rectangle)
```


Преобразует  RectangleF  в  System.Drawing.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Прямоугольник для преобразования. |

**Returns:**
java.awt.geom.Rectangle2D.Float - Преобразованный  System.Drawing.RectangleF .
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unionWith(RectangleF rectangle, RectangleF otherRectangle) {#unionWith-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF unionWith(RectangleF rectangle, RectangleF otherRectangle)
```


Объединяет два прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Первый прямоугольник. |
| otherRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Второй прямоугольник. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - New rectangle as union operation result
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

