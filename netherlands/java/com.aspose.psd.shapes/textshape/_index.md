---
title: "TextShape"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt een tekstvorm voor."
type: docs
weight: 18
url: /nl/java/com.aspose.psd.shapes/textshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape)
```
public final class TextShape extends RectangleProjectedShape
```

Stelt een tekstvorm voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TextShape()](#TextShape--) | Initialiseert een nieuw exemplaar van de  TextShape  klasse. |
| [TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)](#TextShape-java.lang.String-com.aspose.psd.RectangleF-com.aspose.psd.Font-com.aspose.psd.StringFormat-) | Initialiseert een nieuw exemplaar van de  TextShape  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Haalt de grenzen van het object op. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Haalt de grenzen van het object op. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Haalt de grenzen van het object op. |
| [getCenter()](#getCenter--) | Haalt het middelpunt van de vorm op. |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | Haalt op of stelt het lettertype in dat wordt gebruikt om de tekst te tekenen. |
| [getLeftBottom()](#getLeftBottom--) | Haalt het linksonderhoekpunt van de rechthoek op. |
| [getLeftTop()](#getLeftTop--) | Haalt het linkerbovenhoekpunt van de rechthoek op. |
| [getRectangleHeight()](#getRectangleHeight--) | Haalt de hoogte van de rechthoek op. |
| [getRectangleWidth()](#getRectangleWidth--) | Haalt de breedte van de rechthoek op. |
| [getRightBottom()](#getRightBottom--) | Haalt het rechtsonderhoekpunt van de rechthoek op. |
| [getRightTop()](#getRightTop--) | Haalt het rechterbovenhoekpunt van de rechthoek op. |
| [getSegments()](#getSegments--) | Haalt de vormsegmenten op. |
| [getText()](#getText--) | Haalt op of stelt de getekende tekst in. |
| [getTextFormat()](#getTextFormat--) | Haalt op of stelt het tekstformaat in. |
| [hasSegments()](#hasSegments--) | Haalt een waarde op die aangeeft of de vorm segmenten heeft. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFont(Font value)](#setFont-com.aspose.psd.Font-) | Haalt op of stelt het lettertype in dat wordt gebruikt om de tekst te tekenen. |
| [setText(String value)](#setText-java.lang.String-) | Haalt op of stelt de getekende tekst in. |
| [setTextFormat(StringFormat value)](#setTextFormat-com.aspose.psd.StringFormat-) | Haalt op of stelt het tekstformaat in. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Past de opgegeven transformatie toe op de vorm. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextShape() {#TextShape--}
```
public TextShape()
```


Initialiseert een nieuw exemplaar van de  TextShape  klasse.

### TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat) {#TextShape-java.lang.String-com.aspose.psd.RectangleF-com.aspose.psd.Font-com.aspose.psd.StringFormat-}
```
public TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)
```


Initialiseert een nieuw exemplaar van de  TextShape  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tekst | java.lang.String | De tekst om te tekenen. |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | De tekstrechthoek. |
| font | [Font](../../com.aspose.psd/font) | Het te gebruiken lettertype. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | Het tekenreeksformaat. |

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
### getFont() {#getFont--}
```
public Font getFont()
```


Haalt op of stelt het lettertype in dat wordt gebruikt om de tekst te tekenen.

Waarde: Het lettertype dat wordt gebruikt om de tekst te tekenen.

**Returns:**
[Font](../../com.aspose.psd/font)
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
### getText() {#getText--}
```
public String getText()
```


Haalt op of stelt de getekende tekst in.

Waarde: De getekende tekst.

**Returns:**
java.lang.String
### getTextFormat() {#getTextFormat--}
```
public StringFormat getTextFormat()
```


Haalt op of stelt het tekstformaat in.

Waarde: Het tekstformaat.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat)
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


Haalt op of stelt het lettertype in dat wordt gebruikt om de tekst te tekenen.

Waarde: Het lettertype dat wordt gebruikt om de tekst te tekenen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Font](../../com.aspose.psd/font) |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Haalt op of stelt de getekende tekst in.

Waarde: De getekende tekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setTextFormat(StringFormat value) {#setTextFormat-com.aspose.psd.StringFormat-}
```
public void setTextFormat(StringFormat value)
```


Haalt op of stelt het tekstformaat in.

Waarde: Het tekstformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
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

