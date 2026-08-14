---
title: "Kelas BezierShape"
type: docs
weight: 20
url: /id/python-net/aspose.psd.shapes/beziershape/
---

**Summary:** Represents a bezier spline.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.BezierShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [BezierShape()](#BezierShape__1) | Menginisialisasi sebuah instance baru dari kelas [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/). |
| [BezierShape(points)](#BezierShape_points_2) | Menginisialisasi sebuah instance baru dari kelas [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/). |
| [BezierShape(points, is_closed)](#BezierShape_points_is_closed_3) | Menginisialisasi sebuah instance baru dari kelas [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Mendapatkan batas objek. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan pusat bentuk. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan titik akhir bentuk. |
| has_segments | bool | r | Mendapatkan nilai yang menunjukkan apakah bentuk memiliki segmen. |
| is_closed | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah bentuk tertutup. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | Mendapatkan atau mengatur titik kurva. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Mendapatkan segmen bentuk. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan titik awal bentuk. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Mendapatkan batas objek. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Mendapatkan batas objek. |
| reverse() | Membalik urutan titik untuk bentuk ini. |
| [transform(transform)](#transform_transform_3) | Menerapkan transformasi yang ditentukan ke bentuk. |


### Constructor: BezierShape() {#BezierShape__1}


```
 BezierShape() 
```

Menginisialisasi sebuah instance baru dari kelas [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/).

### Constructor: BezierShape(points) {#BezierShape_points_2}


```
 BezierShape(points) 
```

Menginisialisasi sebuah instance baru dari kelas [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array titik. |

### Constructor: BezierShape(points, is_closed) {#BezierShape_points_is_closed_3}


```
 BezierShape(points, is_closed) 
```

Menginisialisasi sebuah instance baru dari kelas [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array titik. |
| is_closed | bool | Jika diatur ke <c>true</c> spline bezier ditutup. |

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

