---
title: "Figure"
second_title: "Aspose.PSD 的 Java API 参考"
description: "图形。"
type: docs
weight: 42
url: /zh/java/com.aspose.psd/figure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

图形。形状的容器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Figure()](#Figure--) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [addShape(Shape shape)](#addShape-com.aspose.psd.Shape-) | 向图形添加形状。 |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.psd.Shape---) | 向图形添加一系列形状。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | 获取或设置对象的边界。 |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | 获取对象的边界。 |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | 获取对象的边界。 |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | 获取整个图形的段。 |
| [getShapes()](#getShapes--) | 获取图形的形状。 |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | 获取一个值，指示此图形是否闭合。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeShape(Shape shape)](#removeShape-com.aspose.psd.Shape-) | 从图形中移除一个形状。 |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.psd.Shape---) | 从图形中移除一系列形状。 |
| [reverse()](#reverse--) | 反转此图形的形状顺序和形状点的顺序。 |
| [setClosed(boolean value)](#setClosed-boolean-) | 设置一个值，指示此图形是否闭合。 |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | 将指定的变换应用于形状。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Figure() {#Figure--}
```
public Figure()
```


### addShape(Shape shape) {#addShape-com.aspose.psd.Shape-}
```
public void addShape(Shape shape)
```


向图形添加形状。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | 要添加的形状。 |

### addShapes(Shape[] shapes) {#addShapes-com.aspose.psd.Shape---}
```
public void addShapes(Shape[] shapes)
```


向图形添加一系列形状。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | 要添加的形状集合。 |

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
public RectangleF getBounds()
```


获取或设置对象的边界。

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
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
public RectangleF getBounds(Matrix matrix, Pen pen)
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
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


获取整个图形的段。

**Returns:**
com.aspose.psd.ShapeSegment[] - 图形段。
### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


获取图形的形状。

**Returns:**
com.aspose.psd.Shape[] - 图形形状。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


获取一个值，指示此图形是否闭合。闭合图形仅在首个和最后一个图形的形状是连续形状的情况下才会产生差异。在这种情况下，首个形状的第一个点将通过一条直线与最后一个形状的最后一点相连。

**Returns:**
boolean - 如果此图形闭合则为 True；否则为 false。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeShape(Shape shape) {#removeShape-com.aspose.psd.Shape-}
```
public void removeShape(Shape shape)
```


从图形中移除一个形状。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | 要移除的形状。 |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.psd.Shape---}
```
public void removeShapes(Shape[] shapes)
```


从图形中移除一系列形状。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | 要移除的形状范围。 |

### reverse() {#reverse--}
```
public void reverse()
```


反转此图形的形状顺序和形状点的顺序。

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


设置一个值，指示此图形是否闭合。闭合图形仅在首个和最后一个图形的形状是连续形状的情况下才会产生差异。在这种情况下，首个形状的第一个点将通过一条直线与最后一个形状的最后一点相连。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | 如果此图形闭合则为 True；否则为 false。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
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

