---
title: "CurvesContinuousManager Κλάση"
type: docs
weight: 200
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates curves

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesContinuousManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [CurvesContinuousManager(max_channel_count)](#CurvesContinuousManager_max_channel_count_1) | Αρχικοποιεί μια νέα παρουσία του [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) κλάσης. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Λαμβάνει το μέγιστο πλήθος καναλιών. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [add_curve_point(channel_index, x, y)](#add_curve_point_channel_index_x_y_1) | Προσθέτει το σημείο της καμπύλης. |
| [get_curve_point_by_index(channel_index, point_index)](#get_curve_point_by_index_channel_index_point_index_2) | Λαμβάνει το σημείο της καμπύλης με βάση το δείκτη. |
| [get_curve_point_count(channel_index)](#get_curve_point_count_channel_index_3) | Λαμβάνει το πλήθος σημείων της καμπύλης. |
| [remove_curve_point(channel_index, point_index)](#remove_curve_point_channel_index_point_index_4) | Αφαιρεί το σημείο της καμπύλης. |
| [update_curve_point(channel_index, point_index, x, y)](#update_curve_point_channel_index_point_index_x_y_5) | Ενημερώνει το σημείο της καμπύλης. |


### Constructor: CurvesContinuousManager(max_channel_count) {#CurvesContinuousManager_max_channel_count_1}


```
 CurvesContinuousManager(max_channel_count) 
```

Αρχικοποιεί μια νέα παρουσία του [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) κλάσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| max_channel_count | int | Το μέγιστο πλήθος καναλιών. |

### Method: add_curve_point(channel_index, x, y) {#add_curve_point_channel_index_x_y_1}


```
 add_curve_point(channel_index, x, y) 
```

Προσθέτει το σημείο της καμπύλης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| channel_index | int | Δείκτης του καναλιού. |
| x | byte | Η θέση x. |
| y | byte | Η θέση y. |

### Method: get_curve_point_by_index(channel_index, point_index) {#get_curve_point_by_index_channel_index_point_index_2}


```
 get_curve_point_by_index(channel_index, point_index) 
```

Λαμβάνει το σημείο της καμπύλης με βάση το δείκτη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| channel_index | int | Δείκτης του καναλιού. |
| point_index | int | Δείκτης του σημείου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Σημείο καμπύλης με δείκτη καναλιού |


### Method: get_curve_point_count(channel_index) {#get_curve_point_count_channel_index_3}


```
 get_curve_point_count(channel_index) 
```

Λαμβάνει το πλήθος σημείων της καμπύλης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| channel_index | int | Δείκτης του καναλιού. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Πλήθος σημείων καμπύλης στο κανάλι |


### Method: remove_curve_point(channel_index, point_index) {#remove_curve_point_channel_index_point_index_4}


```
 remove_curve_point(channel_index, point_index) 
```

Αφαιρεί το σημείο της καμπύλης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| channel_index | int | Δείκτης του καναλιού. |
| point_index | int | Δείκτης του σημείου. |

### Method: update_curve_point(channel_index, point_index, x, y) {#update_curve_point_channel_index_point_index_x_y_5}


```
 update_curve_point(channel_index, point_index, x, y) 
```

Ενημερώνει το σημείο της καμπύλης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| channel_index | int | Δείκτης του καναλιού. |
| point_index | int | Δείκτης του σημείου. |
| x | byte | Η θέση x. |
| y | byte | Η θέση y. |

