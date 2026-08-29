---
title: "ColorComponent"
second_title: "Aspose.PSD 的 Java API 参考"
description: "颜色组件是对通道值的抽象。"
type: docs
weight: 10
url: /zh/java/com.aspose.psd.fileformats.psd.rawcolor/colorcomponent/
---

**Inheritance:**
java.lang.Object
```
public final class ColorComponent
```

颜色组件是对 Channel Value 和 Channel Value 的抽象。任何颜色都由 ColorComponent 数组组成。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorComponent(byte bitDepth, String fullName)](#ColorComponent-byte-java.lang.String-) | 初始化 [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | 获取颜色组件/通道的位深度 |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | 获取颜色组件的描述 |
| [getFullName()](#getFullName--) | 获取颜色组件的完整名称，包含名称和以空格分隔的描述 |
| [getName()](#getName--) | 获取颜色组件的名称。 |
| [getPermittedFullNames()](#getPermittedFullNames--) | 获取允许的完整名称。 |
| [getValue()](#getValue--) | 获取或设置该值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(long value)](#setValue-long-) | 获取或设置该值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorComponent(byte bitDepth, String fullName) {#ColorComponent-byte-java.lang.String-}
```
public ColorComponent(byte bitDepth, String fullName)
```


初始化 [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) 类的新实例。请检查

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bitDepth | byte | 位深度。 |
| fullName | java.lang.String | 完整名称。 |

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
### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


获取颜色组件/通道的位深度

值：位深度。

**Returns:**
byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


获取颜色组件的描述

值：描述。

**Returns:**
java.lang.String
### getFullName() {#getFullName--}
```
public final String getFullName()
```


获取颜色组件的完整名称，包含名称和以空格分隔的描述

值：完整名称。

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


获取颜色组件的名称。

值：名称。

**Returns:**
java.lang.String
### getPermittedFullNames() {#getPermittedFullNames--}
```
public static String[] getPermittedFullNames()
```


获取允许的完整名称。

值：允许的完整名称。

**Returns:**
java.lang.String[]
### getValue() {#getValue--}
```
public final long getValue()
```


获取或设置该值。请注意，如果尝试设置的值超过当前位深度可存储的范围，将会抛出异常。

值：该值。

**Returns:**
long
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




### setValue(long value) {#setValue-long-}
```
public final void setValue(long value)
```


获取或设置该值。请注意，如果尝试设置的值超过当前位深度可存储的范围，将会抛出异常。

值：该值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

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

