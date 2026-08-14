---
title: "Kelas Rectangle"
type: docs
weight: 3810
url: /id/python-net/aspose.psd/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Rectangle

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Menginisialisasi instance baru dari kelas Rectangle |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Menginisialisasi instance baru dari struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) dengan lokasi dan ukuran yang ditentukan. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Menginisialisasi instance baru dari struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) dengan lokasi dan ukuran yang ditentukan. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| bottom | int | r/w | Mendapatkan atau mengatur koordinat y yang merupakan jumlah dari nilai properti [Rectangle.y](/psd/python-net/aspose.psd/rectangle/) dan [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) dari struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini. |
| empty [static] | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Mendapatkan instance baru dari struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang memiliki nilai [Rectangle.x](/psd/python-net/aspose.psd/rectangle/), [Rectangle.y](/psd/python-net/aspose.psd/rectangle/), [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) dan [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) diatur ke nol. |
| height | int | r/w | Mendapatkan atau mengatur tinggi dari struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini. |
| is_empty | bool | r | Mendapatkan nilai yang menunjukkan apakah semua properti numerik dari [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini memiliki nilai nol. |
| left | int | r/w | Mendapatkan atau mengatur koordinat x dari tepi kiri struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini. |
| location | [Point](/psd/python-net/aspose.psd/point) | r/w | Mendapatkan atau mengatur koordinat sudut kiri atas dari struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini. |
| right | int | r/w | Mendapatkan atau mengatur koordinat x yang merupakan jumlah nilai properti [Rectangle.x](/psd/python-net/aspose.psd/rectangle/) dan [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) dari struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini. |
| size | [Size](/psd/python-net/aspose.psd/size) | r/w | Mendapatkan atau mengatur ukuran dari [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini. |
| top | int | r/w | Mendapatkan atau mengatur koordinat y dari tepi atas struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini. |
| width | int | r/w | Mendapatkan atau mengatur lebar dari struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini. |
| x | int | r/w | Mendapatkan atau mengatur koordinat x dari sudut kiri atas struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini. |
| y | int | r/w | Mendapatkan atau mengatur koordinat y dari sudut kiri atas struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Mengonversi struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan menjadi struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) dengan membulatkan nilai [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ke nilai integer berikutnya yang lebih tinggi. |
| [contains(point)](#contains_point_2) | Menentukan apakah titik yang ditentukan berada di dalam struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini. |
| [contains(rect)](#contains_rect_3) | Menentukan apakah wilayah persegi panjang yang direpresentasikan oleh <paramref name="rect" /> sepenuhnya berada di dalam struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini. |
| [contains(x, y)](#contains_x_y_4) | Menentukan apakah titik yang ditentukan berada di dalam struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_5) | Membuat struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) dengan lokasi tepi yang ditentukan. |
| [from_points(point1, point2)](#from_points_point1_point2_6) | Membuat [Rectangle](/psd/python-net/aspose.psd/rectangle/) baru dari dua titik yang ditentukan. Dua sisi vertikal dari [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang dibuat akan sama dengan <paramref name="point1" /> dan <paramref name="point2" /> yang diberikan. Ini biasanya merupakan titik berlawanan. |
| [inflate(rect, x, y)](#inflate_rect_x_y_7) | Membuat dan mengembalikan salinan yang diperbesar dari struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang ditentukan. Salinan tersebut diperbesar sebesar jumlah yang ditentukan. Struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) asli tetap tidak berubah. |
| [inflate(size)](#inflate_size_8) | Membesarkan [Rectangle] ini sebesar jumlah yang ditentukan. |
| [inflate(width, height)](#inflate_width_height_9) | Membesarkan [Rectangle] ini sebesar jumlah yang ditentukan. |
| [intersect(a, b)](#intersect_a_b_10) | Mengembalikan struktur [Rectangle] ketiga yang mewakili irisan dari dua struktur [Rectangle] lainnya. Jika tidak ada irisan, sebuah [Rectangle] kosong dikembalikan. |
| [intersect(rect)](#intersect_rect_11) | Mengganti [Rectangle] ini dengan irisan antara dirinya sendiri dan [Rectangle] yang ditentukan. |
| [intersects_with(rect)](#intersects_with_rect_12) | Menentukan apakah persegi panjang ini berpotongan dengan <paramref name="rect" />. |
| normalize() | Menormalkan persegi panjang dengan membuat lebar dan tingginya positif, kiri lebih kecil dari kanan, dan atas lebih kecil dari bawah. |
| [offset(pos)](#offset_pos_13) | Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan. |
| [offset(x, y)](#offset_x_y_14) | Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan. |
| [round(value)](#round_value_15) | Mengonversi [RectangleF] yang ditentukan menjadi [Rectangle] dengan membulatkan nilai-nilai [RectangleF] ke nilai bulat terdekat. |
| [truncate(value)](#truncate_value_16) | Mengonversi [RectangleF] yang ditentukan menjadi [Rectangle] dengan memotong nilai-nilai [RectangleF]. |
| [union(a, b)](#union_a_b_17) | Mendapatkan struktur [Rectangle] yang berisi gabungan dari dua struktur [Rectangle]. |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Menginisialisasi instance baru dari kelas Rectangle

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Menginisialisasi instance baru dari struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) dengan lokasi dan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | Sebuah [Point] yang mewakili sudut kiri atas dari wilayah persegi panjang. |
| size | [Size](/psd/python-net/aspose.psd/size) | Sebuah [Size] yang mewakili lebar dan tinggi wilayah persegi panjang. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Menginisialisasi instance baru dari struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) dengan lokasi dan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | int | Koordinat x dari sudut kiri atas persegi panjang. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang. |
| width | int | Lebar persegi panjang. |
| tinggi | int | Tinggi persegi panjang. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Mengonversi struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan menjadi struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) dengan membulatkan nilai [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ke nilai integer berikutnya yang lebih tinggi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF] yang akan dikonversi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Mengembalikan sebuah [Rectangle]. |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Menentukan apakah titik yang ditentukan berada di dalam struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point] yang akan diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang diwakili oleh <paramref name=\"point\" /> berada di dalam struktur [Rectangle] ini; jika tidak false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Menentukan apakah wilayah persegi panjang yang direpresentasikan oleh <paramref name="rect" /> sepenuhnya berada di dalam struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle] yang akan diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika wilayah persegi panjang yang diwakili oleh <paramref name=\"rect\" /> sepenuhnya berada di dalam struktur [Rectangle] ini; jika tidak false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Menentukan apakah titik yang ditentukan berada di dalam struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | int | Koordinat x dari titik yang akan diuji. |
| y | int | Koordinat y dari titik yang akan diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang didefinisikan oleh <paramref name=\"x\" /> dan <paramref name=\"y\" /> berada di dalam struktur [Rectangle] ini; jika tidak false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_5}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Membuat struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) dengan lokasi tepi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| left | int | Koordinat x dari sudut kiri atas [Rectangle] ini. |
| top | int | Koordinat y dari sudut kiri atas [Rectangle] ini. |
| right | int | Koordinat x dari sudut kanan bawah [Rectangle] ini. |
| bottom | int | Koordinat y dari sudut kanan bawah [Rectangle] ini. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle] baru yang dibuat oleh metode ini. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_6}


```
 from_points(point1, point2) 
```

Membuat [Rectangle](/psd/python-net/aspose.psd/rectangle/) baru dari dua titik yang ditentukan. Dua sisi vertikal dari [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang dibuat akan sama dengan <paramref name="point1" /> dan <paramref name="point2" /> yang diberikan. Ini biasanya merupakan titik berlawanan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) pertama untuk persegi panjang baru. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) kedua untuk persegi panjang baru. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang baru dibuat. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_7}


```
 inflate(rect, x, y) 
```

Membuat dan mengembalikan salinan yang diperbesar dari struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang ditentukan. Salinan tersebut diperbesar sebesar jumlah yang ditentukan. Struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) asli tetap tidak berubah.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle] yang akan dijadikan awal. Persegi panjang ini tidak dimodifikasi. |
| x | int | Jumlah untuk memperbesar [Rectangle] ini secara horizontal. |
| y | int | Jumlah untuk memperbesar [Rectangle] ini secara vertikal. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle] yang diperbesar. |


### Method: inflate(size) {#inflate_size_8}


```
 inflate(size) 
```

Membesarkan [Rectangle] ini sebesar jumlah yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | Jumlah untuk memperluas persegi panjang ini. |

### Method: inflate(width, height) {#inflate_width_height_9}


```
 inflate(width, height) 
```

Membesarkan [Rectangle] ini sebesar jumlah yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| width | int | Jumlah untuk memperbesar [Rectangle] ini secara horizontal. |
| height | int | Jumlah untuk memperbesar [Rectangle] ini secara vertikal. |

### Method: intersect(a, b)  [static] {#intersect_a_b_10}


```
 intersect(a, b) 
```

Mengembalikan struktur [Rectangle] ketiga yang mewakili irisan dari dua struktur [Rectangle] lainnya. Jika tidak ada irisan, sebuah [Rectangle] kosong dikembalikan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang pertama untuk diinterseksi. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang kedua untuk diinterseksi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Sebuah [Rectangle] yang mewakili irisan antara <paramref name=\"a\" /> dan <paramref name=\"b\" />. |


### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Mengganti [Rectangle] ini dengan irisan antara dirinya sendiri dan [Rectangle] yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang akan diinterseksikan. |

### Method: intersects_with(rect) {#intersects_with_rect_12}


```
 intersects_with(rect) 
```

Menentukan apakah persegi panjang ini berpotongan dengan <paramref name="rect" />.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika ada interseksi apa pun, jika tidak false. |


### Method: offset(pos) {#offset_pos_13}


```
 offset(pos) 
```

Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pos | [Point](/psd/python-net/aspose.psd/point) | Jumlah untuk menggeser lokasi. |

### Method: offset(x, y) {#offset_x_y_14}


```
 offset(x, y) 
```

Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | int | Offset horizontal. |
| y | int | Offset vertikal. |

### Method: round(value)  [static] {#round_value_15}


```
 round(value) 
```

Mengonversi [RectangleF] yang ditentukan menjadi [Rectangle] dengan membulatkan nilai-nilai [RectangleF] ke nilai bulat terdekat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang akan dikonversi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Sebuah [Rectangle](/psd/python-net/aspose.psd/rectangle/) baru. |


### Method: truncate(value)  [static] {#truncate_value_16}


```
 truncate(value) 
```

Mengonversi [RectangleF] yang ditentukan menjadi [Rectangle] dengan memotong nilai-nilai [RectangleF].

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang akan dikonversi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Sebuah [Rectangle](/psd/python-net/aspose.psd/rectangle/) baru. |


### Method: union(a, b)  [static] {#union_a_b_17}


```
 union(a, b) 
```

Mendapatkan struktur [Rectangle] yang berisi gabungan dari dua struktur [Rectangle].

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Sebuah persegi panjang pertama untuk digabungkan. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Sebuah persegi panjang kedua untuk digabungkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Sebuah struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang membatasi gabungan dari dua struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


