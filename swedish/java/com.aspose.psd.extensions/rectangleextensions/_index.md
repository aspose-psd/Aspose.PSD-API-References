---
title: "RectangleExtensions"
second_title: "Aspose.PSD för Java API-referens"
description: "Innehåller förlängningsmetoder för Rectangle."
type: docs
weight: 23
url: /sv/java/com.aspose.psd.extensions/rectangleextensions/
---

**Inheritance:**
java.lang.Object
```
public final class RectangleExtensions
```

Innehåller förlängningsmetoder för Rectangle.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toGdiRectangle(Rectangle rectangle)](#toGdiRectangle-com.aspose.psd.Rectangle-) | Konverterar Rectangle till System.Drawing.Rectangle. |
| [toGdiRectangle(RectangleF rectangle)](#toGdiRectangle-com.aspose.psd.RectangleF-) | Konverterar RectangleF till System.Drawing.Rectangle. |
| [toString()](#toString--) |  |
| [unionWith(RectangleF rectangle, RectangleF otherRectangle)](#unionWith-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Förenar två rektanglar. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Konverterar Rectangle till System.Drawing.Rectangle.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln att konvertera. |

**Returns:**
[Rectangle](../../java.awt/rectangle) - The converted  System.Drawing.Rectangle .
### toGdiRectangle(RectangleF rectangle) {#toGdiRectangle-com.aspose.psd.RectangleF-}
```
public static Rectangle2D.Float toGdiRectangle(RectangleF rectangle)
```


Konverterar RectangleF till System.Drawing.Rectangle.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Rektangeln att konvertera. |

**Returns:**
java.awt.geom.Rectangle2D.Float - Den konverterade System.Drawing.RectangleF.
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


Förenar två rektanglar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Den första rektangeln. |
| otherRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Den andra rektangeln. |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

