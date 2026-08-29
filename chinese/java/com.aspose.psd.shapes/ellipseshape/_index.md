---
title: "EllipseShape"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示椭圆形状。"
type: docs
weight: 13
url: /zh/java/com.aspose.psd.shapes/ellipseshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape)
```
public class EllipseShape extends RectangleShape
```

表示椭圆形状。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EllipseShape()](#EllipseShape--) | 初始化 EllipseShape 类的新实例。 |
| [EllipseShape(RectangleF rectangle)](#EllipseShape-com.aspose.psd.RectangleF-) | 初始化 EllipseShape 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | 获取对象的边界。 |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | 获取对象的边界。 |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | 获取对象的边界。 |
| [getCenter()](#getCenter--) | 获取形状的中心。 |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | 获取左下角矩形点。 |
| [getLeftTop()](#getLeftTop--) | 获取左上角矩形点。 |
| [getRectangleHeight()](#getRectangleHeight--) | 获取矩形高度。 |
| [getRectangleWidth()](#getRectangleWidth--) | 获取矩形宽度。 |
| [getRightBottom()](#getRightBottom--) | 获取右下角矩形点。 |
| [getRightTop()](#getRightTop--) | 获取右上角矩形点。 |
| [getSegments()](#getSegments--) | 获取形状的段。 |
| [hasSegments()](#hasSegments--) | 获取指示形状是否有段的值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | 将指定的变换应用于形状。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EllipseShape() {#EllipseShape--}
```
public EllipseShape()
```


初始化 EllipseShape 类的新实例。

### EllipseShape(RectangleF rectangle) {#EllipseShape-com.aspose.psd.RectangleF-}
```
public EllipseShape(RectangleF rectangle)
```


初始化 EllipseShape 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 矩形。 |

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
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


获取对象的边界。

值：对象的边界。

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


获取对象的边界。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 在计算边界之前要应用的矩阵。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


获取对象的边界。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 在计算边界之前要应用的矩阵。 |
| pen | [Pen](../../com.aspose.psd/pen) | 用于对象的笔。这可能会影响对象的边界大小。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


获取形状的中心。

值：形状的中心。

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


获取左下角矩形点。

值：左下矩形点。

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


获取左上角矩形点。

值：左上矩形点。

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


获取矩形高度。

值：矩形高度。

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


获取矩形宽度。

值：矩形宽度。

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


获取右下角矩形点。

值：右下矩形点。

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


获取右上角矩形点。

值：右上矩形点。

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


获取形状的段。

值：形状段。

**Returns:**
com.aspose.psd.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


获取指示形状是否有段的值。

值：如果形状有段，则为 True；否则为 false。

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


将指定的变换应用于形状。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | 要应用的变换。 |

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

