---
title: "BezierShape"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar en Bézier-spline."
type: docs
weight: 11
url: /sv/java/com.aspose.psd.shapes/beziershape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.PolygonShape](../../com.aspose.psd.shapes/polygonshape)
```
public final class BezierShape extends PolygonShape
```

Representerar en Bézier-spline.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [BezierShape()](#BezierShape--) | Initierar en ny instans av  BezierShape  klassen. |
| [BezierShape(PointF[] points)](#BezierShape-com.aspose.psd.PointF---) | Initierar en ny instans av  BezierShape  klassen. |
| [BezierShape(PointF[] points, boolean isClosed)](#BezierShape-com.aspose.psd.PointF---boolean-) | Initierar en ny instans av  BezierShape  klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Hämtar objektets gränser. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Hämtar objektets gränser. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Hämtar objektets gränser. |
| [getCenter()](#getCenter--) | Hämtar formens centrum. |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Hämtar den avslutande formpunkten. |
| [getPoints()](#getPoints--) | Hämtar eller anger kurvpunkterna. |
| [getSegments()](#getSegments--) | Hämtar formens segment. |
| [getStartPoint()](#getStartPoint--) | Hämtar startpunkten för formen. |
| [hasSegments()](#hasSegments--) | Hämtar ett värde som indikerar om formen har segment. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Hämtar eller anger ett värde som indikerar om formen är sluten. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Vänder ordningen på punkterna för denna form. |
| [setClosed(boolean value)](#setClosed-boolean-) | Hämtar eller anger ett värde som indikerar om formen är sluten. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.psd.PointF---) | Hämtar eller anger kurvpunkterna. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Tillämpar den angivna transformationen på formen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BezierShape() {#BezierShape--}
```
public BezierShape()
```


Initierar en ny instans av  BezierShape  klassen.

### BezierShape(PointF[] points) {#BezierShape-com.aspose.psd.PointF---}
```
public BezierShape(PointF[] points)
```


Initierar en ny instans av  BezierShape  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Punktarrayen. |

### BezierShape(PointF[] points, boolean isClosed) {#BezierShape-com.aspose.psd.PointF---boolean-}
```
public BezierShape(PointF[] points, boolean isClosed)
```


Initierar en ny instans av  BezierShape  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Punktarrayen. |
| isClosed | boolean | Om den är satt till  true  är bezier-splinen sluten. |

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
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Hämtar objektets gränser.

Värde: Objektets gränser.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Hämtar objektets gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matrisen att tillämpa innan gränser beräknas. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Hämtar objektets gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matrisen att tillämpa innan gränser beräknas. |
| pen | [Pen](../../com.aspose.psd/pen) | Pennan att använda för objektet. Detta kan påverka objektets gränsstorlek. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Hämtar formens centrum.

Värde: Formens centrum.

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


Hämtar den avslutande formpunkten.

Värde: Formens avslutningspunkt.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Hämtar eller anger kurvpunkterna.

Värde: Kurvpunkterna.

**Returns:**
com.aspose.psd.PointF[]
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Hämtar formens segment.

Värde: Formsegmenten.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Hämtar startpunkten för formen.

Värde: Startpunkten för formen.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Hämtar ett värde som indikerar om formen har segment.

Värde:  Sant  om formen har segment; annars,  falskt .

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


Hämtar eller anger ett värde som indikerar om formen är sluten.

Värde:  true  om formen är sluten; annars  false .

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


Vänder ordningen på punkterna för denna form.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Hämtar eller anger ett värde som indikerar om formen är sluten.

Värde:  true  om formen är sluten; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setPoints(PointF[] value) {#setPoints-com.aspose.psd.PointF---}
```
public void setPoints(PointF[] value)
```


Hämtar eller anger kurvpunkterna.

Värde: Kurvpunkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

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


Tillämpar den angivna transformationen på formen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | Transformationen att tillämpa. |

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

