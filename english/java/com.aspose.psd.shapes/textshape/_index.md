---
title: TextShape
second_title: Aspose.PSD for Java API Reference
description: Represents a text shape.
type: docs
weight: 18
url: /java/com.aspose.psd.shapes/textshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape)
```
public final class TextShape extends RectangleProjectedShape
```

Represents a text shape.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextShape()](#TextShape--) | Initializes a new instance of the  TextShape  class. |
| [TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)](#TextShape-java.lang.String-com.aspose.psd.RectangleF-com.aspose.psd.Font-com.aspose.psd.StringFormat-) | Initializes a new instance of the  TextShape  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Gets the object's bounds. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Gets the object's bounds. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Gets the object's bounds. |
| [getCenter()](#getCenter--) | Gets the shape's center. |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | Gets or sets the font used to draw the text. |
| [getLeftBottom()](#getLeftBottom--) | Gets the left bottom rectangle point. |
| [getLeftTop()](#getLeftTop--) | Gets the left top rectangle point. |
| [getRectangleHeight()](#getRectangleHeight--) | Gets the rectangle height. |
| [getRectangleWidth()](#getRectangleWidth--) | Gets the rectangle width. |
| [getRightBottom()](#getRightBottom--) | Gets the right bottom rectangle point. |
| [getRightTop()](#getRightTop--) | Gets the right top rectangle point. |
| [getSegments()](#getSegments--) | Gets the shape segments. |
| [getText()](#getText--) | Gets or sets the drawn text. |
| [getTextFormat()](#getTextFormat--) | Gets or sets the text format. |
| [hasSegments()](#hasSegments--) | Gets a value indicating whether shape has segments. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFont(Font value)](#setFont-com.aspose.psd.Font-) | Gets or sets the font used to draw the text. |
| [setText(String value)](#setText-java.lang.String-) | Gets or sets the drawn text. |
| [setTextFormat(StringFormat value)](#setTextFormat-com.aspose.psd.StringFormat-) | Gets or sets the text format. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applies the specified transformation to the shape. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextShape() {#TextShape--}
```
public TextShape()
```


Initializes a new instance of the  TextShape  class.

### TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat) {#TextShape-java.lang.String-com.aspose.psd.RectangleF-com.aspose.psd.Font-com.aspose.psd.StringFormat-}
```
public TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)
```


Initializes a new instance of the  TextShape  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text to draw. |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | The text rectangle. |
| font | [Font](../../com.aspose.psd/font) | The font to use. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | The string format. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Gets the object's bounds.

Value: The object's bounds.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Gets the object's bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | The matrix to apply before bounds will be calculated. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Gets the object's bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | The matrix to apply before bounds will be calculated. |
| pen | [Pen](../../com.aspose.psd/pen) | The pen to use for object. This can influence the object's bounds size. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Gets the shape's center.

Value: The shape's center.

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


Gets or sets the font used to draw the text.

Value: The font used to draw the text.

**Returns:**
[Font](../../com.aspose.psd/font)
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Gets the left bottom rectangle point.

Value: The left bottom rectangle point.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Gets the left top rectangle point.

Value: The left top rectangle point.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Gets the rectangle height.

Value: The rectangle height.

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Gets the rectangle width.

Value: The rectangle width.

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Gets the right bottom rectangle point.

Value: The right bottom rectangle point.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Gets the right top rectangle point.

Value: The right top rectangle point.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Gets the shape segments.

Value: The shape segments.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getText() {#getText--}
```
public String getText()
```


Gets or sets the drawn text.

Value: The drawn text.

**Returns:**
java.lang.String
### getTextFormat() {#getTextFormat--}
```
public StringFormat getTextFormat()
```


Gets or sets the text format.

Value: The text format.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat)
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Gets a value indicating whether shape has segments.

Value:  True  if shape has segments; otherwise,  false .

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


Gets or sets the font used to draw the text.

Value: The font used to draw the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Font](../../com.aspose.psd/font) |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Gets or sets the drawn text.

Value: The drawn text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setTextFormat(StringFormat value) {#setTextFormat-com.aspose.psd.StringFormat-}
```
public void setTextFormat(StringFormat value)
```


Gets or sets the text format.

Value: The text format.

**Parameters:**
| Parameter | Type | Description |
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


Applies the specified transformation to the shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | The transformation to apply. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

