---
title: "ObjectWithBounds"
second_title: "Aspose.PSD 的 Java API 参考"
description: "具有边界的对象。"
type: docs
weight: 74
url: /zh/java/com.aspose.psd/objectwithbounds/
---

**Inheritance:**
java.lang.Object
```
public abstract class ObjectWithBounds
```

具有边界的对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ObjectWithBounds()](#ObjectWithBounds--) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | 获取对象的边界。 |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | 获取对象的边界。 |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | 获取对象的边界。 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | 将指定的变换应用于形状。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ObjectWithBounds() {#ObjectWithBounds--}
```
public ObjectWithBounds()
```


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
### getBounds() {#getBounds--}
```
public abstract RectangleF getBounds()
```


获取对象的边界。

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public abstract RectangleF getBounds(Matrix matrix)
```


获取对象的边界。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 在计算边界之前要应用的矩阵。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public abstract RectangleF getBounds(Matrix matrix, Pen pen)
```


获取对象的边界。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 在计算边界之前要应用的矩阵。 |
| pen | [Pen](../../com.aspose.psd/pen) | 用于对象的笔。这可能会影响对象的边界大小。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public abstract void transform(Matrix transform)
```


将指定的变换应用于形状。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | 要应用的变换。 |

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

