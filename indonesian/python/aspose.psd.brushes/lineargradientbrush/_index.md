---
title: "Kelas LinearGradientBrush"
type: docs
weight: 20
url: /id/python-net/aspose.psd.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | Menginisialisasi instance baru dari kelas [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) dengan parameter default.<br/>            Warna awal adalah hitam, warna akhir adalah putih, sudutnya 45 derajat dan persegi panjang berada di (0,0) dengan ukuran (1,1). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | Menginisialisasi instance baru dari kelas [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) dengan titik dan warna yang ditentukan. |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | Menginisialisasi instance baru dari kelas [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) dengan titik dan warna yang ditentukan. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | Menginisialisasi instance baru dari kelas [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | Menginisialisasi instance baru dari kelas [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | Menginisialisasi instance baru dari kelas [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | Menginisialisasi instance baru dari kelas [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| sudut | float | r/w | Mendapatkan atau mengatur sudut gradien. |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Mendapatkan atau mengatur sebuah [Blend](/psd/python-net/aspose.psd/blend/) yang menentukan posisi dan faktor yang mendefinisikan penurunan khusus untuk gradien. |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| end_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur warna gradien akhir. |
| gamma_correction | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah koreksi gamma diaktifkan untuk [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) ini. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Mendapatkan atau mengatur [ColorBlend](/psd/python-net/aspose.psd/colorblend/) yang mendefinisikan gradien linear multicolor. |
| is_angle_scalable | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) berubah selama transformasi dengan [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) ini. |
| is_transform_changed | bool | r | Mendapatkan nilai yang menunjukkan apakah transformasi telah diubah dengan cara tertentu. Misalnya mengatur matriks transformasi atau<br/>            memanggil salah satu metode yang mengubah matriks transformasi. Properti ini diperkenalkan untuk kompatibilitas mundur dengan GDI+. |
| linear_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur warna awal dan akhir gradien. |
| opasitas | float | r/w | Mendapatkan atau mengatur opasitas kuas. Nilainya harus antara 0 dan 1. Nilai 0 berarti kuas sepenuhnya terlihat, nilai 1 berarti kuas sepenuhnya tidak tembus pandang. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | Mendapatkan atau mengatur wilayah persegi panjang yang mendefinisikan titik awal dan akhir gradien. |
| start_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur warna gradien awal. |
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
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Membuat gradien linear dengan warna tengah dan penurunan linear ke satu warna di kedua ujung. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Membuat gradien linear dengan warna tengah dan penurunan linear ke satu warna di kedua ujung. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Membuat penurunan gradien berdasarkan kurva berbentuk lonceng. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Membuat penurunan gradien berdasarkan kurva berbentuk lonceng. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke transformasi. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

Menginisialisasi instance baru dari kelas [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) dengan parameter default.<br/>            Warna awal adalah hitam, warna akhir adalah putih, sudutnya 45 derajat dan persegi panjang berada di (0,0) dengan ukuran (1,1).

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Menginisialisasi instance baru dari kelas [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) dengan titik dan warna yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Sebuah struktur [Point](/psd/python-net/aspose.psd/point/) yang mewakili titik awal gradien linier. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Sebuah struktur [Point](/psd/python-net/aspose.psd/point/) yang mewakili titik akhir gradien linier. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Sebuah struktur [Color](/psd/python-net/aspose.psd/color/) yang mewakili warna awal dari gradien linear. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Sebuah struktur [Color](/psd/python-net/aspose.psd/color/) yang mewakili warna akhir dari gradien linear. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Menginisialisasi instance baru dari kelas [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) dengan titik dan warna yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Sebuah struktur [Point](/psd/python-net/aspose.psd/point/) yang mewakili titik awal gradien linier. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Sebuah struktur [Point](/psd/python-net/aspose.psd/point/) yang mewakili titik akhir gradien linier. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Sebuah struktur [Color](/psd/python-net/aspose.psd/color/) yang mewakili warna awal dari gradien linear. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Sebuah struktur [Color](/psd/python-net/aspose.psd/color/) yang mewakili warna akhir dari gradien linear. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Menginisialisasi instance baru dari kelas [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Sebuah struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang menentukan batas gradien linier. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Sebuah struktur [Color](/psd/python-net/aspose.psd/color/) yang mewakili warna awal untuk gradien. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Sebuah struktur [Color](/psd/python-net/aspose.psd/color/) yang mewakili warna akhir untuk gradien. |
| sudut | float | Sudut, diukur dalam derajat searah jarum jam dari sumbu x, dari garis orientasi gradien. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Menginisialisasi instance baru dari kelas [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Sebuah struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang menentukan batas gradien linier. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Sebuah struktur [Color](/psd/python-net/aspose.psd/color/) yang mewakili warna awal untuk gradien. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Sebuah struktur [Color](/psd/python-net/aspose.psd/color/) yang mewakili warna akhir untuk gradien. |
| sudut | float | Sudut, diukur dalam derajat searah jarum jam dari sumbu x, dari garis orientasi gradien. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Menginisialisasi instance baru dari kelas [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Sebuah struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang menentukan batas gradien linier. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Sebuah struktur [Color](/psd/python-net/aspose.psd/color/) yang mewakili warna awal untuk gradien. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Sebuah struktur [Color](/psd/python-net/aspose.psd/color/) yang mewakili warna akhir untuk gradien. |
| sudut | float | Sudut, diukur dalam derajat searah jarum jam dari sumbu x, dari garis orientasi gradien. |
| is_angle_scalable | bool | Jika disetel ke <c>true</c> sudut akan berubah selama transformasi dengan [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) ini. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Menginisialisasi instance baru dari kelas [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Sebuah struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang menentukan batas gradien linier. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Sebuah struktur [Color](/psd/python-net/aspose.psd/color/) yang mewakili warna awal untuk gradien. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Sebuah struktur [Color](/psd/python-net/aspose.psd/color/) yang mewakili warna akhir untuk gradien. |
| sudut | float | Sudut, diukur dalam derajat searah jarum jam dari sumbu x, dari garis orientasi gradien. |
| is_angle_scalable | bool | Jika disetel ke <c>true</c> sudut akan berubah selama transformasi dengan [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) ini. |

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

Membuat gradien linear dengan warna tengah dan penurunan linear ke satu warna di kedua ujung.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fokus | float | Nilai dari 0 hingga 1 yang menentukan pusat gradien (titik di mana gradien hanya terdiri dari warna akhir). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Membuat gradien linear dengan warna tengah dan penurunan linear ke satu warna di kedua ujung.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fokus | float | Nilai dari 0 hingga 1 yang menentukan pusat gradien (titik di mana gradien hanya terdiri dari warna akhir). |
| scale | float | Nilai dari 0 hingga1 yang menentukan seberapa cepat warna berkurang dari warna awal ke <paramref name="focus" /> (warna akhir) |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Membuat penurunan gradien berdasarkan kurva berbentuk lonceng.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fokus | float | Nilai dari 0 hingga 1 yang menentukan pusat gradien (titik di mana warna awal dan warna akhir tercampur secara merata). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Membuat penurunan gradien berdasarkan kurva berbentuk lonceng.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fokus | float | Nilai dari 0 hingga 1 yang menentukan pusat gradien (titik di mana gradien hanya terdiri dari warna akhir). |
| scale | float | Nilai dari 0 hingga 1 yang menentukan seberapa cepat warna berkurang dari <paramref name="focus" />. |

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

