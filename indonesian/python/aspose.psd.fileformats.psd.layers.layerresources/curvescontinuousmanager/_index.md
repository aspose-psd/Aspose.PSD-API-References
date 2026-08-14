---
title: "Kelas CurvesContinuousManager"
type: docs
weight: 200
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates curves

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesContinuousManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [CurvesContinuousManager(max_channel_count)](#CurvesContinuousManager_max_channel_count_1) | Menginisialisasi sebuah instance baru dari kelas [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Mendapatkan jumlah saluran maksimum. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_curve_point(channel_index, x, y)](#add_curve_point_channel_index_x_y_1) | Menambahkan titik kurva. |
| [get_curve_point_by_index(channel_index, point_index)](#get_curve_point_by_index_channel_index_point_index_2) | Mendapatkan titik kurva berdasarkan indeks. |
| [get_curve_point_count(channel_index)](#get_curve_point_count_channel_index_3) | Mendapatkan jumlah titik kurva. |
| [remove_curve_point(channel_index, point_index)](#remove_curve_point_channel_index_point_index_4) | Menghapus titik kurva. |
| [update_curve_point(channel_index, point_index, x, y)](#update_curve_point_channel_index_point_index_x_y_5) | Memperbarui titik kurva. |


### Constructor: CurvesContinuousManager(max_channel_count) {#CurvesContinuousManager_max_channel_count_1}


```
 CurvesContinuousManager(max_channel_count) 
```

Menginisialisasi sebuah instance baru dari kelas [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| max_channel_count | int | Jumlah saluran maksimum. |

### Method: add_curve_point(channel_index, x, y) {#add_curve_point_channel_index_x_y_1}


```
 add_curve_point(channel_index, x, y) 
```

Menambahkan titik kurva.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| channel_index | int | Indeks saluran. |
| x | byte | Lokasi x. |
| y | byte | Lokasi y. |

### Method: get_curve_point_by_index(channel_index, point_index) {#get_curve_point_by_index_channel_index_point_index_2}


```
 get_curve_point_by_index(channel_index, point_index) 
```

Mendapatkan titik kurva berdasarkan indeks.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| channel_index | int | Indeks saluran. |
| point_index | int | Indeks titik. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Titik kurva berdasarkan indeks saluran |


### Method: get_curve_point_count(channel_index) {#get_curve_point_count_channel_index_3}


```
 get_curve_point_count(channel_index) 
```

Mendapatkan jumlah titik kurva.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| channel_index | int | Indeks saluran. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Jumlah Titik Kurva dalam saluran |


### Method: remove_curve_point(channel_index, point_index) {#remove_curve_point_channel_index_point_index_4}


```
 remove_curve_point(channel_index, point_index) 
```

Menghapus titik kurva.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| channel_index | int | Indeks saluran. |
| point_index | int | Indeks titik. |

### Method: update_curve_point(channel_index, point_index, x, y) {#update_curve_point_channel_index_point_index_x_y_5}


```
 update_curve_point(channel_index, point_index, x, y) 
```

Memperbarui titik kurva.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| channel_index | int | Indeks saluran. |
| point_index | int | Indeks titik. |
| x | byte | Lokasi x. |
| y | byte | Lokasi y. |

