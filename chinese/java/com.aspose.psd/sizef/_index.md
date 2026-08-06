---
title: "SizeF"
second_title: "Aspose.PSD 的 Java API 参考"
description: "存储一对有序的浮点数，通常表示矩形的宽度和高度。"
type: docs
weight: 99
url: /zh/java/com.aspose.psd/sizef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class SizeF extends Struct<SizeF>
```

存储一对有序的浮点数，通常表示矩形的宽度和高度。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(SizeF size)](#SizeF-com.aspose.psd.SizeF-) | 从指定的 Aspose.Imaging.SizeF 初始化一个新的 Aspose.Imaging.SizeF 结构实例。 |
| [SizeF(PointF point)](#SizeF-com.aspose.psd.PointF-) | 从指定的 Aspose.Imaging.PointF 初始化一个新的 Aspose.Imaging.SizeF 结构实例。 |
| [SizeF(float width, float height)](#SizeF-float-float-) | 从指定的尺寸初始化一个新的 Aspose.Imaging.SizeF 结构实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.psd.SizeF-) |  |
| [add(SizeF size1, SizeF size2)](#add-com.aspose.psd.SizeF-com.aspose.psd.SizeF-) | 将一个 Aspose.Imaging.SizeF 结构的宽度和高度添加到另一个 Aspose.Imaging.SizeF 结构的宽度和高度。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 测试指定的对象是否为具有与此 Aspose.Imaging.SizeF 相同尺寸的 Aspose.Imaging.SizeF。 |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | 获取一个新的 Aspose.Imaging.SizeF 结构实例，其 Aspose.Imaging.SizeF.Width 和 Aspose.Imaging.SizeF.Height 值均为零。 |
| [getHeight()](#getHeight--) | 获取或设置此 Aspose.Imaging.SizeF 的垂直分量。 |
| [getWidth()](#getWidth--) | 获取或设置此 Aspose.Imaging.SizeF 的水平分量。 |
| [hashCode()](#hashCode--) | 返回此 Aspose.Imaging.Size 结构的哈希码。 |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 Aspose.Imaging.SizeF 是否宽度和高度均为零。 |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.psd.SizeF-com.aspose.psd.SizeF-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(SizeF size1, SizeF size2)](#op-Addition-com.aspose.psd.SizeF-com.aspose.psd.SizeF-) | 将一个 Aspose.Imaging.SizeF 结构的宽度和高度添加到另一个 Aspose.Imaging.SizeF 结构的宽度和高度。 |
| [op_Equality(SizeF size1, SizeF size2)](#op-Equality-com.aspose.psd.SizeF-com.aspose.psd.SizeF-) | 测试两个 Aspose.Imaging.SizeF 结构是否相等。 |
| [op_Inequality(SizeF size1, SizeF size2)](#op-Inequality-com.aspose.psd.SizeF-com.aspose.psd.SizeF-) | 测试两个 Aspose.Imaging.SizeF 结构是否不同。 |
| [op_Subtraction(SizeF size1, SizeF size2)](#op-Subtraction-com.aspose.psd.SizeF-com.aspose.psd.SizeF-) | 从另一个 Aspose.Imaging.SizeF 结构的宽度和高度中减去一个 Aspose.Imaging.SizeF 结构的宽度和高度。 |
| [setHeight(float value)](#setHeight-float-) | 获取或设置此 Aspose.Imaging.SizeF 的垂直分量。 |
| [setWidth(float value)](#setWidth-float-) | 获取或设置此 Aspose.Imaging.SizeF 的水平分量。 |
| [subtract(SizeF size1, SizeF size2)](#subtract-com.aspose.psd.SizeF-com.aspose.psd.SizeF-) | 从另一个 Aspose.Imaging.SizeF 结构的宽度和高度中减去一个 Aspose.Imaging.SizeF 结构的宽度和高度。 |
| [toPointF()](#toPointF--) | 将 Aspose.Imaging.SizeF 转换为 Aspose.Imaging.PointF。 |
| [toSize()](#toSize--) | 将 Aspose.Imaging.SizeF 转换为具有截断尺寸值的 Aspose.Imaging.Size 结构。 |
| [toString()](#toString--) | 创建一个可读的字符串，表示此 Aspose.Imaging.SizeF。 |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.psd.SizeF-) | 将指定的 Aspose.Imaging.SizeF 转换为 Aspose.Imaging.PointF。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(SizeF size) {#SizeF-com.aspose.psd.SizeF-}
```
public SizeF(SizeF size)
```


从指定的 Aspose.Imaging.SizeF 初始化一个新的 Aspose.Imaging.SizeF 结构实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | 用于创建新 Aspose.Imaging.SizeF 的 Aspose.Imaging.SizeF。 |

### SizeF(PointF point) {#SizeF-com.aspose.psd.PointF-}
```
public SizeF(PointF point)
```


从指定的 Aspose.Imaging.PointF 初始化一个新的 Aspose.Imaging.SizeF 结构实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 用于初始化此 Aspose.Imaging.SizeF 的 Aspose.Imaging.PointF。 |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


从指定的尺寸初始化一个新的 Aspose.Imaging.SizeF 结构实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 宽度 | float | 新 Aspose.Imaging.SizeF 的宽度分量。 |
| 高度 | float | 新 Aspose.Imaging.SizeF 的高度分量。 |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.psd/sizef)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(SizeF that) {#CloneTo-com.aspose.psd.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.psd/sizef) |  |

### add(SizeF size1, SizeF size2) {#add-com.aspose.psd.SizeF-com.aspose.psd.SizeF-}
```
public static SizeF add(SizeF size1, SizeF size2)
```


将一个 Aspose.Imaging.SizeF 结构的宽度和高度添加到另一个 Aspose.Imaging.SizeF 结构的宽度和高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.psd/sizef) | 要添加的第一个 Aspose.Imaging.SizeF。 |
| size2 | [SizeF](../../com.aspose.psd/sizef) | 要添加的第二个 Aspose.Imaging.SizeF。 |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  Aspose.Imaging.SizeF  structure that is the result of the addition operation.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


测试指定的对象是否为具有与此 Aspose.Imaging.SizeF 相同尺寸的 Aspose.Imaging.SizeF。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于测试的  System.Object  。 |

**Returns:**
boolean - 如果 obj 是 Aspose.Imaging.SizeF 且其宽度和高度与此 Aspose.Imaging.SizeF 相同，则此方法返回 true；否则返回 false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```


