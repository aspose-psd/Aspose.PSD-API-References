---
title: "RectangleExtensions"
second_title: "Java용 Aspose.PSD API 참조"
description: "Rectangle에 대한 확장 메서드를 포함합니다."
type: docs
weight: 23
url: /ko/java/com.aspose.psd.extensions/rectangleextensions/
---

**Inheritance:**
java.lang.Object
```
public final class RectangleExtensions
```

Rectangle에 대한 확장 메서드를 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toGdiRectangle(Rectangle rectangle)](#toGdiRectangle-com.aspose.psd.Rectangle-) | Rectangle를 System.Drawing.Rectangle 로 변환합니다. |
| [toGdiRectangle(RectangleF rectangle)](#toGdiRectangle-com.aspose.psd.RectangleF-) | RectangleF를 System.Drawing.Rectangle 로 변환합니다. |
| [toString()](#toString--) |  |
| [unionWith(RectangleF rectangle, RectangleF otherRectangle)](#unionWith-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | 두 개의 사각형을 합칩니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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


Rectangle를 System.Drawing.Rectangle 로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 변환할 사각형. |

**Returns:**
[Rectangle](../../java.awt/rectangle) - The converted  System.Drawing.Rectangle .
### toGdiRectangle(RectangleF rectangle) {#toGdiRectangle-com.aspose.psd.RectangleF-}
```
public static Rectangle2D.Float toGdiRectangle(RectangleF rectangle)
```


RectangleF를 System.Drawing.Rectangle 로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 변환할 사각형. |

**Returns:**
java.awt.geom.Rectangle2D.Float - 변환된  System.Drawing.RectangleF .
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


두 개의 사각형을 합칩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 첫 번째 사각형. |
| otherRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 두 번째 사각형. |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

