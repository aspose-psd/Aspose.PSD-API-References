---
title: "Kelas Pen"
type: docs
weight: 3360
url: /id/python-net/aspose.psd/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Pen

**Inheritance:** TransparencySupporter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Menginisialisasi instance baru dari kelas [Pen](/psd/python-net/aspose.psd/pen/) dengan [Pen.brush](/psd/python-net/aspose.psd/pen/) yang ditentukan. |
| [Pen(brush, width)](#Pen_brush_width_2) | Menginisialisasi instance baru dari kelas [Pen](/psd/python-net/aspose.psd/pen/) dengan [Pen.brush](/psd/python-net/aspose.psd/pen/) dan [Pen.width](/psd/python-net/aspose.psd/pen/) yang ditentukan. |
| [Pen(color)](#Pen_color_3) | Menginisialisasi instance baru dari kelas [Pen](/psd/python-net/aspose.psd/pen/) dengan warna yang ditentukan. |
| [Pen(color, width)](#Pen_color_width_4) | Menginisialisasi instance baru dari kelas [Pen](/psd/python-net/aspose.psd/pen/) dengan properti [Pen.color](/psd/python-net/aspose.psd/pen/) dan [Pen.width](/psd/python-net/aspose.psd/pen/) yang ditentukan. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/psd/python-net/aspose.psd/penalignment) | r/w | Mendapatkan atau mengatur penyelarasan untuk [Pen](/psd/python-net/aspose.psd/pen/) ini. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | r/w | Mendapatkan atau mengatur [Pen.brush](/psd/python-net/aspose.psd/pen/) yang menentukan atribut dari [Pen](/psd/python-net/aspose.psd/pen/) ini. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur warna dari [Pen](/psd/python-net/aspose.psd/pen/) ini. |
| compound_array | float | r/w | Mendapatkan atau mengatur array nilai yang menentukan pena komposit. Pena komposit menggambar garis komposit yang terdiri dari garis paralel dan ruang. |
| custom_end_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Mendapatkan atau mengatur cap khusus yang digunakan di akhir garis yang digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) ini. |
| custom_start_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Mendapatkan atau mengatur cap khusus yang digunakan di awal garis yang digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) ini. |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | r/w | Mendapatkan atau mengatur gaya cap yang digunakan di akhir garis putus-putus yang membentuk garis bergaris yang digambar dengan [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_offset | float | r/w | Mendapatkan atau mengatur jarak dari awal garis ke permulaan pola putus-putus. |
| dash_pattern | float | r/w | Mendapatkan atau mengatur array putus-putus khusus dan ruang. |
| dash_style | [DashStyle](/psd/python-net/aspose.psd/dashstyle) | r/w | Mendapatkan atau mengatur gaya yang digunakan untuk garis bergaris yang digambar dengan [Pen](/psd/python-net/aspose.psd/pen/). |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Mendapatkan atau mengatur gaya cap yang digunakan di akhir garis yang digambar dengan [Pen](/psd/python-net/aspose.psd/pen/). |
| line_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Mendapatkan atau mengatur gaya sambungan untuk ujung dua garis berurutan yang digambar dengan [Pen](/psd/python-net/aspose.psd/pen/). |
| miter_limit | float | r/w | Mendapatkan atau mengatur batas ketebalan sambungan pada sudut miter. |
| opasitas | float | r/w | Mendapatkan atau mengatur opacity objek. Nilainya harus antara 0 dan 1. Nilai 0 berarti objek sepenuhnya terlihat, nilai 1 berarti objek sepenuhnya tidak tembus. |
| pen_type | [PenType](/psd/python-net/aspose.psd/pentype) | r | Mendapatkan gaya garis yang digambar dengan [Pen](/psd/python-net/aspose.psd/pen/). |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Mendapatkan atau mengatur gaya cap yang digunakan di awal garis yang digambar dengan [Pen](/psd/python-net/aspose.psd/pen/). |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Mendapatkan atau mengatur salinan transformasi geometrik untuk [Pen](/psd/python-net/aspose.psd/pen/) ini. |
| width | float | r/w | Mendapatkan atau mengatur lebar [Pen](/psd/python-net/aspose.psd/pen/) ini, dalam satuan objek Graphics yang digunakan untuk menggambar. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [multiply_transform(matrix)](#multiply_transform_matrix_1) | Mengalikan matriks transformasi untuk [Pen](/psd/python-net/aspose.psd/pen/) ini dengan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_2) | Mengalikan matriks transformasi untuk [Pen](/psd/python-net/aspose.psd/pen/) ini dengan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan dalam urutan yang ditentukan. |
| reset_transform() | Mengatur ulang matriks transformasi geometrik untuk [Pen](/psd/python-net/aspose.psd/pen/) ini menjadi identitas. |
| [rotate_transform(angle)](#rotate_transform_angle_3) | Memutar transformasi geometrik lokal sebesar sudut yang ditentukan. Metode ini menambahkan rotasi ke depan transformasi. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_4) | Memutar transformasi geometrik lokal sebesar sudut yang ditentukan dalam urutan yang ditentukan. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_5) | Menskalakan transformasi geometris lokal dengan faktor yang ditentukan. Metode ini menambahkan matriks skala ke depan transformasi. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_6) | Menskalakan transformasi geometris lokal dengan faktor yang ditentukan dalam urutan yang ditentukan. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_7) | Mengatur nilai yang menentukan gaya cap yang digunakan untuk mengakhiri garis yang digambar oleh [Pen](/psd/python-net/aspose.psd/pen/). |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Mentranslasi transformasi geometris lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke depan transformasi. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Mentranslasi transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Menginisialisasi instance baru dari kelas [Pen](/psd/python-net/aspose.psd/pen/) dengan [Pen.brush](/psd/python-net/aspose.psd/pen/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Sebuah [Pen.brush](/psd/python-net/aspose.psd/pen/) yang menentukan properti isi dari [Pen](/psd/python-net/aspose.psd/pen/) ini. |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Menginisialisasi instance baru dari kelas [Pen](/psd/python-net/aspose.psd/pen/) dengan [Pen.brush](/psd/python-net/aspose.psd/pen/) dan [Pen.width](/psd/python-net/aspose.psd/pen/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Sebuah [Pen.brush](/psd/python-net/aspose.psd/pen/) yang menentukan karakteristik dari [Pen](/psd/python-net/aspose.psd/pen/) ini. |
| width | float | Lebar [Pen](/psd/python-net/aspose.psd/pen/) baru. |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Menginisialisasi instance baru dari kelas [Pen](/psd/python-net/aspose.psd/pen/) dengan warna yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Sebuah struktur [Pen.color](/psd/python-net/aspose.psd/pen/) yang menunjukkan warna dari [Pen](/psd/python-net/aspose.psd/pen/) ini. |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Menginisialisasi instance baru dari kelas [Pen](/psd/python-net/aspose.psd/pen/) dengan properti [Pen.color](/psd/python-net/aspose.psd/pen/) dan [Pen.width](/psd/python-net/aspose.psd/pen/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Sebuah struktur [Pen.color](/psd/python-net/aspose.psd/pen/) yang menunjukkan warna dari [Pen](/psd/python-net/aspose.psd/pen/) ini. |
| width | float | Nilai yang menunjukkan lebar dari [Pen](/psd/python-net/aspose.psd/pen/) ini. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_1}


```
 multiply_transform(matrix) 
```

Mengalikan matriks transformasi untuk [Pen](/psd/python-net/aspose.psd/pen/) ini dengan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Objek [Matrix](/psd/python-net/aspose.psd/matrix/) yang digunakan untuk mengalikan matriks transformasi. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_2}


```
 multiply_transform(matrix, order) 
```

Mengalikan matriks transformasi untuk [Pen](/psd/python-net/aspose.psd/pen/) ini dengan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/) yang digunakan untuk mengalikan matriks transformasi. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Urutan di mana operasi perkalian harus dilakukan. |

### Method: rotate_transform(angle) {#rotate_transform_angle_3}


```
 rotate_transform(angle) 
```

Memutar transformasi geometrik lokal sebesar sudut yang ditentukan. Metode ini menambahkan rotasi ke depan transformasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sudut | float | Sudut rotasi. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_4}


```
 rotate_transform(angle, order) 
```

Memutar transformasi geometrik lokal sebesar sudut yang ditentukan dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sudut | float | Sudut rotasi. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Sebuah [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) yang menentukan apakah akan menambahkan atau menyisipkan matriks rotasi. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_5}


