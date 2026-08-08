---
title: "ArcShape"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt een boogvorm voor."
type: docs
weight: 10
url: /nl/java/com.aspose.psd.shapes/arcshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape), [com.aspose.psd.shapes.EllipseShape](../../com.aspose.psd.shapes/ellipseshape), [com.aspose.psd.shapes.PieShape](../../com.aspose.psd.shapes/pieshape)

**All Implemented Interfaces:**
[com.aspose.psd.IOrderedShape](../../com.aspose.psd/iorderedshape)
```
public final class ArcShape extends PieShape implements IOrderedShape
```

Stelt een boogvorm voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ArcShape()](#ArcShape--) | Initialiseert een nieuw exemplaar van de  ArcShape  klasse. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)](#ArcShape-com.aspose.psd.RectangleF-float-float-) | Initialiseert een nieuw exemplaar van de  ArcShape  klasse. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)](#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-) | Initialiseert een nieuw exemplaar van de  ArcShape  klasse. |
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
| [getLeftBottom()](#getLeftBottom--) | Haalt het linksonderhoekpunt van de rechthoek op. |
| [getLeftTop()](#getLeftTop--) | Haalt het linkerbovenhoekpunt van de rechthoek op. |
| [getRectangleHeight()](#getRectangleHeight--) | Haalt de hoogte van de rechthoek op. |
| [getRectangleWidth()](#getRectangleWidth--) | Haalt de breedte van de rechthoek op. |
| [getRightBottom()](#getRightBottom--) | Haalt het rechtsonderhoekpunt van de rechthoek op. |
| [getRightTop()](#getRightTop--) | Haalt het rechterbovenhoekpunt van de rechthoek op. |
| [getSegments()](#getSegments--) | Haalt de vormsegmenten op. |
| [getStartAngle()](#getStartAngle--) | Haalt op of stelt de starthoek in. |
| [getStartPoint()](#getStartPoint--) | Haalt het startpunt van de vorm op. |
| [getSweepAngle()](#getSweepAngle--) | Haalt op of stelt de sweephoek in. |
| [hasSegments()](#hasSegments--) | Haalt een waarde op die aangeeft of de vorm segmenten heeft. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Haalt een waarde op of stelt deze in die aangeeft of de geordende vorm gesloten is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Keert de volgorde van punten voor deze vorm om. |
| [setClosed(boolean value)](#setClosed-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of de geordende vorm gesloten is. |
| [setStartAngle(float value)](#setStartAngle-float-) | Haalt op of stelt de starthoek in. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Haalt op of stelt de sweephoek in. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Past de opgegeven transformatie toe op de vorm. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArcShape() {#ArcShape--}
```
public ArcShape()
```


Initialiseert een nieuw exemplaar van de  ArcShape  klasse.

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle) {#ArcShape-com.aspose.psd.RectangleF-float-float-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Initialiseert een nieuw exemplaar van de  ArcShape  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | De rechthoek. |
| startAngle | float | De starthoek. |
| sweepAngle | float | De sweephoek. |

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed) {#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)
```


Initialiseert een nieuw exemplaar van de  ArcShape  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | De rechthoek. |
| startAngle | float | De starthoek. |
| sweepAngle | float | De sweephoek. |
| isClosed | boolean | Indien ingesteld op  true  is de boog gesloten. De gesloten boog degeneert eigenlijk tot een ellips. |

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
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Haalt het linksonderhoekpunt van de rechthoek op.

Waarde: Het linksonderhoekpunt van de rechthoek.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Haalt het linkerbovenhoekpunt van de rechthoek op.

Waarde: Het linkerbovenhoekpunt van de rechthoek.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Haalt de hoogte van de rechthoek op.

Waarde: De hoogte van de rechthoek.

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Haalt de breedte van de rechthoek op.

Waarde: De breedte van de rechthoek.

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Haalt het rechtsonderhoekpunt van de rechthoek op.

Waarde: Het rechteronderhoekpunt van de rechthoek.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Haalt het rechterbovenhoekpunt van de rechthoek op.

Waarde: Het rechterbovenhoekpunt van de rechthoek.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Haalt de vormsegmenten op.

Waarde: De vormsegmenten.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Haalt op of stelt de starthoek in.

Waarde: De starthoek.

**Returns:**
float
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Haalt het startpunt van de vorm op.

Waarde: Het startpunt van de vorm.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Haalt op of stelt de sweephoek in.

Waarde: De sweephoek.

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


Haalt een waarde op of stelt deze in die aangeeft of de geordende vorm gesloten is. Bij het verwerken van een gesloten geordende vorm hebben de begin- en eindpunten geen betekenis.

Waarde:  True  als deze geordende vorm gesloten is; anders,  false .

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


Haalt een waarde op of stelt deze in die aangeeft of de geordende vorm gesloten is. Bij het verwerken van een gesloten geordende vorm hebben de begin- en eindpunten geen betekenis.

Waarde:  True  als deze geordende vorm gesloten is; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Haalt op of stelt de starthoek in.

Waarde: De starthoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Haalt op of stelt de sweephoek in.

Waarde: De sweephoek.

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

