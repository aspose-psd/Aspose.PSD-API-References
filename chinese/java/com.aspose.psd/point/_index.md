---
title: "Point"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示整数 x 和 y 坐标的有序对，用于定义二维平面中的点。"
type: docs
weight: 82
url: /zh/java/com.aspose.psd/point/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

表示整数 x 和 y 坐标的有序对，用于定义二维平面中的点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | 使用指定的坐标初始化 Aspose.Imaging.Point 结构的新实例。 |
| [Point(Size size)](#Point-com.aspose.psd.Size-) | 从 Aspose.Imaging.Size 结构初始化 Aspose.Imaging.Point 结构的新实例。 |
| [Point(int dw)](#Point-int-) | 使用整数值指定的坐标初始化 Aspose.Imaging.Point 结构的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [PointFormat_internalized](#PointFormat-internalized) | 表示点格式。 |
## Methods

| Method | 描述 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Point that)](#CloneTo-com.aspose.psd.Point-) |  |
| [add(Point point, Size size)](#add-com.aspose.psd.Point-com.aspose.psd.Size-) | 将指定的 Aspose.Imaging.Size 添加到指定的 Aspose.Imaging.Point。 |
| [ceiling(PointF point)](#ceiling-com.aspose.psd.PointF-) | 通过将 Aspose.Imaging.PointF 的值向上取整为更高的整数，将指定的 Aspose.Imaging.PointF 转换为 Aspose.Imaging.Point。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定此 Aspose.Imaging.Point 是否包含与指定的 System.Object 相同的坐标。 |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | 获取 Aspose.Imaging.Point 结构的新实例，其 Aspose.Imaging.Point.X 和 Aspose.Imaging.Point.Y 值均设为零。 |
| [getX()](#getX--) | 获取或设置此 Aspose.Imaging.Point 的 X 坐标。 |
| [getY()](#getY--) | 获取或设置此 Aspose.Imaging.Point 的 Y 坐标。 |
| [hashCode()](#hashCode--) | 返回此 Aspose.Imaging.Point 的哈希码。 |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 Aspose.Imaging.Point 是否为空。 |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point point)](#offset-com.aspose.psd.Point-) | 按指定的 Aspose.Imaging.Point 平移此 Aspose.Imaging.Point。 |
| [offset(int dx, int dy)](#offset-int-int-) | 按指定的量平移此 Aspose.Imaging.Point。 |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-) | 按给定的 Aspose.Imaging.Size 平移 Aspose.Imaging.Point。 |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-) | 比较两个 Aspose.Imaging.Point 对象。 |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-) | 比较两个 Aspose.Imaging.Point 对象。 |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-) | 按给定 Aspose.Imaging.Size 的相反数平移 Aspose.Imaging.Point。 |
| [round(PointF point)](#round-com.aspose.psd.PointF-) | 通过将 Aspose.Imaging.Point 的值四舍五入到最近的整数，将指定的 Aspose.Imaging.PointF 转换为 Aspose.Imaging.Point 对象。 |
| [setX(int value)](#setX-int-) | 获取或设置此 Aspose.Imaging.Point 的 X 坐标。 |
| [setY(int value)](#setY-int-) | 获取或设置此 Aspose.Imaging.Point 的 Y 坐标。 |
| [subtract(Point point, Size size)](#subtract-com.aspose.psd.Point-com.aspose.psd.Size-) | 返回从指定的 Aspose.Imaging.Point 中减去指定的 Aspose.Imaging.Size 的结果。 |
| [toString()](#toString--) | 将此 Aspose.Imaging.Point 转换为可读的字符串。 |
| [to_PointF(Point point)](#to-PointF-com.aspose.psd.Point-) | 将指定的 Point 结构转换为 PointF 结构。 |
| [to_Size(Point point)](#to-Size-com.aspose.psd.Point-) | 将指定的 Aspose.Imaging.Point 结构转换为 Aspose.Imaging.Size 结构。 |
| [truncate(PointF point)](#truncate-com.aspose.psd.PointF-) | 通过截断 Aspose.Imaging.Point 的值，将指定的 Aspose.Imaging.PointF 转换为 Aspose.Imaging.Point。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


使用指定的坐标初始化 Aspose.Imaging.Point 结构的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | int | 点的水平位置。 |
| y | int | 点的垂直位置。 |

### Point(Size size) {#Point-com.aspose.psd.Size-}
```
public Point(Size size)
```


从 Aspose.Imaging.Size 结构初始化 Aspose.Imaging.Point 结构的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | 包含新的点坐标。 |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


使用整数值指定的坐标初始化 Aspose.Imaging.Point 结构的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dw | int | 一个指定新点坐标的 32 位整数。 |

### PointFormat_internalized {#PointFormat-internalized}
```
public static final String PointFormat_internalized
```


表示点格式。

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.psd/point)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Point that) {#CloneTo-com.aspose.psd.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| that | [Point](../../com.aspose.psd/point) |  |

### add(Point point, Size size) {#add-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point add(Point point, Size size)
```


将指定的 Aspose.Imaging.Size 添加到指定的 Aspose.Imaging.Point。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 要添加到的 Aspose.Imaging.Point。 |
| size | [Size](../../com.aspose.psd/size) | 要添加到该点的 Aspose.Imaging.Size。 |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the addition operation.
### ceiling(PointF point) {#ceiling-com.aspose.psd.PointF-}
```
public static Point ceiling(PointF point)
```


通过将 Aspose.Imaging.PointF 的值向上取整为更高的整数，将指定的 Aspose.Imaging.PointF 转换为 Aspose.Imaging.Point。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 要转换的 Aspose.Imaging.PointF。 |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定此 Aspose.Imaging.Point 是否包含与指定的 System.Object 相同的坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于测试的  System.Object  。 |

**Returns:**
布尔值 - 如果 obj 是 Aspose.Imaging.Point 并且具有与此 Aspose.Imaging.Point 相同的坐标，则为 True。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


获取 Aspose.Imaging.Point 结构的新实例，其 Aspose.Imaging.Point.X 和 Aspose.Imaging.Point.Y 值均设为零。

**Returns:**
[Point](../../com.aspose.psd/point)
### getX() {#getX--}
```
public int getX()
```


获取或设置此 Aspose.Imaging.Point 的 X 坐标。

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


获取或设置此 Aspose.Imaging.Point 的 Y 坐标。

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此 Aspose.Imaging.Point 的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和诸如哈希表之类的数据结构。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


获取一个值，指示此 Aspose.Imaging.Point 是否为空。

**Returns:**
布尔值 - 如果 Aspose.Imaging.Point.X 和 Aspose.Imaging.Point.Y 均为 0，则为 True；否则为 false。
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.psd/point) |  |
| obj2 | [Point](../../com.aspose.psd/point) |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(Point point) {#offset-com.aspose.psd.Point-}
```
public void offset(Point point)
```


按指定的 Aspose.Imaging.Point 平移此 Aspose.Imaging.Point。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 用于偏移此 Aspose.Imaging.Point 的 Aspose.Imaging.Point。 |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


按指定的量平移此 Aspose.Imaging.Point。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dx | int | 用于偏移 x 坐标的量。 |
| dy | int | 用于偏移 y 坐标的量。 |

### op_Addition(Point point, Size size) {#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Addition(Point point, Size size)
```


按给定的 Aspose.Imaging.Size 平移 Aspose.Imaging.Point。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 要平移的 Aspose.Imaging.Point。 |
| size | [Size](../../com.aspose.psd/size) | 一个 Aspose.Imaging.Size，用于指定要添加到 point 坐标的数字对。 |

**Returns:**
[Point](../../com.aspose.psd/point) - The translated  Aspose.Imaging.Point .
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


比较两个 Aspose.Imaging.Point 对象。结果指定这两个 Aspose.Imaging.Point 对象的 Aspose.Imaging.Point.X 和 Aspose.Imaging.Point.Y 属性的值是否相等。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | 第一个用于比较的 Aspose.Imaging.Point。 |
| point2 | [Point](../../com.aspose.psd/point) | 第二个用于比较的 Aspose.Imaging.Point。 |

**Returns:**
boolean - 如果 point1 和 point2 的 Aspose.Imaging.Point.X 与 Aspose.Imaging.Point.Y 值相等，则为 True；否则为 false。
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


比较两个 Aspose.Imaging.Point 对象。结果指定这两个 Aspose.Imaging.Point 对象的 Aspose.Imaging.Point.X 或 Aspose.Imaging.Point.Y 属性的值是否不相等。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | 第一个用于比较的 Aspose.Imaging.Point。 |
| point2 | [Point](../../com.aspose.psd/point) | 第二个用于比较的 Aspose.Imaging.Point。 |

**Returns:**
boolean - 如果 point1 和 point2 的 Aspose.Imaging.Point.X 属性或 Aspose.Imaging.Point.Y 属性的值任一不同，则为 True；否则为 false。
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


按给定 Aspose.Imaging.Size 的相反数平移 Aspose.Imaging.Point。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 要平移的 Aspose.Imaging.Point。 |
| size | [Size](../../com.aspose.psd/size) | 一个 Aspose.Imaging.Size，用于指定要从 point 坐标中减去的数字对。 |

**Returns:**
[Point](../../com.aspose.psd/point) - A  Aspose.Imaging.Point  structure that is translated by the negative of a given  Aspose.Imaging.Size  structure.
### round(PointF point) {#round-com.aspose.psd.PointF-}
```
public static Point round(PointF point)
```


通过将 Aspose.Imaging.Point 的值四舍五入到最近的整数，将指定的 Aspose.Imaging.PointF 转换为 Aspose.Imaging.Point 对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 要转换的 Aspose.Imaging.PointF。 |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


获取或设置此 Aspose.Imaging.Point 的 X 坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


获取或设置此 Aspose.Imaging.Point 的 Y 坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### subtract(Point point, Size size) {#subtract-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point subtract(Point point, Size size)
```


返回从指定的 Aspose.Imaging.Point 中减去指定的 Aspose.Imaging.Size 的结果。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 要被减去的 Aspose.Imaging.Point。 |
| size | [Size](../../com.aspose.psd/size) | 用于从 point 减去的 Aspose.Imaging.Size。 |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


将此 Aspose.Imaging.Point 转换为可读的字符串。

**Returns:**
java.lang.String - 一个  System.String  表示此实例。
### to_PointF(Point point) {#to-PointF-com.aspose.psd.Point-}
```
public static PointF to_PointF(Point point)
```


将指定的 Point 结构转换为 PointF 结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 要转换的 Point。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  PointF  that results from the conversion.
### to_Size(Point point) {#to-Size-com.aspose.psd.Point-}
```
public static Size to_Size(Point point)
```


将指定的 Aspose.Imaging.Point 结构转换为 Aspose.Imaging.Size 结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 要转换的 Aspose.Imaging.Point。 |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that results from the conversion.
### truncate(PointF point) {#truncate-com.aspose.psd.PointF-}
```
public static Point truncate(PointF point)
```


通过截断 Aspose.Imaging.Point 的值，将指定的 Aspose.Imaging.PointF 转换为 Aspose.Imaging.Point。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 要转换的 Aspose.Imaging.PointF。 |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
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

