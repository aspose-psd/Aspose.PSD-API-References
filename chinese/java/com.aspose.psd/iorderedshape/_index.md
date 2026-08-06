---
title: "IOrderedShape"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示有序形状。"
type: docs
weight: 129
url: /zh/java/com.aspose.psd/iorderedshape/
---
```
public interface IOrderedShape
```

表示有序形状。有序形状是一组连续的点，具有起始点和结束点。该连续点集使用特定规则连接。
## Methods

| Method | 描述 |
| --- | --- |
| [getEndPoint()](#getEndPoint--) | 获取结束形状点。 |
| [getStartPoint()](#getStartPoint--) | 获取起始形状点。 |
| [isClosed()](#isClosed--) | 获取指示有序形状是否闭合的值。 |
| [reverse()](#reverse--) | 反转此形状的点顺序。 |
| [setClosed(boolean value)](#setClosed-boolean-) | 设置指示有序形状是否闭合的值。 |
### getEndPoint() {#getEndPoint--}
```
public abstract PointF getEndPoint()
```


获取结束形状点。

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The ending shape point.
### getStartPoint() {#getStartPoint--}
```
public abstract PointF getStartPoint()
```


获取起始形状点。

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The starting shape point.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


获取指示有序形状是否闭合的值。处理闭合有序形状时，起始点和结束点没有意义。

**Returns:**
boolean -  true  如果此有序形状闭合；否则，  false 。
### reverse() {#reverse--}
```
public abstract void reverse()
```


反转此形状的点顺序。

### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


设置指示有序形状是否闭合的值。处理闭合有序形状时，起始点和结束点没有意义。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | true  如果此有序形状闭合；否则，  false 。 |

