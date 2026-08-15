---
title: "CurvesContinuousManager klass"
type: docs
weight: 200
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates curves

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesContinuousManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [CurvesContinuousManager(max_channel_count)](#CurvesContinuousManager_max_channel_count_1) | Initierar en ny instans av [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Hämtar det maximala kanalantalet. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_curve_point(channel_index, x, y)](#add_curve_point_channel_index_x_y_1) | Lägger till kurvans punkt. |
| [get_curve_point_by_index(channel_index, point_index)](#get_curve_point_by_index_channel_index_point_index_2) | Hämtar kurvpunkten efter index. |
| [get_curve_point_count(channel_index)](#get_curve_point_count_channel_index_3) | Hämtar antalet kurvpunkter. |
| [remove_curve_point(channel_index, point_index)](#remove_curve_point_channel_index_point_index_4) | Tar bort kurvpunkten. |
| [update_curve_point(channel_index, point_index, x, y)](#update_curve_point_channel_index_point_index_x_y_5) | Uppdaterar kurvpunkten. |


### Constructor: CurvesContinuousManager(max_channel_count) {#CurvesContinuousManager_max_channel_count_1}


```
 CurvesContinuousManager(max_channel_count) 
```

Initierar en ny instans av [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| max_channel_count | int | Det maximala kanalantalet. |

### Method: add_curve_point(channel_index, x, y) {#add_curve_point_channel_index_x_y_1}


```
 add_curve_point(channel_index, x, y) 
```

Lägger till kurvans punkt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| channel_index | int | Kanalens index. |
| x | byte | x‑positionen. |
| y | byte | y‑positionen. |

### Method: get_curve_point_by_index(channel_index, point_index) {#get_curve_point_by_index_channel_index_point_index_2}


```
 get_curve_point_by_index(channel_index, point_index) 
```

Hämtar kurvpunkten efter index.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| channel_index | int | Kanalens index. |
| point_index | int | Index för punkten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Kurvpunkt efter kanalens index |


### Method: get_curve_point_count(channel_index) {#get_curve_point_count_channel_index_3}


```
 get_curve_point_count(channel_index) 
```

Hämtar antalet kurvpunkter.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| channel_index | int | Kanalens index. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Antal kurvpunkter i kanal |


### Method: remove_curve_point(channel_index, point_index) {#remove_curve_point_channel_index_point_index_4}


```
 remove_curve_point(channel_index, point_index) 
```

Tar bort kurvpunkten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| channel_index | int | Kanalens index. |
| point_index | int | Index för punkten. |

### Method: update_curve_point(channel_index, point_index, x, y) {#update_curve_point_channel_index_point_index_x_y_5}


```
 update_curve_point(channel_index, point_index, x, y) 
```

Uppdaterar kurvpunkten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| channel_index | int | Kanalens index. |
| point_index | int | Index för punkten. |
| x | byte | x‑positionen. |
| y | byte | y‑positionen. |

