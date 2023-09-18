---
title: LinearGradientBrush
second_title: Aspose.PSD for Java API Reference
description: Encapsulates a Aspose.Imaging.Brush with a linear gradient.
type: docs
weight: 11
url: /java/com.aspose.psd.brushes/lineargradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Encapsulates a  Aspose.Imaging.Brush  with a linear gradient. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [LinearGradientBrush()](#LinearGradientBrush--) | Initializes a new instance of the  LinearGradientBrush  class with default parameters. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-) | Initializes a new instance of the  LinearGradientBrush  class with the specified points and colors. |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-) | Initializes a new instance of the  LinearGradientBrush  class with the specified points and colors. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Initializes a new instance of the  LinearGradientBrush  class based on a rectangle, starting and ending colors, and an orientation angle. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Initializes a new instance of the  LinearGradientBrush  class based on a rectangle, starting and ending colors, and an orientation angle. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Initializes a new instance of the  LinearGradientBrush  class based on a rectangle, starting and ending colors, and an orientation angle. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Initializes a new instance of the  LinearGradientBrush  class based on a rectangle, starting and ending colors, and an orientation angle. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. |
| [deepClone()](#deepClone--) | Creates a new deep clone of the current  Brush . |
| [dispose()](#dispose--) | Disposes the current instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Gets the gradient angle. |
| [getBlend()](#getBlend--) | Gets a  Aspose.Imaging.Blend  that specifies positions and factors that define a custom falloff for the gradient. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Gets a value indicating whether this instance is disposed. |
| [getEndColor()](#getEndColor--) | Gets the ending gradient color. |
| [getGammaCorrection()](#getGammaCorrection--) | Gets a value indicating whether gamma correction is enabled for this  LinearGradientBrushBase . |
| [getInterpolationColors()](#getInterpolationColors--) | Gets a  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient. |
| [getLinearColors()](#getLinearColors--) | Gets the starting and ending colors of the gradient. |
| [getOpacity()](#getOpacity--) | Gets the brush opacity. |
| [getRectangle()](#getRectangle--) | Gets a rectangular region that defines the starting and ending points of the gradient. |
| [getStartColor()](#getStartColor--) | Gets the starting gradient color. |
| [getTransform()](#getTransform--) | Gets or sets a copy  Aspose.Imaging.Matrix  that defines a local geometric transform for this  TransformBrush . |
| [getWrapMode()](#getWrapMode--) | Gets or sets a  Aspose.Imaging.WrapMode  enumeration that indicates the wrap mode for this  TransformBrush . |
| [hashCode()](#hashCode--) |  |
| [isAngleScalable()](#isAngleScalable--) | Gets a value indicating whether  LinearGradientBrushBase.Angle  is changed during trasnformations with this  LinearGradientBrushBase . |
| [isTransformChanged()](#isTransformChanged--) | Gets a value indicating whether transformations were changed in some way. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Multiplies the  Aspose.Imaging.Matrix  that represents the local geometric transform of this  LinearGradientBrush  by the specified  Aspose.Imaging.Matrix  by prepending the specified  Aspose.Imaging.Matrix . |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Multiplies the  Aspose.Imaging.Matrix  that represents the local geometric transform of this  LinearGradientBrush  by the specified  Aspose.Imaging.Matrix  in the specified order. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Resets the  TransformBrush.Transform  property to identity. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rotates the local geometric transform by the specified amount. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rotates the local geometric transform by the specified amount in the specified order. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Scales the local geometric transform by the specified amounts. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Scales the local geometric transform by the specified amounts in the specified order. |
| [setAngle(float value)](#setAngle-float-) | Sets the gradient angle. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Sets a value indicating whether  LinearGradientBrushBase.Angle  is changed during trasnformations with this  LinearGradientBrushBase . |
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Sets a  Aspose.Imaging.Blend  that specifies positions and factors that define a custom falloff for the gradient. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Creates a linear gradient with a center color and a linear falloff to a single color on both ends. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Creates a linear gradient with a center color and a linear falloff to a single color on both ends. |
| [setEndColor(Color value)](#setEndColor-com.aspose.psd.Color-) | Sets the ending gradient color. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Sets a value indicating whether gamma correction is enabled for this  LinearGradientBrushBase . |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Sets a  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.psd.Color---) | Sets the starting and ending colors of the gradient. |
| [setOpacity(float value)](#setOpacity-float-) | Sets the brush opacity. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Sets a rectangular region that defines the starting and ending points of the gradient. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Creates a gradient falloff based on a bell-shaped curve. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Creates a gradient falloff based on a bell-shaped curve. |
| [setStartColor(Color value)](#setStartColor-com.aspose.psd.Color-) | Sets the starting gradient color. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Gets or sets a copy  Aspose.Imaging.Matrix  that defines a local geometric transform for this  TransformBrush . |
| [setWrapMode(int value)](#setWrapMode-int-) | Gets or sets a  Aspose.Imaging.WrapMode  enumeration that indicates the wrap mode for this  TransformBrush . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Translates the local geometric transform by the specified dimensions. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Translates the local geometric transform by the specified dimensions in the specified order. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Initializes a new instance of the  LinearGradientBrush  class with default parameters. The starting color is black, the ending color is white, the angle is 45 degrees and the rectangle is located in (0,0) with size (1,1).

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Initializes a new instance of the  LinearGradientBrush  class with the specified points and colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | A  Aspose.Imaging.Point  structure that represents the starting point of the linear gradient. |
| point2 | [Point](../../com.aspose.psd/point) | A  Aspose.Imaging.Point  structure that represents the endpoint of the linear gradient. |
| color1 | [Color](../../com.aspose.psd/color) | A  com.aspose.psd.Color  structure that represents the starting color of the linear gradient. |
| color2 | [Color](../../com.aspose.psd/color) | A  com.aspose.psd.Color  structure that represents the ending color of the linear gradient. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Initializes a new instance of the  LinearGradientBrush  class with the specified points and colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | A  Aspose.Imaging.PointF  structure that represents the starting point of the linear gradient. |
| point2 | [PointF](../../com.aspose.psd/pointf) | A  Aspose.Imaging.PointF  structure that represents the endpoint of the linear gradient. |
| color1 | [Color](../../com.aspose.psd/color) | A  com.aspose.psd.Color  structure that represents the starting color of the linear gradient. |
| color2 | [Color](../../com.aspose.psd/color) | A  com.aspose.psd.Color  structure that represents the ending color of the linear gradient. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Initializes a new instance of the  LinearGradientBrush  class based on a rectangle, starting and ending colors, and an orientation angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | A  Aspose.Imaging.RectangleF  structure that specifies the bounds of the linear gradient. |
| color1 | [Color](../../com.aspose.psd/color) | A  com.aspose.psd.Color  structure that represents the starting color for the gradient. |
| color2 | [Color](../../com.aspose.psd/color) | A  com.aspose.psd.Color  structure that represents the ending color for the gradient. |
| angle | float | The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Initializes a new instance of the  LinearGradientBrush  class based on a rectangle, starting and ending colors, and an orientation angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | A  Aspose.Imaging.RectangleF  structure that specifies the bounds of the linear gradient. |
| color1 | [Color](../../com.aspose.psd/color) | A  com.aspose.psd.Color  structure that represents the starting color for the gradient. |
| color2 | [Color](../../com.aspose.psd/color) | A  com.aspose.psd.Color  structure that represents the ending color for the gradient. |
| angle | float | The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initializes a new instance of the  LinearGradientBrush  class based on a rectangle, starting and ending colors, and an orientation angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | A  Aspose.Imaging.RectangleF  structure that specifies the bounds of the linear gradient. |
| color1 | [Color](../../com.aspose.psd/color) | A  com.aspose.psd.Color  structure that represents the starting color for the gradient. |
| color2 | [Color](../../com.aspose.psd/color) | A  com.aspose.psd.Color  structure that represents the ending color for the gradient. |
| angle | float | The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line. |
| isAngleScalable | boolean | if set to  true  the angle is changed during transformations with this  LinearGradientBrush . |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initializes a new instance of the  LinearGradientBrush  class based on a rectangle, starting and ending colors, and an orientation angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | A  Aspose.Imaging.RectangleF  structure that specifies the bounds of the linear gradient. |
| color1 | [Color](../../com.aspose.psd/color) | A  com.aspose.psd.Color  structure that represents the starting color for the gradient. |
| color2 | [Color](../../com.aspose.psd/color) | A  com.aspose.psd.Color  structure that represents the ending color for the gradient. |
| angle | float | The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line. |
| isAngleScalable | boolean | if set to  true  the angle is changed during transformations with this  LinearGradientBrush . |

### close() {#close--}
```
public void close()
```


Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. This method simply call dispose method.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Creates a new deep clone of the current  Brush .

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Disposes the current instance.

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
### getAngle() {#getAngle--}
```
public float getAngle()
```


Gets the gradient angle.

**Returns:**
float - The gradient angle.
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Gets a  Aspose.Imaging.Blend  that specifies positions and factors that define a custom falloff for the gradient.

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gets a value indicating whether this instance is disposed.

**Returns:**
boolean -  true  if disposed; otherwise,  false .
### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Gets the ending gradient color.

**Returns:**
[Color](../../com.aspose.psd/color) - The ending gradient color.
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Gets a value indicating whether gamma correction is enabled for this  LinearGradientBrushBase .

**Returns:**
boolean - The value is true if gamma correction is enabled for this  LinearGradientBrushBase ; otherwise, false.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Gets a  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Gets the starting and ending colors of the gradient.

**Returns:**
com.aspose.psd.Color[] - An array of two  Color  structures that represents the starting and ending colors of the gradient.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Gets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque.

**Returns:**
float - The brush opacity value.
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Gets a rectangular region that defines the starting and ending points of the gradient.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient.
### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Gets the starting gradient color.

**Returns:**
[Color](../../com.aspose.psd/color) - The starting gradient color.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Gets or sets a copy  Aspose.Imaging.Matrix  that defines a local geometric transform for this  TransformBrush .

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Gets or sets a  Aspose.Imaging.WrapMode  enumeration that indicates the wrap mode for this  TransformBrush .

**Returns:**
int - A  Aspose.Imaging.WrapMode  that specifies how fills drawn with this  TransformBrush  are tiled.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Gets a value indicating whether  LinearGradientBrushBase.Angle  is changed during trasnformations with this  LinearGradientBrushBase .

**Returns:**
boolean -  true  if  LinearGradientBrushBase.Angle  is changed during transformations with this  LinearGradientBrushBase ; otherwise,  false .
### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+.

Value:  True  if transformation was changed; otherwise,  false .

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplies the  Aspose.Imaging.Matrix  that represents the local geometric transform of this  LinearGradientBrush  by the specified  Aspose.Imaging.Matrix  by prepending the specified  Aspose.Imaging.Matrix .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | The  Aspose.Imaging.Matrix  by which to multiply the geometric transform. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplies the  Aspose.Imaging.Matrix  that represents the local geometric transform of this  LinearGradientBrush  by the specified  Aspose.Imaging.Matrix  in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | The  Aspose.Imaging.Matrix  by which to multiply the geometric transform. |
| order | int | A  Aspose.Imaging.MatrixOrder  that specifies in which order to multiply the two matrices. |

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


Resets the  TransformBrush.Transform  property to identity.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The angle of rotation. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rotates the local geometric transform by the specified amount in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The angle of rotation. |
| order | int | A  Aspose.Imaging.MatrixOrder  that specifies whether to append or prepend the rotation matrix. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Scales the local geometric transform by the specified amounts in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |
| order | int | A  Aspose.Imaging.MatrixOrder  that specifies whether to append or prepend the scaling matrix. |

### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Sets the gradient angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The gradient angle. |

### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Sets a value indicating whether  LinearGradientBrushBase.Angle  is changed during trasnformations with this  LinearGradientBrushBase .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if  LinearGradientBrushBase.Angle  is changed during transformations with this  LinearGradientBrushBase ; otherwise,  false . |

### setBlend(Blend value) {#setBlend-com.aspose.psd.Blend-}
```
public void setBlend(Blend value)
```


Sets a  Aspose.Imaging.Blend  that specifies positions and factors that define a custom falloff for the gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Blend](../../com.aspose.psd/blend) | A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Creates a linear gradient with a center color and a linear falloff to a single color on both ends.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| focus | float | A value from 0 through 1 that specifies the center of the gradient (the point where the gradient is composed of only the ending color). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Creates a linear gradient with a center color and a linear falloff to a single color on both ends.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| focus | float | A value from 0 through 1 that specifies the center of the gradient (the point where the gradient is composed of only the ending color). |
| scale | float | A value from 0 through1 that specifies how fast the colors falloff from the starting color to  focus  (ending color) |

### setEndColor(Color value) {#setEndColor-com.aspose.psd.Color-}
```
public void setEndColor(Color value)
```


Sets the ending gradient color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | The ending gradient color. |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Sets a value indicating whether gamma correction is enabled for this  LinearGradientBrushBase .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | The value is true if gamma correction is enabled for this  LinearGradientBrushBase ; otherwise, false. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Sets a  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient. |

### setLinearColors(Color[] value) {#setLinearColors-com.aspose.psd.Color---}
```
public void setLinearColors(Color[] value)
```


Sets the starting and ending colors of the gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | An array of two  Color  structures that represents the starting and ending colors of the gradient. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The brush opacity value. |

### setRectangle(RectangleF value) {#setRectangle-com.aspose.psd.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Sets a rectangular region that defines the starting and ending points of the gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Creates a gradient falloff based on a bell-shaped curve.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| focus | float | A value from 0 through 1 that specifies the center of the gradient (the point where the starting color and ending color are blended equally). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Creates a gradient falloff based on a bell-shaped curve.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| focus | float | A value from 0 through 1 that specifies the center of the gradient (the point where the gradient is composed of only the ending color). |
| scale | float | A value from 0 through 1 that specifies how fast the colors falloff from the  focus . |

### setStartColor(Color value) {#setStartColor-com.aspose.psd.Color-}
```
public void setStartColor(Color value)
```


Sets the starting gradient color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | The starting gradient color. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Gets or sets a copy  Aspose.Imaging.Matrix  that defines a local geometric transform for this  TransformBrush .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Gets or sets a  Aspose.Imaging.WrapMode  enumeration that indicates the wrap mode for this  TransformBrush .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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


Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Translates the local geometric transform by the specified dimensions in the specified order.

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

