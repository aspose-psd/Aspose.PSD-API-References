---
title: RectangleExtensions
second_title: Aspose.PSD for Java API Reference
description: Contains extension methods for Rectangle.
type: docs
weight: 23
url: /java/com.aspose.psd.extensions/rectangleextensions/
---

**Inheritance:**
java.lang.Object
```
public final class RectangleExtensions
```

Contains extension methods for  Rectangle .
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toGdiRectangle(Rectangle rectangle)](#toGdiRectangle-com.aspose.psd.Rectangle-) | Converts the  Rectangle  to the  System.Drawing.Rectangle . |
| [toGdiRectangle(RectangleF rectangle)](#toGdiRectangle-com.aspose.psd.RectangleF-) | Converts the  RectangleF  to the  System.Drawing.Rectangle . |
| [toString()](#toString--) |  |
| [unionWith(RectangleF rectangle, RectangleF otherRectangle)](#unionWith-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Unions two rectangle. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


Converts the  Rectangle  to the  System.Drawing.Rectangle .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to convert. |

**Returns:**
[Rectangle](../../java.awt/rectangle) - The converted  System.Drawing.Rectangle .
### toGdiRectangle(RectangleF rectangle) {#toGdiRectangle-com.aspose.psd.RectangleF-}
```
public static Rectangle2D.Float toGdiRectangle(RectangleF rectangle)
```


Converts the  RectangleF  to the  System.Drawing.Rectangle .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | The rectangle to convert. |

**Returns:**
java.awt.geom.Rectangle2D.Float - The converted  System.Drawing.RectangleF .
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


Unions two rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | The first rectangle. |
| otherRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | The second rectangle. |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

