---
title: "RectangleF"
second_title: "Aspose.PSD 的 Java API 参考"
description: "存储一组四个浮点数，表示矩形的位置和大小。"
type: docs
weight: 89
url: /zh/java/com.aspose.psd/rectanglef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

存储一组四个浮点数，表示矩形的位置和大小。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | 使用指定的位置和大小初始化一个新的  com.aspose.psd.RectangleF  结构实例。 |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | 使用指定的位置和大小初始化一个新的  com.aspose.psd.RectangleF  结构实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.psd.RectangleF-) |  |
| [contains(PointF point)](#contains-com.aspose.psd.PointF-) | 确定指定的点是否包含在此  com.aspose.psd.RectangleF  结构中。 |
| [contains(RectangleF rect)](#contains-com.aspose.psd.RectangleF-) | 确定由  rect  表示的矩形区域是否完全包含在此  com.aspose.psd.RectangleF  结构中。 |
| [contains(float x, float y)](#contains-float-float-) | 确定指定的点是否包含在此  com.aspose.psd.RectangleF  结构中。 |
| [create_internalized(float x, float y, SizeF size)](#create-internalized-float-float-com.aspose.psd.SizeF-) |  |
| [divideToTransformMatrix_internalized(double[] transformMatrix)](#divideToTransformMatrix-internalized-double---) | 将当前矩形值除以以转换矩阵的垂直和水平缩放值，并返回一个带有结果值的新 [RectangleF](../../com.aspose.psd/rectanglef) 实例。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 测试  obj  是否为具有与此  com.aspose.psd.RectangleF  相同位置和大小的  com.aspose.psd.RectangleF 。 |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | 在指定的位置创建一个上左角和下右角位于指定位置的  com.aspose.psd.RectangleF  结构。 |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-) | 从指定的两个点创建一个新的  Rectangle 。 |
| [getBottom()](#getBottom--) | 获取或设置此  com.aspose.psd.RectangleF  结构的 y 坐标，该坐标是  com.aspose.psd.RectangleF.Y  与  com.aspose.psd.RectangleF.Height  的和。 |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | 获取一个新的  com.aspose.psd.RectangleF  结构实例，其  com.aspose.psd.RectangleF.X 、 com.aspose.psd.RectangleF.Y 、 com.aspose.psd.RectangleF.Width 和 com.aspose.psd.RectangleF.Height 值均为零。 |
| [getHeight()](#getHeight--) | 获取或设置此  com.aspose.psd.RectangleF  结构的高度。 |
| [getLeft()](#getLeft--) | 获取或设置此  com.aspose.psd.RectangleF  结构左边缘的 x 坐标。 |
| [getLocation()](#getLocation--) | 获取或设置此  com.aspose.psd.RectangleF  结构左上角的坐标。 |
| [getRight()](#getRight--) | 获取或设置此  com.aspose.psd.RectangleF  结构的 x 坐标，该坐标是  com.aspose.psd.RectangleF.X  与  com.aspose.psd.RectangleF.Width  的和。 |
| [getSize()](#getSize--) | 获取或设置此  com.aspose.psd.RectangleF  的大小。 |
| [getTop()](#getTop--) | 获取或设置此  com.aspose.psd.RectangleF  结构顶部边缘的 y 坐标。 |
| [getWidth()](#getWidth--) | 获取或设置此  com.aspose.psd.RectangleF  结构的宽度。 |
| [getX()](#getX--) | 获取或设置此  com.aspose.psd.RectangleF  结构左上角的 x 坐标。 |
| [getY()](#getY--) | 获取或设置此  com.aspose.psd.RectangleF  结构左上角的 y 坐标。 |
| [hashCode()](#hashCode--) | 获取此  com.aspose.psd.RectangleF  结构的哈希码。 |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.psd.RectangleF-float-float-) | 创建并返回指定的  com.aspose.psd.RectangleF  结构的膨胀副本。 |
| [inflate(SizeF size)](#inflate-com.aspose.psd.SizeF-) | 按指定的量膨胀此  com.aspose.psd.RectangleF  。 |
| [inflate(float x, float y)](#inflate-float-float-) | 按指定的量膨胀此  com.aspose.psd.RectangleF  结构。 |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | 用自身与指定的 com.aspose.psd.RectangleF 结构的交集替换此 com.aspose.psd.RectangleF 结构。 |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | 返回一个表示两个矩形交集的 com.aspose.psd.RectangleF 结构。 |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.psd.RectangleF-) | 确定此矩形是否与 rect 相交。 |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 com.aspose.psd.RectangleF 的 com.aspose.psd.RectangleF.Width 或 com.aspose.psd.RectangleF.Height 属性是否为零。 |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) |  |
| [multiplyToTransformMatrix_internalized(double[] transformMatrix)](#multiplyToTransformMatrix-internalized-double---) | 将当前矩形值相乘以转换矩阵的垂直和水平缩放值，并返回一个带有结果值的新 [RectangleF](../../com.aspose.psd/rectanglef) 实例。 |
| [normalize()](#normalize--) | 通过使宽度和高度为正、左侧小于右侧、顶部小于底部来规范化矩形。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(PointF pos)](#offset-com.aspose.psd.PointF-) | 按指定的量调整此矩形的位置。 |
| [offset(float x, float y)](#offset-float-float-) | 按指定的量调整此矩形的位置。 |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.psd.RectangleF-float-) | 实现运算符 /. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | 测试两个 com.aspose.psd.RectangleF 结构的位置和大小是否相等。 |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | 测试两个 com.aspose.psd.RectangleF 结构的位置或大小是否不同。 |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.psd.RectangleF-float-) | 实现运算符 \*。 |
| [setBottom(float value)](#setBottom-float-) | 获取或设置此  com.aspose.psd.RectangleF  结构的 y 坐标，该坐标是  com.aspose.psd.RectangleF.Y  与  com.aspose.psd.RectangleF.Height  的和。 |
| [setHeight(float value)](#setHeight-float-) | 获取或设置此  com.aspose.psd.RectangleF  结构的高度。 |
| [setLeft(float value)](#setLeft-float-) | 获取或设置此  com.aspose.psd.RectangleF  结构左边缘的 x 坐标。 |
| [setLocation(PointF value)](#setLocation-com.aspose.psd.PointF-) | 获取或设置此  com.aspose.psd.RectangleF  结构左上角的坐标。 |
| [setRight(float value)](#setRight-float-) | 获取或设置此  com.aspose.psd.RectangleF  结构的 x 坐标，该坐标是  com.aspose.psd.RectangleF.X  与  com.aspose.psd.RectangleF.Width  的和。 |
| [setSize(SizeF value)](#setSize-com.aspose.psd.SizeF-) | 获取或设置此  com.aspose.psd.RectangleF  的大小。 |
| [setTop(float value)](#setTop-float-) | 获取或设置此  com.aspose.psd.RectangleF  结构顶部边缘的 y 坐标。 |
| [setWidth(float value)](#setWidth-float-) | 获取或设置此  com.aspose.psd.RectangleF  结构的宽度。 |
| [setX(float value)](#setX-float-) | 获取或设置此  com.aspose.psd.RectangleF  结构左上角的 x 坐标。 |
| [setY(float value)](#setY-float-) | 获取或设置此  com.aspose.psd.RectangleF  结构左上角的 y 坐标。 |
| [toRectangle_internalized()](#toRectangle-internalized--) | 将 [RectangleF](../../com.aspose.psd/rectanglef) 转换为带有截断矩形值的 [Rectangle](../../com.aspose.psd/rectangle) 结构。 |
| [toString()](#toString--) | 将此 com.aspose.psd.RectangleF 的属性转换为可读的字符串。 |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.psd.Rectangle-) | 将指定的 com.aspose.psd.Rectangle 结构转换为 com.aspose.psd.RectangleF 结构。 |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | 创建可以容纳两个形成并集的矩形的最小可能的第三个矩形。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


使用指定的位置和大小初始化一个新的  com.aspose.psd.RectangleF  结构实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | float | 矩形左上角的 x 坐标。 |
| y | float | 矩形左上角的 y 坐标。 |
| 宽度 | float | 矩形的宽度。 |
| 高度 | float | 矩形的高度。 |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


使用指定的位置和大小初始化一个新的  com.aspose.psd.RectangleF  结构实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| location | [PointF](../../com.aspose.psd/pointf) | 表示矩形区域左上角的 com.aspose.psd.PointF。 |
| size | [SizeF](../../com.aspose.psd/sizef) | 表示矩形区域宽度和高度的 com.aspose.psd.SizeF。 |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(RectangleF that) {#CloneTo-com.aspose.psd.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### contains(PointF point) {#contains-com.aspose.psd.PointF-}
```
public boolean contains(PointF point)
```


确定指定的点是否包含在此  com.aspose.psd.RectangleF  结构中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 要测试的 com.aspose.psd.PointF。 |

**Returns:**
boolean - 如果 point 参数表示的点位于此 com.aspose.psd.RectangleF 结构内，则此方法返回 true；否则返回 false。
### contains(RectangleF rect) {#contains-com.aspose.psd.RectangleF-}
```
public boolean contains(RectangleF rect)
```


确定由  rect  表示的矩形区域是否完全包含在此  com.aspose.psd.RectangleF  结构中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 用于测试的  com.aspose.psd.RectangleF  。 |

**Returns:**
boolean - 如果由  rect  表示的矩形区域完全包含在此  com.aspose.psd.RectangleF  表示的矩形区域中，则此方法返回 true；否则返回 false。
### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


确定指定的点是否包含在此  com.aspose.psd.RectangleF  结构中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | float | 用于测试的点的 x 坐标。 |
| y | float | 用于测试的点的 y 坐标。 |

**Returns:**
boolean - 如果由  x  和  y  定义的点位于此  com.aspose.psd.RectangleF  结构内部，则此方法返回 true；否则返回 false。
### create_internalized(float x, float y, SizeF size) {#create-internalized-float-float-com.aspose.psd.SizeF-}
```
public static RectangleF create_internalized(float x, float y, SizeF size)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | float |  |
| y | float |  |
| size | [SizeF](../../com.aspose.psd/sizef) |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### divideToTransformMatrix_internalized(double[] transformMatrix) {#divideToTransformMatrix-internalized-double---}
```
public final RectangleF divideToTransformMatrix_internalized(double[] transformMatrix)
```


将当前矩形值除以以转换矩阵的垂直和水平缩放值，并返回一个带有结果值的新 [RectangleF](../../com.aspose.psd/rectanglef) 实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| transformMatrix | double[] | 图层变换矩阵。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with divided values.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


测试  obj  是否为具有与此  com.aspose.psd.RectangleF  相同位置和大小的  com.aspose.psd.RectangleF 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于测试的  System.Object  。 |

**Returns:**
boolean - 如果  obj  是一个  com.aspose.psd.RectangleF  且其 X、Y、Width 和 Height 属性等于此  com.aspose.psd.RectangleF  的相应属性，则此方法返回 true；否则返回 false。
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


在指定的位置创建一个上左角和下右角位于指定位置的  com.aspose.psd.RectangleF  结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| left | float | 矩形区域左上角的 x 坐标。 |
| top | float | 矩形区域左上角的 y 坐标。 |
| right | float | 矩形区域右下角的 x 坐标。 |
| bottom | float | 矩形区域右下角的 y 坐标。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The new  com.aspose.psd.RectangleF  that this method creates.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


从指定的两个点创建一个新的  Rectangle  。创建的  Rectangle  的两个顶点将等于传入的  point1  和  point2  。这些通常是相对的顶点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | 新矩形的第一个  Point  。 |
| point2 | [PointF](../../com.aspose.psd/pointf) | 新矩形的第二个  Point  。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public float getBottom()
```


获取或设置此  com.aspose.psd.RectangleF  结构的 y 坐标，该坐标是  com.aspose.psd.RectangleF.Y  与  com.aspose.psd.RectangleF.Height  的和。

**Returns:**
float - 此  com.aspose.psd.RectangleF  结构的 y 坐标，为  com.aspose.psd.RectangleF.Y  与  com.aspose.psd.RectangleF.Height  的和。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


获取一个新的  com.aspose.psd.RectangleF  结构实例，其  com.aspose.psd.RectangleF.X 、 com.aspose.psd.RectangleF.Y 、 com.aspose.psd.RectangleF.Width 和 com.aspose.psd.RectangleF.Height 值均为零。

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


获取或设置此  com.aspose.psd.RectangleF  结构的高度。

**Returns:**
float - 此  com.aspose.psd.RectangleF  结构的高度。
### getLeft() {#getLeft--}
```
public float getLeft()
```


获取或设置此  com.aspose.psd.RectangleF  结构左边缘的 x 坐标。

**Returns:**
float - 此  com.aspose.psd.RectangleF  结构左边缘的 x 坐标。
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


获取或设置此  com.aspose.psd.RectangleF  结构左上角的坐标。

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  com.aspose.psd.PointF  that represents the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getRight() {#getRight--}
```
public float getRight()
```


获取或设置此  com.aspose.psd.RectangleF  结构的 x 坐标，该坐标是  com.aspose.psd.RectangleF.X  与  com.aspose.psd.RectangleF.Width  的和。

**Returns:**
float - 此  com.aspose.psd.RectangleF  结构的 x 坐标，为  com.aspose.psd.RectangleF.X  与  com.aspose.psd.RectangleF.Width  的和。
### getSize() {#getSize--}
```
public SizeF getSize()
```


获取或设置此  com.aspose.psd.RectangleF  的大小。

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  com.aspose.psd.SizeF  that represents the width and height of this  com.aspose.psd.RectangleF  structure.
### getTop() {#getTop--}
```
public float getTop()
```


获取或设置此  com.aspose.psd.RectangleF  结构顶部边缘的 y 坐标。

**Returns:**
float - 此  com.aspose.psd.RectangleF  结构顶部边缘的 y 坐标。
### getWidth() {#getWidth--}
```
public float getWidth()
```


获取或设置此  com.aspose.psd.RectangleF  结构的宽度。

**Returns:**
float - 此  com.aspose.psd.RectangleF  结构的宽度。
### getX() {#getX--}
```
public float getX()
```


获取或设置此  com.aspose.psd.RectangleF  结构左上角的 x 坐标。

**Returns:**
float - 此  com.aspose.psd.RectangleF  结构左上角的 x 坐标。
### getY() {#getY--}
```
public float getY()
```


获取或设置此  com.aspose.psd.RectangleF  结构左上角的 y 坐标。

**Returns:**
float - 此  com.aspose.psd.RectangleF  结构左上角的 y 坐标。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取此  com.aspose.psd.RectangleF  结构的哈希码。

**Returns:**
int - 此  com.aspose.psd.RectangleF  的哈希码。
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.psd.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


创建并返回指定  com.aspose.psd.RectangleF  结构的膨胀副本。副本将按指定的量进行膨胀。原始矩形保持不变。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 要复制的  com.aspose.psd.RectangleF  。此矩形未被修改。 |
| x | float | 水平膨胀矩形副本的量。 |
| y | float | 垂直膨胀矩形副本的量。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The inflated  com.aspose.psd.RectangleF .
### inflate(SizeF size) {#inflate-com.aspose.psd.SizeF-}
```
public void inflate(SizeF size)
```


按指定的量膨胀此  com.aspose.psd.RectangleF  。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | 膨胀此矩形的量。 |

### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


按指定的量膨胀此  com.aspose.psd.RectangleF  结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | float | 水平膨胀此  com.aspose.psd.RectangleF  结构的量。 |
| y | float | 垂直膨胀此  com.aspose.psd.RectangleF  结构的量。 |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


用自身与指定的 com.aspose.psd.RectangleF 结构的交集替换此 com.aspose.psd.RectangleF 结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 要相交的矩形。 |

### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


返回一个  com.aspose.psd.RectangleF  结构，表示两个矩形的交集。如果没有交集，则返回一个空的  com.aspose.psd.RectangleF  。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | 第一个要相交的矩形。 |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | 第二个要相交的矩形。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure the size of which represents the overlapped area of the two specified rectangles.
### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.psd.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


确定此矩形是否与 rect 相交。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 要测试的矩形。 |

**Returns:**
boolean - 如果存在任何交集，此方法返回 true。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


获取一个值，指示此 com.aspose.psd.RectangleF 的 com.aspose.psd.RectangleF.Width 或 com.aspose.psd.RectangleF.Height 属性是否为零。

**Returns:**
boolean - 如果此  com.aspose.psd.RectangleF  的  com.aspose.psd.RectangleF.Width  或  com.aspose.psd.RectangleF.Height  属性的值为零，则此属性返回 true；否则返回 false。
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.psd/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.psd/rectanglef) |  |

**Returns:**
boolean
### multiplyToTransformMatrix_internalized(double[] transformMatrix) {#multiplyToTransformMatrix-internalized-double---}
```
public final RectangleF multiplyToTransformMatrix_internalized(double[] transformMatrix)
```


将当前矩形值相乘以转换矩阵的垂直和水平缩放值，并返回一个带有结果值的新 [RectangleF](../../com.aspose.psd/rectanglef) 实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| transformMatrix | double[] | 图层变换矩阵。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with multiplied values.
### normalize() {#normalize--}
```
public void normalize()
```


通过使宽度和高度为正、左侧小于右侧、顶部小于底部来规范化矩形。

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(PointF pos) {#offset-com.aspose.psd.PointF-}
```
public void offset(PointF pos)
```


按指定的量调整此矩形的位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.psd/pointf) | 偏移位置的量。 |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


按指定的量调整此矩形的位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | float | 水平偏移位置的量。 |
| y | float | 垂直偏移位置的量。 |

### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


实现运算符 /.

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 矩形。 |
| 分隔符 | float | 分隔符。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


测试两个 com.aspose.psd.RectangleF 结构的位置和大小是否相等。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | 等号运算符左侧的  com.aspose.psd.RectangleF  结构。 |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | 等号运算符右侧的  com.aspose.psd.RectangleF  结构。 |

**Returns:**
boolean - 如果两个指定的  com.aspose.psd.RectangleF  结构的  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width , 和  com.aspose.psd.RectangleF.Height  属性相等，则此运算符返回 true。
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


测试两个 com.aspose.psd.RectangleF 结构的位置或大小是否不同。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | 位于不等运算符左侧的  com.aspose.psd.RectangleF  结构。 |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | 位于不等运算符右侧的  com.aspose.psd.RectangleF  结构。 |

**Returns:**
boolean - 如果两个  com.aspose.psd.RectangleF  结构的  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width , 或  com.aspose.psd.RectangleF.Height  属性中有任意不相等，则此运算符返回 true；否则返回 false。
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


实现运算符 \*。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 矩形。 |
| 乘数 | float | 乘数。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


获取或设置此  com.aspose.psd.RectangleF  结构的 y 坐标，该坐标是  com.aspose.psd.RectangleF.Y  与  com.aspose.psd.RectangleF.Height  的和。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


获取或设置此  com.aspose.psd.RectangleF  结构的高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


获取或设置此  com.aspose.psd.RectangleF  结构左边缘的 x 坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setLocation(PointF value) {#setLocation-com.aspose.psd.PointF-}
```
public void setLocation(PointF value)
```


获取或设置此  com.aspose.psd.RectangleF  结构左上角的坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


获取或设置此  com.aspose.psd.RectangleF  结构的 x 坐标，该坐标是  com.aspose.psd.RectangleF.X  与  com.aspose.psd.RectangleF.Width  的和。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setSize(SizeF value) {#setSize-com.aspose.psd.SizeF-}
```
public void setSize(SizeF value)
```


获取或设置此  com.aspose.psd.RectangleF  的大小。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) |  |

### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


获取或设置此  com.aspose.psd.RectangleF  结构顶部边缘的 y 坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


获取或设置此  com.aspose.psd.RectangleF  结构的宽度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setX(float value) {#setX-float-}
```
public void setX(float value)
```


获取或设置此  com.aspose.psd.RectangleF  结构左上角的 x 坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


获取或设置此  com.aspose.psd.RectangleF  结构左上角的 y 坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### toRectangle_internalized() {#toRectangle-internalized--}
```
public final Rectangle toRectangle_internalized()
```


将 [RectangleF](../../com.aspose.psd/rectanglef) 转换为带有截断矩形值的 [Rectangle](../../com.aspose.psd/rectangle) 结构。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a [Rectangle](../../com.aspose.psd/rectangle) structure.
### toString() {#toString--}
```
public String toString()
```


将此 com.aspose.psd.RectangleF 的属性转换为可读的字符串。

**Returns:**
java.lang.String - 包含此  com.aspose.psd.RectangleF  结构的位置、宽度和高度的字符串。
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.psd.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


将指定的 com.aspose.psd.Rectangle 结构转换为 com.aspose.psd.RectangleF 结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 要转换的  com.aspose.psd.Rectangle  结构。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The  com.aspose.psd.RectangleF  structure that is converted from the specified  com.aspose.psd.Rectangle  structure.
### union(RectangleF a, RectangleF b) {#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


创建可以容纳两个形成并集的矩形的最小可能的第三个矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | 第一个用于合并的矩形。 |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | 第二个用于合并的矩形。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure that contains both of the two rectangles that form the union.
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

