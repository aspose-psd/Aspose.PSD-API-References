---
title: "LinearGradientBrush"
second_title: "Aspose.PSD 的 Java API 参考"
description: "封装一个带有线性渐变的 Aspose.Imaging.Brush。"
type: docs
weight: 11
url: /zh/java/com.aspose.psd.brushes/lineargradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

封装一个带有线性渐变的 Aspose.Imaging.Brush。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LinearGradientBrush()](#LinearGradientBrush--) | 使用默认参数初始化 LinearGradientBrush 类的新实例。 |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-) | 使用指定的点和颜色初始化 LinearGradientBrush 类的新实例。 |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-) | 使用指定的点和颜色初始化 LinearGradientBrush 类的新实例。 |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-) | 基于矩形、起始和结束颜色以及方向角度，初始化 LinearGradientBrush 类的新实例。 |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-) | 基于矩形、起始和结束颜色以及方向角度，初始化 LinearGradientBrush 类的新实例。 |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | 基于矩形、起始和结束颜色以及方向角度，初始化 LinearGradientBrush 类的新实例。 |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | 基于矩形、起始和结束颜色以及方向角度，初始化 LinearGradientBrush 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [close()](#close--) | 实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。 |
| [deepClone()](#deepClone--) | 创建当前  Brush  的深度克隆副本。 |
| [dispose()](#dispose--) | 释放当前实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | 获取渐变角度。 |
| [getBlend()](#getBlend--) | 获取一个 Aspose.Imaging.Blend，用于指定定义渐变自定义衰减的位置信息和因子。 |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | 获取指示此实例是否已释放的值。 |
| [getEndColor()](#getEndColor--) | 获取结束渐变颜色。 |
| [getGammaCorrection()](#getGammaCorrection--) | 获取一个值，指示此  LinearGradientBrushBase  是否启用了伽马校正。 |
| [getInterpolationColors()](#getInterpolationColors--) | 获取一个  com.aspose.psd.ColorBlend ，它定义了多颜色线性渐变。 |
| [getLinearColors()](#getLinearColors--) | 获取渐变的起始和结束颜色。 |
| [getOpacity()](#getOpacity--) | 获取画笔不透明度。 |
| [getRectangle()](#getRectangle--) | 获取定义渐变起始和结束点的矩形区域。 |
| [getStartColor()](#getStartColor--) | 获取起始渐变颜色。 |
| [getTransform()](#getTransform--) | 获取或设置一个 Aspose.Imaging.Matrix 副本，该副本定义此 TransformBrush 的本地几何变换。 |
| [getWrapMode()](#getWrapMode--) | 获取或设置一个 Aspose.Imaging.WrapMode 枚举，指示此 TransformBrush 的包装模式。 |
| [hashCode()](#hashCode--) |  |
| [isAngleScalable()](#isAngleScalable--) | 获取一个值，指示在使用此 LinearGradientBrushBase 进行变换时是否更改 LinearGradientBrushBase.Angle。 |
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
| [setAngle(float value)](#setAngle-float-) | 设置渐变角度。 |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | 设置一个值，指示在使用此 LinearGradientBrushBase 进行变换时是否更改 LinearGradientBrushBase.Angle。 |
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | 设置一个 Aspose.Imaging.Blend，用于指定定义渐变自定义衰减的位置信息和因子。 |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | 创建一个线性渐变，中心颜色为指定颜色，两端线性衰减至单一颜色。 |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | 创建一个线性渐变，中心颜色为指定颜色，两端线性衰减至单一颜色。 |
| [setEndColor(Color value)](#setEndColor-com.aspose.psd.Color-) | 设置结束渐变颜色。 |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | 设置一个值，指示此 LinearGradientBrushBase 是否启用伽马校正。 |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | 设置一个 com.aspose.psd.ColorBlend，用于定义多颜色线性渐变。 |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.psd.Color---) | 设置渐变的起始和结束颜色。 |
| [setOpacity(float value)](#setOpacity-float-) | 设置画笔不透明度。 |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | 设置一个矩形区域，定义渐变的起始点和结束点。 |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | 基于钟形曲线创建渐变衰减。 |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | 基于钟形曲线创建渐变衰减。 |
| [setStartColor(Color value)](#setStartColor-com.aspose.psd.Color-) | 设置起始渐变颜色。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | 获取或设置一个 Aspose.Imaging.Matrix 副本，该副本定义此 TransformBrush 的本地几何变换。 |
| [setWrapMode(int value)](#setWrapMode-int-) | 获取或设置一个 Aspose.Imaging.WrapMode 枚举，指示此 TransformBrush 的包装模式。 |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 按指定的尺寸平移本地几何变换。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 按指定的顺序，以指定的尺寸平移本地几何变换。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


使用默认参数初始化 LinearGradientBrush 类的新实例。起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


使用指定的点和颜色初始化 LinearGradientBrush 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | 一个 Aspose.Imaging.Point 结构，表示线性渐变的起始点。 |
| point2 | [Point](../../com.aspose.psd/point) | 一个 Aspose.Imaging.Point 结构，表示线性渐变的结束点。 |
| color1 | [Color](../../com.aspose.psd/color) | 一个 com.aspose.psd.Color 结构，表示线性渐变的起始颜色。 |
| color2 | [Color](../../com.aspose.psd/color) | 一个 com.aspose.psd.Color 结构，表示线性渐变的结束颜色。 |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


使用指定的点和颜色初始化 LinearGradientBrush 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | 一个 Aspose.Imaging.PointF 结构，表示线性渐变的起始点。 |
| point2 | [PointF](../../com.aspose.psd/pointf) | 一个 Aspose.Imaging.PointF 结构，表示线性渐变的结束点。 |
| color1 | [Color](../../com.aspose.psd/color) | 一个 com.aspose.psd.Color 结构，表示线性渐变的起始颜色。 |
| color2 | [Color](../../com.aspose.psd/color) | 一个 com.aspose.psd.Color 结构，表示线性渐变的结束颜色。 |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


基于矩形、起始和结束颜色以及方向角度，初始化 LinearGradientBrush 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 一个 Aspose.Imaging.RectangleF 结构，指定线性渐变的边界。 |
| color1 | [Color](../../com.aspose.psd/color) | 一个 com.aspose.psd.Color 结构，表示渐变的起始颜色。 |
| color2 | [Color](../../com.aspose.psd/color) | 一个 com.aspose.psd.Color 结构，表示渐变的结束颜色。 |
| angle | float | 角度，以顺时针方向从 x 轴测量的度数，表示渐变方向线的角度。 |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


基于矩形、起始和结束颜色以及方向角度，初始化 LinearGradientBrush 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 一个 Aspose.Imaging.RectangleF 结构，指定线性渐变的边界。 |
| color1 | [Color](../../com.aspose.psd/color) | 一个 com.aspose.psd.Color 结构，表示渐变的起始颜色。 |
| color2 | [Color](../../com.aspose.psd/color) | 一个 com.aspose.psd.Color 结构，表示渐变的结束颜色。 |
| angle | float | 角度，以顺时针方向从 x 轴测量的度数，表示渐变方向线的角度。 |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


基于矩形、起始和结束颜色以及方向角度，初始化 LinearGradientBrush 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 一个 Aspose.Imaging.RectangleF 结构，指定线性渐变的边界。 |
| color1 | [Color](../../com.aspose.psd/color) | 一个 com.aspose.psd.Color 结构，表示渐变的起始颜色。 |
| color2 | [Color](../../com.aspose.psd/color) | 一个 com.aspose.psd.Color 结构，表示渐变的结束颜色。 |
| angle | float | 角度，以顺时针方向从 x 轴测量的度数，表示渐变方向线的角度。 |
| isAngleScalable | boolean | 如果设置为 true，则在使用此 LinearGradientBrush 进行变换时角度会被更改。 |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


基于矩形、起始和结束颜色以及方向角度，初始化 LinearGradientBrush 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 一个 Aspose.Imaging.RectangleF 结构，指定线性渐变的边界。 |
| color1 | [Color](../../com.aspose.psd/color) | 一个 com.aspose.psd.Color 结构，表示渐变的起始颜色。 |
| color2 | [Color](../../com.aspose.psd/color) | 一个 com.aspose.psd.Color 结构，表示渐变的结束颜色。 |
| angle | float | 角度，以顺时针方向从 x 轴测量的度数，表示渐变方向线的角度。 |
| isAngleScalable | boolean | 如果设置为 true，则在使用此 LinearGradientBrush 进行变换时角度会被更改。 |

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
### getAngle() {#getAngle--}
```
public float getAngle()
```


获取渐变角度。

**Returns:**
float - 渐变角度。
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


获取一个 Aspose.Imaging.Blend，用于指定定义渐变自定义衰减的位置信息和因子。

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


获取指示此实例是否已释放的值。

**Returns:**
boolean -  true  如果已释放；否则，  false 。
### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


获取结束渐变颜色。

**Returns:**
[Color](../../com.aspose.psd/color) - The ending gradient color.
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


获取一个值，指示此  LinearGradientBrushBase  是否启用了伽马校正。

**Returns:**
boolean - 如果为此 LinearGradientBrushBase 启用了伽马校正，则该值为 true；否则为 false。
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


获取一个  com.aspose.psd.ColorBlend ，它定义了多颜色线性渐变。

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


获取渐变的起始和结束颜色。

**Returns:**
com.aspose.psd.Color[] - 一个包含两个 Color 结构的数组，表示渐变的起始和结束颜色。
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


获取画刷的不透明度。该值应在 0 到 1 之间。0 表示画刷完全可见，1 表示画刷完全不透明。

**Returns:**
float - 画刷不透明度值。
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


获取定义渐变起始和结束点的矩形区域。

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient.
### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


获取起始渐变颜色。

**Returns:**
[Color](../../com.aspose.psd/color) - The starting gradient color.
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
### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


获取一个值，指示在使用此 LinearGradientBrushBase 进行变换时是否更改 LinearGradientBrushBase.Angle。

**Returns:**
boolean - 如果在使用此 LinearGradientBrushBase 进行变换时 LinearGradientBrushBase.Angle 被更改，则为 true；否则为 false。
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

### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


设置渐变角度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 渐变角度。 |

### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


设置一个值，指示在使用此 LinearGradientBrushBase 进行变换时是否更改 LinearGradientBrushBase.Angle。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | 如果在使用此 LinearGradientBrushBase 进行变换时 LinearGradientBrushBase.Angle 被更改，则为 true；否则为 false。 |

### setBlend(Blend value) {#setBlend-com.aspose.psd.Blend-}
```
public void setBlend(Blend value)
```


设置一个 Aspose.Imaging.Blend，用于指定定义渐变自定义衰减的位置信息和因子。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Blend](../../com.aspose.psd/blend) | 一个 Aspose.Imaging.Blend，表示渐变的自定义衰减。 |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


创建一个线性渐变，中心颜色为指定颜色，两端线性衰减至单一颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，用于指定渐变的中心（即渐变仅由结束颜色组成的点）。 |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


创建一个线性渐变，中心颜色为指定颜色，两端线性衰减至单一颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，用于指定渐变的中心（即渐变仅由结束颜色组成的点）。 |
| 比例 | float | 一个取值范围为 0 到 1 的值，用于指定颜色从起始颜色到焦点（结束颜色）的衰减速度。 |

### setEndColor(Color value) {#setEndColor-com.aspose.psd.Color-}
```
public void setEndColor(Color value)
```


设置结束渐变颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 结束渐变颜色。 |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


设置一个值，指示此 LinearGradientBrushBase 是否启用伽马校正。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | 如果为此 LinearGradientBrushBase 启用了伽马校正，则该值为 true；否则为 false。 |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


设置一个 com.aspose.psd.ColorBlend，用于定义多颜色线性渐变。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | 一个定义多色线性渐变的 com.aspose.psd.ColorBlend。 |

### setLinearColors(Color[] value) {#setLinearColors-com.aspose.psd.Color---}
```
public void setLinearColors(Color[] value)
```


设置渐变的起始和结束颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | 一个包含两个 Color 结构的数组，表示渐变的起始颜色和结束颜色。 |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全可见，1 表示画笔完全不透明。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 画笔不透明度的值。 |

### setRectangle(RectangleF value) {#setRectangle-com.aspose.psd.RectangleF-}
```
public void setRectangle(RectangleF value)
```


设置一个矩形区域，定义渐变的起始点和结束点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | 一个指定渐变起始和结束点的 com.aspose.psd.RectangleF 结构。 |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


基于钟形曲线创建渐变衰减。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，用于指定渐变的中心（即起始颜色和结束颜色等比例混合的点）。 |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


基于钟形曲线创建渐变衰减。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，用于指定渐变的中心（即渐变仅由结束颜色组成的点）。 |
| 比例 | float | 一个取值范围为 0 到 1 的值，用于指定颜色从 焦点 衰减的速度。 |

### setStartColor(Color value) {#setStartColor-com.aspose.psd.Color-}
```
public void setStartColor(Color value)
```


设置起始渐变颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 起始渐变颜色。 |

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

