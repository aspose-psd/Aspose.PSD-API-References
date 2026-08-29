---
title: "ArcShape"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar en bågform."
type: docs
weight: 10
url: /sv/java/com.aspose.psd.shapes/arcshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape), [com.aspose.psd.shapes.EllipseShape](../../com.aspose.psd.shapes/ellipseshape), [com.aspose.psd.shapes.PieShape](../../com.aspose.psd.shapes/pieshape)

**All Implemented Interfaces:**
[com.aspose.psd.IOrderedShape](../../com.aspose.psd/iorderedshape)
```
public final class ArcShape extends PieShape implements IOrderedShape
```

Representerar en bågform.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ArcShape()](#ArcShape--) | Initierar en ny instans av  ArcShape  klassen. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)](#ArcShape-com.aspose.psd.RectangleF-float-float-) | Initierar en ny instans av  ArcShape  klassen. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)](#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-) | Initierar en ny instans av  ArcShape  klassen. |
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
| [getLeftBottom()](#getLeftBottom--) | Hämtar den vänstra nedre rektangelpunkten. |
| [getLeftTop()](#getLeftTop--) | Hämtar den vänstra övre rektangelpunkten. |
| [getRectangleHeight()](#getRectangleHeight--) | Hämtar rektangelns höjd. |
| [getRectangleWidth()](#getRectangleWidth--) | Hämtar rektangelns bredd. |
| [getRightBottom()](#getRightBottom--) | Hämtar den högra nedre rektangelpunkten. |
| [getRightTop()](#getRightTop--) | Hämtar den högra övre rektangelpunkten. |
| [getSegments()](#getSegments--) | Hämtar formens segment. |
| [getStartAngle()](#getStartAngle--) | Hämtar eller anger startvinkeln. |
| [getStartPoint()](#getStartPoint--) | Hämtar startpunkten för formen. |
| [getSweepAngle()](#getSweepAngle--) | Hämtar eller anger svepvinkeln. |
| [hasSegments()](#hasSegments--) | Hämtar ett värde som indikerar om formen har segment. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Hämtar eller anger ett värde som indikerar om den ordnade formen är sluten. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Vänder ordningen på punkterna för denna form. |
| [setClosed(boolean value)](#setClosed-boolean-) | Hämtar eller anger ett värde som indikerar om den ordnade formen är sluten. |
| [setStartAngle(float value)](#setStartAngle-float-) | Hämtar eller anger startvinkeln. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Hämtar eller anger svepvinkeln. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Tillämpar den angivna transformationen på formen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArcShape() {#ArcShape--}
```
public ArcShape()
```


Initierar en ny instans av  ArcShape  klassen.

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle) {#ArcShape-com.aspose.psd.RectangleF-float-float-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Initierar en ny instans av  ArcShape  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Rektangeln. |
| startvinkel | float | Startvinkeln. |
| sweepAngle | float | Svepvinkeln. |

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed) {#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)
```


Initierar en ny instans av  ArcShape  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Rektangeln. |
| startvinkel | float | Startvinkeln. |
| sweepAngle | float | Svepvinkeln. |
| isClosed | boolean | Om den är satt till  true  är bågen sluten. Den slutna bågen degenererar i själva verket till en ellips. |

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
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Hämtar den vänstra nedre rektangelpunkten.

Värde: Den vänstra nedre rektangelpunkten.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Hämtar den vänstra övre rektangelpunkten.

Värde: Den vänstra övre rektangelpunkten.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Hämtar rektangelns höjd.

Värde: Rektangelns höjd.

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Hämtar rektangelns bredd.

Värde: Rektangelns bredd.

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Hämtar den högra nedre rektangelpunkten.

Värde: Den högra nedre rektangelpunkten.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Hämtar den högra övre rektangelpunkten.

Värde: Den högra övre rektangelpunkten.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Hämtar formens segment.

Värde: Formsegmenten.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Hämtar eller anger startvinkeln.

Värde: Startvinkeln.

**Returns:**
float
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Hämtar startpunkten för formen.

Värde: Startpunkten för formen.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Hämtar eller anger svepvinkeln.

Värde: Svepvinkeln.

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


Hämtar eller anger ett värde som indikerar om den ordnade formen är sluten. Vid bearbetning av en sluten ordnad form har start- och slutpunkterna ingen betydelse.

Värde:  True  om denna ordnade form är sluten; annars  false .

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


Hämtar eller anger ett värde som indikerar om den ordnade formen är sluten. Vid bearbetning av en sluten ordnad form har start- och slutpunkterna ingen betydelse.

Värde:  True  om denna ordnade form är sluten; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Hämtar eller anger startvinkeln.

Värde: Startvinkeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Hämtar eller anger svepvinkeln.

Värde: Svepvinkeln.

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

