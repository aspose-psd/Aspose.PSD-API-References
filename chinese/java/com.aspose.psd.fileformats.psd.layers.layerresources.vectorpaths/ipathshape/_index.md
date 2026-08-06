---
title: "IPathShape"
second_title: "Aspose.PSD 的 Java API 参考"
description: "来自贝塞尔曲线节点的形状。"
type: docs
weight: 31
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape/
---
```
public interface IPathShape
```

来自贝塞尔曲线节点的形状。
## Methods

| Method | 描述 |
| --- | --- |
| [getItems()](#getItems--) | 获取贝塞尔节点数组。 |
| [getPathOperations()](#getPathOperations--) | 路径形状组合的操作（布尔运算）。 |
| [isClosed()](#isClosed--) | 获取或设置决定形状是否闭合的属性。 |
| [setClosed(boolean value)](#setClosed-boolean-) | 获取或设置决定形状是否闭合的属性。 |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | 分配 Bexier 节点数组。 |
| [setPathOperations(int value)](#setPathOperations-int-) | 路径形状组合的操作（布尔运算）。 |
### getItems() {#getItems--}
```
public abstract BezierKnotRecord[] getItems()
```


获取贝塞尔节点数组。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - BezierKnotRecord 的数组。
### getPathOperations() {#getPathOperations--}
```
public abstract int getPathOperations()
```


路径形状组合的操作（布尔运算）。

**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


获取或设置决定形状是否闭合的属性。

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


获取或设置决定形状是否闭合的属性。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public abstract void setItems(BezierKnotRecord[] bezierPoints)
```


分配 Bexier 节点数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | 贝塞尔节点数组 |

### setPathOperations(int value) {#setPathOperations-int-}
```
public abstract void setPathOperations(int value)
```


路径形状组合的操作（布尔运算）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

