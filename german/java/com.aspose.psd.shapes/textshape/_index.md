---
title: "TextShape"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt eine Textform dar."
type: docs
weight: 18
url: /de/java/com.aspose.psd.shapes/textshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape)
```
public final class TextShape extends RectangleProjectedShape
```

Stellt eine Textform dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextShape()](#TextShape--) | Initialisiert eine neue Instanz der  TextShape  Klasse. |
| [TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)](#TextShape-java.lang.String-com.aspose.psd.RectangleF-com.aspose.psd.Font-com.aspose.psd.StringFormat-) | Initialisiert eine neue Instanz der  TextShape  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Liest die Begrenzungen des Objekts. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Liest die Begrenzungen des Objekts. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Liest die Begrenzungen des Objekts. |
| [getCenter()](#getCenter--) | Gibt das Zentrum der Form zurück. |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | Liest oder setzt die Schriftart, die zum Zeichnen des Textes verwendet wird. |
| [getLeftBottom()](#getLeftBottom--) | Liefert den linken unteren Rechteckpunkt. |
| [getLeftTop()](#getLeftTop--) | Liefert den linken oberen Rechteckpunkt. |
| [getRectangleHeight()](#getRectangleHeight--) | Liefert die Rechteckhöhe. |
| [getRectangleWidth()](#getRectangleWidth--) | Liefert die Rechteckbreite. |
| [getRightBottom()](#getRightBottom--) | Liefert den rechten unteren Rechteckpunkt. |
| [getRightTop()](#getRightTop--) | Liefert den rechten oberen Rechteckpunkt. |
| [getSegments()](#getSegments--) | Gibt die Segmente der Form zurück. |
| [getText()](#getText--) | Liest oder setzt den gezeichneten Text. |
| [getTextFormat()](#getTextFormat--) | Liest oder setzt das Textformat. |
| [hasSegments()](#hasSegments--) | Gibt einen Wert zurück, der angibt, ob die Form Segmente hat. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFont(Font value)](#setFont-com.aspose.psd.Font-) | Liest oder setzt die Schriftart, die zum Zeichnen des Textes verwendet wird. |
| [setText(String value)](#setText-java.lang.String-) | Liest oder setzt den gezeichneten Text. |
| [setTextFormat(StringFormat value)](#setTextFormat-com.aspose.psd.StringFormat-) | Liest oder setzt das Textformat. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Wendet die angegebene Transformation auf die Form an. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextShape() {#TextShape--}
```
public TextShape()
```


Initialisiert eine neue Instanz der  TextShape  Klasse.

### TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat) {#TextShape-java.lang.String-com.aspose.psd.RectangleF-com.aspose.psd.Font-com.aspose.psd.StringFormat-}
```
public TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)
```


Initialisiert eine neue Instanz der  TextShape  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der zu zeichnende Text. |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Das Textrechteck. |
| font | [Font](../../com.aspose.psd/font) | Die zu verwendende Schriftart. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | Das Zeichenkettenformat. |

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
### getFont() {#getFont--}
```
public Font getFont()
```


Liest oder setzt die Schriftart, die zum Zeichnen des Textes verwendet wird.

Wert: Die zum Zeichnen des Textes verwendete Schriftart.

**Returns:**
[Font](../../com.aspose.psd/font)
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
### getText() {#getText--}
```
public String getText()
```


Liest oder setzt den gezeichneten Text.

Wert: Der gezeichnete Text.

**Returns:**
java.lang.String
### getTextFormat() {#getTextFormat--}
```
public StringFormat getTextFormat()
```


Liest oder setzt das Textformat.

Wert: Das Textformat.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat)
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




### setFont(Font value) {#setFont-com.aspose.psd.Font-}
```
public void setFont(Font value)
```


Liest oder setzt die Schriftart, die zum Zeichnen des Textes verwendet wird.

Wert: Die zum Zeichnen des Textes verwendete Schriftart.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Font](../../com.aspose.psd/font) |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Liest oder setzt den gezeichneten Text.

Wert: Der gezeichnete Text.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setTextFormat(StringFormat value) {#setTextFormat-com.aspose.psd.StringFormat-}
```
public void setTextFormat(StringFormat value)
```


Liest oder setzt das Textformat.

Wert: Das Textformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StringFormat](../../com.aspose.psd/stringformat) |  |

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

