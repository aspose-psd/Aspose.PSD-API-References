---
title: "Classe CurvesContinuousManager"
type: docs
weight: 200
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates curves

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesContinuousManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CurvesContinuousManager(max_channel_count)](#CurvesContinuousManager_max_channel_count_1) | Initialise une nouvelle instance de la classe [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Obtient le nombre maximal de canaux. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_curve_point(channel_index, x, y)](#add_curve_point_channel_index_x_y_1) | Ajoute le point de la courbe. |
| [get_curve_point_by_index(channel_index, point_index)](#get_curve_point_by_index_channel_index_point_index_2) | Obtient le point de la courbe par indice. |
| [get_curve_point_count(channel_index)](#get_curve_point_count_channel_index_3) | Obtient le nombre de points de la courbe. |
| [remove_curve_point(channel_index, point_index)](#remove_curve_point_channel_index_point_index_4) | Supprime le point de la courbe. |
| [update_curve_point(channel_index, point_index, x, y)](#update_curve_point_channel_index_point_index_x_y_5) | Met à jour le point de la courbe. |


### Constructor: CurvesContinuousManager(max_channel_count) {#CurvesContinuousManager_max_channel_count_1}


```
 CurvesContinuousManager(max_channel_count) 
```

Initialise une nouvelle instance de la classe [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| max_channel_count | int | Le nombre maximal de canaux. |

### Method: add_curve_point(channel_index, x, y) {#add_curve_point_channel_index_x_y_1}


```
 add_curve_point(channel_index, x, y) 
```

Ajoute le point de la courbe.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| channel_index | int | Indice du canal. |
| x | byte | La position x. |
| y | byte | La position y. |

### Method: get_curve_point_by_index(channel_index, point_index) {#get_curve_point_by_index_channel_index_point_index_2}


```
 get_curve_point_by_index(channel_index, point_index) 
```

Obtient le point de la courbe par indice.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| channel_index | int | Indice du canal. |
| point_index | int | Indice du point. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Point de courbe par indice de canal |


### Method: get_curve_point_count(channel_index) {#get_curve_point_count_channel_index_3}


```
 get_curve_point_count(channel_index) 
```

Obtient le nombre de points de la courbe.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| channel_index | int | Indice du canal. |

**Returns**

| Type | Description |
| :- | :- |
| int | Nombre de points de courbe dans le canal |


### Method: remove_curve_point(channel_index, point_index) {#remove_curve_point_channel_index_point_index_4}


```
 remove_curve_point(channel_index, point_index) 
```

Supprime le point de la courbe.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| channel_index | int | Indice du canal. |
| point_index | int | Indice du point. |

### Method: update_curve_point(channel_index, point_index, x, y) {#update_curve_point_channel_index_point_index_x_y_5}


```
 update_curve_point(channel_index, point_index, x, y) 
```

Met à jour le point de la courbe.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| channel_index | int | Indice du canal. |
| point_index | int | Indice du point. |
| x | byte | La position x. |
| y | byte | La position y. |

