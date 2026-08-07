---
title: "RectangleExtensions"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Enthält Erweiterungsmethoden für Rectangle."
type: docs
weight: 23
url: /de/java/com.aspose.psd.extensions/rectangleextensions/
---

**Inheritance:**
java.lang.Object
```
public final class RectangleExtensions
```

Enthält Erweiterungsmethoden für  Rectangle .
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toGdiRectangle(Rectangle rectangle)](#toGdiRectangle-com.aspose.psd.Rectangle-) | Konvertiert das  Rectangle  in das  System.Drawing.Rectangle . |
| [toGdiRectangle(RectangleF rectangle)](#toGdiRectangle-com.aspose.psd.RectangleF-) | Konvertiert das  RectangleF  in das  System.Drawing.Rectangle . |
| [toString()](#toString--) |  |
| [unionWith(RectangleF rectangle, RectangleF otherRectangle)](#unionWith-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Vereint zwei Rechtecke. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Konvertiert das  Rectangle  in das  System.Drawing.Rectangle .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck zum Konvertieren. |

**Returns:**
[Rectangle](../../java.awt/rectangle) - The converted  System.Drawing.Rectangle .
### toGdiRectangle(RectangleF rectangle) {#toGdiRectangle-com.aspose.psd.RectangleF-}
```
public static Rectangle2D.Float toGdiRectangle(RectangleF rectangle)
```


Konvertiert das  RectangleF  in das  System.Drawing.Rectangle .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Das Rechteck zum Konvertieren. |

**Returns:**
java.awt.geom.Rectangle2D.Float - Das konvertierte  System.Drawing.RectangleF .
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


Vereint zwei Rechtecke.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Das erste Rechteck. |
| otherRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Das zweite Rechteck. |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

