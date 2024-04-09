---
title: CurvesContinuousManager Class
type: docs
weight: 160
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates curves

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesContinuousManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.2.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CurvesContinuousManager(max_channel_count)](#CurvesContinuousManager_max_channel_count_1) | Initializes a new instance of the [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Gets the maximum channel count. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_curve_point(channel_index, x, y)](#add_curve_point_channel_index_x_y_1) | Adds the point of curve. |
| [get_curve_point_by_index(channel_index, point_index)](#get_curve_point_by_index_channel_index_point_index_2) | Gets the curve point by index. |
| [get_curve_point_count(channel_index)](#get_curve_point_count_channel_index_3) | Gets the curve point count. |
| [remove_curve_point(channel_index, point_index)](#remove_curve_point_channel_index_point_index_4) | Removes the point of curve. |
| [update_curve_point(channel_index, point_index, x, y)](#update_curve_point_channel_index_point_index_x_y_5) | Updates the point of curve. |


### Constructor: CurvesContinuousManager(max_channel_count) {#CurvesContinuousManager_max_channel_count_1}


```
 CurvesContinuousManager(max_channel_count) 
```

Initializes a new instance of the [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| max_channel_count | int | The maximum channel count. |

### Method: add_curve_point(channel_index, x, y) {#add_curve_point_channel_index_x_y_1}


```
 add_curve_point(channel_index, x, y) 
```

Adds the point of curve.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| channel_index | int | Index of the channel. |
| x | byte | The x location. |
| y | byte | The y location. |

### Method: get_curve_point_by_index(channel_index, point_index) {#get_curve_point_by_index_channel_index_point_index_2}


```
 get_curve_point_by_index(channel_index, point_index) 
```

Gets the curve point by index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| channel_index | int | Index of the channel. |
| point_index | int | Index of the point. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Curve point by index of channel |


### Method: get_curve_point_count(channel_index) {#get_curve_point_count_channel_index_3}


```
 get_curve_point_count(channel_index) 
```

Gets the curve point count.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| channel_index | int | Index of the channel. |

**Returns**

| Type | Description |
| :- | :- |
| int | Count of Curve Point in channel |


### Method: remove_curve_point(channel_index, point_index) {#remove_curve_point_channel_index_point_index_4}


```
 remove_curve_point(channel_index, point_index) 
```

Removes the point of curve.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| channel_index | int | Index of the channel. |
| point_index | int | Index of the point. |

### Method: update_curve_point(channel_index, point_index, x, y) {#update_curve_point_channel_index_point_index_x_y_5}


```
 update_curve_point(channel_index, point_index, x, y) 
```

Updates the point of curve.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| channel_index | int | Index of the channel. |
| point_index | int | Index of the point. |
| x | byte | The x location. |
| y | byte | The y location. |

