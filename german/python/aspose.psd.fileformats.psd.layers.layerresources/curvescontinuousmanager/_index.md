---
title: "CurvesContinuousManager Klasse"
type: docs
weight: 200
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates curves

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesContinuousManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [CurvesContinuousManager(max_channel_count)](#CurvesContinuousManager_max_channel_count_1) | Initialisiert eine neue Instanz der [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Liefert die maximale Kanalanzahl. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_curve_point(channel_index, x, y)](#add_curve_point_channel_index_x_y_1) | Fügt den Punkt der Kurve hinzu. |
| [get_curve_point_by_index(channel_index, point_index)](#get_curve_point_by_index_channel_index_point_index_2) | Liefert den Kurvenpunkt nach Index. |
| [get_curve_point_count(channel_index)](#get_curve_point_count_channel_index_3) | Liefert die Anzahl der Kurvenpunkte. |
| [remove_curve_point(channel_index, point_index)](#remove_curve_point_channel_index_point_index_4) | Entfernt den Punkt der Kurve. |
| [update_curve_point(channel_index, point_index, x, y)](#update_curve_point_channel_index_point_index_x_y_5) | Aktualisiert den Punkt der Kurve. |


### Constructor: CurvesContinuousManager(max_channel_count) {#CurvesContinuousManager_max_channel_count_1}


```
 CurvesContinuousManager(max_channel_count) 
```

Initialisiert eine neue Instanz der [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| max_channel_count | int | Die maximale Kanalanzahl. |

### Method: add_curve_point(channel_index, x, y) {#add_curve_point_channel_index_x_y_1}


```
 add_curve_point(channel_index, x, y) 
```

Fügt den Punkt der Kurve hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| channel_index | int | Index des Kanals. |
| x | byte | Der x-Standort. |
| y | byte | Der y-Standort. |

### Method: get_curve_point_by_index(channel_index, point_index) {#get_curve_point_by_index_channel_index_point_index_2}


```
 get_curve_point_by_index(channel_index, point_index) 
```

Liefert den Kurvenpunkt nach Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| channel_index | int | Index des Kanals. |
| point_index | int | Index des Punktes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Kurvenpunkt nach Index des Kanals |


### Method: get_curve_point_count(channel_index) {#get_curve_point_count_channel_index_3}


```
 get_curve_point_count(channel_index) 
```

Liefert die Anzahl der Kurvenpunkte.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| channel_index | int | Index des Kanals. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Anzahl der Kurvenpunkte im Kanal |


### Method: remove_curve_point(channel_index, point_index) {#remove_curve_point_channel_index_point_index_4}


```
 remove_curve_point(channel_index, point_index) 
```

Entfernt den Punkt der Kurve.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| channel_index | int | Index des Kanals. |
| point_index | int | Index des Punktes. |

### Method: update_curve_point(channel_index, point_index, x, y) {#update_curve_point_channel_index_point_index_x_y_5}


```
 update_curve_point(channel_index, point_index, x, y) 
```

Aktualisiert den Punkt der Kurve.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| channel_index | int | Index des Kanals. |
| point_index | int | Index des Punktes. |
| x | byte | Der x-Standort. |
| y | byte | Der y-Standort. |

