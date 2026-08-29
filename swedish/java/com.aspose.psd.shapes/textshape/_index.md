---
title: "TextShape"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar en textform."
type: docs
weight: 18
url: /sv/java/com.aspose.psd.shapes/textshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape)
```
public final class TextShape extends RectangleProjectedShape
```

Representerar en textform.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextShape()](#TextShape--) | Initierar en ny instans av den  TextShape  klassen. |
| [TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)](#TextShape-java.lang.String-com.aspose.psd.RectangleF-com.aspose.psd.Font-com.aspose.psd.StringFormat-) | Initierar en ny instans av den  TextShape  klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Hämtar objektets gränser. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Hämtar objektets gränser. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Hämtar objektets gränser. |
| [getCenter()](#getCenter--) | Hämtar formens centrum. |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | Hämtar eller anger teckensnittet som används för att rita texten. |
| [getLeftBottom()](#getLeftBottom--) | Hämtar den vänstra nedre rektangelpunkten. |
| [getLeftTop()](#getLeftTop--) | Hämtar den vänstra övre rektangelpunkten. |
| [getRectangleHeight()](#getRectangleHeight--) | Hämtar rektangelns höjd. |
| [getRectangleWidth()](#getRectangleWidth--) | Hämtar rektangelns bredd. |
| [getRightBottom()](#getRightBottom--) | Hämtar den högra nedre rektangelpunkten. |
| [getRightTop()](#getRightTop--) | Hämtar den högra övre rektangelpunkten. |
| [getSegments()](#getSegments--) | Hämtar formens segment. |
| [getText()](#getText--) | Hämtar eller anger den ritade texten. |
| [getTextFormat()](#getTextFormat--) | Hämtar eller anger textformatet. |
| [hasSegments()](#hasSegments--) | Hämtar ett värde som indikerar om formen har segment. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFont(Font value)](#setFont-com.aspose.psd.Font-) | Hämtar eller anger teckensnittet som används för att rita texten. |
| [setText(String value)](#setText-java.lang.String-) | Hämtar eller anger den ritade texten. |
| [setTextFormat(StringFormat value)](#setTextFormat-com.aspose.psd.StringFormat-) | Hämtar eller anger textformatet. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Tillämpar den angivna transformationen på formen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextShape() {#TextShape--}
```
public TextShape()
```


Initierar en ny instans av den  TextShape  klassen.

### TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat) {#TextShape-java.lang.String-com.aspose.psd.RectangleF-com.aspose.psd.Font-com.aspose.psd.StringFormat-}
```
public TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)
```


Initierar en ny instans av den  TextShape  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Texten att rita. |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Textrektangeln. |
| font | [Font](../../com.aspose.psd/font) | Teckensnittet att använda. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | Strängformatet. |

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
### getFont() {#getFont--}
```
public Font getFont()
```


Hämtar eller anger teckensnittet som används för att rita texten.

Värde: Teckensnittet som används för att rita texten.

**Returns:**
[Font](../../com.aspose.psd/font)
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
### getText() {#getText--}
```
public String getText()
```


Hämtar eller anger den ritade texten.

Värde: Den ritade texten.

**Returns:**
java.lang.String
### getTextFormat() {#getTextFormat--}
```
public StringFormat getTextFormat()
```


Hämtar eller anger textformatet.

Värde: Textformatet.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat)
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




### setFont(Font value) {#setFont-com.aspose.psd.Font-}
```
public void setFont(Font value)
```


Hämtar eller anger teckensnittet som används för att rita texten.

Värde: Teckensnittet som används för att rita texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Font](../../com.aspose.psd/font) |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Hämtar eller anger den ritade texten.

Värde: Den ritade texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setTextFormat(StringFormat value) {#setTextFormat-com.aspose.psd.StringFormat-}
```
public void setTextFormat(StringFormat value)
```


Hämtar eller anger textformatet.

Värde: Textformatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
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

