---
title: "CurveShape"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar en böjd spline‑form."
type: docs
weight: 12
url: /sv/java/com.aspose.psd.shapes/curveshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.PolygonShape](../../com.aspose.psd.shapes/polygonshape)
```
public final class CurveShape extends PolygonShape
```

Representerar en böjd spline‑form.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [CurveShape()](#CurveShape--) | Initierar en ny instans av den  CurveShape  klassen. |
| [CurveShape(PointF[] points)](#CurveShape-com.aspose.psd.PointF---) | Initierar en ny instans av den  CurveShape  klassen. |
| [CurveShape(PointF[] points, boolean isClosed)](#CurveShape-com.aspose.psd.PointF---boolean-) | Initierar en ny instans av den  CurveShape  klassen. |
| [CurveShape(PointF[] points, float tension)](#CurveShape-com.aspose.psd.PointF---float-) | Initierar en ny instans av den  CurveShape  klassen. |
| [CurveShape(PointF[] points, float tension, boolean isClosed)](#CurveShape-com.aspose.psd.PointF---float-boolean-) | Initierar en ny instans av den  CurveShape  klassen. |
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
| [getTension()](#getTension--) | Hämtar eller anger kurvspänningen. |
| [hasSegments()](#hasSegments--) | Hämtar ett värde som indikerar om formen har segment. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Hämtar eller anger ett värde som indikerar om formen är sluten. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Vänder ordningen på punkterna för denna form. |
| [setClosed(boolean value)](#setClosed-boolean-) | Hämtar eller anger ett värde som indikerar om formen är sluten. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.psd.PointF---) | Hämtar eller anger kurvpunkterna. |
| [setTension(float value)](#setTension-float-) | Hämtar eller anger kurvspänningen. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Tillämpar den angivna transformationen på formen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurveShape() {#CurveShape--}
```
public CurveShape()
```


Initierar en ny instans av den  CurveShape  klassen.

### CurveShape(PointF[] points) {#CurveShape-com.aspose.psd.PointF---}
```
public CurveShape(PointF[] points)
```


Initierar en ny instans av den  CurveShape  klassen. Standardspänningen 0.5 används.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Punktarrayen. |

### CurveShape(PointF[] points, boolean isClosed) {#CurveShape-com.aspose.psd.PointF---boolean-}
```
public CurveShape(PointF[] points, boolean isClosed)
```


Initierar en ny instans av den  CurveShape  klassen. Standardspänningen 0.5 används.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Punktarrayen. |
| isClosed | boolean |  |

### CurveShape(PointF[] points, float tension) {#CurveShape-com.aspose.psd.PointF---float-}
```
public CurveShape(PointF[] points, float tension)
```


Initierar en ny instans av den  CurveShape  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Punktarrayen. |
| spänning | float | Kurvspänningen. |

### CurveShape(PointF[] points, float tension, boolean isClosed) {#CurveShape-com.aspose.psd.PointF---float-boolean-}
```
public CurveShape(PointF[] points, float tension, boolean isClosed)
```


Initierar en ny instans av den  CurveShape  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Punktarrayen. |
| spänning | float | Kurvspänningen. |
| isClosed | boolean | om den är satt till  true  är kurvan sluten. |

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
### getTension() {#getTension--}
```
public float getTension()
```


Hämtar eller anger kurvspänningen.

Värde: Kurvspänningen.

**Returns:**
float
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

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Hämtar eller anger kurvspänningen.

Värde: Kurvspänningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

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

