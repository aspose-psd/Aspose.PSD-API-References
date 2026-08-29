---
title: "CurveShape"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt eine gekrümmte Spline-Form dar."
type: docs
weight: 12
url: /de/java/com.aspose.psd.shapes/curveshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.PolygonShape](../../com.aspose.psd.shapes/polygonshape)
```
public final class CurveShape extends PolygonShape
```

Stellt eine gekrümmte Spline-Form dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CurveShape()](#CurveShape--) | Initialisiert eine neue Instanz der  CurveShape  Klasse. |
| [CurveShape(PointF[] points)](#CurveShape-com.aspose.psd.PointF---) | Initialisiert eine neue Instanz der  CurveShape  Klasse. |
| [CurveShape(PointF[] points, boolean isClosed)](#CurveShape-com.aspose.psd.PointF---boolean-) | Initialisiert eine neue Instanz der  CurveShape  Klasse. |
| [CurveShape(PointF[] points, float tension)](#CurveShape-com.aspose.psd.PointF---float-) | Initialisiert eine neue Instanz der  CurveShape  Klasse. |
| [CurveShape(PointF[] points, float tension, boolean isClosed)](#CurveShape-com.aspose.psd.PointF---float-boolean-) | Initialisiert eine neue Instanz der  CurveShape  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Liest die Begrenzungen des Objekts. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Liest die Begrenzungen des Objekts. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Liest die Begrenzungen des Objekts. |
| [getCenter()](#getCenter--) | Gibt das Zentrum der Form zurück. |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Ruft den Endpunkt der Form ab. |
| [getPoints()](#getPoints--) | Liest oder schreibt die Kurvenpunkte. |
| [getSegments()](#getSegments--) | Gibt die Segmente der Form zurück. |
| [getStartPoint()](#getStartPoint--) | Ruft den Startpunkt der Form ab. |
| [getTension()](#getTension--) | Liest oder setzt die Kurvenspannung. |
| [hasSegments()](#hasSegments--) | Gibt einen Wert zurück, der angibt, ob die Form Segmente hat. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Liest oder schreibt einen Wert, der angibt, ob die Form geschlossen ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Kehrt die Reihenfolge der Punkte für diese Form um. |
| [setClosed(boolean value)](#setClosed-boolean-) | Liest oder schreibt einen Wert, der angibt, ob die Form geschlossen ist. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.psd.PointF---) | Liest oder schreibt die Kurvenpunkte. |
| [setTension(float value)](#setTension-float-) | Liest oder setzt die Kurvenspannung. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Wendet die angegebene Transformation auf die Form an. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurveShape() {#CurveShape--}
```
public CurveShape()
```


Initialisiert eine neue Instanz der  CurveShape  Klasse.

### CurveShape(PointF[] points) {#CurveShape-com.aspose.psd.PointF---}
```
public CurveShape(PointF[] points)
```


Initialisiert eine neue Instanz der  CurveShape  Klasse. Die Standardspannung von 0,5 wird verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Das Punkte-Array. |

### CurveShape(PointF[] points, boolean isClosed) {#CurveShape-com.aspose.psd.PointF---boolean-}
```
public CurveShape(PointF[] points, boolean isClosed)
```


Initialisiert eine neue Instanz der  CurveShape  Klasse. Die Standardspannung von 0,5 wird verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Das Punkte-Array. |
| isClosed | boolean |  |

### CurveShape(PointF[] points, float tension) {#CurveShape-com.aspose.psd.PointF---float-}
```
public CurveShape(PointF[] points, float tension)
```


Initialisiert eine neue Instanz der  CurveShape  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Das Punkte-Array. |
| Spannung | float | Die Kurvenspannung. |

### CurveShape(PointF[] points, float tension, boolean isClosed) {#CurveShape-com.aspose.psd.PointF---float-boolean-}
```
public CurveShape(PointF[] points, float tension, boolean isClosed)
```


Initialisiert eine neue Instanz der  CurveShape  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Das Punkte-Array. |
| Spannung | float | Die Kurvenspannung. |
| isClosed | boolean | Wenn auf  true  gesetzt, ist die Kurve geschlossen. |

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
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Ruft den Endpunkt der Form ab.

Wert: Der Endpunkt der Form.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Liest oder schreibt die Kurvenpunkte.

Wert: Die Kurvenpunkte.

**Returns:**
com.aspose.psd.PointF[]
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Gibt die Segmente der Form zurück.

Wert: Die Formsegmente.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Ruft den Startpunkt der Form ab.

Wert: Der Startpunkt der Form.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getTension() {#getTension--}
```
public float getTension()
```


Liest oder setzt die Kurvenspannung.

Wert: Die Kurvenspannung.

**Returns:**
float
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
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Liest oder schreibt einen Wert, der angibt, ob die Form geschlossen ist.

Wert:  true  wenn die Form geschlossen ist; andernfalls  false .

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


Kehrt die Reihenfolge der Punkte für diese Form um.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Liest oder schreibt einen Wert, der angibt, ob die Form geschlossen ist.

Wert:  true  wenn die Form geschlossen ist; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setPoints(PointF[] value) {#setPoints-com.aspose.psd.PointF---}
```
public void setPoints(PointF[] value)
```


Liest oder schreibt die Kurvenpunkte.

Wert: Die Kurvenpunkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Liest oder setzt die Kurvenspannung.

Wert: Die Kurvenspannung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

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

