---
title: "CurvesContinuousManager Klasse"
type: docs
weight: 200
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates curves

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesContinuousManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [CurvesContinuousManager(max_channel_count)](#CurvesContinuousManager_max_channel_count_1) | Initialiseert een nieuw exemplaar van de [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Haalt het maximale kanaalaantal op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_curve_point(channel_index, x, y)](#add_curve_point_channel_index_x_y_1) | Voegt het punt van de curve toe. |
| [get_curve_point_by_index(channel_index, point_index)](#get_curve_point_by_index_channel_index_point_index_2) | Haalt het curvepunt op op basis van index. |
| [get_curve_point_count(channel_index)](#get_curve_point_count_channel_index_3) | Haalt het aantal curvepunten op. |
| [remove_curve_point(channel_index, point_index)](#remove_curve_point_channel_index_point_index_4) | Verwijdert het punt van de curve. |
| [update_curve_point(channel_index, point_index, x, y)](#update_curve_point_channel_index_point_index_x_y_5) | Werk het punt van de curve bij. |


### Constructor: CurvesContinuousManager(max_channel_count) {#CurvesContinuousManager_max_channel_count_1}


```
 CurvesContinuousManager(max_channel_count) 
```

Initialiseert een nieuw exemplaar van de [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| max_channel_count | int | Het maximale kanaalaantal. |

### Method: add_curve_point(channel_index, x, y) {#add_curve_point_channel_index_x_y_1}


```
 add_curve_point(channel_index, x, y) 
```

Voegt het punt van de curve toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| channel_index | int | Index van het kanaal. |
| x | byte | De x‑locatie. |
| y | byte | De y‑locatie. |

### Method: get_curve_point_by_index(channel_index, point_index) {#get_curve_point_by_index_channel_index_point_index_2}


```
 get_curve_point_by_index(channel_index, point_index) 
```

Haalt het curvepunt op op basis van index.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| channel_index | int | Index van het kanaal. |
| point_index | int | Index van het punt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Curvepunt op index van kanaal |


### Method: get_curve_point_count(channel_index) {#get_curve_point_count_channel_index_3}


```
 get_curve_point_count(channel_index) 
```

Haalt het aantal curvepunten op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| channel_index | int | Index van het kanaal. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | Aantal curvepunten in kanaal |


### Method: remove_curve_point(channel_index, point_index) {#remove_curve_point_channel_index_point_index_4}


```
 remove_curve_point(channel_index, point_index) 
```

Verwijdert het punt van de curve.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| channel_index | int | Index van het kanaal. |
| point_index | int | Index van het punt. |

### Method: update_curve_point(channel_index, point_index, x, y) {#update_curve_point_channel_index_point_index_x_y_5}


```
 update_curve_point(channel_index, point_index, x, y) 
```

Werk het punt van de curve bij.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| channel_index | int | Index van het kanaal. |
| point_index | int | Index van het punt. |
| x | byte | De x‑locatie. |
| y | byte | De y‑locatie. |