获取一个新的 Aspose.Imaging.SizeF 结构实例，其 Aspose.Imaging.SizeF.Width 和 Aspose.Imaging.SizeF.Height 值均为零。

**Returns:**
[SizeF](../../com.aspose.psd/sizef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


获取或设置此 Aspose.Imaging.SizeF 的垂直分量。

**Returns:**
float - 此 Aspose.Imaging.SizeF 的垂直分量，通常以像素为单位。
### getWidth() {#getWidth--}
```
public float getWidth()
```


获取或设置此 Aspose.Imaging.SizeF 的水平分量。

**Returns:**
float - 此 Aspose.Imaging.SizeF 的水平分量，通常以像素为单位。
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


获取一个值，指示此 Aspose.Imaging.SizeF 是否宽度和高度均为零。

**Returns:**
boolean - 当此 Aspose.Imaging.SizeF 的宽度和高度均为零时，此属性返回 true；否则返回 false。
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.psd.SizeF-com.aspose.psd.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.psd/sizef) |  |
| obj2 | [SizeF](../../com.aspose.psd/sizef) |  |

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




### op_Addition(SizeF size1, SizeF size2) {#op-Addition-com.aspose.psd.SizeF-com.aspose.psd.SizeF-}
```
public static SizeF op_Addition(SizeF size1, SizeF size2)
```


将一个 Aspose.Imaging.SizeF 结构的宽度和高度添加到另一个 Aspose.Imaging.SizeF 结构的宽度和高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.psd/sizef) | 要添加的第一个 Aspose.Imaging.SizeF。 |
| size2 | [SizeF](../../com.aspose.psd/sizef) | 要添加的第二个 Aspose.Imaging.SizeF。 |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  Aspose.Imaging.SizeF  structure that is the result of the addition operation.
### op_Equality(SizeF size1, SizeF size2) {#op-Equality-com.aspose.psd.SizeF-com.aspose.psd.SizeF-}
```
public static boolean op_Equality(SizeF size1, SizeF size2)
```


