---
title: "فئة CurvesContinuousManager"
type: docs
weight: 200
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates curves

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesContinuousManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [CurvesContinuousManager(max_channel_count)](#CurvesContinuousManager_max_channel_count_1) | يقوم بتهيئة نسخة جديدة من الفئة [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| max_channel_count | int | r | يحصل على الحد الأقصى لعدد القنوات. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_curve_point(channel_index, x, y)](#add_curve_point_channel_index_x_y_1) | يضيف نقطة المنحنى. |
| [get_curve_point_by_index(channel_index, point_index)](#get_curve_point_by_index_channel_index_point_index_2) | يحصل على نقطة المنحنى حسب الفهرس. |
| [get_curve_point_count(channel_index)](#get_curve_point_count_channel_index_3) | يحصل على عدد نقاط المنحنى. |
| [remove_curve_point(channel_index, point_index)](#remove_curve_point_channel_index_point_index_4) | يزيل نقطة المنحنى. |
| [update_curve_point(channel_index, point_index, x, y)](#update_curve_point_channel_index_point_index_x_y_5) | يحدّث نقطة المنحنى. |


### Constructor: CurvesContinuousManager(max_channel_count) {#CurvesContinuousManager_max_channel_count_1}


```
 CurvesContinuousManager(max_channel_count) 
```

يقوم بتهيئة نسخة جديدة من الفئة [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| max_channel_count | int | الحد الأقصى لعدد القنوات. |

### Method: add_curve_point(channel_index, x, y) {#add_curve_point_channel_index_x_y_1}


```
 add_curve_point(channel_index, x, y) 
```

يضيف نقطة المنحنى.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| channel_index | int | فهرس القناة. |
| x | byte | الموقع x. |
| y | byte | الموقع y. |

### Method: get_curve_point_by_index(channel_index, point_index) {#get_curve_point_by_index_channel_index_point_index_2}


```
 get_curve_point_by_index(channel_index, point_index) 
```

يحصل على نقطة المنحنى حسب الفهرس.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| channel_index | int | فهرس القناة. |
| point_index | int | فهرس النقطة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | نقطة المنحنى حسب فهرس القناة |


### Method: get_curve_point_count(channel_index) {#get_curve_point_count_channel_index_3}


```
 get_curve_point_count(channel_index) 
```

يحصل على عدد نقاط المنحنى.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| channel_index | int | فهرس القناة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | عدد نقاط المنحنى في القناة |


### Method: remove_curve_point(channel_index, point_index) {#remove_curve_point_channel_index_point_index_4}


```
 remove_curve_point(channel_index, point_index) 
```

يزيل نقطة المنحنى.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| channel_index | int | فهرس القناة. |
| point_index | int | فهرس النقطة. |

### Method: update_curve_point(channel_index, point_index, x, y) {#update_curve_point_channel_index_point_index_x_y_5}


```
 update_curve_point(channel_index, point_index, x, y) 
```

يحدّث نقطة المنحنى.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| channel_index | int | فهرس القناة. |
| point_index | int | فهرس النقطة. |
| x | byte | الموقع x. |
| y | byte | الموقع y. |

