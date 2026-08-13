---
title: "IPathShape 类"
type: docs
weight: 380
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---

**Summary:** The Shape from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IPathShape

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_closed | bool | 读/写 | 获取或设置决定 Shape 是否闭合的属性。 |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | 用于路径形状组合的操作（布尔运算）。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_items()](#get_items__1) | 获取贝塞尔节点数组。 |
| [set_items(bezier_points)](#set_items_bezier_points_2) | 分配 Bexier 节点数组。 |


### Method: get_items() {#get_items__1}


```
 get_items() 
```

获取贝塞尔节点数组。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | BezierKnotRecord 数组。 |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

分配 Bexier 节点数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | 贝塞尔节点数组 |

