---
title: "PathGradientBrush"
second_title: "Aspose.PSD 的 Java API 参考"
description: "封装了带有渐变的 Aspose.Imaging.Brush 对象。"
type: docs
weight: 14
url: /zh/java/com.aspose.psd.brushes/pathgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.PathGradientBrushBase](../../com.aspose.psd.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

封装一个带有渐变的  Aspose.Imaging.Brush  对象。此类不可被继承。

默认情况下，中心颜色为白色。用户可以随时更改此值。

默认情况下，环绕颜色数组使用包含白色的单个元素进行初始化。环绕颜色以后可以更改，但在设置环绕颜色时至少需要一个元素。

有关其初始化的更多细节，请参阅 Blend。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.psd.PointF---) | 使用指定的点初始化 PathGradientBrush 类的新实例。 |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.PointF---int-) | 使用指定的点和包装模式初始化 PathGradientBrush 类的新实例。 |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.psd.Point---) | 使用指定的点初始化 PathGradientBrush 类的新实例。 |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.Point---int-) | 使用指定的点和包装模式初始化 PathGradientBrush 类的新实例。 |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.psd.GraphicsPath-) | 使用指定的路径初始化 PathGradientBrush 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [close()](#close--) | 实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。 |
| [deepClone()](#deepClone--) | 创建当前  Brush  的深度克隆副本。 |
| [dispose()](#dispose--) | 释放当前实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlend()](#getBlend--) | 获取一个 Aspose.Imaging.Blend，用于指定定义渐变自定义衰减的位置信息和因子。 |
| [getCenterColor()](#getCenterColor--) | 获取路径渐变中心的颜色。 |
| [getCenterPoint()](#getCenterPoint--) | 获取或设置路径渐变的中心点。 |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | 获取指示此实例是否已释放的值。 |
| [getFocusScales()](#getFocusScales--) | 获取渐变衰减的焦点。 |
| [getGraphicsPath()](#getGraphicsPath--) | 获取此画笔构建所基于的图形路径。 |
| [getInterpolationColors()](#getInterpolationColors--) | 获取一个  com.aspose.psd.ColorBlend ，它定义了多颜色线性渐变。 |
| [getOpacity()](#getOpacity--) | 获取画笔不透明度。 |
| [getPathPoints()](#getPathPoints--) | 获取此画笔构建所基于的路径点。 |
| [getSurroundColors()](#getSurroundColors--) | 获取一个颜色数组，该数组对应于此 PathGradientBrush 所填充路径中的点。 |
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
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | 设置一个 Aspose.Imaging.Blend，用于指定定义渐变自定义衰减的位置信息和因子。 |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | 创建一个以中心颜色为起点、线性衰减到单一环绕颜色的渐变。 |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | 创建一个以中心颜色为起点、线性衰减到每个环绕颜色的渐变。 |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.psd.Color-) | 设置路径渐变中心的颜色。 |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | 获取或设置路径渐变的中心点。 |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | 获取或设置渐变衰减的焦点。 |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | 设置一个 com.aspose.psd.ColorBlend，用于定义多颜色线性渐变。 |
| [setOpacity(float value)](#setOpacity-float-) | 设置画笔不透明度。 |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | 创建一个渐变画刷，使颜色从路径中心向外变化直至路径边界。 |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | 创建一个渐变画刷，使颜色从路径中心向外变化直至路径边界。 |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.psd.Color---) | 设置一个颜色数组，该数组对应于此 PathGradientBrush 所填充路径中的点。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | 获取或设置一个 Aspose.Imaging.Matrix 副本，该副本定义此 TransformBrush 的本地几何变换。 |
| [setWrapMode(int value)](#setWrapMode-int-) | 获取或设置一个 Aspose.Imaging.WrapMode 枚举，指示此 TransformBrush 的包装模式。 |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 按指定的尺寸平移本地几何变换。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 按指定的顺序，以指定的尺寸平移本地几何变换。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.psd.PointF---}
```
public PathGradientBrush(PointF[] points)
```


使用指定的点初始化 PathGradientBrush 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 一个由  Aspose.Imaging.PointF  结构组成的数组，表示构成路径顶点的点。 |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


使用指定的点和包装模式初始化 PathGradientBrush 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 一个由  Aspose.Imaging.PointF  结构组成的数组，表示构成路径顶点的点。 |
| wrapMode | int | 指定使用此  PathGradientBrush 绘制的填充如何平铺的  Aspose.Imaging.WrapMode。 |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.psd.Point---}
```
public PathGradientBrush(Point[] points)
```


使用指定的点初始化 PathGradientBrush 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | 一个由  Aspose.Imaging.Point  结构组成的数组，表示构成路径顶点的点。 |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


使用指定的点和包装模式初始化 PathGradientBrush 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | 一个由  Aspose.Imaging.Point  结构组成的数组，表示构成路径顶点的点。 |
| wrapMode | int | 指定使用此  PathGradientBrush 绘制的填充如何平铺的  Aspose.Imaging.WrapMode。 |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.psd.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


使用指定的路径初始化 PathGradientBrush 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 定义此  PathGradientBrush 填充区域的  GraphicsPath。 |

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
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


获取一个 Aspose.Imaging.Blend，用于指定定义渐变自定义衰减的位置信息和因子。

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


获取路径渐变中心的颜色。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  that represents the color at the center of the path gradient.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


获取或设置路径渐变的中心点。

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


获取指示此实例是否已释放的值。

**Returns:**
boolean -  true  如果已释放；否则，  false 。
### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


获取渐变衰减的焦点。

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


获取此画笔构建所基于的图形路径。

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The graphics path.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


获取一个  com.aspose.psd.ColorBlend ，它定义了多颜色线性渐变。

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


获取画刷的不透明度。该值应在 0 到 1 之间。0 表示画刷完全可见，1 表示画刷完全不透明。

**Returns:**
float - 画刷不透明度值。
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


获取此画笔构建所基于的路径点。

**Returns:**
com.aspose.psd.PointF[] - 路径点。
### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


获取一个颜色数组，该数组对应于此 PathGradientBrush 所填充路径中的点。

**Returns:**
com.aspose.psd.Color[] - 表示此  PathGradientBrush 填充路径中每个点关联颜色的 com.aspose.psd.Color 结构数组。
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


创建一个以中心颜色为起点、线性衰减到单一环绕颜色的渐变。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 焦点 | float | 一个介于 0 到 1 之间的值，指定沿从路径中心到路径边界的任意径向，中心颜色在最高强度时的位置。值为 1（默认）时，最高强度位于路径中心。 |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


创建一个以中心颜色为起点、线性衰减到每个环绕颜色的渐变。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 焦点 | float | 一个介于 0 到 1 之间的值，指定沿从路径中心到路径边界的任意径向，中心颜色在最高强度时的位置。值为 1（默认）时，最高强度位于路径中心。 |
| 比例 | float | 一个介于 0 到 1 之间的值，指定中心颜色与边界颜色混合时的最大强度。值为 1 时会产生中心颜色的最高可能强度，这是默认值。 |

### setCenterColor(Color value) {#setCenterColor-com.aspose.psd.Color-}
```
public void setCenterColor(Color value)
```


设置路径渐变中心的颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 表示路径渐变中心颜色的 com.aspose.psd.Color。 |

### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.psd.PointF-}
```
public void setCenterPoint(PointF value)
```


获取或设置路径渐变的中心点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | 一个表示路径渐变中心点的 Aspose.Imaging.PointF。 |

### setFocusScales(PointF value) {#setFocusScales-com.aspose.psd.PointF-}
```
public void setFocusScales(PointF value)
```


获取或设置渐变衰减的焦点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | 一个表示渐变衰减焦点的 Aspose.Imaging.PointF。 |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


设置一个 com.aspose.psd.ColorBlend，用于定义多颜色线性渐变。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | 一个定义多色线性渐变的 com.aspose.psd.ColorBlend。 |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全可见，1 表示画笔完全不透明。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 画笔不透明度的值。 |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


创建一种渐变画刷，从路径中心向路径边界逐渐改变颜色。颜色之间的过渡基于钟形曲线。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 焦点 | float | 一个介于 0 到 1 之间的值，指定沿从路径中心到路径边界的任意径向，中心颜色在最高强度时的位置。值为 1（默认）时，最高强度位于路径中心。 |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


创建一种渐变画刷，从路径中心向路径边界逐渐改变颜色。颜色之间的过渡基于钟形曲线。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 焦点 | float | 一个介于 0 到 1 之间的值，指定沿从路径中心到路径边界的任意径向，中心颜色在最高强度时的位置。值为 1（默认）时，最高强度位于路径中心。 |
| 比例 | float | 一个介于 0 到 1 之间的值，指定中心颜色与边界颜色混合时的最大强度。值为 1 时会产生中心颜色的最高可能强度，这是默认值。 |

### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.psd.Color---}
```
public void setSurroundColors(Color[] value)
```


设置一个颜色数组，该数组对应于此 PathGradientBrush 所填充路径中的点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | 表示此  PathGradientBrush 填充路径中每个点关联颜色的 com.aspose.psd.Color 结构数组。 |

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

