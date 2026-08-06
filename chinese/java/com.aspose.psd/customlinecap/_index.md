---
title: "CustomLineCap"
second_title: "Aspose.PSD 的 Java API 参考"
description: "封装自定义的用户定义线帽。"
type: docs
weight: 34
url: /zh/java/com.aspose.psd/customlinecap/
---

**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

封装自定义的用户定义线帽。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-) | 使用指定的轮廓和填充初始化 CustomLineCap 类的新实例。 |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-) | 使用指定的轮廓和填充，从指定的现有 LineCap 枚举初始化 CustomLineCap 类的新实例。 |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-) | 使用指定的轮廓、填充和插入，从指定的现有 LineCap 枚举初始化 CustomLineCap 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaseCap()](#getBaseCap--) | 获取此 CustomLineCap 所基于的 LineCap 枚举。 |
| [getBaseInset()](#getBaseInset--) | 获取帽子与线之间的距离。 |
| [getClass()](#getClass--) |  |
| [getFillPath()](#getFillPath--) | 获取定义自定义帽子填充的对象。 |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | 获取用于开始和结束构成此自定义帽子的线的帽子。 |
| [getStrokeJoin()](#getStrokeJoin--) | 获取决定组成此 CustomLineCap 对象的线如何连接的 LineJoin 枚举。 |
| [getStrokePath()](#getStrokePath--) | 获取定义自定义帽子轮廓的对象。 |
| [getWidthScale()](#getWidthScale--) | 获取相对于 System.Drawing.Pen 对象宽度，对此 CustomLineCap 类对象的缩放量。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBaseCap(int value)](#setBaseCap-int-) | 设置此 CustomLineCap 所基于的 LineCap 枚举。 |
| [setBaseInset(float value)](#setBaseInset-float-) | 设置帽子与线之间的距离。 |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.psd.GraphicsPath-) | 设置定义自定义帽子填充的对象。 |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | 设置用于开始和结束构成此自定义帽子的线的帽子。 |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | 设置决定组成此 CustomLineCap 对象的线如何连接的 LineJoin 枚举。 |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.psd.GraphicsPath-) | 设置定义自定义帽子轮廓的对象。 |
| [setWidthScale(float value)](#setWidthScale-float-) | 设置相对于 System.Drawing.Pen 对象宽度，对此 CustomLineCap 类对象的缩放量。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


使用指定的轮廓和填充初始化 CustomLineCap 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | 一个定义自定义帽子填充的 GraphicsPath 对象。 |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | 一个定义自定义帽子轮廓的 GraphicsPath 对象。 |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


使用指定的轮廓和填充，从指定的现有 LineCap 枚举初始化 CustomLineCap 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | 一个定义自定义帽子填充的 GraphicsPath 对象。 |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | 一个定义自定义帽子轮廓的 GraphicsPath 对象。 |
| baseCap | int | 用于创建自定义帽子的线帽。 |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


使用指定的轮廓、填充和插入，从指定的现有 LineCap 枚举初始化 CustomLineCap 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | 一个定义自定义帽子填充的 GraphicsPath 对象。 |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | 一个定义自定义帽子轮廓的 GraphicsPath 对象。 |
| baseCap | int | 用于创建自定义帽子的线帽。 |
| baseInset | float | 帽子与线之间的距离。 |

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
### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


获取此 CustomLineCap 所基于的 LineCap 枚举。

**Returns:**
int - 此 CustomLineCap 所基于的 LineCap 枚举。
### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


获取帽子与线之间的距离。

**Returns:**
float - 帽子起点与线结束点之间的距离。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


获取定义自定义帽子填充的对象。

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the fill for the custom cap.
### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


获取用于开始和结束构成此自定义帽子的线的帽子。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| startCap | int[] | 此帽子内线起始处使用的 LineCap 枚举。 |
| endCap | int[] | 此帽子中用于线段末端的 LineCap 枚举。 |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


获取决定组成此 CustomLineCap 对象的线如何连接的 LineJoin 枚举。

**Returns:**
int - 此 CustomLineCap 对象用于连接线段的 LineJoin 枚举。
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


获取定义自定义帽子轮廓的对象。

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the outline of the custom cap.
### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


获取相对于 System.Drawing.Pen 对象宽度，对此 CustomLineCap 类对象的缩放量。

**Returns:**
float - 缩放帽子的量。
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




### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


设置此 CustomLineCap 所基于的 LineCap 枚举。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 此 CustomLineCap 基于的 LineCap 枚举。 |

### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


设置帽子与线之间的距离。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 帽子起点与线段终点之间的距离。 |

### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.psd.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


设置定义自定义帽子填充的对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | 定义自定义帽子填充的对象。 |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


设置用于开始和结束构成此自定义帽子的线的帽子。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| startCap | int | 此帽子内线起始处使用的 LineCap 枚举。 |
| endCap | int | 此帽子中用于线段末端的 LineCap 枚举。 |

### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


设置决定组成此 CustomLineCap 对象的线如何连接的 LineJoin 枚举。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 此 CustomLineCap 对象用于连接线段的 LineJoin 枚举。 |

### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.psd.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


设置定义自定义帽子轮廓的对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | 定义自定义帽子轮廓的对象。 |

### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


设置相对于 System.Drawing.Pen 对象宽度，对此 CustomLineCap 类对象的缩放量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 缩放帽子的量。 |

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

