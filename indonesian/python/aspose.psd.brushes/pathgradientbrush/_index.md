---
title: "Kelas PathGradientBrush"
type: docs
weight: 50
url: /id/python-net/aspose.psd.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | Menginisialisasi instance baru dari kelas [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) dengan jalur yang ditentukan. |
| [PathGradientBrush(points)](#PathGradientBrush_points_2) | Menginisialisasi instance baru dari kelas [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) dengan titik-titik yang ditentukan. |
| [PathGradientBrush(points)](#PathGradientBrush_points_3) | Menginisialisasi instance baru dari kelas [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) dengan titik-titik yang ditentukan. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_4) | Menginisialisasi instance baru dari kelas [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) dengan titik-titik dan mode pembungkus yang ditentukan. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_5) | Menginisialisasi instance baru dari kelas [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) dengan titik-titik dan mode pembungkus yang ditentukan. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Mendapatkan atau mengatur sebuah [Blend](/psd/python-net/aspose.psd/blend/) yang menentukan posisi dan faktor yang mendefinisikan penurunan khusus untuk gradien. |
| center_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur warna di pusat gradien jalur. |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Mendapatkan atau mengatur titik pusat gradien jalur. |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Mendapatkan atau mengatur titik fokus untuk penurunan gradien. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | Mendapatkan jalur grafis yang menjadi dasar kuas ini. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Mendapatkan atau mengatur [ColorBlend](/psd/python-net/aspose.psd/colorblend/) yang mendefinisikan gradien linear multicolor. |
| is_transform_changed | bool | r | Mendapatkan nilai yang menunjukkan apakah transformasi telah diubah dengan cara tertentu. Misalnya mengatur matriks transformasi atau<br/>            memanggil salah satu metode yang mengubah matriks transformasi. Properti ini diperkenalkan untuk kompatibilitas mundur dengan GDI+. |
| opasitas | float | r/w | Mendapatkan atau mengatur opasitas kuas. Nilainya harus antara 0 dan 1. Nilai 0 berarti kuas sepenuhnya terlihat, nilai 1 berarti kuas sepenuhnya tidak tembus pandang. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan titik-titik jalur yang menjadi dasar kuas ini. |
| surround_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur array warna yang sesuai dengan titik-titik pada jalur yang diisi oleh [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) ini. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Mendapatkan atau mengatur salinan [Matrix](/psd/python-net/aspose.psd/matrix/) yang mendefinisikan transformasi geometris lokal untuk [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Mendapatkan atau mengatur enumerasi [WrapMode](/psd/python-net/aspose.psd/wrapmode/) yang menunjukkan mode pembungkus untuk [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Membuat klon dalam baru dari [Brush](/psd/python-net/aspose.psd/brush/) saat ini. |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Mengalikan [Matrix](/psd/python-net/aspose.psd/matrix/) yang mewakili transformasi geometris lokal dari [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) dengan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan dengan menambahkan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan di depan. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Mengalikan [Matrix](/psd/python-net/aspose.psd/matrix/) yang mewakili transformasi geometris lokal dari [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) dengan [Matrix](/psd/python-net/aspose.psd/matrix/) dalam urutan yang ditentukan. |
| reset_transform() | Mengatur ulang properti [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) menjadi identitas. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Memutar transformasi geometrik lokal sebesar jumlah yang ditentukan. Metode ini menambahkan rotasi ke transformasi. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Memutar transformasi geometrik lokal sebesar jumlah yang ditentukan dalam urutan yang ditentukan. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Menskalakan transformasi geometrik lokal dengan nilai yang ditentukan. Metode ini menambahkan matriks skala ke transformasi. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Menskalakan transformasi geometrik lokal dengan nilai yang ditentukan dalam urutan yang ditentukan. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Membuat gradien dengan warna pusat dan penurunan linear ke satu warna di sekitarnya. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Membuat gradien dengan warna pusat dan penurunan linear ke setiap warna di sekitarnya. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Membuat kuas gradien yang mengubah warna mulai dari pusat jalur ke luar hingga batas jalur. Transisi dari satu warna ke warna lain didasarkan pada kurva berbentuk lonceng. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Membuat kuas gradien yang mengubah warna mulai dari pusat jalur ke luar hingga batas jalur. Transisi dari satu warna ke warna lain didasarkan pada kurva berbentuk lonceng. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke transformasi. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

Menginisialisasi instance baru dari kelas [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) dengan jalur yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang mendefinisikan area yang diisi oleh [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) ini. |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_2}


```
 PathGradientBrush(points) 
```

Menginisialisasi instance baru dari kelas [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) dengan titik-titik yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik-titik yang membentuk simpul-simpul jalur. |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_3}


```
 PathGradientBrush(points) 
```

Menginisialisasi instance baru dari kelas [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) dengan titik-titik yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik-titik yang membentuk simpul-simpul jalur. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_4}


```
 PathGradientBrush(points, wrap_mode) 
```

Menginisialisasi instance baru dari kelas [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) dengan titik-titik dan mode pembungkus yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik-titik yang membentuk simpul-simpul jalur. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | [WrapMode](/psd/python-net/aspose.psd/wrapmode/) yang menentukan bagaimana isian yang digambar dengan [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) ditata ubin. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_5}


