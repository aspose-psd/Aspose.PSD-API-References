---
title: "CurveShape"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt een gebogen spline-vorm voor."
type: docs
weight: 12
url: /nl/java/com.aspose.psd.shapes/curveshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.PolygonShape](../../com.aspose.psd.shapes/polygonshape)
```
public final class CurveShape extends PolygonShape
```

Stelt een gebogen spline-vorm voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CurveShape()](#CurveShape--) | Initialiseert een nieuw exemplaar van de  CurveShape  klasse. |
| [CurveShape(PointF[] points)](#CurveShape-com.aspose.psd.PointF---) | Initialiseert een nieuw exemplaar van de  CurveShape  klasse. |
| [CurveShape(PointF[] points, boolean isClosed)](#CurveShape-com.aspose.psd.PointF---boolean-) | Initialiseert een nieuw exemplaar van de  CurveShape  klasse. |
| [CurveShape(PointF[] points, float tension)](#CurveShape-com.aspose.psd.PointF---float-) | Initialiseert een nieuw exemplaar van de  CurveShape  klasse. |
| [CurveShape(PointF[] points, float tension, boolean isClosed)](#CurveShape-com.aspose.psd.PointF---float-boolean-) | Initialiseert een nieuw exemplaar van de  CurveShape  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Haalt de grenzen van het object op. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Haalt de grenzen van het object op. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Haalt de grenzen van het object op. |
| [getCenter()](#getCenter--) | Haalt het middelpunt van de vorm op. |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Haalt het eindpunt van de vorm op. |
| [getPoints()](#getPoints--) | Haalt of stelt de krommepunten in. |
| [getSegments()](#getSegments--) | Haalt de vormsegmenten op. |
| [getStartPoint()](#getStartPoint--) | Haalt het startpunt van de vorm op. |
| [getTension()](#getTension--) | Haalt of stelt de krommespanning in. |
| [hasSegments()](#hasSegments--) | Haalt een waarde op die aangeeft of de vorm segmenten heeft. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Haalt of stelt een waarde in die aangeeft of de vorm gesloten is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Keert de volgorde van punten voor deze vorm om. |
| [setClosed(boolean value)](#setClosed-boolean-) | Haalt of stelt een waarde in die aangeeft of de vorm gesloten is. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.psd.PointF---) | Haalt of stelt de krommepunten in. |
| [setTension(float value)](#setTension-float-) | Haalt of stelt de krommespanning in. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Past de opgegeven transformatie toe op de vorm. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurveShape() {#CurveShape--}
```
public CurveShape()
```


Initialiseert een nieuw exemplaar van de  CurveShape  klasse.

### CurveShape(PointF[] points) {#CurveShape-com.aspose.psd.PointF---}
```
public CurveShape(PointF[] points)
```


Initialiseert een nieuw exemplaar van de  CurveShape  klasse. De standaardspanning van 0.5 wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | De puntenarray. |

### CurveShape(PointF[] points, boolean isClosed) {#CurveShape-com.aspose.psd.PointF---boolean-}
```
public CurveShape(PointF[] points, boolean isClosed)
```


Initialiseert een nieuw exemplaar van de  CurveShape  klasse. De standaardspanning van 0.5 wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | De puntenarray. |
| isClosed | boolean |  |

### CurveShape(PointF[] points, float tension) {#CurveShape-com.aspose.psd.PointF---float-}
```
public CurveShape(PointF[] points, float tension)
```


Initialiseert een nieuw exemplaar van de  CurveShape  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | De puntenarray. |
| spanning | float | De krommespanning. |

### CurveShape(PointF[] points, float tension, boolean isClosed) {#CurveShape-com.aspose.psd.PointF---float-boolean-}
```
public CurveShape(PointF[] points, float tension, boolean isClosed)
```


Initialiseert een nieuw exemplaar van de  CurveShape  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | De puntenarray. |
| spanning | float | De krommespanning. |
| isClosed | boolean | Als ingesteld op  true  is de curve gesloten. |

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


Haalt de grenzen van het object op.

Waarde: De grenzen van het object.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
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
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Haalt het middelpunt van de vorm op.

Waarde: Het midden van de vorm.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Haalt het eindpunt van de vorm op.

Waarde: Het eindpunt van de vorm.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Haalt of stelt de krommepunten in.

Waarde: De krommepunten.

**Returns:**
com.aspose.psd.PointF[]
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Haalt de vormsegmenten op.

Waarde: De vormsegmenten.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Haalt het startpunt van de vorm op.

Waarde: Het startpunt van de vorm.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getTension() {#getTension--}
```
public float getTension()
```


Haalt of stelt de krommespanning in.

Waarde: De krommespanning.

**Returns:**
float
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Haalt een waarde op die aangeeft of de vorm segmenten heeft.

Waarde:  True  als de vorm segmenten heeft; anders,  false .

**Returns:**
boolean
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


Haalt of stelt een waarde in die aangeeft of de vorm gesloten is.

Waarde:  true  als de vorm gesloten is; anders,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reverse() {#reverse--}
```
public void reverse()
```


Keert de volgorde van punten voor deze vorm om.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Haalt of stelt een waarde in die aangeeft of de vorm gesloten is.

Waarde:  true  als de vorm gesloten is; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setPoints(PointF[] value) {#setPoints-com.aspose.psd.PointF---}
```
public void setPoints(PointF[] value)
```


Haalt of stelt de krommepunten in.

Waarde: De krommepunten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Haalt of stelt de krommespanning in.

Waarde: De krommespanning.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

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

