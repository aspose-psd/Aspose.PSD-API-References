---
title: "FixedPointDecimal"
second_title: "Aspose.PSD 的 Java API 参考"
description: "具有 16 位整数和 16 位小数的定点小数。"
type: docs
weight: 17
url: /zh/java/com.aspose.psd.fileformats.psd.resources/fixedpointdecimal/
---

**Inheritance:**
java.lang.Object
```
public class FixedPointDecimal
```

定点小数，具有 16 位整数和 16 位小数部分。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FixedPointDecimal(int integer, int fraction)](#FixedPointDecimal-int-int-) | 初始化 [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) 类的新实例。 |
| [FixedPointDecimal(long value)](#FixedPointDecimal-long-) | 初始化 [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) 类的新实例。 |
| [FixedPointDecimal(double value)](#FixedPointDecimal-double-) | 初始化 [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFraction()](#getFraction--) | 获取或设置分数。 |
| [getInteger()](#getInteger--) | 获取或设置整数。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFraction(int value)](#setFraction-int-) | 获取或设置分数。 |
| [setInteger(int value)](#setInteger-int-) | 获取或设置整数。 |
| [toDouble()](#toDouble--) | 将当前定点小数转换为 double。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FixedPointDecimal(int integer, int fraction) {#FixedPointDecimal-int-int-}
```
public FixedPointDecimal(int integer, int fraction)
```


初始化 [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 整数 | int | 整数。 |
| 分数 | int | 分数。 |

### FixedPointDecimal(long value) {#FixedPointDecimal-long-}
```
public FixedPointDecimal(long value)
```


初始化 [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) 类的新实例。将 32 位整数的高位和低位拆分为定点数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long | 该值。 |

### FixedPointDecimal(double value) {#FixedPointDecimal-double-}
```
public FixedPointDecimal(double value)
```


初始化 [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double | 该值。 |

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
### getFraction() {#getFraction--}
```
public final int getFraction()
```


获取或设置分数。

值：分数。

**Returns:**
int
### getInteger() {#getInteger--}
```
public final int getInteger()
```


获取或设置整数。

值：整数。

**Returns:**
int
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




### setFraction(int value) {#setFraction-int-}
```
public final void setFraction(int value)
```


获取或设置分数。

值：分数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setInteger(int value) {#setInteger-int-}
```
public final void setInteger(int value)
```


获取或设置整数。

值：整数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```


将当前定点小数转换为 double。

**Returns:**
double - 转换后的值。
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

