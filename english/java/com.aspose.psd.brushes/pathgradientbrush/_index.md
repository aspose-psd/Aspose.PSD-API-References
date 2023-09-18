---
title: PathGradientBrush
second_title: Aspose.PSD for Java API Reference
description: Encapsulates a Aspose.Imaging.Brush object with a gradient.
type: docs
weight: 14
url: /java/com.aspose.psd.brushes/pathgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.PathGradientBrushBase](../../com.aspose.psd.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

Encapsulates a  Aspose.Imaging.Brush  object with a gradient. This class cannot be inherited.

The center color is white by default. A user can changed this value at any time later.

The surround colors array is initialized by single element containing white color by default. The surround colors may be changed later, however at least single element is required when setting up the surround colors.

See the  Blend  for more details about its initialization.
## Constructors

| Constructor | Description |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.psd.PointF---) | Initializes a new instance of the  PathGradientBrush  class with the specified points. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.PointF---int-) | Initializes a new instance of the  PathGradientBrush  class with the specified points and wrap mode. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.psd.Point---) | Initializes a new instance of the  PathGradientBrush  class with the specified points. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.Point---int-) | Initializes a new instance of the  PathGradientBrush  class with the specified points and wrap mode. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.psd.GraphicsPath-) | Initializes a new instance of the  PathGradientBrush  class with the specified path. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. |
| [deepClone()](#deepClone--) | Creates a new deep clone of the current  Brush . |
| [dispose()](#dispose--) | Disposes the current instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlend()](#getBlend--) | Gets a  Aspose.Imaging.Blend  that specifies positions and factors that define a custom falloff for the gradient. |
| [getCenterColor()](#getCenterColor--) | Gets the color at the center of the path gradient. |
| [getCenterPoint()](#getCenterPoint--) | Gets or sets the center point of the path gradient. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Gets a value indicating whether this instance is disposed. |
| [getFocusScales()](#getFocusScales--) | Gets the focus point for the gradient falloff. |
| [getGraphicsPath()](#getGraphicsPath--) | Gets the graphics path this brush was build upon. |
| [getInterpolationColors()](#getInterpolationColors--) | Gets a  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient. |
| [getOpacity()](#getOpacity--) | Gets the brush opacity. |
| [getPathPoints()](#getPathPoints--) | Gets the path points this brush was build upon. |
| [getSurroundColors()](#getSurroundColors--) | Gets an array of colors that correspond to the points in the path this  PathGradientBrush  fills. |
| [getTransform()](#getTransform--) | Gets or sets a copy  Aspose.Imaging.Matrix  that defines a local geometric transform for this  TransformBrush . |
| [getWrapMode()](#getWrapMode--) | Gets or sets a  Aspose.Imaging.WrapMode  enumeration that indicates the wrap mode for this  TransformBrush . |
| [hashCode()](#hashCode--) |  |
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
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Sets a  Aspose.Imaging.Blend  that specifies positions and factors that define a custom falloff for the gradient. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Creates a gradient with a center color and a linear falloff to one surrounding color. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Creates a gradient with a center color and a linear falloff to each surrounding color. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.psd.Color-) | Sets the color at the center of the path gradient. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | Gets or sets the center point of the path gradient. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | Gets or sets the focus point for the gradient falloff. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Sets a  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient. |
| [setOpacity(float value)](#setOpacity-float-) | Sets the brush opacity. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Creates a gradient brush that changes color starting from the center of the path outward to the path's boundary. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Creates a gradient brush that changes color starting from the center of the path outward to the path's boundary. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.psd.Color---) | Sets an array of colors that correspond to the points in the path this  PathGradientBrush  fills. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Gets or sets a copy  Aspose.Imaging.Matrix  that defines a local geometric transform for this  TransformBrush . |
| [setWrapMode(int value)](#setWrapMode-int-) | Gets or sets a  Aspose.Imaging.WrapMode  enumeration that indicates the wrap mode for this  TransformBrush . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Translates the local geometric transform by the specified dimensions. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Translates the local geometric transform by the specified dimensions in the specified order. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.psd.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Initializes a new instance of the  PathGradientBrush  class with the specified points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | An array of  Aspose.Imaging.PointF  structures that represents the points that make up the vertices of the path. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Initializes a new instance of the  PathGradientBrush  class with the specified points and wrap mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | An array of  Aspose.Imaging.PointF  structures that represents the points that make up the vertices of the path. |
| wrapMode | int | A  Aspose.Imaging.WrapMode  that specifies how fills drawn with this  PathGradientBrush  are tiled. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.psd.Point---}
```
public PathGradientBrush(Point[] points)
```


Initializes a new instance of the  PathGradientBrush  class with the specified points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | An array of  Aspose.Imaging.Point  structures that represents the points that make up the vertices of the path. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Initializes a new instance of the  PathGradientBrush  class with the specified points and wrap mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | An array of  Aspose.Imaging.Point  structures that represents the points that make up the vertices of the path. |
| wrapMode | int | A  Aspose.Imaging.WrapMode  that specifies how fills drawn with this  PathGradientBrush  are tiled. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.psd.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Initializes a new instance of the  PathGradientBrush  class with the specified path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | The  GraphicsPath  that defines the area filled by this  PathGradientBrush . |

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
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Gets a  Aspose.Imaging.Blend  that specifies positions and factors that define a custom falloff for the gradient.

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Gets the color at the center of the path gradient.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  that represents the color at the center of the path gradient.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Gets or sets the center point of the path gradient.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the center point of the path gradient.
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
### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Gets the focus point for the gradient falloff.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Gets the graphics path this brush was build upon.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The graphics path.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Gets a  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Gets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque.

**Returns:**
float - The brush opacity value.
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Gets the path points this brush was build upon.

**Returns:**
com.aspose.psd.PointF[] - The path points.
### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Gets an array of colors that correspond to the points in the path this  PathGradientBrush  fills.

**Returns:**
com.aspose.psd.Color[] - An array of  com.aspose.psd.Color  structures that represents the colors associated with each point in the path this  PathGradientBrush  fills.
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


Creates a gradient with a center color and a linear falloff to one surrounding color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| focus | float | A value from 0 through 1 that specifies where, along any radial from the center of the path to the path's boundary, the center color will be at its highest intensity. A value of 1 (the default) places the highest intensity at the center of the path. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Creates a gradient with a center color and a linear falloff to each surrounding color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| focus | float | A value from 0 through 1 that specifies where, along any radial from the center of the path to the path's boundary, the center color will be at its highest intensity. A value of 1 (the default) places the highest intensity at the center of the path. |
| scale | float | A value from 0 through 1 that specifies the maximum intensity of the center color that gets blended with the boundary color. A value of 1 causes the highest possible intensity of the center color, and it is the default value. |

### setCenterColor(Color value) {#setCenterColor-com.aspose.psd.Color-}
```
public void setCenterColor(Color value)
```


Sets the color at the center of the path gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | A  com.aspose.psd.Color  that represents the color at the center of the path gradient. |

### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.psd.PointF-}
```
public void setCenterPoint(PointF value)
```


Gets or sets the center point of the path gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | A  Aspose.Imaging.PointF  that represents the center point of the path gradient. |

### setFocusScales(PointF value) {#setFocusScales-com.aspose.psd.PointF-}
```
public void setFocusScales(PointF value)
```


Gets or sets the focus point for the gradient falloff.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Sets a  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The brush opacity value. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Creates a gradient brush that changes color starting from the center of the path outward to the path's boundary. The transition from one color to another is based on a bell-shaped curve.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| focus | float | A value from 0 through 1 that specifies where, along any radial from the center of the path to the path's boundary, the center color will be at its highest intensity. A value of 1 (the default) places the highest intensity at the center of the path. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Creates a gradient brush that changes color starting from the center of the path outward to the path's boundary. The transition from one color to another is based on a bell-shaped curve.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| focus | float | A value from 0 through 1 that specifies where, along any radial from the center of the path to the path's boundary, the center color will be at its highest intensity. A value of 1 (the default) places the highest intensity at the center of the path. |
| scale | float | A value from 0 through 1 that specifies the maximum intensity of the center color that gets blended with the boundary color. A value of 1 causes the highest possible intensity of the center color, and it is the default value. |

### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.psd.Color---}
```
public void setSurroundColors(Color[] value)
```


Sets an array of colors that correspond to the points in the path this  PathGradientBrush  fills.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | An array of  com.aspose.psd.Color  structures that represents the colors associated with each point in the path this  PathGradientBrush  fills. |

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