测试两个 Aspose.Imaging.SizeF 结构是否相等。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.psd/sizef) | 相等运算符左侧的 Aspose.Imaging.SizeF 结构体。 |
| size2 | [SizeF](../../com.aspose.psd/sizef) | 相等运算符右侧的 Aspose.Imaging.SizeF 结构体。 |

**Returns:**
boolean - 如果 size1 和 size2 的宽度和高度相等，则此运算符返回 true；否则返回 false。
### op_Inequality(SizeF size1, SizeF size2) {#op-Inequality-com.aspose.psd.SizeF-com.aspose.psd.SizeF-}
```
public static boolean op_Inequality(SizeF size1, SizeF size2)
```


测试两个 Aspose.Imaging.SizeF 结构是否不同。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.psd/sizef) | 不等运算符左侧的 Aspose.Imaging.SizeF 结构体。 |
| size2 | [SizeF](../../com.aspose.psd/sizef) | 不等运算符右侧的 Aspose.Imaging.SizeF 结构体。 |

**Returns:**
boolean - 如果 size1 和 size2 在宽度或高度任一方面不同，则此运算符返回 true；如果 size1 和 size2 相等，则返回 false。
### op_Subtraction(SizeF size1, SizeF size2) {#op-Subtraction-com.aspose.psd.SizeF-com.aspose.psd.SizeF-}
```
public static SizeF op_Subtraction(SizeF size1, SizeF size2)
```


从另一个 Aspose.Imaging.SizeF 结构的宽度和高度中减去一个 Aspose.Imaging.SizeF 结构的宽度和高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.psd/sizef) | 减法运算符左侧的 Aspose.Imaging.SizeF。 |
| size2 | [SizeF](../../com.aspose.psd/sizef) | 减法运算符右侧的 Aspose.Imaging.SizeF。 |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  Aspose.Imaging.SizeF  that is the result of the subtraction operation.
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


获取或设置此 Aspose.Imaging.SizeF 的垂直分量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


获取或设置此 Aspose.Imaging.SizeF 的水平分量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### subtract(SizeF size1, SizeF size2) {#subtract-com.aspose.psd.SizeF-com.aspose.psd.SizeF-}
```
public static SizeF subtract(SizeF size1, SizeF size2)
```


从另一个 Aspose.Imaging.SizeF 结构的宽度和高度中减去一个 Aspose.Imaging.SizeF 结构的宽度和高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.psd/sizef) | 减法运算符左侧的 Aspose.Imaging.SizeF 结构体。 |
| size2 | [SizeF](../../com.aspose.psd/sizef) | 减法运算符右侧的 Aspose.Imaging.SizeF 结构体。 |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The  Aspose.Imaging.SizeF  that is a result of the subtraction operation.
### toPointF() {#toPointF--}
```
public PointF toPointF()
```


将 Aspose.Imaging.SizeF 转换为 Aspose.Imaging.PointF。

**Returns:**
[PointF](../../com.aspose.psd/pointf) - Returns a  Aspose.Imaging.PointF  structure.
### toSize() {#toSize--}
```
public Size toSize()
```


将 Aspose.Imaging.SizeF 转换为具有截断尺寸值的 Aspose.Imaging.Size 结构。

**Returns:**
[Size](../../com.aspose.psd/size) - Returns a  Aspose.Imaging.Size  structure.
### toString() {#toString--}
```
public String toString()
```


创建一个可读的字符串，表示此 Aspose.Imaging.SizeF。

**Returns:**
java.lang.String - 表示此 Aspose.Imaging.SizeF 的字符串。
### to_PointF(SizeF size) {#to-PointF-com.aspose.psd.SizeF-}
```
public static PointF to_PointF(SizeF size)
```


将指定的 Aspose.Imaging.SizeF 转换为 Aspose.Imaging.PointF。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | 待转换的 Aspose.Imaging.SizeF 结构体 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  Aspose.Imaging.PointF  structure to which this operator converts.
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

