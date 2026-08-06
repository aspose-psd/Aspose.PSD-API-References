---
title: "ComplexTypeBase"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示 XMP 复合值类型的基础抽象。"
type: docs
weight: 10
url: /zh/java/com.aspose.psd.xmp.types.complex/complextypebase/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public class ComplexTypeBase extends XmpTypeBase
```

表示 XMP 复合值类型的基础抽象。

查看更多：XMP Specification Part 2, Chapter 1.2.2
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ComplexTypeBase(String prefix, String namespaceUri)](#ComplexTypeBase-java.lang.String-java.lang.String-) | 初始化 ComplexTypeBase 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | 添加指定的键。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getNamespaceUri()](#getNamespaceUri--) | 获取默认命名空间 URI。 |
| [getPrefix()](#getPrefix--) | 获取前缀。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取 XMP 格式的字符串值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexTypeBase(String prefix, String namespaceUri) {#ComplexTypeBase-java.lang.String-java.lang.String-}
```
public ComplexTypeBase(String prefix, String namespaceUri)
```


初始化 ComplexTypeBase 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 前缀 | java.lang.String | 前缀。 |
| namespaceUri | java.lang.String | 命名空间 URI。 |

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


添加指定的键。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | java.lang.String | key 的字符串表示形式，用于标识已添加的值。 |
| 值 | java.lang.Object | 要添加到的值。 |

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
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


获取默认命名空间 URI。

**Returns:**
java.lang.String - 默认的命名空间 URI。
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


获取前缀。

**Returns:**
java.lang.String - 前缀。
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


获取 XMP 格式的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式的字符串值。
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

