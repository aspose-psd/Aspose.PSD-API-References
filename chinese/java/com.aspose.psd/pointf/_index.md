---
title: "PointF"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示一对有序的浮点数 x 和 y 坐标，用于定义二维平面中的一个点。"
type: docs
weight: 83
url: /zh/java/com.aspose.psd/pointf/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

表示一对有序的浮点数 x 和 y 坐标，用于定义二维平面中的一个点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | 使用指定坐标初始化 com.aspose.psd.PointF 结构的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(PointF that)](#CloneTo-com.aspose.psd.PointF-) |  |
| [add(PointF point, Size size)](#add-com.aspose.psd.PointF-com.aspose.psd.Size-) | 按指定的 com.aspose.psd.Size 平移给定的 com.aspose.psd.PointF。 |
| [add(PointF point, SizeF size)](#add-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | 按指定的 com.aspose.psd.SizeF 平移给定的 com.aspose.psd.PointF。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定此 com.aspose.psd.PointF 是否包含与指定的 System.Object 相同的坐标。 |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | 获取一个新的 com.aspose.psd.PointF 结构实例，其 com.aspose.psd.PointF.X 和 com.aspose.psd.PointF.Y 值均为零。 |
| [getX()](#getX--) | 获取或设置此 com.aspose.psd.PointF 的 X 坐标。 |
| [getY()](#getY--) | 获取或设置此 com.aspose.psd.PointF 的 Y 坐标。 |
| [hashCode()](#hashCode--) | 返回此 com.aspose.psd.PointF 结构的哈希码。 |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 com.aspose.psd.PointF 是否为空。 |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.psd.PointF-com.aspose.psd.PointF-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.psd.PointF-com.aspose.psd.Size-) | 按给定的 com.aspose.psd.Size 平移 com.aspose.psd.PointF。 |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | 按指定的 com.aspose.psd.SizeF 平移 com.aspose.psd.PointF。 |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.psd.PointF-com.aspose.psd.PointF-) | 比较两个 com.aspose.psd.PointF 结构。 |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.psd.PointF-com.aspose.psd.PointF-) | 确定指定点的坐标是否不相等。 |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.Size-) | 按给定的 com.aspose.psd.Size 的相反方向平移 com.aspose.psd.PointF。 |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | 按指定的 com.aspose.psd.SizeF 的相反方向平移 com.aspose.psd.PointF。 |
| [setX(float value)](#setX-float-) | 获取或设置此 com.aspose.psd.PointF 的 X 坐标。 |
| [setY(float value)](#setY-float-) | 获取或设置此 com.aspose.psd.PointF 的 Y 坐标。 |
| [subtract(PointF point, Size size)](#subtract-com.aspose.psd.PointF-com.aspose.psd.Size-) | 按指定尺寸的相反方向平移 com.aspose.psd.PointF。 |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | 按指定尺寸的相反方向平移 com.aspose.psd.PointF。 |
| [toString()](#toString--) | 将此 com.aspose.psd.PointF 转换为可读的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


使用指定坐标初始化 com.aspose.psd.PointF 结构的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | float | 点的水平位置。 |
| y | float | 点的垂直位置。 |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.psd/pointf)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(PointF that) {#CloneTo-com.aspose.psd.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| that | [PointF](../../com.aspose.psd/pointf) |  |

### add(PointF point, Size size) {#add-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF add(PointF point, Size size)
```


按指定的 com.aspose.psd.Size 平移给定的 com.aspose.psd.PointF。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 要平移的 com.aspose.psd.PointF。 |
| size | [Size](../../com.aspose.psd/size) | 指定要添加到点坐标的数值的 com.aspose.psd.Size。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### add(PointF point, SizeF size) {#add-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


按指定的 com.aspose.psd.SizeF 平移给定的 com.aspose.psd.PointF。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 要平移的 com.aspose.psd.PointF。 |
| size | [SizeF](../../com.aspose.psd/sizef) | 指定要添加到 point 坐标的数字的  com.aspose.psd.SizeF  。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定此 com.aspose.psd.PointF 是否包含与指定的 System.Object 相同的坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于测试的  System.Object  。 |

**Returns:**
boolean - 如果  obj  是一个  com.aspose.psd.PointF  并且具有与此  com.aspose.psd.Point  相同的坐标，则此方法返回 true。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


获取一个新的 com.aspose.psd.PointF 结构实例，其 com.aspose.psd.PointF.X 和 com.aspose.psd.PointF.Y 值均为零。

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getX() {#getX--}
```
public float getX()
```


获取或设置此 com.aspose.psd.PointF 的 X 坐标。

**Returns:**
float
### getY() {#getY--}
```
public float getY()
```


获取或设置此 com.aspose.psd.PointF 的 Y 坐标。

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此 com.aspose.psd.PointF 结构的哈希码。

**Returns:**
int - 为此  com.aspose.psd.PointF  结构指定哈希值的整数。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


获取一个值，指示此 com.aspose.psd.PointF 是否为空。

**Returns:**
boolean - 如果  com.aspose.psd.PointF.X  和  com.aspose.psd.PointF.Y  均为 0，则为 True；否则为 false。
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.psd/pointf) |  |
| obj2 | [PointF](../../com.aspose.psd/pointf) |  |

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




### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


按给定的 com.aspose.psd.Size 平移 com.aspose.psd.PointF。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 要平移的 com.aspose.psd.PointF。 |
| size | [Size](../../com.aspose.psd/size) | 指定要添加到 point 坐标的数字对的  com.aspose.psd.Size  。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - Returns the translated  com.aspose.psd.PointF .
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


按指定的 com.aspose.psd.SizeF 平移 com.aspose.psd.PointF。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 要平移的 com.aspose.psd.PointF。 |
| size | [SizeF](../../com.aspose.psd/sizef) | 指定要添加到 point 的 x 和 y 坐标的数字的  com.aspose.psd.SizeF  。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


比较两个  com.aspose.psd.PointF  结构。结果指定这两个  com.aspose.psd.PointF  结构的  com.aspose.psd.PointF.X  和  com.aspose.psd.PointF.Y  属性的值是否相等。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | 要比较的第一个  com.aspose.psd.PointF  。 |
| point2 | [PointF](../../com.aspose.psd/pointf) | 要比较的第二个  com.aspose.psd.PointF  。 |

**Returns:**
boolean - 如果第一个和第二个  com.aspose.psd.PointF  结构的  com.aspose.psd.PointF.X  和  com.aspose.psd.PointF.Y  值相等，则为 True；否则为 false。
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


确定指定点的坐标是否不相等。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | 要比较的第一个  com.aspose.psd.PointF  。 |
| point2 | [PointF](../../com.aspose.psd/pointf) | 要比较的第二个  com.aspose.psd.PointF  。 |

**Returns:**
boolean - 如果  point1  和  point2  的  com.aspose.psd.PointF.X  与  com.aspose.psd.PointF.Y  值不相等，则为 True；否则为 false。
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


按给定的 com.aspose.psd.Size 的相反方向平移 com.aspose.psd.PointF。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 要平移的  com.aspose.psd.PointF  。 |
| size | [Size](../../com.aspose.psd/size) | 指定要从 point 的 x 和 y 坐标减去的数字的  com.aspose.psd.Size  。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


按指定的 com.aspose.psd.SizeF 的相反方向平移 com.aspose.psd.PointF。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 要平移的 com.aspose.psd.PointF。 |
| size | [SizeF](../../com.aspose.psd/sizef) | 指定要从 point 坐标减去的数字的  com.aspose.psd.SizeF  。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


获取或设置此 com.aspose.psd.PointF 的 X 坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


获取或设置此 com.aspose.psd.PointF 的 Y 坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### subtract(PointF point, Size size) {#subtract-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF subtract(PointF point, Size size)
```


按指定尺寸的相反方向平移 com.aspose.psd.PointF。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 要平移的 com.aspose.psd.PointF。 |
| size | [Size](../../com.aspose.psd/size) | 指定要从 point 坐标减去的数字的  com.aspose.psd.Size  。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### subtract(PointF point, SizeF size) {#subtract-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


按指定尺寸的相反方向平移 com.aspose.psd.PointF。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 要平移的 com.aspose.psd.PointF。 |
| size | [SizeF](../../com.aspose.psd/sizef) | 指定要从 point 坐标减去的数字的  com.aspose.psd.SizeF  。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### toString() {#toString--}
```
public String toString()
```


将此 com.aspose.psd.PointF 转换为可读的字符串。

**Returns:**
java.lang.String - 表示此  com.aspose.psd.PointF  的字符串。
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

