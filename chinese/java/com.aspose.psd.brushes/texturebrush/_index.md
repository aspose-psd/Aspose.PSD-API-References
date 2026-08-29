---
title: "TextureBrush"
second_title: "Aspose.PSD 的 Java API 参考"
description: "Aspose.Imaging.Brushes.TextureBrush 类的每个属性都是使用图像填充形状内部的 Aspose.Imaging.Brush 对象。"
type: docs
weight: 18
url: /zh/java/com.aspose.psd.brushes/texturebrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush)
```
public final class TextureBrush extends TransformBrush
```

每个  Aspose.Imaging.Brushes.TextureBrush  类的属性都是使用图像填充形状内部的  Aspose.Imaging.Brush  对象。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextureBrush(Image image)](#TextureBrush-com.aspose.psd.Image-) | 初始化使用指定图像的  Aspose.Imaging.Brushes.TextureBrush  类的新实例。 |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.psd.Image-int-) | 初始化使用指定图像和 wrap mode 的  Aspose.Imaging.Brushes.TextureBrush  类的新实例。 |
| [TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)](#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.RectangleF-) | 初始化使用指定图像、wrap mode 和边界矩形的  Aspose.Imaging.Brushes.TextureBrush  类的新实例。 |
| [TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)](#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.Rectangle-) | 初始化使用指定图像、wrap mode 和边界矩形的  Aspose.Imaging.Brushes.TextureBrush  类的新实例。 |
| [TextureBrush(Image image, RectangleF destinationRectangle)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | 初始化使用指定图像和边界矩形的  Aspose.Imaging.Brushes.TextureBrush  类的新实例。 |
| [TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.ImageAttributes-) | 初始化使用指定图像、边界矩形和图像属性的  Aspose.Imaging.Brushes.TextureBrush  类的新实例。 |
| [TextureBrush(Image image, Rectangle destinationRectangle)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | 初始化使用指定图像和边界矩形的  Aspose.Imaging.Brushes.TextureBrush  类的新实例。 |
| [TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.ImageAttributes-) | 初始化使用指定图像、边界矩形和图像属性的  Aspose.Imaging.Brushes.TextureBrush  类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [close()](#close--) | 实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。 |
| [deepClone()](#deepClone--) | 创建当前  Brush  的深度克隆副本。 |
| [dispose()](#dispose--) | 释放当前实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | 获取指示此实例是否已释放的值。 |
| [getImage()](#getImage--) | 获取与此  com.aspose.psd.brushes.TextureBrush  对象关联的  com.aspose.psd.Image  对象。 |
| [getImageAttributes()](#getImageAttributes--) | 获取与此  TextureBrush  关联的  ImageAttributes  。 |
| [getImageRectangle()](#getImageRectangle--) | 获取与此  TextureBrush  关联的  Rectangle  。 |
| [getOpacity()](#getOpacity--) | 获取画笔不透明度。 |
| [getTransform()](#getTransform--) | 获取或设置一个 Aspose.Imaging.Matrix 副本，该副本定义此 TransformBrush 的本地几何变换。 |
| [getWrapMode()](#getWrapMode--) | 获取或设置一个 Aspose.Imaging.WrapMode 枚举，指示此 TransformBrush 的包装模式。 |
| [hashCode()](#hashCode--) |  |
| [isTransformChanged()](#isTransformChanged--) | 获取一个值，指示变换是否以某种方式被更改。 |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | 将表示此 LinearGradientBrush 本地几何变换的 Aspose.Imaging.Matrix 与指定的 Aspose.Imaging.Matrix 相乘，方式是将指定的 Aspose.Imaging.Matrix 前置。 |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | 将表示此 LinearGradientBrush 本地几何变换的 Aspose.Imaging.Matrix 与指定的 Aspose.Imaging.Matrix 按指定顺序相乘。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | 将 TransformBrush.Transform 属性重置为单位矩阵。 |
| [rotateTransform(float angle)](#rotateTransform-float-) | 按指定的角度旋转本地几何变换。 |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 按指定的顺序，以指定的角度旋转本地几何变换。 |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 按指定的比例缩放本地几何变换。 |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 按指定的顺序，以指定的比例缩放本地几何变换。 |
| [setOpacity(float value)](#setOpacity-float-) | 设置画笔不透明度。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | 获取或设置一个 Aspose.Imaging.Matrix 副本，该副本定义此 TransformBrush 的本地几何变换。 |
| [setWrapMode(int value)](#setWrapMode-int-) | 获取或设置一个 Aspose.Imaging.WrapMode 枚举，指示此 TransformBrush 的包装模式。 |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 按指定的尺寸平移本地几何变换。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 按指定的顺序，以指定的尺寸平移本地几何变换。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureBrush(Image image) {#TextureBrush-com.aspose.psd.Image-}
```
public TextureBrush(Image image)
```


初始化使用指定图像的  Aspose.Imaging.Brushes.TextureBrush  类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 此  Aspose.Imaging.Brushes.TextureBrush  对象用于填充内部的  Aspose.Imaging.Image  对象。 |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.psd.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


初始化使用指定图像和 wrap mode 的  Aspose.Imaging.Brushes.TextureBrush  类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 此  Aspose.Imaging.Brushes.TextureBrush  对象用于填充内部的  Aspose.Imaging.Image  对象。 |
| wrapMode | int | 一个  Aspose.Imaging.WrapMode  枚举，指定此  Aspose.Imaging.Brushes.TextureBrush  对象的平铺方式。 |

### TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle) {#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)
```


初始化使用指定图像、wrap mode 和边界矩形的  Aspose.Imaging.Brushes.TextureBrush  类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 此  Aspose.Imaging.Brushes.TextureBrush  对象用于填充内部的  Aspose.Imaging.Image  对象。 |
| wrapMode | int | 一个  Aspose.Imaging.WrapMode  枚举，指定此  Aspose.Imaging.Brushes.TextureBrush  对象的平铺方式。 |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 一个  Aspose.Imaging.RectangleF  结构，表示此  Aspose.Imaging.Brushes.TextureBrush  对象的边界矩形。 |

### TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle) {#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.Rectangle-}
```
public TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)
```


初始化使用指定图像、wrap mode 和边界矩形的  Aspose.Imaging.Brushes.TextureBrush  类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 此  Aspose.Imaging.Brushes.TextureBrush  对象用于填充内部的  Aspose.Imaging.Image  对象。 |
| wrapMode | int | 一个  Aspose.Imaging.WrapMode  枚举，指定此  Aspose.Imaging.Brushes.TextureBrush  对象的平铺方式。 |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 一个  Aspose.Imaging.Rectangle  结构，表示此  Aspose.Imaging.Brushes.TextureBrush  对象的边界矩形。 |

### TextureBrush(Image image, RectangleF destinationRectangle) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public TextureBrush(Image image, RectangleF destinationRectangle)
```


初始化使用指定图像和边界矩形的  Aspose.Imaging.Brushes.TextureBrush  类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 此  Aspose.Imaging.Brushes.TextureBrush  对象用于填充内部的  Aspose.Imaging.Image  对象。 |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 一个  Aspose.Imaging.RectangleF  结构，表示此  Aspose.Imaging.Brushes.TextureBrush  对象的边界矩形。 |

### TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)
```


初始化使用指定图像、边界矩形和图像属性的  Aspose.Imaging.Brushes.TextureBrush  类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 此  Aspose.Imaging.Brushes.TextureBrush  对象用于填充内部的  Aspose.Imaging.Image  对象。 |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 一个  Aspose.Imaging.RectangleF  结构，表示此  Aspose.Imaging.Brushes.TextureBrush  对象的边界矩形。 |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 一个  com.aspose.psd.ImageAttributes  对象，包含此  Aspose.Imaging.Brushes.TextureBrush  对象使用的图像的附加信息。 |

### TextureBrush(Image image, Rectangle destinationRectangle) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public TextureBrush(Image image, Rectangle destinationRectangle)
```


初始化使用指定图像和边界矩形的  Aspose.Imaging.Brushes.TextureBrush  类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 此  Aspose.Imaging.Brushes.TextureBrush  对象用于填充内部的  Aspose.Imaging.Image  对象。 |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 一个  Aspose.Imaging.Rectangle  结构，表示此  Aspose.Imaging.Brushes.TextureBrush  对象的边界矩形。 |

### TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.ImageAttributes-}
```
public TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)
```


初始化使用指定图像、边界矩形和图像属性的  Aspose.Imaging.Brushes.TextureBrush  类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 此  Aspose.Imaging.Brushes.TextureBrush  对象用于填充内部的  Aspose.Imaging.Image  对象。 |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 一个  Aspose.Imaging.Rectangle  结构，表示此  Aspose.Imaging.Brushes.TextureBrush  对象的边界矩形。 |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 一个  com.aspose.psd.ImageAttributes  对象，包含此  Aspose.Imaging.Brushes.TextureBrush  对象使用的图像的附加信息。 |

### close() {#close--}
```
public void close()
```


实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。此方法仅调用 dispose 方法。

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


创建当前  Brush  的深度克隆副本。

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


释放当前实例。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
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


获取指示此实例是否已释放的值。

**Returns:**
boolean -  true  如果已释放；否则，  false 。
### getImage() {#getImage--}
```
public Image getImage()
```


获取与此  com.aspose.psd.brushes.TextureBrush  对象关联的  com.aspose.psd.Image  对象。

值：一个  com.aspose.psd.Image  对象，表示此  com.aspose.psd.brushes.TextureBrush  对象用于填充形状的图像。

**Returns:**
[Image](../../com.aspose.psd/image)
### getImageAttributes() {#getImageAttributes--}
```
public ImageAttributes getImageAttributes()
```


获取与此  TextureBrush  关联的  ImageAttributes  。

值：该  ImageAttributes 。

**Returns:**
[ImageAttributes](../../com.aspose.psd/imageattributes)
### getImageRectangle() {#getImageRectangle--}
```
public RectangleF getImageRectangle()
```


获取与此  TextureBrush  关联的  Rectangle  。

值：该  Rectangle 。

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


获取画刷的不透明度。该值应在 0 到 1 之间。0 表示画刷完全可见，1 表示画刷完全不透明。

**Returns:**
float - 画刷不透明度值。
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


获取或设置一个 Aspose.Imaging.Matrix 副本，该副本定义此 TransformBrush 的本地几何变换。

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


获取或设置一个 Aspose.Imaging.WrapMode 枚举，指示此 TransformBrush 的包装模式。

**Returns:**
int - 一个 Aspose.Imaging.WrapMode，指定使用此 TransformBrush 绘制的填充如何平铺。
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


获取一个值，指示变换是否以某种方式被更改。例如设置变换矩阵或调用任何修改变换矩阵的方法。此属性为向后兼容 GDI+ 而引入。

值：如果变换被更改，则为 True；否则为 false。

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


将表示此 LinearGradientBrush 本地几何变换的 Aspose.Imaging.Matrix 与指定的 Aspose.Imaging.Matrix 相乘，方式是将指定的 Aspose.Imaging.Matrix 前置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 用于乘以几何变换的 Aspose.Imaging.Matrix。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


将表示此 LinearGradientBrush 本地几何变换的 Aspose.Imaging.Matrix 与指定的 Aspose.Imaging.Matrix 按指定顺序相乘。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 用于乘以几何变换的 Aspose.Imaging.Matrix。 |
| 顺序 | int | 一个 Aspose.Imaging.MatrixOrder，指定两个矩阵相乘的顺序。 |

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


将 TransformBrush.Transform 属性重置为单位矩阵。

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


按指定量旋转局部几何变换。此方法将在变换前预先添加旋转。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度。 |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


按指定的顺序，以指定的角度旋转本地几何变换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度。 |
| 顺序 | int | 一个 Aspose.Imaging.MatrixOrder，指定是追加还是预先添加旋转矩阵。 |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


按指定量缩放局部几何变换。此方法将在变换前预先添加缩放矩阵。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


按指定的顺序，以指定的比例缩放本地几何变换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |
| 顺序 | int | 一个 Aspose.Imaging.MatrixOrder，指定是追加还是预先添加缩放矩阵。 |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全可见，1 表示画笔完全不透明。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 画笔不透明度的值。 |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


获取或设置一个 Aspose.Imaging.Matrix 副本，该副本定义此 TransformBrush 的本地几何变换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


获取或设置一个 Aspose.Imaging.WrapMode 枚举，指示此 TransformBrush 的包装模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

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


按指定的尺寸平移本地几何变换。此方法将平移预置到变换之前。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dx | float | x 方向平移的值。 |
| dy | float | y 方向平移的值。 |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


按指定的顺序，以指定的尺寸平移本地几何变换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dx | float | x 方向平移的值。 |
| dy | float | y 方向平移的值。 |
| 顺序 | int | 应用平移的顺序（预置或追加）。 |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

