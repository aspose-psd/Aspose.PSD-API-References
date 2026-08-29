---
title: "Figur"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die Figur."
type: docs
weight: 42
url: /de/java/com.aspose.psd/figure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

Die Figur. Ein Container für Formen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Figure()](#Figure--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addShape(Shape shape)](#addShape-com.aspose.psd.Shape-) | Fügt der Figur eine Form hinzu. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.psd.Shape---) | Fügt der Figur einen Bereich von Formen hinzu. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Liest oder setzt die Begrenzungen des Objekts. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Liest die Begrenzungen des Objekts. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Liest die Begrenzungen des Objekts. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | Liest die gesamten Figursegmente. |
| [getShapes()](#getShapes--) | Liest die Formen der Figur. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Liest einen Wert, der angibt, ob diese Figur geschlossen ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeShape(Shape shape)](#removeShape-com.aspose.psd.Shape-) | Entfernt eine Form aus der Figur. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.psd.Shape---) | Entfernt einen Bereich von Formen aus der Figur. |
| [reverse()](#reverse--) | Kehrt die Reihenfolge der Formen dieser Figur und die Punktreihenfolge der Formen um. |
| [setClosed(boolean value)](#setClosed-boolean-) | Setzt einen Wert, der angibt, ob diese Figur geschlossen ist. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Wendet die angegebene Transformation auf die Form an. |
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


Fügt der Figur eine Form hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | Die hinzuzufügende Form. |

### addShapes(Shape[] shapes) {#addShapes-com.aspose.psd.Shape---}
```
public void addShapes(Shape[] shapes)
```


Fügt der Figur einen Bereich von Formen hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | Die hinzuzufügenden Formen. |

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
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Liest oder setzt die Begrenzungen des Objekts.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Liest die Begrenzungen des Objekts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Liest die Begrenzungen des Objekts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |
| pen | [Pen](../../com.aspose.psd/pen) | Der Stift, der für das Objekt verwendet wird. Dies kann die Größe der Objektbegrenzungen beeinflussen. |

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


Liest die gesamten Figursegmente.

**Returns:**
com.aspose.psd.ShapeSegment[] - Die Figursegmente.
### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Liest die Formen der Figur.

**Returns:**
com.aspose.psd.Shape[] - Die Formen der Figur.
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


Liest einen Wert, der angibt, ob diese Figur geschlossen ist. Eine geschlossene Figur macht nur dann einen Unterschied, wenn die erste und die letzte Form der Figur kontinuierliche Formen sind. In einem solchen Fall wird der erste Punkt der ersten Form durch eine gerade Linie mit dem letzten Punkt der letzten Form verbunden.

**Returns:**
boolean -  True  wenn diese Figur geschlossen ist; andernfalls,  false .
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


Entfernt eine Form aus der Figur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | Die zu entfernende Form. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.psd.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Entfernt einen Bereich von Formen aus der Figur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | Der zu entfernende Formenbereich. |

### reverse() {#reverse--}
```
public void reverse()
```


Kehrt die Reihenfolge der Formen dieser Figur und die Punktreihenfolge der Formen um.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Legt einen Wert fest, der angibt, ob diese Figur geschlossen ist. Eine geschlossene Figur macht nur dann einen Unterschied, wenn die Formen der ersten und der letzten Figur kontinuierliche Formen sind. In einem solchen Fall wird der erste Punkt der ersten Form durch eine gerade Linie vom letzten Punkt der letzten Form verbunden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | True, wenn diese Figur geschlossen ist; andernfalls false. |

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


Wendet die angegebene Transformation auf die Form an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | Die anzuwendende Transformation. |

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

