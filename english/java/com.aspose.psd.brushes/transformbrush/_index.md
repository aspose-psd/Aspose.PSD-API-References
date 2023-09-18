---
title: TransformBrush
second_title: Aspose.PSD for Java API Reference
description: A Brush with transform capabilities.
type: docs
weight: 19
url: /java/com.aspose.psd.brushes/transformbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush)
```
public abstract class TransformBrush extends Brush
```

A  Brush  with transform capabilities.
## Constructors

| Constructor | Description |
| --- | --- |
| [TransformBrush()](#TransformBrush--) |  |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. |
| [deepClone()](#deepClone--) | Creates a new deep clone of the current  Brush . |
| [dispose()](#dispose--) | Disposes the current instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Gets a value indicating whether this instance is disposed. |
| [getOpacity()](#getOpacity--) | Gets the brush opacity. |
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
| [setOpacity(float value)](#setOpacity-float-) | Sets the brush opacity. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Gets or sets a copy  Aspose.Imaging.Matrix  that defines a local geometric transform for this  TransformBrush . |
| [setWrapMode(int value)](#setWrapMode-int-) | Gets or sets a  Aspose.Imaging.WrapMode  enumeration that indicates the wrap mode for this  TransformBrush . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Translates the local geometric transform by the specified dimensions. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Translates the local geometric transform by the specified dimensions in the specified order. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransformBrush() {#TransformBrush--}
```
public TransformBrush()
```


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
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Gets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque.

**Returns:**
float - The brush opacity value.
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

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The brush opacity value. |

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

