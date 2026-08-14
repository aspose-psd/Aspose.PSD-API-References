---
title: "Kelas Point"
type: docs
weight: 3530
url: /id/python-net/aspose.psd/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Point

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Point()](#Point__1) | Menginisialisasi instance baru dari kelas Point |
| [Point(dw)](#Point_dw_2) | Menginisialisasi instance baru dari struktur [Point](/psd/python-net/aspose.psd/point/) menggunakan koordinat yang ditentukan oleh nilai integer. |
| [Point(size)](#Point_size_3) | Menginisialisasi instance baru dari struktur [Point](/psd/python-net/aspose.psd/point/) dari struktur [Size](/psd/python-net/aspose.psd/size/). |
| [Point(x, y)](#Point_x_y_4) | Menginisialisasi instance baru dari struktur [Point](/psd/python-net/aspose.psd/point/) dengan koordinat yang ditentukan. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| empty [static] | [Point](/psd/python-net/aspose.psd/point) | r | Mendapatkan instance baru dari struktur [Point](/psd/python-net/aspose.psd/point/) yang memiliki nilai [Point.x](/psd/python-net/aspose.psd/point/) dan [Point.y](/psd/python-net/aspose.psd/point/) diatur ke nol. |
| is_empty | bool | r | Mendapatkan nilai yang menunjukkan apakah [Point](/psd/python-net/aspose.psd/point/) ini kosong. |
| x | int | r/w | Mendapatkan atau mengatur koordinat x dari [Point](/psd/python-net/aspose.psd/point/) ini. |
| y | int | r/w | Mendapatkan atau mengatur koordinat y dari [Point](/psd/python-net/aspose.psd/point/) ini. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Menambahkan [Size](/psd/python-net/aspose.psd/size/) yang ditentukan ke [Point](/psd/python-net/aspose.psd/point/) yang ditentukan. |
| [ceiling(point)](#ceiling_point_2) | Mengonversi [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan menjadi [Point](/psd/python-net/aspose.psd/point/) dengan membulatkan nilai [PointF](/psd/python-net/aspose.psd/pointf/) ke nilai integer berikutnya yang lebih tinggi. |
| [offset(dx, dy)](#offset_dx_dy_3) | Mentranslasi [Point](/psd/python-net/aspose.psd/point/) ini dengan jumlah yang ditentukan. |
| [offset(point)](#offset_point_4) | Mentranslasi [Point](/psd/python-net/aspose.psd/point/) ini dengan [Point](/psd/python-net/aspose.psd/point/) yang ditentukan. |
| [round(point)](#round_point_5) | Mengonversi [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan menjadi objek [Point](/psd/python-net/aspose.psd/point/) dengan membulatkan nilai [Point](/psd/python-net/aspose.psd/point/) ke integer terdekat. |
| [subtract(point, size)](#subtract_point_size_6) | Mengembalikan hasil pengurangan [Size](/psd/python-net/aspose.psd/size/) yang ditentukan dari [Point](/psd/python-net/aspose.psd/point/) yang ditentukan. |
| [truncate(point)](#truncate_point_7) | Mengonversi [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan menjadi [Point](/psd/python-net/aspose.psd/point/) dengan memotong nilai [Point](/psd/python-net/aspose.psd/point/). |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Menginisialisasi instance baru dari kelas Point

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Menginisialisasi instance baru dari struktur [Point](/psd/python-net/aspose.psd/point/) menggunakan koordinat yang ditentukan oleh nilai integer.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dw | int | Integer 32-bit yang menentukan koordinat untuk titik baru. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

Menginisialisasi instance baru dari struktur [Point](/psd/python-net/aspose.psd/point/) dari struktur [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | Berisi koordinat titik baru. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Menginisialisasi instance baru dari struktur [Point](/psd/python-net/aspose.psd/point/) dengan koordinat yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | int | Posisi horizontal titik. |
| y | int | Posisi vertikal titik. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Menambahkan [Size](/psd/python-net/aspose.psd/size/) yang ditentukan ke [Point](/psd/python-net/aspose.psd/point/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) yang akan ditambahkan ke. |
| size | [Size](/psd/python-net/aspose.psd/size) | [Size](/psd/python-net/aspose.psd/size/) untuk ditambahkan ke <paramref name="point" />. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) yang merupakan hasil operasi penjumlahan. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Mengonversi [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan menjadi [Point](/psd/python-net/aspose.psd/point/) dengan membulatkan nilai [PointF](/psd/python-net/aspose.psd/pointf/) ke nilai integer berikutnya yang lebih tinggi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) yang akan dikonversi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) yang dikonversi oleh metode ini. |


### Method: offset(dx, dy) {#offset_dx_dy_3}


```
 offset(dx, dy) 
```

Mentranslasi [Point](/psd/python-net/aspose.psd/point/) ini dengan jumlah yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dx | int | Jumlah untuk menggeser koordinat x. |
| dy | int | Jumlah untuk menggeser koordinat y. |

### Method: offset(point) {#offset_point_4}


```
 offset(point) 
```

Mentranslasi [Point](/psd/python-net/aspose.psd/point/) ini dengan [Point](/psd/python-net/aspose.psd/point/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) yang digunakan untuk menggeser [Point](/psd/python-net/aspose.psd/point/) ini. |

### Method: round(point)  [static] {#round_point_5}


```
 round(point) 
```

Mengonversi [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan menjadi objek [Point](/psd/python-net/aspose.psd/point/) dengan membulatkan nilai [Point](/psd/python-net/aspose.psd/point/) ke integer terdekat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) yang akan dikonversi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) yang dikonversi oleh metode ini. |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

Mengembalikan hasil pengurangan [Size](/psd/python-net/aspose.psd/size/) yang ditentukan dari [Point](/psd/python-net/aspose.psd/point/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) yang akan dikurangkan dari. |
| size | [Size](/psd/python-net/aspose.psd/size) | [Size](/psd/python-net/aspose.psd/size/) untuk dikurangkan dari <paramref name="point" />. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) yang merupakan hasil operasi pengurangan. |


### Method: truncate(point)  [static] {#truncate_point_7}


```
 truncate(point) 
```

Mengonversi [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan menjadi [Point](/psd/python-net/aspose.psd/point/) dengan memotong nilai [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) yang akan dikonversi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) yang dikonversi oleh metode ini. |