```
 scale_transform(sx, sy) 
```

Menskalakan transformasi geometris lokal dengan faktor yang ditentukan. Metode ini menambahkan matriks skala ke depan transformasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sx | float | Faktor yang digunakan untuk menskalakan transformasi pada arah sumbu x. |
| sy | float | Faktor yang digunakan untuk menskalakan transformasi pada arah sumbu y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_6}


```
 scale_transform(sx, sy, order) 
```

Menskalakan transformasi geometris lokal dengan faktor yang ditentukan dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sx | float | Faktor yang digunakan untuk menskalakan transformasi pada arah sumbu x. |
| sy | float | Faktor yang digunakan untuk menskalakan transformasi pada arah sumbu y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Sebuah [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) yang menentukan apakah akan menambahkan atau menyisipkan matriks skala. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_7}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Mengatur nilai yang menentukan gaya cap yang digunakan untuk mengakhiri garis yang digambar oleh [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Sebuah [LineCap](/psd/python-net/aspose.psd/linecap/) yang mewakili gaya cap yang digunakan di awal garis yang digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) ini. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Sebuah [LineCap](/psd/python-net/aspose.psd/linecap/) yang mewakili gaya cap yang digunakan di akhir garis yang digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) ini. |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | Sebuah [LineCap](/psd/python-net/aspose.psd/linecap/) yang mewakili gaya cap yang digunakan di awal atau akhir garis putus-putus yang digambar dengan [Pen](/psd/python-net/aspose.psd/pen/) ini. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Mentranslasi transformasi geometris lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke depan transformasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Mentranslasi transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Urutan (menambahkan di depan atau di belakang) untuk menerapkan translasi. |

