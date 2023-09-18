---
title: Pen
second_title: Aspose.PSD for Java API Reference
description: Defines an object used to draw lines curves and figures.
type: docs
weight: 77
url: /java/com.aspose.psd/pen/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.TransparencySupporter](../../com.aspose.psd/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Defines an object used to draw lines, curves and figures.
## Constructors

| Constructor | Description |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.psd.Color-) | Initializes a new instance of the  Pen  class with the specified color. |
| [Pen(Color color, float width)](#Pen-com.aspose.psd.Color-float-) | Initializes a new instance of the  Pen  class with the specified  Color  and  Pen.Width  properties. |
| [Pen(Brush brush)](#Pen-com.aspose.psd.Brush-) | Initializes a new instance of the  Pen  class with the specified  Brush . |
| [Pen(Brush brush, float width)](#Pen-com.aspose.psd.Brush-float-) | Initializes a new instance of the  Pen  class with the specified  Brush  and  Pen.Width . |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Gets the alignment for this  Pen . |
| [getBrush()](#getBrush--) | Gets the  Brush  that determines attributes of this  Pen . |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Gets the color of this  Pen . |
| [getCompoundArray()](#getCompoundArray--) | Gets an array of values that specifies a compound pen. |
| [getCustomEndCap()](#getCustomEndCap--) | Gets a custom cap to use at the end of lines drawn with this  Pen . |
| [getCustomStartCap()](#getCustomStartCap--) | Gets a custom cap to use at the beginning of lines drawn with this  Pen . |
| [getDashCap()](#getDashCap--) | Gets the cap style used at the end of the dashes that make up dashed lines drawn with this  Pen . |
| [getDashOffset()](#getDashOffset--) | Gets the distance from the start of a line to the beginning of a dash pattern. |
| [getDashPattern()](#getDashPattern--) | Gets an array of custom dashes and spaces. |
| [getDashStyle()](#getDashStyle--) | Gets the style used for dashed lines drawn with this  Pen . |
| [getEndCap()](#getEndCap--) | Gets the cap style used at the end of lines drawn with this  Pen . |
| [getLineJoin()](#getLineJoin--) | Gets the join style for the ends of two consecutive lines drawn with this  Pen . |
| [getMiterLimit()](#getMiterLimit--) | Gets the limit of the thickness of the join on a mitered corner. |
| [getOpacity()](#getOpacity--) | Gets the object's opacity. |
| [getPenType()](#getPenType--) | Gets the style of lines drawn with this  Pen . |
| [getStartCap()](#getStartCap--) | Gets the cap style used at the beginning of lines drawn with this  Pen . |
| [getTransform()](#getTransform--) | Gets a copy of the geometric transformation for this  Pen . |
| [getWidth()](#getWidth--) | Gets the width of this  Pen , in units of the Graphics object used for drawing. |
| [hashCode()](#hashCode--) |  |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Multiplies the transformation matrix for this  Pen  by the specified  Matrix . |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Multiplies the transformation matrix for this  Pen  by the specified  Matrix  in the specified order. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Resets the geometric transformation matrix for this  Pen  to identity. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rotates the local geometric transformation by the specified angle. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rotates the local geometric transformation by the specified angle in the specified order. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Scales the local geometric transformation by the specified factors. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Scales the local geometric transformation by the specified factors in the specified order. |
| [setAlignment(int value)](#setAlignment-int-) | Sets the alignment for this  Pen . |
| [setBrush(Brush value)](#setBrush-com.aspose.psd.Brush-) | Sets the  Brush  that determines attributes of this  Pen . |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Sets the color of this  Pen . |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Sets an array of values that specifies a compound pen. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.psd.CustomLineCap-) | Sets a custom cap to use at the end of lines drawn with this  Pen . |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.psd.CustomLineCap-) | Sets a custom cap to use at the beginning of lines drawn with this  Pen . |
| [setDashCap(int value)](#setDashCap-int-) | Sets the cap style used at the end of the dashes that make up dashed lines drawn with this  Pen . |
| [setDashOffset(float value)](#setDashOffset-float-) | Sets the distance from the start of a line to the beginning of a dash pattern. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Sets an array of custom dashes and spaces. |
| [setDashStyle(int value)](#setDashStyle-int-) | Sets the style used for dashed lines drawn with this  Pen . |
| [setEndCap(int value)](#setEndCap-int-) | Sets the cap style used at the end of lines drawn with this  Pen . |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Sets the values that determine the style of cap used to end lines drawn by this  Pen . |
| [setLineJoin(int value)](#setLineJoin-int-) | Sets the join style for the ends of two consecutive lines drawn with this  Pen . |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Sets the limit of the thickness of the join on a mitered corner. |
| [setOpacity(float value)](#setOpacity-float-) | Sets the object's opacity. |
| [setStartCap(int value)](#setStartCap-int-) | Sets the cap style used at the beginning of lines drawn with this  Pen . |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Sets a copy of the geometric transformation for this  Pen . |
| [setWidth(float value)](#setWidth-float-) | Sets the width of this  Pen , in units of the Graphics object used for drawing. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Translates the local geometric transformation by the specified dimensions. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Translates the local geometric transformation by the specified dimensions in the specified order. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pen(Color color) {#Pen-com.aspose.psd.Color-}
```
public Pen(Color color)
```


Initializes a new instance of the  Pen  class with the specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | A  Color  structure that indicates the color of this  Pen . |

### Pen(Color color, float width) {#Pen-com.aspose.psd.Color-float-}
```
public Pen(Color color, float width)
```


Initializes a new instance of the  Pen  class with the specified  Color  and  Pen.Width  properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | A  Color  structure that indicates the color of this  Pen . |
| width | float | A value indicating the width of this  Pen . |

### Pen(Brush brush) {#Pen-com.aspose.psd.Brush-}
```
public Pen(Brush brush)
```


Initializes a new instance of the  Pen  class with the specified  Brush .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | A  Brush  that determines the fill properties of this  Pen . |

### Pen(Brush brush, float width) {#Pen-com.aspose.psd.Brush-float-}
```
public Pen(Brush brush, float width)
```


Initializes a new instance of the  Pen  class with the specified  Brush  and  Pen.Width .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | A  Brush  that determines the characteristics of this  Pen . |
| width | float | The width of the new  Pen . |

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Gets the alignment for this  Pen .

**Returns:**
int - A  PenAlignment  that represents the alignment for this  Pen .
### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Gets the  Brush  that determines attributes of this  Pen .

**Returns:**
[Brush](../../com.aspose.psd/brush) - A  Brush  that determines attributes of this  Pen .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Gets the color of this  Pen .

**Returns:**
[Color](../../com.aspose.psd/color) - A  Color  structure that represents the color of this  Pen .
### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Gets an array of values that specifies a compound pen. A compound pen draws a compound line made up of parallel lines and spaces.

**Returns:**
float[] - An array of real numbers that specifies the compound array. The elements in the array must be in increasing order, not less than 0, and not greater than 1.
### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Gets a custom cap to use at the end of lines drawn with this  Pen .

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen .
### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Gets a custom cap to use at the beginning of lines drawn with this  Pen .

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen .
### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Gets the cap style used at the end of the dashes that make up dashed lines drawn with this  Pen .

**Returns:**
int - One of the  DashCap  values that represents the cap style used at the beginning and end of the dashes that make up dashed lines drawn with this  Pen .
### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Gets the distance from the start of a line to the beginning of a dash pattern.

**Returns:**
float - The distance from the start of a line to the beginning of a dash pattern.
### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Gets an array of custom dashes and spaces.

**Returns:**
float[] - An array of real numbers that specifies the lengths of alternating dashes and spaces in dashed lines.
### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Gets the style used for dashed lines drawn with this  Pen .

**Returns:**
int - A  DashStyle  that represents the style used for dashed lines drawn with this  Pen .
### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Gets the cap style used at the end of lines drawn with this  Pen .

**Returns:**
int - One of the  LineCap  values that represents the cap style used at the end of lines drawn with this  Pen .
### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Gets the join style for the ends of two consecutive lines drawn with this  Pen .

**Returns:**
int - A  LineJoin  that represents the join style for the ends of two consecutive lines drawn with this  Pen .
### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Gets the limit of the thickness of the join on a mitered corner.

**Returns:**
float - The limit of the thickness of the join on a mitered corner.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Gets the object's opacity. The value should be between 0 and 1. Value of 0 means that object is fully visible, value of 1 means the object is fully opaque.

**Returns:**
float - The opacity value.
### getPenType() {#getPenType--}
```
public int getPenType()
```


Gets the style of lines drawn with this  Pen .

**Returns:**
int - A  PenType  enumeration that specifies the style of lines drawn with this  Pen .
### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Gets the cap style used at the beginning of lines drawn with this  Pen .

**Returns:**
int - One of the  LineCap  values that represents the cap style used at the beginning of lines drawn with this  Pen .
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Gets a copy of the geometric transformation for this  Pen .

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Matrix  that represents the geometric transformation for this  Pen .
### getWidth() {#getWidth--}
```
public float getWidth()
```


Gets the width of this  Pen , in units of the Graphics object used for drawing.

**Returns:**
float - The width of this  Pen .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplies the transformation matrix for this  Pen  by the specified  Matrix .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | The  Matrix  object by which to multiply the transformation matrix. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplies the transformation matrix for this  Pen  by the specified  Matrix  in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | The  Matrix  by which to multiply the transformation matrix. |
| order | int | The order in which to perform the multiplication operation. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Resets the geometric transformation matrix for this  Pen  to identity.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Rotates the local geometric transformation by the specified angle. This method prepends the rotation to the transformation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The angle of rotation. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rotates the local geometric transformation by the specified angle in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The angle of rotation. |
| order | int | A  MatrixOrder  that specifies whether to append or prepend the rotation matrix. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Scales the local geometric transformation by the specified factors. This method prepends the scaling matrix to the transformation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sx | float | The factor by which to scale the transformation in the x-axis direction. |
| sy | float | The factor by which to scale the transformation in the y-axis direction. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Scales the local geometric transformation by the specified factors in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sx | float | The factor by which to scale the transformation in the x-axis direction. |
| sy | float | The factor by which to scale the transformation in the y-axis direction. |
| order | int | A  MatrixOrder  that specifies whether to append or prepend the scaling matrix. |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Sets the alignment for this  Pen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A  PenAlignment  that represents the alignment for this  Pen . |

### setBrush(Brush value) {#setBrush-com.aspose.psd.Brush-}
```
public void setBrush(Brush value)
```


Sets the  Brush  that determines attributes of this  Pen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Brush](../../com.aspose.psd/brush) | A  Brush  that determines attributes of this  Pen . |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


Sets the color of this  Pen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | A  Color  structure that represents the color of this  Pen . |

### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Sets an array of values that specifies a compound pen. A compound pen draws a compound line made up of parallel lines and spaces.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] | An array of real numbers that specifies the compound array. The elements in the array must be in increasing order, not less than 0, and not greater than 1. |

### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Sets a custom cap to use at the end of lines drawn with this  Pen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen . |

### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Sets a custom cap to use at the beginning of lines drawn with this  Pen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen . |

### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Sets the cap style used at the end of the dashes that make up dashed lines drawn with this  Pen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | One of the  DashCap  values that represents the cap style used at the beginning and end of the dashes that make up dashed lines drawn with this  Pen . |

### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Sets the distance from the start of a line to the beginning of a dash pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The distance from the start of a line to the beginning of a dash pattern. |

### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Sets an array of custom dashes and spaces.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] | An array of real numbers that specifies the lengths of alternating dashes and spaces in dashed lines. |

### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Sets the style used for dashed lines drawn with this  Pen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A  DashStyle  that represents the style used for dashed lines drawn with this  Pen . |

### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Sets the cap style used at the end of lines drawn with this  Pen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | One of the  LineCap  values that represents the cap style used at the end of lines drawn with this  Pen . |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Sets the values that determine the style of cap used to end lines drawn by this  Pen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startCap | int | A  LineCap  that represents the cap style to use at the beginning of lines drawn with this  Pen . |
| endCap | int | A  LineCap  that represents the cap style to use at the end of lines drawn with this  Pen . |
| dashCap | int | A  LineCap  that represents the cap style to use at the beginning or end of dashed lines drawn with this  Pen . |

### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Sets the join style for the ends of two consecutive lines drawn with this  Pen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A  LineJoin  that represents the join style for the ends of two consecutive lines drawn with this  Pen . |

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Sets the limit of the thickness of the join on a mitered corner.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The limit of the thickness of the join on a mitered corner. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Sets the object's opacity. The value should be between 0 and 1. Value of 0 means that object is fully visible, value of 1 means the object is fully opaque.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The opacity value. |

### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Sets the cap style used at the beginning of lines drawn with this  Pen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | One of the  LineCap  values that represents the cap style used at the beginning of lines drawn with this  Pen . |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Sets a copy of the geometric transformation for this  Pen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | A copy of the  Matrix  that represents the geometric transformation for this  Pen . |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Sets the width of this  Pen , in units of the Graphics object used for drawing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The width of this  Pen . |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Translates the local geometric transformation by the specified dimensions. This method prepends the translation to the transformation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Translates the local geometric transformation by the specified dimensions in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |
| order | int | The order (prepend or append) in which to apply the translation. |

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