```
 PathGradientBrush(points, wrap_mode) 
```

Menginisialisasi instance baru dari kelas [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) dengan titik-titik dan mode pembungkus yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik-titik yang membentuk simpul-simpul jalur. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | [WrapMode](/psd/python-net/aspose.psd/wrapmode/) yang menentukan bagaimana isian yang digambar dengan [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) ditata ubin. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Membuat klon dalam baru dari [Brush](/psd/python-net/aspose.psd/brush/) saat ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | Sebuah [Brush](/psd/python-net/aspose.psd/brush/) baru yang merupakan klon mendalam dari instance [Brush](/psd/python-net/aspose.psd/brush/) ini. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Mengalikan [Matrix](/psd/python-net/aspose.psd/matrix/) yang mewakili transformasi geometris lokal dari [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) dengan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan dengan menambahkan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan di depan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/) yang digunakan untuk mengalikan transformasi geometrik. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Mengalikan [Matrix](/psd/python-net/aspose.psd/matrix/) yang mewakili transformasi geometris lokal dari [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) dengan [Matrix](/psd/python-net/aspose.psd/matrix/) dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/) yang digunakan untuk mengalikan transformasi geometrik. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Sebuah [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) yang menentukan urutan pengalian kedua matriks. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Memutar transformasi geometrik lokal sebesar jumlah yang ditentukan. Metode ini menambahkan rotasi ke transformasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sudut | float | Sudut rotasi. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Memutar transformasi geometrik lokal sebesar jumlah yang ditentukan dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sudut | float | Sudut rotasi. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Sebuah [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) yang menentukan apakah akan menambahkan atau menyisipkan matriks rotasi. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Menskalakan transformasi geometrik lokal dengan nilai yang ditentukan. Metode ini menambahkan matriks skala ke transformasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sx | float | Jumlah skala yang diterapkan pada transformasi dalam arah sumbu x. |
| sy | float | Jumlah skala yang diterapkan pada transformasi dalam arah sumbu y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Menskalakan transformasi geometrik lokal dengan nilai yang ditentukan dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sx | float | Jumlah skala yang diterapkan pada transformasi dalam arah sumbu x. |
| sy | float | Jumlah skala yang diterapkan pada transformasi dalam arah sumbu y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Sebuah [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) yang menentukan apakah akan menambahkan atau menyisipkan matriks skala. |

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_8}


```
 set_blend_triangular_shape(focus) 
```

Membuat gradien dengan warna pusat dan penurunan linear ke satu warna di sekitarnya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fokus | float | Nilai dari 0 hingga 1 yang menentukan di mana, sepanjang radial apa pun dari pusat jalur ke batas jalur, warna pusat akan berada pada intensitas tertinggi. Nilai 1 (default) menempatkan intensitas tertinggi di pusat jalur. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Membuat gradien dengan warna pusat dan penurunan linear ke setiap warna di sekitarnya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fokus | float | Nilai dari 0 hingga 1 yang menentukan di mana, sepanjang radial apa pun dari pusat jalur ke batas jalur, warna pusat akan berada pada intensitas tertinggi. Nilai 1 (default) menempatkan intensitas tertinggi di pusat jalur. |
| scale | float | Nilai dari 0 hingga 1 yang menentukan intensitas maksimum warna pusat yang dicampur dengan warna batas. Nilai 1 menghasilkan intensitas tertinggi yang mungkin dari warna pusat, dan itu adalah nilai default. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Membuat kuas gradien yang mengubah warna mulai dari pusat jalur ke luar hingga batas jalur. Transisi dari satu warna ke warna lain didasarkan pada kurva berbentuk lonceng.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fokus | float | Nilai dari 0 hingga 1 yang menentukan di mana, sepanjang radial apa pun dari pusat jalur ke batas jalur, warna pusat akan berada pada intensitas tertinggi. Nilai 1 (default) menempatkan intensitas tertinggi di pusat jalur. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Membuat kuas gradien yang mengubah warna mulai dari pusat jalur ke luar hingga batas jalur. Transisi dari satu warna ke warna lain didasarkan pada kurva berbentuk lonceng.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fokus | float | Nilai dari 0 hingga 1 yang menentukan di mana, sepanjang radial apa pun dari pusat jalur ke batas jalur, warna pusat akan berada pada intensitas tertinggi. Nilai 1 (default) menempatkan intensitas tertinggi di pusat jalur. |
| scale | float | Nilai dari 0 hingga 1 yang menentukan intensitas maksimum warna pusat yang dicampur dengan warna batas. Nilai 1 menghasilkan intensitas tertinggi yang mungkin dari warna pusat, dan itu adalah nilai default. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke transformasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Urutan (menambahkan di depan atau di belakang) untuk menerapkan translasi. |

