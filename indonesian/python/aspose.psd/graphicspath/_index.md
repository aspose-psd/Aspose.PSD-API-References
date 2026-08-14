---
title: "Kelas GraphicsPath"
type: docs
weight: 1570
url: /id/python-net/aspose.psd/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Menginisialisasi instance baru dari kelas [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Menginisialisasi instance baru dari kelas [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Menginisialisasi instance baru dari kelas [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Menginisialisasi instance baru dari kelas [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Mendapatkan atau mengatur batas objek. |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | r | Mendapatkan figur jalur. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | r/w | Mendapatkan atau mengatur sebuah enumerasi [FillMode](/psd/python-net/aspose.psd/fillmode/) yang menentukan bagaimana interior bentuk dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) diisi. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Menambahkan sebuah figur baru. |
| [add_figures(figures)](#add_figures_figures_2) | Menambahkan figur-figur baru. |
| [add_path(adding_path)](#add_path_adding_path_3) | Menambahkan [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang ditentukan ke jalur ini. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Menambahkan [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang ditentukan ke jalur ini. |
| [deep_clone()](#deep_clone__5) | Melakukan kloning mendalam dari jalur grafis ini. |
| flatten() | Mengonversi setiap kurva dalam jalur ini menjadi urutan segmen garis yang terhubung. |
| [flatten(matrix)](#flatten_matrix_6) | Menerapkan transformasi yang ditentukan lalu mengonversi setiap kurva dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) menjadi urutan segmen garis yang terhubung. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Mengonversi setiap kurva dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) menjadi urutan segmen garis yang terhubung. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Mendapatkan batas objek. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Mendapatkan batas objek. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan dan menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan dan menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan dan menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan dan menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan. |
| [is_visible(point)](#is_visible_point_18) | Menunjukkan apakah titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini. |
| [is_visible(point)](#is_visible_point_19) | Menunjukkan apakah titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini. |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_20) | Menunjukkan apakah titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini. |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_21) | Menunjukkan apakah titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini. |
| [is_visible(x, y)](#is_visible_x_y_22) | Menunjukkan apakah titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini. |
| [is_visible(x, y)](#is_visible_x_y_23) | Menunjukkan apakah titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_24) | Menunjukkan apakah titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini dalam wilayah klip yang terlihat dari [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_25) | Menunjukkan apakah titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini dalam wilayah klip yang terlihat dari [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan. |
| [remove_figure(figure)](#remove_figure_figure_26) | Menghapus sebuah figur. |
| [remove_figures(figures)](#remove_figures_figures_27) | Menghapus figur-figur. |
| reset() | Mengosongkan jalur grafis dan mengatur [FillMode](/psd/python-net/aspose.psd/fillmode/) menjadi [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| reverse() | Membalik urutan figur, bentuk, dan titik dalam setiap bentuk pada [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini. |
| [transform(transform)](#transform_transform_28) | Menerapkan transformasi yang ditentukan ke bentuk. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_29) | Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan sebuah paralelogram, ke [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini. |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_30) | Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan sebuah paralelogram, ke [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini. |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_31) | Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan sebuah paralelogram, ke [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini. |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_32) | Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan sebuah paralelogram, ke [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini. |
| [widen(pen)](#widen_pen_33) | Menambahkan kontur tambahan ke jalur. |
| [widen(pen, matrix)](#widen_pen_matrix_34) | Menambahkan kontur tambahan ke [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_35) | Mengganti [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini dengan kurva yang melingkupi area yang diisi ketika jalur ini digambar dengan pen yang ditentukan. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Menginisialisasi instance baru dari kelas [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Menginisialisasi instance baru dari kelas [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Figur-figur untuk diinisialisasi dari. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Menginisialisasi instance baru dari kelas [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Figur-figur untuk diinisialisasi dari. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Mode pengisian. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Menginisialisasi instance baru dari kelas [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Mode pengisian. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Menambahkan sebuah figur baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | Figur yang akan ditambahkan. |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Menambahkan figur-figur baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Figur-figur yang akan ditambahkan. |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Menambahkan [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang ditentukan ke jalur ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang akan ditambahkan. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Menambahkan [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang ditentukan ke jalur ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang akan ditambahkan. |
| sambungkan | bool | Nilai Boolean yang menentukan apakah gambar pertama dalam jalur yang ditambahkan merupakan bagian dari gambar terakhir dalam jalur ini. Nilai true menunjukkan bahwa gambar pertama dalam jalur yang ditambahkan merupakan bagian dari gambar terakhir dalam jalur ini. Nilai false menunjukkan bahwa gambar pertama dalam jalur yang ditambahkan terpisah dari gambar terakhir dalam jalur ini. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Melakukan kloning mendalam dari jalur grafis ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Salinan dalam dari jalur grafik. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Menerapkan transformasi yang ditentukan lalu mengonversi setiap kurva dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) menjadi urutan segmen garis yang terhubung.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Sebuah [Matrix](/psd/python-net/aspose.psd/matrix/) yang digunakan untuk mentransformasi [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini sebelum diratakan. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Mengonversi setiap kurva dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) menjadi urutan segmen garis yang terhubung.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Sebuah [Matrix](/psd/python-net/aspose.psd/matrix/) yang digunakan untuk mentransformasi [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini sebelum diratakan. |
| kelengkungan | float | Menentukan kesalahan maksimum yang diizinkan antara kurva dan pendekatan yang diratakan. Nilai default adalah 0,25. Mengurangi nilai kelengkungan akan meningkatkan jumlah segmen garis dalam pendekatan. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

Mendapatkan batas objek.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Matriks yang akan diterapkan sebelum batas akan dihitung. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Batas objek yang diperkirakan. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

Mendapatkan batas objek.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Matriks yang akan diterapkan sebelum batas akan dihitung. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Pen yang digunakan untuk objek. Ini dapat memengaruhi ukuran batas objek. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Batas objek yang diperkirakan. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Sebuah [PointF](/psd/python-net/aspose.psd/pointf/) yang menentukan lokasi untuk diuji. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) untuk diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang ditentukan berada di dalam kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan; jika tidak, false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Sebuah [PointF](/psd/python-net/aspose.psd/pointf/) yang menentukan lokasi untuk diuji. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) untuk diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang ditentukan berada di dalam kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan; jika tidak, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan dan menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Sebuah [PointF](/psd/python-net/aspose.psd/pointf/) yang menentukan lokasi untuk diuji. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) untuk diuji. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | [Graphics](/psd/python-net/aspose.psd/graphics/) untuk menguji visibilitas. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan; jika tidak, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan dan menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Sebuah [PointF](/psd/python-net/aspose.psd/pointf/) yang menentukan lokasi untuk diuji. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) untuk diuji. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | [Graphics](/psd/python-net/aspose.psd/graphics/) untuk menguji visibilitas. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan; jika tidak, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) untuk diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang ditentukan berada di dalam kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan; jika tidak, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | int | Koordinat x dari titik yang akan diuji. |
| y | int | Koordinat y dari titik yang akan diuji. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) untuk diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang ditentukan berada di dalam kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan; jika tidak, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan dan menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) untuk diuji. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | [Graphics](/psd/python-net/aspose.psd/graphics/) untuk menguji visibilitas. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan; jika tidak, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan dan menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | int | Koordinat x dari titik yang akan diuji. |
| y | int | Koordinat y dari titik yang akan diuji. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) untuk diuji. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | [Graphics](/psd/python-net/aspose.psd/graphics/) untuk menguji visibilitas. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang ditentukan berada di dalam (di bawah) kontur [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ketika digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) yang ditentukan; jika tidak, false. |


### Method: is_visible(point) {#is_visible_point_18}


```
 is_visible(point) 
```

Menunjukkan apakah titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Sebuah [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik untuk diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); jika tidak, false. |


### Method: is_visible(point) {#is_visible_point_19}


```
 is_visible(point) 
```

Menunjukkan apakah titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Sebuah [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik untuk diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); jika tidak, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_20}


```
 is_visible(pt, graphics) 
```

Menunjukkan apakah titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Sebuah [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik untuk diuji. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | [Graphics](/psd/python-net/aspose.psd/graphics/) untuk menguji visibilitas. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang ditentukan berada di dalam ini; jika tidak, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_21}


```
 is_visible(pt, graphics) 
```

Menunjukkan apakah titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Sebuah [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik untuk diuji. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | [Graphics](/psd/python-net/aspose.psd/graphics/) untuk menguji visibilitas. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang ditentukan berada di dalam ini; jika tidak, false. |


### Method: is_visible(x, y) {#is_visible_x_y_22}


```
 is_visible(x, y) 
```

Menunjukkan apakah titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); jika tidak, false. |


### Method: is_visible(x, y) {#is_visible_x_y_23}


```
 is_visible(x, y) 
```

Menunjukkan apakah titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | int | Koordinat x dari titik yang akan diuji. |
| y | int | Koordinat y dari titik yang akan diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); jika tidak, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_24}


```
 is_visible(x, y, graphics) 
```

Menunjukkan apakah titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini dalam wilayah klip yang terlihat dari [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | [Graphics](/psd/python-net/aspose.psd/graphics/) untuk menguji visibilitas. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); jika tidak, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_25}


```
 is_visible(x, y, graphics) 
```

Menunjukkan apakah titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini dalam wilayah klip yang terlihat dari [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | int | Koordinat x dari titik yang akan diuji. |
| y | int | Koordinat y dari titik yang akan diuji. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | [Graphics](/psd/python-net/aspose.psd/graphics/) untuk menguji visibilitas. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Metode ini mengembalikan true jika titik yang ditentukan berada di dalam [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); jika tidak, false. |


### Method: remove_figure(figure) {#remove_figure_figure_26}


```
 remove_figure(figure) 
```

Menghapus sebuah figur.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | Gambar yang akan dihapus. |

### Method: remove_figures(figures) {#remove_figures_figures_27}


```
 remove_figures(figures) 
```

Menghapus figur-figur.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Gambar-gambar yang akan dihapus. |

### Method: transform(transform) {#transform_transform_28}


```
 transform(transform) 
```

Menerapkan transformasi yang ditentukan ke bentuk.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Transformasi yang akan diterapkan. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_29}


```
 warp(dest_points, src_rect) 
```

Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan sebuah paralelogram, ke [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan sebuah paralelogram tempat persegi panjang yang didefinisikan oleh <paramref name=\"srcRect\" /> ditransformasikan. Array dapat berisi tiga atau empat elemen. Jika array berisi tiga elemen, sudut kanan-bawah paralelogram diasumsikan dari tiga titik pertama. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Sebuah [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang yang ditransformasikan menjadi paralelogram yang didefinisikan oleh <paramref name=\"destPoints\" />. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_30}


```
 warp(dest_points, src_rect, matrix) 
```

Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan sebuah paralelogram, ke [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan sebuah paralelogram tempat persegi panjang yang didefinisikan oleh <paramref name=\"srcRect\" /> ditransformasikan. Array dapat berisi tiga atau empat elemen. Jika array berisi tiga elemen, sudut kanan-bawah paralelogram diasumsikan dari tiga titik pertama. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Sebuah [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang yang ditransformasikan menjadi paralelogram yang didefinisikan oleh <paramref name=\"destPoints\" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Sebuah [Matrix](/psd/python-net/aspose.psd/matrix/) yang menentukan transformasi geometrik yang diterapkan pada jalur. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_31}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan sebuah paralelogram, ke [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan sebuah paralelogram tempat persegi panjang yang didefinisikan oleh <paramref name=\"srcRect\" /> ditransformasikan. Array dapat berisi tiga atau empat elemen. Jika array berisi tiga elemen, sudut kanan-bawah paralelogram diasumsikan dari tiga titik pertama. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Sebuah [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang yang ditransformasikan menjadi paralelogram yang didefinisikan oleh <paramref name=\"destPoints\" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Sebuah [Matrix](/psd/python-net/aspose.psd/matrix/) yang menentukan transformasi geometrik yang diterapkan pada jalur. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Enum [WarpMode](/psd/python-net/aspose.psd/warpmode/) yang menentukan apakah operasi warp ini menggunakan mode perspektif atau bilinear. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_32}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan sebuah paralelogram, ke [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan sebuah paralelogram tempat persegi panjang yang didefinisikan oleh <paramref name=\"srcRect\" /> ditransformasikan. Array dapat berisi tiga atau empat elemen. Jika array berisi tiga elemen, sudut kanan-bawah paralelogram diasumsikan dari tiga titik pertama. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Sebuah [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang yang ditransformasikan menjadi paralelogram yang didefinisikan oleh <paramref name=\"destPoints\" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Sebuah [Matrix](/psd/python-net/aspose.psd/matrix/) yang menentukan transformasi geometrik yang diterapkan pada jalur. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Enum [WarpMode](/psd/python-net/aspose.psd/warpmode/) yang menentukan apakah operasi warp ini menggunakan mode perspektif atau bilinear. |
| flatness | float | Nilai antara 0 hingga 1 yang menentukan seberapa datar jalur yang dihasilkan. Untuk informasi lebih lanjut, lihat metode [GraphicsPath.flatten()](/psd/python-net/aspose.psd/graphicspath/). |

### Method: widen(pen) {#widen_pen_33}


```
 widen(pen) 
```

Menambahkan kontur tambahan ke jalur.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan lebar antara kontur asli jalur dan kontur baru yang dibuat oleh metode ini. |

### Method: widen(pen, matrix) {#widen_pen_matrix_34}


```
 widen(pen, matrix) 
```

Menambahkan kontur tambahan ke [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan lebar antara kontur asli jalur dan kontur baru yang dibuat oleh metode ini. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Sebuah [Matrix](/psd/python-net/aspose.psd/matrix/) yang menentukan transformasi yang diterapkan pada jalur sebelum diperlebar. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_35}


```
 widen(pen, matrix, flatness) 
```

Mengganti [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ini dengan kurva yang melingkupi area yang diisi ketika jalur ini digambar dengan pen yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan lebar antara kontur asli jalur dan kontur baru yang dibuat oleh metode ini. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Sebuah [Matrix](/psd/python-net/aspose.psd/matrix/) yang menentukan transformasi yang diterapkan pada jalur sebelum diperlebar. |
| kelengkungan | float | Nilai yang menentukan kelengkungan untuk kurva. |

