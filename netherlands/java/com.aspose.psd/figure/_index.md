---
title: "Figuur"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De figuur."
type: docs
weight: 42
url: /nl/java/com.aspose.psd/figure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

De figuur. Een container voor vormen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Figure()](#Figure--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addShape(Shape shape)](#addShape-com.aspose.psd.Shape-) | Voegt een vorm toe aan de figuur. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.psd.Shape---) | Voegt een reeks vormen toe aan de figuur. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Haalt de grenzen van het object op of stelt ze in. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Haalt de grenzen van het object op. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Haalt de grenzen van het object op. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | Haalt alle segmenten van de figuur op. |
| [getShapes()](#getShapes--) | Haalt de vormen van de figuur op. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Haalt een waarde op die aangeeft of deze figuur gesloten is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeShape(Shape shape)](#removeShape-com.aspose.psd.Shape-) | Verwijdert een vorm uit de figuur. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.psd.Shape---) | Verwijdert een reeks vormen uit de figuur. |
| [reverse()](#reverse--) | Keert de volgorde van de vormen van deze figuur en de volgorde van de punten van de vormen om. |
| [setClosed(boolean value)](#setClosed-boolean-) | Stelt een waarde in die aangeeft of deze figuur gesloten is. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Past de opgegeven transformatie toe op de vorm. |
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


Voegt een vorm toe aan de figuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | De toe te voegen vorm. |

### addShapes(Shape[] shapes) {#addShapes-com.aspose.psd.Shape---}
```
public void addShapes(Shape[] shapes)
```


Voegt een reeks vormen toe aan de figuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | De toe te voegen vormen. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Haalt de grenzen van het object op of stelt ze in.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Haalt de grenzen van het object op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | De matrix die moet worden toegepast voordat de grenzen worden berekend. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Haalt de grenzen van het object op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | De matrix die moet worden toegepast voordat de grenzen worden berekend. |
| pen | [Pen](../../com.aspose.psd/pen) | De pen die voor het object moet worden gebruikt. Dit kan de grootte van de grenzen van het object beïnvloeden. |

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


Haalt alle segmenten van de figuur op.

**Returns:**
com.aspose.psd.ShapeSegment[] - De segmenten van de figuur.
### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Haalt de vormen van de figuur op.

**Returns:**
com.aspose.psd.Shape[] - De vormen van de figuur.
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


Haalt een waarde op die aangeeft of deze figuur gesloten is. Een gesloten figuur maakt alleen een verschil in het geval dat de eerste en de laatste vormen van de figuur doorlopende vormen zijn. In dat geval wordt het eerste punt van de eerste vorm verbonden met een rechte lijn vanaf het laatste punt van de laatste vorm.

**Returns:**
boolean -  True  als deze figuur gesloten is; anders,  false .
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


Verwijdert een vorm uit de figuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | De te verwijderen vorm. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.psd.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Verwijdert een reeks vormen uit de figuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | Het te verwijderen bereik van vormen. |

### reverse() {#reverse--}
```
public void reverse()
```


Keert de volgorde van de vormen van deze figuur en de volgorde van de punten van de vormen om.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Stelt een waarde in die aangeeft of deze figuur gesloten is. Een gesloten figuur maakt alleen een verschil in het geval dat de eerste en de laatste vormen van de figuur doorlopende vormen zijn. In dat geval wordt het eerste punt van de eerste vorm verbonden met een rechte lijn vanaf het laatste punt van de laatste vorm.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Waar als deze figuur gesloten is; anders onwaar. |

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


Past de opgegeven transformatie toe op de vorm.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | De transformatie die moet worden toegepast. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

