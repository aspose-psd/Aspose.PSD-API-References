---
title: "RectangleProjectedShape"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar en form som projiceras över en rektangel vriden till en viss orientering."
type: docs
weight: 16
url: /sv/java/com.aspose.psd.shapes/rectangleprojectedshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape)
```
public abstract class RectangleProjectedShape extends Shape
```

Representerar en form som projiceras över en rektangel vriden till en viss orientering. Anges av fyra punkter som kan roteras i rymden samtidigt som de behåller samma kantlängd och 90 grader mellan intilliggande kanter.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [RectangleProjectedShape()](#RectangleProjectedShape--) | Initierar en ny instans av klassen  RectangleProjectedShape  . |
| [RectangleProjectedShape(RectangleF rectangle)](#RectangleProjectedShape-com.aspose.psd.RectangleF-) | Initierar en ny instans av klassen  RectangleProjectedShape  . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Hämtar objektets gränser. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Hämtar objektets gränser. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Hämtar objektets gränser. |
| [getCenter()](#getCenter--) | Hämtar formens centrum. |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Hämtar den vänstra nedre rektangelpunkten. |
| [getLeftTop()](#getLeftTop--) | Hämtar den vänstra övre rektangelpunkten. |
| [getRectangleHeight()](#getRectangleHeight--) | Hämtar rektangelns höjd. |
| [getRectangleWidth()](#getRectangleWidth--) | Hämtar rektangelns bredd. |
| [getRightBottom()](#getRightBottom--) | Hämtar den högra nedre rektangelpunkten. |
| [getRightTop()](#getRightTop--) | Hämtar den högra övre rektangelpunkten. |
| [getSegments()](#getSegments--) | Hämtar formens segment. |
| [hasSegments()](#hasSegments--) | Hämtar ett värde som indikerar om formen har segment. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Tillämpar den angivna transformationen på formen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleProjectedShape() {#RectangleProjectedShape--}
```
public RectangleProjectedShape()
```


Initierar en ny instans av klassen  RectangleProjectedShape  .

### RectangleProjectedShape(RectangleF rectangle) {#RectangleProjectedShape-com.aspose.psd.RectangleF-}
```
public RectangleProjectedShape(RectangleF rectangle)
```


Initierar en ny instans av klassen  RectangleProjectedShape  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Rektangeln att initiera från. |

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
public abstract ShapeSegment[] getSegments()
```


Hämtar formens segment.

**Returns:**
com.aspose.psd.ShapeSegment[] - Formens segment.
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

