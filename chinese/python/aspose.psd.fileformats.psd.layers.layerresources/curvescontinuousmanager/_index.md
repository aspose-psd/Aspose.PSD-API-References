---
title: "CurvesContinuousManager 类"
type: docs
weight: 200
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates curves

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesContinuousManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CurvesContinuousManager(max_channel_count)](#CurvesContinuousManager_max_channel_count_1) | 初始化一个新的 [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| max_channel_count | int | r | 获取最大通道数。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_curve_point(channel_index, x, y)](#add_curve_point_channel_index_x_y_1) | 添加曲线的点。 |
| [get_curve_point_by_index(channel_index, point_index)](#get_curve_point_by_index_channel_index_point_index_2) | 按索引获取曲线点。 |
| [get_curve_point_count(channel_index)](#get_curve_point_count_channel_index_3) | 获取曲线点的计数。 |
| [remove_curve_point(channel_index, point_index)](#remove_curve_point_channel_index_point_index_4) | 移除曲线的点。 |
| [update_curve_point(channel_index, point_index, x, y)](#update_curve_point_channel_index_point_index_x_y_5) | 更新曲线的点。 |


### Constructor: CurvesContinuousManager(max_channel_count) {#CurvesContinuousManager_max_channel_count_1}


```
 CurvesContinuousManager(max_channel_count) 
```

初始化一个新的 [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) 类的实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| max_channel_count | int | 最大通道数。 |

### Method: add_curve_point(channel_index, x, y) {#add_curve_point_channel_index_x_y_1}


```
 add_curve_point(channel_index, x, y) 
```

添加曲线的点。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| channel_index | int | 通道的索引。 |
| x | byte | x 位置。 |
| y | byte | y 位置。 |

### Method: get_curve_point_by_index(channel_index, point_index) {#get_curve_point_by_index_channel_index_point_index_2}


```
 get_curve_point_by_index(channel_index, point_index) 
```

按索引获取曲线点。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| channel_index | int | 通道的索引。 |
| point_index | int | 点的索引。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | 按通道索引的曲线点 |


### Method: get_curve_point_count(channel_index) {#get_curve_point_count_channel_index_3}


```
 get_curve_point_count(channel_index) 
```

获取曲线点的计数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| channel_index | int | 通道的索引。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 通道中曲线点的计数 |


### Method: remove_curve_point(channel_index, point_index) {#remove_curve_point_channel_index_point_index_4}


```
 remove_curve_point(channel_index, point_index) 
```

移除曲线的点。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| channel_index | int | 通道的索引。 |
| point_index | int | 点的索引。 |

### Method: update_curve_point(channel_index, point_index, x, y) {#update_curve_point_channel_index_point_index_x_y_5}


```
 update_curve_point(channel_index, point_index, x, y) 
```

更新曲线的点。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| channel_index | int | 通道的索引。 |
| point_index | int | 点的索引。 |
| x | byte | x 位置。 |
| y | byte | y 位置。 |

