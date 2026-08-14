---
title: "Kelas ArcShape"
type: docs
weight: 10
url: /id/python-net/aspose.psd.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | Menginisialisasi sebuah instance baru dari kelas [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | Menginisialisasi sebuah instance baru dari kelas [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | Menginisialisasi sebuah instance baru dari kelas [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Mendapatkan batas objek. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan pusat bentuk. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan titik akhir bentuk. |
| has_segments | bool | r | Mendapatkan nilai yang menunjukkan apakah bentuk memiliki segmen. |
| is_closed | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah bentuk terurut ditutup. Saat memproses bentuk terurut yang ditutup, titik awal dan akhir tidak memiliki arti. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan titik kiri bawah persegi panjang. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan titik kiri atas persegi panjang. |
| rectangle_height | double | r | Mendapatkan tinggi persegi panjang. |
| rectangle_width | double | r | Mendapatkan lebar persegi panjang. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan titik kanan bawah persegi panjang. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan titik kanan atas persegi panjang. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Mendapatkan segmen bentuk. |
| start_angle | float | r/w | Mendapatkan atau mengatur sudut awal. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan titik awal bentuk. |
| sweep_angle | float | r/w | Mendapatkan atau mengatur sudut sapuan. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Mendapatkan batas objek. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Mendapatkan batas objek. |
| reverse() | Membalik urutan titik untuk bentuk ini. |
| [transform(transform)](#transform_transform_3) | Menerapkan transformasi yang ditentukan ke bentuk. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

Menginisialisasi sebuah instance baru dari kelas [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

Menginisialisasi sebuah instance baru dari kelas [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Persegi panjang. |
| start_angle | float | Sudut awal. |
| sweep_angle | float | Sudut sapuan. |

### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

Menginisialisasi sebuah instance baru dari kelas [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Persegi panjang. |
| start_angle | float | Sudut awal. |
| sweep_angle | float | Sudut sapuan. |
| is_closed | bool | Jika diatur ke <c>true</c> busur ditutup. Busur yang ditutup sebenarnya menjadi elips. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


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


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Menerapkan transformasi yang ditentukan ke bentuk.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Transformasi yang akan diterapkan. |

