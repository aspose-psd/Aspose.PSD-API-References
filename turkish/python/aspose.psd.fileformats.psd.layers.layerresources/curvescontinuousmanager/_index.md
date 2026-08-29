---
title: "CurvesContinuousManager Sınıfı"
type: docs
weight: 200
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates curves

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesContinuousManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [CurvesContinuousManager(max_channel_count)](#CurvesContinuousManager_max_channel_count_1) | Yeni bir [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Maksimum kanal sayısını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_curve_point(channel_index, x, y)](#add_curve_point_channel_index_x_y_1) | Eğri noktasını ekler. |
| [get_curve_point_by_index(channel_index, point_index)](#get_curve_point_by_index_channel_index_point_index_2) | Eğri noktasını indeks ile alır. |
| [get_curve_point_count(channel_index)](#get_curve_point_count_channel_index_3) | Eğri nokta sayısını alır. |
| [remove_curve_point(channel_index, point_index)](#remove_curve_point_channel_index_point_index_4) | Eğri noktasını kaldırır. |
| [update_curve_point(channel_index, point_index, x, y)](#update_curve_point_channel_index_point_index_x_y_5) | Eğri noktasını günceller. |


### Constructor: CurvesContinuousManager(max_channel_count) {#CurvesContinuousManager_max_channel_count_1}


```
 CurvesContinuousManager(max_channel_count) 
```

Yeni bir [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| max_channel_count | int | Maksimum kanal sayısı. |

### Method: add_curve_point(channel_index, x, y) {#add_curve_point_channel_index_x_y_1}


```
 add_curve_point(channel_index, x, y) 
```

Eğri noktasını ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| channel_index | int | Kanalın indeksi. |
| x | byte | x konumu. |
| y | byte | y konumu. |

### Method: get_curve_point_by_index(channel_index, point_index) {#get_curve_point_by_index_channel_index_point_index_2}


```
 get_curve_point_by_index(channel_index, point_index) 
```

Eğri noktasını indeks ile alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| channel_index | int | Kanalın indeksi. |
| point_index | int | Noktanın indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Kanal indeksine göre eğri noktası |


### Method: get_curve_point_count(channel_index) {#get_curve_point_count_channel_index_3}


```
 get_curve_point_count(channel_index) 
```

Eğri nokta sayısını alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| channel_index | int | Kanalın indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Kanal içindeki eğri nokta sayısı |


### Method: remove_curve_point(channel_index, point_index) {#remove_curve_point_channel_index_point_index_4}


```
 remove_curve_point(channel_index, point_index) 
```

Eğri noktasını kaldırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| channel_index | int | Kanalın indeksi. |
| point_index | int | Noktanın indeksi. |

### Method: update_curve_point(channel_index, point_index, x, y) {#update_curve_point_channel_index_point_index_x_y_5}


```
 update_curve_point(channel_index, point_index, x, y) 
```

Eğri noktasını günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| channel_index | int | Kanalın indeksi. |
| point_index | int | Noktanın indeksi. |
| x | byte | x konumu. |
| y | byte | y konumu. |

