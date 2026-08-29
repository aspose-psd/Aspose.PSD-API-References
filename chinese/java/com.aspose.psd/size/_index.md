---
title: "尺寸"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示大小。"
type: docs
weight: 98
url: /zh/java/com.aspose.psd/size/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

表示大小。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.psd.Point-) | 从指定的 Aspose.Imaging.Point 初始化 Aspose.Imaging.Size 结构的新实例。 |
| [Size(int width, int height)](#Size-int-int-) | 从指定的尺寸初始化 Aspose.Imaging.Size 结构的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Size that)](#CloneTo-com.aspose.psd.Size-) |  |
| [add(Size size1, Size size2)](#add-com.aspose.psd.Size-com.aspose.psd.Size-) | 将一个 Aspose.Imaging.Size 结构的宽度和高度添加到另一个 Aspose.Imaging.Size 结构的宽度和高度。 |
| [ceiling(SizeF size)](#ceiling-com.aspose.psd.SizeF-) | 通过将 Aspose.Imaging.Size 结构的值向上取整为更高的整数，将指定的 Aspose.Imaging.SizeF 结构转换为 Aspose.Imaging.Size 结构。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 测试指定的对象是否为具有与此 Aspose.Imaging.Size 相同尺寸的 Aspose.Imaging.Size。 |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | 获取一个新的 Aspose.Imaging.Size 结构实例，其 Aspose.Imaging.Size.Width 和 Aspose.Imaging.Size.Height 值均为零。 |
| [getHeight()](#getHeight--) | 获取或设置此 Aspose.Imaging.Size 的垂直分量。 |
| [getWidth()](#getWidth--) | 获取或设置此 Aspose.Imaging.Size 的水平分量。 |
| [hashCode()](#hashCode--) | 返回此 Aspose.Imaging.Size 结构的哈希码。 |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 Aspose.Imaging.Size 的宽度和高度是否为 0。 |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-) | 将一个 Aspose.Imaging.Size 结构的宽度和高度添加到另一个 Aspose.Imaging.Size 结构的宽度和高度。 |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-) | 测试两个 Aspose.Imaging.Size 结构是否相等。 |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-) | 测试两个 Aspose.Imaging.Size 结构是否不同。 |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-) | 从另一个  Aspose.Imaging.Size  结构的宽度和高度中减去一个  Aspose.Imaging.Size  结构的宽度和高度。 |
| [round(SizeF size)](#round-com.aspose.psd.SizeF-) | 通过将指定的  Aspose.Imaging.SizeF  结构的值四舍五入到最接近的整数，将其转换为  Aspose.Imaging.Size  结构。 |
| [setHeight(int value)](#setHeight-int-) | 获取或设置此 Aspose.Imaging.Size 的垂直分量。 |
| [setWidth(int value)](#setWidth-int-) | 获取或设置此 Aspose.Imaging.Size 的水平分量。 |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.psd.Size-com.aspose.psd.Size-) | 从另一个  Aspose.Imaging.Size  结构的宽度和高度中减去一个  Aspose.Imaging.Size  结构的宽度和高度。 |
| [toString()](#toString--) | 创建一个可读的字符串来表示此  Aspose.Imaging.Size  。 |
| [to_Point(Size size)](#to-Point-com.aspose.psd.Size-) | 将指定的  Aspose.Imaging.Size  转换为  Aspose.Imaging.Point  。 |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.psd.Size-) | 将指定的  Aspose.Imaging.Size  转换为  Aspose.Imaging.SizeF  。 |
| [truncate(SizeF size)](#truncate-com.aspose.psd.SizeF-) | 通过将指定的  Aspose.Imaging.SizeF  结构的值截断为下一个更低的整数值，将其转换为  Aspose.Imaging.Size  结构。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.psd.Point-}
```
public Size(Point point)
```


从指定的 Aspose.Imaging.Point 初始化 Aspose.Imaging.Size 结构的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 用于初始化此  Aspose.Imaging.Size  的  Aspose.Imaging.Point  。 |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


从指定的尺寸初始化 Aspose.Imaging.Size 结构的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 宽度 | int | 新  Aspose.Imaging.Size  的宽度分量。 |
| 高度 | int | 新  Aspose.Imaging.Size  的高度分量。 |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.psd/size)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Size that) {#CloneTo-com.aspose.psd.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| that | [Size](../../com.aspose.psd/size) |  |

### add(Size size1, Size size2) {#add-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size add(Size size1, Size size2)
```


将一个 Aspose.Imaging.Size 结构的宽度和高度添加到另一个 Aspose.Imaging.Size 结构的宽度和高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 要相加的第一个  Aspose.Imaging.Size  。 |
| size2 | [Size](../../com.aspose.psd/size) | 要相加的第二个  Aspose.Imaging.Size  。 |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.psd.SizeF-}
```
public static Size ceiling(SizeF size)
```


通过将 Aspose.Imaging.Size 结构的值向上取整为更高的整数，将指定的 Aspose.Imaging.SizeF 结构转换为 Aspose.Imaging.Size 结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | 要转换的  Aspose.Imaging.SizeF  结构。 |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


测试指定的对象是否为具有与此 Aspose.Imaging.Size 相同尺寸的 Aspose.Imaging.Size。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于测试的  System.Object  。 |

**Returns:**
boolean - 如果  obj  是一个  Aspose.Imaging.Size  并且其宽度和高度与此  Aspose.Imaging.Size 相同，则为 True；否则为 false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


获取一个新的 Aspose.Imaging.Size 结构实例，其 Aspose.Imaging.Size.Width 和 Aspose.Imaging.Size.Height 值均为零。

**Returns:**
[Size](../../com.aspose.psd/size)
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取或设置此 Aspose.Imaging.Size 的垂直分量。

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取或设置此 Aspose.Imaging.Size 的水平分量。

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此 Aspose.Imaging.Size 结构的哈希码。

**Returns:**
int - 一个整数值，指定此  Aspose.Imaging.Size  结构的哈希值。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


获取一个值，指示此 Aspose.Imaging.Size 的宽度和高度是否为 0。

**Returns:**
boolean
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.psd/size) |  |
| obj2 | [Size](../../com.aspose.psd/size) |  |

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




### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


将一个 Aspose.Imaging.Size 结构的宽度和高度添加到另一个 Aspose.Imaging.Size 结构的宽度和高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 要相加的第一个  Aspose.Imaging.Size  。 |
| size2 | [Size](../../com.aspose.psd/size) | 要相加的第二个  Aspose.Imaging.Size  。 |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


测试两个 Aspose.Imaging.Size 结构是否相等。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 等号运算符左侧的  Aspose.Imaging.Size  结构。 |
| size2 | [Size](../../com.aspose.psd/size) | 等号运算符右侧的  Aspose.Imaging.Size  结构。 |

**Returns:**
boolean - 如果  size1  和  size2  的宽度和高度相等，则为 True；否则为 false。
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


测试两个 Aspose.Imaging.Size 结构是否不同。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 不等号运算符左侧的  Aspose.Imaging.Size  结构。 |
| size2 | [Size](../../com.aspose.psd/size) | 不等号运算符右侧的  Aspose.Imaging.Size  结构。 |

**Returns:**
boolean - 如果  size1  和  size2  在宽度或高度上任一不同，则为 True；如果  size1  和  size2  相等，则为 false。
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


从另一个  Aspose.Imaging.Size  结构的宽度和高度中减去一个  Aspose.Imaging.Size  结构的宽度和高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 减法运算符左侧的  Aspose.Imaging.Size  结构。 |
| size2 | [Size](../../com.aspose.psd/size) | 减法运算符右侧的  Aspose.Imaging.Size  结构。 |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the subtraction operation.
### round(SizeF size) {#round-com.aspose.psd.SizeF-}
```
public static Size round(SizeF size)
```


通过将指定的  Aspose.Imaging.SizeF  结构的值四舍五入到最接近的整数，将其转换为  Aspose.Imaging.Size  结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | 要转换的  Aspose.Imaging.SizeF  结构。 |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


获取或设置此 Aspose.Imaging.Size 的垂直分量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


获取或设置此 Aspose.Imaging.Size 的水平分量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### subtract(Size size1, Size size2) {#subtract-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size subtract(Size size1, Size size2)
```


从另一个  Aspose.Imaging.Size  结构的宽度和高度中减去一个  Aspose.Imaging.Size  结构的宽度和高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 减法运算符左侧的  Aspose.Imaging.Size  结构。 |
| size2 | [Size](../../com.aspose.psd/size) | 减法运算符右侧的  Aspose.Imaging.Size  结构。 |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that is a result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


创建一个可读的字符串来表示此  Aspose.Imaging.Size  。

**Returns:**
java.lang.String - 表示此  Aspose.Imaging.Size  的字符串。
### to_Point(Size size) {#to-Point-com.aspose.psd.Size-}
```
public static Point to_Point(Size size)
```


将指定的  Aspose.Imaging.Size  转换为  Aspose.Imaging.Point  。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | 要转换的  Aspose.Imaging.Size  。 |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  structure to which this operator converts.
### to_SizeF(Size size) {#to-SizeF-com.aspose.psd.Size-}
```
public static SizeF to_SizeF(Size size)
```


将指定的  Aspose.Imaging.Size  转换为  Aspose.Imaging.SizeF  。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | 要转换的  Aspose.Imaging.Size  。 |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The  Aspose.Imaging.SizeF  structure to which this operator converts.
### truncate(SizeF size) {#truncate-com.aspose.psd.SizeF-}
```
public static Size truncate(SizeF size)
```


通过将指定的  Aspose.Imaging.SizeF  结构的值截断为下一个更低的整数值，将其转换为  Aspose.Imaging.Size  结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | 要转换的  Aspose.Imaging.SizeF  结构。 |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
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

