---
title: "Vorm"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De vorm."
type: docs
weight: 96
url: /nl/java/com.aspose.psd/shape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public abstract class Shape extends ObjectWithBounds
```

De vorm. Een doorlopend geheel van punten verbonden volgens een specifieke regel.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Shape()](#Shape--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Haalt de grenzen van het object op. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Haalt de grenzen van het object op. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Haalt de grenzen van het object op. |
| [getCenter()](#getCenter--) | Haalt het middelpunt van de vorm op. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | Haalt de vormsegmenten op. |
| [hasSegments()](#hasSegments--) | Haalt een waarde op die aangeeft of de vorm segmenten heeft. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Past de opgegeven transformatie toe op de vorm. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


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
public abstract RectangleF getBounds()
```


Haalt de grenzen van het object op.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public abstract RectangleF getBounds(Matrix matrix)
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
public abstract RectangleF getBounds(Matrix matrix, Pen pen)
```


Haalt de grenzen van het object op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | De matrix die moet worden toegepast voordat de grenzen worden berekend. |
| pen | [Pen](../../com.aspose.psd/pen) | De pen die voor het object moet worden gebruikt. Dit kan de grootte van de grenzen van het object beïnvloeden. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public abstract PointF getCenter()
```


Haalt het middelpunt van de vorm op.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The shape's center.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSegments() {#getSegments--}
```
public abstract ShapeSegment[] getSegments()
```


Haalt de vormsegmenten op.

**Returns:**
com.aspose.psd.ShapeSegment[] - De vormsegmenten.
### hasSegments() {#hasSegments--}
```
public abstract boolean hasSegments()
```


Haalt een waarde op die aangeeft of de vorm segmenten heeft.

**Returns:**
boolean -  True  als de vorm segmenten heeft; anders,  false .
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
public abstract void transform(Matrix transform)
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

