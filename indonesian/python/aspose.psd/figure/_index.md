---
title: "Kelas Figure"
type: docs
weight: 1220
url: /id/python-net/aspose.psd/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Figure

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Figure()](#Figure__1) | Menginisialisasi instance baru dari kelas Figure. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Mendapatkan atau mengatur batas objek. |
| is_closed | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar ini tertutup. Gambar tertutup hanya akan berpengaruh bila<br/>            bentuk pertama dan terakhir dari gambar merupakan bentuk kontinu. Dalam kasus tersebut titik pertama dari bentuk pertama akan<br/>            terhubung dengan garis lurus dari titik terakhir bentuk terakhir. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Mendapatkan semua segmen gambar. |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | r | Mendapatkan bentuk-bentuk gambar. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Menambahkan sebuah bentuk ke gambar. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Menambahkan rentang bentuk ke gambar. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Mendapatkan batas objek. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Mendapatkan batas objek. |
| [remove_shape(shape)](#remove_shape_shape_5) | Menghapus sebuah bentuk dari gambar. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Menghapus rentang bentuk dari gambar. |
| reverse() | Membalik urutan bentuk gambar ini dan urutan titik bentuk. |
| [transform(transform)](#transform_transform_7) | Menerapkan transformasi yang ditentukan ke bentuk. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Menginisialisasi instance baru dari kelas Figure.

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Menambahkan sebuah bentuk ke gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | Bentuk yang akan ditambahkan. |

### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Menambahkan rentang bentuk ke gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | Bentuk-bentuk yang akan ditambahkan. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Menghapus sebuah bentuk dari gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | Bentuk yang akan dihapus. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Menghapus rentang bentuk dari gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | Rentang bentuk yang akan dihapus. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

Menerapkan transformasi yang ditentukan ke bentuk.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Transformasi yang akan diterapkan. |

