---
title: "RectangleShape"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt eine rechteckige Form dar."
type: docs
weight: 17
url: /de/java/com.aspose.psd.shapes/rectangleshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape)
```
public class RectangleShape extends RectangleProjectedShape
```

Stellt eine rechteckige Form dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RectangleShape()](#RectangleShape--) | Initialisiert eine neue Instanz der  RectangleShape  Klasse. |
| [RectangleShape(RectangleF rectangle)](#RectangleShape-com.aspose.psd.RectangleF-) | Initialisiert eine neue Instanz der  RectangleShape  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Liest die Begrenzungen des Objekts. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Liest die Begrenzungen des Objekts. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Liest die Begrenzungen des Objekts. |
| [getCenter()](#getCenter--) | Gibt das Zentrum der Form zurück. |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Liefert den linken unteren Rechteckpunkt. |
| [getLeftTop()](#getLeftTop--) | Liefert den linken oberen Rechteckpunkt. |
| [getRectangleHeight()](#getRectangleHeight--) | Liefert die Rechteckhöhe. |
| [getRectangleWidth()](#getRectangleWidth--) | Liefert die Rechteckbreite. |
| [getRightBottom()](#getRightBottom--) | Liefert den rechten unteren Rechteckpunkt. |
| [getRightTop()](#getRightTop--) | Liefert den rechten oberen Rechteckpunkt. |
| [getSegments()](#getSegments--) | Gibt die Segmente der Form zurück. |
| [hasSegments()](#hasSegments--) | Gibt einen Wert zurück, der angibt, ob die Form Segmente hat. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Wendet die angegebene Transformation auf die Form an. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleShape() {#RectangleShape--}
```
public RectangleShape()
```


Initialisiert eine neue Instanz der  RectangleShape  Klasse.

### RectangleShape(RectangleF rectangle) {#RectangleShape-com.aspose.psd.RectangleF-}
```
public RectangleShape(RectangleF rectangle)
```


Initialisiert eine neue Instanz der  RectangleShape  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Das Rechteck. |

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


Liest die Begrenzungen des Objekts.

Wert: Die Begrenzungen des Objekts.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
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
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Gibt das Zentrum der Form zurück.

Wert: Das Zentrum der Form.

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


Liefert den linken unteren Rechteckpunkt.

Wert: Der linke untere Rechteckpunkt.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Liefert den linken oberen Rechteckpunkt.

Wert: Der linke obere Rechteckpunkt.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Liefert die Rechteckhöhe.

Wert: Die Rechteckhöhe.

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Liefert die Rechteckbreite.

Wert: Die Rechteckbreite.

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Liefert den rechten unteren Rechteckpunkt.

Wert: Der rechte untere Rechteckpunkt.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Liefert den rechten oberen Rechteckpunkt.

Wert: Der rechte obere Rechteckpunkt.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Gibt die Segmente der Form zurück.

Wert: Die Formsegmente.

**Returns:**
com.aspose.psd.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Gibt einen Wert zurück, der angibt, ob die Form Segmente hat.

Wert:  True  wenn die Form Segmente hat; andernfalls,  false .

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

