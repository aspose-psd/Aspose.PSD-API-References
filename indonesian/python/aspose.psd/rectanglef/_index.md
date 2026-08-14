---
title: "Kelas RectangleF"
type: docs
weight: 3830
url: /id/python-net/aspose.psd/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RectangleF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | Menginisialisasi instance baru dari kelas RectangleF |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Menginisialisasi instance baru dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dengan lokasi dan ukuran yang ditentukan. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Menginisialisasi instance baru dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dengan lokasi dan ukuran yang ditentukan. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| bottom | float | r/w | Mendapatkan atau mengatur koordinat y yang merupakan jumlah dari [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/) dan [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) pada struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini. |
| empty [static] | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Mendapatkan instance baru dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang memiliki nilai [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) dan [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) diatur ke nol. |
| height | float | r/w | Mendapatkan atau mengatur tinggi dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini. |
| is_empty | bool | r | Mendapatkan nilai yang menunjukkan apakah properti [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) atau [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) dari [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini memiliki nilai nol. |
| left | float | r/w | Mendapatkan atau mengatur koordinat x dari tepi kiri struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini. |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Mendapatkan atau mengatur koordinat sudut kiri atas dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini. |
| right | float | r/w | Mendapatkan atau mengatur koordinat x yang merupakan jumlah dari [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/) dan [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) pada struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Mendapatkan atau mengatur ukuran dari [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini. |
| top | float | r/w | Mendapatkan atau mengatur koordinat y dari tepi atas struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini. |
| width | float | r/w | Mendapatkan atau mengatur lebar dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini. |
| x | float | r/w | Mendapatkan atau mengatur koordinat x dari sudut kiri atas struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini. |
| y | float | r/w | Mendapatkan atau mengatur koordinat y dari sudut kiri atas struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [contains(point)](#contains_point_1) | Menentukan apakah titik yang ditentukan berada di dalam struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini. |
| [contains(rect)](#contains_rect_2) | Menentukan apakah wilayah persegi panjang yang direpresentasikan oleh <paramref name="rect" /> sepenuhnya berada dalam struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini. |
| [contains(x, y)](#contains_x_y_3) | Menentukan apakah titik yang ditentukan berada di dalam struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_4) | Membuat struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dengan sudut kiri atas dan sudut kanan bawah pada lokasi yang ditentukan. |
| [from_points(point1, point2)](#from_points_point1_point2_5) | Membuat [Rectangle](/psd/python-net/aspose.psd/rectangle/) baru dari dua titik yang ditentukan. Dua sudut dari [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang dibuat akan sama dengan <paramref name="point1" /> dan <paramref name="point2" /> yang diberikan. Ini biasanya merupakan titik-titik berlawanan. |
| [inflate(rect, x, y)](#inflate_rect_x_y_6) | Membuat dan mengembalikan salinan yang diperbesar dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan. Salinan tersebut diperbesar sebesar jumlah yang ditentukan. Persegi panjang asli tetap tidak berubah. |
| [inflate(size)](#inflate_size_7) | Memperbesar [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini sebesar jumlah yang ditentukan. |
| [inflate(x, y)](#inflate_x_y_8) | Memperbesar struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini sebesar jumlah yang ditentukan. |
| [intersect(a, b)](#intersect_a_b_9) | Mengembalikan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili irisan dua persegi panjang. Jika tidak ada irisan, sebuah [RectangleF](/psd/python-net/aspose.psd/rectanglef/) kosong akan dikembalikan. |
| [intersect(rect)](#intersect_rect_10) | Mengganti struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini dengan irisan antara dirinya sendiri dan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan. |
| [intersects_with(rect)](#intersects_with_rect_11) | Menentukan apakah persegi panjang ini berpotongan dengan <paramref name="rect" />. |
| normalize() | Menormalkan persegi panjang dengan membuat lebar dan tingginya positif, kiri lebih kecil dari kanan, dan atas lebih kecil dari bawah. |
| [offset(pos)](#offset_pos_12) | Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan. |
| [offset(x, y)](#offset_x_y_13) | Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan. |
| [union(a, b)](#union_a_b_14) | Membuat persegi panjang ketiga terkecil yang dapat menampung kedua persegi panjang yang membentuk sebuah gabungan. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

Menginisialisasi instance baru dari kelas RectangleF

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Menginisialisasi instance baru dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dengan lokasi dan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | Sebuah [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili sudut kiri atas wilayah persegi panjang. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Sebuah [SizeF](/psd/python-net/aspose.psd/sizef/) yang mewakili lebar dan tinggi wilayah persegi panjang. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Menginisialisasi instance baru dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dengan lokasi dan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | float | Koordinat x dari sudut kiri atas persegi panjang. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang. |
| width | float | Lebar persegi panjang. |
| tinggi | float | Tinggi persegi panjang. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Menentukan apakah titik yang ditentukan berada di dalam struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) untuk diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang direpresentasikan oleh parameter <paramref name="point" /> berada dalam struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini; jika tidak false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Menentukan apakah wilayah persegi panjang yang direpresentasikan oleh <paramref name="rect" /> sepenuhnya berada dalam struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) untuk diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika wilayah persegi panjang yang direpresentasikan oleh <paramref name="rect" /> sepenuhnya berada dalam wilayah persegi panjang yang direpresentasikan oleh [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini; jika tidak false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Menentukan apakah titik yang ditentukan berada di dalam struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang didefinisikan oleh <paramref name="x" /> dan <paramref name="y" /> berada di dalam struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini; jika tidak false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_4}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Membuat struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dengan sudut kiri atas dan sudut kanan bawah pada lokasi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| kiri | float | Koordinat x dari sudut kiri atas wilayah persegi panjang. |
| atas | float | Koordinat y dari sudut kiri atas wilayah persegi panjang. |
| kanan | float | Koordinat x dari sudut kanan bawah wilayah persegi panjang. |
| bawah | float | Koordinat y dari sudut kanan bawah wilayah persegi panjang. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) baru yang dibuat oleh metode ini. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_5}


```
 from_points(point1, point2) 
```

Membuat [Rectangle](/psd/python-net/aspose.psd/rectangle/) baru dari dua titik yang ditentukan. Dua sudut dari [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang dibuat akan sama dengan <paramref name="point1" /> dan <paramref name="point2" /> yang diberikan. Ini biasanya merupakan titik-titik berlawanan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) pertama untuk persegi panjang baru. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) kedua untuk persegi panjang baru. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang baru dibuat. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_6}


```
 inflate(rect, x, y) 
```

Membuat dan mengembalikan salinan yang diperbesar dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan. Salinan tersebut diperbesar sebesar jumlah yang ditentukan. Persegi panjang asli tetap tidak berubah.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang akan disalin. Persegi panjang ini tidak dimodifikasi. |
| x | float | Jumlah untuk memperluas salinan persegi panjang secara horizontal. |
| y | float | Jumlah untuk memperluas salinan persegi panjang secara vertikal. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang diperluas. |


### Method: inflate(size) {#inflate_size_7}


```
 inflate(size) 
```

Memperbesar [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini sebesar jumlah yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Jumlah untuk memperluas persegi panjang ini. |

### Method: inflate(x, y) {#inflate_x_y_8}


```
 inflate(x, y) 
```

Memperbesar struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini sebesar jumlah yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | float | Jumlah untuk memperluas struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini secara horizontal. |
| y | float | Jumlah untuk memperluas struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini secara vertikal. |

### Method: intersect(a, b)  [static] {#intersect_a_b_9}


```
 intersect(a, b) 
```

Mengembalikan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili irisan dua persegi panjang. Jika tidak ada irisan, sebuah [RectangleF](/psd/python-net/aspose.psd/rectanglef/) kosong akan dikembalikan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Persegi panjang pertama untuk diinterseksi. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Persegi panjang kedua untuk diinterseksi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ketiga yang ukurannya mewakili area tumpang tindih dari dua persegi panjang yang ditentukan. |


### Method: intersect(rect) {#intersect_rect_10}


```
 intersect(rect) 
```

Mengganti struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ini dengan irisan antara dirinya sendiri dan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Persegi panjang untuk diinterseksi. |

### Method: intersects_with(rect) {#intersects_with_rect_11}


```
 intersects_with(rect) 
```

Menentukan apakah persegi panjang ini berpotongan dengan <paramref name="rect" />.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Persegi panjang untuk diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika ada interseksi apa pun. |


### Method: offset(pos) {#offset_pos_12}


```
 offset(pos) 
```

Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pos | [PointF](/psd/python-net/aspose.psd/pointf) | Jumlah untuk menggeser lokasi. |

### Method: offset(x, y) {#offset_x_y_13}


```
 offset(x, y) 
```

Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | float | Jumlah untuk menggeser lokasi secara horizontal. |
| y | float | Jumlah untuk menggeser lokasi secara vertikal. |

### Method: union(a, b)  [static] {#union_a_b_14}


```
 union(a, b) 
```

Membuat persegi panjang ketiga terkecil yang dapat menampung kedua persegi panjang yang membentuk sebuah gabungan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Sebuah persegi panjang pertama untuk digabungkan. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Sebuah persegi panjang kedua untuk digabungkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ketiga yang berisi kedua persegi panjang yang membentuk gabungan. |


