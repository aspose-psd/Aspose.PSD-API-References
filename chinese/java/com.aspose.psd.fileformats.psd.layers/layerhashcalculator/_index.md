---
title: "LayerHashCalculator"
second_title: "Aspose.PSD 的 Java API 参考"
description: "PSD 图层的哈希计算器。"
type: docs
weight: 20
url: /zh/java/com.aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Inheritance:**
java.lang.Object
```
public class LayerHashCalculator
```

PSD 图层的哈希计算器。它可用于在不同的 PSD 文件中查找相等或不同的图层。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LayerHashCalculator(Layer layer)](#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-) | 初始化 [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator) 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendingHash()](#getBlendingHash--) | 获取混合哈希。 |
| [getChannelsHash()](#getChannelsHash--) | 获取通道哈希。 |
| [getClass()](#getClass--) |  |
| [getContentHash()](#getContentHash--) | 获取内容哈希。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerHashCalculator(Layer layer) {#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public LayerHashCalculator(Layer layer)
```


初始化 [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 该图层。 |

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
### getBlendingHash() {#getBlendingHash--}
```
public final int getBlendingHash()
```


获取混合哈希。

**Returns:**
int - 图层混合选项的唯一哈希
### getChannelsHash() {#getChannelsHash--}
```
public final int getChannelsHash()
```


获取通道哈希。

**Returns:**
int - 所有图层通道的哈希
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentHash() {#getContentHash--}
```
public final int getContentHash()
```


获取内容哈希。

**Returns:**
int - 图层重要参数的哈希。此哈希对所有图层类型均不同
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

