---
title: "CurvesContinuousManager क्लास"
type: docs
weight: 200
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates curves

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesContinuousManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [CurvesContinuousManager(max_channel_count)](#CurvesContinuousManager_max_channel_count_1) | नया उदाहरण प्रारंभ करता है [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| max_channel_count | int | r | अधिकतम चैनल गिनती प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [add_curve_point(channel_index, x, y)](#add_curve_point_channel_index_x_y_1) | वक्र का बिंदु जोड़ता है। |
| [get_curve_point_by_index(channel_index, point_index)](#get_curve_point_by_index_channel_index_point_index_2) | सूचकांक द्वारा वक्र बिंदु प्राप्त करता है। |
| [get_curve_point_count(channel_index)](#get_curve_point_count_channel_index_3) | वक्र बिंदु गिनती प्राप्त करता है। |
| [remove_curve_point(channel_index, point_index)](#remove_curve_point_channel_index_point_index_4) | वक्र का बिंदु हटाता है। |
| [update_curve_point(channel_index, point_index, x, y)](#update_curve_point_channel_index_point_index_x_y_5) | वक्र का बिंदु अद्यतन करता है। |


### Constructor: CurvesContinuousManager(max_channel_count) {#CurvesContinuousManager_max_channel_count_1}


```
 CurvesContinuousManager(max_channel_count) 
```

नया उदाहरण प्रारंभ करता है [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| max_channel_count | int | अधिकतम चैनल गिनती। |

### Method: add_curve_point(channel_index, x, y) {#add_curve_point_channel_index_x_y_1}


```
 add_curve_point(channel_index, x, y) 
```

वक्र का बिंदु जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| channel_index | int | चैनल का सूचकांक। |
| x | byte | x स्थान। |
| y | byte | y स्थान। |

### Method: get_curve_point_by_index(channel_index, point_index) {#get_curve_point_by_index_channel_index_point_index_2}


```
 get_curve_point_by_index(channel_index, point_index) 
```

सूचकांक द्वारा वक्र बिंदु प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| channel_index | int | चैनल का सूचकांक। |
| point_index | int | बिंदु का सूचकांक। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | चैनल के सूचकांक द्वारा वक्र बिंदु |


### Method: get_curve_point_count(channel_index) {#get_curve_point_count_channel_index_3}


```
 get_curve_point_count(channel_index) 
```

वक्र बिंदु गिनती प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| channel_index | int | चैनल का सूचकांक। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | चैनल में वक्र बिंदु की गिनती |


### Method: remove_curve_point(channel_index, point_index) {#remove_curve_point_channel_index_point_index_4}


```
 remove_curve_point(channel_index, point_index) 
```

वक्र का बिंदु हटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| channel_index | int | चैनल का सूचकांक। |
| point_index | int | बिंदु का सूचकांक। |

### Method: update_curve_point(channel_index, point_index, x, y) {#update_curve_point_channel_index_point_index_x_y_5}


```
 update_curve_point(channel_index, point_index, x, y) 
```

वक्र का बिंदु अद्यतन करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| channel_index | int | चैनल का सूचकांक। |
| point_index | int | बिंदु का सूचकांक। |
| x | byte | x स्थान। |
| y | byte | y स्थान। |

