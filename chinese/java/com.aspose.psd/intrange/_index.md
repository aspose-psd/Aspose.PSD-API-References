---
title: "IntRange"
second_title: "Aspose.PSD 的 Java API 参考"
description: "用于表示元素序列的类"
type: docs
weight: 62
url: /zh/java/com.aspose.psd/intrange/
---

**Inheritance:**
java.lang.Object
```
public class IntRange
```

用于表示元素序列的类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [IntRange(int start, int count)](#IntRange-int-int-) | 初始化一个新的  IntRange  类实例。 |
| [IntRange(int start, int count, int delta)](#IntRange-int-int-int-) | 初始化一个新的  IntRange  类实例。 |
| [IntRange(int[] range)](#IntRange-int---) | 初始化一个新的  IntRange  类实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArrayOneItemFromIndex(int index)](#getArrayOneItemFromIndex-int-) | 返回从指定索引开始的单项数组 |
| [getClass()](#getClass--) |  |
| [getRange()](#getRange--) | 获取范围。 |
| [getRange(int start, int count, int delta)](#getRange-int-int-int-) | 获取从 start 开始的 int 元素的计数范围 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setRange(int[] value)](#setRange-int---) | 设置范围。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IntRange(int start, int count) {#IntRange-int-int-}
```
public IntRange(int start, int count)
```


初始化一个新的  IntRange  类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 起始 | int | 开始。 |
| count | int | 计数。 |

### IntRange(int start, int count, int delta) {#IntRange-int-int-int-}
```
public IntRange(int start, int count, int delta)
```


初始化一个新的  IntRange  类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 起始 | int | 开始。 |
| count | int | 计数。 |
| 增量 | int | 增量。 |

### IntRange(int[] range) {#IntRange-int---}
```
public IntRange(int[] range)
```


初始化一个新的  IntRange  类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 范围 | int[] | 范围。 |

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
### getArrayOneItemFromIndex(int index) {#getArrayOneItemFromIndex-int-}
```
public int[] getArrayOneItemFromIndex(int index)
```


返回从指定索引开始的单项数组

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| index | int | 范围索引。 |

**Returns:**
int[] - System.Int32 的数组
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getRange() {#getRange--}
```
public int[] getRange()
```


获取范围。

**Returns:**
int[] - 范围。
### getRange(int start, int count, int delta) {#getRange-int-int-int-}
```
public static int[] getRange(int start, int count, int delta)
```


获取从 start 开始的 int 元素的计数范围

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 起始 | int | 开始。 |
| count | int | 计数。 |
| 增量 | int | 增量。 |

**Returns:**
int[] - 项目数组
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




### setRange(int[] value) {#setRange-int---}
```
public void setRange(int[] value)
```


设置范围。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] | 范围。 |

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

