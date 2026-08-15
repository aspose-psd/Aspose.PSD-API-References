---
title: "CurvesContinuousManager 클래스"
type: docs
weight: 200
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates curves

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesContinuousManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [CurvesContinuousManager(max_channel_count)](#CurvesContinuousManager_max_channel_count_1) | 새 인스턴스를 초기화합니다 [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| max_channel_count | int | r | 최대 채널 수를 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_curve_point(channel_index, x, y)](#add_curve_point_channel_index_x_y_1) | 곡선의 점을 추가합니다. |
| [get_curve_point_by_index(channel_index, point_index)](#get_curve_point_by_index_channel_index_point_index_2) | 인덱스로 곡선 점을 가져옵니다. |
| [get_curve_point_count(channel_index)](#get_curve_point_count_channel_index_3) | 곡선 점 개수를 가져옵니다. |
| [remove_curve_point(channel_index, point_index)](#remove_curve_point_channel_index_point_index_4) | 곡선의 점을 제거합니다. |
| [update_curve_point(channel_index, point_index, x, y)](#update_curve_point_channel_index_point_index_x_y_5) | 곡선의 점을 업데이트합니다. |


### Constructor: CurvesContinuousManager(max_channel_count) {#CurvesContinuousManager_max_channel_count_1}


```
 CurvesContinuousManager(max_channel_count) 
```

새 인스턴스를 초기화합니다 [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| max_channel_count | int | 최대 채널 수. |

### Method: add_curve_point(channel_index, x, y) {#add_curve_point_channel_index_x_y_1}


```
 add_curve_point(channel_index, x, y) 
```

곡선의 점을 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| channel_index | int | 채널의 인덱스. |
| x | byte | x 위치. |
| y | byte | y 위치. |

### Method: get_curve_point_by_index(channel_index, point_index) {#get_curve_point_by_index_channel_index_point_index_2}


```
 get_curve_point_by_index(channel_index, point_index) 
```

인덱스로 곡선 점을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| channel_index | int | 채널의 인덱스. |
| point_index | int | 점의 인덱스. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | 채널 인덱스로 곡선 점 |


### Method: get_curve_point_count(channel_index) {#get_curve_point_count_channel_index_3}


```
 get_curve_point_count(channel_index) 
```

곡선 점 개수를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| channel_index | int | 채널의 인덱스. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 채널 내 곡선 점 개수 |


### Method: remove_curve_point(channel_index, point_index) {#remove_curve_point_channel_index_point_index_4}


```
 remove_curve_point(channel_index, point_index) 
```

곡선의 점을 제거합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| channel_index | int | 채널의 인덱스. |
| point_index | int | 점의 인덱스. |

### Method: update_curve_point(channel_index, point_index, x, y) {#update_curve_point_channel_index_point_index_x_y_5}


```
 update_curve_point(channel_index, point_index, x, y) 
```

곡선의 점을 업데이트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| channel_index | int | 채널의 인덱스. |
| point_index | int | 점의 인덱스. |
| x | byte | x 위치. |
| y | byte | y 위치. |

