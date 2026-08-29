---
title: "矩形"
second_title: "Aspose.PSD 的 Java API 参考"
description: "存储一组四个整数，表示矩形的位置和大小。"
type: docs
weight: 88
url: /zh/java/com.aspose.psd/rectangle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

存储一组四个整数，表示矩形的位置和大小。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | 使用指定的位置和大小初始化  com.aspose.psd.Rectangle  结构的新实例。 |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-) | 使用指定的位置和大小初始化  com.aspose.psd.Rectangle  结构的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.psd.Rectangle-) |  |
| [ceiling(RectangleF value)](#ceiling-com.aspose.psd.RectangleF-) | 通过将  com.aspose.psd.RectangleF  的值向上取整为下一个整数，将指定的  com.aspose.psd.RectangleF  结构转换为  com.aspose.psd.Rectangle  结构。 |
| [contains(Point point)](#contains-com.aspose.psd.Point-) | 确定指定的点是否包含在此  com.aspose.psd.Rectangle  结构中。 |
| [contains(Rectangle rect)](#contains-com.aspose.psd.Rectangle-) | 确定由  rect  表示的矩形区域是否完全包含在此  com.aspose.psd.Rectangle  结构中。 |
| [contains(int x, int y)](#contains-int-int-) | 确定指定的点是否包含在此  com.aspose.psd.Rectangle  结构中。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 测试  obj  是否为具有与此  com.aspose.psd.Rectangle  结构相同位置和大小的  com.aspose.psd.Rectangle  结构。 |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | 使用指定的边缘位置创建  com.aspose.psd.Rectangle  结构。 |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-) | 从指定的两个点创建一个新的  Rectangle 。 |
| [getBottom()](#getBottom--) | 获取或设置此  com.aspose.psd.Rectangle  结构的 y 坐标，该坐标为  com.aspose.psd.Rectangle.Y  与  com.aspose.psd.Rectangle.Height  属性值之和。 |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | 获取一个新的  com.aspose.psd.Rectangle  结构实例，其  com.aspose.psd.Rectangle.X、com.aspose.psd.Rectangle.Y、com.aspose.psd.Rectangle.Width 和 com.aspose.psd.Rectangle.Height 值均为零。 |
| [getHeight()](#getHeight--) | 获取或设置此  com.aspose.psd.Rectangle  结构的高度。 |
| [getLeft()](#getLeft--) | 获取或设置此  com.aspose.psd.Rectangle  结构左边缘的 x 坐标。 |
| [getLocation()](#getLocation--) | 获取或设置此  com.aspose.psd.Rectangle  结构左上角的坐标。 |
| [getRight()](#getRight--) | 获取或设置此  com.aspose.psd.Rectangle  结构的 x 坐标，该坐标是 com.aspose.psd.Rectangle.X 和 com.aspose.psd.Rectangle.Width 属性值之和。 |
| [getSize()](#getSize--) | 获取或设置此  com.aspose.psd.Rectangle  的大小。 |
| [getTop()](#getTop--) | 获取或设置此  com.aspose.psd.Rectangle  结构顶部边缘的 y 坐标。 |
| [getWidth()](#getWidth--) | 获取此  com.aspose.psd.Rectangle  结构的宽度。 |
| [getX()](#getX--) | 获取或设置此  com.aspose.psd.Rectangle  结构左上角的 x 坐标。 |
| [getY()](#getY--) | 获取或设置此  com.aspose.psd.Rectangle  结构左上角的 y 坐标。 |
| [hashCode()](#hashCode--) | 返回此  com.aspose.psd.Rectangle  结构的哈希码。 |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.psd.Rectangle-int-int-) | 创建并返回指定  com.aspose.psd.Rectangle  结构的膨胀副本。 |
| [inflate(Size size)](#inflate-com.aspose.psd.Size-) | 按指定量膨胀此  com.aspose.psd.Rectangle。 |
| [inflate(int width, int height)](#inflate-int-int-) | 按指定量膨胀此  com.aspose.psd.Rectangle。 |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | 用自身与指定的  com.aspose.psd.Rectangle  的交集替换此  com.aspose.psd.Rectangle。 |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | 返回第三个  com.aspose.psd.Rectangle  结构，表示另外两个  com.aspose.psd.Rectangle  结构的交集。 |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.psd.Rectangle-) | 确定此矩形是否与 rect 相交。 |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此  com.aspose.psd.Rectangle  的所有数值属性是否为零。 |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) |  |
| [isVisible_internalized()](#isVisible-internalized--) | 获取一个值，指示此  Rectangle  是否至少部分可见 |
| [normalize()](#normalize--) | 通过使宽度和高度为正、左侧小于右侧、顶部小于底部来规范化矩形。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point pos)](#offset-com.aspose.psd.Point-) | 按指定的量调整此矩形的位置。 |
| [offset(int x, int y)](#offset-int-int-) | 按指定的量调整此矩形的位置。 |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | 测试两个  com.aspose.psd.Rectangle  结构是否具有相同的位置和大小。 |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | 测试两个  com.aspose.psd.Rectangle  结构在位置或大小上是否不同。 |
| [round(RectangleF value)](#round-com.aspose.psd.RectangleF-) | 将指定的  com.aspose.psd.RectangleF  转换为  com.aspose.psd.Rectangle ，通过将  com.aspose.psd.RectangleF  的值四舍五入为最接近的整数值。 |
| [setBottom(int value)](#setBottom-int-) | 获取或设置此  com.aspose.psd.Rectangle  结构的 y 坐标，该坐标为  com.aspose.psd.Rectangle.Y  与  com.aspose.psd.Rectangle.Height  属性值之和。 |
| [setHeight(int value)](#setHeight-int-) | 获取或设置此  com.aspose.psd.Rectangle  结构的高度。 |
| [setLeft(int value)](#setLeft-int-) | 获取或设置此  com.aspose.psd.Rectangle  结构左边缘的 x 坐标。 |
| [setLocation(Point value)](#setLocation-com.aspose.psd.Point-) | 获取或设置此  com.aspose.psd.Rectangle  结构左上角的坐标。 |
| [setRight(int value)](#setRight-int-) | 获取或设置此  com.aspose.psd.Rectangle  结构的 x 坐标，该坐标是 com.aspose.psd.Rectangle.X 和 com.aspose.psd.Rectangle.Width 属性值之和。 |
| [setSize(Size value)](#setSize-com.aspose.psd.Size-) | 获取或设置此  com.aspose.psd.Rectangle  的大小。 |
| [setTop(int value)](#setTop-int-) | 获取或设置此  com.aspose.psd.Rectangle  结构顶部边缘的 y 坐标。 |
| [setWidth(int value)](#setWidth-int-) | 设置此  com.aspose.psd.Rectangle  结构的宽度。 |
| [setX(int value)](#setX-int-) | 获取或设置此  com.aspose.psd.Rectangle  结构左上角的 x 坐标。 |
| [setY(int value)](#setY-int-) | 获取或设置此  com.aspose.psd.Rectangle  结构左上角的 y 坐标。 |
| [toString()](#toString--) | 将此  com.aspose.psd.Rectangle  的属性转换为可读的字符串。 |
| [truncate(RectangleF value)](#truncate-com.aspose.psd.RectangleF-) | 将指定的  com.aspose.psd.RectangleF  转换为  com.aspose.psd.Rectangle ，通过截断  com.aspose.psd.RectangleF  的值。 |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | 获取一个  com.aspose.psd.Rectangle  结构，该结构包含两个  com.aspose.psd.Rectangle  结构的并集。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


使用指定的位置和大小初始化  com.aspose.psd.Rectangle  结构的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | int | 矩形左上角的 x 坐标。 |
| y | int | 矩形左上角的 y 坐标。 |
| 宽度 | int | 矩形的宽度。 |
| 高度 | int | 矩形的高度。 |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public Rectangle(Point location, Size size)
```


使用指定的位置和大小初始化  com.aspose.psd.Rectangle  结构的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | 一个  com.aspose.psd.Point ，表示矩形区域的左上角。 |
| size | [Size](../../com.aspose.psd/size) | 一个  com.aspose.psd.Size ，表示矩形区域的宽度和高度。 |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Rectangle that) {#CloneTo-com.aspose.psd.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.psd/rectangle) |  |

### ceiling(RectangleF value) {#ceiling-com.aspose.psd.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


通过将  com.aspose.psd.RectangleF  的值向上取整为下一个整数，将指定的  com.aspose.psd.RectangleF  结构转换为  com.aspose.psd.Rectangle  结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | 要转换的  com.aspose.psd.RectangleF  结构。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a  com.aspose.psd.Rectangle .
### contains(Point point) {#contains-com.aspose.psd.Point-}
```
public boolean contains(Point point)
```


确定指定的点是否包含在此  com.aspose.psd.Rectangle  结构中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 用于测试的  com.aspose.psd.Point  。 |

**Returns:**
boolean - 如果由  point  表示的点位于此  com.aspose.psd.Rectangle  结构内部，则此方法返回 true；否则返回 false。
### contains(Rectangle rect) {#contains-com.aspose.psd.Rectangle-}
```
public boolean contains(Rectangle rect)
```


确定由  rect  表示的矩形区域是否完全包含在此  com.aspose.psd.Rectangle  结构中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 用于测试的  com.aspose.psd.Rectangle  。 |

**Returns:**
boolean - 如果由  rect  表示的矩形区域完全位于此  com.aspose.psd.Rectangle  结构内部，则此方法返回 true；否则返回 false。
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


确定指定的点是否包含在此  com.aspose.psd.Rectangle  结构中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | int | 用于测试的点的 x 坐标。 |
| y | int | 用于测试的点的 y 坐标。 |

**Returns:**
boolean - 如果由  x  和  y  定义的点位于此  com.aspose.psd.Rectangle  结构内部，则此方法返回 true；否则返回 false。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


测试  obj  是否为具有与此  com.aspose.psd.Rectangle  结构相同位置和大小的  com.aspose.psd.Rectangle  结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于测试的  System.Object  。 |

**Returns:**
boolean - 如果  obj  是一个  com.aspose.psd.Rectangle  结构，并且其  com.aspose.psd.Rectangle.X 、 com.aspose.psd.Rectangle.Y 、 com.aspose.psd.Rectangle.Width 和 com.aspose.psd.Rectangle.Height 属性等于此  com.aspose.psd.Rectangle  结构的相应属性，则此方法返回 true；否则返回 false。
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


使用指定的边缘位置创建  com.aspose.psd.Rectangle  结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| left | int | 此  com.aspose.psd.Rectangle  结构左上角的 x 坐标。 |
| top | int | 此  com.aspose.psd.Rectangle  结构左上角的 y 坐标。 |
| right | int | 此  com.aspose.psd.Rectangle  结构右下角的 x 坐标。 |
| bottom | int | 此  com.aspose.psd.Rectangle  结构右下角的 y 坐标。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The new  com.aspose.psd.Rectangle  that this method creates.
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


根据指定的两个点创建一个新的  Rectangle。创建的  Rectangle 的两个顶点将等于传入的  point1  和  point2 。这些通常是相对的顶点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | 新矩形的第一个  Point  。 |
| point2 | [Point](../../com.aspose.psd/point) | 新矩形的第二个  Point  。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public int getBottom()
```


获取或设置此  com.aspose.psd.Rectangle  结构的 y 坐标，该坐标为  com.aspose.psd.Rectangle.Y  与  com.aspose.psd.Rectangle.Height  属性值之和。

**Returns:**
int - 此  com.aspose.psd.Rectangle  的 y 坐标，为  com.aspose.psd.Rectangle.Y  与  com.aspose.psd.Rectangle.Height  的和。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


获取一个新的  com.aspose.psd.Rectangle  结构实例，其  com.aspose.psd.Rectangle.X、com.aspose.psd.Rectangle.Y、com.aspose.psd.Rectangle.Width 和 com.aspose.psd.Rectangle.Height 值均为零。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取或设置此  com.aspose.psd.Rectangle  结构的高度。

**Returns:**
int - 此  com.aspose.psd.Rectangle  结构的高度。
### getLeft() {#getLeft--}
```
public int getLeft()
```


获取或设置此  com.aspose.psd.Rectangle  结构左边缘的 x 坐标。

**Returns:**
int - 此  com.aspose.psd.Rectangle  结构左边缘的 x 坐标。
### getLocation() {#getLocation--}
```
public Point getLocation()
```


获取或设置此  com.aspose.psd.Rectangle  结构左上角的坐标。

**Returns:**
[Point](../../com.aspose.psd/point) - A  com.aspose.psd.Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getRight() {#getRight--}
```
public int getRight()
```


获取或设置此  com.aspose.psd.Rectangle  结构的 x 坐标，该坐标是 com.aspose.psd.Rectangle.X 和 com.aspose.psd.Rectangle.Width 属性值之和。

**Returns:**
int - 此  com.aspose.psd.Rectangle  的 x 坐标，为  com.aspose.psd.Rectangle.X  与  com.aspose.psd.Rectangle.Width  的和。
### getSize() {#getSize--}
```
public Size getSize()
```


获取或设置此  com.aspose.psd.Rectangle  的大小。

**Returns:**
[Size](../../com.aspose.psd/size) - A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure.
### getTop() {#getTop--}
```
public int getTop()
```


获取或设置此  com.aspose.psd.Rectangle  结构顶部边缘的 y 坐标。

**Returns:**
int - 此  com.aspose.psd.Rectangle  结构顶部边缘的 y 坐标。
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取此  com.aspose.psd.Rectangle  结构的宽度。

**Returns:**
int - 此  com.aspose.psd.Rectangle  结构的宽度。
### getX() {#getX--}
```
public int getX()
```


获取或设置此  com.aspose.psd.Rectangle  结构左上角的 x 坐标。

**Returns:**
int - 此  com.aspose.psd.Rectangle  结构左上角的 x 坐标。
### getY() {#getY--}
```
public int getY()
```


获取或设置此  com.aspose.psd.Rectangle  结构左上角的 y 坐标。

**Returns:**
int - 此  com.aspose.psd.Rectangle  结构左上角的 y 坐标。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此  com.aspose.psd.Rectangle  结构的哈希码。

**Returns:**
int - 表示此矩形哈希码的整数。
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


创建并返回指定的  com.aspose.psd.Rectangle  结构的膨胀副本。该副本按指定的量进行膨胀。原始的  com.aspose.psd.Rectangle  结构保持不变。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 用于起始的  com.aspose.psd.Rectangle。此矩形未被修改。 |
| x | int | 水平膨胀此  com.aspose.psd.Rectangle 的量。 |
| y | int | 垂直膨胀此  com.aspose.psd.Rectangle 的量。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The inflated  com.aspose.psd.Rectangle .
### inflate(Size size) {#inflate-com.aspose.psd.Size-}
```
public void inflate(Size size)
```


按指定量膨胀此  com.aspose.psd.Rectangle。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | 膨胀此矩形的量。 |

### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


按指定量膨胀此  com.aspose.psd.Rectangle。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 宽度 | int | 水平膨胀此  com.aspose.psd.Rectangle 的量。 |
| 高度 | int | 垂直膨胀此  com.aspose.psd.Rectangle 的量。 |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


用自身与指定的  com.aspose.psd.Rectangle  的交集替换此  com.aspose.psd.Rectangle。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 用于相交的  com.aspose.psd.Rectangle  。 |

### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


返回第三个  com.aspose.psd.Rectangle  结构，表示两个其他  com.aspose.psd.Rectangle  结构的交集。如果没有交集，则返回一个空的  com.aspose.psd.Rectangle  。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | 第一个要相交的矩形。 |
| b | [Rectangle](../../com.aspose.psd/rectangle) | 第二个要相交的矩形。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  that represents the intersection of  a  and  b .
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.psd.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


确定此矩形是否与 rect 相交。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 要测试的矩形。 |

**Returns:**
boolean - 如果存在任何交集，此方法返回 true，否则返回 false。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


获取一个值，指示此  com.aspose.psd.Rectangle  的所有数值属性是否为零。

**Returns:**
boolean - 如果此  com.aspose.psd.Rectangle  的  com.aspose.psd.Rectangle.Width 、 com.aspose.psd.Rectangle.Height 、 com.aspose.psd.Rectangle.X 和 com.aspose.psd.Rectangle.Y 属性全部为零，则返回 true；否则返回 false。
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.psd/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
boolean
### isVisible_internalized() {#isVisible-internalized--}
```
public boolean isVisible_internalized()
```


获取一个值，指示此  Rectangle  是否至少部分可见

**Returns:**
boolean - 如果此  Rectangle  至少部分可见，则为 true；否则为 false。
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




### offset(Point pos) {#offset-com.aspose.psd.Point-}
```
public void offset(Point pos)
```


按指定的量调整此矩形的位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pos | [Point](../../com.aspose.psd/point) | 位置的偏移量。 |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


按指定的量调整此矩形的位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | int | 水平偏移。 |
| y | int | 垂直偏移。 |

### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


测试两个  com.aspose.psd.Rectangle  结构是否具有相同的位置和大小。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | 等号运算符左侧的  com.aspose.psd.Rectangle  结构。 |
| right | [Rectangle](../../com.aspose.psd/rectangle) | 等号运算符右侧的  com.aspose.psd.Rectangle  结构。 |

**Returns:**
boolean - 如果两个  com.aspose.psd.Rectangle  结构的  com.aspose.psd.Rectangle.X 、 com.aspose.psd.Rectangle.Y 、 com.aspose.psd.Rectangle.Width 和 com.aspose.psd.Rectangle.Height 属性相等，则此运算符返回 true。
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


测试两个  com.aspose.psd.Rectangle  结构在位置或大小上是否不同。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | 不等号运算符左侧的  com.aspose.psd.Rectangle  结构。 |
| right | [Rectangle](../../com.aspose.psd/rectangle) | 不等号运算符右侧的  com.aspose.psd.Rectangle  结构。 |

**Returns:**
boolean - 如果两个  com.aspose.psd.Rectangle  结构的任一  com.aspose.psd.Rectangle.X 、 com.aspose.psd.Rectangle.Y 、 com.aspose.psd.Rectangle.Width 或 com.aspose.psd.Rectangle.Height 属性不相等，则此运算符返回 true；否则返回 false。
### round(RectangleF value) {#round-com.aspose.psd.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


将指定的  com.aspose.psd.RectangleF  转换为  com.aspose.psd.Rectangle ，通过将  com.aspose.psd.RectangleF  的值四舍五入为最接近的整数值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | 要转换的  com.aspose.psd.RectangleF  。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


获取或设置此  com.aspose.psd.Rectangle  结构的 y 坐标，该坐标为  com.aspose.psd.Rectangle.Y  与  com.aspose.psd.Rectangle.Height  属性值之和。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 此  com.aspose.psd.Rectangle  的 y 坐标，为  com.aspose.psd.Rectangle.Y  与 com.aspose.psd.Rectangle.Height 之和。 |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


获取或设置此  com.aspose.psd.Rectangle  结构的高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 此  com.aspose.psd.Rectangle  结构的高度。 |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


获取或设置此  com.aspose.psd.Rectangle  结构左边缘的 x 坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 此  com.aspose.psd.Rectangle  结构左边缘的 x 坐标。 |

### setLocation(Point value) {#setLocation-com.aspose.psd.Point-}
```
public void setLocation(Point value)
```


获取或设置此  com.aspose.psd.Rectangle  结构左上角的坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) | 表示此  com.aspose.psd.Rectangle  结构左上角的  Point  。 |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


获取或设置此  com.aspose.psd.Rectangle  结构的 x 坐标，该坐标是 com.aspose.psd.Rectangle.X 和 com.aspose.psd.Rectangle.Width 属性值之和。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 此  com.aspose.psd.Rectangle  的 x 坐标，为  com.aspose.psd.Rectangle.X  与 com.aspose.psd.Rectangle.Width 之和。 |

### setSize(Size value) {#setSize-com.aspose.psd.Size-}
```
public void setSize(Size value)
```


获取或设置此  com.aspose.psd.Rectangle  的大小。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) | 表示此  com.aspose.psd.Rectangle  结构宽度和高度的  com.aspose.psd.Size  。 |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


获取或设置此  com.aspose.psd.Rectangle  结构顶部边缘的 y 坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 此  com.aspose.psd.Rectangle  结构顶部边缘的 y 坐标。 |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


设置此  com.aspose.psd.Rectangle  结构的宽度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 此  com.aspose.psd.Rectangle  结构的宽度。 |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


获取或设置此  com.aspose.psd.Rectangle  结构左上角的 x 坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 此  com.aspose.psd.Rectangle  结构左上角的 x 坐标。 |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


获取或设置此  com.aspose.psd.Rectangle  结构左上角的 y 坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 此  com.aspose.psd.Rectangle  结构左上角的 y 坐标。 |

### toString() {#toString--}
```
public String toString()
```


将此  com.aspose.psd.Rectangle  的属性转换为可读的字符串。

**Returns:**
java.lang.String - 包含此  com.aspose.psd.Rectangle  结构的位置、宽度和高度的字符串。
### truncate(RectangleF value) {#truncate-com.aspose.psd.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


将指定的  com.aspose.psd.RectangleF  转换为  com.aspose.psd.Rectangle ，通过截断  com.aspose.psd.RectangleF  的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | 要转换的  com.aspose.psd.RectangleF  。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### union(Rectangle a, Rectangle b) {#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


获取一个  com.aspose.psd.Rectangle  结构，该结构包含两个  com.aspose.psd.Rectangle  结构的并集。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | 第一个用于合并的矩形。 |
| b | [Rectangle](../../com.aspose.psd/rectangle) | 第二个用于合并的矩形。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  structure that bounds the union of the two  com.aspose.psd.Rectangle  structures.
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

