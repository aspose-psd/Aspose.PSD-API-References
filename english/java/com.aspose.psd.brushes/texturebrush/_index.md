---
title: TextureBrush
second_title: Aspose.PSD for Java API Reference
description: Each property of the Aspose.Imaging.Brushes.TextureBrush class is a Aspose.Imaging.Brush object that uses an image to fill the interior of a shape.
type: docs
weight: 18
url: /java/com.aspose.psd.brushes/texturebrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush)
```
public final class TextureBrush extends TransformBrush
```

Each property of the  Aspose.Imaging.Brushes.TextureBrush  class is a  Aspose.Imaging.Brush  object that uses an image to fill the interior of a shape. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextureBrush(Image image)](#TextureBrush-com.aspose.psd.Image-) | Initializes a new instance of the  Aspose.Imaging.Brushes.TextureBrush  class that uses the specified image. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.psd.Image-int-) | Initializes a new instance of the  Aspose.Imaging.Brushes.TextureBrush  class that uses the specified image and wrap mode. |
| [TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)](#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.RectangleF-) | Initializes a new instance of the  Aspose.Imaging.Brushes.TextureBrush  class that uses the specified image, wrap mode, and bounding rectangle. |
| [TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)](#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.Rectangle-) | Initializes a new instance of the  Aspose.Imaging.Brushes.TextureBrush  class that uses the specified image, wrap mode, and bounding rectangle. |
| [TextureBrush(Image image, RectangleF destinationRectangle)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Initializes a new instance of the  Aspose.Imaging.Brushes.TextureBrush  class that uses the specified image and bounding rectangle. |
| [TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.ImageAttributes-) | Initializes a new instance of the  Aspose.Imaging.Brushes.TextureBrush  class that uses the specified image, bounding rectangle, and image attributes. |
| [TextureBrush(Image image, Rectangle destinationRectangle)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Initializes a new instance of the  Aspose.Imaging.Brushes.TextureBrush  class that uses the specified image and bounding rectangle. |
| [TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.ImageAttributes-) | Initializes a new instance of the  Aspose.Imaging.Brushes.TextureBrush  class that uses the specified image, bounding rectangle, and image attributes. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. |
| [deepClone()](#deepClone--) | Creates a new deep clone of the current  Brush . |
| [dispose()](#dispose--) | Disposes the current instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Gets a value indicating whether this instance is disposed. |
| [getImage()](#getImage--) | Gets the  com.aspose.psd.Image  object associated with this  com.aspose.psd.brushes.TextureBrush  object. |
| [getImageAttributes()](#getImageAttributes--) | Gets the  ImageAttributes  associated with this  TextureBrush . |
| [getImageRectangle()](#getImageRectangle--) | Gets the  Rectangle  associated with this  TextureBrush . |
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
### TextureBrush(Image image) {#TextureBrush-com.aspose.psd.Image-}
```
public TextureBrush(Image image)
```


Initializes a new instance of the  Aspose.Imaging.Brushes.TextureBrush  class that uses the specified image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The  Aspose.Imaging.Image  object with which this  Aspose.Imaging.Brushes.TextureBrush  object fills interiors. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.psd.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Initializes a new instance of the  Aspose.Imaging.Brushes.TextureBrush  class that uses the specified image and wrap mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The  Aspose.Imaging.Image  object with which this  Aspose.Imaging.Brushes.TextureBrush  object fills interiors. |
| wrapMode | int | A  Aspose.Imaging.WrapMode  enumeration that specifies how this  Aspose.Imaging.Brushes.TextureBrush  object is tiled. |

### TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle) {#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)
```


Initializes a new instance of the  Aspose.Imaging.Brushes.TextureBrush  class that uses the specified image, wrap mode, and bounding rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The  Aspose.Imaging.Image  object with which this  Aspose.Imaging.Brushes.TextureBrush  object fills interiors. |
| wrapMode | int | A  Aspose.Imaging.WrapMode  enumeration that specifies how this  Aspose.Imaging.Brushes.TextureBrush  object is tiled. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | A  Aspose.Imaging.RectangleF  structure that represents the bounding rectangle for this  Aspose.Imaging.Brushes.TextureBrush  object. |

### TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle) {#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.Rectangle-}
```
public TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)
```


Initializes a new instance of the  Aspose.Imaging.Brushes.TextureBrush  class that uses the specified image, wrap mode, and bounding rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The  Aspose.Imaging.Image  object with which this  Aspose.Imaging.Brushes.TextureBrush  object fills interiors. |
| wrapMode | int | A  Aspose.Imaging.WrapMode  enumeration that specifies how this  Aspose.Imaging.Brushes.TextureBrush  object is tiled. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | A  Aspose.Imaging.Rectangle  structure that represents the bounding rectangle for this  Aspose.Imaging.Brushes.TextureBrush  object. |

### TextureBrush(Image image, RectangleF destinationRectangle) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public TextureBrush(Image image, RectangleF destinationRectangle)
```


Initializes a new instance of the  Aspose.Imaging.Brushes.TextureBrush  class that uses the specified image and bounding rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The  Aspose.Imaging.Image  object with which this  Aspose.Imaging.Brushes.TextureBrush  object fills interiors. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | A  Aspose.Imaging.RectangleF  structure that represents the bounding rectangle for this  Aspose.Imaging.Brushes.TextureBrush  object. |

### TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)
```


Initializes a new instance of the  Aspose.Imaging.Brushes.TextureBrush  class that uses the specified image, bounding rectangle, and image attributes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The  Aspose.Imaging.Image  object with which this  Aspose.Imaging.Brushes.TextureBrush  object fills interiors. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | A  Aspose.Imaging.RectangleF  structure that represents the bounding rectangle for this  Aspose.Imaging.Brushes.TextureBrush  object. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | An  com.aspose.psd.ImageAttributes  object that contains additional information about the image used by this  Aspose.Imaging.Brushes.TextureBrush  object. |

### TextureBrush(Image image, Rectangle destinationRectangle) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public TextureBrush(Image image, Rectangle destinationRectangle)
```


Initializes a new instance of the  Aspose.Imaging.Brushes.TextureBrush  class that uses the specified image and bounding rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The  Aspose.Imaging.Image  object with which this  Aspose.Imaging.Brushes.TextureBrush  object fills interiors. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | A  Aspose.Imaging.Rectangle  structure that represents the bounding rectangle for this  Aspose.Imaging.Brushes.TextureBrush  object. |

### TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.ImageAttributes-}
```
public TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)
```


Initializes a new instance of the  Aspose.Imaging.Brushes.TextureBrush  class that uses the specified image, bounding rectangle, and image attributes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The  Aspose.Imaging.Image  object with which this  Aspose.Imaging.Brushes.TextureBrush  object fills interiors. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | A  Aspose.Imaging.Rectangle  structure that represents the bounding rectangle for this  Aspose.Imaging.Brushes.TextureBrush  object. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | An  com.aspose.psd.ImageAttributes  object that contains additional information about the image used by this  Aspose.Imaging.Brushes.TextureBrush  object. |

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
### getImage() {#getImage--}
```
public Image getImage()
```


Gets the  com.aspose.psd.Image  object associated with this  com.aspose.psd.brushes.TextureBrush  object.

Value: An  com.aspose.psd.Image  object that represents the image with which this  com.aspose.psd.brushes.TextureBrush  object fills shapes.

**Returns:**
[Image](../../com.aspose.psd/image)
### getImageAttributes() {#getImageAttributes--}
```
public ImageAttributes getImageAttributes()
```


Gets the  ImageAttributes  associated with this  TextureBrush .

Value: The  ImageAttributes .

**Returns:**
[ImageAttributes](../../com.aspose.psd/imageattributes)
### getImageRectangle() {#getImageRectangle--}
```
public RectangleF getImageRectangle()
```


Gets the  Rectangle  associated with this  TextureBrush .

Value: The  Rectangle .

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
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

